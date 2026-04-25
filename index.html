<!DOCTYPE html>

<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MODO · CX Demo — Emotional Briefing</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:ital,wght@0,300;0,400;0,500;0,700;1,400&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet">
<style>
  :root {
    --navy:      #001F5B;
    --blue:      #003DA5;
    --lightblue: #5B8DEF;
    --dark:      #000D2B;
    --dark2:     #001540;
    --dark3:     #002266;
    --card:      #012A7A;
    --accent:    #00C9A7;
    --accent2:   #7FDFD0;
    --teal:      #00C9A7;
    --teal2:     #7FDFD0;
    --white:     #FFFFFF;
    --offwhite:  #EEF4FF;
    --gray:      #7B9BC8;
    --red:       #EF5350;
  }

- { margin: 0; padding: 0; box-sizing: border-box; }

body {
font-family: ‘DM Sans’, sans-serif;
background: var(–dark);
color: var(–white);
min-height: 100vh;
overflow-x: hidden;
}

/* ── NOISE OVERLAY ── */
body::before {
content: ‘’;
position: fixed; inset: 0;
background-image: url(“data:image/svg+xml,%3Csvg viewBox=‘0 0 256 256’ xmlns=‘http://www.w3.org/2000/svg’%3E%3Cfilter id=‘noise’%3E%3CfeTurbulence type=‘fractalNoise’ baseFrequency=‘0.9’ numOctaves=‘4’ stitchTiles=‘stitch’/%3E%3C/filter%3E%3Crect width=‘100%25’ height=‘100%25’ filter=‘url(%23noise)’ opacity=‘0.04’/%3E%3C/svg%3E”);
pointer-events: none; z-index: 0; opacity: 0.4;
}

/* ── AMBIENT ORBS ── */
.orb {
position: fixed; border-radius: 50%;
filter: blur(80px); pointer-events: none; z-index: 0;
animation: float 8s ease-in-out infinite;
}
.orb1 { width: 500px; height: 500px; background: rgba(0,31,91,0.25); top: -150px; left: -150px; animation-delay: 0s; }
.orb2 { width: 400px; height: 400px; background: rgba(0,201,167,0.12); top: 40%; right: -100px; animation-delay: -3s; }
.orb3 { width: 350px; height: 350px; background: rgba(0,61,165,0.15); bottom: -100px; left: 30%; animation-delay: -6s; }

@keyframes float {
0%,100% { transform: translateY(0) scale(1); }
50% { transform: translateY(-30px) scale(1.05); }
}

/* ── LAYOUT ── */
.app { position: relative; z-index: 1; max-width: 1100px; margin: 0 auto; padding: 0 24px 80px; }

/* ── HEADER ── */
header {
display: flex; align-items: center; justify-content: space-between;
padding: 28px 0 40px;
border-bottom: 1px solid rgba(91,141,239,0.15);
margin-bottom: 40px;
}
.logo {
font-family: ‘Space Mono’, monospace;
font-size: 22px; font-weight: 700;
letter-spacing: 6px; color: var(–white);
display: flex; align-items: center; gap: 8px;
}
.logo-dot { width: 8px; height: 8px; background: var(–accent); border-radius: 50%; }
.badge {
background: rgba(0,31,91,0.4);
border: 1px solid rgba(91,141,239,0.3);
border-radius: 20px; padding: 6px 14px;
font-size: 11px; color: var(–lightblue); letter-spacing: 1px;
text-transform: uppercase;
}

/* ── PAGE TITLE ── */
.page-title {
text-align: center; margin-bottom: 48px;
}
.page-title h1 {
font-size: clamp(28px, 4vw, 44px);
font-weight: 700; line-height: 1.15;
background: linear-gradient(135deg, #fff 20%, #7FDFD0 60%, #00C9A7 100%);
-webkit-background-clip: text; -webkit-text-fill-color: transparent;
background-clip: text;
margin-bottom: 12px;
}
.page-title p {
color: var(–gray); font-size: 15px; max-width: 480px; margin: 0 auto;
}

/* ── STEP INDICATOR ── */
.steps-bar {
display: flex; align-items: center; justify-content: center;
gap: 0; margin-bottom: 48px;
}
.step-item {
display: flex; align-items: center; gap: 8px;
font-size: 12px; color: var(–gray);
transition: color 0.3s;
}
.step-item.active { color: var(–white); }
.step-item.done { color: var(–teal); }
.step-num {
width: 28px; height: 28px; border-radius: 50%;
background: rgba(255,255,255,0.06);
border: 1.5px solid rgba(91,141,239,0.2);
display: flex; align-items: center; justify-content: center;
font-size: 11px; font-weight: 700; transition: all 0.3s;
flex-shrink: 0;
}
.step-item.active .step-num {
background: var(–blue); border-color: var(–blue);
color: white; box-shadow: 0 0 16px rgba(0,61,165,0.6);
}
.step-item.done .step-num {
background: var(–teal); border-color: var(–teal); color: white;
}
.step-line {
width: 48px; height: 1px;
background: rgba(91,141,239,0.2); margin: 0 4px;
transition: background 0.3s;
}
.step-line.done { background: var(–teal); }

/* ── SCREENS ── */
.screen { display: none; animation: fadeUp 0.4s ease; }
.screen.active { display: block; }
@keyframes fadeUp {
from { opacity: 0; transform: translateY(20px); }
to { opacity: 1; transform: translateY(0); }
}

/* ── CARDS ── */
.glass-card {
background: rgba(1,42,122,0.35);
border: 1px solid rgba(91,141,239,0.18);
border-radius: 20px; padding: 28px;
backdrop-filter: blur(20px);
box-shadow: 0 8px 40px rgba(0,0,0,0.35);
}
.glass-card-light {
background: rgba(238,244,255,0.04);
border: 1px solid rgba(91,141,239,0.12);
border-radius: 16px; padding: 22px;
}

/* ── SCREEN 1: Incoming Case ── */
.section-label {
font-size: 10px; letter-spacing: 2px; text-transform: uppercase;
color: var(–lightblue); margin-bottom: 8px; font-family: ‘Space Mono’, monospace;
}
.screen-title { font-size: 22px; font-weight: 700; margin-bottom: 6px; }
.screen-sub { font-size: 14px; color: var(–gray); margin-bottom: 28px; }

/* Email mockup */
.email-mock {
background: #1e1030;
border: 1px solid rgba(91,141,239,0.2);
border-radius: 16px; overflow: hidden;
margin-bottom: 24px;
}
.email-header {
background: rgba(0,31,91,0.3);
padding: 14px 20px;
display: flex; align-items: center; gap: 12px;
border-bottom: 1px solid rgba(91,141,239,0.15);
}
.email-avatar {
width: 38px; height: 38px; border-radius: 50%;
background: linear-gradient(135deg, var(–blue), var(–accent));
display: flex; align-items: center; justify-content: center;
font-size: 15px; font-weight: 700; flex-shrink: 0;
}
.email-meta { flex: 1; }
.email-from { font-size: 13px; font-weight: 600; }
.email-subj { font-size: 11px; color: var(–gray); }
.email-time { font-size: 11px; color: var(–gray); font-family: ‘Space Mono’; }
.email-body { padding: 20px; font-size: 13.5px; line-height: 1.7; color: var(–accent2); }
.email-body .highlight { color: var(–red); font-weight: 600; }

/* Case selection */
.case-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; margin-bottom: 28px; }
.case-card {
border: 1.5px solid rgba(91,141,239,0.2);
border-radius: 14px; padding: 16px 18px;
cursor: pointer; transition: all 0.25s;
background: rgba(255,255,255,0.03);
position: relative; overflow: hidden;
}
.case-card::before {
content: ‘’; position: absolute; inset: 0;
background: linear-gradient(135deg, rgba(0,61,165,0.15), transparent);
opacity: 0; transition: opacity 0.25s;
}
.case-card:hover { border-color: rgba(91,141,239,0.5); transform: translateY(-2px); }
.case-card:hover::before { opacity: 1; }
.case-card.selected {
border-color: var(–blue); background: rgba(0,61,165,0.2);
box-shadow: 0 0 20px rgba(0,61,165,0.3);
}
.case-priority {
font-size: 10px; font-weight: 700; letter-spacing: 1px;
padding: 3px 8px; border-radius: 6px; display: inline-block;
margin-bottom: 8px; text-transform: uppercase;
}
.priority-alta { background: rgba(239,83,80,0.2); color: var(–red); }
.priority-media { background: rgba(255,167,38,0.2); color: #FFA726; }
.case-name { font-size: 13px; font-weight: 600; margin-bottom: 4px; }
.case-preview { font-size: 11.5px; color: var(–gray); line-height: 1.5; }
.case-check {
position: absolute; top: 12px; right: 12px;
width: 20px; height: 20px; border-radius: 50%;
background: var(–blue); display: none;
align-items: center; justify-content: center; font-size: 10px;
}
.case-card.selected .case-check { display: flex; }

/* ── SCREEN 2: IA Analysis ── */
.analysis-wrap { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-bottom: 24px; }
.progress-wrap { margin-bottom: 28px; }
.progress-label { display: flex; justify-content: space-between; font-size: 12px; color: var(–gray); margin-bottom: 8px; }
.progress-bar { height: 6px; background: rgba(255,255,255,0.08); border-radius: 3px; overflow: hidden; }
.progress-fill {
height: 100%; width: 0; border-radius: 3px;
background: linear-gradient(90deg, var(–blue), var(–accent));
transition: width 0.05s linear;
}

.analysis-step {
display: flex; align-items: flex-start; gap: 12px;
padding: 12px 16px; border-radius: 12px;
background: rgba(255,255,255,0.03);
margin-bottom: 10px;
border: 1px solid rgba(91,141,239,0.08);
transition: all 0.3s; opacity: 0.4;
}
.analysis-step.active { opacity: 1; background: rgba(0,61,165,0.15); border-color: rgba(91,141,239,0.3); }
.analysis-step.done { opacity: 1; }
.step-icon {
width: 32px; height: 32px; border-radius: 8px;
background: rgba(0,31,91,0.4); flex-shrink: 0;
display: flex; align-items: center; justify-content: center; font-size: 15px;
}
.analysis-step.active .step-icon { background: var(–blue); }
.analysis-step.done .step-icon { background: rgba(0,191,165,0.2); }
.step-text { font-size: 13px; font-weight: 500; margin-bottom: 2px; }
.step-detail { font-size: 11px; color: var(–gray); }
.step-spinner {
margin-left: auto; width: 16px; height: 16px;
border: 2px solid rgba(91,141,239,0.2);
border-top-color: var(–accent); border-radius: 50%;
animation: spin 0.8s linear infinite; display: none; flex-shrink: 0;
}
.analysis-step.active .step-spinner { display: block; }
.step-checkmark { margin-left: auto; color: var(–teal); font-size: 14px; display: none; flex-shrink: 0; }
.analysis-step.done .step-checkmark { display: block; }
.analysis-step.done .step-spinner { display: none; }

@keyframes spin { to { transform: rotate(360deg); } }

/* ── SCREEN 3: Emotional Briefing ── */
.briefing-header {
display: flex; align-items: center; justify-content: space-between;
background: rgba(0,31,91,0.25);
padding: 16px 20px; border-radius: 14px 14px 0 0;
border: 1px solid rgba(91,141,239,0.2);
border-bottom: none;
}
.briefing-body {
background: rgba(0,13,43,0.8);
border: 1px solid rgba(91,141,239,0.2);
border-top: none;
border-radius: 0 0 14px 14px;
padding: 20px;
}
.briefing-row {
display: flex; gap: 14px; padding: 12px 0;
border-bottom: 1px solid rgba(91,141,239,0.08);
align-items: flex-start;
}
.briefing-row:last-child { border-bottom: none; }
.briefing-key {
font-size: 11px; font-weight: 700; color: var(–lightblue);
letter-spacing: 0.5px; min-width: 110px; padding-top: 2px;
font-family: ‘Space Mono’, monospace;
}
.briefing-val { font-size: 13px; color: var(–white); line-height: 1.55; }
.tone-badge {
display: inline-flex; align-items: center; gap: 6px;
padding: 4px 10px; border-radius: 8px;
font-size: 12px; font-weight: 700;
}
.tone-frustrated { background: rgba(239,83,80,0.2); color: var(–red); }
.tone-confused { background: rgba(255,167,38,0.2); color: #FFA726; }
.ai-quote {
background: rgba(0,61,165,0.15);
border-left: 3px solid var(–accent);
border-radius: 0 10px 10px 0;
padding: 12px 16px; font-size: 13px;
color: var(–accent2); font-style: italic; line-height: 1.6;
margin-top: 14px;
}

/* ── SCREEN 4: Agent Response ── */
.response-area {
width: 100%; min-height: 130px;
background: rgba(255,255,255,0.04);
border: 1.5px solid rgba(91,141,239,0.25);
border-radius: 14px; padding: 16px;
color: var(–white); font-family: ‘DM Sans’, sans-serif;
font-size: 14px; line-height: 1.7; resize: none;
outline: none; transition: border-color 0.25s;
}
.response-area:focus { border-color: var(–blue); }
.response-area::placeholder { color: rgba(139,125,168,0.5); }

.tone-meter { margin: 16px 0; }
.tone-meter-label { font-size: 12px; color: var(–gray); margin-bottom: 8px; }
.tone-bar { display: flex; gap: 6px; }
.tone-segment {
flex: 1; height: 8px; border-radius: 4px;
background: rgba(255,255,255,0.06); transition: background 0.4s;
}
.tone-segment.lit-empathic { background: var(–teal); }
.tone-segment.lit-neutral { background: #FFA726; }
.tone-segment.lit-cold { background: var(–red); }
.tone-label-row {
display: flex; justify-content: space-between;
font-size: 10px; color: var(–gray); margin-top: 5px;
}

.mirror-feedback {
background: rgba(0,191,165,0.08);
border: 1px solid rgba(0,191,165,0.25);
border-radius: 12px; padding: 14px 16px;
margin-top: 14px; font-size: 13px;
color: var(–teal2); line-height: 1.6;
display: none;
}
.mirror-feedback.visible { display: block; }
.mirror-feedback strong { color: var(–teal); }

/* ── SCREEN 5: Closure ── */
.csat-stars { display: flex; gap: 10px; margin: 16px 0; }
.star {
font-size: 28px; cursor: pointer;
filter: grayscale(1) opacity(0.4);
transition: all 0.15s; transform-origin: center;
}
.star.lit { filter: none; transform: scale(1.2); }
.star:hover { transform: scale(1.3); filter: none; }

.result-box {
border-radius: 14px; padding: 20px;
text-align: center; margin-top: 20px;
display: none;
}
.result-box.visible { display: block; }
.result-good { background: rgba(0,61,165,0.15); border: 1px solid rgba(0,191,165,0.3); }
.result-bad { background: rgba(239,83,80,0.1); border: 1px solid rgba(239,83,80,0.3); }
.result-icon { font-size: 36px; margin-bottom: 8px; }
.result-title { font-size: 17px; font-weight: 700; margin-bottom: 6px; }
.result-text { font-size: 13px; color: var(–gray); line-height: 1.6; }

/* ── BUTTONS ── */
.btn {
display: inline-flex; align-items: center; gap: 8px;
padding: 13px 24px; border-radius: 12px;
font-size: 14px; font-weight: 600;
cursor: pointer; border: none; outline: none;
transition: all 0.2s; font-family: ‘DM Sans’, sans-serif;
letter-spacing: 0.3px;
}
.btn-primary {
background: var(–blue);
color: white;
box-shadow: 0 4px 20px rgba(0,61,165,0.4);
}
.btn-primary:hover {
background: var(–navy);
box-shadow: 0 6px 28px rgba(0,61,165,0.6);
transform: translateY(-1px);
}
.btn-accent {
background: linear-gradient(135deg, #00C9A7, #00A68C);
color: white;
box-shadow: 0 4px 20px rgba(0,201,167,0.35);
}
.btn-accent:hover { transform: translateY(-1px); box-shadow: 0 6px 28px rgba(0,201,167,0.5); }
.btn-ghost {
background: rgba(255,255,255,0.06);
color: var(–gray); border: 1px solid rgba(255,255,255,0.08);
}
.btn-ghost:hover { background: rgba(255,255,255,0.1); color: white; }
.btn-teal {
background: rgba(0,191,165,0.15); color: var(–teal);
border: 1px solid rgba(0,191,165,0.3);
}
.btn-teal:hover { background: rgba(0,191,165,0.25); }
.btn:disabled { opacity: 0.4; cursor: not-allowed; transform: none !important; }
.btn-row { display: flex; gap: 10px; margin-top: 24px; flex-wrap: wrap; }

/* ── SALESFORCE MINI PANEL ── */
.sf-panel {
background: rgba(0,114,206,0.08);
border: 1px solid rgba(0,114,206,0.25);
border-radius: 14px; padding: 16px 20px;
margin-bottom: 16px;
}
.sf-header { display: flex; align-items: center; gap: 8px; margin-bottom: 12px; }
.sf-logo { font-size: 11px; font-weight: 700; color: #60b5f5; letter-spacing: 1px; }
.sf-field { display: flex; gap: 12px; font-size: 12px; margin-bottom: 6px; }
.sf-field-key { color: #60b5f5; min-width: 90px; font-weight: 600; }
.sf-field-val { color: var(–accent2); }

/* ── SLACK NOTIFICATION ── */
.slack-notif {
background: #001540;
border: 1px solid rgba(0,31,91,0.4);
border-left: 4px solid #00C9A7;
border-radius: 12px; padding: 14px 18px;
margin-bottom: 16px;
display: none;
}
.slack-notif.visible { display: block; animation: slideIn 0.4s ease; }
@keyframes slideIn { from { opacity:0; transform: translateX(-12px); } to { opacity:1; transform: translateX(0); } }
.slack-header { display: flex; align-items: center; gap: 8px; margin-bottom: 10px; }
.slack-icon { font-size: 16px; }
.slack-channel { font-size: 12px; font-weight: 700; color: #5B8DEF; }
.slack-time { font-size: 11px; color: var(–gray); margin-left: auto; }
.slack-msg { font-size: 13px; color: #ccc; line-height: 1.6; }
.slack-msg .s-bold { font-weight: 700; color: white; }
.slack-msg .s-code {
font-family: ‘Space Mono’, monospace; font-size: 11px;
background: rgba(255,255,255,0.08); padding: 1px 5px; border-radius: 4px;
}

/* ── MISC ── */
.divider { height: 1px; background: rgba(91,141,239,0.1); margin: 24px 0; }
.tag { display: inline-flex; align-items: center; gap: 5px; font-size: 11px; padding: 4px 10px; border-radius: 6px; font-weight: 600; }
.tag-sf { background: rgba(0,114,206,0.15); color: #60b5f5; }
.tag-zapier { background: rgba(255,80,0,0.15); color: #ff8c42; }
.tag-slack { background: rgba(0,31,91,0.3); color: #7FDFD0; }
.tag-ai { background: rgba(0,201,167,0.15); color: #00C9A7; }

.history-item {
display: flex; align-items: center; gap: 10px;
padding: 8px 12px; border-radius: 10px;
background: rgba(239,83,80,0.08); border: 1px solid rgba(239,83,80,0.2);
margin-bottom: 8px; font-size: 12px; color: var(–accent2);
}
.history-dot { width: 6px; height: 6px; border-radius: 50%; background: var(–red); flex-shrink:0; }

.two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
@media (max-width: 640px) {
.two-col, .case-grid, .analysis-wrap { grid-template-columns: 1fr; }
.steps-bar { gap: 2px; }
.step-line { width: 20px; }
}

/* typing cursor */
.typing::after { content: ‘|’; animation: blink 0.7s infinite; }
@keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }

.pulse { animation: pulse 2s infinite; }
@keyframes pulse { 0%,100%{box-shadow:0 0 0 0 rgba(0,201,167,0.4)} 50%{box-shadow:0 0 0 10px rgba(0,201,167,0)} }

/* confetti burst */
.confetti { position: fixed; pointer-events:none; z-index: 999; }
.conf-piece {
position: absolute; width: 8px; height: 8px;
border-radius: 2px;
animation: confFall 1.2s ease-out forwards;
}
@keyframes confFall {
0%   { transform: translateY(0) rotate(0deg); opacity:1; }
100% { transform: translateY(160px) rotate(540deg); opacity:0; }
}
</style>

</head>
<body>

<div class="orb orb1"></div>
<div class="orb orb2"></div>
<div class="orb orb3"></div>

<div class="app">

  <!-- HEADER -->

  <header>
    <div class="logo">M O D O <div class="logo-dot"></div></div>
    <div class="badge">CX Demo · Emotional Briefing</div>
  </header>

  <!-- PAGE TITLE -->

  <div class="page-title">
    <h1>Sistema CX Empático con IA</h1>
    <p>Simulación interactiva del flujo completo: desde que llega un caso hasta el cierre empático</p>
  </div>

  <!-- STEPS BAR -->

  <div class="steps-bar" id="stepsBar">
    <div class="step-item active" id="stepItem1">
      <div class="step-num">1</div>
      <span>Caso nuevo</span>
    </div>
    <div class="step-line" id="stepLine1"></div>
    <div class="step-item" id="stepItem2">
      <div class="step-num">2</div>
      <span>Análisis IA</span>
    </div>
    <div class="step-line" id="stepLine2"></div>
    <div class="step-item" id="stepItem3">
      <div class="step-num">3</div>
      <span>Briefing</span>
    </div>
    <div class="step-line" id="stepLine3"></div>
    <div class="step-item" id="stepItem4">
      <div class="step-num">4</div>
      <span>Respuesta</span>
    </div>
    <div class="step-line" id="stepLine4"></div>
    <div class="step-item" id="stepItem5">
      <div class="step-num">5</div>
      <span>Cierre</span>
    </div>
  </div>

  <!-- ═══════════════════════════════════════════════════
       SCREEN 1 — Incoming Case
  ═══════════════════════════════════════════════════ -->

  <div class="screen active" id="screen1">

```
<div class="section-label">Salesforce Service Cloud</div>
<div class="screen-title">Acaba de llegar un caso nuevo</div>
<div class="screen-sub">Selecciona el caso que quieres que la IA analice</div>

<div class="case-grid">

  <div class="case-card" id="case1" onclick="selectCase(1)">
    <div class="case-check">✓</div>
    <div class="case-priority priority-alta">🔴 Alta</div>
    <div class="case-name">María González</div>
    <div class="case-preview">
      "Ya es la tercera vez que les escribo por el mismo problema. Esto es inaceptable, necesito una respuesta ahora..."
    </div>
  </div>

  <div class="case-card" id="case2" onclick="selectCase(2)">
    <div class="case-check">✓</div>
    <div class="case-priority priority-media">🟡 Media</div>
    <div class="case-name">Carlos Ruiz</div>
    <div class="case-preview">
      "Hola, no entiendo cómo funciona el límite de transferencias. Me confundí y no sé si hice algo mal..."
    </div>
  </div>

</div>

<!-- Email preview (shows after selecting) -->
<div id="emailPreview" style="display:none">
  <div class="section-label" style="margin-top:24px">Email recibido</div>
  <div class="email-mock" id="emailMock"></div>

  <div class="sf-panel">
    <div class="sf-header">
      <span class="sf-logo">☁ SALESFORCE</span>
      <span class="tag tag-sf">Caso creado automáticamente</span>
    </div>
    <div id="sfFields"></div>
  </div>
</div>

<div class="btn-row">
  <button class="btn btn-primary" id="btnAnalyze" disabled onclick="goToScreen2()">
    ⚡ Enviar a análisis IA
  </button>
  <button class="btn btn-ghost" onclick="resetDemo()">↺ Reiniciar demo</button>
</div>
```

  </div>

  <!-- ═══════════════════════════════════════════════════
       SCREEN 2 — IA Analysis
  ═══════════════════════════════════════════════════ -->

  <div class="screen" id="screen2">

```
<div class="section-label">Zapier → OpenAI API</div>
<div class="screen-title">La IA está analizando el caso</div>
<div class="screen-sub">Esto tarda ~3 segundos en la vida real</div>

<div class="glass-card" style="margin-bottom:20px">
  <div class="progress-wrap">
    <div class="progress-label">
      <span id="progressLabel">Iniciando análisis...</span>
      <span id="progressPct">0%</span>
    </div>
    <div class="progress-bar"><div class="progress-fill" id="progressFill"></div></div>
  </div>

  <div class="analysis-step" id="aStep1">
    <div class="step-icon">☁️</div>
    <div>
      <div class="step-text">Leyendo caso en Salesforce</div>
      <div class="step-detail">Extrayendo asunto, descripción e historial del cliente</div>
    </div>
    <div class="step-spinner"></div>
    <div class="step-checkmark">✓</div>
  </div>

  <div class="analysis-step" id="aStep2">
    <div class="step-icon">⚡</div>
    <div>
      <div class="step-text">Zapier activa el webhook</div>
      <div class="step-detail">Enviando datos a la API de OpenAI</div>
    </div>
    <div class="step-spinner"></div>
    <div class="step-checkmark">✓</div>
  </div>

  <div class="analysis-step" id="aStep3">
    <div class="step-icon">🧠</div>
    <div>
      <div class="step-text">IA analiza el tono emocional</div>
      <div class="step-detail">Detectando frustración, urgencia, confusión...</div>
    </div>
    <div class="step-spinner"></div>
    <div class="step-checkmark">✓</div>
  </div>

  <div class="analysis-step" id="aStep4">
    <div class="step-icon">📋</div>
    <div>
      <div class="step-text">Generando Emotional Briefing</div>
      <div class="step-detail">Construyendo el resumen empático para el agente</div>
    </div>
    <div class="step-spinner"></div>
    <div class="step-checkmark">✓</div>
  </div>

  <div class="analysis-step" id="aStep5">
    <div class="step-icon">💬</div>
    <div>
      <div class="step-text">Enviando a Slack</div>
      <div class="step-detail">Notificando al agente asignado en #cx-urgente</div>
    </div>
    <div class="step-spinner"></div>
    <div class="step-checkmark">✓</div>
  </div>
</div>

<!-- Slack notification preview -->
<div class="slack-notif" id="slackNotif">
  <div class="slack-header">
    <span class="slack-icon">💬</span>
    <span class="slack-channel">#cx-urgente</span>
    <span class="tag tag-slack">Slack</span>
    <span class="slack-time">ahora</span>
  </div>
  <div class="slack-msg" id="slackMsg"></div>
</div>
```

  </div>

  <!-- ═══════════════════════════════════════════════════
       SCREEN 3 — Emotional Briefing
  ═══════════════════════════════════════════════════ -->

  <div class="screen" id="screen3">

```
<div class="section-label">Lo que ve el agente en Slack</div>
<div class="screen-title">🧠 Emotional Briefing</div>
<div class="screen-sub">El agente recibe este resumen ANTES de abrir el caso</div>

<div style="margin-bottom:24px">
  <div class="briefing-header">
    <div style="display:flex;align-items:center;gap:10px">
      <span style="font-size:13px;font-weight:700" id="briefingTitle">CASO #—</span>
      <span id="briefingPriorityTag"></span>
    </div>
    <div style="display:flex;gap:6px">
      <span class="tag tag-sf">Salesforce</span>
      <span class="tag tag-ai">IA</span>
    </div>
  </div>
  <div class="briefing-body" id="briefingBody"></div>
</div>

<div class="ai-quote" id="aiQuote"></div>

<div class="btn-row">
  <button class="btn btn-primary pulse" onclick="goToScreen4()">
    💬 Redactar respuesta →
  </button>
</div>
```

  </div>

  <!-- ═══════════════════════════════════════════════════
       SCREEN 4 — Agent Response + Mirror Assistant
  ═══════════════════════════════════════════════════ -->

  <div class="screen" id="screen4">

```
<div class="two-col">
  <div>
    <div class="section-label">Agente redacta respuesta</div>
    <div class="screen-title" style="font-size:19px">Mirror Assistant activo</div>
    <div class="screen-sub">La IA analiza tu borrador en tiempo real</div>

    <div class="glass-card-light" style="margin-bottom:16px">
      <div style="font-size:11px;color:var(--lightblue);margin-bottom:8px;font-family:'Space Mono'">MINI BRIEFING</div>
      <div style="font-size:12px;color:var(--accent2);line-height:1.6" id="miniBriefing"></div>
    </div>

    <textarea
      class="response-area"
      id="responseArea"
      placeholder="Escribe tu respuesta al cliente aquí... El Mirror Assistant analiza tu tono mientras escribes."
      oninput="analyzeTone()"
    ></textarea>

    <div class="tone-meter">
      <div class="tone-meter-label">Tono detectado por IA:</div>
      <div class="tone-bar" id="toneBar">
        <div class="tone-segment" id="ts1"></div>
        <div class="tone-segment" id="ts2"></div>
        <div class="tone-segment" id="ts3"></div>
        <div class="tone-segment" id="ts4"></div>
        <div class="tone-segment" id="ts5"></div>
      </div>
      <div class="tone-label-row">
        <span id="toneLeft">—</span>
        <span id="toneRight">—</span>
      </div>
    </div>

    <div class="mirror-feedback" id="mirrorFeedback"></div>
  </div>

  <div>
    <div class="section-label">Sugerencia de la IA</div>
    <div class="screen-title" style="font-size:18px;margin-bottom:14px">Plantilla empática</div>

    <div class="glass-card" style="cursor:pointer;transition:all 0.2s" id="templateCard" onclick="useTemplate()">
      <div style="font-size:11px;color:var(--accent);margin-bottom:10px;font-family:'Space Mono'">
        ✨ CLIC PARA USAR ESTA PLANTILLA
      </div>
      <div style="font-size:13px;color:var(--accent2);line-height:1.75" id="templateText"></div>
    </div>

    <div class="divider"></div>

    <div class="section-label">Canales en Slack</div>
    <div style="display:flex;flex-wrap:wrap;gap:8px;margin-top:8px">
      <span style="font-size:12px;color:var(--accent);padding:6px 12px;background:rgba(0,201,167,0.1);border:1px solid rgba(0,201,167,0.2);border-radius:8px">#cx-urgente</span>
      <span style="font-size:12px;color:var(--teal);padding:6px 12px;background:rgba(0,61,165,0.15);border:1px solid rgba(0,191,165,0.2);border-radius:8px">#cx-equipo</span>
      <span style="font-size:12px;color:var(--lightblue);padding:6px 12px;background:rgba(91,141,239,0.1);border:1px solid rgba(91,141,239,0.2);border-radius:8px">#cx-metricas</span>
    </div>
  </div>
</div>

<div class="btn-row">
  <button class="btn btn-accent" onclick="goToScreen5()" id="btnSend">
    ✅ Enviar y cerrar caso
  </button>
  <button class="btn btn-ghost" onclick="goToScreen3()">← Volver al briefing</button>
</div>
```

  </div>

  <!-- ═══════════════════════════════════════════════════
       SCREEN 5 — Closure & CSAT
  ═══════════════════════════════════════════════════ -->

  <div class="screen" id="screen5">

```
<div class="section-label">Cierre del caso</div>
<div class="screen-title">Caso enviado al cliente 🎉</div>
<div class="screen-sub">El cliente recibe la respuesta y califica la experiencia</div>

<div class="two-col" style="margin-bottom:24px">
  <div class="glass-card">
    <div class="section-label">Calificación del cliente (CSAT)</div>
    <div style="font-size:13px;color:var(--gray);margin-bottom:12px">¿Cómo calificarías la atención recibida?</div>
    <div class="csat-stars" id="csatStars">
      <span class="star" onclick="rateStar(1)" data-val="1">⭐</span>
      <span class="star" onclick="rateStar(2)" data-val="2">⭐</span>
      <span class="star" onclick="rateStar(3)" data-val="3">⭐</span>
      <span class="star" onclick="rateStar(4)" data-val="4">⭐</span>
      <span class="star" onclick="rateStar(5)" data-val="5">⭐</span>
    </div>
    <div id="csatLabel" style="font-size:13px;color:var(--gray);min-height:20px"></div>
  </div>

  <div class="glass-card">
    <div class="section-label">Índice de empatía del caso</div>
    <div style="font-size:13px;color:var(--gray);margin-bottom:16px">Registrado en Salesforce</div>
    <div style="display:flex;flex-direction:column;gap:10px" id="empathyMetrics"></div>
  </div>
</div>

<div class="result-box" id="resultBox"></div>

<div class="btn-row" style="margin-top:28px">
  <button class="btn btn-primary" onclick="resetDemo()">↺ Volver al inicio</button>
  <button class="btn btn-teal" onclick="showNextCase()">▶ Siguiente caso →</button>
</div>
```

  </div>

</div><!-- /app -->

<!-- CONFETTI container -->

<div class="confetti" id="confetti"></div>

<script>
// ─────────────────────────────────────────────────────────────
// DATA
// ─────────────────────────────────────────────────────────────
const cases = {
  1: {
    name: "María González",
    email: "maria.g@email.com",
    priority: "Alta",
    subject: "3er reclamo: problema no resuelto con mi cuenta",
    body: `Hola,\n\nYa es la <span class="highlight">tercera vez que les escribo</span> por el mismo problema y nadie me da una solución. Hace dos semanas me prometieron que lo resolverían y nada.\n\nEstoy muy frustrada. Necesito que esto se resuelva HOY o voy a tener que escalar esto a una queja formal.\n\nAtenamente,\nMaría González`,
    history: ["Caso #4819 · Sin resolución · Hace 3 semanas", "Caso #4820 · Cerrado sin solución · Hace 2 semanas"],
    caseNum: "4821",
    briefing: {
      tone: { label: "Frustración alta", type: "tone-frustrated", emoji: "😤" },
      history: "3er contacto por el mismo problema sin resolución",
      csat: "2 / 5 hace 2 semanas",
      needs: "Ser escuchada y validada — no busca excusas, busca reconocimiento",
      suggestion: "Comienza reconociendo su frustración explícitamente antes de ofrecer cualquier solución",
      aiQuote: '"María no está frustrada con el problema técnico — está frustrada con no sentirse escuchada. Si empezas con \'entiendo perfectamente tu situación\', la temperatura baja 70% antes de dar la solución."',
    },
    template: `Hola María,\n\nMe imagino lo frustrante que debe ser escribirnos por tercera vez sin recibir una solución real. Tienes toda la razón y entiendo completamente tu malestar.\n\nTe pido disculpas sinceras por la demora. Acabo de revisar los casos anteriores y veo exactamente qué pasó. Voy a resolver esto personalmente hoy mismo y te confirmo el resultado antes de las 5pm.\n\n¿Podría llamarte en los próximos 15 minutos para explicarte los pasos?\n\nGracias por tu paciencia,\n[Tu nombre]`,
  },
  2: {
    name: "Carlos Ruiz",
    email: "c.ruiz@gmail.com",
    priority: "Media",
    subject: "Confusión con límites de transferencias",
    body: `Buenos días,\n\nNo sé si hice algo mal pero intenté hacer una transferencia ayer y me apareció un mensaje de "límite alcanzado". <span class="highlight">No entiendo muy bien cómo funciona</span> eso.\n\n¿Me pueden explicar? Quiero asegurarme de no haber hecho algo incorrecto.\n\nGracias,\nCarlos`,
    history: ["Sin historial previo — primer contacto"],
    caseNum: "4822",
    briefing: {
      tone: { label: "Confusión / ansiedad leve", type: "tone-confused", emoji: "😕" },
      history: "Primer contacto — cliente nuevo, sin antecedentes",
      csat: "Sin historial",
      needs: "Claridad y tranquilidad — teme haber cometido un error",
      suggestion: "Primero tranquilízalo ('no hiciste nada mal'), luego explica con lenguaje simple",
      aiQuote: '"Carlos tiene ansiedad de usuario nuevo — siente que \'hizo algo mal\'. Una frase de tranquilidad al inicio (\'no te preocupes, no hiciste nada incorrecto\') convierte este caso en una oportunidad de generar confianza duradera."',
    },
    template: `Hola Carlos,\n\nNo te preocupes para nada — no hiciste absolutamente nada mal. 😊\n\nEl mensaje de "límite alcanzado" es completamente normal y es una función de seguridad de tu cuenta. Te explico cómo funciona en 30 segundos:\n\nTodos los usuarios tienen un límite diario de transferencias por seguridad. Una vez que ese límite se cumple, el sistema bloquea nuevas operaciones hasta el día siguiente, cuando se reinicia automáticamente.\n\nSi necesitás hacer la transferencia hoy mismo, puedo ayudarte a ajustar ese límite. ¿Te parece bien?\n\nUn saludo,\n[Tu nombre]`,
  }
};

let selectedCase = null;
let currentScreen = 1;

// ─────────────────────────────────────────────────────────────
// CASE SELECTION
// ─────────────────────────────────────────────────────────────
function selectCase(id) {
  selectedCase = id;
  document.querySelectorAll('.case-card').forEach(c => c.classList.remove('selected'));
  document.getElementById('case' + id).classList.add('selected');

  const c = cases[id];

  // show email
  document.getElementById('emailPreview').style.display = 'block';
  document.getElementById('emailMock').innerHTML = `
    <div class="email-header">
      <div class="email-avatar">${c.name[0]}</div>
      <div class="email-meta">
        <div class="email-from">${c.name} &lt;${c.email}&gt;</div>
        <div class="email-subj">${c.subject}</div>
      </div>
      <div class="email-time">ahora</div>
    </div>
    <div class="email-body">${c.body.replace(/\n/g,'<br>')}</div>
  `;

  document.getElementById('sfFields').innerHTML = `
    <div class="sf-field"><span class="sf-field-key">Caso #</span><span class="sf-field-val">${c.caseNum}</span></div>
    <div class="sf-field"><span class="sf-field-key">Cliente</span><span class="sf-field-val">${c.name}</span></div>
    <div class="sf-field"><span class="sf-field-key">Prioridad</span><span class="sf-field-val">${c.priority}</span></div>
    <div class="sf-field"><span class="sf-field-key">Estado</span><span class="sf-field-val">Nuevo — Sin asignar</span></div>
    ${c.history.map(h => `<div class="history-item"><div class="history-dot"></div>${h}</div>`).join('')}
  `;

  document.getElementById('btnAnalyze').disabled = false;
}

// ─────────────────────────────────────────────────────────────
// SCREEN NAVIGATION
// ─────────────────────────────────────────────────────────────
function showScreen(n) {
  document.querySelectorAll('.screen').forEach(s => s.classList.remove('active'));
  document.getElementById('screen' + n).classList.add('active');
  currentScreen = n;

  // update steps
  for (let i = 1; i <= 5; i++) {
    const item = document.getElementById('stepItem' + i);
    item.classList.remove('active','done');
    if (i < n) { item.classList.add('done'); }
    else if (i === n) { item.classList.add('active'); }
    if (i < 5) {
      const line = document.getElementById('stepLine' + i);
      line.classList.toggle('done', i < n);
    }
  }
  window.scrollTo({top: 0, behavior:'smooth'});
}

// ─────────────────────────────────────────────────────────────
// SCREEN 2: IA ANALYSIS ANIMATION
// ─────────────────────────────────────────────────────────────
function goToScreen2() {
  showScreen(2);
  runAnalysis();
}

function runAnalysis() {
  const steps = [1,2,3,4,5];
  const labels = [
    "Leyendo caso en Salesforce...",
    "Conectando con Zapier...",
    "Analizando tono emocional...",
    "Generando Emotional Briefing...",
    "Enviando notificación a Slack..."
  ];
  let pct = 0;
  let stepIdx = 0;

  const fill = document.getElementById('progressFill');
  const lbl = document.getElementById('progressLabel');
  const pctEl = document.getElementById('progressPct');

  // reset
  steps.forEach(i => {
    const el = document.getElementById('aStep' + i);
    el.classList.remove('active','done');
  });
  document.getElementById('slackNotif').classList.remove('visible');

  function activateStep(i) {
    if (i > 0) document.getElementById('aStep' + i).classList.remove('active');
    if (i <= 5) document.getElementById('aStep' + i).classList.add('active');
  }

  function doneStep(i) {
    const el = document.getElementById('aStep' + i);
    el.classList.remove('active');
    el.classList.add('done');
  }

  // animate progress
  const interval = setInterval(() => {
    pct++;
    fill.style.width = pct + '%';
    pctEl.textContent = pct + '%';

    // step triggers
    if (pct === 10) { activateStep(1); lbl.textContent = labels[0]; }
    if (pct === 22) { doneStep(1); activateStep(2); lbl.textContent = labels[1]; }
    if (pct === 40) { doneStep(2); activateStep(3); lbl.textContent = labels[2]; }
    if (pct === 62) { doneStep(3); activateStep(4); lbl.textContent = labels[3]; }
    if (pct === 82) { doneStep(4); activateStep(5); lbl.textContent = labels[4]; }
    if (pct === 95) { doneStep(5); }

    if (pct >= 100) {
      clearInterval(interval);
      lbl.textContent = "✓ Análisis completo";
      showSlackNotif();
      setTimeout(() => showScreen3(), 1800);
    }
  }, 28);
}

function showSlackNotif() {
  const c = cases[selectedCase];
  const b = c.briefing;
  const notif = document.getElementById('slackNotif');
  document.getElementById('slackMsg').innerHTML = `
    <span class="s-bold">🧠 Emotional Briefing — Caso #${c.caseNum}</span><br>
    <span class="s-code">Cliente:</span> ${c.name} &nbsp;·&nbsp;
    <span class="s-code">Prioridad:</span> ${c.priority}<br>
    <span class="s-code">Tono:</span> ${b.tone.emoji} ${b.tone.label}<br>
    <span class="s-code">Sugerencia IA:</span> ${b.suggestion}
  `;
  notif.classList.add('visible');
}

// ─────────────────────────────────────────────────────────────
// SCREEN 3: BRIEFING
// ─────────────────────────────────────────────────────────────
function showScreen3() {
  const c = cases[selectedCase];
  const b = c.briefing;

  document.getElementById('briefingTitle').textContent = `CASO #${c.caseNum} — ${c.name}`;
  document.getElementById('briefingPriorityTag').innerHTML =
    `<span class="tag ${c.priority === 'Alta' ? 'priority-alta' : 'priority-media'}">${c.priority === 'Alta' ? '🔴' : '🟡'} ${c.priority}</span>`;

  document.getElementById('briefingBody').innerHTML = `
    <div class="briefing-row">
      <div class="briefing-key">😤 Tono</div>
      <div class="briefing-val"><span class="tone-badge ${b.tone.type}">${b.tone.emoji} ${b.tone.label}</span></div>
    </div>
    <div class="briefing-row">
      <div class="briefing-key">🔁 Historial</div>
      <div class="briefing-val">${b.history}</div>
    </div>
    <div class="briefing-row">
      <div class="briefing-key">⭐ Último CSAT</div>
      <div class="briefing-val">${b.csat}</div>
    </div>
    <div class="briefing-row">
      <div class="briefing-key">💬 Lo que necesita</div>
      <div class="briefing-val">${b.needs}</div>
    </div>
    <div class="briefing-row">
      <div class="briefing-key">💡 Sugerencia IA</div>
      <div class="briefing-val" style="color:var(--accent2)">${b.suggestion}</div>
    </div>
  `;

  document.getElementById('aiQuote').textContent = `🤖 IA dice: ${b.aiQuote}`;
  showScreen(3);
}

function goToScreen3() { showScreen3(); }

// ─────────────────────────────────────────────────────────────
// SCREEN 4: MIRROR ASSISTANT
// ─────────────────────────────────────────────────────────────
function goToScreen4() {
  const c = cases[selectedCase];
  const b = c.briefing;

  document.getElementById('miniBriefing').innerHTML =
    `<strong style="color:var(--lightblue)">${b.tone.emoji} Tono detectado:</strong> ${b.tone.label}<br>` +
    `<strong style="color:var(--lightblue)">💡 Recordatorio:</strong> ${b.suggestion}`;

  document.getElementById('templateText').innerHTML =
    c.template.replace(/\n/g,'<br>');

  // reset
  document.getElementById('responseArea').value = '';
  document.getElementById('mirrorFeedback').classList.remove('visible');
  resetToneBar();

  showScreen(4);
}

let toneTimer = null;
function analyzeTone() {
  const text = document.getElementById('responseArea').value.toLowerCase();
  clearTimeout(toneTimer);
  toneTimer = setTimeout(() => {
    if (text.length < 20) { resetToneBar(); return; }

    // simple keyword scoring
    const empathicWords = ['entiendo','comprendo','imagino','frustrante','disculpa','perdón','razón','sincera','gracias','ayuda','tranquil','no te preocupes','solucion'];
    const coldWords = ['según','normas','política','procedimiento','le informamos','estimado usuario','no podemos','imposible'];

    let empathicScore = 0, coldScore = 0;
    empathicWords.forEach(w => { if (text.includes(w)) empathicScore++; });
    coldWords.forEach(w => { if (text.includes(w)) coldScore++; });

    const total = Math.max(empathicScore + coldScore, 1);
    const ratio = empathicScore / total;
    const segs = Math.round(ratio * 5);

    const bar = document.getElementById('toneBar');
    bar.querySelectorAll('.tone-segment').forEach((s,i) => {
      s.className = 'tone-segment';
      if (i < segs) s.classList.add('lit-empathic');
      else if (i < segs + 1 && coldScore > 0) s.classList.add('lit-neutral');
    });

    const feedback = document.getElementById('mirrorFeedback');
    if (ratio >= 0.7) {
      document.getElementById('toneLeft').textContent = '😊 Empático';
      document.getElementById('toneRight').textContent = 'Excelente tono';
      feedback.innerHTML = `<strong>✅ Tono excelente.</strong> Tu respuesta tiene un tono empático y cálido. El cliente va a sentirse escuchado. ¡Listo para enviar!`;
      feedback.className = 'mirror-feedback visible';
      feedback.style.borderColor = 'rgba(0,191,165,0.3)';
      feedback.style.background = 'rgba(0,191,165,0.08)';
      feedback.style.color = 'var(--teal2)';
    } else if (ratio >= 0.4) {
      document.getElementById('toneLeft').textContent = '😐 Neutral';
      document.getElementById('toneRight').textContent = 'Puede mejorar';
      feedback.innerHTML = `<strong>💡 Sugerencia:</strong> Tu respuesta es correcta pero suena un poco protocolar. Intenta agregar una frase de reconocimiento emocional al inicio.`;
      feedback.className = 'mirror-feedback visible';
      feedback.style.borderColor = 'rgba(255,167,38,0.3)';
      feedback.style.background = 'rgba(255,167,38,0.06)';
      feedback.style.color = '#FFA726';
    } else if (coldScore > 0) {
      document.getElementById('toneLeft').textContent = '🥶 Frío';
      document.getElementById('toneRight').textContent = 'Revisar tono';
      feedback.innerHTML = `<strong>⚠️ Tono muy formal/frío.</strong> Palabras como "normas", "política" o "le informamos" suenan distantes. Para este cliente, considera usar un lenguaje más cercano.`;
      feedback.className = 'mirror-feedback visible';
      feedback.style.borderColor = 'rgba(239,83,80,0.3)';
      feedback.style.background = 'rgba(239,83,80,0.06)';
      feedback.style.color = 'var(--red)';
    } else {
      feedback.classList.remove('visible');
      document.getElementById('toneLeft').textContent = 'Escribiendo...';
      document.getElementById('toneRight').textContent = '';
    }
  }, 400);
}

function resetToneBar() {
  document.querySelectorAll('.tone-segment').forEach(s => { s.className = 'tone-segment'; });
  document.getElementById('toneLeft').textContent = '—';
  document.getElementById('toneRight').textContent = '—';
}

function useTemplate() {
  const c = cases[selectedCase];
  document.getElementById('responseArea').value = c.template;
  analyzeTone();
  document.getElementById('templateCard').style.opacity = '0.5';
  setTimeout(() => document.getElementById('templateCard').style.opacity = '1', 1000);
}

// ─────────────────────────────────────────────────────────────
// SCREEN 5: CSAT & CLOSURE
// ─────────────────────────────────────────────────────────────
function goToScreen5() {
  const text = document.getElementById('responseArea').value;
  if (text.length < 15) {
    document.getElementById('responseArea').style.borderColor = 'var(--red)';
    document.getElementById('responseArea').placeholder = '⚠️ Escribe una respuesta primero...';
    setTimeout(() => {
      document.getElementById('responseArea').style.borderColor = '';
      document.getElementById('responseArea').placeholder = 'Escribe tu respuesta al cliente aquí...';
    }, 2000);
    return;
  }

  // compute empathy from response
  const lowText = text.toLowerCase();
  const empathic = ['entiendo','comprendo','imagino','disculpa','razón','gracias','tranquil','no te preocupes'].filter(w => lowText.includes(w)).length;
  const empathyScore = Math.min(Math.round((empathic / 3) * 100), 100);

  // fill metrics
  document.getElementById('empathyMetrics').innerHTML = `
    <div style="display:flex;justify-content:space-between;font-size:12px">
      <span style="color:var(--gray)">🫀 Empatía detectada</span>
      <span style="color:var(--teal);font-weight:700">${empathyScore}%</span>
    </div>
    <div style="height:5px;background:rgba(255,255,255,0.06);border-radius:3px;overflow:hidden">
      <div style="height:100%;width:${empathyScore}%;background:var(--teal);border-radius:3px;transition:width 0.8s ease"></div>
    </div>
    <div style="display:flex;justify-content:space-between;font-size:12px;margin-top:8px">
      <span style="color:var(--gray)">⏱️ Tiempo de respuesta</span>
      <span style="color:var(--accent2);font-weight:700">~2 min</span>
    </div>
    <div style="display:flex;justify-content:space-between;font-size:12px;margin-top:6px">
      <span style="color:var(--gray)">🧠 Briefing IA utilizado</span>
      <span style="color:var(--teal);font-weight:700">Sí</span>
    </div>
  `;

  document.getElementById('resultBox').className = 'result-box';
  document.getElementById('resultBox').innerHTML = '';

  showScreen(5);
}

let csatVal = 0;
function rateStar(n) {
  csatVal = n;
  const stars = document.querySelectorAll('.star');
  stars.forEach((s, i) => s.classList.toggle('lit', i < n));

  const labels = ['', '😠 Muy mala experiencia', '😞 Mala experiencia', '😐 Regular', '😊 Buena experiencia', '🤩 Excelente experiencia'];
  document.getElementById('csatLabel').textContent = labels[n];

  const result = document.getElementById('resultBox');
  if (n >= 4) {
    result.className = 'result-box result-good visible';
    result.innerHTML = `
      <div class="result-icon">🎉</div>
      <div class="result-title" style="color:var(--teal)">¡Caso cerrado exitosamente!</div>
      <div class="result-text">El cliente calificó con ${n}/5. El Emotional Briefing funcionó — el agente llegó preparado emocionalmente y el cliente lo sintió. Este resultado queda registrado en Salesforce como KPI de empatía.</div>
    `;
    spawnConfetti();
  } else {
    result.className = 'result-box result-bad visible';
    result.innerHTML = `
      <div class="result-icon">🔴</div>
      <div class="result-title" style="color:var(--red)">Caso escalado a #cx-recuperacion</div>
      <div class="result-text">CSAT bajo (${n}/5). Zapier envía automáticamente una alerta al canal #cx-recuperacion para intervención proactiva del líder de CX. El sistema aprende de este caso para mejorar futuros briefings.</div>
    `;
  }
}

function spawnConfetti() {
  const container = document.getElementById('confetti');
  container.innerHTML = '';
  const colors = ['#00C9A7','#003DA5','#00BFA5','#5B8DEF','#FFFFFF'];
  for (let i = 0; i < 40; i++) {
    const piece = document.createElement('div');
    piece.className = 'conf-piece';
    piece.style.left = (20 + Math.random() * 60) + '%';
    piece.style.top = (30 + Math.random() * 30) + '%';
    piece.style.background = colors[Math.floor(Math.random() * colors.length)];
    piece.style.animationDelay = (Math.random() * 0.5) + 's';
    piece.style.animationDuration = (0.8 + Math.random() * 0.8) + 's';
    container.appendChild(piece);
  }
  setTimeout(() => container.innerHTML = '', 2000);
}

// ─────────────────────────────────────────────────────────────
// UTILS
// ─────────────────────────────────────────────────────────────
function resetDemo() {
  selectedCase = null;
  document.querySelectorAll('.case-card').forEach(c => c.classList.remove('selected'));
  document.getElementById('emailPreview').style.display = 'none';
  document.getElementById('btnAnalyze').disabled = true;
  document.getElementById('responseArea') && (document.getElementById('responseArea').value = '');
  document.getElementById('resultBox') && (document.getElementById('resultBox').className = 'result-box');
  document.getElementById('mirrorFeedback') && document.getElementById('mirrorFeedback').classList.remove('visible');
  csatVal = 0;
  showScreen(1);
}

function showNextCase() {
  const nextId = selectedCase === 1 ? 2 : 1;
  resetDemo();
  setTimeout(() => selectCase(nextId), 100);
}
</script>

</body>
</html>
