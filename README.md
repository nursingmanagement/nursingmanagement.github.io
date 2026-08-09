<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>B.Sc. Nursing VI Semester · NMLE 330 PYQ Tracker & Syllabus</title>
<style>
:root{
  --bg:#EEF2EE;
  --bg-grad:#E5EEE9;
  --surface:#FFFFFF;
  --surface-2:#F7F9F6;
  --ink:#16211D;
  --ink-dim:#4B5B54;
  --ink-faint:#7C8B83;
  --line:#DCE5DE;

  --primary:#145C52;
  --primary-container:#D6EFE7;
  --on-primary-container:#0B332C;
  --secondary:#B8722A;
  --secondary-container:#F5E1C4;
  --on-secondary-container:#4A2F0B;
  --tertiary:#4B3F72;
  --tertiary-container:#E4DEF3;
  --on-tertiary-container:#241C43;

  --tier1:#9C2B2B;
  --tier1-c:#F6DCDA;
  --tier2:#B8722A;
  --tier2-c:#F5E1C4;
  --tier3:#2F7A68;
  --tier3-c:#D9EFE8;

  --ans-bg:#D1F2D9;
  --ans-border:#288A43;
  --ans-text:#0C401C;

  --shadow-1:0 1px 2px rgba(20,40,32,.08),0 1px 8px rgba(20,40,32,.06);
  --shadow-2:0 4px 14px rgba(20,40,32,.10),0 2px 4px rgba(20,40,32,.08);
  --radius-lg:24px;
  --radius-md:18px;
  --radius-sm:12px;

  --font-display:"Iowan Old Style","Palatino Linotype",Palatino,Georgia,serif;
  --font-body:-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
  --font-mono:"SFMono-Regular",Consolas,"Liberation Mono",Menlo,monospace;
}
html[data-theme="dark"]{
  --bg:#0E1613;
  --bg-grad:#0A100E;
  --surface:#17211D;
  --surface-2:#1D2823;
  --ink:#E8F0EC;
  --ink-dim:#AEC0B7;
  --ink-faint:#7E948A;
  --line:#2A3A33;

  --primary:#6FCDB8;
  --primary-container:#123B34;
  --on-primary-container:#BEEBDF;
  --secondary:#E3A85C;
  --secondary-container:#43300F;
  --on-secondary-container:#F3DBAE;
  --tertiary:#B6A8E8;
  --tertiary-container:#332A54;
  --on-tertiary-container:#E4DEF3;

  --tier1:#E37A72;
  --tier1-c:#3E1C1B;
  --tier2:#E3A85C;
  --tier2-c:#3E2C10;
  --tier3:#6FCDB8;
  --tier3-c:#12332C;

  --ans-bg:#10381E;
  --ans-border:#42BA6A;
  --ans-text:#A8F2BE;

  --shadow-1:0 1px 2px rgba(0,0,0,.35),0 1px 8px rgba(0,0,0,.3);
  --shadow-2:0 4px 16px rgba(0,0,0,.45),0 2px 6px rgba(0,0,0,.35);
}

*{box-sizing:border-box;}
html,body{margin:0;padding:0;}
body{
  background:
    radial-gradient(1200px 600px at 8% -10%, var(--bg-grad), transparent 60%),
    var(--bg);
  color:var(--ink);
  font-family:var(--font-body);
  line-height:1.5;
  min-height:100vh;
  padding-bottom:110px; /* Safe padding for bottom tab bar */
}
@media (prefers-reduced-motion: reduce){
  *{animation-duration:.001ms !important; transition-duration:.001ms !important;}
}
:focus-visible{outline:3px solid var(--primary); outline-offset:2px; border-radius:6px;}

.wrap{max-width:1180px; margin:0 auto; padding:0 20px;}

