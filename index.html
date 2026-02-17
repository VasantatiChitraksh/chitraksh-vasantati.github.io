<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chitraksh Vasantati — Developer & Builder</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Space+Mono:ital,wght@0,400;0,700;1,400&family=Exo+2:wght@100;300;400;600&display=swap" rel="stylesheet">
<style>
  :root {
    --cyan: #00f5ff;
    --magenta: #ff00a0;
    --gold: #ffd700;
    --bg: #030610;
    --bg2: #060d1e;
    --surface: rgba(0,245,255,0.04);
    --border: rgba(0,245,255,0.15);
    --text: #cce8f0;
    --text-dim: #4a7080;
    --glow-cyan: 0 0 20px rgba(0,245,255,0.5), 0 0 40px rgba(0,245,255,0.2);
    --glow-mag: 0 0 20px rgba(255,0,160,0.5), 0 0 40px rgba(255,0,160,0.2);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Exo 2', sans-serif;
    font-weight: 300;
    overflow-x: hidden;
    cursor: none;
  }

  /* ── CUSTOM CURSOR ── */
  #cursor {
    position: fixed; width: 12px; height: 12px;
    background: var(--cyan); border-radius: 50%;
    pointer-events: none; z-index: 9999;
    transform: translate(-50%, -50%);
    transition: width .15s, height .15s, background .15s;
    box-shadow: var(--glow-cyan);
    mix-blend-mode: screen;
  }
  #cursor-ring {
    position: fixed; width: 36px; height: 36px;
    border: 1px solid rgba(0,245,255,0.5);
    border-radius: 50%; pointer-events: none; z-index: 9998;
    transform: translate(-50%, -50%);
    transition: transform .08s ease-out, width .15s, height .15s;
  }

  /* ── CANVAS PARTICLES ── */
  #particles { position: fixed; top:0; left:0; width:100%; height:100%; z-index:0; pointer-events:none; }

  /* ── NOISE OVERLAY ── */
  body::before {
    content:''; position:fixed; inset:0; z-index:1; pointer-events:none;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
    background-size: 150px;
    opacity: 0.35;
  }

  /* ── SCANLINES ── */
  body::after {
    content:''; position:fixed; inset:0; z-index:2; pointer-events:none;
    background: repeating-linear-gradient(0deg, transparent, transparent 2px, rgba(0,0,0,0.08) 2px, rgba(0,0,0,0.08) 4px);
  }

  /* ── LAYOUT ── */
  .wrap { position:relative; z-index:10; max-width: 1100px; margin: 0 auto; padding: 0 2rem; }

  /* ── NAV ── */
  nav {
    position: fixed; top:0; left:0; right:0; z-index: 100;
    display: flex; align-items: center; justify-content: space-between;
    padding: 1.2rem 3rem;
    background: rgba(3,6,16,0.85);
    backdrop-filter: blur(16px);
    border-bottom: 1px solid var(--border);
  }
  .nav-logo {
    font-family: 'Orbitron', monospace;
    font-size: .85rem; font-weight: 700;
    color: var(--cyan); letter-spacing: .15em;
    text-shadow: var(--glow-cyan);
  }
  .nav-links { display:flex; gap:2rem; list-style:none; }
  .nav-links a {
    font-family: 'Space Mono', monospace;
    font-size: .7rem; letter-spacing: .15em; text-transform:uppercase;
    color: var(--text-dim); text-decoration:none;
    transition: color .2s;
    position: relative;
  }
  .nav-links a::after {
    content:''; position:absolute; bottom:-4px; left:0; right:0;
    height:1px; background: var(--cyan); transform:scaleX(0);
    transition: transform .25s;
  }
  .nav-links a:hover { color: var(--cyan); }
  .nav-links a:hover::after { transform:scaleX(1); }

  /* ── HERO ── */
  #hero {
    min-height: 100vh; display:flex; align-items:center;
    padding: 8rem 3rem 4rem;
    position:relative;
  }
  .hero-inner { max-width: 1100px; margin:0 auto; width:100%; }

  .hero-tag {
    font-family: 'Space Mono', monospace; font-size:.7rem;
    color: var(--magenta); letter-spacing:.2em; text-transform:uppercase;
    margin-bottom:1.2rem; opacity:0;
    animation: fadeUp .6s .3s forwards;
  }

  h1.hero-name {
    font-family: 'Orbitron', monospace;
    font-size: clamp(2.8rem, 6vw, 5.5rem);
    font-weight: 900;
    line-height: 1;
    letter-spacing:-.02em;
    background: linear-gradient(135deg, #fff 0%, var(--cyan) 50%, var(--magenta) 100%);
    -webkit-background-clip: text; -webkit-text-fill-color: transparent;
    filter: drop-shadow(0 0 30px rgba(0,245,255,0.3));
    opacity:0; animation: fadeUp .7s .5s forwards;
  }

  .hero-title-line {
    font-family: 'Orbitron', monospace;
    font-size: clamp(1rem, 2vw, 1.4rem);
    color: var(--gold); font-weight:400; letter-spacing:.08em;
    margin-top:.8rem;
    opacity:0; animation: fadeUp .6s .7s forwards;
  }

  .hero-desc {
    max-width: 560px; margin-top:1.8rem;
    font-size:1.05rem; line-height:1.8; color:#8aaaba; font-weight:300;
    opacity:0; animation: fadeUp .6s .9s forwards;
  }
  .hero-desc strong { color:var(--cyan); font-weight:600; }

  .hero-cta {
    display:flex; gap:1rem; margin-top:2.5rem; flex-wrap:wrap;
    opacity:0; animation: fadeUp .6s 1.1s forwards;
  }
  .btn {
    font-family:'Space Mono', monospace; font-size:.72rem;
    letter-spacing:.15em; text-transform:uppercase; text-decoration:none;
    padding:.85rem 2rem; border-radius:2px;
    transition: all .25s; position:relative; overflow:hidden;
    display:inline-flex; align-items:center; gap:.6rem;
  }
  .btn-primary {
    background: var(--cyan); color: var(--bg); border:none;
    font-weight:700;
  }
  .btn-primary:hover {
    background: #fff; box-shadow: var(--glow-cyan);
    transform: translateY(-2px);
  }
  .btn-outline {
    background:transparent; color:var(--cyan);
    border: 1px solid var(--cyan);
  }
  .btn-outline:hover {
    background: rgba(0,245,255,.08); box-shadow: var(--glow-cyan);
    transform: translateY(-2px);
  }
  .btn-mag {
    background:transparent; color:var(--magenta);
    border: 1px solid var(--magenta);
  }
  .btn-mag:hover {
    background: rgba(255,0,160,.08); box-shadow: var(--glow-mag);
    transform: translateY(-2px);
  }

  /* ── GLITCH ── */
  .glitch { position:relative; }
  .glitch::before, .glitch::after {
    content: attr(data-text);
    position:absolute; top:0; left:0;
    background: linear-gradient(135deg, #fff 0%, var(--cyan) 50%, var(--magenta) 100%);
    -webkit-background-clip: text; -webkit-text-fill-color: transparent;
    width:100%;
  }
  .glitch::before {
    left:2px; text-shadow: -1px 0 var(--magenta);
    clip: rect(44px,550px,56px,0);
    animation: glitch-anim 3s infinite linear alternate-reverse;
  }
  .glitch::after {
    left:-2px; text-shadow: -1px 0 var(--cyan);
    clip: rect(44px,550px,56px,0);
    animation: glitch-anim2 2.5s .5s infinite linear alternate-reverse;
  }
  @keyframes glitch-anim {
    0%   { clip:rect(10px,9999px,25px,0); transform:skew(.4deg); }
    20%  { clip:rect(80px,9999px,90px,0); transform:skew(.1deg); }
    40%  { clip:rect(40px,9999px,55px,0); transform:skew(-.3deg); }
    60%  { clip:rect(5px,9999px,18px,0); transform:skew(.5deg); }
    80%  { clip:rect(60px,9999px,72px,0); transform:skew(-.2deg); }
    100% { clip:rect(30px,9999px,42px,0); transform:skew(.3deg); }
  }
  @keyframes glitch-anim2 {
    0%   { clip:rect(55px,9999px,68px,0); transform:skew(-.4deg); }
    25%  { clip:rect(15px,9999px,28px,0); transform:skew(.2deg); }
    50%  { clip:rect(70px,9999px,84px,0); transform:skew(-.5deg); }
    75%  { clip:rect(35px,9999px,48px,0); transform:skew(.3deg); }
    100% { clip:rect(92px,9999px,104px,0); transform:skew(-.1deg); }
  }

  /* ── HERO GRID LINES ── */
  .hero-grid {
    position:absolute; inset:0; pointer-events:none;
    background:
      linear-gradient(rgba(0,245,255,0.03) 1px, transparent 1px),
      linear-gradient(90deg, rgba(0,245,255,0.03) 1px, transparent 1px);
    background-size: 60px 60px;
    mask-image: radial-gradient(ellipse 70% 80% at 80% 50%, black, transparent);
  }

  /* ── SECTION ── */
  section { padding: 6rem 3rem; }

  .section-label {
    font-family: 'Space Mono', monospace;
    font-size:.65rem; letter-spacing:.25em; text-transform:uppercase;
    color: var(--magenta); margin-bottom:.8rem;
    display:flex; align-items:center; gap:.8rem;
  }
  .section-label::before {
    content:''; display:block; width:30px; height:1px; background:var(--magenta);
  }

  .section-title {
    font-family:'Orbitron', monospace;
    font-size:clamp(1.8rem,3.5vw,2.8rem); font-weight:700;
    color:#fff; margin-bottom:3rem; line-height:1.1;
  }
  .section-title span { color:var(--cyan); }

  /* ── APPS ── */
  #apps { background: var(--bg2); }
  .apps-grid { display:grid; grid-template-columns: repeat(auto-fit, minmax(300px,1fr)); gap:1.5rem; }

  .app-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 4px;
    padding: 2rem;
    position:relative; overflow:hidden;
    transition: border-color .3s, transform .3s;
    text-decoration:none; color:inherit;
    display:block;
  }
  .app-card::before {
    content:''; position:absolute; inset:0;
    background: linear-gradient(135deg, rgba(0,245,255,.05), transparent 60%);
    opacity:0; transition:opacity .3s;
  }
  .app-card:hover { border-color:var(--cyan); transform:translateY(-4px); }
  .app-card:hover::before { opacity:1; }
  .app-card:hover .app-icon { box-shadow: var(--glow-cyan); }

  .app-num {
    font-family:'Space Mono', monospace; font-size:.6rem;
    color:var(--text-dim); letter-spacing:.15em; margin-bottom:1.2rem;
  }
  .app-icon {
    width:56px; height:56px; border-radius:12px;
    background: linear-gradient(135deg, var(--cyan), var(--magenta));
    display:flex; align-items:center; justify-content:center;
    font-size:1.5rem; margin-bottom:1.2rem;
    transition: box-shadow .3s;
  }
  .app-name {
    font-family:'Orbitron', monospace; font-size:.9rem;
    font-weight:700; color:#fff; margin-bottom:.5rem;
  }
  .app-desc { font-size:.85rem; color:#7090a0; line-height:1.6; margin-bottom:1.2rem; }
  .app-badge {
    display:inline-flex; align-items:center; gap:.4rem;
    font-family:'Space Mono', monospace; font-size:.6rem;
    color:var(--cyan); border:1px solid rgba(0,245,255,.3);
    padding:.3rem .7rem; border-radius:2px; letter-spacing:.1em;
  }
  .app-corner {
    position:absolute; top:1rem; right:1rem;
    font-size:1.2rem; opacity:.3;
  }

  /* ── ABOUT / INTERESTS ── */
  .about-grid { display:grid; grid-template-columns: 1fr 1fr; gap:3rem; }
  @media(max-width:768px){ .about-grid{grid-template-columns:1fr;} }

  .interest-card {
    background:var(--surface); border:1px solid var(--border);
    border-radius:4px; padding:1.5rem;
    transition: border-color .3s, transform .3s;
    position:relative; overflow:hidden;
  }
  .interest-card:hover { border-color:var(--cyan); transform:translateY(-3px); }
  .interest-card::after {
    content:''; position:absolute; bottom:0; left:0; right:0;
    height:2px;
    background: linear-gradient(90deg, var(--cyan), var(--magenta));
    transform:scaleX(0); transform-origin:left;
    transition: transform .4s;
  }
  .interest-card:hover::after { transform:scaleX(1); }

  .interest-icon { font-size:1.8rem; margin-bottom:.8rem; }
  .interest-title {
    font-family:'Orbitron', monospace; font-size:.85rem;
    font-weight:700; color:var(--cyan); margin-bottom:.5rem;
    letter-spacing:.05em;
  }
  .interest-text { font-size:.85rem; color:#7090a0; line-height:1.7; }

  /* ── TECH STACK ── */
  #stack { background: var(--bg2); }
  .stack-categories { display:grid; grid-template-columns: repeat(auto-fit, minmax(220px,1fr)); gap:1.5rem; }

  .stack-cat {
    background:var(--surface); border:1px solid var(--border);
    border-radius:4px; padding:1.5rem;
    position:relative; overflow:hidden;
  }
  .stack-cat-title {
    font-family:'Space Mono', monospace; font-size:.65rem;
    letter-spacing:.15em; text-transform:uppercase;
    color:var(--magenta); margin-bottom:1rem;
    display:flex; align-items:center; gap:.5rem;
  }
  .stack-tags { display:flex; flex-wrap:wrap; gap:.5rem; }
  .tag {
    font-family:'Space Mono', monospace; font-size:.62rem;
    padding:.3rem .75rem; border-radius:2px;
    border:1px solid; letter-spacing:.05em;
    transition: all .2s; cursor:default;
  }
  .tag-cyan { color:var(--cyan); border-color:rgba(0,245,255,.25); background:rgba(0,245,255,.04); }
  .tag-cyan:hover { background:rgba(0,245,255,.12); box-shadow:var(--glow-cyan); }
  .tag-mag { color:var(--magenta); border-color:rgba(255,0,160,.25); background:rgba(255,0,160,.04); }
  .tag-mag:hover { background:rgba(255,0,160,.12); box-shadow:var(--glow-mag); }
  .tag-gold { color:var(--gold); border-color:rgba(255,215,0,.25); background:rgba(255,215,0,.04); }
  .tag-gold:hover { background:rgba(255,215,0,.12); box-shadow:0 0 15px rgba(255,215,0,.3); }

  /* ── STATS ── */
  .stats-row { display:grid; grid-template-columns: repeat(auto-fit,minmax(180px,1fr)); gap:1.5rem; margin-bottom:3rem; }

  .stat-box {
    background:var(--surface); border:1px solid var(--border);
    border-radius:4px; padding:1.5rem; text-align:center;
    position:relative; overflow:hidden;
  }
  .stat-box::before {
    content:''; position:absolute; top:0; left:0; right:0; height:2px;
    background: linear-gradient(90deg, var(--cyan), var(--magenta));
  }
  .stat-num {
    font-family:'Orbitron', monospace; font-size:2rem; font-weight:900;
    color:var(--cyan); display:block; line-height:1;
    text-shadow: var(--glow-cyan);
  }
  .stat-label {
    font-family:'Space Mono', monospace; font-size:.6rem;
    color:var(--text-dim); letter-spacing:.12em; text-transform:uppercase;
    margin-top:.5rem; display:block;
  }

  /* ── CONNECT ── */
  .connect-grid { display:grid; grid-template-columns: repeat(auto-fit,minmax(160px,1fr)); gap:1rem; }

  .social-link {
    background:var(--surface); border:1px solid var(--border);
    border-radius:4px; padding:1.2rem 1rem;
    display:flex; flex-direction:column; align-items:center; gap:.6rem;
    text-decoration:none; transition: all .25s;
    position:relative; overflow:hidden;
  }
  .social-link:hover { border-color:var(--cyan); transform:translateY(-3px); box-shadow:var(--glow-cyan); }
  .social-icon { font-size:1.4rem; }
  .social-name {
    font-family:'Space Mono', monospace; font-size:.62rem;
    letter-spacing:.1em; color:var(--text-dim); text-transform:uppercase;
    transition: color .25s;
  }
  .social-link:hover .social-name { color:var(--cyan); }

  /* ── FOOTER ── */
  footer {
    border-top:1px solid var(--border);
    padding:2rem 3rem;
    display:flex; align-items:center; justify-content:space-between;
    flex-wrap:wrap; gap:1rem;
  }
  .footer-brand {
    font-family:'Orbitron', monospace; font-size:.7rem;
    color:var(--cyan); letter-spacing:.1em;
  }
  .footer-note {
    font-family:'Space Mono', monospace; font-size:.6rem;
    color:var(--text-dim); letter-spacing:.08em;
  }

  /* ── ANIMATIONS ── */
  @keyframes fadeUp {
    from { opacity:0; transform:translateY(24px); }
    to   { opacity:1; transform:translateY(0); }
  }

  .fade-in {
    opacity:0; transform:translateY(30px);
    transition: opacity .7s ease, transform .7s ease;
  }
  .fade-in.visible { opacity:1; transform:none; }

  /* ── TERMINAL TYPING ── */
  .terminal {
    background:#0a1220; border:1px solid rgba(0,245,255,.2);
    border-radius:4px; padding:1.5rem; margin-top:2rem;
    font-family:'Space Mono', monospace; font-size:.8rem;
    line-height:1.8; max-width:480px;
    position:relative;
    opacity:0; animation: fadeUp .6s 1.4s forwards;
  }
  .terminal::before {
    content:'● ● ●'; position:absolute; top:.7rem; left:1rem;
    font-size:.5rem; color:#4a5568; letter-spacing:.5rem;
  }
  .terminal .line { padding-top:.8rem; }
  .terminal .prompt { color:var(--cyan); }
  .terminal .comment { color:#4a6070; }
  .terminal .value { color:var(--gold); }
  .terminal .key { color:#c0e0f0; }
  .cursor-blink {
    display:inline-block; width:8px; height:14px;
    background:var(--cyan); vertical-align:middle;
    animation: blink 1s infinite;
  }
  @keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }

  /* ── ORBIT DECORATION ── */
  .orbit-deco {
    position:absolute; right:-80px; top:50%;
    transform:translateY(-50%);
    width:500px; height:500px; pointer-events:none;
    opacity:.12;
  }
  .orbit-deco circle { fill:none; stroke:var(--cyan); stroke-width:1; }
  .orbit-ring { animation: spin 20s linear infinite; transform-origin:250px 250px; }
  .orbit-ring2 { animation: spin 14s linear infinite reverse; transform-origin:250px 250px; }
  .orbit-ring3 { animation: spin 30s linear infinite; transform-origin:250px 250px; }
  @keyframes spin { to{transform:rotate(360deg)} }

  /* ── SECTION DIVIDER ── */
  .divider {
    width:100%; height:1px;
    background:linear-gradient(90deg, transparent, var(--cyan), var(--magenta), transparent);
    margin:0;
  }

  /* ── MOBILE ── */
  @media(max-width:600px) {
    nav { padding:.8rem 1.2rem; }
    .nav-links { gap:1rem; }
    section { padding:4rem 1.2rem; }
    #hero { padding:7rem 1.2rem 3rem; }
    footer { padding:1.5rem 1.2rem; flex-direction:column; }
    .orbit-deco { display:none; }
  }

  /* ── SCROLL PROGRESS ── */
  #progress {
    position:fixed; top:0; left:0; height:2px; z-index:200;
    background:linear-gradient(90deg, var(--cyan), var(--magenta));
    transition:width .1s;
  }
</style>
</head>
<body>
<div id="progress"></div>
<canvas id="particles"></canvas>
<div id="cursor"></div>
<div id="cursor-ring"></div>

<nav>
  <div class="nav-logo">CV_23076</div>
  <ul class="nav-links">
    <li><a href="#apps">Apps</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#stack">Stack</a></li>
    <li><a href="#connect">Connect</a></li>
  </ul>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-grid"></div>
  <div class="hero-inner">
    <p class="hero-tag">// CS Undergraduate · Full-Stack · ML · DevOps</p>
    <h1 class="hero-name glitch" data-text="CHITRAKSH VASANTATI">CHITRAKSH VASANTATI</h1>
    <p class="hero-title-line">BUILDER. EXPLORER. ENGINEER.</p>
    <p class="hero-desc">
      3rd-year CS undergrad crafting <strong>purpose-driven applications</strong> that solve real problems. 
      From deploying mobile apps on the Play Store to engineering cloud-native backends — I build things that <strong>actually ship</strong>.
    </p>
    <div class="hero-cta">
      <a href="mailto:chitravasantati@gmail.com" class="btn btn-primary">⚡ Hire Me</a>
      <a href="https://github.com/VasantatiChitraksh?tab=repositories" target="_blank" class="btn btn-outline">↗ GitHub</a>
      <a href="https://www.linkedin.com/in/chitraksh-vasantati/" target="_blank" class="btn btn-mag">↗ LinkedIn</a>
    </div>

    <div class="terminal">
      <div class="line" style="padding-top:1.4rem">
        <span class="prompt">$ </span><span class="key">whoami</span>
      </div>
      <div class="line"><span class="comment"># Chitraksh Vasantati | chitravasantati@gmail.com</span></div>
      <div class="line">
        <span class="prompt">$ </span><span class="key">status</span>
      </div>
      <div class="line"><span class="value">"Open to internships, freelance & collabs"</span></div>
      <div class="line">
        <span class="prompt">$ </span><span class="key">passion</span>
      </div>
      <div class="line"><span class="value">"Building things that matter"</span> <span class="cursor-blink"></span></div>
    </div>

    <!-- SVG orbit deco -->
    <svg class="orbit-deco" viewBox="0 0 500 500">
      <circle cx="250" cy="250" r="200"/>
      <g class="orbit-ring">
        <circle cx="250" cy="250" r="160" stroke-dasharray="8 12"/>
        <circle cx="410" cy="250" r="6" fill="rgba(0,245,255,0.6)" stroke="none"/>
      </g>
      <g class="orbit-ring2">
        <circle cx="250" cy="250" r="115" stroke-dasharray="4 8"/>
        <circle cx="365" cy="250" r="4" fill="rgba(255,0,160,0.6)" stroke="none"/>
      </g>
      <g class="orbit-ring3">
        <circle cx="250" cy="250" r="230" stroke-dasharray="2 6"/>
        <circle cx="480" cy="250" r="5" fill="rgba(255,215,0,0.5)" stroke="none"/>
      </g>
    </svg>
  </div>
</section>

<div class="divider"></div>

<!-- APPS -->
<section id="apps">
  <div class="wrap">
    <p class="section-label fade-in">Live on Play Store</p>
    <h2 class="section-title fade-in">Shipped <span>Apps</span></h2>

    <div class="stats-row fade-in">
      <div class="stat-box">
        <span class="stat-num">500+</span>
        <span class="stat-label">Downloads</span>
      </div>
      <div class="stat-box">
        <span class="stat-num">2</span>
        <span class="stat-label">Live Apps</span>
      </div>
      <div class="stat-box">
        <span class="stat-num">Play</span>
        <span class="stat-label">Store Deployed</span>
      </div>
      <div class="stat-box">
        <span class="stat-num">Flutter</span>
        <span class="stat-label">Native Mobile</span>
      </div>
    </div>

    <div class="apps-grid">
      <a href="https://play.google.com/store/apps/details?id=org.iitt.iccms2025" target="_blank" class="app-card fade-in">
        <div class="app-num">APP_01 / 2025</div>
        <div class="app-icon">📡</div>
        <div class="app-name">ICCMS 2025</div>
        <div class="app-desc">
          Conference Companion App for ICCMS 2025 — an international conference on Communication, Management and Security. Built with Flutter & Firebase, it delivers schedules, speaker profiles, venue maps, and real-time updates to 500+ attendees.
        </div>
        <span class="app-badge">▶ 500+ Downloads on Play Store</span>
        <div class="app-corner">↗</div>
      </a>

      <a href="https://play.google.com/store/apps/details?id=com.iittp.iism25&hl=en_IN" target="_blank" class="app-card fade-in">
        <div class="app-num">APP_02 / 2025</div>
        <div class="app-icon">🔬</div>
        <div class="app-name">IISM 2025</div>
        <div class="app-desc">
          Official companion app for IISM 2025 — a flagship symposium hosted at IIT Tirupati. Features event listings, abstract browsing, networking tools, and live announcements for delegates, speakers, and organizers.
        </div>
        <span class="app-badge">▶ Live on Play Store</span>
        <div class="app-corner">↗</div>
      </a>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- ABOUT / INTERESTS -->
<section id="about">
  <div class="wrap">
    <p class="section-label fade-in">What Drives Me</p>
    <h2 class="section-title fade-in">Interests & <span>Curiosities</span></h2>

    <div class="about-grid">
      <div>
        <div class="interest-card fade-in" style="margin-bottom:1.2rem">
          <div class="interest-icon">🤖</div>
          <div class="interest-title">Large Language Models & RAG</div>
          <div class="interest-text">Fascinated by how LLMs can be grounded with real-world knowledge through Retrieval-Augmented Generation. I explore how to build systems that are accurate, context-aware, and production-ready — going beyond demo-ware.</div>
        </div>
        <div class="interest-card fade-in" style="margin-bottom:1.2rem">
          <div class="interest-icon">👁️</div>
          <div class="interest-title">Computer Vision</div>
          <div class="interest-text">Exploring object detection, image segmentation, and visual understanding pipelines using PyTorch. I'm particularly drawn to real-world applications in healthcare, surveillance, and accessibility tooling.</div>
        </div>
        <div class="interest-card fade-in">
          <div class="interest-icon">🎙️</div>
          <div class="interest-title">Speech & Audio Transformers</div>
          <div class="interest-text">Deep-diving into transformer architectures for speech recognition, synthesis, and audio classification. The intersection of language and acoustics is one of the most exciting frontiers in AI right now.</div>
        </div>
      </div>
      <div>
        <div class="interest-card fade-in" style="margin-bottom:1.2rem">
          <div class="interest-icon">📱</div>
          <div class="interest-title">Mobile-First Product Development</div>
          <div class="interest-text">I believe the best software reaches users where they are — on their phones. Flutter lets me build beautiful, native-feeling apps from a single codebase. Two Play Store apps and counting.</div>
        </div>
        <div class="interest-card fade-in" style="margin-bottom:1.2rem">
          <div class="interest-icon">☁️</div>
          <div class="interest-title">Cloud-Native & DevOps</div>
          <div class="interest-text">Infrastructure is code. I enjoy containerizing applications with Docker, orchestrating them with Kubernetes, and building CI/CD pipelines that make deployment as boring as possible — which is exactly the goal.</div>
        </div>
        <div class="interest-card fade-in">
          <div class="interest-icon">🌐</div>
          <div class="interest-title">Full-Stack Web Engineering</div>
          <div class="interest-text">React frontends backed by Node/Express or FastAPI services, connected to MongoDB or PostgreSQL. I care about the full loop — from a clean UI to a well-designed API to a performant database query.</div>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="divider"></div>

<!-- STACK -->
<section id="stack">
  <div class="wrap">
    <p class="section-label fade-in">Tools of the Trade</p>
    <h2 class="section-title fade-in">Tech <span>Stack</span></h2>

    <div class="stack-categories fade-in">

      <div class="stack-cat">
        <div class="stack-cat-title">🔤 Languages</div>
        <div class="stack-tags">
          <span class="tag tag-cyan">Python</span>
          <span class="tag tag-cyan">JavaScript</span>
          <span class="tag tag-cyan">Java</span>
          <span class="tag tag-cyan">C++</span>
          <span class="tag tag-cyan">C</span>
        </div>
      </div>

      <div class="stack-cat">
        <div class="stack-cat-title">📱 Mobile</div>
        <div class="stack-tags">
          <span class="tag tag-mag">Flutter</span>
          <span class="tag tag-mag">Dart</span>
          <span class="tag tag-mag">Firebase</span>
        </div>
      </div>

      <div class="stack-cat">
        <div class="stack-cat-title">🌐 Web</div>
        <div class="stack-tags">
          <span class="tag tag-cyan">React</span>
          <span class="tag tag-cyan">Node.js</span>
          <span class="tag tag-cyan">Express.js</span>
          <span class="tag tag-cyan">MongoDB</span>
          <span class="tag tag-cyan">FastAPI</span>
        </div>
      </div>

      <div class="stack-cat">
        <div class="stack-cat-title">☁️ DevOps</div>
        <div class="stack-tags">
          <span class="tag tag-gold">Docker</span>
          <span class="tag tag-gold">Kubernetes</span>
          <span class="tag tag-gold">Git</span>
          <span class="tag tag-gold">SQL</span>
          <span class="tag tag-gold">PostgreSQL</span>
        </div>
      </div>

      <div class="stack-cat">
        <div class="stack-cat-title">🧠 ML / AI</div>
        <div class="stack-tags">
          <span class="tag tag-mag">TensorFlow</span>
          <span class="tag tag-mag">PyTorch</span>
          <span class="tag tag-mag">LLMs</span>
          <span class="tag tag-mag">RAG</span>
          <span class="tag tag-mag">Computer Vision</span>
          <span class="tag tag-mag">Speech AI</span>
          <span class="tag tag-mag">Transformers</span>
        </div>
      </div>

      <div class="stack-cat">
        <div class="stack-cat-title">🎯 Currently Learning</div>
        <div class="stack-tags">
          <span class="tag tag-gold">LangChain</span>
          <span class="tag tag-gold">Vector DBs</span>
          <span class="tag tag-gold">Whisper</span>
          <span class="tag tag-gold">YOLO</span>
        </div>
      </div>

    </div>
  </div>
</section>

<div class="divider"></div>

<!-- CONNECT -->
<section id="connect">
  <div class="wrap">
    <p class="section-label fade-in">Reach Out</p>
    <h2 class="section-title fade-in">Let's <span>Build Together</span></h2>

    <div class="connect-grid fade-in">
      <a href="https://www.linkedin.com/in/chitraksh-vasantati/" target="_blank" class="social-link">
        <div class="social-icon">💼</div>
        <div class="social-name">LinkedIn</div>
      </a>
      <a href="https://github.com/VasantatiChitraksh?tab=repositories" target="_blank" class="social-link">
        <div class="social-icon">🐙</div>
        <div class="social-name">GitHub</div>
      </a>
      <a href="https://www.youtube.com/@Chitraksh_vasantati_2307" target="_blank" class="social-link">
        <div class="social-icon">📺</div>
        <div class="social-name">YouTube</div>
      </a>
      <a href="https://www.instagram.com/cv_23076/" target="_blank" class="social-link">
        <div class="social-icon">📸</div>
        <div class="social-name">Instagram</div>
      </a>
      <a href="mailto:chitravasantati@gmail.com" class="social-link">
        <div class="social-icon">📬</div>
        <div class="social-name">Email</div>
      </a>
    </div>
  </div>
</section>

<div class="divider"></div>

<footer>
  <div class="footer-brand">CHITRAKSH VASANTATI</div>
  <div class="footer-note">Open to freelance · internships · collaborations</div>
  <div class="footer-note">chitravasantati@gmail.com</div>
</footer>

<script>
// ── CURSOR ──
const cur = document.getElementById('cursor');
const ring = document.getElementById('cursor-ring');
let mx=0, my=0, rx=0, ry=0;

document.addEventListener('mousemove', e => {
  mx = e.clientX; my = e.clientY;
  cur.style.left = mx+'px'; cur.style.top = my+'px';
});

const animRing = () => {
  rx += (mx-rx)*0.12; ry += (my-ry)*0.12;
  ring.style.left = rx+'px'; ring.style.top = ry+'px';
  requestAnimationFrame(animRing);
};
animRing();

document.querySelectorAll('a,button').forEach(el => {
  el.addEventListener('mouseenter',()=>{ cur.style.width='20px'; cur.style.height='20px'; cur.style.background='var(--magenta)'; });
  el.addEventListener('mouseleave',()=>{ cur.style.width='12px'; cur.style.height='12px'; cur.style.background='var(--cyan)'; });
});

// ── PARTICLES ──
const canvas = document.getElementById('particles');
const ctx = canvas.getContext('2d');
let W, H, dots=[];

const resize = () => { W=canvas.width=innerWidth; H=canvas.height=innerHeight; };
resize(); addEventListener('resize', resize);

class Dot {
  constructor() { this.reset(); }
  reset() {
    this.x = Math.random()*W;
    this.y = Math.random()*H;
    this.vx = (Math.random()-.5)*.3;
    this.vy = (Math.random()-.5)*.3;
    this.r = Math.random()*1.5+.5;
    this.life = Math.random()*200+100;
    this.age = 0;
    this.col = Math.random()>.5 ? '0,245,255' : '255,0,160';
  }
  update() {
    this.x += this.vx; this.y += this.vy; this.age++;
    if(this.age>this.life || this.x<0 || this.x>W || this.y<0 || this.y>H) this.reset();
  }
  draw() {
    const a = Math.sin(Math.PI*this.age/this.life)*.6;
    ctx.beginPath();
    ctx.arc(this.x,this.y,this.r,0,Math.PI*2);
    ctx.fillStyle = `rgba(${this.col},${a})`;
    ctx.fill();
  }
}

for(let i=0;i<120;i++) dots.push(new Dot());

// connection lines
const drawLines = () => {
  for(let i=0;i<dots.length;i++){
    for(let j=i+1;j<dots.length;j++){
      const dx=dots[i].x-dots[j].x, dy=dots[i].y-dots[j].y;
      const d=Math.sqrt(dx*dx+dy*dy);
      if(d<100){
        const a=(1-d/100)*.1;
        ctx.beginPath();
        ctx.moveTo(dots[i].x,dots[i].y);
        ctx.lineTo(dots[j].x,dots[j].y);
        ctx.strokeStyle=`rgba(0,245,255,${a})`;
        ctx.lineWidth=.5; ctx.stroke();
      }
    }
  }
};

const loop = () => {
  ctx.clearRect(0,0,W,H);
  dots.forEach(d=>{ d.update(); d.draw(); });
  drawLines();
  requestAnimationFrame(loop);
};
loop();

// ── SCROLL PROGRESS ──
const prog = document.getElementById('progress');
window.addEventListener('scroll', () => {
  const p = scrollY/(document.body.scrollHeight-innerHeight)*100;
  prog.style.width = p+'%';
});

// ── FADE IN ON SCROLL ──
const obs = new IntersectionObserver(entries => {
  entries.forEach(e => { if(e.isIntersecting) e.target.classList.add('visible'); });
}, { threshold:.1 });

document.querySelectorAll('.fade-in').forEach(el => obs.observe(el));
</script>
</body>
</html>
