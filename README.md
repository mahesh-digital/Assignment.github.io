<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8"><meta name="viewport" content="width=device-width,initial-scale=1">
<title>Mahesh Kumar – Portfolio</title>
<meta name="description" content="Personal portfolio of Mahesh Kumar: about, education, skills, projects, certifications and contact.">
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Space+Grotesk:wght@600;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#f6f7fb;--surface:#fff;--ink:#14182b;--muted:#5d6580;--line:#e2e5f0;--brand:#4f46e5;--brand2:#06b6d4;--soft:#eceefc;--shadow:0 8px 28px rgba(30,35,90,.08)}
:root[data-theme=dark]{--bg:#0c1020;--surface:#151a30;--ink:#eef0fb;--muted:#9aa3c4;--line:#252c4a;--brand:#8b93ff;--brand2:#22d3ee;--soft:#1b2140;--shadow:0 8px 28px rgba(0,0,0,.4)}
*{box-sizing:border-box}html{scroll-behavior:smooth;scroll-padding-top:76px}
body{margin:0;font-family:Inter,system-ui,sans-serif;background:var(--bg);color:var(--ink);line-height:1.65}
h1,h2,h3{font-family:'Space Grotesk',Inter,sans-serif;line-height:1.15;margin:0 0 .5em}
a{color:var(--brand)}.container{width:min(1080px,100% - 32px);margin-inline:auto}
section{padding:80px 0}section.alt{background:var(--soft)}
.tag-h{font-size:.78rem;font-weight:700;letter-spacing:.14em;text-transform:uppercase;color:var(--brand)}
h2{font-size:clamp(1.7rem,3.5vw,2.4rem)}
.muted{color:var(--muted)}
/* nav */
header{position:fixed;inset:0 0 auto 0;z-index:50;background:color-mix(in srgb,var(--surface) 88%,transparent);backdrop-filter:blur(10px);border-bottom:1px solid var(--line)}
.nav{display:flex;align-items:center;justify-content:space-between;height:64px}
.logo{font-family:'Space Grotesk';font-weight:700;font-size:1.2rem;text-decoration:none;color:var(--ink)}
.logo span{background:linear-gradient(135deg,var(--brand),var(--brand2));color:#fff;border-radius:8px;padding:2px 8px;margin-right:8px}
nav ul{display:flex;gap:2px;list-style:none;margin:0;padding:0}
nav a{display:block;padding:8px 12px;border-radius:8px;text-decoration:none;color:var(--ink);font-size:.93rem}
nav a:hover,nav a.active{background:var(--soft);color:var(--brand)}
.icon-btn{background:none;border:1px solid var(--line);border-radius:8px;padding:7px 10px;cursor:pointer;color:var(--ink);font-size:1rem}
.right{display:flex;gap:8px}.burger{display:none}
@media(max-width:860px){.burger{display:block}nav{position:absolute;left:0;right:0;top:64px;background:var(--surface);border-bottom:1px solid var(--line);display:none;padding:10px 16px}nav.open{display:block}nav ul{flex-direction:column}}
/* hero */
.hero{padding:150px 0 80px;background:radial-gradient(900px 400px at 85% -10%,color-mix(in srgb,var(--brand) 22%,transparent),transparent),radial-gradient(700px 400px at 0 20%,color-mix(in srgb,var(--brand2) 18%,transparent),transparent)}
.hero h1{font-size:clamp(2.4rem,6.5vw,4.4rem)}
.grad{background:linear-gradient(135deg,var(--brand),var(--brand2));-webkit-background-clip:text;background-clip:text;color:transparent}
.hero p.lead{font-size:1.2rem;color:var(--muted);max-width:60ch}
.btns{display:flex;gap:12px;flex-wrap:wrap;margin:26px 0}
.btn{display:inline-block;padding:12px 22px;border-radius:10px;font-weight:600;text-decoration:none;border:1px solid transparent;cursor:pointer;font:inherit;font-weight:600}
.btn.p{background:linear-gradient(135deg,var(--brand),var(--brand2));color:#fff}.btn.g{border-color:var(--line);color:var(--ink);background:var(--surface)}
.btn:hover{transform:translateY(-1px)}
.stats{display:grid;grid-template-columns:repeat(4,1fr);gap:16px;margin-top:40px}
.stat{background:var(--surface);border:1px solid var(--line);border-radius:14px;padding:18px;text-align:center;box-shadow:var(--shadow)}
.stat b{display:block;font-family:'Space Grotesk';font-size:1.9rem;color:var(--brand)}
@media(max-width:700px){.stats{grid-template-columns:repeat(2,1fr)}}
/* cards */
.grid{display:grid;gap:20px}.g2{grid-template-columns:repeat(2,1fr)}.g3{grid-template-columns:repeat(3,1fr)}
@media(max-width:860px){.g3{grid-template-columns:repeat(2,1fr)}}@media(max-width:620px){.g2,.g3{grid-template-columns:1fr}}
.card{background:var(--surface);border:1px solid var(--line);border-radius:16px;padding:24px;box-shadow:var(--shadow)}
.pill{display:inline-block;padding:3px 12px;margin:3px 4px 3px 0;border-radius:999px;background:var(--soft);color:var(--brand);font-size:.8rem;font-weight:600}
.facts{list-style:none;padding:0;margin:0}.facts li{display:flex;justify-content:space-between;gap:12px;padding:10px 0;border-bottom:1px solid var(--line)}.facts li:last-child{border:0}
.timeline{border-left:2px solid var(--line);margin-left:8px;padding-left:26px;display:grid;gap:22px}
.tl{position:relative}.tl::before{content:"";position:absolute;left:-34px;top:8px;width:14px;height:14px;border-radius:50%;background:var(--brand);border:3px solid var(--bg)}
.bar{margin-bottom:16px}.bar .top{display:flex;justify-content:space-between;font-weight:600;font-size:.92rem}
.track{height:9px;background:var(--soft);border-radius:99px;overflow:hidden;margin-top:6px}
.fill{height:100%;width:0;border-radius:99px;background:linear-gradient(90deg,var(--brand),var(--brand2));transition:width 1.1s ease}
.proj h3{margin-top:10px}.proj .ic{font-size:1.8rem}
.proj a{font-weight:600;text-decoration:none}
/* form */
label{display:block;font-weight:600;font-size:.88rem;margin-bottom:4px}
input,textarea{width:100%;padding:11px 12px;border:1px solid var(--line);border-radius:10px;background:var(--bg);color:var(--ink);font:inherit;margin-bottom:14px}
textarea{min-height:120px;resize:vertical}
input:focus,textarea:focus,.btn:focus-visible,a:focus-visible,button:focus-visible{outline:3px solid color-mix(in srgb,var(--brand) 45%,transparent)}
.links{display:flex;flex-wrap:wrap;gap:10px;margin-top:16px}
footer{padding:28px 0;border-top:1px solid var(--line);text-align:center;color:var(--muted);font-size:.9rem}
.reveal{opacity:0;transform:translateY(18px);transition:.6s}.reveal.in{opacity:1;transform:none}
@media(prefers-reduced-motion:reduce){.reveal{opacity:1;transform:none;transition:none}.fill{transition:none}html{scroll-behavior:auto}}
.toast{position:fixed;bottom:24px;left:50%;transform:translateX(-50%);background:var(--ink);color:var(--bg);padding:12px 20px;border-radius:10px;z-index:99}
</style>
</head>
<body>
<header><div class="container nav">
  <a class="logo" href="#home"><span>MK</span>Mahesh Kumar</a>
  <nav id="nav" aria-label="Main"><ul id="menu"></ul></nav>
  <div class="right"><button class="icon-btn" id="theme" aria-label="Toggle dark mode">🌙</button><button class="icon-btn burger" id="burger" aria-label="Menu">☰</button></div>
</div></header>

<main>
<section class="hero" id="home"><div class="container">
  <div class="tag-h" id="hello">Hello, I'm</div>
  <h1><span class="grad" id="name"></span></h1>
  <p class="lead" id="tagline"></p>
  <div class="btns"><a class="btn p" href="#projects">View my work</a><a class="btn g" href="#contact">Contact me</a></div>
  <div class="stats" id="stats"></div>
</div></section>

<section id="about"><div class="container grid g2 reveal">
  <div><div class="tag-h">About</div><h2>A little about me</h2><p id="aboutText" class="muted"></p><div id="values"></div></div>
  <div class="card"><h3>Quick facts</h3><ul class="facts" id="facts"></ul></div>
</div></section>

<section class="alt" id="education"><div class="container reveal">
  <div class="tag-h">Education</div><h2>Learning journey</h2>
  <div class="timeline" id="edu"></div>
</div></section>

<section id="skills"><div class="container grid g2 reveal">
  <div><div class="tag-h">Skills</div><h2>What I'm good at</h2><div id="bars"></div></div>
  <div><h3 style="margin-top:34px">Tools &amp; technologies</h3><div id="tools"></div></div>
</div></section>

<section class="alt" id="projects"><div class="container reveal">
  <div class="tag-h">Projects</div><h2>Things I've built</h2>
  <div class="grid g3" id="projList"></div>
</div></section>

<section id="certifications"><div class="container reveal">
  <div class="tag-h">Certifications</div><h2>Credentials</h2>
  <div class="grid g3" id="certs"></div>
</div></section>

<section class="alt" id="contact"><div class="container grid g2 reveal">
  <div><div class="tag-h">Contact</div><h2>Let's connect</h2>
    <p class="muted">Have a question, an opportunity or just want to say hi? Send me a message.</p>
    <div class="links" id="links"></div></div>
  <form class="card" id="form" novalidate>
    <label for="fn">Your name</label><input id="fn" autocomplete="name" required>
    <label for="fe">Your email</label><input id="fe" type="email" autocomplete="email" required>
    <label for="fm">Message</label><textarea id="fm" required></textarea>
    <button class="btn p" style="width:100%">Send message</button>
    <p class="muted" style="font-size:.8rem;margin:10px 0 0">This opens your email app with the message ready to send.</p>
  </form>
</div></section>
</main>
<footer><div class="container">© <span id="yr"></span> <span id="fname"></span>. Built with HTML, CSS and JavaScript.</div></footer>

<script>
/* =====================================================================
   EDIT THIS BLOCK: all text on the site comes from here.
   Items in [square brackets] are placeholders. Replace them with your real details.
   ===================================================================== */
const ME = {
  name: 'Mahesh Kumar',
  tagline: '[Your role, e.g. Software Developer · Student · Designer] — I build useful things and keep learning every day.',
  email: 'your.email@example.com',          // <-- change
  github: 'https://github.com/your-username', // <-- change
  linkedin: 'https://linkedin.com/in/your-name', // <-- change
  stats: [['3+', 'Years learning'], ['10+', 'Projects'], ['5', 'Certifications'], ['100%', 'Curiosity']],
  about: "I'm Mahesh Kumar, [a short introduction: what you study or do, what you enjoy, and what you want to achieve]. I like solving real problems, working with others and turning ideas into finished work.",
  values: ['🎯 Focused', '🤝 Team player', '🚀 Fast learner', '💡 Creative'],
  facts: [['Location', '[City, Country]'], ['Studying / Working', '[University or Company]'], ['Languages', '[English, Hindi, …]'], ['Interests', '[Technology, reading, sport]'], ['Status', '🟢 Open to opportunities']],
  education: [
    {when: '[2023 – Present]', title: '[Bachelor of …]', where: '[University name]', text: '[Main subjects, achievements or current focus.]'},
    {when: '[2021 – 2023]', title: '[Higher secondary / Diploma]', where: '[School / College name]', text: '[Stream, result or highlights.]'},
    {when: 'Ongoing', title: 'Self-directed learning', where: 'Online courses & practice', text: '[Topics you are teaching yourself.]'}
  ],
  skills: [['[Main skill 1]', 90], ['[Main skill 2]', 80], ['[Main skill 3]', 75], ['Communication', 85], ['Problem solving', 88]],
  tools: ['HTML', 'CSS', 'JavaScript', 'Git & GitHub', 'Python', 'MS Office', 'Figma', '[Add yours]'],
  projects: [
    {icon: '🌐', title: '[Project one]', text: 'Short description of what it does and what you learned.', tags: ['HTML', 'CSS', 'JS'], link: '#'},
    {icon: '📱', title: '[Project two]', text: 'Short description of what it does and what you learned.', tags: ['Python'], link: '#'},
    {icon: '📊', title: '[Project three]', text: 'Short description of what it does and what you learned.', tags: ['Data', 'Excel'], link: '#'}
  ],
  certs: [
    {title: '[Certificate name]', by: '[Issuer, e.g. Coursera / Google]', year: '[2025]', link: ''},
    {title: '[Certificate name]', by: '[Issuer]', year: '[2025]', link: ''},
    {title: 'More coming soon…', by: 'Always learning', year: '', link: ''}
  ]
};
/* =================== end of editable content =================== */

const $ = (s, r = document) => r.querySelector(s), $$ = (s, r = document) => [...r.querySelectorAll(s)];
const esc = s => String(s).replace(/[&<>"']/g, c => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
const safeUrl = u => /^(https?:\/\/|#|mailto:)/.test(u) ? u : '#';

document.title = ME.name + ' – Portfolio';
$('#name').textContent = ME.name; $('#tagline').textContent = ME.tagline; $('#fname').textContent = ME.name;
$('#yr').textContent = new Date().getFullYear(); $('#aboutText').textContent = ME.about;
$('#stats').innerHTML = ME.stats.map(s => `<div class="stat"><b>${esc(s[0])}</b><span class="muted">${esc(s[1])}</span></div>`).join('');
$('#values').innerHTML = ME.values.map(v => `<span class="pill">${esc(v)}</span>`).join('');
$('#facts').innerHTML = ME.facts.map(f => `<li><strong>${esc(f[0])}</strong><span class="muted">${esc(f[1])}</span></li>`).join('');
$('#edu').innerHTML = ME.education.map(e => `<div class="tl card"><span class="pill">${esc(e.when)}</span><h3>${esc(e.title)}</h3><strong class="muted">${esc(e.where)}</strong><p class="muted" style="margin:6px 0 0">${esc(e.text)}</p></div>`).join('');
$('#bars').innerHTML = ME.skills.map(s => `<div class="bar"><div class="top"><span>${esc(s[0])}</span><span>${s[1]}%</span></div><div class="track"><div class="fill" data-w="${s[1]}"></div></div></div>`).join('');
$('#tools').innerHTML = ME.tools.map(t => `<span class="pill">${esc(t)}</span>`).join('');
$('#projList').innerHTML = ME.projects.map(p => `<article class="card proj"><div class="ic">${p.icon}</div><h3>${esc(p.title)}</h3><p class="muted">${esc(p.text)}</p>${p.tags.map(t => `<span class="pill">${esc(t)}</span>`).join('')}<p><a href="${safeUrl(p.link)}" target="_blank" rel="noopener">View project →</a></p></article>`).join('');
$('#certs').innerHTML = ME.certs.map(c => `<div class="card"><div style="font-size:1.6rem">🏅</div><h3>${esc(c.title)}</h3><p class="muted" style="margin:0">${esc(c.by)} ${c.year ? '· ' + esc(c.year) : ''}</p>${c.link ? `<p><a href="${safeUrl(c.link)}" target="_blank" rel="noopener">Verify →</a></p>` : ''}</div>`).join('');
$('#links').innerHTML = [['✉️ Email', 'mailto:' + ME.email], ['💼 LinkedIn', ME.linkedin], ['🐙 GitHub', ME.github]].map(l => `<a class="btn g" href="${safeUrl(l[1])}" target="_blank" rel="noopener">${l[0]}</a>`).join('');

// Menu
const SECTIONS = [['home', 'Home'], ['about', 'About'], ['education', 'Education'], ['skills', 'Skills'], ['projects', 'Projects'], ['certifications', 'Certifications'], ['contact', 'Contact']];
$('#menu').innerHTML = SECTIONS.map(s => `<li><a href="#${s[0]}">${s[1]}</a></li>`).join('');
$('#burger').onclick = () => $('#nav').classList.toggle('open');
$$('#menu a').forEach(a => a.addEventListener('click', () => $('#nav').classList.remove('open')));

// Active link on scroll + reveal + skill bars
const links = $$('#menu a');
const spy = new IntersectionObserver(es => es.forEach(e => { if (e.isIntersecting) links.forEach(l => l.classList.toggle('active', l.getAttribute('href') === '#' + e.target.id)); }), {rootMargin: '-45% 0px -50% 0px'});
SECTIONS.forEach(s => spy.observe($('#' + s[0])));
const rv = new IntersectionObserver(es => es.forEach(e => { if (e.isIntersecting) { e.target.classList.add('in'); $$('.fill', e.target).forEach(f => f.style.width = f.dataset.w + '%'); rv.unobserve(e.target); } }), {threshold: .15});
$$('.reveal').forEach(el => rv.observe(el));

// Theme (saved if storage is available)
const root = document.documentElement;
function setTheme(t) { root.dataset.theme = t; $('#theme').textContent = t === 'dark' ? '☀️' : '🌙'; try { localStorage.setItem('theme', t); } catch {} }
let saved = null; try { saved = localStorage.getItem('theme'); } catch {}
setTheme(saved || (matchMedia('(prefers-color-scheme: dark)').matches ? 'dark' : 'light'));
$('#theme').onclick = () => setTheme(root.dataset.theme === 'dark' ? 'light' : 'dark');

// Contact form -> opens email app
$('#form').onsubmit = e => {
  e.preventDefault();
  const n = $('#fn').value.trim(), m = $('#fe').value.trim(), b = $('#fm').value.trim();
  if (!n || !/^\S+@\S+\.\S+$/.test(m) || !b) { const t = document.createElement('div'); t.className = 'toast'; t.textContent = 'Please fill in all fields with a valid email.'; document.body.appendChild(t); setTimeout(() => t.remove(), 3000); return; }
  location.href = `mailto:${ME.email}?subject=${encodeURIComponent('Portfolio message from ' + n)}&body=${encodeURIComponent(b + '\n\n— ' + n + ' (' + m + ')')}`;
};
</script>
</body>
</html>