/* ---------- HEADER ---------- */
header.top{padding:24px 0 10px;}
.top-row{display:flex; align-items:flex-start; justify-content:space-between; gap:16px; flex-wrap:wrap;}
.brand{display:flex; align-items:center; gap:14px;}
.brand-mark{
  width:52px; height:52px; border-radius:16px;
  background:linear-gradient(155deg, var(--primary), #0B332C);
  display:flex; align-items:center; justify-content:center;
  box-shadow:var(--shadow-2);
  flex-shrink:0;
}
.brand-mark svg{width:30px; height:30px;}
.brand-text h1{
  font-family:var(--font-display);
  font-size:25px; margin:0 0 2px; font-weight:700; letter-spacing:.2px;
}
.brand-text p{margin:0; color:var(--ink-dim); font-size:13px;}
.brand-text .code{font-family:var(--font-mono); color:var(--primary); font-weight:600;}

.header-actions{display:flex; gap:10px; align-items:center;}
.icon-btn{
  border:1px solid var(--line); background:var(--surface); color:var(--ink);
  width:44px; height:44px; border-radius:14px; display:flex; align-items:center; justify-content:center;
  cursor:pointer; box-shadow:var(--shadow-1); transition:transform .15s ease, background .15s ease;
  touch-action:manipulation;
}
.icon-btn:hover{transform:translateY(-1px);}
.icon-btn:active{transform:scale(.94);}
.icon-btn svg{width:20px; height:20px;}

/* pulse divider */
.pulse-divider{width:100%; height:24px; margin:14px 0 6px; opacity:.85;}
.pulse-divider path{fill:none; stroke:var(--primary); stroke-width:2; stroke-linecap:round; stroke-linejoin:round;}
html[data-theme="dark"] .pulse-divider path{stroke:var(--primary);}

/* ---------- HERO / PROGRESS ---------- */
.hero{
  display:grid; grid-template-columns:auto 1fr; gap:26px; align-items:center;
  background:var(--surface); border:1px solid var(--line); border-radius:var(--radius-lg);
  padding:22px 26px; box-shadow:var(--shadow-2); margin-top:8px; margin-bottom:20px;
}
@media (max-width:640px){ .hero{grid-template-columns:1fr; text-align:center;} }

.ring-wrap{position:relative; width:132px; height:132px; margin:0 auto;}
.ring-wrap svg{transform:rotate(-90deg);}
.ring-bg{fill:none; stroke:var(--line); stroke-width:11;}
.ring-fg{fill:none; stroke:var(--primary); stroke-width:11; stroke-linecap:round; transition:stroke-dashoffset .5s ease;}
.ring-center{position:absolute; inset:0; display:flex; flex-direction:column; align-items:center; justify-content:center;}
.ring-center .num{font-family:var(--font-display); font-size:30px; font-weight:700; line-height:1;}
.ring-center .lbl{font-size:10.5px; color:var(--ink-faint); text-transform:uppercase; letter-spacing:.08em; margin-top:2px;}

.hero-info h2{font-family:var(--font-display); font-size:19px; margin:0 0 6px;}
.hero-info p{margin:0 0 12px; color:var(--ink-dim); font-size:14px; max-width:60ch;}
.hero-stats{display:flex; gap:22px; flex-wrap:wrap;}
.hero-stat .n{font-family:var(--font-mono); font-weight:700; font-size:17px; color:var(--primary);}
.hero-stat .l{font-size:11.5px; color:var(--ink-faint); text-transform:uppercase; letter-spacing:.06em;}

/* ---------- HOME DASHBOARD QUICK LAUNCH GRID ---------- */
.section-heading{
  font-family:var(--font-display); font-size:19px; margin:24px 0 12px;
  display:flex; align-items:center; justify-content:space-between;
}
.section-heading span{font-family:var(--font-mono); font-size:12px; color:var(--ink-faint); font-weight:600;}
.launch-grid{
  display:grid; grid-template-columns:repeat(auto-fill,minmax(250px,1fr)); gap:14px; margin-bottom:24px;
}
.launch-card{
  background:var(--surface); border:1px solid var(--line); border-radius:var(--radius-md);
  padding:16px 18px; box-shadow:var(--shadow-1); cursor:pointer;
  display:flex; align-items:flex-start; justify-content:space-between; gap:12px;
  transition:transform .15s ease, box-shadow .15s ease, border-color .15s ease;
  touch-action:manipulation; text-decoration:none; color:inherit;
}
.launch-card:hover{transform:translateY(-2px); box-shadow:var(--shadow-2); border-color:var(--primary);}
.launch-card-info h4{margin:0 0 4px; font-family:var(--font-display); font-size:16px; color:var(--ink);}
.launch-card-info p{margin:0; font-size:12.5px; color:var(--ink-dim); line-height:1.4;}
.launch-card .ic{
  width:40px; height:40px; border-radius:12px; background:var(--primary-container);
  color:var(--on-primary-container); display:flex; align-items:center; justify-content:center; flex-shrink:0;
}
.launch-card .ic svg{width:20px; height:20px;}

/* ---------- SUB-NAVIGATION PILL BAR (PYQ BANK) ---------- */
.sub-nav{
  display:flex; flex-wrap:nowrap; gap:8px; margin:16px 0 20px; overflow-x:auto; padding-bottom:4px;
  -webkit-overflow-scrolling:touch; scrollbar-width:thin;
}
.sub-tab{
  flex-shrink:0; cursor:pointer; user-select:none; white-space:nowrap;
  padding:10px 18px; border-radius:100px; font-size:13px; font-weight:600;
  background:var(--surface); border:1px solid var(--line); color:var(--ink-dim);
  display:flex; align-items:center; gap:8px; transition:all .15s ease;
  touch-action:manipulation;
}
.sub-tab:hover{border-color:var(--primary); color:var(--ink);}
.sub-tab.active{background:var(--primary); border-color:var(--primary); color:#fff; box-shadow:var(--shadow-1);}

/* ---------- CONTROLS ROW ---------- */
.controls{
  display:flex; flex-wrap:wrap; gap:10px; align-items:center; margin-bottom:18px;
}
.search-box{
  flex:1 1 240px; position:relative; display:flex; align-items:center;
  background:var(--surface); border:1px solid var(--line); border-radius:14px;
  padding:0 14px; box-shadow:var(--shadow-1);
}
.search-box svg{width:17px; height:17px; color:var(--ink-faint); flex-shrink:0;}
.search-box input{
  border:none; outline:none; background:transparent; padding:11px 10px; font-size:14px;
  width:100%; color:var(--ink); font-family:var(--font-body);
}
.chip{
  border:1px solid var(--line); background:var(--surface); color:var(--ink-dim);
  padding:8px 14px; border-radius:100px; font-size:12.5px; font-weight:600; cursor:pointer;
  display:flex; align-items:center; gap:6px; transition:all .15s ease; white-space:nowrap;
  touch-action:manipulation; user-select:none;
}
.chip:hover{border-color:var(--primary);}
.chip.active{background:var(--primary); border-color:var(--primary); color:#fff;}
.chip .sw{width:8px; height:8px; border-radius:50%;}
.toggle-row{display:flex; align-items:center; gap:8px; font-size:12.5px; color:var(--ink-dim); font-weight:600; cursor:pointer; user-select:none;}
.switch{width:36px; height:20px; border-radius:100px; background:var(--line); position:relative; transition:background .2s;}
.switch::after{content:""; position:absolute; width:16px; height:16px; border-radius:50%; background:#fff; top:2px; left:2px; transition:left .2s; box-shadow:0 1px 3px rgba(0,0,0,.3);}
.switch.on{background:var(--primary);}
.switch.on::after{left:18px;}

/* ---------- CALLOUT (comparison pairs) ---------- */
.callout{
  background:linear-gradient(135deg, var(--tertiary-container), var(--surface));
  border:1px solid var(--line); border-radius:var(--radius-md);
  padding:18px 20px; margin-bottom:20px; box-shadow:var(--shadow-1);
}
.callout-head{display:flex; align-items:center; gap:10px; margin-bottom:10px;}
.callout-head .ic{width:34px; height:34px; border-radius:10px; background:var(--tertiary); color:#fff; display:flex; align-items:center; justify-content:center; flex-shrink:0;}
.callout-head .ic svg{width:18px; height:18px;}
.callout-head h3{margin:0; font-family:var(--font-display); font-size:16px; color:var(--on-tertiary-container);}
.callout-head p{margin:2px 0 0; font-size:12px; color:var(--ink-dim);}
.pairs{display:grid; grid-template-columns:repeat(auto-fill,minmax(230px,1fr)); gap:8px;}
.pair{
  background:var(--surface); border:1px solid var(--line); border-radius:10px; padding:9px 12px;
  font-size:12.8px; display:flex; align-items:center; gap:8px;
}
.pair b{color:var(--primary); font-weight:700;}
.pair .vs{color:var(--ink-faint); font-family:var(--font-mono); font-size:11px;}

/* ---------- TIER SECTION ---------- */
.tier-section{margin-bottom:30px;}
.tier-header{display:flex; align-items:center; gap:12px; margin-bottom:14px;}
.tier-badge{
  font-family:var(--font-mono); font-size:11px; font-weight:700; letter-spacing:.05em;
  padding:5px 12px; border-radius:100px; text-transform:uppercase;
}
.tier-header h3{font-family:var(--font-display); font-size:17px; margin:0; flex-shrink:0;}
.tier-header .sub{font-size:12px; color:var(--ink-faint); margin-left:2px;}
.tier-bar-track{flex:1; height:6px; border-radius:4px; background:var(--line); overflow:hidden; min-width:60px;}
.tier-bar-fill{height:100%; border-radius:4px; transition:width .4s ease;}
.tier-pct{font-family:var(--font-mono); font-size:12px; font-weight:700; flex-shrink:0; width:38px; text-align:right;}

.grid{display:grid; grid-template-columns:repeat(auto-fill,minmax(280px,1fr)); gap:14px;}

/* ---------- CARD ---------- */
.card{
  background:var(--surface); border:1px solid var(--line); border-radius:var(--radius-md);
  padding:16px; box-shadow:var(--shadow-1); position:relative; overflow:hidden;
  transition:transform .15s ease, box-shadow .15s ease;
  display:flex; flex-direction:column; justify-content:space-between;
}
.card:hover{box-shadow:var(--shadow-2); transform:translateY(-2px);}
.card.done{opacity:.6;}
.card-top{display:flex; align-items:flex-start; gap:12px; margin-bottom:10px;}
.card-icon{
  width:44px; height:44px; border-radius:14px; flex-shrink:0;
  display:flex; align-items:center; justify-content:center; font-weight:700; font-size:15px;
  font-family:var(--font-mono);
}
.card-title-wrap{flex:1; min-width:0;}
.card-title{font-family:var(--font-display); font-size:15.5px; font-weight:700; margin:0 0 4px; line-height:1.3;}
.card.done .card-title{text-decoration:line-through; text-decoration-color:var(--ink-faint);}
.freq-badge{
  display:inline-flex; align-items:center; gap:5px; font-family:var(--font-mono);
  font-size:10.5px; font-weight:700; padding:3px 9px; border-radius:100px;
}
.card-years{font-size:10.5px; color:var(--ink-faint); margin-top:5px; font-family:var(--font-mono);}
.card-points{margin:8px 0 12px; padding-left:18px; font-size:12.8px; color:var(--ink-dim);}
.card-points li{margin-bottom:4px;}
.card-actions{display:flex; justify-content:flex-end; margin-top:12px;}

/* 100% Reliable Mark Button */
.mark-btn{
  border:1.5px solid var(--primary); background:transparent; color:var(--primary);
  padding:7px 14px; border-radius:100px; font-size:12px; font-weight:700; cursor:pointer;
  display:flex; align-items:center; gap:6px; transition:all .12s ease;
  touch-action:manipulation; user-select:none;
}
.mark-btn * { pointer-events: none; }
.mark-btn svg{width:14px; height:14px;}
.mark-btn.on{background:var(--primary); color:#fff;}
.mark-btn:active{transform:scale(.93);}
@keyframes pop{0%{transform:scale(1);}45%{transform:scale(.88);}100%{transform:scale(1);}}
.mark-btn.pulse{animation:pop .28s ease;}

/* ---------- MCQ HIGHLIGHT STYLES ---------- */
.mcq-options{
  list-style:none; padding:0; margin:10px 0; display:grid; gap:6px; font-size:13px;
}
.mcq-opt{
  padding:7px 11px; border-radius:8px; background:var(--surface-2);
  border:1px solid var(--line); color:var(--ink-dim);
}
.mcq-opt.correct{
  background:var(--ans-bg); border-color:var(--ans-border);
  color:var(--ans-text); font-weight:700;
  display:flex; align-items:center; justify-content:space-between;
}
.mcq-opt.correct::after{
  content:"✓ Correct Answer"; font-family:var(--font-mono); font-size:11px;
  background:var(--ans-border); color:#fff; padding:2px 7px; border-radius:100px;
}

/* ---------- STUDY PLAN (48 HOURS SPRINT) ---------- */
.stepper{position:relative; margin:10px 0 0; padding-left:34px;}
.step{position:relative; padding-bottom:26px;}
.step:last-child{padding-bottom:0;}
.step::before{
  content:""; position:absolute; left:-34px; top:28px; bottom:-4px; width:2px; background:var(--line);
}
.step:last-child::before{display:none;}
.step-num{
  position:absolute; left:-46px; top:0; width:28px; height:28px; border-radius:50%;
  background:var(--primary); color:#fff; display:flex; align-items:center; justify-content:center;
  font-family:var(--font-mono); font-weight:700; font-size:12.5px; box-shadow:var(--shadow-1);
}
.step-card{background:var(--surface); border:1px solid var(--line); border-radius:var(--radius-sm); padding:16px 18px; box-shadow:var(--shadow-1);}
.step-card h4{margin:0 0 6px; font-family:var(--font-display); font-size:16px; color:var(--primary);}
.step-card .date-tag{font-family:var(--font-mono); font-size:11px; font-weight:700; color:var(--secondary); text-transform:uppercase; margin-bottom:4px; display:block;}
.step-card p{margin:0; font-size:13.5px; color:var(--ink-dim); line-height:1.6;}

/* ---------- YEAR ARCHIVE ---------- */
.year-picker{
  display:flex; flex-wrap:nowrap; gap:8px; overflow-x:auto; padding:4px 2px 14px;
  -webkit-overflow-scrolling:touch;
}
.year-chip{
  flex-shrink:0; font-family:var(--font-mono); font-weight:700; font-size:13px; white-space:nowrap;
  padding:10px 16px; border-radius:12px; border:1px solid var(--line); background:var(--surface);
  cursor:pointer; color:var(--ink-dim); transition:all .15s ease; text-align:center; min-width:84px;
  touch-action:manipulation; user-select:none;
}
.year-chip .yr{display:block; font-size:14px;}
.year-chip .mo{display:block; font-size:9.5px; font-weight:600; letter-spacing:.05em; opacity:.7; margin-top:2px;}
.year-chip.active{background:var(--primary); border-color:var(--primary); color:#fff;}
.year-chip:hover{border-color:var(--primary);}

.year-paper{background:var(--surface); border:1px solid var(--line); border-radius:var(--radius-lg); padding:22px 24px; box-shadow:var(--shadow-2);}
.year-paper-head{border-bottom:1px dashed var(--line); padding-bottom:14px; margin-bottom:18px;}
.year-paper-head .tag{font-family:var(--font-mono); font-size:11px; color:var(--primary); font-weight:700; letter-spacing:.06em;}
.year-paper-head h3{font-family:var(--font-display); font-size:19px; margin:6px 0 3px;}
.year-paper-head p{margin:0; font-size:12.5px; color:var(--ink-faint);}

.paper-section{margin-bottom:24px;}
.paper-section:last-child{margin-bottom:0;}
.paper-section-title{
  display:flex; align-items:center; gap:8px; font-family:var(--font-mono); font-size:12px;
  font-weight:700; text-transform:uppercase; letter-spacing:.06em; color:var(--ink-dim);
  margin-bottom:12px; padding-bottom:6px; border-bottom:1px solid var(--line);
}
.paper-section-title .n{background:var(--secondary-container); color:var(--on-secondary-container); border-radius:100px; padding:2px 9px; font-size:10.5px;}
.q-list{list-style:none; margin:0; padding:0; counter-reset:qnum;}
.q-list li{
  counter-increment:qnum; position:relative; padding:12px 0 12px 32px; font-size:14px; line-height:1.55;
  border-bottom:1px solid var(--line);
}
.q-list li:last-child{border-bottom:none;}
.q-list li::before{
  content:counter(qnum); position:absolute; left:0; top:12px; width:22px; height:22px; border-radius:7px;
  background:var(--primary-container); color:var(--on-primary-container); font-family:var(--font-mono);
  font-size:11px; font-weight:700; display:flex; align-items:center; justify-content:center;
}
.q-empty{font-size:13px; color:var(--ink-faint); font-style:italic; padding:6px 0;}

/* ---------- SYLLABUS TAB ---------- */
.syl-unit{
  background:var(--surface); border:1px solid var(--line); border-radius:var(--radius-md);
  margin-bottom:16px; overflow:hidden; box-shadow:var(--shadow-1);
}
.syl-unit-head{
  padding:14px 18px; background:var(--surface-2); border-bottom:1px solid var(--line);
  display:flex; align-items:center; justify-content:space-between; flex-wrap:wrap; gap:10px;
}
.syl-unit-head h3{margin:0; font-family:var(--font-display); font-size:16px; color:var(--primary);}
.syl-unit-head .syl-tag{font-family:var(--font-mono); font-size:11px; font-weight:700; background:var(--primary-container); color:var(--on-primary-container); padding:3px 10px; border-radius:100px;}
.syl-body{padding:16px 18px; display:grid; grid-template-columns:1fr 1fr; gap:20px;}
@media (max-width:768px){ .syl-body{grid-template-columns:1fr;} }
.syl-topics h4, .syl-pyqs h4{
  font-family:var(--font-mono); font-size:12px; text-transform:uppercase; letter-spacing:.05em;
  color:var(--ink-faint); margin:0 0 8px; border-bottom:1px solid var(--line); padding-bottom:4px;
}
.syl-topics ul{margin:0; padding-left:18px; font-size:13px; color:var(--ink-dim);}
.syl-topics li{margin-bottom:5px;}
.syl-pyq-item{
  font-size:13px; padding:8px 10px; background:var(--surface-2); border:1px solid var(--line);
  border-radius:8px; margin-bottom:6px; display:flex; justify-content:space-between; align-items:flex-start; gap:8px;
}
.syl-pyq-item b{color:var(--primary); font-size:11.5px; font-family:var(--font-mono);}

/* ---------- FOOTER BANNER ---------- */
.footer-banner{
  margin-top:30px; border-radius:var(--radius-lg); padding:22px 26px;
  background:linear-gradient(120deg, var(--primary-container), var(--secondary-container));
  border:1px solid var(--line); box-shadow:var(--shadow-2);
  display:flex; align-items:center; gap:16px; justify-content:space-between; flex-wrap:wrap;
}
.footer-banner .msg{font-family:var(--font-display); font-size:16px; color:var(--on-primary-container); max-width:60ch;}
.footer-banner .msg strong{color:var(--primary);}
.footer-actions{display:flex; gap:10px; flex-wrap:wrap;}
.btn-ghost{
  border:1px solid var(--line); background:var(--surface); color:var(--ink);
  padding:9px 16px; border-radius:100px; font-size:12.5px; font-weight:700; cursor:pointer;
  display:flex; align-items:center; gap:6px; touch-action:manipulation;
}
.btn-ghost svg{width:15px; height:15px;}
.btn-ghost:hover{border-color:var(--primary); color:var(--primary);}

.empty-state{text-align:center; padding:60px 20px; color:var(--ink-faint);}
.empty-state svg{width:44px; height:44px; margin-bottom:10px; opacity:.5;}

.streak-pill{
  display:inline-flex; align-items:center; gap:6px; font-family:var(--font-mono); font-size:11.5px;
  font-weight:700; color:var(--secondary); background:var(--secondary-container); padding:5px 11px; border-radius:100px;
}

/* ============================= BOTTOM APP BAR ============================= */
.bottom-nav{
  position:fixed; bottom:0; left:0; right:0; z-index:1000;
  background:var(--surface); border-top:1px solid var(--line);
  box-shadow:0 -4px 18px rgba(0,0,0,0.08);
  display:flex; justify-content:space-around; align-items:center;
  padding:8px 12px; padding-bottom:max(8px, env(safe-area-inset-bottom));
  height:72px;
}
.b-tab{
  flex:1; display:flex; flex-direction:column; align-items:center; justify-content:center;
  gap:4px; cursor:pointer; color:var(--ink-faint); font-size:11px; font-weight:600;
  transition:color .15s ease, transform .1s ease;
  touch-action:manipulation; user-select:none;
}
.b-tab svg{width:22px; height:22px; stroke-width:2;}
.b-tab.active{color:var(--primary); font-weight:700;}
.b-tab.active svg{stroke-width:2.5;}
.b-tab:active{transform:scale(.92);}

@media (min-width:768px){
  .bottom-nav{
    max-width:720px; left:50%; right:auto; transform:translateX(-50%);
    bottom:16px; border:1px solid var(--line); border-radius:100px;
    box-shadow:var(--shadow-2); height:66px; padding:6px 20px;
  }
}

@media (max-width:560px){
  .brand-text h1{font-size:20px;}
  .hero{padding:18px;}
  .year-paper{padding:18px 16px;}
  .launch-grid{grid-template-columns:1fr;}
}
</style>
</head>
<body>
<div class="wrap">

  <header class="top">
    <div class="top-row">
      <div class="brand">
        <div class="brand-mark">
          <svg viewBox="0 0 24 24" fill="none" stroke="#fff" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 12h4l2 8 4-16 2 8h6"/></svg>
        </div>
        <div class="brand-text">
          <h1>B.Sc. Nursing VI Semester</h1>
          <p>Nursing Management &amp; Leadership PYQ Tracker &middot; <span class="code">GBU ALL</span></p>
        </div>
      </div>
      <div class="header-actions">
        <span class="streak-pill" id="streakPill">🔥 1 day streak</span>
        <button class="icon-btn" id="themeToggle" title="Toggle dark mode" aria-label="Toggle dark mode" type="button">
          <svg id="themeIcon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="4"/><path d="M12 2v2M12 20v2M4.9 4.9l1.4 1.4M17.7 17.7l1.4 1.4M2 12h2M20 12h2M4.9 19.1l1.4-1.4M17.7 6.3l1.4-1.4"/></svg>
        </button>
      </div>
    </div>

    <svg class="pulse-divider" viewBox="0 0 600 26" preserveAspectRatio="none">
      <path d="M0 13 H220 L232 4 L244 22 L256 8 L268 18 L280 13 H600"/>
    </svg>
  </header>

  <div id="mainArea"></div>

  <div class="footer-banner">
    <div class="msg" id="footerMsg">Start with <strong>Tier 1 — High Yield</strong> in Long Essay — those topics have shown up 3–4 times since 2009.</div>
    <div class="footer-actions">
      <button class="btn-ghost" id="exportBtn" type="button"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 3v12M7 10l5 5 5-5M4 21h16"/></svg>Export progress</button>
      <button class="btn-ghost" id="importBtn" type="button"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 21V9M7 14l5-5 5 5M4 3h16"/></svg>Import</button>
      <input type="file" id="importFile" accept="application/json" style="display:none">
      <button class="btn-ghost" id="resetBtn" type="button"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 12a9 9 0 1 0 3-6.7M3 4v6h6"/></svg>Reset progress</button>
    </div>
  </div>

</div>

<!-- Fixed Bottom Navigation Bar -->
<nav class="bottom-nav" id="bottomNav">
  <div class="b-tab active" data-tab="home" id="btnHome">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg>
    <span>Home</span>
  </div>
  <div class="b-tab" data-tab="pyq" id="btnPyq">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6M9 13h6M9 17h6M9 9h1"/></svg>
    <span>PYQ Bank</span>
  </div>
  <div class="b-tab" data-tab="syllabus" id="btnSyl">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor"><path d="M4 19.5v-15A2.5 2.5 0 0 1 6.5 2H20v20H6.5a2.5 2.5 0 0 1-2.5-2.5V19.5z"/><path d="M6 18h14"/></svg>
    <span>Syllabus</span>
  </div>
  <div class="b-tab" data-tab="sprint" id="btnSprint">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg>
    <span>48-Hr Sprint</span>
  </div>
  <div class="b-tab" data-tab="archive" id="btnArchive">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor"><path d="M21 8v13H3V8M1 3h22v5H1zM10 12h4"/></svg>
    <span>Archive</span>
  </div>
</nav>

<script>
/* ============================= SAFE STORAGE WRAPPER ============================= */
const STORAGE_KEY = "chart-rounds-nmle330-v1";
const memoryStore = {};

function safeGetItem(key) {
  try { return localStorage.getItem(key); }
  catch(e) { return memoryStore[key] || null; }
}
function safeSetItem(key, val) {
  try { localStorage.setItem(key, val); }
  catch(e) { memoryStore[key] = val; }
}

/* ============================= DATA ============================= */

const COMPARISON_PAIRS = [
  ["Autocratic", "Democratic Leadership"],
  ["Centralization", "Decentralization"],
  ["In-service Education", "Continuing Education"],
  ["Concurrent Audit", "Retrospective Audit"],
  ["Fixed Budget", "Flexible Budget"],
  ["PERT", "GANTT Chart"],
  ["Formal Communication", "Informal Communication"],
  ["Delegation", "Supervision"],
  ["Line Organization", "Staff Organization"],
  ["Functional Nursing", "Team Nursing"]
];

// ---- 48-Hour Exam Sprint (August 8 - 10) ----
const STUDY_PLAN = [
  {
    date: "Day 1 — Saturday, Aug 8 (Today)",
    title: "High-Yield Administration, HR & Finance Core",
    body: "Focus on the big-weight essay & short note topics: <strong>Management Principles & Process (Taylor/Fayol)</strong>, <strong>Faculty & Principal Responsibilities</strong>, <strong>Staffing / HRM (Recruitment to Promotion & INC Staffing Norms)</strong>, and <strong>Financial Management & College Budgeting (50 intake)</strong>. Clear all Tier 1 Essay and Short Note cards."
  },
  {
    date: "Day 2 — Sunday, Aug 9 (Tomorrow)",
    title: "Educational Setup, Legal Aspects & MCQ/Short Answer Sweep",
    body: "Master <strong>INC Educational Institution Norms (Physical & Academic facilities)</strong>, <strong>Curriculum Revision & Administrator Role</strong>, and essential legal topics: <strong>Consumer Protection Act</strong>, <strong>Legal Responsibilities / Malpractice</strong>, and <strong>Nursing Audit (Concurrent vs Retrospective)</strong>. Then drill through every Tier 1 & Tier 2 MCQ and Short Answer."
  },
  {
    date: "Exam Morning — Monday, Aug 10 (Exam Day)",
    title: "Final Quick-Fire Review & Year Archive Sweep",
    body: "Review the <strong>Comparison Pairs</strong> box, check numerical staffing formulas (250-bed calculation, ICU 1:1, General Ward 1:6, CHC 80,000 population), and read verbatim through the latest two papers (March 2026 & June/July 2026) in the Year Archive tab."
  }
];

function T(title, freq, years, points){ return {title, freq, years, points}; }

function TMCQ(title, freq, years, qText, options, answer, points=[]){
  return { title, freq, years, qText, options, answer, points };
}

const DATA = {
  essay: {
    label: "Long Essay",
    sub: "15 / 20 Marks",
    color: "primary",
    tiers: {
      1: [
        T("Faculty Recruitment & Principal's Responsibilities","4",["Aug 2009","Feb 2010","Aug 2011","Feb 2014"],
          ["Organization & control of school of nursing","Principal's role in faculty administration","Faculty recruitment procedure & criteria","Principles of staff counseling"]),
        T("Management Principles, Theories & Process","4",["Aug 2012","Feb 2013","Oct 2023","Mar 2026"],
          ["Definition & principles of management","Theories of management (Taylor, Fayol)","Steps in the management process","Apply each step to a healthcare example"]),
        T("Staffing, Recruitment & HRM","3",["Mar 2026","Jun 2026","Jul 2026"],
          ["HRM definition & scope","Recruitment–Selection–Deployment–Retention–Promotion","Staffing norms as per INC","Philosophy & objectives of staffing"]),
        T("Financial Management in Nursing Services","3",["Nov 2025","Mar 2026","Jul 2026"],
          ["Definition of financial management","Elements & functions","Principles & scope","Role in nursing college/service budgeting"]),
        T("Curriculum – Development, Revision & Evaluation","3",["Feb 2025","Oct 2025","Jun 2026"],
          ["Definition & types of curriculum","Steps in curriculum development/revision","Administrator's role in revision","Planning–implementation–evaluation cycle"])
      ],
      2: [
        T("Ward Management – Principles & Factors","2",["Feb 2009","Feb 2012"],
          ["Principles of good ward management","Factors affecting ward management"]),
        T("Clinical / Nursing Supervision","2",["Feb 2010","Feb 2013"],
          ["Functions of supervision","Principles & methods of clinical supervision"]),
        T("Community Health Supervisor – Qualities & Role","2",["Feb 2010","Feb 2014"],
          ["Qualities of a community health supervisor","Responsibilities in community settings"]),
        T("Budgeting","2",["Jun 2024","Nov 2025"],
          ["Definition & principles of budgeting","Types of budget","Nurse administrator's role in budget planning"]),
        T("Regulatory Bodies & Indian Nursing Council","2",["Oct 2025","Jun 2026"],
          ["Definition of regulatory bodies","Objectives, functions & committees of INC"]),
        T("In-Service Education & Staff Development","2",["Feb 2014","Feb 2025"],
          ["Ward teaching programme","In-service education for staff development"]),
        T("Professional Nurse – Characteristics & Philosophy","2",["Jun 2024","Nov 2025"],
          ["Characteristics of a professional nurse","Philosophy, aim & objectives of practice","Current trends & issues in nursing"])
      ],
      3: [
        T("Quality Nursing Care & Head Nurse Role","1",["Feb 2009"],["Definition of quality nursing care","Head nurse responsibilities in clinical care"]),
        T("Multi-Purpose Health Workers","1",["Aug 2011"],["Roles & functions"]),
        T("Patient Assignment Methods & Records/Reports","1",["Feb 2012"],["Methods of patient assignment","Records and reports in detail"]),
        T("Nursing Staff Requirement Calculation","1",["Aug 2012"],["Planning factors for staffing","Formula-based staff calculation, 250-bed hospital"]),
        T("Material Management Process","1",["Oct 2023"],["Definition","Steps in the material management process"]),
        T("Job Description of Nursing Personnel","1",["Oct 2023"],["Job description in a college of nursing"]),
        T("Planning & Nursing Care Planning","1",["Jun 2024"],["Definition & components of planning","Clinical nurse's role in patient-care planning"]),
        T("Emergency & Disaster Management","1",["Jul 2026"],["Nurse's role in emergency/disaster","Phases of disaster management"]),
        T("Physical & Academic Facilities per INC Norms","1",["Jun 2026"],["Facilities for 50-student intake","Staffing norms as per INC"])
      ]
    }
  },

  shortNotes: {
    label: "Short Notes",
    sub: "5 Marks each",
    color: "secondary",
    tiers: {
      1: [
        T("Nursing Audit","5",["Feb 2009","Feb 2012","Feb 2013","Mar 2026","Jul 2026"],["Definition & purposes","Concurrent vs retrospective audit","Steps in conducting an audit"]),
        T("Group Dynamics","5",["Aug 2011","Aug 2012","Feb 2014","Nov 2025","Mar 2026"],["Definition & characteristics","Stages of group development","Factors influencing group behaviour"]),
        T("Legal Aspects in Nursing","3",["Aug 2009","Aug 2011","Feb 2013"],["Legal responsibilities of a nurse","Consumer protection & malpractice","Documentation as legal evidence"]),
        T("In-Service Education","3",["Feb 2012","Mar 2026","Jul 2026"],["Purpose & importance","Techniques & methods","Role in professional development"]),
        T("Consumer Protection Act","3",["Oct 2023","Oct 2025","Jun 2026"],["Provisions relevant to healthcare","Patient rights","Application in nursing negligence"]),
        T("Inventory Control Methods","3",["Oct 2023","Nov 2025","Jul 2026"],["ABC / VED / FSN analysis","Stock control procedures"]),
        T("Faculty Development & Recruitment","3",["Aug 2012","Feb 2013","Jun 2026"],["Faculty development programme","Recruitment criteria","Faculty welfare measures"])
      ],
      2: [
        T("Performance Appraisal","2",["Nov 2025","Mar 2026"],["Purpose & methods"]),
        T("Collective Bargaining","2",["Jun 2024","Jun 2026"],["Definition & process"]),
        T("Material Management","2",["Aug 2012","Mar 2026"],["Scope in hospital setting"]),
        T("Budget & Types of Budgeting","2",["Aug 2012","Oct 2023"],["Classification of budget types"]),
        T("Leadership Styles","2",["Feb 2013","Jun 2026"],["Autocratic, democratic, laissez-faire"]),
        T("Principles of Adult Learning","2",["Feb 2025","Nov 2025"],["Andragogy principles"]),
        T("Resilience Building","2",["Nov 2025","Jul 2026"],["Strategies for personal resilience"]),
        T("Housekeeping in Ward/Hospital","2",["Aug 2009","Aug 2012"],["Standards & responsibilities"]),
        T("Five Year Plan","2",["Aug 2009","Feb 2014"],["Health planning milestones"]),
        T("Professional Organization – International Level","2",["Oct 2025","Jun 2026"],["ICN and similar bodies"]),
        T("Bedside Clinic","2",["Aug 2011","Aug 2012"],["Purpose & conduct"]),
        T("Prevention of Hospital Acquired Infections","2",["Feb 2009","Feb 2010"],["Infection control measures"]),
        T("Code of Ethics / Professional Ethics","2",["Jun 2024","Feb 2025"],["ANA/INC code of ethics"])
      ],
      3: [
        T("Team Conference","1",["Feb 2009"],[]),
        T("Orientation","1",["Feb 2009"],[]),
        T("Special Projects for Children","1",["Feb 2009"],[]),
        T("Progressive Patient Care","1",["Feb 2010"],[]),
        T("Functions of Primary Health Centre","1",["Feb 2010"],[]),
        T("Community Health Nurse – Handicapped Children","1",["Feb 2010"],[]),
        T("Indian Nursing Council","1",["Aug 2011"],[]),
        T("Industrial Health","1",["Feb 2012"],[]),
        T("Central Health Education Bureau – Functions","1",["Feb 2012"],[]),
        T("Welfare Programme for Physically Challenged Children","1",["Feb 2012"],[]),
        T("Job Description","1",["Aug 2012"],[]),
        T("Methods of Communication","1",["Aug 2012"],[]),
        T("Barriers of Communication","1",["Feb 2013"],[]),
        T("Principles of Delegation","1",["Feb 2013"],[]),
        T("Principles of Clinical Rotation Plan","1",["Oct 2023"],[]),
        T("Patient Classification System","1",["Oct 2023"],[]),
        T("Records and Reports","1",["Oct 2023"],[]),
        T("Role of Nurse Manager in Discipline","1",["Jun 2024"],[]),
        T("Career Opportunities in Nursing","1",["Jun 2024"],[]),
        T("Physical Facilities per INC Norms","1",["Feb 2025"],[]),
        T("Legal Responsibilities of Nurse Administrator","1",["Oct 2025"],[]),
        T("Organizational Chart","1",["Oct 2025"],[]),
        T("Leadership Theories in Nursing","1",["Nov 2025"],[]),
        T("Management by Objectives","1",["Jun 2026"],[]),
        T("Theories of Motivation","1",["Jul 2026"],[]),
        T("Types & Sources of Conflict and its Management","1",["Jul 2026"],[])
      ]
    }
  },

  shortAnswer: {
    label: "Short Answer",
    sub: "2 Marks each",
    color: "tertiary",
    tiers: {
      1: [
        T("Recruitment – Methods & Process","3",["Feb 2009","Feb 2014","Oct 2023"],["Recruitment methods used by health agencies","Process of recruitment"]),
        T("Job Analysis","3",["Feb 2009","Aug 2011","Feb 2014"],["Definition & purpose"]),
        T("Records – Purposes, Benefits & Types","3",["Feb 2010","Aug 2012","Feb 2014"],["Purposes of written reports","Benefits of records","Important hospital reports"])
      ],
      2: [
        T("Nursing Audit – Purposes","2",["Feb 2010","Aug 2011"],[]),
        T("Continuing Education","2",["Feb 2010","Aug 2011"],[]),
        T("PERT","2",["Oct 2023","Jun 2024"],[]),
        T("GANTT Chart","2",["Nov 2025","Mar 2026"],[]),
        T("Performance Appraisal","2",["Jun 2024","Oct 2025"],[]),
        T("Types of Law","2",["Jun 2024","Jun 2026"],[]),
        T("Collective Bargaining – Advantages/Disadvantages","2",["Feb 2013","Jun 2024"],[]),
        T("Nursing Rounds – Purposes","2",["Feb 2012","Aug 2012"],[]),
        T("Modular Nursing","2",["Feb 2009","Feb 2013"],[]),
        T("Public Health Nurse – Functions in Homes","2",["Aug 2009","Feb 2014"],[]),
        T("Staffing – Influencing Factors","2",["Feb 2009","Feb 2012"],[]),
        T("Budget – Types","2",["Aug 2011","Mar 2026"],[]),
        T("Supervision – Definition","2",["Aug 2012","Jun 2026"],[])
      ],
      3: [
        T("Kartar Singh Committee","1",["Feb 2009"],[]),
        T("Methods of Sterilization & Disinfection","1",["Feb 2009"],[]),
        T("Community Health Programme Planning","1",["Aug 2009"],[]),
        T("Importance of Delegating Responsibility","1",["Aug 2009"],[]),
        T("Organization Chart – Advantages","1",["Feb 2010"],[]),
        T("Quality Recording & Reporting Guidelines","1",["Feb 2010"],[]),
        T("Ward Supervisor – Duty Schedule Planning","1",["Feb 2010"],[]),
        T("IPR (Interpersonal Relations)","1",["Aug 2011"],[]),
        T("Ward Management – Contributing Factors","1",["Aug 2011"],[]),
        T("Leadership Styles (List)","1",["Feb 2012"],[]),
        T("Time Planning – Advantages","1",["Feb 2012"],[]),
        T("Channels of Communication","1",["Feb 2012"],[]),
        T("Nurse–Patient Ratio – Influencing Factors","1",["Feb 2012"],[]),
        T("Geriatric Problems","1",["Aug 2012"],[]),
        T("Counselling – Definition","1",["Aug 2012"],[]),
        T("Quality Control & Total Quality Management","1",["Feb 2013"],[]),
        T("Systems Theory","1",["Feb 2013"],[]),
        T("Ethical Principles","1",["Feb 2013"],[]),
        T("Anecdotal Notes","1",["Feb 2013"],[]),
        T("Criteria for a Good Report / Accreditation","1",["Feb 2014"],[]),
        T("Health Problems of the Aged / Primary Health Care","1",["Feb 2014"],[]),
        T("Bench Mark / Adult Learning – Definition","1",["Oct 2023"],[]),
        T("Objectives of Planning in Management","1",["Oct 2023"],[]),
        T("Beneficence / Tele-Nursing","1",["Jun 2024"],[]),
        T("Functions of SNA","1",["Jun 2024"],[]),
        T("Maslow's Classification of Human Needs","1",["Oct 2025"],[]),
        T("Autocratic vs Democratic Leadership – Difference","1",["Oct 2025"],[]),
        T("Concept of Management by Objectives","1",["Nov 2025"],[]),
        T("Interim Audit","1",["Nov 2025"],[]),
        T("Theories of Organization","1",["Mar 2026"],[]),
        T("Telemedicine","1",["Mar 2026"],[]),
        T("Laws Related to Nursing Practice","1",["Jun 2026"],[]),
        T("Emotional Intelligence","1",["Jun 2026"],[]),
        T("Andragogy / Johari Window","1",["Jul 2026"],[]),
        T("Functions & Principles of Management","1",["Jul 2026"],[])
      ]
    }
  },

  mcq: {
    label: "MCQ",
    sub: "Objective, 1 Mark each (With Answers)",
    color: "tertiary",
    tiers: {
      1: [
        TMCQ("Authority — Legitimate Power to Decide","2",["Oct 2025","Jun 2026"],
          "Select the appropriate term for the legitimate power to make decisions:",
          ["A) Delegation", "B) Leadership", "C) Authority", "D) Command"], "C", ["Asked almost verbatim in both papers"]),
        TMCQ("Final Stage of Team Development — Adjourning","2",["Oct 2025","Jun 2026"],
          "The final stage of team development is:",
          ["A) Storming", "B) Performing", "C) Norming", "D) Adjourning"], "D", ["Storming / Norming / Performing / Adjourning sequence"]),
        TMCQ("Budget Preparation — NOT an Essential Requisite","2",["Oct 2025","Mar 2026"],
          "Which of the following is NOT an essential requisite for budget preparation?",
          ["A) Period of budget", "B) Forecasting", "C) Accounting", "D) Line organization"], "D", ["Identical question repeated"]),
        TMCQ("Electronic Medical Records (EMR) — Definition","2",["Nov 2025","Mar 2026"],
          "Which of the following best describes Electronic Medical Records (EMRs)?",
          ["A) Digital versions of a patient's medical history maintained by healthcare providers", "B) Emergency Medical Record", "C) Essential Medical Report", "D) Non-clinical data storage"], "A", []),
        TMCQ("Maslow's Hierarchy of Needs","2",["Oct 2025","Nov 2025"],
          "Maslow's hierarchy of needs suggests that:",
          ["A) Lower-level needs must be satisfied before higher-level ones", "B) All needs must be satisfied simultaneously", "C) People are motivated only by monetary rewards", "D) Social needs are the most important"], "A", []),
        TMCQ("PERT — Purpose & Use","2",["Nov 2025","Mar 2026"],
          "Which one of the following project management tools is best for showing task dependencies and project flow?",
          ["A) Gantt Chart", "B) Budget Report", "C) Line Graph", "D) PERT Chart"], "D", []),
        TMCQ("Nurse–Patient Ratio per IPHS Norms","2",["Nov 2025","Mar 2026"],
          "What is the nurse-patient ratio for a general ward according to IPHS standards?",
          ["a) 1:1 (ICU)", "b) 1:6 (General Ward)", "c) 1:2", "d) 1:3"], "B", ["ICU 1:1, general ward 1:6"])
      ],
      2: [
        TMCQ("Scientific Management Theory — Taylor","1",["Oct 2025"],
          "Who put forward the Scientific Management Theory?",
          ["A) Peter Drucker", "B) Frederic Taylor", "C) Henri Fayol", "D) Henry I. Gantt"], "B", []),
        TMCQ("Delphi Technique","1",["Oct 2025"],
          "The technique used to estimate human resource needs from a group of expert managers is:",
          ["A) Delphi Technique", "B) Discipline Technique", "C) Planning Technique", "D) Expert Technique"], "A", []),
        TMCQ("TQM / Six Sigma","1",["Oct 2025"],
          "A Total Quality Management (TQM) strategy developed by the Motorola company in 1986 is:",
          ["A) Plan-Do-Check-Act", "B) ANA Model", "C) Six Sigma Model", "D) Lean Methodology"], "C", []),
        TMCQ("Primary Group Characteristics","1",["Oct 2025"],
          "A common characteristic present in a primary group is:",
          ["A) Large size", "B) Physical proximity", "C) Conflict", "D) Artificiality"], "B", []),
        TMCQ("Telenursing — Key Benefit","1",["Nov 2025"],
          "Which of the following is a key benefit of telenursing?",
          ["A) Reduces documentation", "B) Limits communication", "C) Enables nurses to deliver care remotely", "D) Eliminates registered nurses"], "C", []),
        TMCQ("Electronic Health Records — Primary Benefit","1",["Jun 2026"],
          "Predict the primary benefit of Electronic Health Records (EHRs) in nursing informatics:",
          ["A) Increase paperwork", "B) Decrease patient privacy", "C) Replace nurses entirely", "D) Improve access to patient information"], "D", []),
        TMCQ("Resilience — Key Component","1",["Jun 2026"],
          "Select the key component of personal resilience:",
          ["A) Isolation", "B) Emotional awareness and regulation", "C) Denial of challenges", "D) Rigid thinking"], "B", []),
        TMCQ("Positive Approach to Discipline","1",["Jun 2026"],
          "Choose the positive approach to discipline:",
          ["A) Public shaming", "B) Encouraging good behavior through rewards and praise", "C) Ignoring all rule violations", "D) Harsh punishments for every mistake"], "B", []),
        TMCQ("Purpose of Nursing Regulations","1",["Jun 2026"],
          "What is the main purpose of nursing regulations?",
          ["A) To increase paperwork", "B) To punish nurses for errors", "C) To ensure safe, ethical, and competent nursing practice", "D) To assign career roles"], "C", []),
        TMCQ("Type of Law — Criminal Law Example","1",["Jun 2026"],
          "Identify the type of law applicable to a nurse who steals medications from the hospital:",
          ["A) Administrative law", "B) Criminal law", "C) Civil law", "D) Tort law"], "B", []),
        TMCQ("Downward Communication Flow","1",["Jun 2026"],
          "Identify the communication flow that occurs from the nurse manager to staff nurses:",
          ["A) Upward communication", "B) Downward communication", "C) Horizontal communication", "D) Informal communication"], "B", []),
        TMCQ("Strategic Planning — Stakeholder Collaboration","1",["Mar 2026"],
          "Which planning process involves collaborating with various stakeholders to achieve common healthcare goals?",
          ["a) Program planning", "b) Functional planning", "c) Budget planning", "d) Strategic planning"], "D", []),
        TMCQ("Three-Tier Healthcare Delivery System","1",["Mar 2026"],
          "Which of the following best describes the current healthcare delivery system in India?",
          ["a) Only private sector services", "b) Three-tier system consisting of primary, secondary, and tertiary care", "c) Only urban-based hospitals", "d) Only traditional medicine system"], "B", []),
        TMCQ("Inventory Control Technique — NOT a Method","1",["Mar 2026"],
          "Which of the following is NOT a technique of inventory control?",
          ["a) ABC analysis", "b) VED analysis", "c) FSN analysis", "d) BSN analysis"], "D", []),
        TMCQ("Democratic Leadership Style","1",["Jul 2026"],
          "Which leadership style encourages staff participation in decision-making?",
          ["A) Autocratic", "B) Democratic", "C) Laissez-faire", "D) Bureaucratic"], "B", []),
        TMCQ("Collaborating Conflict-Management Strategy","1",["Jul 2026"],
          "Which conflict management strategy aims for a win-win solution?",
          ["A) Avoiding", "B) Competing", "C) Collaborating", "D) Accommodating"], "C", []),
        TMCQ("Assertive Communication — Definition","1",["Nov 2025"],
          "Which of the following best defines assertive communication in nursing?",
          ["A) Being passive to avoid conflict", "B) Expressing one's needs and opinions clearly and respectfully", "C) Dominating conversations to assert control", "D) Avoiding eye contact while communicating"], "B", []),
        TMCQ("Benchmarking — Use in Nursing Management","1",["Jul 2026"],
          "The term \"benchmarking\" is used in nursing management for:",
          ["a) Comparing salaries", "b) Improving documentation", "c) Setting performance standards", "d) Scheduling duties"], "C", []),
        TMCQ("Intrinsic Motivation — Example","1",["Jul 2026"],
          "Which of the following is an example of intrinsic motivation?",
          ["a) Bonus", "b) Praise from supervisor", "c) Personal satisfaction", "d) Promotion"], "C", []),
        TMCQ("Anecdotal Record — Definition & Timing","1",["Jul 2026"],
          "Which of the following best defines an anecdotal record in nursing documentation?",
          ["a) A laboratory report", "b) A detailed medical report", "c) A brief narrative account of a specific incident or behavior", "d) A financial report of a patient"], "C", []),
        TMCQ("CHC Population Coverage","1",["Oct 2025"],
          "The population coverage of a Community Health Centre (CHC) is:",
          ["A) 80,000", "B) 30,000", "C) 10,000", "D) 3,000"], "A", []),
        TMCQ("Auditing — Definition","1",["Oct 2025"],
          "The systematic examination of financial statement records and related operations is called:",
          ["A) Budget", "B) Auditing", "C) Statements", "D) Measurement"], "B", [])
      ],
      3: []
    }
  }
};

const TIER_META = {
  1:{label:"Tier 1 — High Yield", key:"tier1", note:"Repeated 3+ times (2+ for MCQ)"},
  2:{label:"Tier 2 — Medium Yield", key:"tier2", note:"Repeated twice (1+ for MCQ)"},
  3:{label:"Tier 3 — Emerging / Single Appearance", key:"tier3", note:"Asked once so far"}
};

// ---- Year Archive (verbatim, chronological, structured MCQs) ----
const YEARS = [
  {id:"2009-02", yr:"2009", mo:"FEB", label:"February 2009", exam:"B.Sc (Nursing) Degree Examination", code:"Sub. Code: 4777",
    essay:["1a) What is quality nursing care? (3)\n1b) Describe the responsibilities of head nurse in clinical setting in terms of providing quality patient care. (12)",
           "2a) List the principles of good ward management. (3)\n2b) Describe the various factors involved in good ward management. (12)"],
    shortNotes:["Team conference.","Orientation.","Nursing Audit.","Special projects for children.","Prevention of hospital acquired infections"],
    shortAnswer:["What is modular nursing?","What are the four types of supervision?","Define management.","Name the recruitment methods used by the health agencies.","Define job analysis.","What is nursing care study?","What is the importance of records for the nurses?","Write few lines about Kartar Singh committee.","Write any four factors influencing staffing.","Name any four methods recommended for sterilization and disinfection."],
    mcq:[]},

  {id:"2009-08", yr:"2009", mo:"AUG", label:"August 2009", exam:"B.Sc (Nursing) Degree Examination", code:"Sub. Code: 4777",
    essay:["1) Discuss the principles of administration and their application by the head nurse. (15)",
           "2a) Define nursing school administration. (1)\n2b) Discuss briefly on faculty recruitment. (4)\n2c) Explain organization and control of nursing school. (5)\n2d) Enumerate principles to staff counseling. (5)"],
    shortNotes:["Interpersonal relations in organization.","Public relations and leadership.","Five year plan.","Legal aspects in nursing.","House keeping in ward management."],
    shortAnswer:["Write four functions of public health nurse in homes.","Write four principles followed in carrying out rotation plan.","Write four points in planning community health programme.","Write four importance of delegating responsibility.","Name four types of records used by the students.","Write four factors affecting nursing in-service education programme.","Name four methods of staff development programmes.","Write four advantages of nursing audit.","List four important principles of management.","Name four principles of delegation."],
    mcq:[]},

  {id:"2010-02", yr:"2010", mo:"FEB", label:"February 2010", exam:"B.Sc (Nursing) Degree Examination", code:"Sub. Code: 4777",
    essay:["1a) Discuss the functions of supervision in nursing service administration. (7)\n1b) Write the merits and demerits of functional method of nursing care delivery system. (8)",
           "2a) Discuss the responsibilities of the principal of school of nursing with regard to administration of faculty. (7)\n2b) Enumerate the qualities of the community health supervisor. (8)"],
    shortNotes:["Progressive patient care.","Advantages of delegation.","Prevention of hospital acquired infections.","Functions of primary health centre.","Responsibilities of community health nurse in care of handicapped children."],
    shortAnswer:["Define job description.","List four purposes of written report.","Write four benefits of community health program planning.","List four advantages of having organization chart.","Write four purposes of nursing audit.","Mention four roles of the community leaders.","Define continuing education.","Write the responsibilities of the community health nurse in the care of the aged.","Write four guidelines used for quality recording and reporting.","Write four responsibilities of a ward supervisor in planning duty schedule for the students."],
    mcq:[]},

  {id:"2011-08", yr:"2011", mo:"AUG", label:"August 2011", exam:"B.Sc (Nursing) Degree Examination", code:"Sub. Code: 4777",
    essay:["1) Explain the roles and functions of the Multi-purpose health workers.",
           "2a) Explain the organization and control of School of Nursing.\n2b) Discuss about faculty recruitment.\n2c) Discuss the responsibility of the Principal, School of Nursing in relation to administration of student and faculty."],
    shortNotes:["Responsibilities of Community Health Nurse in the care of children.","Factors influencing staffing of the nursing unit.","Bed side clinic.","Methods of patient care assignment.","Legal responsibilities of Nurse.","Principles of supervision.","Group dynamics.","Indian nursing council."],
    shortAnswer:["List four qualities of maintaining records.","IPR.","Affiliation.","Job analysis.","List four factors involved in good ward management.","Recruitment.","List the types of Budget.","Continuing education.","Purposes of nursing audit.","List the four records of school of nursing."],
    mcq:[]},

  {id:"2012-02", yr:"2012", mo:"FEB", label:"February 2012", exam:"B.Sc (Nursing) Degree Examination", code:"Sub. Code: 4777",
    essay:["1a) Explain the principles of good ward management.\n1b) Describe the various factors involved in good ward management.",
           "2a) Describe various methods of patient assignment.\n2b) Explain in detail about records and reports."],
    shortNotes:["Nursing Audit.","Industrial health.","Functions of central health education bureau.","Welfare program for physically challenged children.","In-service education."],
    shortAnswer:["List four organization principles.","List four leadership styles.","List any four purposes of nursing rounds.","Identify four qualities of a nurse administrator.","Name any four methods of evaluating patient care.","List four principles to be followed when planning clinical assignment for students.","List four responsibilities of a public health Nurse.","List four advantages of time planning.","Mention channels of communication.","Mention any four factors influencing nurse patient ratio."],
    mcq:[]},

  {id:"2012-08", yr:"2012", mo:"AUG", label:"August 2012", exam:"Fourth Year B.Sc Nursing Examination", code:"Sub. Code: 4777",
    essay:["1a) Define the term management.\n1b) Explain the principles of management with examples.",
           "2a) As a nurse administrator what are the various factors you will consider while planning for nursing service department.\n2b) Calculate the nursing staff requirement for a 250 bedded multispeciality hospital."],
    shortNotes:["Legal aspects in nursing.","Housekeeping in hospital.","Bedside clinics.","Job description.","Faculty development programme.","Budget.","Methods of communication.","Material management."],
    shortAnswer:["Define supervision.","Write four benefits of records.","List any four methods of evaluation of staff.","Write any four functions of Nursing Superintendent.","List any four purposes of nursing rounds.","List any four criteria for faculty recruitment.","Define group dynamics.","List four functions of a primary health centre.","List four geriatric problems.","Define the term counselling."],
    mcq:[]},

  {id:"2013-02", yr:"2013", mo:"FEB", label:"February 2013", exam:"B.Sc (Nursing) Degree Examination", code:"Sub. Code: 4777",
    essay:["1a) Explain the principles of clinical supervision\n1b) Discuss the methods of clinical supervision",
           "2a) Explain the principles of management\n2b) As a nurse administrator prepare plan for continuing nursing education"],
    shortNotes:["Nursing audit","Functions of planning","Recruitment of faculty in college of nursing","Principles of budgeting","Leadership styles","Barriers of communication","Principles of delegation","Legal aspects in nursing"],
    shortAnswer:["Define quality control;","Four purposes of staff development","Advantages of collective bargaining","Define standards","What is total quality management","Systems theory","Ethical principles","Define staffing","Modular nursing","Define anecdotal notes"],
    mcq:[]},

  {id:"2014-02", yr:"2014", mo:"FEB", label:"February 2014", exam:"B.Sc. (Nursing) Degree Examination", code:"Sub. Code: 4777",
    essay:["1) Explain the role of a head nurse in relation to (a) Ward teaching programme (b) In-service education for staff development",
           "2a) Discuss the responsibilities of the principal of nursing with regard to administration of faculty\n2b) Enumerate the qualities of the community health supervisor"],
    shortNotes:["Group dynamics","Factors involved in good ward management","Principles of management","Methods of staffing","Five year plan"],
    shortAnswer:["Criteria for a good report","Define Accreditation","List four functions of public health nurse in homes","List four principles of supervision","Name the recruitment methods used by health agencies","Health problems of the aged","Define Job analysis","Define primary health care","Name four important reports used in a hospital setting","Mention the process of Recruitment"],
    mcq:[]},

  {id:"2023-10", yr:"2023", mo:"OCT", label:"October 2023", exam:"B.Sc. Nursing Degree Examination", code:"BSN1620 – Management of Nursing Services and Education",
    essay:["1) Explain the theories of management.","2) What is Material Management? Explain the Material Management Process.","3) Describe the Job description of nursing personnel in college of nursing."],
    shortNotes:["Write Principles of Clinical Rotation Plan.","Explain patient classification system.","Classify the types of Budgeting.","Explain consumer protection act.","Describe Records and Reports.","Explain methods of Inventory control."],
    shortAnswer:["Define Retaining.","List four roles of Nurse Manager.","What is PERT?","List down the four quality of supervisor.","Define group dynamic Leadership.","Enlist the styles.","What is Bench Mark?","Define Adult learning.","List down the process of Recruitment.","Write any two objectives of planning in management process."],
    mcq:[]},

  {id:"2024-06", yr:"2024", mo:"JUN", label:"June 11, 2024", exam:"Sessional Examination I", code:"BSN 1620 – Management of Nursing Service and Education",
    essay:["1a) Define Planning (2)\n1b) Explain the components of Planning (6)\n1c) Describe the role of the clinical nurse in planning nursing care of a patient admitted in ward/unit (7)",
           "2a) Define Budgeting (2)\n2b) List the principles of budgeting (5)\n2c) Explain the various types of budgeting (8)",
           "3a) Define Nursing as a Profession (2)\n3b) Explain the characteristic of a Professional nurse (5)\n3c) Discuss the Current trends and issues in Nursing (8)"],
    shortNotes:["Describe Code of Ethics in Nursing","Describe Collective Bargaining","Explain Material Management","Describe the role of nurse manager in maintaining discipline","Discuss about career opportunities in nursing","Describe the process of inventory control"],
    shortAnswer:["Define Planning in Nursing","Define PERT","Define Performance Appraisal","Mention the types of law","Define beneficence","Define Tele-nursing","State the two function of SNA","List the importance of participation of research activities in nursing service","List any four needs for continuing education","Enlist the career opportunities in nursing","List any four Disadvantages of collective bargaining"],
    mcq:[]},

  {id:"2025-02", yr:"2025", mo:"FEB", label:"February 27, 2025", exam:"Continuous Assessment Test II", code:"BSN1620 – Management of Nursing Services and Education",
    essay:["1a) Define Curriculum. (2)\n1b) List the Types of Curriculum (5)\n1c) Describe the steps in Nursing Curriculum (8)",
           "2a) What is In-service Education? (2)\n2b) List the technique and method to conduct the in-service education (5)\n2c) Prepare an outline for conducting an In-service education program for Nurses on Communication (8)"],
    shortNotes:["Define Group Dynamics and Discuss about Method of Group Dynamic.","List the Principles of Adult Learning.","What is Professional Ethics and Explain the Code of ethics in nursing","Enumerate the physical facilities of nursing college as per INC Norms","Define Continuing Education and explain the Importance of Continuing Education"],
    shortAnswer:[],
    mcq:[]},

  {id:"2025-10", yr:"2025", mo:"OCT", label:"October 2025", exam:"B.Sc. (Nursing) Degree Examination", code:"BSCN 1025 / Sub. Code: 2324 – Nursing Management and Leadership",
    essay:["1) Define Regulatory bodies. Describe the objectives, functions and committees of Indian Nursing Council.","2) Define Curriculum. Explain the steps in curriculum revision. Discuss the role of Administrator in curriculum revision."],
    shortNotes:["In-service Education.","The legal responsibilities of Nurse Administrator.","Consumer Act.","Write in brief about Professional organization at International Level.","Write briefly about Organizational chart."],
    shortAnswer:["List the components of Hospital Management Information System.","Classification of Human need based on Maslow.","Four methods of Performance appraisal.","Write the difference between Autocratic and Democratic Leadership."],
    mcq:[
      {q:"The population coverage of a Community Health Centre (CHC) is:", options:["A) 80,000", "B) 30,000", "C) 10,000", "D) 3,000"], answer:"A"},
      {q:"Who put forward the Scientific Management Theory?", options:["A) Peter Drucker", "B) Frederic Taylor", "C) Henri Fayol", "D) Henry I. Gantt"], answer:"B"},
      {q:"The systematic examination of financial statement records and related operations is called:", options:["A) Budget", "B) Auditing", "C) Statements", "D) Measurement"], answer:"B"},
      {q:"The most popular theory of motivation is:", options:["A) Hierarchy of Needs Theory", "B) Centralized Theory", "C) Leadership Theory", "D) Decentralized Theory"], answer:"A"},
      {q:"The technique used to estimate human resource needs from a group of expert managers is:", options:["A) Delphi Technique", "B) Discipline Technique", "C) Planning Technique", "D) Expert Technique"], answer:"A"},
      {q:"The final stage of team development is:", options:["A) Storming", "B) Performing", "C) Norming", "D) Adjourning"], answer:"D"},
      {q:"Training of the mind to bring about desired behavior is known as:", options:["A) Performance", "B) Discipline", "C) Motivation", "D) Supervision"], answer:"B"},
      {q:"The legitimate power to make decisions is:", options:["A) Delegation", "B) Leadership", "C) Authority", "D) Command"], answer:"C"},
      {q:"A Total Quality Management (TQM) strategy developed by the Motorola company in 1986 is:", options:["A) Plan-Do-Check-Act", "B) ANA Model", "C) Six Sigma Model", "D) Lean Methodology"], answer:"C"},
      {q:"A common characteristic present in a primary group is:", options:["A) Large size", "B) Physical proximity", "C) Conflict", "D) Artificiality"], answer:"B"},
      {q:"Which of the following is NOT an essential requisite for budget preparation?", options:["A) Period of budget", "B) Forecasting", "C) Accounting", "D) Line organization"], answer:"D"},
      {q:"Which among the following is NOT an important source of environmental stressor?", options:["A) Weather", "B) Traffic", "C) Substandard housing", "D) Financial problems"], answer:"D"}
    ]},

  {id:"2025-11", yr:"2025", mo:"NOV", label:"November 2025", exam:"B.Sc. Nursing Degree Examination", code:"NMLE330T – Nursing Management and Leadership",
    essay:["13) Write in detail about the characteristics of a professional nurse and describe the philosophy, aim and objectives of Nursing practice.","14) Define Financial Management and explain the elements, functions, principles and scope of financial management in nursing services.","15) Define Budget and enumerate types of budget. Describe the role of nurse administrator in planning the budget for a nursing college with intake of 50 B.Sc. (N) per year."],
    shortNotes:["What are the leadership theories in nursing?","Performance appraisal.","Principles of adult learning.","Write about Resilience building.","Write about Group dynamics.","Methods of inventory control."],
    shortAnswer:["Concept of management by Objectives.","Mention four needs for Public Relations in Nursing.","What is Interim audit?","What is a Gantt chart?"],
    mcq:[
      {q:"What is the recommended nurse-to-patient ratio in Intensive Care Units (ICUs) as per Indian Public Health Standards (IPHS) norms?", options:["(a) 1:3", "(b) 1:2", "(c) 1:1", "(d) 1:4"], answer:"C"},
      {q:"Which one of the following project management tools is best for showing task dependencies and project flow?", options:["(a) Gantt Chart", "(b) Budget Report", "(c) Line Graph", "(d) PERT Chart"], answer:"D"},
      {q:"Which of the following is a key benefit of telenursing?", options:["(a) Reduces the need for nursing documentation", "(b) Limits communication with patients", "(c) Enables nurses to deliver care remotely", "(d) Eliminates the role of registered nurses"], answer:"C"},
      {q:"Which of the following best describes Electronic Medical Records (EMRs)?", options:["(a) Paper-based records", "(b) Legal documents kept in archives", "(c) Digital versions of a patient's medical history maintained by healthcare providers", "(d) Non-clinical data storage"], answer:"C"},
      {q:"Maslow's hierarchy of needs suggests that:", options:["(a) People are motivated only by monetary rewards", "(b) All needs must be satisfied simultaneously", "(c) Lower-level needs must be satisfied before higher-level ones", "(d) Social needs are the most important"], answer:"C"},
      {q:"Which of the following is a strategy to resolve interpersonal conflict in nursing teams?", options:["(a) Ignoring the problem", "(b) Encouraging open and respectful communication", "(c) Assigning blame", "(d) Reassigning staff without discussion"], answer:"B"},
      {q:"The main objective of performance appraisal in nursing is to:", options:["(a) Identify personal issues in staff", "(b) Dismiss underperformers", "(c) Evaluate job performance and improve staff development", "(d) Promote competition"], answer:"C"},
      {q:"Which of the following strategies is most effective for stress management among nurses?", options:["(a) Time management and relaxation techniques", "(b) Avoiding social interaction", "(c) Suppressing emotions", "(d) Skipping meals to save time"], answer:"A"},
      {q:"When should anecdotal records ideally be written?", options:["(a) Days after the event", "(b) At the end of the month", "(c) Immediately after the observed incident", "(d) Before the incident happens"], answer:"C"},
      {q:"Which of the following best defines assertive communication in nursing?", options:["(a) Being passive to avoid conflict", "(b) Expressing one's needs and opinions clearly and respectfully", "(c) Dominating conversations to assert control", "(d) Avoiding eye contact while communicating"], answer:"B"},
      {q:"Which activity falls under the staffing function of management?", options:["(a) Conflict resolution", "(b) Budget planning", "(c) Hiring and training nurses", "(d) Patient discharge planning"], answer:"C"},
      {q:"The function of controlling in the management process is best described as:", options:["(a) Giving orders to staff", "(b) Planning future strategies", "(c) Evaluating performance and correcting deviations", "(d) Designing hospital architecture"], answer:"C"}
    ]},

  {id:"2026-03", yr:"2026", mo:"MAR", label:"March 27, 2026", exam:"VI Semester Sessional Examination I", code:"NMLE 330 – Nursing Management & Leadership",
    essay:["13a) Explain the various steps involved in the management process. (7)\n13b) Interpret each step with examples from healthcare or nursing administration (8)",
           "14a) Define Human Resource Management. (2)\n14b) Explain in detail about Recruitment, Selection, Deployment, Retention, and Promotion of nurses in hospital setting. (13)",
           "15a) Define financial management (2)\n15b) Discuss the elements, functions, principles and scope of financial management in nursing services. (13)"],
    shortNotes:["16) Discuss about performance appraisal.","17) Illustrate the in-service education","18) Explain regarding Nursing Audit","19) Describe group dynamics","20) Explain the principles of management","21) Describe about material management"],
    shortAnswer:["Classify the budget","List the uses of GANTT chart.","Identify any four theories of organization","Define telemedicine"],
    mcq:[
      {q:"What is the nurse-patient ratio for a general ward according to IPHS standards?", options:["a) 1:1", "b) 1:6", "c) 1:2", "d) 1:3"], answer:"B"},
      {q:"Which planning process involves collaborating with various stakeholders to achieve common healthcare goals?", options:["a) Program planning", "b) Functional planning", "c) Budget planning", "d) Strategic planning"], answer:"D"},
      {q:"Which management function involves allocating resources?", options:["a) Planning", "b) Organizing", "c) Staffing", "d) Controlling"], answer:"B"},
      {q:"Which of the following is NOT a technique of inventory control?", options:["a) ABC analysis", "b) VED analysis", "c) FSN analysis", "d) BSN analysis"], answer:"D"},
      {q:"What does EMR stand for?", options:["a) Electronic Medical Record", "b) Emergency Medical Record", "c) Essential Medical Report", "d) Electronic Management Record"], answer:"A"},
      {q:"What is meant by procurement?", options:["a) Selling goods", "b) Purchasing supplies", "c) Storing items", "d) Distributing staff"], answer:"B"},
      {q:"What does an organizational chart show?", options:["a) Patient data", "b) Structure and authority", "c) Budget", "d) Records"], answer:"B"},
      {q:"PERT is mainly used for:", options:["a) Staffing", "b) Project planning", "c) Budgeting", "d) Auditing"], answer:"B"},
      {q:"Nursing rounds help in:", options:["a) Ignoring patients", "b) Monitoring patient care", "c) Reducing staff", "d) Avoiding care"], answer:"B"},
      {q:"Which of the following is NOT an essential requisite for budget preparation?", options:["a) Period of budget", "b) Forecasting", "c) Accounting", "d) Line organization"], answer:"D"},
      {q:"Which of the following is a key aspect of employee relations in Human Resource Management (HRM)?", options:["a) Conflict resolution", "b) Staff management", "c) Performance management", "d) All of the above"], answer:"D"},
      {q:"Which of the following best describes the current healthcare delivery system in India?", options:["a) Only private sector services", "b) Three-tier system consisting of primary, secondary, and tertiary care", "c) Only urban-based hospitals", "d) Only traditional medicine system"], answer:"B"}
    ]},

  {id:"2026-06", yr:"2026", mo:"JUN", label:"June 24, 2026", exam:"VI Semester Sessional Examination II", code:"NMLE 330 – Nursing Management & Leadership",
    essay:["13a) Define Regulatory bodies. (2)\n13b) Describe the objectives, functions and committees of Indian Nursing Council. (13)",
           "14) Appraise the physical, and academic facilities required for the nursing educational institution including staffing norms as per INC for 50 students intake per annum (15)",
           "15) Explain curriculum planning, implementation and evaluation in nursing educational institutions (15)"],
    shortNotes:["16) Write briefly about Professional organization at International Level","17) Criticize Consumer Act.","18) Explain about Management by Objectives","19) Summarize the styles of Leadership.","20) Present briefly faculty development & faculty welfare","21) Describe collective bargaining"],
    shortAnswer:["22) Write 4 laws related to nursing practice","23) Define emotional intelligence","24) Define supervision","25) Write the records maintained for students at an educational institution"],
    mcq:[
      {q:"Identify the communication flow that occurs from the nurse manager to staff nurses:", options:["A) Upward communication", "B) Downward communication", "C) Horizontal communication", "D) Informal communication"], answer:"B"},
      {q:"Predict the primary benefit of Electronic Health Records (EHRs) in nursing informatics:", options:["A) Increase paperwork", "B) Decrease patient privacy", "C) Replace nurses entirely", "D) Improve access to patient information"], answer:"D"},
      {q:"Select the key component of personal resilience:", options:["A) Isolation", "B) Emotional awareness and regulation", "C) Denial of challenges", "D) Rigid thinking"], answer:"B"},
      {q:"Choose the positive approach to discipline:", options:["A) Public shaming", "B) Encouraging good behavior through rewards and praise", "C) Ignoring all rule violations", "D) Harsh punishments for every mistake"], answer:"B"},
      {q:"Which strategy best promotes self-discipline in students?", options:["A) Encouraging goal-setting and time management", "B) Constant supervision", "C) Giving all responsibilities to teachers", "D) Avoiding consequences for actions"], answer:"A"},
      {q:"What is the main purpose of inspection in nursing management?", options:["A) To punish underperforming nurses", "B) To reduce patient care", "C) To evaluate and improve the quality of nursing services", "D) To increase documentation work"], answer:"C"},
      {q:"A nurse who is interested in teaching and shaping future nurses should pursue a career as a:", options:["A) Clinical Nurse Specialist", "B) Nurse Educator", "C) Operating Room Nurse", "D) Travel Nurse"], answer:"B"},
      {q:"What is the main purpose of nursing regulations?", options:["A) To increase paperwork", "B) To punish nurses for errors", "C) To ensure safe, ethical, and competent nursing practice", "D) To assign career roles"], answer:"C"},
      {q:"Select the final stage of team development:", options:["A) Storming", "B) Performing", "C) Norming", "D) Adjourning"], answer:"D"},
      {q:"Identify the type of law applicable to a nurse who steals medications from the hospital:", options:["A) Administrative law", "B) Criminal law", "C) Civil law", "D) Tort law"], answer:"B"},
      {q:"Select the appropriate term for the legitimate power to make decisions:", options:["A) Delegation", "B) Leadership", "C) Authority", "D) Command"], answer:"C"},
      {q:"What is the primary goal of guidance and counseling?", options:["A) To punish inappropriate behavior", "B) To provide academic instruction", "C) To help individuals understand and solve personal, social, or educational problems", "D) To limit the number of nurses in hospitals"], answer:"C"}
    ]},

  {id:"2026-07", yr:"2026", mo:"JUL", label:"July 25, 2026", exam:"VI Semester Model Examination", code:"NMLE 330 – Nursing Management & Leadership",
    essay:["13a) Explain the Philosophy and Objectives of staffing in nursing (8)\n13b) Interpret about the steps in staff recruitment process (7)",
           "14a) Define financial management (2)\n14b) Write in detail the elements, functions, principles and scope of financial management in nursing services (13)",
           "15a) Explain the role of a nurse in emergency and Disaster management (2)\n15b) List the phases of disaster management and discuss the significant role of nurse in each phase (13)"],
    shortNotes:["16) Appraise the methods of inventory control","17) Write about Resilience building","18) Explain the theories of motivation.","19) Summarize the types and sources of conflict and its management","20) Discuss the importance of in service education in nursing for professional development","21) Interpret the Nursing Audit"],
    shortAnswer:["22) Define Andragogy","23) Interpret four quadrants of a Johari Window","24) Mention any four Functions of management","25) Write any four principles of management"],
    mcq:[
      {q:"Which leadership style encourages staff participation in decision-making?", options:["A) Autocratic", "B) Democratic", "C) Laissez-faire", "D) Bureaucratic"], answer:"B"},
      {q:"The primary purpose of delegation is to:", options:["A) Avoid responsibility", "B) Improve efficiency and patient care", "C) Reduce staff workload permanently", "D) Transfer accountability"], answer:"B"},
      {q:"Which conflict management strategy aims for a win-win solution?", options:["A) Avoiding", "B) Competing", "C) Collaborating", "D) Accommodating"], answer:"C"},
      {q:"Which communication style is considered most effective in nursing leadership?", options:["A) Passive", "B) Aggressive", "C) Assertive", "D) Defensive"], answer:"C"},
      {q:"Which level of management is responsible for strategic planning?", options:["a) First-line managers", "b) Middle-level managers", "c) Top-level managers", "d) Nurse assistants"], answer:"C"},
      {q:"Which principle is most important when delegating a task?", options:["A) Delegate accountability", "B) Delegate only to licensed nurses", "C) Match the task to the individual's competence", "D) Delegate all routine tasks"], answer:"C"},
      {q:"Quality improvement in nursing primarily aims to:", options:["A) Increase hospital profits", "B) Improve patient outcomes and safety", "C) Reduce staff numbers", "D) Eliminate documentation"], answer:"B"},
      {q:"Which of the following is an example of informal communication?", options:["A) Policy manual", "B) Staff meeting minutes", "C) Casual conversation between coworkers", "D) Written incident report"], answer:"C"},
      {q:"Who is primarily responsible for policy formulation in a hospital?", options:["a) Staff nurses", "b) Nurse educator", "c) Nurse executive", "d) Ward in-charge"], answer:"C"},
      {q:"Which of the following is an example of intrinsic motivation?", options:["a) Bonus", "b) Praise from supervisor", "c) Personal satisfaction", "d) Promotion"], answer:"C"},
      {q:"The term \"benchmarking\" is used in nursing management for:", options:["a) Comparing salaries", "b) Improving documentation", "c) Setting performance standards", "d) Scheduling duties"], answer:"C"},
      {q:"Which of the following best defines an anecdotal record in nursing documentation?", options:["a) A laboratory report", "b) A detailed medical report", "c) A brief narrative account of a specific incident or behavior", "d) A financial report of a patient"], answer:"C"}
    ]}
];

// ---- SYLLABUS UNITS & PYQ MAPPING (VERBATIM 18 UNITS) ----
const SYLLABUS_UNITS = [
  {
    id: "unit1",
    title: "Unit I: Health Care and Development of Nursing Services in India",
    topics: [
      "Current health care delivery system of India – review",
      "Planning and development of nursing services and education at global and national scenario",
      "Recent trends and issues of nursing service and management"
    ],
    pyqs: [
      {type:"Long Essay", text:"Current trends & issues in nursing (Jun 2024, Nov 2025)"},
      {type:"Short Notes", text:"Five Year Plan – Health planning milestones (Aug 2009, Feb 2014)"},
      {type:"Short Notes", text:"Functions of Primary Health Centre (Feb 2010)"},
      {type:"Short Answer", text:"Kartar Singh Committee (Feb 2009)"},
      {type:"Short Answer", text:"Health Problems of the Aged / Primary Health Care (Feb 2014)"},
      {type:"MCQ", text:"Three-tier healthcare delivery system in India (Mar 2026)"},
      {type:"MCQ", text:"CHC Population Coverage – 80,000 (Oct 2025)"}
    ]
  },
  {
    id: "unit2",
    title: "Unit II: Management Basics Applied to Nursing",
    topics: [
      "Definitions, concepts and theories of management",
      "Importance, features and levels of management",
      "Management and administration",
      "Functions of management",
      "Principles of management",
      "Role of a nurse as a manager",
      "Introduction to Management Process: Planning, Organizing, Staffing, Directing/Leading, Controlling"
    ],
    pyqs: [
      {type:"Long Essay", text:"Management Principles, Theories & Process (Aug 2012, Feb 2013, Oct 2023, Mar 2026)"},
      {type:"Long Essay", text:"Theories of management – Taylor & Fayol (Oct 2023, Mar 2026)"},
      {type:"Short Notes", text:"Principles of management (Feb 2014, Mar 2026)"},
      {type:"Short Answer", text:"Define management & list important principles (Feb 2009, Jul 2026)"},
      {type:"Short Answer", text:"Systems theory & Theories of organization (Feb 2013, Mar 2026)"},
      {type:"MCQ", text:"Scientific Management Theory – Frederic Taylor (Oct 2025)"},
      {type:"MCQ", text:"Level of management responsible for strategic planning – Top-level (Jul 2026)"}
    ]
  },
  {
    id: "unit3",
    title: "Unit III: Planning Nursing Services",
    topics: [
      "Vision, Mission, philosophy, objectives",
      "Nursing service policies, procedures and manuals",
      "Functional and operational planning",
      "Strategic planning",
      "Program planning – Gantt chart & milestone chart",
      "Budgeting – concepts, principles, types",
      "Budget proposal, cost benefit analysis",
      "Planning hospital and patient care unit (Ward)",
      "Planning for emergency and disaster"
    ],
    pyqs: [
      {type:"Long Essay", text:"Budgeting – Definition, principles & types (Jun 2024, Nov 2025)"},
      {type:"Long Essay", text:"Planning & components of planning in clinical patient care (Jun 2024)"},
      {type:"Long Essay", text:"Emergency & Disaster Management – Phases & nurse's role (Jul 2026)"},
      {type:"Short Notes", text:"Budget & Types of Budgeting (Aug 2012, Oct 2023)"},
      {type:"Short Answer", text:"PERT & GANTT Chart uses (Oct 2023, Jun 2024, Nov 2025, Mar 2026)"},
      {type:"MCQ", text:"Strategic planning – Stakeholder collaboration (Mar 2026)"},
      {type:"MCQ", text:"Project management tool for task dependencies – PERT Chart (Nov 2025)"}
    ]
  },
  {
    id: "unit4",
    title: "Unit IV: Organizing",
    topics: [
      "Organizing as a process – assignment, delegation and coordination",
      "Hospital – types, functions & organization",
      "Organizational development, structure, charts & effectiveness",
      "Hospital administration, Control & line of authority",
      "Hospital statistics including hospital utilization indices",
      "Nursing care delivery systems and trends",
      "Role of nurse in maintenance of effective organizational climate"
    ],
    pyqs: [
      {type:"Long Essay", text:"Ward Management – Principles & factors (Feb 2009, Feb 2012)"},
      {type:"Long Essay", text:"Patient Assignment Methods & Records/Reports (Feb 2012)"},
      {type:"Short Notes", text:"Organizational chart (Oct 2025)"},
      {type:"Short Answer", text:"Modular Nursing & Functional Nursing merits/demerits (Feb 2009, Feb 2010, Feb 2013)"},
      {type:"Short Answer", text:"Line vs Staff organization & Authority (Aug 2009, Oct 2025)"},
      {type:"MCQ", text:"Legitimate power to make decisions – Authority (Oct 2025, Jun 2026)"},
      {type:"MCQ", text:"Organizational chart shows structure and authority (Mar 2026)"}
    ]
  },
  {
    id: "unit5",
    title: "Unit V: Staffing (Human Resource Management)",
    topics: [
      "Definition, objectives, components and functions",
      "Staffing & Scheduling: Philosophy, staffing activities",
      "Recruiting, selecting, deployment, training, development, credentialing, retaining, promoting, transfer, terminating, superannuation",
      "Staffing units – Projecting staffing requirements/calculation of requirements of staff resources, Nurse patient ratio, Nurse Population ratio as per SIU norms/IPH Norms, and Patient classification system",
      "Categories of nursing personnel including job description of all levels",
      "Assignment and nursing care responsibilities, turnover and absenteeism",
      "Staff welfare, discipline and grievances",
      "In-Service Education: Nature and scope, principles of adult learning, planning, organizing, methods, techniques, evaluation, report preparation",
      "Material Resource Management: Procurement, purchasing process, inventory control & role of nurse",
      "Auditing and maintenance in hospital and patient care unit"
    ],
    pyqs: [
      {type:"Long Essay", text:"Staffing, Recruitment & HRM – Complete process (Mar 2026, Jun 2026, Jul 2026)"},
      {type:"Long Essay", text:"Nursing Staff Requirement Calculation – 250 bed hospital (Aug 2012)"},
      {type:"Long Essay", text:"Material Management Process (Oct 2023)"},
      {type:"Short Notes", text:"Nursing Audit – Definition, Concurrent vs Retrospective (Feb 2009, Feb 2012, Feb 2013, Mar 2026, Jul 2026)"},
      {type:"Short Notes", text:"In-Service Education & Techniques (Feb 2012, Mar 2026, Jul 2026)"},
      {type:"Short Notes", text:"Inventory Control Methods – ABC / VED / FSN (Oct 2023, Nov 2025, Jul 2026)"},
      {type:"MCQ", text:"Nurse-to-patient ratio ICU 1:1, General Ward 1:6 per IPHS norms (Nov 2025, Mar 2026)"},
      {type:"MCQ", text:"ABC / VED / FSN inventory control techniques (Mar 2026)"}
    ]
  },
  {
    id: "unit6",
    title: "Unit VI: Directing and Leading",
    topics: [
      "Definition, principles, elements of directing",
      "Supervision and guidance",
      "Participatory management & inter-professional collaboration",
      "Management by objectives",
      "Team management",
      "Assignments, rotations",
      "Maintenance of discipline",
      "Leadership in management"
    ],
    pyqs: [
      {type:"Long Essay", text:"Clinical / Nursing Supervision – Principles & methods (Feb 2010, Feb 2013)"},
      {type:"Long Essay", text:"Community Health Supervisor – Qualities & role (Feb 2010, Feb 2014)"},
      {type:"Short Notes", text:"Management by Objectives (Jun 2026)"},
      {type:"Short Notes", text:"Role of Nurse Manager in Discipline (Jun 2024)"},
      {type:"Short Answer", text:"Supervision definition & four types (Feb 2009, Aug 2012, Jun 2026)"},
      {type:"MCQ", text:"Positive approach to discipline – encouraging good behavior (Jun 2026)"},
      {type:"MCQ", text:"Primary goal of guidance and counseling (Jun 2026)"}
    ]
  },
  {
    id: "unit7",
    title: "Unit VII: Leadership",
    topics: [
      "Definition, concepts, and theories",
      "Leadership principles and competencies",
      "Leadership styles: Situational leadership, Transformational leadership",
      "Methods of leadership development",
      "Mentorship/preceptorship in nursing",
      "Delegation, power & politics, empowerment, mentoring and coaching",
      "Decision making and problem solving",
      "Conflict management and negotiation",
      "Implementing planned change"
    ],
    pyqs: [
      {type:"Short Notes", text:"Leadership Styles – Autocratic, Democratic, Laissez-faire (Feb 2013, Jun 2026)"},
      {type:"Short Notes", text:"Leadership Theories in Nursing (Nov 2025)"},
      {type:"Short Notes", text:"Types & Sources of Conflict and its Management (Jul 2026)"},
      {type:"Short Notes", text:"Principles of Delegation (Feb 2013)"},
      {type:"Short Answer", text:"Autocratic vs Democratic Leadership differences (Oct 2025)"},
      {type:"MCQ", text:"Collaborating conflict management strategy – Win-Win (Jul 2026)"},
      {type:"MCQ", text:"Primary purpose of delegation – improve efficiency (Jul 2026)"}
    ]
  },
  {
    id: "unit8",
    title: "Unit VIII: Controlling",
    topics: [
      "Implementing standards, policies, procedures, protocols and practices",
      "Nursing performance audit, patient satisfaction",
      "Nursing rounds, Documentation – records and reports",
      "Total quality management – Quality assurance, Quality and safety",
      "Performance appraisal",
      "Program evaluation review technique (PERT)",
      "Bench marking, Activity plan (Gantt chart)",
      "Critical path analysis"
    ],
    pyqs: [
      {type:"Short Notes", text:"Performance Appraisal – Purpose & methods (Nov 2025, Mar 2026)"},
      {type:"Short Notes", text:"Records and Reports in hospital setting (Oct 2023)"},
      {type:"Short Answer", text:"Total Quality Management (TQM) & Quality Control (Feb 2013)"},
      {type:"Short Answer", text:"Nursing Rounds purposes & Anecdotal Notes (Feb 2012, Feb 2013)"},
      {type:"MCQ", text:"TQM Six Sigma Model developed by Motorola (Oct 2025)"},
      {type:"MCQ", text:"Benchmarking used for setting performance standards (Jul 2026)"}
    ]
  },
  {
    id: "unit9",
    title: "Unit IX: Organizational Behavior and Human Relations",
    topics: [
      "Concepts and theories of organizational behavior",
      "Group dynamics",
      "Review – Interpersonal relationship & Human relations",
      "Public relations in the context of nursing",
      "Relations with professional associations and employee unions",
      "Collective bargaining",
      "Review – Motivation and morale building",
      "Communication in the workplace – assertive communication",
      "Committees – importance in the organization, functioning"
    ],
    pyqs: [
      {type:"Short Notes", text:"Group Dynamics – Characteristics & stages (Aug 2011, Aug 2012, Feb 2014, Nov 2025, Mar 2026)"},
      {type:"Short Notes", text:"Collective Bargaining – Definition & process (Jun 2024, Jun 2026)"},
      {type:"Short Notes", text:"Theories of Motivation (Jul 2026)"},
      {type:"Short Answer", text:"Maslow's Hierarchy of Needs classification (Oct 2025)"},
      {type:"MCQ", text:"Final stage of team development – Adjourning (Oct 2025, Jun 2026)"},
      {type:"MCQ", text:"Assertive communication definition (Nov 2025, Jul 2026)"}
    ]
  },
  {
    id: "unit10",
    title: "Unit X: Financial Management",
    topics: [
      "Definition, objectives, elements, functions, principles & scope of financial management",
      "Financial planning (budgeting for nursing department)",
      "Proposal, projecting requirement for staff, equipment and supplies for – Hospital & patient care units & emergency and disaster units",
      "Budget and Budgetary process",
      "Financial audit"
    ],
    pyqs: [
      {type:"Long Essay", text:"Financial Management in Nursing Services – Complete scope (Nov 2025, Mar 2026, Jul 2026)"},
      {type:"Long Essay", text:"Budgeting for College of Nursing – 50 intake (Nov 2025)"},
      {type:"Short Notes", text:"Classification of budget types (Aug 2012, Oct 2023)"},
      {type:"Short Answer", text:"Interim Audit (Nov 2025)"},
      {type:"MCQ", text:"Systematic examination of financial statement records – Auditing (Oct 2025)"},
      {type:"MCQ", text:"Budget preparation requisites – Line organization NOT essential (Oct 2025, Mar 2026)"}
    ]
  },
  {
    id: "unit11",
    title: "Unit XI: Nursing Informatics / Information Management – Review",
    topics: [
      "Patient records & Nursing records",
      "Use of computers in hospital, college and community",
      "Telemedicine & Tele nursing",
      "Electronic Medical Records (EMR), EHR"
    ],
    pyqs: [
      {type:"Short Answer", text:"Tele-nursing & Telemedicine definitions (Jun 2024, Mar 2026)"},
      {type:"Short Answer", text:"Components of Hospital Management Information System (Oct 2025)"},
      {type:"MCQ", text:"Electronic Medical Records (EMR) – Digital patient history (Nov 2025, Mar 2026)"},
      {type:"MCQ", text:"Primary benefit of EHRs – improve access to patient info (Jun 2026)"},
      {type:"MCQ", text:"Key benefit of telenursing – deliver care remotely (Nov 2025)"}
    ]
  },
  {
    id: "unit12",
    title: "Unit XII: Personal Management – Review",
    topics: [
      "Emotional intelligence",
      "Resilience building",
      "Stress and time management – de stressing",
      "Career planning"
    ],
    pyqs: [
      {type:"Short Notes", text:"Resilience Building strategies (Nov 2025, Jul 2026)"},
      {type:"Short Notes", text:"Career Opportunities in Nursing (Jun 2024)"},
      {type:"Short Answer", text:"Emotional Intelligence (Jun 2026)"},
      {type:"Short Answer", text:"Time planning advantages (Feb 2012)"},
      {type:"MCQ", text:"Key component of resilience – emotional awareness and regulation (Jun 2026)"},
      {type:"MCQ", text:"Stress management strategies – time management & relaxation (Nov 2025)"}
    ]
  },
  {
    id: "unit13",
    title: "Unit XIII: Establishment of Nursing Educational Institutions",
    topics: [
      "Indian Nursing Council norms and guidelines – Faculty norms, physical facilities, clinical facilities, curriculum implementation, and evaluation/examination guidelines",
      "Coordination with regulatory bodies – INC and State Nursing Council",
      "Accreditation – Inspections",
      "Affiliation with university/State council/board of examinations"
    ],
    pyqs: [
      {type:"Long Essay", text:"Physical & Academic Facilities per INC Norms for 50 students intake (Jun 2026)"},
      {type:"Long Essay", text:"Regulatory Bodies & INC objectives, functions & committees (Oct 2025, Jun 2026)"},
      {type:"Short Notes", text:"Physical facilities per INC Norms (Feb 2025)"},
      {type:"Short Answer", text:"Accreditation definition & Criteria for good report (Feb 2014)"},
      {type:"MCQ", text:"Purpose of nursing regulations – ensure safe & ethical practice (Jun 2026)"}
    ]
  },
  {
    id: "unit14",
    title: "Unit XIV: Planning and Organizing (Educational Institutions)",
    topics: [
      "Philosophy, objectives and mission of the college",
      "Organization structure of school/college",
      "Review – Curriculum planning",
      "Planning teaching and learning experiences, clinical facilities – master plan, time table and clinical rotation",
      "Budget planning – faculty, staff, equipment & supplies, AV aids, Lab equipment, library books, journals, computers and maintenance",
      "Infrastructure facilities – college, classrooms, hostel, library, labs, computer lab, transport facilities",
      "Records & reports for students, staff, faculty and administrative",
      "Committees and functioning",
      "Clinical experiences"
    ],
    pyqs: [
      {type:"Long Essay", text:"Organization & Control of School of Nursing (Aug 2009, Aug 2011)"},
      {type:"Long Essay", text:"Curriculum – Development, Revision & Administrator Role (Feb 2025, Oct 2025, Jun 2026)"},
      {type:"Short Notes", text:"Principles of Clinical Rotation Plan (Oct 2023)"},
      {type:"Short Answer", text:"Records maintained for students at an educational institution (Jun 2026)"}
    ]
  },
  {
    id: "unit15",
    title: "Unit XV: Staffing and Student Selection",
    topics: [
      "Faculty/staff selection, recruitment and placement, job description",
      "Performance appraisal",
      "Faculty development",
      "Faculty/staff welfare",
      "Student recruitment, admission, clinical placement"
    ],
    pyqs: [
      {type:"Long Essay", text:"Faculty Recruitment & Principal's Responsibilities (Aug 2009, Feb 2010, Aug 2011, Feb 2014)"},
      {type:"Short Notes", text:"Faculty Development & Welfare measures (Aug 2012, Feb 2013, Jun 2026)"},
      {type:"Short Notes", text:"Job Description of Nursing Personnel in college (Oct 2023)"},
      {type:"Short Answer", text:"Criteria for faculty recruitment (Aug 2012)"}
    ]
  },
  {
    id: "unit16",
    title: "Unit XVI: Directing and Controlling (Educational Institutions)",
    topics: [
      "Review – Curriculum implementation and evaluation",
      "Leadership and motivation, supervision – review",
      "Guidance and counseling",
      "Quality management – educational audit",
      "Program evaluation, evaluation of performance",
      "Maintaining discipline",
      "Institutional records and reports – administrative, faculty, staff and students"
    ],
    pyqs: [
      {type:"Long Essay", text:"Curriculum planning, implementation and evaluation (Jun 2026)"},
      {type:"Long Essay", text:"Principles of staff counseling (Aug 2009)"},
      {type:"Short Notes", text:"Educational audit & quality recording guidelines (Feb 2010)"},
      {type:"MCQ", text:"Guidance and counseling primary goal – personal/educational problem solving (Jun 2026)"}
    ]
  },
  {
    id: "unit17",
    title: "Unit XVII: Professional Considerations",
    topics: [
      "Review – Legal and Ethical Issues",
      "Nursing as a profession – Characteristics of a professional nurse",
      "Nursing practice – philosophy, aim and objectives",
      "Regulatory bodies – INC and SNC constitution and functions",
      "Review – Professional ethics: Code of ethics and professional conduct – INC & ICN",
      "Practice standards for nursing – INC & International Council for Nurses (ICN)",
      "Legal aspects in nursing: Consumer protection act, patient rights",
      "Legal terms related to practice, legal system – types of law, tort law & liabilities",
      "Laws related to nursing practice – negligence, malpractice, breach, penalties",
      "Invasion of privacy, defamation of character",
      "Nursing regulatory mechanisms – registration, licensure, renewal, accreditation, nurse practice act, regulation for nurse practitioner/specialist nursing practice"
    ],
    pyqs: [
      {type:"Long Essay", text:"Professional Nurse – Characteristics, philosophy, aim & objectives (Jun 2024, Nov 2025)"},
      {type:"Short Notes", text:"Legal Aspects in Nursing – Malpractice & evidence (Aug 2009, Aug 2011, Feb 2013)"},
      {type:"Short Notes", text:"Consumer Protection Act provisions (Oct 2023, Oct 2025, Jun 2026)"},
      {type:"Short Notes", text:"Code of Ethics / Professional Ethics (Jun 2024, Feb 2025)"},
      {type:"Short Notes", text:"Legal responsibilities of Nurse Administrator (Oct 2025)"},
      {type:"Short Answer", text:"Types of Law & Laws related to nursing practice (Jun 2024, Jun 2026)"},
      {type:"MCQ", text:"Criminal law example – stealing hospital medications (Jun 2026)"}
    ]
  },
  {
    id: "unit18",
    title: "Unit XVIII: Professional Advancement",
    topics: [
      "Continuing Nursing Education",
      "Career opportunities",
      "Membership with professional organizations – national and international",
      "Participation in research activities",
      "Publications – journals, newspaper"
    ],
    pyqs: [
      {type:"Short Notes", text:"Professional Organization at International Level – ICN (Oct 2025, Jun 2026)"},
      {type:"Short Notes", text:"Career Opportunities in Nursing (Jun 2024)"},
      {type:"Short Notes", text:"Continuing Education importance (Feb 2025)"},
      {type:"Short Answer", text:"Importance of participation in research activities (Jun 2024)"},
      {type:"MCQ", text:"Career path for teaching/shaping future nurses – Nurse Educator (Jun 2026)"}
    ]
  }
];

/* ============================= STATE ============================= */

let state = {
  theme: "light",
  completed: {},
  activeTab: "home", // Starts on Home Dashboard
  activeSubTab: "essay", // Default subtab for PYQ bank
  activeTier: "all",
  search: "",
  hideCompleted: false,
  activeYear: YEARS[YEARS.length-1].id,
  lastVisit: null,
  streak: 0
};

function loadState(){
  try{
    const raw = safeGetItem(STORAGE_KEY);
    if(raw){
      const parsed = JSON.parse(raw);
      state = Object.assign(state, parsed);
    }
  }catch(e){ console.warn("Could not load saved progress", e); }

  // streak logic
  const today = new Date().toDateString();
  if(state.lastVisit !== today){
    const y = new Date(); y.setDate(y.getDate()-1);
    if(state.lastVisit === y.toDateString()){
      state.streak = (state.streak||0) + 1;
    } else if(state.lastVisit === null){
      state.streak = 1;
    } else {
      state.streak = 1;
    }
    state.lastVisit = today;
    saveState();
  }
}
function saveState(){
  try{ safeSetItem(STORAGE_KEY, JSON.stringify(state)); }
  catch(e){ console.warn("Could not save progress", e); }
}

function allTopics(){
  const out = [];
  Object.keys(DATA).forEach(cat=>{
    [1,2,3].forEach(tier=>{
      DATA[cat].tiers[tier].forEach((t,idx)=>{
        out.push({cat, tier, idx, id: cat+"-"+tier+"-"+idx, topic:t});
      });
    });
  });
  return out;
}

/* ============================= RENDER HELPERS ============================= */

function iconSvg(name){
  const paths = {
    "file-text":'<path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><path d="M14 2v6h6M9 13h6M9 17h6M9 9h1"/>',
    "list":'<path d="M8 6h13M8 12h13M8 18h13M3 6h.01M3 12h.01M3 18h.01"/>',
    "edit":'<path d="M11 4H4a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-7"/><path d="M18.5 2.5a2.1 2.1 0 0 1 3 3L12 15l-4 1 1-4Z"/>',
    "check-square":'<path d="M9 11l3 3L22 4"/><path d="M21 12v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h11"/>',
    "book":'<path d="M4 19.5v-15A2.5 2.5 0 0 1 6.5 2H20v20H6.5a2.5 2.5 0 0 1-2.5-2.5V19.5z"/><path d="M6 18h14"/>',
    "map":'<path d="M9 20l-6 3V6l6-3 6 3 6-3v17l-6 3-6-3zM9 3v17M15 6v17"/>',
    "archive":'<path d="M21 8v13H3V8M1 3h22v5H1zM10 12h4"/>'
  };
  return '<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">'+(paths[name]||"")+'</svg>';
}

function isDone(id){ return !!state.completed[id]; }

function toggleDone(id, btn){
  state.completed[id] = !state.completed[id];
  saveState();
  if(btn){ btn.classList.add("pulse"); setTimeout(()=>btn.classList.remove("pulse"),300); }
  renderHeroStats();
  renderMain();
}

function computeTierStats(cat, tier){
  let total=0, done=0;
  DATA[cat].tiers[tier].forEach((t,idx)=>{
    total++; if(isDone(cat+"-"+tier+"-"+idx)) done++;
  });
  return {total, done};
}

function renderHeroStats(){
  const topics = allTopics();
  const total = topics.length;
  const done = topics.filter(t=>isDone(t.id)).length;
  const pct = total? Math.round(done/total*100) : 0;

  const circumference = 2*Math.PI*56;
  const offset = circumference - (pct/100)*circumference;
  const ring = document.getElementById("ringFg");
  if(ring){
    ring.setAttribute("stroke-dasharray", circumference.toFixed(1));
    ring.setAttribute("stroke-dashoffset", offset.toFixed(1));
  }
  const pctEl = document.getElementById("ringPct");
  if(pctEl) pctEl.textContent = pct+"%";
  
  const doneEl = document.getElementById("statDone");
  if(doneEl) doneEl.textContent = done+"/"+total;

  const tier1Topics = topics.filter(t=>t.tier==1);
  const tier1Done = tier1Topics.filter(t=>isDone(t.id)).length;
  const tier1Pct = tier1Topics.length? Math.round(tier1Done/tier1Topics.length*100) : 0;
  const t1El = document.getElementById("statTier1");
  if(t1El) t1El.textContent = tier1Pct+"%";

  const streakEl = document.getElementById("streakPill");
  if(streakEl) streakEl.textContent = "🔥 " + (state.streak||0) + " day streak";

  // Dynamic guidance message
  let msg;
  if(pct===0) msg = "Start with <strong>Tier 1 — High Yield</strong> in Long Essay — those topics have shown up 3–4 times since 2009.";
  else if(pct<25) msg = "<strong>"+pct+"% cleared.</strong> Good start — keep working through Tier 1 before touching single-appearance topics.";
  else if(pct<50) msg = "<strong>"+pct+"% cleared.</strong> Over a quarter cleared! Keep your momentum going into Tier 2.";
  else if(pct<75) msg = "<strong>"+pct+"% cleared.</strong> Over halfway. Review the Year Archive now so recent phrasing feels familiar.";
  else if(pct<100) msg = "<strong>"+pct+"% cleared.</strong> Almost ready! Finish up remaining cards and review comparison pairs.";
  else msg = "<strong>100% cleared.</strong> Every tracked topic is marked done. You are fully prepared for August 10!";
  const footEl = document.getElementById("footerMsg");
  if(footEl) footEl.innerHTML = msg;
}

function tierColorVars(tier){
  return {bg:"var(--tier"+tier+"-c)", fg:"var(--tier"+tier+")"};
}

function renderComparisonCallout(){
  return `
  <div class="callout">
    <div class="callout-head">
      <div class="ic">${iconSvg("edit")}</div>
      <div>
        <h3>Compare &amp; contrast, examiners' favorite move</h3>
        <p>These pairs get reused as "differentiate X vs Y" prompts across papers — know both sides of each.</p>
      </div>
    </div>
    <div class="pairs">
      ${COMPARISON_PAIRS.map(p=>`<div class="pair"><b>${p[0]}</b><span class="vs">vs</span>${p[1]}</div>`).join("")}
    </div>
  </div>`;
}

function cardHtml(cat, tier, idx, t){
  const id = cat+"-"+tier+"-"+idx;
  const done = isDone(id);
  const tc = tierColorVars(tier);
  const initials = t.title.split(" ").filter(w=>w.length>2 || /[A-Z]/.test(w[0])).slice(0,2).map(w=>w[0]).join("").toUpperCase() || "•";
  
  let mcqBlock = "";
  if(t.options && t.options.length){
    mcqBlock = `
    <div style="margin:10px 0;">
      ${t.qText ? `<strong style="font-size:13.5px;display:block;margin-bottom:8px;color:var(--ink);">${t.qText}</strong>` : ""}
      <ul class="mcq-options">
        ${t.options.map((opt, i) => {
          const letter = String.fromCharCode(65 + i);
          const ansStr = (t.answer || "").toUpperCase();
          const isCorrect = (letter === ansStr || opt.trim().toUpperCase().startsWith(ansStr) || opt.trim().toUpperCase().startsWith("(" + ansStr + ")"));
          return `<li class="mcq-opt ${isCorrect ? 'correct' : ''}">${opt}</li>`;
        }).join("")}
      </ul>
    </div>`;
  }

  return `
  <div class="card ${done?'done':''}" data-id="${id}">
    <div>
      <div class="card-top">
        <div class="card-icon" style="background:${tc.bg};color:${tc.fg}">${initials}</div>
        <div class="card-title-wrap">
          <p class="card-title">${t.title}</p>
          <span class="freq-badge" style="background:${tc.bg};color:${tc.fg}">×${t.freq} repeats</span>
          <div class="card-years">${t.years.join(" · ")}</div>
        </div>
      </div>
      ${t.points && t.points.length ? `<ul class="card-points">${t.points.map(p=>`<li>${p}</li>`).join("")}</ul>` : ""}
      ${mcqBlock}
    </div>
    <div class="card-actions">
      <button class="mark-btn ${done?'on':''}" data-id="${id}" type="button" aria-label="Mark ${t.title} as completed">
        ${iconSvg("check-square")} <span>${done?'Completed':'Mark complete'}</span>
      </button>
    </div>
  </div>`;
}

/* ============================= RENDER TABS & VIEWS ============================= */

function renderHomeDashboard(){
  return `
  <section class="hero">
    <div class="ring-wrap">
      <svg width="132" height="132" viewBox="0 0 132 132">
        <circle class="ring-bg" cx="66" cy="66" r="56"></circle>
        <circle class="ring-fg" id="ringFg" cx="66" cy="66" r="56" stroke-dasharray="352" stroke-dashoffset="352"></circle>
      </svg>
      <div class="ring-center">
        <span class="num" id="ringPct">0%</span>
        <span class="lbl">Prepared</span>
      </div>
    </div>
    <div class="hero-info">
      <h2>Your revision vitals — 48 Hours to Exam!</h2>
      <p>Frequency-ranked topics from 16 question papers (Feb 2009 – Jul 2026), mapped to your exact INC 18-Unit Syllabus, with MCQs structured and answers highlighted.</p>
      <div class="hero-stats">
        <div class="hero-stat"><div class="n" id="statDone">0/0</div><div class="l">Topics cleared</div></div>
        <div class="hero-stat"><div class="n" id="statTier1">0%</div><div class="l">High-yield done</div></div>
        <div class="hero-stat"><div class="n">16</div><div class="l">Papers archived</div></div>
      </div>
    </div>
  </section>

  <div class="section-heading">
    <span>PYQ Question Banks</span>
    <span>Filter by marks</span>
  </div>
  <div class="launch-grid">
    <div class="launch-card" data-launch="pyq" data-sub="essay">
      <div class="launch-card-info">
        <h4>Long Essay</h4>
        <p>15 / 20 Marks · 21 Ranked Topics</p>
      </div>
      <div class="ic">${iconSvg("file-text")}</div>
    </div>
    <div class="launch-card" data-launch="pyq" data-sub="shortNotes">
      <div class="launch-card-info">
        <h4>Short Notes</h4>
        <p>5 Marks each · 46 Ranked Topics</p>
      </div>
      <div class="ic">${iconSvg("list")}</div>
    </div>
    <div class="launch-card" data-launch="pyq" data-sub="shortAnswer">
      <div class="launch-card-info">
        <h4>Short Answer</h4>
        <p>2 Marks each · 51 Ranked Topics</p>
      </div>
      <div class="ic">${iconSvg("edit")}</div>
    </div>
    <div class="launch-card" data-launch="pyq" data-sub="mcq">
      <div class="launch-card-info">
        <h4>MCQ / Objective</h4>
        <p>1 Mark each · 29 Repeats + Answers</p>
      </div>
      <div class="ic">${iconSvg("check-square")}</div>
    </div>
  </div>

  <div class="section-heading">
    <span>Official Exam Resources</span>
    <span>Google Drive &amp; Docs</span>
  </div>
  <div class="launch-grid">
    <a class="launch-card" href="https://drive.google.com/drive/folders/1lIu6myYADtGdOJ5rkWwL4xKIlFPrUgDL" target="_blank" rel="noopener noreferrer">
      <div class="launch-card-info">
        <h4>Original NMLE PYQ Papers</h4>
        <p>Access official question paper PDFs directly in Drive</p>
      </div>
      <div class="ic">${iconSvg("book")}</div>
    </a>
    <a class="launch-card" href="https://docs.google.com/document/d/1VmmGQXDhA3ZdvOijFAoGqCRqw3SHnRrduNtLSowO4D8/edit?usp=sharing" target="_blank" rel="noopener noreferrer">
      <div class="launch-card-info">
        <h4>Content Reference Document</h4>
        <p>Shared Google Doc with comprehensive study notes</p>
      </div>
      <div class="ic">${iconSvg("file-text")}</div>
    </a>
  </div>

  <div class="section-heading">
    <span>Study Tools &amp; Syllabus</span>
    <span>Sprint &amp; Reference</span>
  </div>
  <div class="launch-grid">
    <div class="launch-card" data-launch="syllabus">
      <div class="launch-card-info">
        <h4>Syllabus &amp; PYQs</h4>
        <p>Complete INC Units I–XVIII with mapped PYQs</p>
      </div>
      <div class="ic">${iconSvg("book")}</div>
    </div>
    <div class="launch-card" data-launch="sprint">
      <div class="launch-card-info">
        <h4>48-Hr Sprint Plan</h4>
        <p>August 8–10 emergency high-yield schedule</p>
      </div>
      <div class="ic">${iconSvg("map")}</div>
    </div>
    <div class="launch-card" data-launch="archive">
      <div class="launch-card-info">
        <h4>Year Archive</h4>
        <p>Every paper (2009–2026) reproduced verbatim</p>
      </div>
      <div class="ic">${iconSvg("archive")}</div>
    </div>
  </div>

  ${renderComparisonCallout()}`;
}

function renderPYQBankTab(subCat){
  const d = DATA[subCat];
  const search = state.search.toLowerCase();
  let html = "";

  // Sub-navigation bar at the top of PYQ Bank
  const subTabs = [
    {id:"essay", label:"Long Essay", icon:"file-text"},
    {id:"shortNotes", label:"Short Notes", icon:"list"},
    {id:"shortAnswer", label:"Short Answer", icon:"edit"},
    {id:"mcq", label:"MCQ + Answers", icon:"check-square"}
  ];

  html += `
  <div class="sub-nav">
    ${subTabs.map(t=>`
      <div class="sub-tab ${state.activeSubTab===t.id?'active':''}" data-subtab="${t.id}">
        ${iconSvg(t.icon)} ${t.label}
      </div>`).join("")}
  </div>`;

  // Compare and contrast box removed from Long Essay view as it is already displayed on Home

  html += `
  <div class="controls">
    <div class="search-box">
      ${iconSvg("edit")}
      <input type="text" id="searchInput" placeholder="Search ${d.label.toLowerCase()} topics…" value="${state.search.replace(/"/g,'&quot;')}">
    </div>
    <div class="chip ${state.activeTier==='all'?'active':''}" data-tier="all">All tiers</div>
    <div class="chip ${state.activeTier=='1'?'active':''}" data-tier="1"><span class="sw" style="background:var(--tier1)"></span>Tier 1</div>
    <div class="chip ${state.activeTier=='2'?'active':''}" data-tier="2"><span class="sw" style="background:var(--tier2)"></span>Tier 2</div>
    <div class="chip ${state.activeTier=='3'?'active':''}" data-tier="3"><span class="sw" style="background:var(--tier3)"></span>Tier 3</div>
    <div class="toggle-row" id="hideCompletedToggle">
      <div class="switch ${state.hideCompleted?'on':''}"></div> Hide completed
    </div>
  </div>`;

  const tiersToShow = state.activeTier === "all" ? [1,2,3] : [Number(state.activeTier)];
  let anyRendered = false;

  tiersToShow.forEach(tier=>{
    let topics = d.tiers[tier].map((t,idx)=>({t, idx})).filter(o=>{
      if(search && !o.t.title.toLowerCase().includes(search) && !(o.t.points||[]).join(" ").toLowerCase().includes(search) && !(o.t.qText||"").toLowerCase().includes(search)) return false;
      if(state.hideCompleted && isDone(subCat+"-"+tier+"-"+o.idx)) return false;
      return true;
    });
    if(!topics.length) return;
    anyRendered = true;
    const stats = computeTierStats(subCat, tier);
    const pct = stats.total? Math.round(stats.done/stats.total*100) : 0;
    const meta = TIER_META[tier];
    const tc = tierColorVars(tier);
    html += `
    <div class="tier-section">
      <div class="tier-header">
        <span class="tier-badge" style="background:${tc.bg};color:${tc.fg}">${meta.label}</span>
        <span class="sub">${meta.note}</span>
        <div class="tier-bar-track"><div class="tier-bar-fill" style="width:${pct}%;background:${tc.fg}"></div></div>
        <span class="tier-pct">${pct}%</span>
      </div>
      <div class="grid">
        ${topics.map(o=>cardHtml(subCat, tier, o.idx, o.t)).join("")}
      </div>
    </div>`;
  });

  if(!anyRendered){
    html += `<div class="empty-state">${iconSvg("edit")}<p>No topics match your search or filters.</p></div>`;
  }

  return html;
}

function renderSyllabusTab(){
  return `
  <div class="year-paper" style="margin-bottom:20px;">
    <div class="year-paper-head">
      <span class="tag">INC Syllabus Mapping</span>
      <h3>Complete 18-Unit Syllabus &amp; Categorized PYQs</h3>
      <p>Every syllabus subtopic from Unit I to XVIII reproduced verbatim without omission, accompanied by relevant previous year questions.</p>
    </div>
  </div>
  <div class="syl-list">
    ${SYLLABUS_UNITS.map(u => `
      <div class="syl-unit" id="${u.id}">
        <div class="syl-unit-head">
          <h3>${u.title}</h3>
          <span class="syl-tag">${u.pyqs.length} PYQs Mapped</span>
        </div>
        <div class="syl-body">
          <div class="syl-topics">
            <h4>Syllabus Subtopics</h4>
            <ul>
              ${u.topics.map(topic => `<li>${topic}</li>`).join("")}
            </ul>
          </div>
          <div class="syl-pyqs">
            <h4>Mapped Examination Questions</h4>
            ${u.pyqs.length ? u.pyqs.map(p => `
              <div class="syl-pyq-item">
                <span>${p.text}</span>
                <b>[${p.type}]</b>
              </div>`).join("") : `<p class="q-empty">No direct PYQ mapped in recent papers — review syllabus concepts.</p>`}
          </div>
        </div>
      </div>
    `).join("")}
  </div>`;
}

function renderSprintTab(){
  return `
  <div class="year-paper">
    <div class="year-paper-head">
      <span class="tag">Emergency Exam Schedule</span>
      <h3>48-Hour Exam Sprint — Countdown to August 10!</h3>
      <p>High-yield triage designed to maximize your marks in 2 remaining study days.</p>
    </div>
    <div class="stepper">
      ${STUDY_PLAN.map((s,i)=>`
        <div class="step">
          <div class="step-num">${i+1}</div>
          <div class="step-card">
            <span class="date-tag">${s.date}</span>
            <h4>${s.title}</h4>
            <p>${s.body}</p>
          </div>
        </div>`).join("")}
    </div>
  </div>
  ${renderComparisonCallout()}`;
}

function renderArchiveTab(){
  const year = YEARS.find(y=>y.id===state.activeYear) || YEARS[YEARS.length-1];
  return `
  <div class="year-picker" id="yearPicker">
    ${YEARS.map(y=>`
      <div class="year-chip ${y.id===year.id?'active':''}" data-year="${y.id}">
        <span class="yr">${y.yr}</span><span class="mo">${y.mo}</span>
      </div>`).join("")}
  </div>
  <div class="year-paper">
    <div class="year-paper-head">
      <span class="tag">${year.label}</span>
      <h3>${year.exam}</h3>
      <p>${year.code}</p>
    </div>
    <div class="paper-section">
      <div class="paper-section-title">Long Essay <span class="n">${year.essay.length} question${year.essay.length===1?'':'s'}</span></div>
      ${year.essay.length ? `<ul class="q-list">${year.essay.map(q=>`<li>${q.replace(/\n/g,'<br>')}</li>`).join("")}</ul>` : `<p class="q-empty">No questions of this type in this paper.</p>`}
    </div>
    <div class="paper-section">
      <div class="paper-section-title">Short Notes <span class="n">${year.shortNotes.length} question${year.shortNotes.length===1?'':'s'}</span></div>
      ${year.shortNotes.length ? `<ul class="q-list">${year.shortNotes.map(q=>`<li>${q.replace(/\n/g,'<br>')}</li>`).join("")}</ul>` : `<p class="q-empty">No questions of this type in this paper.</p>`}
    </div>
    <div class="paper-section">
      <div class="paper-section-title">Short Answer <span class="n">${year.shortAnswer.length} question${year.shortAnswer.length===1?'':'s'}</span></div>
      ${year.shortAnswer.length ? `<ul class="q-list">${year.shortAnswer.map(q=>`<li>${q.replace(/\n/g,'<br>')}</li>`).join("")}</ul>` : `<p class="q-empty">No questions of this type in this paper.</p>`}
    </div>
    <div class="paper-section">
      <div class="paper-section-title">MCQ / Objective <span class="n">${year.mcq.length} question${year.mcq.length===1?'':'s'}</span></div>
      ${year.mcq.length ? `
        <ul class="q-list">
          ${year.mcq.map(m => {
            if(typeof m === "string"){
              return `<li>${m}</li>`;
            } else {
              return `
              <li>
                <strong>${m.q}</strong>
                <ul class="mcq-options">
                  ${m.options.map((opt, i) => {
                    const letter = String.fromCharCode(65 + i);
                    const isCorrect = (letter === m.answer.toUpperCase() || opt.trim().toUpperCase().startsWith(m.answer.toUpperCase()) || opt.trim().toUpperCase().startsWith("(" + m.answer.toUpperCase() + ")"));
                    return `<li class="mcq-opt ${isCorrect ? 'correct' : ''}">${opt}</li>`;
                  }).join("")}
                </ul>
              </li>`;
            }
          }).join("")}
        </ul>` : `<p class="q-empty">No questions of this type in this paper.</p>`}
    </div>
  </div>`;
}

/* ============================= NAVIGATION CONTROLLER ============================= */

function updateBottomNavUI(){
  document.querySelectorAll(".b-tab").forEach(tab=>{
    if(tab.dataset.tab === state.activeTab){
      tab.classList.add("active");
    } else {
      tab.classList.remove("active");
    }
  });
}

function renderMain(){
  const area = document.getElementById("mainArea");
  if(!area) return;

  if(state.activeTab === "home"){
    area.innerHTML = renderHomeDashboard();
    bindHomeEvents();
  } else if(state.activeTab === "pyq"){
    area.innerHTML = renderPYQBankTab(state.activeSubTab);
    bindPYQBankEvents();
  } else if(state.activeTab === "syllabus"){
    area.innerHTML = renderSyllabusTab();
  } else if(state.activeTab === "sprint"){
    area.innerHTML = renderSprintTab();
  } else if(state.activeTab === "archive"){
    area.innerHTML = renderArchiveTab();
    bindArchiveEvents();
  }

  updateBottomNavUI();
  renderHeroStats();
  bindMarkButtons();
}

function bindHomeEvents(){
  document.querySelectorAll(".launch-card[data-launch]").forEach(card=>{
    card.addEventListener("click", ()=>{
      const launch = card.dataset.launch;
      const sub = card.dataset.sub;
      state.activeTab = launch;
      if(sub) state.activeSubTab = sub;
      state.activeTier = "all";
      state.search = "";
      saveState();
      renderMain();
      window.scrollTo({top:0, behavior:"smooth"});
    });
  });
}

function bindPYQBankEvents(){
  // Sub-tabs switching
  document.querySelectorAll(".sub-tab[data-subtab]").forEach(el=>{
    el.addEventListener("click", ()=>{
      state.activeSubTab = el.dataset.subtab;
      state.activeTier = "all";
      state.search = "";
      saveState();
      renderMain();
    });
  });

  const input = document.getElementById("searchInput");
  if(input){
    input.addEventListener("input", (e)=>{
      state.search = e.target.value;
      renderMain();
      const newIn = document.getElementById("searchInput");
      if(newIn){
        newIn.focus();
        newIn.selectionStart = newIn.selectionEnd = newIn.value.length;
      }
    });
  }
  document.querySelectorAll(".chip[data-tier]").forEach(el=>{
    el.addEventListener("click", ()=>{
      state.activeTier = el.dataset.tier;
      saveState();
      renderMain();
    });
  });
  const hideToggle = document.getElementById("hideCompletedToggle");
  if(hideToggle){
    hideToggle.addEventListener("click", ()=>{
      state.hideCompleted = !state.hideCompleted;
      saveState();
      renderMain();
    });
  }
}

function bindArchiveEvents(){
  document.querySelectorAll(".year-chip").forEach(el=>{
    el.addEventListener("click", ()=>{
      state.activeYear = el.dataset.year;
      saveState();
      renderMain();
    });
  });
}

/* ============================= RELIABLE CLICK HANDLERS FOR MARK COMPLETE ============================= */
function bindMarkButtons(){
  document.querySelectorAll(".mark-btn").forEach(btn => {
    btn.addEventListener("click", function(e){
      e.preventDefault();
      e.stopPropagation();
      const id = this.dataset.id;
      if(id){
        toggleDone(id, this);
      }
    });
  });
}

// Backup event delegation on mainArea
document.getElementById("mainArea").addEventListener("click", (e)=>{
  const btn = e.target.closest(".mark-btn");
  if(btn && btn.dataset.id){
    e.stopPropagation();
    toggleDone(btn.dataset.id, btn);
  }
});

/* ============================= BOTTOM NAV LISTENERS ============================= */
document.querySelectorAll(".b-tab[data-tab]").forEach(tab=>{
  tab.addEventListener("click", ()=>{
    state.activeTab = tab.dataset.tab;
    state.activeTier = "all";
    state.search = "";
    saveState();
    renderMain();
    window.scrollTo({top:0, behavior:"smooth"});
  });
});

/* ============================= THEME ============================= */
function applyTheme(){
  document.documentElement.setAttribute("data-theme", state.theme);
  const icon = document.getElementById("themeIcon");
  if(state.theme === "dark"){
    icon.innerHTML = '<path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"/>';
  } else {
    icon.innerHTML = '<circle cx="12" cy="12" r="4"/><path d="M12 2v2M12 20v2M4.9 4.9l1.4 1.4M17.7 17.7l1.4 1.4M2 12h2M20 12h2M4.9 19.1l1.4-1.4M17.7 6.3l1.4-1.4"/>';
  }
}

document.getElementById("themeToggle").addEventListener("click", ()=>{
  state.theme = state.theme === "dark" ? "light" : "dark";
  saveState();
  applyTheme();
});

/* ============================= RESET / EXPORT / IMPORT ============================= */
document.getElementById("resetBtn").addEventListener("click", ()=>{
  if(confirm("This clears every checkbox you've marked across all question types. Continue?")){
    state.completed = {};
    saveState();
    renderHeroStats();
    renderMain();
  }
});

document.getElementById("exportBtn").addEventListener("click", ()=>{
  const blob = new Blob([JSON.stringify(state, null, 2)], {type:"application/json"});
  const url = URL.createObjectURL(blob);
  const a = document.createElement("a");
  a.href = url; a.download = "chart-rounds-progress.json";
  document.body.appendChild(a); a.click(); document.body.removeChild(a);
  URL.revokeObjectURL(url);
});

document.getElementById("importBtn").addEventListener("click", ()=>{
  document.getElementById("importFile").click();
});
document.getElementById("importFile").addEventListener("change", (e)=>{
  const file = e.target.files[0];
  if(!file) return;
  const reader = new FileReader();
  reader.onload = (ev)=>{
    try{
      const parsed = JSON.parse(ev.target.result);
      if(parsed && typeof parsed === "object"){
        state = Object.assign(state, parsed);
        saveState();
        applyTheme();
        renderMain();
        alert("Progress imported successfully!");
      }
    }catch(err){
      alert("That file doesn't look like a valid progress export.");
    }
  };
  reader.readAsText(file);
  e.target.value = "";
});

/* ============================= INIT ============================= */
loadState();
applyTheme();
renderMain();
</script>
</body>
</html>
