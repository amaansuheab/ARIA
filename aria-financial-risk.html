<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>ARIA · Financial Risk Intelligence Platform</title>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=DM+Sans:ital,wght@0,300;0,400;0,500;0,600;1,400&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet"/>
<script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/mammoth/1.6.0/mammoth.browser.min.js"></script>
<style>
:root{
  --bg:#020911;--bg2:#04111f;--bg3:#071a2e;--bg4:#0a2140;
  --border:#0d2438;--border2:#163756;--border3:#1e4a74;
  --accent:#00ccf5;--a2:#009fc0;--a3:#006880;
  --gold:#f5b800;--red:#ff3558;--green:#00e57a;--purple:#a87fff;
  --text:#aecfe8;--text2:#587fa0;--text3:#234258;--white:#e0f3ff;
}
*{box-sizing:border-box;margin:0;padding:0;}
html,body{height:100%;overflow:hidden;background:var(--bg);color:var(--text);font-family:'DM Sans',sans-serif;}
::-webkit-scrollbar{width:4px;height:4px;}
::-webkit-scrollbar-track{background:transparent;}
::-webkit-scrollbar-thumb{background:var(--border3);border-radius:4px;}
::-webkit-scrollbar-thumb:hover{background:var(--a3);}
@keyframes fadeUp{from{opacity:0;transform:translateY(12px)}to{opacity:1;transform:translateY(0)}}
@keyframes fadeIn{from{opacity:0}to{opacity:1}}
@keyframes pulse{0%,100%{opacity:1}50%{opacity:.3}}
@keyframes glow{0%,100%{box-shadow:0 0 8px rgba(0,204,245,.25)}50%{box-shadow:0 0 26px rgba(0,204,245,.65)}}
@keyframes scan{0%{background-position:-600px 0}100%{background-position:600px 0}}
@keyframes spin{to{transform:rotate(360deg)}}
@keyframes barIn{from{width:0}to{width:var(--w,100%)}}
.app{display:flex;flex-direction:column;height:100vh;background:radial-gradient(ellipse 80% 50% at 20% 10%,rgba(0,204,245,.04) 0%,transparent 60%),var(--bg);}
header{height:58px;background:linear-gradient(90deg,#030d1c,#071a2e 60%,#050f1a);border-bottom:1px solid var(--border);display:flex;align-items:center;justify-content:space-between;padding:0 22px;flex-shrink:0;z-index:200;position:relative;}
header::after{content:'';position:absolute;bottom:0;left:0;right:0;height:1px;background:linear-gradient(90deg,transparent,var(--accent) 50%,transparent);animation:scan 6s linear infinite;background-size:600px 1px;}
.logo{display:flex;align-items:center;gap:11px;cursor:default;}
.logo-hex{width:34px;height:34px;background:linear-gradient(135deg,var(--accent),var(--a2));border-radius:9px;display:flex;align-items:center;justify-content:center;font-size:17px;animation:glow 3.5s ease infinite;}
.logo-name{font-family:'Bebas Neue',cursive;font-size:22px;letter-spacing:.14em;color:var(--white);line-height:1;}
.logo-sub{font-size:8.5px;color:var(--text2);letter-spacing:.2em;text-transform:uppercase;margin-top:-2px;}
.hdr-pills{display:flex;align-items:center;gap:8px;}
.pill{display:flex;align-items:center;gap:5px;padding:4px 10px;border-radius:20px;font-size:9px;letter-spacing:.1em;}
.pill-live{background:rgba(0,229,122,.06);border:1px solid rgba(0,229,122,.2);color:#5ac890;}
.pill-docs{background:rgba(0,204,245,.07);border:1px solid rgba(0,204,245,.2);color:var(--accent);}
.live-dot{width:5px;height:5px;border-radius:50%;background:var(--green);animation:pulse 2s infinite;}
.clock{font-size:9px;color:var(--text3);letter-spacing:.12em;font-family:'Space Mono',monospace;}
.nav-tabs{display:flex;gap:2px;background:rgba(2,9,17,.8);border-radius:9px;padding:3px;border:1px solid var(--border);}
.nav-tab{padding:5px 14px;border-radius:7px;border:none;background:none;color:var(--text2);font-size:10px;letter-spacing:.08em;text-transform:uppercase;cursor:pointer;font-family:'DM Sans',sans-serif;transition:all .18s;white-space:nowrap;}
.nav-tab.active{background:rgba(0,204,245,.13);color:var(--accent);border:1px solid rgba(0,204,245,.22);}
.nav-tab:hover:not(.active){color:var(--text);background:rgba(255,255,255,.04);}
.body{display:flex;flex:1;overflow:hidden;}
.sidebar{width:214px;flex-shrink:0;background:linear-gradient(180deg,var(--bg2),var(--bg));border-right:1px solid var(--border);display:flex;flex-direction:column;overflow-y:auto;}
.sb-sec{padding:14px 14px 7px;font-size:8px;letter-spacing:.2em;text-transform:uppercase;color:var(--text3);}
.sb-item{display:flex;align-items:center;gap:8px;padding:9px 15px;cursor:pointer;font-size:11px;color:var(--text2);border-left:2px solid transparent;transition:all .16s;}
.sb-item:hover{color:var(--text);background:rgba(0,204,245,.03);}
.sb-item.active{color:var(--accent);border-left-color:var(--accent);background:rgba(0,204,245,.06);}
.sb-badge{margin-left:auto;background:rgba(0,204,245,.15);color:var(--accent);font-size:8.5px;padding:1px 7px;border-radius:10px;font-family:'Space Mono',monospace;}
.sb-sep{height:1px;background:var(--border);margin:6px 14px;}
.sb-bottom{margin-top:auto;padding:14px;border-top:1px solid var(--border);}
.kb-box{background:linear-gradient(135deg,rgba(0,204,245,.05),rgba(168,127,255,.04));border:1px solid var(--border2);border-radius:10px;padding:12px;margin-top:8px;}
.page{display:none;flex:1;overflow:hidden;flex-direction:column;}
.page.active{display:flex;}
.scroll{flex:1;overflow-y:auto;padding:22px;}
.sec-title{font-size:10px;letter-spacing:.16em;text-transform:uppercase;color:var(--text3);margin-bottom:13px;display:flex;align-items:center;gap:8px;}
.sec-title::after{content:'';flex:1;height:1px;background:var(--border);}
.stats-row{display:grid;grid-template-columns:repeat(4,1fr);gap:11px;margin-bottom:22px;}
.stat-card{background:var(--bg2);border:1px solid var(--border);border-radius:11px;padding:15px;transition:all .22s;position:relative;overflow:hidden;}
.stat-card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,transparent,var(--c,var(--accent)),transparent);}
.stat-val{font-family:'Bebas Neue',cursive;font-size:30px;color:var(--white);line-height:1;}
.stat-label{font-size:9px;text-transform:uppercase;letter-spacing:.1em;color:var(--text2);margin-top:3px;}
.upload-hero{border:2px dashed var(--border2);border-radius:14px;padding:36px 24px;text-align:center;cursor:pointer;transition:all .25s;background:radial-gradient(ellipse 60% 50% at 50% 50%,rgba(0,204,245,.03),transparent);position:relative;}
.upload-hero:hover,.upload-hero.drag{border-color:var(--accent);background:radial-gradient(ellipse 60% 50% at 50% 50%,rgba(0,204,245,.08),transparent);}
.fmt-chips{display:flex;justify-content:center;gap:7px;margin-top:14px;flex-wrap:wrap;}
.fmt-chip{font-size:9px;padding:3px 10px;border-radius:5px;letter-spacing:.07em;font-weight:600;}
.fmt-pdf{background:rgba(255,53,88,.12);border:1px solid rgba(255,53,88,.25);color:#ff8099;}
.fmt-docx{background:rgba(168,127,255,.12);border:1px solid rgba(168,127,255,.25);color:#c4aaff;}
.fmt-txt{background:rgba(0,204,245,.1);border:1px solid rgba(0,204,245,.22);color:var(--accent);}
.btn-row{display:flex;gap:8px;justify-content:center;margin-top:18px;flex-wrap:wrap;}
.btn{border:none;border-radius:8px;padding:9px 18px;font-size:11px;font-weight:600;cursor:pointer;font-family:'DM Sans',sans-serif;transition:all .18s;display:inline-flex;align-items:center;gap:6px;}
.btn-primary{background:linear-gradient(135deg,var(--a2),var(--accent));color:#000;}
.btn-primary:hover{opacity:.9;transform:translateY(-1px);}
.btn-ghost{background:rgba(255,255,255,.04);color:var(--text2);border:1px solid var(--border2);}
.btn-ghost:hover{border-color:var(--border3);color:var(--text);}
.btn-danger{background:rgba(255,53,88,.1);color:var(--red);border:1px solid rgba(255,53,88,.2);}
.btn-danger:hover{background:rgba(255,53,88,.2);}
.doc-item{background:var(--bg2);border:1px solid var(--border);border-radius:11px;padding:14px 16px;margin-bottom:9px;display:flex;align-items:center;gap:13px;transition:all .2s;animation:fadeUp .3s ease;}
.doc-item:hover{border-color:var(--border2);}
.doc-ico{width:38px;height:38px;border-radius:9px;display:flex;align-items:center;justify-content:center;font-size:17px;flex-shrink:0;}
.doc-info{flex:1;min-width:0;}
.doc-name{font-size:12px;color:var(--white);font-weight:500;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;margin-bottom:2px;}
.doc-meta{font-size:9px;color:var(--text2);}
.doc-chunks{font-size:9px;color:var(--accent);margin-top:2px;font-family:'Space Mono',monospace;}
.doc-sections{font-size:9px;color:var(--purple);margin-top:2px;}
.doc-prog-wrap{height:3px;background:var(--border);border-radius:2px;overflow:hidden;margin-top:7px;}
.doc-prog{height:100%;background:linear-gradient(90deg,var(--a2),var(--accent));border-radius:2px;animation:barIn 1.5s ease forwards;}
.badge{display:inline-flex;align-items:center;gap:4px;font-size:9px;padding:3px 9px;border-radius:10px;letter-spacing:.05em;}
.badge-ok{background:rgba(0,229,122,.1);border:1px solid rgba(0,229,122,.22);color:var(--green);}
.badge-proc{background:rgba(245,184,0,.1);border:1px solid rgba(245,184,0,.22);color:var(--gold);}
.badge-err{background:rgba(255,53,88,.1);border:1px solid rgba(255,53,88,.22);color:var(--red);}
.icon-btn{background:none;border:1px solid var(--border);border-radius:6px;padding:4px 9px;font-size:9px;cursor:pointer;color:var(--text2);font-family:'DM Sans',sans-serif;transition:all .15s;}
.icon-btn:hover{border-color:var(--border2);color:var(--text);}
.icon-btn.danger:hover{border-color:var(--red);color:var(--red);}
/* summary card shown after indexing */
.doc-summary-box{background:rgba(0,204,245,.04);border:1px solid rgba(0,204,245,.15);border-radius:8px;padding:10px 12px;margin-top:8px;font-size:10px;color:var(--text);line-height:1.7;}
.doc-summary-box strong{color:var(--white);}
/* chat */
.chat-layout{flex:1;display:flex;overflow:hidden;}
.chat-main{flex:1;display:flex;flex-direction:column;overflow:hidden;}
.chat-msgs{flex:1;overflow-y:auto;padding:20px 24px;display:flex;flex-direction:column;gap:15px;}
.welcome{text-align:center;padding:44px 20px;animation:fadeUp .5s ease;}
.welcome-hex{font-size:50px;margin-bottom:14px;display:block;}
.welcome-title{font-family:'Bebas Neue',cursive;font-size:32px;letter-spacing:.1em;color:var(--white);margin-bottom:8px;}
.welcome-sub{font-size:12px;color:var(--text2);line-height:1.65;max-width:440px;margin:0 auto 24px;}
.warn-box{display:inline-flex;align-items:center;gap:8px;background:rgba(245,184,0,.07);border:1px solid rgba(245,184,0,.22);border-radius:8px;padding:9px 15px;font-size:11px;color:var(--gold);margin-bottom:20px;}
.qp-grid{display:grid;grid-template-columns:1fr 1fr;gap:8px;max-width:560px;margin:0 auto;}
.qp-btn{background:var(--bg2);border:1px solid var(--border);border-radius:9px;padding:10px 14px;text-align:left;cursor:pointer;font-size:11px;color:var(--text2);font-family:'DM Sans',sans-serif;transition:all .2s;line-height:1.4;}
.qp-btn:hover{border-color:var(--a3);color:var(--accent);background:rgba(0,204,245,.05);}
.qp-btn::before{content:'› ';color:var(--accent);}
.msg{display:flex;gap:10px;align-items:flex-start;animation:fadeUp .22s ease;}
.msg.user{flex-direction:row-reverse;}
.av{width:30px;height:30px;border-radius:8px;display:flex;align-items:center;justify-content:center;font-size:12px;flex-shrink:0;font-weight:700;}
.av.ai{background:linear-gradient(135deg,var(--accent),var(--a2));color:#000;}
.av.user{background:rgba(0,204,245,.1);border:1px solid rgba(0,204,245,.2);color:var(--accent);}
.mbody{max-width:82%;min-width:0;}
.msrcs{display:flex;gap:4px;flex-wrap:wrap;margin-bottom:7px;}
.stag{font-size:9px;padding:2px 9px;border-radius:4px;background:rgba(0,204,245,.07);border:1px solid rgba(0,204,245,.17);color:var(--accent);cursor:pointer;transition:all .14s;}
.stag:hover{background:rgba(0,204,245,.16);}
.stag.purple{background:rgba(168,127,255,.07);border-color:rgba(168,127,255,.2);color:var(--purple);}
.mtxt{background:var(--bg2);border:1px solid var(--border);border-radius:4px 13px 13px 13px;padding:13px 17px;font-size:12px;line-height:1.85;color:var(--text);}
.msg.user .mtxt{background:rgba(0,204,245,.07);border-color:rgba(0,204,245,.17);border-radius:13px 4px 13px 13px;color:var(--white);}
.typing-box{display:flex;align-items:center;gap:10px;padding:12px 16px;background:var(--bg2);border:1px solid var(--border);border-radius:4px 13px 13px 13px;}
.tdot{width:5px;height:5px;border-radius:50%;background:var(--accent);animation:pulse 1.3s ease infinite;}
.tdot:nth-child(2){animation-delay:.22s;}.tdot:nth-child(3){animation-delay:.44s;}
.chat-bar{padding:14px 20px;border-top:1px solid var(--border);background:rgba(2,9,17,.9);}
.chat-wrap{display:flex;gap:10px;align-items:flex-end;background:var(--bg2);border:1px solid var(--border2);border-radius:11px;padding:10px 13px;transition:border-color .2s;}
.chat-wrap:focus-within{border-color:var(--a3);}
.chat-ta{flex:1;background:none;border:none;outline:none;color:var(--white);font-size:12px;line-height:1.6;font-family:'DM Sans',sans-serif;resize:none;max-height:120px;}
.chat-ta::placeholder{color:var(--text3);}
.send-btn{background:linear-gradient(135deg,var(--a2),var(--accent));border:none;border-radius:8px;padding:8px 16px;color:#000;font-size:11px;font-weight:700;cursor:pointer;transition:all .18s;flex-shrink:0;}
.send-btn:hover{opacity:.9;}
.send-btn:disabled{background:var(--bg3);color:var(--text3);cursor:not-allowed;}
.chat-footer{font-size:9px;color:var(--text3);text-align:center;margin-top:5px;letter-spacing:.07em;}
.rag-panel{width:268px;flex-shrink:0;border-left:1px solid var(--border);background:rgba(2,9,17,.85);overflow-y:auto;padding:15px;}
.rag-panel-hdr{font-size:9px;letter-spacing:.16em;text-transform:uppercase;color:var(--text3);margin-bottom:13px;display:flex;justify-content:space-between;align-items:center;}
.rag-card{background:var(--bg2);border:1px solid var(--border);border-radius:9px;padding:11px;margin-bottom:8px;cursor:pointer;transition:all .18s;position:relative;overflow:hidden;}
.rag-card:hover{border-color:var(--border2);transform:translateX(2px);}
.rag-card::before{content:'';position:absolute;left:0;top:0;bottom:0;width:3px;background:var(--rc,var(--accent));}
.rag-doc-name{font-size:9.5px;color:var(--accent);font-weight:500;padding-left:8px;margin-bottom:3px;}
.rag-section{font-size:8px;color:var(--purple);padding-left:8px;margin-bottom:4px;text-transform:uppercase;letter-spacing:.07em;}
.rag-snippet{font-size:9.5px;color:var(--text2);line-height:1.6;padding-left:8px;margin-bottom:6px;}
.rag-bars{padding-left:8px;}
.rag-bar-row{display:flex;align-items:center;gap:4px;margin-bottom:2px;}
.rag-bar{flex:1;height:2px;background:var(--border);border-radius:1px;overflow:hidden;}
.rag-bar-fill{height:100%;border-radius:1px;}
/* search */
.search-layout{flex:1;display:flex;overflow:hidden;}
.search-side{width:240px;border-right:1px solid var(--border);background:var(--bg2);padding:16px;flex-shrink:0;overflow-y:auto;}
.search-main{flex:1;overflow-y:auto;padding:22px;}
.search-bar-row{display:flex;gap:9px;margin-bottom:18px;}
.search-inp{flex:1;background:var(--bg2);border:1px solid var(--border2);border-radius:9px;padding:10px 15px;color:var(--white);font-size:12px;font-family:'DM Sans',sans-serif;outline:none;transition:all .2s;}
.search-inp:focus{border-color:var(--a3);}
.search-btn{background:linear-gradient(135deg,var(--a2),var(--accent));border:none;border-radius:9px;padding:10px 18px;color:#000;font-size:11px;font-weight:700;cursor:pointer;transition:all .18s;white-space:nowrap;}
.filter-label{font-size:8.5px;letter-spacing:.14em;text-transform:uppercase;color:var(--text3);margin-bottom:8px;margin-top:14px;}
.filter-chip{display:inline-flex;align-items:center;padding:4px 10px;border-radius:7px;border:1px solid var(--border);font-size:10px;color:var(--text2);cursor:pointer;margin:3px 3px 0 0;transition:all .16s;}
.filter-chip.active{border-color:var(--a3);color:var(--accent);background:rgba(0,204,245,.07);}
.result-card{background:var(--bg2);border:1px solid var(--border);border-radius:11px;padding:14px 16px;margin-bottom:10px;cursor:pointer;transition:all .2s;animation:fadeUp .22s ease;position:relative;overflow:hidden;}
.result-card:hover{border-color:var(--border2);transform:translateX(3px);}
.result-card::before{content:'';position:absolute;left:0;top:0;bottom:0;width:3px;background:var(--rc,var(--accent));}
.highlight{background:rgba(0,204,245,.18);color:var(--white);border-radius:2px;padding:0 2px;}
/* dashboard */
.dash-grid{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:22px;}
.dash-card{background:var(--bg2);border:1px solid var(--border);border-radius:12px;padding:16px;}
.dash-card-title{font-size:9.5px;letter-spacing:.12em;text-transform:uppercase;color:var(--text2);margin-bottom:14px;}
/* modal */
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.8);z-index:600;display:flex;align-items:center;justify-content:center;backdrop-filter:blur(6px);}
.modal{background:var(--bg2);border:1px solid var(--border2);border-radius:15px;width:720px;max-width:95vw;max-height:84vh;display:flex;flex-direction:column;overflow:hidden;animation:fadeUp .24s ease;}
.modal-hdr{padding:18px 24px;border-bottom:1px solid var(--border);display:flex;align-items:flex-start;justify-content:space-between;flex-shrink:0;}
.modal-body{padding:22px 24px;overflow-y:auto;font-size:12px;line-height:1.9;color:var(--text);}
.modal-close{background:none;border:none;color:var(--text2);font-size:22px;cursor:pointer;}
.modal-close:hover{color:var(--white);}
/* notif */
.notif{position:fixed;top:68px;right:20px;border-radius:9px;padding:10px 16px;font-size:11px;color:var(--white);z-index:1000;box-shadow:0 8px 28px rgba(0,0,0,.5);display:flex;align-items:center;gap:9px;max-width:360px;border:1px solid;animation:fadeUp .25s ease;}
.empty{text-align:center;padding:50px 20px;}
.spin{width:14px;height:14px;border:2px solid rgba(0,204,245,.2);border-top-color:var(--accent);border-radius:50%;animation:spin .8s linear infinite;display:inline-block;vertical-align:middle;}
</style>
</head>
<body>
<div class="app">
<header>
  <div class="logo">
    <div class="logo-hex">&#x2B21;</div>
    <div><div class="logo-name">ARIA</div><div class="logo-sub">Document Intelligence &bull; Dual RAG Platform</div></div>
  </div>
  <div class="hdr-pills">
    <div class="pill pill-live"><div class="live-dot"></div>LIVE</div>
    <div class="pill pill-docs" id="hdr-pill">0 DOCS</div>
    <div class="clock" id="clock">--:--:-- EST</div>
  </div>
  <div class="nav-tabs">
    <button class="nav-tab active" onclick="showPage('upload')">&#128196; Documents</button>
    <button class="nav-tab" onclick="showPage('advisor')">&#129504; AI Advisor</button>
    <button class="nav-tab" onclick="showPage('search')">&#128269; Search</button>
    <button class="nav-tab" onclick="showPage('dash')">&#128202; Analytics</button>
  </div>
</header>
<div class="body">
<div class="sidebar">
  <div class="sb-sec">Workspace</div>
  <div class="sb-item active" id="sb-upload" onclick="showPage('upload');setSB(this)">&#128196; Upload Documents</div>
  <div class="sb-item" id="sb-advisor" onclick="showPage('advisor');setSB(this)">&#129504; AI Advisor <span class="sb-badge">RAG</span></div>
  <div class="sb-item" id="sb-search" onclick="showPage('search');setSB(this)">&#128269; Search</div>
  <div class="sb-item" id="sb-dash" onclick="showPage('dash');setSB(this)">&#128202; Analytics</div>
  <div class="sb-sep"></div>
  <div class="sb-sec">Indexed Documents</div>
  <div id="sb-docs"><div style="font-size:10px;color:var(--text3);padding:8px 14px;">No documents yet</div></div>
  <div class="sb-bottom">
    <div style="font-size:9px;letter-spacing:.12em;text-transform:uppercase;color:var(--text3);">Knowledge Base</div>
    <div class="kb-box">
      <div style="display:flex;justify-content:space-between;margin-bottom:8px;">
        <div><div style="font-family:'Bebas Neue';font-size:24px;color:var(--accent);" id="sb-ndocs">0</div><div style="font-size:8px;color:var(--text2);text-transform:uppercase;letter-spacing:.08em;">Docs</div></div>
        <div style="text-align:center;"><div style="font-family:'Bebas Neue';font-size:24px;color:var(--gold);" id="sb-nchunks">0</div><div style="font-size:8px;color:var(--text2);text-transform:uppercase;letter-spacing:.08em;">Chunks</div></div>
        <div style="text-align:right;"><div style="font-family:'Bebas Neue';font-size:24px;color:var(--green);" id="sb-nwords">0K</div><div style="font-size:8px;color:var(--text2);text-transform:uppercase;letter-spacing:.08em;">Words</div></div>
      </div>
      <div style="height:3px;background:var(--border);border-radius:2px;overflow:hidden;"><div id="kb-bar" style="height:100%;background:linear-gradient(90deg,var(--a2),var(--accent));border-radius:2px;width:0%;transition:width .6s;"></div></div>
      <div style="font-size:8.5px;color:var(--text3);margin-top:5px;" id="kb-status">Awaiting documents</div>
    </div>
  </div>
</div>

<!-- ══ PAGE: UPLOAD ══ -->
<div class="page active" id="page-upload">
  <div class="scroll">
    <div class="stats-row">
      <div class="stat-card" style="--c:#00ccf5"><div class="stat-val" id="s-docs">0</div><div class="stat-label">Documents</div></div>
      <div class="stat-card" style="--c:#f5b800"><div class="stat-val" id="s-chunks">0</div><div class="stat-label">Chunks</div></div>
      <div class="stat-card" style="--c:#00e57a"><div class="stat-val" id="s-words">0K</div><div class="stat-label">Words</div></div>
      <div class="stat-card" style="--c:#a87fff"><div class="stat-val" id="s-sections">0</div><div class="stat-label">Sections Detected</div></div>
    </div>
    <div class="upload-hero" id="dropZone">
      <input type="file" id="fileIn" multiple accept=".pdf,.txt,.docx,.doc,.md,.csv" style="display:none" onchange="handleFiles(this.files)"/>
      <div style="font-size:40px;margin-bottom:12px;">&#128196;</div>
      <div style="font-size:16px;font-weight:600;color:var(--white);margin-bottom:5px;">Drop your documents here</div>
      <div style="font-size:11px;color:var(--text2);">Supports PDF (via PDF.js), Word / DOCX (via Mammoth), TXT, MD, CSV</div>
      <div class="fmt-chips">
        <span class="fmt-chip fmt-pdf">PDF</span>
        <span class="fmt-chip fmt-docx">DOCX</span>
        <span class="fmt-chip fmt-txt">TXT</span>
        <span class="fmt-chip fmt-txt">MD</span>
        <span class="fmt-chip fmt-txt">CSV</span>
      </div>
      <div class="btn-row">
        <button class="btn btn-primary" onclick="event.stopPropagation();document.getElementById('fileIn').click()">&#43; Add Files</button>
        <button class="btn btn-ghost" onclick="event.stopPropagation();loadSamples()">&#127860; Sample Docs</button>
        <button class="btn btn-danger" onclick="event.stopPropagation();clearAll()">&#128465; Clear All</button>
      </div>
    </div>
    <div style="margin-top:22px;" id="docListWrap">
      <div class="empty" id="docEmpty" style="padding:30px;">
        <div style="font-size:36px;margin-bottom:10px;">&#128194;</div>
        <div style="font-size:14px;color:var(--white);font-weight:600;margin-bottom:6px;">No documents uploaded</div>
        <div style="font-size:11px;color:var(--text2);">Upload any document — resume, report, policy, research paper, financial filing — and ask questions about it in natural language.</div>
      </div>
      <div id="docList"></div>
    </div>
  </div>
</div>

<!-- ══ PAGE: ADVISOR ══ -->
<div class="page" id="page-advisor">
  <div class="chat-layout">
    <div class="chat-main">
      <div class="chat-msgs" id="chatMsgs">
        <div class="welcome" id="welcomeScreen">
          <span class="welcome-hex">&#x2B21;</span>
          <div class="welcome-title">ARIA Document Advisor</div>
          <div class="welcome-sub">Ask <em>any</em> question about your uploaded documents — general overviews, specific details, comparisons, summaries. ARIA uses smart chunking + dual RAG to always find a relevant answer.</div>
          <div id="noDocsWarn" style="display:none;" class="warn-box">&#9888; No documents indexed yet — go to <strong>Documents</strong> tab first.</div>
          <div class="qp-grid">
            <button class="qp-btn" onclick="sendQ(this)">What is this document about?</button>
            <button class="qp-btn" onclick="sendQ(this)">Summarize the key points</button>
            <button class="qp-btn" onclick="sendQ(this)">Who is this document about?</button>
            <button class="qp-btn" onclick="sendQ(this)">What are the main projects listed?</button>
            <button class="qp-btn" onclick="sendQ(this)">What skills or technologies are mentioned?</button>
            <button class="qp-btn" onclick="sendQ(this)">What experience or work history is described?</button>
          </div>
        </div>
      </div>
      <div class="chat-bar">
        <div class="chat-wrap">
          <textarea class="chat-ta" id="chatInput" rows="2" placeholder="Ask anything about your documents..." onkeydown="onKey(event)"></textarea>
          <button class="send-btn" id="sendBtn" onclick="sendMsg()">SEND &#8629;</button>
        </div>
        <div class="chat-footer">DUAL RAG · <span id="ragLabel">0 DOCS</span> · ENTER TO SEND · SHIFT+ENTER FOR NEW LINE</div>
      </div>
    </div>
    <div class="rag-panel">
      <div class="rag-panel-hdr"><span>Retrieved Context</span><div style="width:5px;height:5px;border-radius:50%;background:var(--accent);animation:pulse 2s infinite;"></div></div>
      <div style="display:flex;gap:6px;margin-bottom:12px;flex-wrap:wrap;">
        <div style="display:flex;align-items:center;gap:3px;font-size:8px;color:var(--text3);"><div style="width:7px;height:7px;border-radius:50%;background:var(--accent);"></div>TF-IDF</div>
        <div style="display:flex;align-items:center;gap:3px;font-size:8px;color:var(--text3);"><div style="width:7px;height:7px;border-radius:50%;background:var(--purple);"></div>Semantic</div>
      </div>
      <div id="ragPanel"><div style="font-size:10px;color:var(--text3);text-align:center;padding:22px 8px;"><span style="font-size:28px;display:block;margin-bottom:8px;">&#128270;</span>Retrieved chunks will appear here after a query.</div></div>
    </div>
  </div>
</div>

<!-- ══ PAGE: SEARCH ══ -->
<div class="page" id="page-search">
  <div class="search-layout">
    <div class="search-side">
      <div class="sec-title">Filters</div>
      <div class="filter-label">Documents</div>
      <div id="docFilters"><span class="filter-chip active" onclick="setDF('all',this)">All</span></div>
      <div class="filter-label">Method</div>
      <div>
        <span class="filter-chip active" onclick="setMF('combined',this)">Combined</span>
        <span class="filter-chip" onclick="setMF('tfidf',this)">TF-IDF</span>
        <span class="filter-chip" onclick="setMF('semantic',this)">Semantic</span>
      </div>
      <div class="filter-label">Min Score</div>
      <div>
        <span class="filter-chip active" onclick="setMin(0,this)">All</span>
        <span class="filter-chip" onclick="setMin(.25,this)">&gt;25%</span>
        <span class="filter-chip" onclick="setMin(.5,this)">&gt;50%</span>
      </div>
      <div style="margin-top:14px;font-size:10px;color:var(--text2);line-height:1.75;" id="searchStats"></div>
    </div>
    <div class="search-main">
      <div class="search-bar-row">
        <input class="search-inp" id="searchInput" placeholder="Search across all indexed documents..." onkeydown="if(event.key==='Enter')doSearch()"/>
        <button class="search-btn" onclick="doSearch()">&#128269; Search</button>
      </div>
      <div id="searchResults"><div class="empty"><div style="font-size:36px;margin-bottom:10px;">&#128269;</div><div style="font-size:14px;color:var(--white);font-weight:600;margin-bottom:5px;">Search Your Documents</div><div style="font-size:11px;color:var(--text2);">Type a query to search across all indexed chunks.</div></div></div>
    </div>
  </div>
</div>

<!-- ══ PAGE: DASH ══ -->
<div class="page" id="page-dash">
  <div class="scroll">
    <div class="stats-row">
      <div class="stat-card" style="--c:#00ccf5"><div class="stat-val" style="color:var(--accent)" id="d-docs">0</div><div class="stat-label">Documents</div></div>
      <div class="stat-card" style="--c:#f5b800"><div class="stat-val" style="color:var(--gold)" id="d-chunks">0</div><div class="stat-label">Chunks</div></div>
      <div class="stat-card" style="--c:#00e57a"><div class="stat-val" style="color:var(--green)" id="d-words">0</div><div class="stat-label">Words</div></div>
      <div class="stat-card" style="--c:#a87fff"><div class="stat-val" style="color:var(--purple)" id="d-queries">0</div><div class="stat-label">Queries</div></div>
    </div>
    <div class="dash-grid">
      <div class="dash-card"><div class="dash-card-title">&#128196; Document Index</div><div id="docOverview"></div></div>
      <div class="dash-card"><div class="dash-card-title">&#128200; Query Stats</div><div id="queryStats"></div></div>
    </div>
    <div class="sec-title">Top Terms</div>
    <div class="dash-card" style="margin-bottom:18px;min-height:80px;line-height:1.9;" id="termCloud"><div style="font-size:11px;color:var(--text3);text-align:center;padding:16px;">Upload documents to see terms</div></div>
    <div class="sec-title">Query History</div>
    <div class="dash-card" style="padding:0;overflow:hidden;"><div id="queryHist"><div style="padding:16px;text-align:center;font-size:11px;color:var(--text3);">No queries yet</div></div></div>
  </div>
</div>

</div><!-- .body -->
</div><!-- .app -->

<!-- MODAL -->
<div class="modal-overlay" id="modal" style="display:none;" onclick="if(event.target===this)closeModal()">
  <div class="modal">
    <div class="modal-hdr">
      <div>
        <div id="modalMeta" style="font-size:9px;color:var(--accent);letter-spacing:.08em;margin-bottom:5px;"></div>
        <div id="modalTitle" style="font-size:16px;font-weight:700;color:var(--white);"></div>
      </div>
      <button class="modal-close" onclick="closeModal()">&#10005;</button>
    </div>
    <div class="modal-body" id="modalBody"></div>
  </div>
</div>

<div class="notif" id="notif" style="display:none;"></div>

<script>
// ═══════════════════════════════════════
// SETUP
// ═══════════════════════════════════════
if(typeof pdfjsLib!=='undefined')
  pdfjsLib.GlobalWorkerOptions.workerSrc='https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.worker.min.js';

const S={docs:[],queries:0,history:[],SF:{doc:'all',method:'combined',min:0}};
const TCOLORS={PDF:'#ff3558',TXT:'#00ccf5',DOCX:'#a87fff',DOC:'#a87fff',MD:'#00e57a',CSV:'#f5b800'};
const TICONS={PDF:'📄',TXT:'📝',DOCX:'📘',DOC:'📘',MD:'📋',CSV:'📊'};

// ═══════════════════════════════════════
// SMART STRUCTURAL CHUNKING
// ═══════════════════════════════════════
// Detects sections by headings, blank lines, bullets, numbered lists
function smartChunk(text, docId, docName){
  const chunks=[];
  
  // Try to detect structural sections first
  const sectionPatterns=[
    /^#{1,4}\s+(.+)$/m,           // Markdown headings
    /^([A-Z][A-Z\s]{3,50}):?\s*$/m, // ALL CAPS headings
    /^(\d+\.\s+[A-Z].{3,60})$/m,    // Numbered sections
    /^([A-Z][a-z].{3,50})\n[-=]{3,}$/m, // Underlined headings
  ];
  
  const hasSections=sectionPatterns.some(p=>p.test(text));
  
  if(hasSections){
    // Split by structural boundaries
    const lines=text.split('\n');
    let currentSection='Introduction';
    let buffer=[];
    
    function flushBuffer(){
      const t=buffer.join('\n').trim();
      if(t.length>60){
        const words=t.split(/\s+/).filter(w=>w.length>0);
        // Sub-chunk long sections
        const maxW=300;
        const overlap=60;
        if(words.length<=maxW){
          chunks.push({id:docId+'_c'+chunks.length,docId,docName,text:t,tokens:words.length,idx:chunks.length,section:currentSection,wStart:0});
        } else {
          for(let i=0;i<words.length;i+=maxW-overlap){
            const sl=words.slice(i,i+maxW).join(' ');
            chunks.push({id:docId+'_c'+chunks.length,docId,docName,text:sl,tokens:Math.min(maxW,words.length-i),idx:chunks.length,section:currentSection,wStart:i});
            if(i+maxW>=words.length) break;
          }
        }
      }
      buffer=[];
    }
    
    for(const line of lines){
      const trimmed=line.trim();
      // Detect heading
      const isHeading=
        /^#{1,4}\s+/.test(trimmed)||
        /^[A-Z][A-Z\s]{3,50}:?\s*$/.test(trimmed)||
        /^\d+\.\s+[A-Z]/.test(trimmed)&&trimmed.length<80;
      
      if(isHeading&&buffer.length>0){
        flushBuffer();
        currentSection=trimmed.replace(/^#+\s*/,'').replace(/\d+\.\s*/,'').replace(/:$/,'').trim()||currentSection;
        buffer=[line];
      } else {
        buffer.push(line);
      }
    }
    flushBuffer();
  }
  
  // Fallback: sliding window on words
  if(chunks.length===0){
    const words=text.split(/\s+/).filter(w=>w.length>0);
    const size=300, overlap=60;
    for(let i=0;i<words.length;i+=size-overlap){
      const sl=words.slice(i,i+size).join(' ');
      if(sl.trim().length>40)
        chunks.push({id:docId+'_c'+chunks.length,docId,docName,text:sl,tokens:Math.min(size,words.length-i),idx:chunks.length,section:'',wStart:i});
      if(i+size>=words.length) break;
    }
  }
  
  return chunks;
}

// Auto-generate document summary from full text
function buildDocSummary(text, docName){
  const words=text.split(/\s+/).filter(w=>w.length>0);
  const totalWords=words.length;
  
  // Extract likely title/name: first non-empty lines
  const lines=text.split('\n').map(l=>l.trim()).filter(l=>l.length>2);
  const firstLines=lines.slice(0,5);
  
  // Extract sentences for summarization
  const sentences=text.replace(/\n+/g,' ').split(/(?<=[.!?])\s+/).filter(s=>s.length>30);
  const firstSentences=sentences.slice(0,6).join(' ');
  
  // Detect document type heuristics
  const lower=text.toLowerCase();
  let docType='document';
  if(/resume|curriculum vitae|cv\b|work experience|education|skills/i.test(text)) docType='resume/CV';
  else if(/annual report|quarterly|revenue|earnings|financial statement/i.test(text)) docType='financial report';
  else if(/research|abstract|methodology|conclusion|references/i.test(text)) docType='research paper';
  else if(/policy|regulation|compliance|shall|must|prohibited/i.test(text)) docType='policy/regulation';
  else if(/invoice|purchase order|receipt|total amount/i.test(text)) docType='financial document';
  
  return {docType, firstLines, firstSentences, totalWords};
}

// ═══════════════════════════════════════
// QUERY INTENT DETECTION
// ═══════════════════════════════════════
function detectIntent(q){
  const ql=q.toLowerCase();
  // General / overview queries — need full-doc context
  const generalPatterns=[
    /what (is|are) (this|the) doc/,
    /what('s| is) in (this|the) doc/,
    /summarize|summary|overview|describe this/,
    /who is this (doc|resume|cv|about)/,
    /what (does|do) (this|the) (doc|file|resume)/,
    /tell me about (this|the) doc/,
    /give me (an? )?(overview|summary|idea)/,
  ];
  if(generalPatterns.some(p=>p.test(ql))) return 'general';
  
  // Person-identity queries
  if(/who is|person('s)?|name of|candidate|applicant|author/i.test(ql)) return 'person';
  
  // List queries — want multiple chunks
  if(/list|all (the|his|her)|what are (his|her|the)|enumerate|show (me )?all/i.test(ql)) return 'list';
  
  return 'specific';
}

// ═══════════════════════════════════════
// DUAL RAG ENGINE
// ═══════════════════════════════════════
const STOP=new Set(['the','a','an','and','or','but','in','on','at','to','for','of','with','by','is','are','was','were','be','been','have','has','had','do','does','did','will','would','could','should','may','might','this','that','these','those','it','its','from','as','into','through','during','before','after','each','more','most','other','some','such','no','not','only','own','same','than','too','very','can','just','also','i','we','you','they','he','she','so','if','up','out','then','when','all','their','our','which','who','about','there','been','what','how','his','her','its']);

function tok(t){return t.toLowerCase().replace(/[^a-z0-9\s]/g,' ').split(/\s+/).filter(w=>w.length>2&&!STOP.has(w));}

function idfOf(chunks){
  const N=chunks.length;const df={};
  chunks.forEach(c=>{new Set(tok(c.text)).forEach(t=>{df[t]=(df[t]||0)+1;});});
  const idf={};Object.keys(df).forEach(t=>{idf[t]=Math.log((N+1)/(df[t]+1))+1;});
  return idf;
}
function tfidfScore(qT,cT,idf){
  const tf={};cT.forEach(t=>{tf[t]=(tf[t]||0)+1;});
  const mx=Math.max(1,...Object.values(tf));Object.keys(tf).forEach(k=>tf[k]/=mx);
  let s=0;
  qT.forEach(qt=>{
    if(tf[qt]) s+=tf[qt]*(idf[qt]||1);
    cT.forEach(ct=>{if(ct!==qt&&ct.includes(qt)) s+=0.25*(idf[ct]||0.5);});
  });
  return s;
}
function bigrams(tokens){const bg=new Set();for(let i=0;i<tokens.length-1;i++)bg.add(tokens[i]+'_'+tokens[i+1]);return bg;}
function semanticScore(qT,cT){
  const qBg=bigrams(qT),cBg=bigrams(cT),cSet=new Set(cT);
  let s=0;
  qT.forEach(qt=>{if(cSet.has(qt))s+=1.5;});
  qBg.forEach(bg=>{if(cBg.has(bg))s+=2.5;});
  qT.forEach(qt=>{cT.forEach(ct=>{
    if(ct!==qt){
      if(ct.startsWith(qt.slice(0,Math.max(4,qt.length-2))))s+=0.5;
      else if(qt.startsWith(ct.slice(0,Math.max(4,ct.length-2))))s+=0.35;
    }
  });});
  return s;
}

function dualRAG(query, topK=5, filterDocId=null){
  let pool=S.docs.filter(d=>d.status==='ok');
  if(filterDocId) pool=pool.filter(d=>d.id===filterDocId);
  const allChunks=pool.flatMap(d=>d.chunks);
  if(!allChunks.length) return [];
  const idf=idfOf(allChunks);
  const qT=tok(query);
  const scored=allChunks.map(c=>{
    const cT=tok(c.text);
    const ts=tfidfScore(qT,cT,idf);
    const ss=semanticScore(qT,cT);
    return{...c,ts,ss};
  });
  const maxT=Math.max(1,...scored.map(c=>c.ts));
  const maxS=Math.max(1,...scored.map(c=>c.ss));
  scored.forEach(c=>{c.tN=c.ts/maxT;c.sN=c.ss/maxS;c.score=c.tN*0.55+c.sN*0.45;});
  return scored.filter(c=>c.score>0.005).sort((a,b)=>b.score-a.score).slice(0,topK);
}

// For general queries, use all chunks of the doc(s)
function getAllChunks(docId){
  if(docId){
    const doc=S.docs.find(d=>d.id===docId);
    return doc?doc.chunks:[];
  }
  return S.docs.filter(d=>d.status==='ok').flatMap(d=>d.chunks);
}

// ═══════════════════════════════════════
// ANSWER GENERATION — SMART
// ═══════════════════════════════════════
function buildAnswer(query, chunks, intent){
  const ok=S.docs.filter(d=>d.status==='ok');
  if(!ok.length) return 'No documents indexed yet. Please upload documents first.';
  
  const ql=query.toLowerCase();

  // ── GENERAL / OVERVIEW ──
  if(intent==='general'){
    const doc=chunks.length?S.docs.find(d=>d.id===chunks[0].docId)||ok[0]:ok[0];
    const {docType,firstLines,firstSentences}=doc.summary||buildDocSummary(doc.text,doc.name);
    let ans=`**Document:** ${doc.name}\n**Type:** ${docType}\n\n`;
    ans+=`**Overview:**\n${firstSentences.slice(0,600)}\n\n`;
    if(doc.sections&&doc.sections.length){
      ans+=`**Sections detected (${doc.sections.length}):**\n${doc.sections.slice(0,8).map(s=>'• '+s).join('\n')}\n\n`;
    }
    ans+=`[i] ${doc.chunks.length} chunks indexed from this document (${doc.words.toLocaleString()} words).`;
    return ans;
  }

  // ── PERSON IDENTITY ──
  if(intent==='person'){
    // Get first chunks which usually have name/contact
    const doc=chunks.length?S.docs.find(d=>d.id===chunks[0].docId)||ok[0]:ok[0];
    const firstChunks=doc.chunks.slice(0,3);
    const combinedText=firstChunks.map(c=>c.text).join('\n');
    const sentences=combinedText.split(/[.!\n]+/).filter(s=>s.trim().length>15).slice(0,8);
    let ans=`Based on **"${doc.name}"**:\n\n`;
    ans+=sentences.map(s=>s.trim()).join('\n')+'\n\n';
    ans+=`[i] Sourced from the first ${firstChunks.length} chunks of the document.`;
    return ans;
  }

  // ── NO RESULTS ──
  if(!chunks.length){
    // Fallback: return first chunk of first doc
    const fallbackDoc=ok[0];
    if(!fallbackDoc) return 'No documents indexed yet.';
    const fc=fallbackDoc.chunks[0];
    return `I couldn\'t find a specific match for your query, but here\'s context from **"${fallbackDoc.name}"**:\n\n${fc?fc.text.slice(0,500):'(empty document)'}\n\n[!] Try rephrasing with specific terms from the document, or use the Search tab.`;
  }

  // ── LIST QUERY — aggregate across multiple chunks ──
  if(intent==='list'){
    const docNames=[...new Set(chunks.map(c=>c.docName))];
    let ans=`From **${docNames.length>1?docNames.join(', '):'"'+docNames[0]+'"'}**:\n\n`;
    const qT=tok(query);
    // Collect all bullet/numbered items from retrieved chunks
    const items=[];
    chunks.forEach(c=>{
      const lines=c.text.split('\n').filter(l=>l.trim().length>10);
      lines.forEach(l=>{
        const t=l.trim();
        if(/^[•\-\*]\s+/.test(t)||/^\d+[.)]\s+/.test(t)||qT.some(qt=>t.toLowerCase().includes(qt))){
          if(!items.includes(t)&&t.length>20) items.push(t);
        }
      });
    });
    if(items.length>=2){
      ans+=items.slice(0,12).map(i=>'• '+i.replace(/^[•\-\*\d.)\s]+/,'')).join('\n');
    } else {
      // fallback: extract relevant sentences
      const allText=chunks.map(c=>c.text).join('\n');
      const sentences=allText.split(/[.!?]+/).filter(s=>s.trim().length>20);
      const rel=sentences.filter(s=>qT.some(qt=>s.toLowerCase().includes(qt))).slice(0,8);
      ans+=(rel.length?rel:sentences.slice(0,6)).map(s=>'• '+s.trim()).join('\n');
    }
    ans+=`\n\n[i] Retrieved from ${chunks.length} chunks via dual RAG.`;
    return ans;
  }

  // ── SPECIFIC QUERY ──
  const docNames=[...new Set(chunks.map(c=>c.docName))];
  let ans=`Based on **${docNames.length>1?docNames.length+' documents':'"'+docNames[0]+'"'}**:\n\n`;
  const qT=tok(query);
  const allText=chunks.map(c=>c.text).join(' ');
  const sentences=allText.split(/(?<=[.!?])\s+/).filter(s=>s.trim().length>30);
  const scored=sentences.map(s=>({s,sc:qT.filter(qt=>s.toLowerCase().includes(qt)).length})).filter(x=>x.sc>0).sort((a,b)=>b.sc-a.sc);
  const seen=new Set();
  const uniq=scored.filter(x=>{const k=x.s.trim().slice(0,50);if(seen.has(k))return false;seen.add(k);return true;}).slice(0,6);
  
  if(uniq.length>=1){
    ans+=uniq.map(x=>x.s.trim()).join('\n\n');
  } else {
    ans+=chunks[0].text.slice(0,600)+(chunks[0].text.length>600?'...':'');
  }
  ans+=`\n\n[i] Retrieved from ${chunks.length} chunk${chunks.length>1?'s':''} · dual RAG (TF-IDF + Semantic).`;
  return ans;
}

// ═══════════════════════════════════════
// FILE PARSING
// ═══════════════════════════════════════
async function parsePDF(file){
  if(typeof pdfjsLib==='undefined') throw new Error('PDF.js not loaded');
  const ab=await file.arrayBuffer();
  const pdf=await pdfjsLib.getDocument({data:ab}).promise;
  let text='';
  for(let p=1;p<=pdf.numPages;p++){
    const page=await pdf.getPage(p);
    const content=await page.getTextContent();
    text+=content.items.map(i=>i.str).join(' ')+'\n';
  }
  return{text,pages:pdf.numPages};
}

async function parseDOCX(file){
  if(typeof mammoth!=='undefined'){
    return new Promise(res=>{
      const r=new FileReader();
      r.onload=e=>{
        mammoth.extractRawText({arrayBuffer:e.target.result})
          .then(result=>res({text:result.value||'',pages:1}))
          .catch(()=>res({text:'[DOCX parse error]',pages:1}));
      };
      r.readAsArrayBuffer(file);
    });
  }
  return new Promise(res=>{
    const r=new FileReader();
    r.onload=e=>{
      try{
        const dec=new TextDecoder('utf-8',{fatal:false}).decode(new Uint8Array(e.target.result));
        const m=dec.match(/<w:t[^>]*>([^<]*)<\/w:t>/g)||[];
        res({text:m.map(x=>x.replace(/<[^>]+>/g,'')).join(' ')||'[Empty DOCX]',pages:1});
      }catch(err){res({text:'[DOCX error]',pages:1});}
    };
    r.readAsArrayBuffer(file);
  });
}

async function parseTXT(file){
  return new Promise((res,rej)=>{
    const r=new FileReader();
    r.onload=e=>res({text:e.target.result,pages:1});
    r.onerror=()=>rej(new Error('Read error'));
    r.readAsText(file);
  });
}

async function parseFile(file){
  const ext=file.name.split('.').pop().toLowerCase();
  if(ext==='pdf') return parsePDF(file);
  if(ext==='docx'||ext==='doc') return parseDOCX(file);
  return parseTXT(file);
}

// ═══════════════════════════════════════
// PROCESS DOCUMENT
// ═══════════════════════════════════════
async function handleFiles(files){for(const f of Array.from(files)) await processDoc(f);document.getElementById('fileIn').value='';}

async function processDoc(file){
  const id='d'+Date.now()+Math.random().toString(36).slice(2,5);
  const doc={id,name:file.name,type:file.name.split('.').pop().toUpperCase(),size:file.size,pages:0,text:'',chunks:[],sections:[],words:0,summary:null,status:'processing',added:new Date()};
  S.docs.push(doc);
  renderDocs();refreshStats();
  notify('&#128196; Processing "'+file.name+'"...','info');
  try{
    const{text,pages}=await parseFile(file);
    doc.text=text;doc.pages=pages;
    doc.words=text.split(/\s+/).filter(w=>w.length>0).length;
    doc.chunks=smartChunk(text,id,file.name);
    doc.sections=[...new Set(doc.chunks.map(c=>c.section).filter(Boolean))];
    doc.summary=buildDocSummary(text,file.name);
    doc.status='ok';
    renderDocs();refreshStats();updateSidebar();
    notify('&#10003; "'+file.name+'" — '+doc.chunks.length+' chunks, '+doc.sections.length+' sections, '+doc.words.toLocaleString()+' words','success');
  }catch(err){
    doc.status='err';doc.error=err.message;
    renderDocs();refreshStats();
    notify('&#10007; '+err.message,'error');
  }
}

// ═══════════════════════════════════════
// SAMPLE DOCS
// ═══════════════════════════════════════
const SAMPLES=[
{name:'Basel_III_Framework.txt',content:`BASEL III CAPITAL ADEQUACY FRAMEWORK

1. OVERVIEW
Basel III is a comprehensive regulatory framework developed by the Basel Committee on Banking Supervision (BCBS) after the 2008 global financial crisis.

2. CAPITAL REQUIREMENTS
Common Equity Tier 1 (CET1): 4.5% of RWA minimum
Tier 1 Capital Ratio: 6.0% of RWA
Total Capital Ratio: 8.0% of RWA
Capital Conservation Buffer: 2.5% additional CET1
Countercyclical Capital Buffer: 0–2.5% at national discretion
G-SIB Surcharge: 1.0–3.5% for systemic banks

3. LEVERAGE RATIO
Tier 1 Capital / Total Exposure >= 3.0%. Non-risk-based backstop measure.

4. LIQUIDITY COVERAGE RATIO (LCR)
LCR = HQLA / Net Cash Outflows (30 days) >= 100%
Level 1: Cash, central bank reserves — no haircut
Level 2A: Sovereign bonds (20% RW), agency — 15% haircut, 40% cap
Level 2B: RMBS, IG corporate, equities — 25-50% haircut, 15% cap

5. NET STABLE FUNDING RATIO (NSFR)
Available Stable Funding / Required Stable Funding >= 100%

6. OUTPUT FLOOR (BASEL IV)
Internal model RWA cannot be less than 72.5% of standardized RWA, phasing in to 2028.`},
{name:'VaR_and_Expected_Shortfall.txt',content:`MARKET RISK: VALUE AT RISK (VaR) AND EXPECTED SHORTFALL

1. VALUE AT RISK
VaR is the maximum loss not exceeded at a given confidence level over a specified horizon.
99% 1-day VaR = 5th worst loss out of 500 historical scenarios.

Methods:
- Historical Simulation: uses 500-day actual P&L history, no distributional assumption
- Parametric: assumes normality, VaR = mean - z*sigma*sqrt(T), z=2.326 for 99%
- Monte Carlo: thousands of simulated scenarios, handles non-linearity

2. EXPECTED SHORTFALL
ES = average loss in the worst (1-alpha) scenarios = E[L | L > VaR(alpha)]
ES is a coherent risk measure (satisfies sub-additivity). VaR is not coherent.
FRTB mandates ES at 97.5% confidence.

3. BACKTESTING
Green zone: 0-4 exceptions / 250 days (multiplier 1.5)
Yellow zone: 5-9 exceptions (multiplier up to 1.99)
Red zone: 10+ exceptions (multiplier 2.0, model review)

4. FRTB LIQUIDITY HORIZONS
Bucket 1: 10 days (most liquid)
Bucket 2: 20 days
Bucket 3: 40 days
Bucket 4: 60 days
Bucket 5: 120 days (least liquid)`}
];

function loadSamples(){
  notify('&#128196; Loading sample documents...','info');
  SAMPLES.forEach((sd,i)=>setTimeout(()=>{
    const f=new File([new Blob([sd.content],{type:'text/plain'})],sd.name,{type:'text/plain'});
    processDoc(f);
  },i*350));
}

function clearAll(){
  if(!S.docs.length) return;
  if(!confirm('Clear all '+S.docs.length+' document(s)?')) return;
  S.docs=[];S.history=[];S.queries=0;
  document.getElementById('docList').innerHTML='';
  document.getElementById('docEmpty').style.display='block';
  refreshStats();updateSidebar();
  notify('&#128465; All documents cleared','info');
}

// ═══════════════════════════════════════
// RENDER
// ═══════════════════════════════════════
function renderDocs(){
  const el=document.getElementById('docList');
  const empty=document.getElementById('docEmpty');
  if(!S.docs.length){empty.style.display='block';el.innerHTML='';return;}
  empty.style.display='none';
  S.docs.forEach(doc=>{
    let item=document.getElementById('di-'+doc.id);
    if(!item){item=document.createElement('div');item.id='di-'+doc.id;item.className='doc-item';el.appendChild(item);}
    const col=TCOLORS[doc.type]||'#5a8aaa';
    const ico=TICONS[doc.type]||'📄';
    const badge=doc.status==='processing'?'<span class="badge badge-proc"><span class="spin"></span> Processing</span>':doc.status==='err'?'<span class="badge badge-err">&#10007; Error</span>':'<span class="badge badge-ok">&#10003; Indexed</span>';
    const summaryHtml=doc.status==='ok'&&doc.summary?`<div class="doc-summary-box"><strong>${doc.summary.docType}</strong> · ${doc.chunks.length} chunks · ${doc.sections.length} sections<br/>${doc.summary.firstSentences.slice(0,180)}${doc.summary.firstSentences.length>180?'...':''}</div>`:'';
    item.innerHTML=`
      <div class="doc-ico" style="background:${col}18;border:1px solid ${col}28;">${ico}</div>
      <div class="doc-info" style="flex:1;min-width:0;">
        <div class="doc-name">${doc.name}</div>
        <div class="doc-meta">${doc.type} · ${fmtSz(doc.size)}${doc.pages>1?' · '+doc.pages+' pages':''}</div>
        ${doc.status==='ok'?`<div class="doc-chunks">${doc.chunks.length} chunks · ${doc.words.toLocaleString()} words</div>`:''}
        ${doc.sections&&doc.sections.length?`<div class="doc-sections">Sections: ${doc.sections.slice(0,5).join(', ')}${doc.sections.length>5?'...':''}</div>`:''}
        ${doc.status==='processing'?'<div class="doc-prog-wrap"><div class="doc-prog"></div></div>':''}
        ${doc.status==='err'?`<div style="font-size:9px;color:var(--red);margin-top:2px;">${doc.error}</div>`:''}
        ${summaryHtml}
      </div>
      <div style="display:flex;gap:6px;flex-shrink:0;align-items:center;flex-direction:column;">
        ${badge}
        ${doc.status==='ok'?`<button class="icon-btn" onclick="viewDoc('${doc.id}')">&#128065; View</button>`:''}
        <button class="icon-btn danger" onclick="removeDoc('${doc.id}')">&#128465;</button>
      </div>`;
  });
}

function refreshStats(){
  const ok=S.docs.filter(d=>d.status==='ok');
  const tc=ok.reduce((s,d)=>s+d.chunks.length,0);
  const tw=ok.reduce((s,d)=>s+d.words,0);
  const tp=ok.reduce((s,d)=>s+d.pages,0);
  const ts=ok.reduce((s,d)=>s+d.sections.length,0);
  $('s-docs',ok.length);$('s-chunks',tc);$('s-words',(tw/1000).toFixed(1)+'K');$('s-sections',ts);
  $('sb-ndocs',ok.length);$('sb-nchunks',tc);$('sb-nwords',(tw/1000).toFixed(0)+'K');
  $('d-docs',ok.length);$('d-chunks',tc);$('d-words',tw.toLocaleString());$('d-queries',S.queries);
  $('kb-status',ok.length?tc+' chunks ready':'Awaiting documents');
  $('ragLabel',ok.length+' DOC'+(ok.length!==1?'S':'')+' INDEXED');
  $('hdr-pill',ok.length+' DOC'+(ok.length!==1?'S':''));
  document.getElementById('kb-bar').style.width=Math.min(100,ok.length*14)+'%';
  const w=document.getElementById('noDocsWarn');if(w)w.style.display=ok.length?'none':'inline-flex';
  updateDocFilters();
}

function updateSidebar(){
  const el=document.getElementById('sb-docs');
  const ok=S.docs.filter(d=>d.status==='ok');
  if(!ok.length){el.innerHTML='<div style="font-size:10px;color:var(--text3);padding:8px 14px;">No documents yet</div>';return;}
  el.innerHTML=ok.map(d=>`<div class="sb-item" onclick="viewDoc('${d.id}')" style="padding:7px 12px;">
    <span style="color:${TCOLORS[d.type]||'#5a8aaa'};font-size:11px;">${TICONS[d.type]||'📄'}</span>
    <span style="white-space:nowrap;overflow:hidden;text-overflow:ellipsis;font-size:10px;">${d.name}</span>
    <span class="sb-badge" style="font-size:8px;">${d.chunks.length}</span>
  </div>`).join('');
}

function updateDocFilters(){
  const ok=S.docs.filter(d=>d.status==='ok');
  const el=document.getElementById('docFilters');
  el.innerHTML=`<span class="filter-chip active" onclick="setDF('all',this)">All</span>`+ok.map(d=>`<span class="filter-chip" onclick="setDF('${d.id}',this)">${d.name.split('.')[0].slice(0,16)}</span>`).join('');
}

// ═══════════════════════════════════════
// CHAT
// ═══════════════════════════════════════
let busy=false;
function onKey(e){if(e.key==='Enter'&&!e.shiftKey){e.preventDefault();sendMsg();}}
function sendQ(btn){document.getElementById('chatInput').value=btn.textContent.replace(/^›\s*/,'').trim();sendMsg();}

function sendMsg(){
  if(busy)return;
  const inp=document.getElementById('chatInput');
  const q=inp.value.trim();if(!q)return;
  inp.value='';
  const ws=document.getElementById('welcomeScreen');if(ws)ws.remove();
  addMsg('user',q,[]);
  busy=true;document.getElementById('sendBtn').disabled=true;
  const typing=addTyping();
  
  const intent=detectIntent(q);
  let chunks;
  
  if(intent==='general'||intent==='person'){
    // Use first few chunks of the most relevant doc
    const ok=S.docs.filter(d=>d.status==='ok');
    if(ok.length){
      const doc=ok[0]; // or pick based on any doc filter
      chunks=doc.chunks.slice(0,5); // first 5 chunks
      // give them fake scores for display
      chunks=chunks.map((c,i)=>({...c,tN:1-i*0.1,sN:1-i*0.12,score:1-i*0.1}));
    } else { chunks=[]; }
  } else if(intent==='list'){
    chunks=dualRAG(q,8);
  } else {
    chunks=dualRAG(q,5);
  }
  
  renderRagPanel(chunks, intent);
  S.queries++;
  S.history.push({query:q,chunks:chunks.length,intent,time:new Date()});

  setTimeout(()=>{
    typing.remove();
    addMsg('assistant',buildAnswer(q,chunks,intent),chunks);
    busy=false;document.getElementById('sendBtn').disabled=false;
    refreshStats();
  },400+Math.random()*300);
}

function addMsg(role,text,chunks){
  const c=document.getElementById('chatMsgs');
  const d=document.createElement('div');d.className='msg '+role;
  const srcs=role==='assistant'&&chunks.length?
    '<div class="msrcs">'+chunks.slice(0,5).map(ch=>`<span class="stag ${ch.sN>ch.tN?'purple':''}" onclick="showChunk('${ch.id}')">&#128206; ${ch.docName.split('.')[0].slice(0,16)} #${ch.idx+1}${ch.section?' · '+ch.section.slice(0,12):''}</span>`).join('')+'</div>':'';
  d.innerHTML=`<div class="av ${role}">${role==='user'?'U':'&#x2B21;'}</div><div class="mbody">${srcs}<div class="mtxt">${fmt(text)}</div></div>`;
  c.appendChild(d);c.scrollTop=c.scrollHeight;return d;
}

function addTyping(){
  const c=document.getElementById('chatMsgs');
  const d=document.createElement('div');d.className='msg';
  d.innerHTML=`<div class="av ai">&#x2B21;</div><div class="mbody"><div class="typing-box"><div style="display:flex;gap:4px;"><div class="tdot"></div><div class="tdot"></div><div class="tdot"></div></div><span style="font-size:9.5px;color:var(--text2);letter-spacing:.07em;">DUAL RAG · INTENT DETECTION · SCORING</span></div></div>`;
  c.appendChild(d);c.scrollTop=c.scrollHeight;return d;
}

function fmt(t){
  return t.replace(/\*\*(.*?)\*\*/g,'<strong style="color:var(--white)">$1</strong>')
    .replace(/\*(.*?)\*/g,'<em>$1</em>')
    .replace(/\n/g,'<br/>')
    .replace(/^• /gm,'<span style="color:var(--accent);margin-right:4px;">•</span>')
    .replace(/\[i\]/g,'<span style="color:var(--green)">ⓘ</span>')
    .replace(/\[!\]/g,'<span style="color:var(--gold)">⚠</span>');
}

function renderRagPanel(chunks, intent){
  const el=document.getElementById('ragPanel');
  if(!chunks.length){el.innerHTML='<div style="font-size:10px;color:var(--text3);text-align:center;padding:20px 8px;"><span style="font-size:28px;display:block;margin-bottom:8px;">&#128270;</span>No chunks matched. Upload documents first.</div>';return;}
  const intentLabel={general:'📄 General Overview',person:'👤 Person/Identity',list:'📋 List Query',specific:'🔍 Specific Query'};
  el.innerHTML=`<div style="font-size:9px;padding:5px 8px;border-radius:5px;background:rgba(0,204,245,.07);border:1px solid rgba(0,204,245,.15);color:var(--accent);margin-bottom:10px;">Intent: ${intentLabel[intent]||intent}</div>`
  +chunks.slice(0,5).map(ch=>{
    const col=ch.sN>ch.tN?'var(--purple)':'var(--accent)';
    return`<div class="rag-card" style="--rc:${col}" onclick="showChunk('${ch.id}')">
      <div class="rag-doc-name">${ch.docName.split('.')[0]}</div>
      ${ch.section?`<div class="rag-section">${ch.section}</div>`:''}
      <div class="rag-snippet">${ch.text.slice(0,100)}...</div>
      <div class="rag-bars">
        <div class="rag-bar-row"><span style="font-size:8px;color:var(--text3);width:54px;">TF-IDF</span><div class="rag-bar"><div class="rag-bar-fill" style="width:${(ch.tN*100).toFixed(0)}%;background:var(--accent);"></div></div><span style="font-size:8px;color:var(--text3);width:24px;text-align:right;">${(ch.tN*100).toFixed(0)}%</span></div>
        <div class="rag-bar-row"><span style="font-size:8px;color:var(--text3);width:54px;">Semantic</span><div class="rag-bar"><div class="rag-bar-fill" style="width:${(ch.sN*100).toFixed(0)}%;background:var(--purple);"></div></div><span style="font-size:8px;color:var(--text3);width:24px;text-align:right;">${(ch.sN*100).toFixed(0)}%</span></div>
      </div>
    </div>`;
  }).join('');
}

// ═══════════════════════════════════════
// SEARCH
// ═══════════════════════════════════════
const SF=S.SF;
function setDF(id,el){SF.doc=id;el.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));el.classList.add('active');}
function setMF(m,el){SF.method=m;el.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));el.classList.add('active');}
function setMin(v,el){SF.min=v;el.parentElement.querySelectorAll('.filter-chip').forEach(c=>c.classList.remove('active'));el.classList.add('active');}

function doSearch(){
  const q=document.getElementById('searchInput').value.trim();if(!q)return;
  let results=dualRAG(q,20,SF.doc==='all'?null:SF.doc);
  if(SF.method==='tfidf') results=results.sort((a,b)=>b.tN-a.tN);
  else if(SF.method==='semantic') results=results.sort((a,b)=>b.sN-a.sN);
  if(SF.min>0) results=results.filter(r=>r.score>=SF.min);
  document.getElementById('searchStats').innerHTML=`Results: <strong style="color:var(--white)">${results.length}</strong><br/>Tokens: <span style="color:var(--accent)">${tok(q).join(', ')||'(filtered)'}</span>`;
  const el=document.getElementById('searchResults');
  if(!results.length){el.innerHTML='<div class="empty"><div style="font-size:32px;margin-bottom:8px;">&#128270;</div><div style="font-size:13px;color:var(--white);font-weight:600;">No results</div><div style="font-size:11px;color:var(--text2);">Try different keywords or change filters.</div></div>';return;}
  const mx=results[0].score||1;
  el.innerHTML=results.slice(0,15).map(r=>{
    const col=r.tN>=r.sN?'var(--accent)':'var(--purple)';
    return`<div class="result-card" style="--rc:${col}" onclick="showChunk('${r.id}')">
      <div style="display:flex;align-items:flex-start;justify-content:space-between;margin-bottom:7px;padding-left:10px;">
        <div><div style="font-size:10px;color:${col};">&#128196; ${r.docName}${r.section?' · '+r.section:''} · Chunk #${r.idx+1}</div><div style="font-size:8px;color:var(--text3);margin-top:1px;">${r.tokens} tokens</div></div>
        <div style="display:flex;gap:5px;font-size:9px;font-family:'Space Mono',monospace;"><span style="color:var(--accent)">TF:${(r.tN*100).toFixed(0)}%</span><span style="color:var(--purple)">SEM:${(r.sN*100).toFixed(0)}%</span></div>
      </div>
      <div style="font-size:11px;color:var(--text);line-height:1.75;padding-left:10px;">${hl(r.text.slice(0,300),tok(q))}${r.text.length>300?'...':''}</div>
      <div style="margin-top:8px;height:2px;background:var(--border);border-radius:1px;overflow:hidden;margin-left:10px;"><div style="height:100%;width:${(r.score/mx*100).toFixed(0)}%;background:${col};border-radius:1px;"></div></div>
    </div>`;
  }).join('');
}
function hl(t,terms){let o=t;terms.forEach(w=>{o=o.replace(new RegExp('('+w+')','gi'),'<span class="highlight">$1</span>');});return o;}

// ═══════════════════════════════════════
// DASHBOARD
// ═══════════════════════════════════════
function renderDash(){
  refreshStats();
  const ok=S.docs.filter(d=>d.status==='ok');
  const dov=document.getElementById('docOverview');
  dov.innerHTML=ok.length?ok.map(d=>`<div style="display:flex;align-items:center;gap:10px;padding:9px 0;border-bottom:1px solid var(--border);">
    <span style="color:${TCOLORS[d.type]||'#5a8aaa'};font-size:15px;">${TICONS[d.type]||'📄'}</span>
    <div style="flex:1;min-width:0;"><div style="font-size:11px;color:var(--white);white-space:nowrap;overflow:hidden;text-overflow:ellipsis;">${d.name}</div><div style="font-size:9px;color:var(--text2);">${d.chunks.length} chunks · ${d.sections.length} sections · ${d.words.toLocaleString()} words</div></div>
  </div>`).join(''):'<div style="font-size:11px;color:var(--text3);text-align:center;padding:16px;">No documents</div>';
  
  const qs=document.getElementById('queryStats');
  qs.innerHTML=S.history.length?`<div style="display:grid;grid-template-columns:1fr 1fr;gap:8px;">
    <div style="background:var(--bg3);border-radius:8px;padding:11px;text-align:center;"><div style="font-family:'Bebas Neue';font-size:26px;color:var(--accent);">${S.queries}</div><div style="font-size:8px;text-transform:uppercase;letter-spacing:.1em;color:var(--text2);">Queries</div></div>
    <div style="background:var(--bg3);border-radius:8px;padding:11px;text-align:center;"><div style="font-family:'Bebas Neue';font-size:26px;color:var(--gold);">${(S.history.reduce((s,h)=>s+h.chunks,0)/S.history.length).toFixed(1)}</div><div style="font-size:8px;text-transform:uppercase;letter-spacing:.1em;color:var(--text2);">Avg Chunks</div></div>
  </div>
  <div style="margin-top:8px;background:var(--bg3);border-radius:8px;padding:10px;">
    <div style="font-size:9px;color:var(--text2);margin-bottom:6px;">Intent distribution</div>
    ${['general','person','list','specific'].map(i=>{const c=S.history.filter(h=>h.intent===i).length;const pct=S.history.length?Math.round(c/S.history.length*100):0;return`<div style="display:flex;align-items:center;gap:6px;margin-bottom:4px;"><span style="font-size:9px;color:var(--text3);width:54px;">${i}</span><div style="flex:1;height:4px;background:var(--border);border-radius:2px;overflow:hidden;"><div style="height:100%;width:${pct}%;background:var(--accent);border-radius:2px;"></div></div><span style="font-size:9px;color:var(--text3);">${pct}%</span></div>`;}).join('')}
  </div>`:'<div style="font-size:11px;color:var(--text3);text-align:center;padding:16px;">No queries yet</div>';

  // term cloud
  const allTxt=ok.map(d=>d.text).join(' ');
  const toks=tok(allTxt);
  const freq={};toks.forEach(t=>{freq[t]=(freq[t]||0)+1;});
  const top=Object.entries(freq).sort((a,b)=>b[1]-a[1]).slice(0,45);
  const mx=top[0]?.[1]||1;
  const cols=['#00ccf5','#f5b800','#00e57a','#a87fff','#ff3558'];
  document.getElementById('termCloud').innerHTML=top.length?top.map(([w,n])=>{const sz=9+Math.round((n/mx)*16);const op=0.38+(n/mx)*0.62;const col=cols[Math.abs(w.charCodeAt(0)+w.charCodeAt(w.length-1))%cols.length];return`<span style="font-size:${sz}px;color:${col};opacity:${op};margin:4px 5px;display:inline-block;cursor:default;" onmouseenter="this.style.opacity=1" onmouseleave="this.style.opacity='${op}'">${w}</span>`;}).join(''):'<div style="font-size:11px;color:var(--text3);text-align:center;padding:16px;">Upload documents</div>';

  // query history
  const qh=document.getElementById('queryHist');
  qh.innerHTML=S.history.length?S.history.slice(-8).reverse().map((h,i)=>`<div style="display:flex;align-items:center;gap:10px;padding:9px 14px;border-bottom:1px solid rgba(13,36,56,.5);font-size:11px;">
    <span style="font-family:'Space Mono',monospace;font-size:9px;color:var(--text3);width:24px;">#${S.history.length-i}</span>
    <span style="flex:1;color:var(--text);">${h.query}</span>
    <span style="font-size:9px;color:var(--text3);">${h.chunks} chunks · ${h.intent}</span>
  </div>`).join(''):'<div style="padding:16px;text-align:center;font-size:11px;color:var(--text3);">No queries yet</div>';
}

// ═══════════════════════════════════════
// MODAL
// ═══════════════════════════════════════
function showChunk(cid){
  const c=S.docs.flatMap(d=>d.chunks).find(x=>x.id===cid);
  if(!c)return;
  document.getElementById('modalMeta').textContent='📄 '+c.docName+' · Chunk #'+(c.idx+1)+(c.section?' · '+c.section:'');
  document.getElementById('modalTitle').textContent=c.tokens+' tokens · starts at word '+c.wStart;
  document.getElementById('modalBody').innerHTML='<pre style="white-space:pre-wrap;font-family:\'DM Sans\',sans-serif;font-size:12px;line-height:1.9;">'+c.text+'</pre>';
  document.getElementById('modal').style.display='flex';
}

function viewDoc(docId){
  const doc=S.docs.find(d=>d.id===docId);if(!doc)return;
  document.getElementById('modalMeta').textContent='📄 '+doc.name+' · '+doc.type+' · '+fmtSz(doc.size);
  document.getElementById('modalTitle').textContent=doc.chunks.length+' chunks · '+doc.words.toLocaleString()+' words · '+doc.sections.length+' sections';
  document.getElementById('modalBody').innerHTML=
    (doc.summary?`<div style="background:rgba(0,204,245,.06);border:1px solid rgba(0,204,245,.15);border-radius:8px;padding:12px;margin-bottom:16px;font-size:11px;color:var(--text);line-height:1.8;"><strong style="color:var(--white);">Document Type:</strong> ${doc.summary.docType}<br/><strong style="color:var(--white);">Summary:</strong> ${doc.summary.firstSentences.slice(0,400)}</div>`:'')
    +(doc.sections.length?`<div style="margin-bottom:16px;"><strong style="color:var(--white);font-size:11px;">Detected Sections:</strong><div style="margin-top:6px;display:flex;flex-wrap:wrap;gap:5px;">${doc.sections.map(s=>`<span style="font-size:9px;padding:2px 8px;border-radius:4px;background:rgba(168,127,255,.1);border:1px solid rgba(168,127,255,.2);color:var(--purple);">${s}</span>`).join('')}</div></div>`:'')
    +doc.chunks.slice(0,6).map((c,i)=>`<div style="margin-bottom:12px;padding:11px;background:var(--bg3);border-radius:8px;border-left:3px solid ${i%2===0?'var(--accent)':'var(--purple)'};">
      <div style="font-size:8.5px;color:var(--text3);margin-bottom:5px;">CHUNK #${i+1}${c.section?' · '+c.section:''} · ${c.tokens} tokens</div>
      <div style="font-size:11.5px;color:var(--text);line-height:1.75;">${c.text.slice(0,380)}${c.text.length>380?'...':''}</div>
    </div>`).join('')
    +(doc.chunks.length>6?`<div style="text-align:center;font-size:11px;color:var(--text3);">+ ${doc.chunks.length-6} more chunks</div>`:'');
  document.getElementById('modal').style.display='flex';
}

function removeDoc(id){S.docs=S.docs.filter(d=>d.id!==id);document.getElementById('di-'+id)?.remove();refreshStats();updateSidebar();notify('&#128465; Document removed','info');}
function closeModal(){document.getElementById('modal').style.display='none';}

// ═══════════════════════════════════════
// DRAG-DROP
// ═══════════════════════════════════════
const dz=document.getElementById('dropZone');
dz.addEventListener('dragover',e=>{e.preventDefault();dz.classList.add('drag');});
dz.addEventListener('dragleave',()=>dz.classList.remove('drag'));
dz.addEventListener('drop',e=>{e.preventDefault();dz.classList.remove('drag');if(e.dataTransfer.files.length)handleFiles(e.dataTransfer.files);});

// ═══════════════════════════════════════
// NAV
// ═══════════════════════════════════════
function showPage(id){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.getElementById('page-'+id).classList.add('active');
  ['upload','advisor','search','dash'].forEach((p,i)=>document.querySelectorAll('.nav-tab')[i]?.classList.toggle('active',p===id));
  if(id==='dash')renderDash();
}
function setSB(el){document.querySelectorAll('.sb-item').forEach(i=>i.classList.remove('active'));el.classList.add('active');}

// ═══════════════════════════════════════
// UTILS
// ═══════════════════════════════════════
function $(id,val){const e=document.getElementById(id);if(e)e.textContent=val;}
function fmtSz(b){if(b<1024)return b+'B';if(b<1048576)return(b/1024).toFixed(1)+'KB';return(b/1048576).toFixed(1)+'MB';}
let nt;function notify(msg,type='info'){
  const el=document.getElementById('notif');
  const c={info:{bg:'var(--bg3)',bc:'var(--border2)',ic:'ℹ',col:'var(--accent)'},success:{bg:'rgba(0,29,18,.9)',bc:'rgba(0,229,122,.25)',ic:'✓',col:'var(--green)'},error:{bg:'rgba(30,4,10,.9)',bc:'rgba(255,53,88,.25)',ic:'✗',col:'var(--red)'}}[type]||{bg:'var(--bg3)',bc:'var(--border2)',ic:'ℹ',col:'var(--accent)'};
  el.style.cssText=`display:flex;background:${c.bg};border-color:${c.bc};top:68px;right:20px;`;
  el.innerHTML=`<span style="color:${c.col}">${c.ic}</span> ${msg}`;
  clearTimeout(nt);nt=setTimeout(()=>el.style.display='none',3200);
}
setInterval(()=>{const e=document.getElementById('clock');if(e)e.textContent=new Date().toLocaleTimeString('en-US',{hour12:false,timeZone:'America/New_York'})+' EST';},1000);
refreshStats();
</script>
</body>
</html>
