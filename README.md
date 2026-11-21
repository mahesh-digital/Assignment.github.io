# Assignment.github.io
/* Horizon University – shared styles */
:root{
  --bg:#f7f5f0; --surface:#ffffff; --ink:#1a2238; --muted:#5b6478; --line:#e3dfd5;
  --brand:#1b2a5c; --brand-2:#2f4a9e; --accent:#d9a441; --accent-ink:#3a2a05;
  --ok:#1f7a4d; --warn:#b26a00; --bad:#b3261e; --soft:#eef1fa;
  --radius:14px; --shadow:0 6px 24px rgba(27,42,92,.08);
  --font:'Inter',system-ui,-apple-system,Segoe UI,Roboto,sans-serif;
  --serif:'Fraunces',Georgia,'Times New Roman',serif;
}
@media (prefers-color-scheme:dark){
  :root{--bg:#0f1424;--surface:#171e35;--ink:#eceff8;--muted:#a3adc7;--line:#2a3354;--brand:#8fa8ff;--brand-2:#a9bcff;--soft:#1d2644;--accent-ink:#2b1f04;--shadow:0 6px 24px rgba(0,0,0,.35)}
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;font-family:var(--font);background:var(--bg);color:var(--ink);line-height:1.6;font-size:16px}
h1,h2,h3,h4{font-family:var(--serif);line-height:1.2;margin:0 0 .5em;color:var(--ink)}
h1{font-size:clamp(2rem,5vw,3.2rem)} h2{font-size:clamp(1.5rem,3vw,2.1rem)} h3{font-size:1.2rem}
a{color:var(--brand-2)} img{max-width:100%}
.container{width:min(1140px,100% - 32px);margin-inline:auto}
.section{padding:56px 0}
.section.alt{background:var(--soft)}
.lead{font-size:1.15rem;color:var(--muted);max-width:62ch}
.muted{color:var(--muted)} .small{font-size:.88rem}
.center{text-align:center}
.eyebrow{text-transform:uppercase;letter-spacing:.12em;font-size:.75rem;font-weight:700;color:var(--accent);margin-bottom:8px}

/* Header / nav */
.site-header{position:sticky;top:0;z-index:50;background:var(--surface);border-bottom:1px solid var(--line)}
.nav-wrap{display:flex;align-items:center;justify-content:space-between;gap:16px;min-height:68px}
.logo{display:flex;align-items:center;gap:10px;text-decoration:none;color:var(--ink);font-family:var(--serif);font-weight:700;font-size:1.2rem}
.logo-mark{width:36px;height:36px;border-radius:10px;background:var(--brand);color:#fff;display:grid;place-items:center;font-size:1.1rem}
@media (prefers-color-scheme:dark){.logo-mark{background:var(--accent);color:var(--accent-ink)}}
.menu{display:flex;align-items:center;gap:4px;list-style:none;margin:0;padding:0}
.menu>li{position:relative}
.menu a,.menu button.dd{display:block;padding:10px 12px;border-radius:8px;text-decoration:none;color:var(--ink);font:inherit;font-size:.95rem;background:none;border:0;cursor:pointer}
.menu a:hover,.menu button.dd:hover,.menu a.active,.menu button.dd.active{background:var(--soft);color:var(--brand-2)}
.menu .caret{font-size:.7em;margin-left:4px}
.submenu{display:none;position:absolute;left:0;top:100%;min-width:230px;background:var(--surface);border:1px solid var(--line);border-radius:12px;box-shadow:var(--shadow);padding:6px;list-style:none;margin:0}
.menu li:hover>.submenu,.menu li:focus-within>.submenu,.menu li.open>.submenu{display:block}
.nav-cta{display:flex;align-items:center;gap:8px}
.burger{display:none;background:none;border:1px solid var(--line);border-radius:8px;padding:8px 10px;font-size:1.2rem;cursor:pointer;color:var(--ink)}
@media (max-width:960px){
  .burger{display:block}
  .nav-panel{display:none;position:absolute;left:0;right:0;top:100%;background:var(--surface);border-bottom:1px solid var(--line);padding:12px 16px 20px}
  .nav-panel.open{display:block}
  .menu{flex-direction:column;align-items:stretch}
  .submenu{position:static;display:block;box-shadow:none;border:0;padding:0 0 0 14px}
  .nav-cta{margin-top:10px}
}

/* Buttons & forms */
.btn{display:inline-flex;align-items:center;gap:8px;padding:11px 20px;border-radius:10px;border:1px solid transparent;font:inherit;font-weight:600;cursor:pointer;text-decoration:none;background:var(--brand);color:#fff;transition:transform .08s,opacity .15s}
@media (prefers-color-scheme:dark){.btn{background:var(--brand);color:#0f1424}}
.btn:hover{opacity:.92} .btn:active{transform:translateY(1px)}
.btn.accent{background:var(--accent);color:var(--accent-ink)}
.btn.ghost{background:transparent;color:var(--brand-2);border-color:var(--line)}
.btn.danger{background:var(--bad);color:#fff}
.btn.sm{padding:6px 12px;font-size:.85rem;border-radius:8px}
.btn[disabled]{opacity:.5;cursor:not-allowed}
label{display:block;font-weight:600;font-size:.9rem;margin-bottom:4px}
input,select,textarea{width:100%;padding:11px 12px;border:1px solid var(--line);border-radius:10px;background:var(--surface);color:var(--ink);font:inherit}
input:focus,select:focus,textarea:focus,.btn:focus-visible,a:focus-visible,button:focus-visible{outline:3px solid color-mix(in srgb,var(--brand-2) 45%,transparent);outline-offset:1px}
textarea{min-height:110px;resize:vertical}
.field{margin-bottom:16px}
.grid{display:grid;gap:20px}
.g2{grid-template-columns:repeat(2,1fr)} .g3{grid-template-columns:repeat(3,1fr)} .g4{grid-template-columns:repeat(4,1fr)}
@media (max-width:900px){.g3,.g4{grid-template-columns:repeat(2,1fr)}}
@media (max-width:620px){.g2,.g3,.g4{grid-template-columns:1fr}}
.form-error{color:var(--bad);font-size:.85rem;margin-top:4px}

/* Cards, badges, tables */
.card{background:var(--surface);border:1px solid var(--line);border-radius:var(--radius);padding:22px;box-shadow:var(--shadow)}
.card h3{margin-bottom:6px}
.stat{font-family:var(--serif);font-size:2rem;font-weight:700;color:var(--brand-2)}
.badge{display:inline-block;padding:2px 10px;border-radius:999px;font-size:.75rem;font-weight:700;background:var(--soft);color:var(--brand-2)}
.badge.ok{background:#dff3e8;color:var(--ok)} .badge.warn{background:#fdf0d5;color:var(--warn)} .badge.bad{background:#fbe2df;color:var(--bad)}
.table-wrap{overflow-x:auto}
table{width:100%;border-collapse:collapse;background:var(--surface);border-radius:12px;overflow:hidden}
th,td{padding:11px 14px;text-align:left;border-bottom:1px solid var(--line);font-size:.93rem}
th{background:var(--soft);font-size:.8rem;text-transform:uppercase;letter-spacing:.05em;color:var(--muted)}
.tabs{display:flex;gap:6px;border-bottom:1px solid var(--line);margin-bottom:20px;flex-wrap:wrap}
.tab{padding:10px 16px;border:0;background:none;font:inherit;font-weight:600;cursor:pointer;color:var(--muted);border-bottom:3px solid transparent}
.tab.active{color:var(--brand-2);border-color:var(--accent)}

/* Hero */
.hero{background:linear-gradient(135deg,#14214d 0%,#2f4a9e 100%);color:#fff;padding:84px 0 72px;position:relative;overflow:hidden}
.hero::after{content:"";position:absolute;right:-120px;top:-120px;width:420px;height:420px;border-radius:50%;background:radial-gradient(circle,rgba(217,164,65,.45),transparent 70%)}
.hero h1,.hero p{color:#fff;position:relative;z-index:1} .hero p{opacity:.9;max-width:58ch;font-size:1.15rem}
.hero .actions{display:flex;gap:12px;flex-wrap:wrap;margin-top:24px;position:relative;z-index:1}
.hero .btn{background:var(--accent);color:var(--accent-ink)} .hero .btn.ghost{background:transparent;color:#fff;border-color:rgba(255,255,255,.5)}
.page-head{background:var(--soft);padding:40px 0;border-bottom:1px solid var(--line)}
.page-head h1{font-size:clamp(1.8rem,4vw,2.5rem);margin-bottom:6px}

/* Timeline / stepper */
.steps{counter-reset:s;display:grid;gap:14px}
.step{display:flex;gap:16px;align-items:flex-start}
.step::before{counter-increment:s;content:counter(s);flex:none;width:38px;height:38px;border-radius:50%;background:var(--accent);color:var(--accent-ink);display:grid;place-items:center;font-weight:800}
.stepper{display:flex;gap:6px;margin-bottom:24px;flex-wrap:wrap}
.stepper span{flex:1;min-width:90px;text-align:center;padding:8px;border-radius:8px;background:var(--soft);font-size:.82rem;font-weight:600;color:var(--muted)}
.stepper span.on{background:var(--brand);color:#fff} .stepper span.done{background:#dff3e8;color:var(--ok)}
@media (prefers-color-scheme:dark){.stepper span.on{color:#0f1424}}

/* Timetable */
.tt{display:grid;grid-template-columns:60px repeat(5,1fr);border:1px solid var(--line);border-radius:12px;overflow:hidden;background:var(--surface);min-width:760px}
.tt .h{background:var(--soft);font-weight:700;padding:8px;text-align:center;font-size:.85rem}
.tt .t{font-size:.75rem;color:var(--muted);padding:4px 6px;border-top:1px solid var(--line);height:56px}
.tt .col{position:relative;border-left:1px solid var(--line)}
.tt .col .slot{height:56px;border-top:1px solid var(--line)}
.tt .evt{position:absolute;left:3px;right:3px;border-radius:8px;padding:5px 7px;font-size:.75rem;line-height:1.25;color:#fff;overflow:hidden}

/* Misc */
.toast{position:fixed;bottom:24px;left:50%;transform:translateX(-50%);background:var(--ink);color:var(--bg);padding:12px 20px;border-radius:10px;z-index:100;box-shadow:var(--shadow);max-width:90vw}
.alert{padding:12px 16px;border-radius:10px;background:var(--soft);border:1px solid var(--line);margin-bottom:16px}
.alert.warn{background:#fdf0d5;color:#5a3a00;border-color:#efd69b}
.alert.ok{background:#dff3e8;color:#14532d;border-color:#b6e0c8}
.progress{height:10px;background:var(--soft);border-radius:999px;overflow:hidden}
.progress>div{height:100%;background:var(--accent);border-radius:999px;transition:width .3s}
.list-clean{list-style:none;padding:0;margin:0}
.list-clean li{padding:10px 0;border-bottom:1px solid var(--line)}
.list-clean li:last-child{border:0}
details{background:var(--surface);border:1px solid var(--line);border-radius:12px;padding:14px 18px;margin-bottom:10px}
summary{cursor:pointer;font-weight:600}
.site-footer{background:#101a3d;color:#c9d1ee;padding:48px 0 24px;margin-top:40px}
.site-footer a{color:#e6ebff;text-decoration:none} .site-footer a:hover{text-decoration:underline}
.site-footer h4{color:#fff;font-family:var(--font);font-size:.95rem}
.site-footer ul{list-style:none;padding:0;margin:0} .site-footer li{margin-bottom:6px}
.footer-bottom{border-top:1px solid rgba(255,255,255,.15);margin-top:28px;padding-top:16px;font-size:.85rem}
.toolbar{display:flex;gap:12px;flex-wrap:wrap;margin-bottom:20px;align-items:end}
.toolbar>*{flex:1;min-width:170px}
.hidden{display:none!important}
@media print{.site-header,.site-footer,.btn,.toolbar{display:none!important}body{background:#fff}}
