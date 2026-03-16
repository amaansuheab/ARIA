# ARIA — Document Intelligence & RAG Test Harness

A fully browser-based RAG (Retrieval-Augmented Generation) platform. No backend, no server, no installation. Just open the HTML files in any browser.

---

## Files

| File | Purpose |
|------|---------|
| `aria-financial-risk.html` | Full document upload platform — upload PDFs, DOCX, TXT files and chat with them using dual RAG |
| `rag-test-harness.html` | Chunking strategy explorer and retrieval quality tester |
| `README.md` | This file |

---

## How to Run

1. Download both `.html` files
2. Open either file directly in Chrome, Edge, or Firefox
3. No install, no npm, no Python, no server needed

---

## Adding Your Own API Key (to enable LLM answers)

By default the harness runs **without any API calls** — all chunking, scoring, and metrics are pure JavaScript.

To enable actual Claude answers, open `rag-test-harness.html` in a text editor and find this section near the bottom of the `<script>` tag:

```js
const resp = await fetch('https://api.anthropic.com/v1/messages', {
  method: 'POST',
  headers: {
    'Content-Type': 'application/json',
    // 'x-api-key': 'YOUR_KEY_HERE',   <-- uncomment and paste your key
  },
  ...
})
```

Uncomment the `x-api-key` line and replace `YOUR_KEY_HERE` with your Anthropic API key.

**Get an API key at:** https://console.anthropic.com

> ⚠️ Never commit your API key to Git or share the HTML file with it pasted in. Use environment variables or a backend proxy for production.

---

## How to Test RAG Accuracy

### Step 1 — Open the Chunk Explorer tab

Paste your document into the left panel. The system immediately splits it into chunks using your chosen strategy and displays them as pills.

**Green-bordered pills = top 3 chunks retrieved for your query.**

Watch what gets highlighted as you change the query — this tells you exactly what the retriever would inject into the LLM.

### Step 2 — Check the Retrieval Metrics

Four metrics are shown after every query:

| Metric | What it means | Good value |
|--------|--------------|------------|
| **Token hit rate** | % of your query's keywords found in the top-3 chunks | > 70% |
| **Retrieval precision** | % of top chunks that scored above 30% relevance | > 60% |
| **Chunk granularity** | How small/precise the chunks are (smaller = better for specific queries) | > 60% |
| **Coverage** | How many chunks the doc was split into | depends on doc size |

**If token hit rate is low** → your chunks are too large, or the query uses different vocabulary than the document. Switch chunking strategy or rephrase.

**If retrieval precision is low** → the retriever is pulling irrelevant chunks. Try a finer chunking strategy (line/bullet instead of paragraph).

### Step 3 — Compare Strategies

Go to the **Strategy Comparison** tab. Enter your query and click **Compare all**.

The tool runs all four chunking strategies against the same query and ranks them by token hit rate. Use this to pick the right strategy for your document type:

| Strategy | Best for |
|----------|---------|
| **Line / bullet** | Resumes, CVs, lists, structured docs |
| **Sentence** | Dense prose, research papers, articles |
| **Paragraph** | Reports, policies, narrative documents |
| **Sliding window** | Long documents with no clear structure |

### Step 4 — Interpret Results

After running a query the RAG panel shows **TF-IDF %** and **Semantic %** per chunk separately:

- **TF-IDF dominant (blue)** — match was driven by exact keyword overlap
- **Semantic dominant (purple)** — match was driven by conceptual/bigram similarity

If only one method is doing all the work, your chunks may be too short (semantic wins) or your query too literal (TF-IDF wins). The combined 55/45 weighting handles most cases.

---

## Understanding the Dual RAG Engine

```
Query
  │
  ├─► TF-IDF scoring  (keyword frequency × inverse doc frequency)  × 0.55
  │
  └─► Semantic scoring (token overlap + bigram co-occurrence)       × 0.45
           │
           └─► Normalize both → weighted sum → rank chunks → top-k
```

Both scores are normalized to 0–1 before combining, so neither method can dominate purely by scale.

---

## Common Problems & Fixes

**"It retrieved the entire section instead of one bullet"**
→ Switch from Sliding window or Paragraph to **Line / bullet** strategy. This splits each bullet into its own chunk prefixed with its section header.

**"General questions like 'what is this doc about' return nothing"**
→ General queries have no specific keywords to match. The ARIA platform handles this with intent detection — it bypasses RAG for overview queries and uses the document summary layer instead.

**"The answer mentions things not in the document"**
→ Faithfulness is low — the LLM is hallucinating. Inject more chunks (increase top-k) or make your context prompt stricter: add *"Answer ONLY from the excerpts below. If the answer is not present, say so."*

**"Scores are all 0%"**
→ All query terms are in the stopword list. Use more specific/technical terms from your document.

---

## Production Deployment Notes

If you want to deploy this as a real web app:

1. **Never expose your API key in frontend code** — move the `fetch` call to a backend (Node.js, Python Flask, etc.)
2. **Add a vector store** (Pinecone, Chroma, pgvector) for large document sets — TF-IDF doesn't scale past ~500 chunks efficiently
3. **Replace TF-IDF with embeddings** (e.g. `text-embedding-3-small`) for true semantic search
4. **Add re-ranking** — a second-pass model that re-scores the top-k chunks before injecting into the LLM

The current pure-JS implementation is intentionally simple for learning and testing. It works well for documents up to ~50 pages.

---

## Tech Stack

- **Zero dependencies** — pure HTML + CSS + JavaScript
- **PDF parsing** — PDF.js (cdnjs)
- **DOCX parsing** — Mammoth.js (cdnjs)
- **RAG engine** — custom TF-IDF + bigram semantic scoring
- **LLM** — Anthropic Claude API (`claude-sonnet-4-20250514`)
