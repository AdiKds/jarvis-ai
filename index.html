<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<title>J.A.R.V.I.S v6.0 — Cyber Cat Superagent HUD by Mohamad Hartadi</title>
<meta name="description" content="JARVIS AI — Futuristic AI agent interface with Cyber Cat Avatar, 3D atomic orbits, dynamic quotes, and 28 Apps Database. Built by Mohamad Hartadi.">
<meta name="author" content="Mohamad Hartadi">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;500;600;700;800;900&family=Rajdhani:wght@400;500;600;700&family=Share+Tech+Mono&display=swap" rel="stylesheet">
<style>
:root {
  --cyan: #00ffff;
  --blue: #0088ff;
  --amber: #f59e0b;
  --pink: #ff007f;
  --bg-obsidian: #00040a;
  --glow: 0 0 15px rgba(0, 255, 255, 0.7), 0 0 30px rgba(0, 255, 255, 0.3);
  --pink-glow: 0 0 15px rgba(255, 0, 127, 0.7), 0 0 30px rgba(255, 0, 127, 0.3);
  --border: 1px solid rgba(0, 255, 255, 0.3);
}
* { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Rajdhani', sans-serif; user-select: none; }
body { background: var(--bg-obsidian); color: var(--cyan); overflow-x: hidden; min-height: 100vh; display: flex; flex-direction: column; }
.orbitron { font-family: 'Orbitron', sans-serif; }
.mono { font-family: 'Share Tech Mono', monospace; }
.text-glow { text-shadow: var(--glow); }

/* ANIMATIONS & KEYFRAMES */
@keyframes spin { from { transform: rotate(0deg); } to { transform: rotate(360deg); } }
@keyframes spin-rev { from { transform: rotate(360deg); } to { transform: rotate(0deg); } }
@keyframes orbit-3d-1 { 0% { transform: rotateX(65deg) rotateY(-15deg) rotateZ(0deg); } 100% { transform: rotateX(65deg) rotateY(-15deg) rotateZ(360deg); } }
@keyframes orbit-3d-2 { 0% { transform: rotateX(65deg) rotateY(55deg) rotateZ(360deg); } 100% { transform: rotateX(65deg) rotateY(55deg) rotateZ(0deg); } }
@keyframes orbit-3d-3 { 0% { transform: rotateX(25deg) rotateY(70deg) rotateZ(0deg); } 100% { transform: rotateX(25deg) rotateY(70deg) rotateZ(360deg); } }
@keyframes pulse { 0%, 100% { transform: scale(1); opacity: 0.8; } 50% { transform: scale(1.05); opacity: 1; filter: drop-shadow(0 0 25px var(--cyan)); } }
@keyframes scanline { 0% { top: 0%; } 100% { top: 100%; } }
@keyframes floatY { 0%, 100% { transform: translateY(0px); } 50% { transform: translateY(-8px); } }
@keyframes audio-bar { 0%, 100% { height: 4px; } 50% { height: 28px; } }

/* Universal Cyber Cat Animations */
@keyframes blinkL { 0%, 85%, 100% { transform: scaleY(1); } 90% { transform: scaleY(0.05); } }
@keyframes blinkR { 0%, 35%, 100% { transform: scaleY(1); } 40% { transform: scaleY(0.05); } }
@keyframes earL { 0%, 80%, 100% { transform: rotate(0deg); } 90% { transform: rotate(-18deg); } }
@keyframes earR { 0%, 30%, 100% { transform: rotate(0deg); } 40% { transform: rotate(18deg); } }
.eye-left { transform-origin: 35px 50px; animation: blinkL 3.5s infinite; }
.eye-right { transform-origin: 65px 50px; animation: blinkR 3.5s infinite; }
.ear-left { transform-origin: 25px 35px; animation: earL 4s infinite ease-in-out; }
.ear-right { transform-origin: 75px 35px; animation: earR 4.5s infinite ease-in-out; }
@keyframes cat-mouth-talk { 0%, 100% { transform: scaleY(0.2) scaleX(0.9); } 25% { transform: scaleY(1.3) scaleX(1.1); } 50% { transform: scaleY(0.7) scaleX(0.95); } 75% { transform: scaleY(1.1) scaleX(1.05); } }

/* Quote Text Animations */
@keyframes color-shift {
  0% { color: #00ffff; text-shadow: 0 0 10px #00ffff; }
  33% { color: #ff007f; text-shadow: 0 0 10px #ff007f; }
  66% { color: #f59e0b; text-shadow: 0 0 10px #f59e0b; }
  100% { color: #00ffff; text-shadow: 0 0 10px #00ffff; }
}
@keyframes fade-slide { 0% { opacity: 0; transform: translateY(10px); } 10% { opacity: 1; transform: translateY(0); } 90% { opacity: 1; transform: translateY(0); } 100% { opacity: 0; transform: translateY(-10px); } }

/* SCANLINE & CORNERS */
.scan-line { position: fixed; top: 0; left: 0; width: 100%; height: 3px; background: linear-gradient(90deg, transparent, var(--cyan), transparent); opacity: 0.4; animation: scanline 6s linear infinite; z-index: 5; }
.corner { position: fixed; width: 22px; height: 22px; border: 2px solid var(--cyan); z-index: 10; pointer-events: none; }
.c-tl { top: 8px; left: 8px; border-right: none; border-bottom: none; }
.c-tr { top: 8px; right: 8px; border-left: none; border-bottom: none; }
.c-bl { bottom: 8px; left: 8px; border-right: none; border-top: none; }
.c-br { bottom: 8px; right: 8px; border-left: none; border-top: none; }

/* TOOLTIP */
#custom-tooltip { position: fixed; background: rgba(0, 15, 30, 0.95); border: 1px solid var(--cyan); padding: 6px 12px; border-radius: 6px; font-size: 12px; color: #fff; font-family: 'Orbitron'; z-index: 10000; pointer-events: none; opacity: 0; transition: opacity 0.2s, transform 0.2s; box-shadow: var(--glow); transform: translateY(5px); }
#custom-tooltip.show { opacity: 1; transform: translateY(0); }

/* BOOT SCREEN */
#boot-screen { position: fixed; inset: 0; background: #000208; z-index: 500; display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 20px; text-align: center; }
.boot-avatar { width: 150px; height: 150px; margin-bottom: 20px; filter: drop-shadow(0 0 20px rgba(6,182,212,0.6)); animation: pulse 2s infinite; }
.boot-title { font-size: clamp(20px, 5vw, 28px); letter-spacing: 6px; margin-bottom: 10px; }
.boot-bar-wrap { width: 280px; height: 4px; background: rgba(0, 255, 255, 0.1); border-radius: 2px; overflow: hidden; margin: 15px 0; border: 1px solid rgba(0, 255, 255, 0.3); }
.boot-bar-fill { height: 100%; width: 0%; background: var(--cyan); box-shadow: 0 0 12px var(--cyan); transition: width 0.1s linear; }
.boot-status { font-size: 13px; color: rgba(0, 255, 255, 0.7); letter-spacing: 2px; }

/* SCREENSAVER */
#screensaver { position: fixed; inset: 0; background: rgba(0, 3, 10, 0.96); z-index: 400; display: none; flex-direction: column; align-items: center; justify-content: space-evenly; backdrop-filter: blur(12px); cursor: pointer; padding: 20px 10px; }
.ss-time { font-size: clamp(40px, 8vw, 86px); font-weight: 900; letter-spacing: 4px; text-shadow: 0 0 35px var(--cyan); line-height: 1; margin-bottom: 10px; }
.ss-date { font-size: clamp(14px, 2.5vw, 24px); color: #88ccff; letter-spacing: 6px; margin-bottom: 15px; }
.ss-hint { font-size: 12px; letter-spacing: 3px; color: rgba(0, 255, 255, 0.5); animation: pulse 2s infinite; text-align: center; margin-top: 10px; }

/* MAIN HUD LAYOUT */
#main-hud { display: none; flex: 1; width: 100%; padding: 12px; z-index: 10; flex-direction: column; gap: 12px; max-width: 1650px; margin: 0 auto; }
.header-bar { display: flex; justify-content: space-between; align-items: center; border-bottom: 1px solid rgba(0, 255, 255, 0.2); padding-bottom: 8px; flex-wrap: wrap; gap: 10px; }
.header-title { font-size: clamp(16px, 2.5vw, 22px); font-weight: 800; letter-spacing: 4px; display: flex; align-items: center; gap: 10px; }
.header-controls { display: flex; gap: 8px; align-items: center; flex-wrap: wrap; }

.btn-hud { background: rgba(0, 30, 60, 0.6); border: var(--border); color: var(--cyan); padding: 8px 14px; border-radius: 6px; font-size: 12px; font-family: 'Orbitron'; letter-spacing: 1px; cursor: pointer; transition: all 0.2s; display: inline-flex; align-items: center; gap: 6px; }
.btn-hud:hover { background: rgba(0, 255, 255, 0.25); box-shadow: var(--glow); transform: translateY(-2px); }

/* GRID RESPOSIF */
.hud-grid { display: grid; grid-template-columns: 1fr; gap: 12px; flex: 1; }
@media (min-width: 900px) { .hud-grid { grid-template-columns: 290px 1fr 320px; } }
@media (min-width: 1200px) { .hud-grid { grid-template-columns: 320px 1fr 360px; } }

.panel { background: rgba(0, 15, 30, 0.55); border: var(--border); border-radius: 10px; padding: 14px; position: relative; overflow: hidden; display: flex; flex-direction: column; gap: 10px; backdrop-filter: blur(8px); }
.panel::before { content: ''; position: absolute; top: 0; left: 0; width: 30px; height: 2px; background: var(--cyan); }
.panel-title { font-family: 'Orbitron'; font-size: 11px; color: rgba(0, 255, 255, 0.75); letter-spacing: 2px; text-transform: uppercase; border-bottom: 1px dashed rgba(0, 255, 255, 0.2); padding-bottom: 6px; display: flex; justify-content: space-between; align-items: center; }

/* LEFT PANEL: QUICK ACTIONS */
.quick-action-list { display: flex; flex-direction: column; gap: 8px; }
.action-item { background: rgba(0, 25, 50, 0.4); border: 1px solid rgba(0, 255, 255, 0.15); padding: 10px; border-radius: 6px; cursor: pointer; transition: all 0.2s; display: flex; align-items: center; gap: 12px; text-decoration: none; color: inherit; }
.action-item:hover { background: rgba(0, 255, 255, 0.15); border-color: var(--cyan); transform: translateX(5px); }
.action-icon { font-size: 18px; width: 32px; height: 32px; display: flex; align-items: center; justify-content: center; background: rgba(0, 255, 255, 0.1); border-radius: 6px; flex-shrink: 0; }

/* CENTER PANEL: 3D ATOMIC ORBIT & CYBER CAT AVATAR */
.center-stage { display: flex; flex-direction: column; align-items: center; justify-content: center; min-height: 400px; position: relative; padding: 20px 0; perspective: 1000px; flex: 1; }

/* Interactive Clock in Center */
.center-clock-wrap { cursor: pointer; text-align: center; margin-bottom: 15px; z-index: 15; padding: 6px 16px; background: rgba(0, 20, 40, 0.6); border: 1px solid rgba(0,255,255,0.4); border-radius: 30px; transition: all 0.3s; box-shadow: 0 0 15px rgba(0,255,255,0.15); }
.center-clock-wrap:hover { transform: scale(1.05); border-color: var(--cyan); box-shadow: var(--glow); background: rgba(0, 40, 80, 0.8); }
.center-time { font-size: clamp(22px, 4vw, 32px); font-weight: 900; letter-spacing: 4px; animation: color-shift 8s infinite; }
.center-day { font-size: 11px; letter-spacing: 3px; color: #fff; opacity: 0.8; }

/* 3D Atomic Orbit Rings */
.atom-orbit-container { position: absolute; width: clamp(220px, 46vw, 360px); height: clamp(220px, 46vw, 360px); display: flex; align-items: center; justify-content: center; transform-style: preserve-3d; pointer-events: none; }
.orbit-ring-3d { position: absolute; width: 100%; height: 100%; border-radius: 50%; transform-style: preserve-3d; }
.ring-1 { border: 2px solid rgba(0, 255, 255, 0.6); animation: orbit-3d-1 12s linear infinite; box-shadow: inset 0 0 15px rgba(0,255,255,0.2); }
.ring-2 { border: 2px dashed rgba(0, 136, 255, 0.7); animation: orbit-3d-2 16s linear infinite; }
.ring-3 { border: 1px dotted rgba(245, 158, 11, 0.7); animation: orbit-3d-3 20s linear infinite; }
.electron { position: absolute; top: 0; left: 50%; width: 10px; height: 10px; background: #00ffff; border-radius: 50%; box-shadow: 0 0 15px #00ffff, 0 0 25px #ffffff; transform: translate(-50%, -50%); }
.electron.amber { background: #f59e0b; box-shadow: 0 0 15px #f59e0b, 0 0 25px #ffffff; }

/* 2D Background Radar Arcs */
.radar-ring { position: absolute; border-radius: 50%; border: 1px solid rgba(0, 255, 255, 0.15); pointer-events: none; }
.r1 { width: clamp(200px, 42vw, 330px); height: clamp(200px, 42vw, 330px); border-top: 2px solid var(--cyan); border-bottom: 2px solid var(--cyan); animation: spin 20s linear infinite; }
.r2 { width: clamp(150px, 34vw, 260px); height: clamp(150px, 34vw, 260px); border-left: 2px dashed rgba(0, 255, 255, 0.5); border-right: 2px dashed rgba(0, 255, 255, 0.5); animation: spin-rev 25s linear infinite; }

/* Cyber Cat Avatar SVG Wrap */
.cat-avatar-wrap { width: clamp(130px, 28vw, 190px); height: clamp(130px, 28vw, 190px); z-index: 5; filter: drop-shadow(0 0 20px rgba(6,182,212,0.7)); animation: floatY 5s ease-in-out infinite; cursor: pointer; transition: transform 0.3s; }
.cat-avatar-wrap:hover { transform: scale(1.08); filter: drop-shadow(0 0 25px var(--pink)); }

/* Audio Visualizer Wave */
.visualizer-box { display: flex; gap: 4px; align-items: center; justify-content: center; height: 30px; margin-top: 10px; z-index: 5; }
.vis-bar { width: 4px; height: 6px; background: var(--cyan); border-radius: 2px; box-shadow: 0 0 8px var(--cyan); transition: height 0.1s ease; }
.vis-bar.active { animation: audio-bar 0.4s ease-in-out infinite alternate; }

/* Quote Box on Main Center Stage */
.main-quote-box { background: rgba(0, 20, 40, 0.6); border: 1px solid rgba(0, 255, 255, 0.2); border-left: 3px solid var(--pink); padding: 10px 14px; border-radius: 6px; font-size: 13px; color: #fff; max-width: 90%; text-align: center; margin-top: 10px; z-index: 5; min-height: 50px; display: flex; align-items: center; justify-content: center; font-style: italic; animation: color-shift 10s infinite; }

/* COMMAND INPUT */
.command-box { display: flex; gap: 8px; width: 100%; margin-top: auto; }
.cmd-input { flex: 1; background: rgba(0, 10, 20, 0.8); border: var(--border); color: var(--cyan); padding: 12px 16px; border-radius: 8px; font-size: 15px; outline: none; transition: 0.3s; }
.cmd-input:focus { border-color: #fff; box-shadow: var(--glow); }
.mic-btn { width: 45px; height: 45px; border-radius: 8px; border: var(--border); background: rgba(0, 255, 255, 0.1); color: var(--cyan); font-size: 18px; cursor: pointer; transition: 0.3s; display: flex; align-items: center; justify-content: center; flex-shrink: 0; }
.mic-btn.listening { background: rgba(255, 50, 50, 0.3); border-color: #ff3333; color: #ff3333; animation: pulse 1s infinite; }

/* RIGHT PANEL: ACTIVITY LOG */
.log-container { flex: 1; background: rgba(0, 5, 12, 0.6); border: 1px solid rgba(0, 255, 255, 0.15); border-radius: 6px; padding: 10px; overflow-x: hidden; overflow-y: auto; max-height: 350px; display: flex; flex-direction: column; gap: 8px; font-size: 12px; }
.log-entry { display: flex; gap: 8px; line-height: 1.4; border-bottom: 1px solid rgba(0, 255, 255, 0.05); padding-bottom: 6px; }
.log-time { color: rgba(0, 255, 255, 0.5); font-weight: bold; }
.log-text { color: #d0f0ff; flex: 1; word-break: break-word; }
.log-text.sys { color: #00ffaa; }
.log-text.warn { color: #ffaa00; }
.log-text.user { color: #33aaff; }

/* FOOTER CREDIT BAR */
.footer-bar { display: flex; justify-content: space-between; align-items: center; background: rgba(0, 15, 30, 0.75); border: var(--border); border-radius: 8px; padding: 10px 16px; margin-top: auto; flex-wrap: wrap; gap: 10px; }
.dev-info { display: flex; align-items: center; gap: 12px; }
.dev-icon { font-size: 26px; color: var(--cyan); filter: drop-shadow(0 0 10px var(--cyan)); }

/* MODALS / OVERLAYS */
.modal-overlay { position: fixed; inset: 0; background: rgba(0, 5, 15, 0.92); backdrop-filter: blur(12px); z-index: 300; display: none; align-items: center; justify-content: center; padding: 15px; opacity: 0; transition: opacity 0.3s; }
.modal-overlay.active { display: flex; opacity: 1; }
.modal-box { background: rgba(0, 20, 40, 0.88); border: 1px solid var(--cyan); border-radius: 12px; width: 100%; max-width: 900px; max-height: 88vh; overflow-y: auto; padding: 22px; position: relative; box-shadow: 0 0 35px rgba(0, 255, 255, 0.25); }
.modal-close { position: absolute; top: 15px; right: 15px; width: 34px; height: 34px; border-radius: 50%; border: 1px solid #ff4444; background: rgba(255, 50, 50, 0.1); color: #ff4444; font-size: 18px; cursor: pointer; display: flex; align-items: center; justify-content: center; transition: 0.2s; z-index: 100; }
.modal-close:hover { background: #ff4444; color: #fff; box-shadow: 0 0 10px #ff4444; }

/* MY APPS & DATABASE GRID */
.apps-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(160px, 1fr)); gap: 10px; margin-top: 15px; }
@media (max-width: 480px) { .apps-grid { grid-template-columns: repeat(2, 1fr); } }
.app-card { background: rgba(0, 30, 60, 0.5); border: 1px solid rgba(0, 255, 255, 0.2); border-radius: 8px; padding: 14px 10px; text-align: center; text-decoration: none; color: #fff; transition: all 0.25s; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 8px; min-height: 110px; position: relative; }
.app-card:hover { border-color: var(--cyan); background: rgba(0, 255, 255, 0.15); transform: translateY(-4px); box-shadow: var(--glow); }
.app-card i { font-size: 26px; color: var(--cyan); }
.app-card span { font-size: 12px; font-family: 'Orbitron'; font-weight: 600; line-height: 1.3; }
.app-actions { display: flex; gap: 4px; position: absolute; top: 4px; right: 4px; opacity: 0; transition: 0.2s; }
.app-card:hover .app-actions { opacity: 1; }
.btn-mini { background: rgba(0,0,0,0.8); border: 1px solid var(--cyan); color: var(--cyan); width: 22px; height: 22px; border-radius: 4px; font-size: 10px; cursor: pointer; display: flex; align-items: center; justify-content: center; }
.btn-mini:hover { background: var(--cyan); color: #000; }

/* CREDIT & MOTTO MODAL STYLE */
.credit-content { display: flex; flex-direction: column; align-items: center; text-align: center; gap: 16px; padding: 10px; }
.credit-robot-wrap { width: 140px; height: 140px; position: relative; margin: 0 auto; cursor: pointer; }
.quote-box { background: rgba(0, 255, 255, 0.05); border-left: 3px solid var(--cyan); padding: 14px 18px; border-radius: 4px; font-size: 15px; font-style: italic; color: #d0f0ff; max-width: 680px; line-height: 1.6; animation: color-shift 6s infinite; }
.social-links { display: flex; gap: 12px; flex-wrap: wrap; justify-content: center; margin-top: 10px; }
.soc-btn { padding: 10px 18px; border-radius: 6px; text-decoration: none; font-family: 'Orbitron'; font-size: 12px; font-weight: bold; display: inline-flex; align-items: center; gap: 8px; transition: 0.2s; }
.soc-fb { background: rgba(24, 119, 242, 0.2); border: 1px solid #1877f2; color: #58a5ff; }
.soc-fb:hover { background: #1877f2; color: #fff; box-shadow: 0 0 15px #1877f2; }
.soc-wa { background: rgba(37, 211, 102, 0.2); border: 1px solid #25d366; color: #5df894; }
.soc-wa:hover { background: #25d366; color: #fff; box-shadow: 0 0 15px #25d366; }
.soc-blog { background: rgba(255, 153, 0, 0.2); border: 1px solid #ff9900; color: #ffba4d; }
.soc-blog:hover { background: #ff9900; color: #fff; box-shadow: 0 0 15px #ff9900; }

/* SETTINGS & HELP TABLE */
.setting-row { display: flex; justify-content: space-between; align-items: center; padding: 12px 0; border-bottom: 1px solid rgba(0, 255, 255, 0.1); flex-wrap: wrap; gap: 10px; }
.setting-select, .setting-input { background: rgba(0, 10, 20, 0.9); border: var(--border); color: var(--cyan); padding: 8px 12px; border-radius: 6px; font-family: 'Orbitron'; font-size: 12px; outline: none; }
.help-table { width: 100%; border-collapse: collapse; margin-top: 10px; font-size: 12px; }
.help-table th, .help-table td { border: 1px solid rgba(0,255,255,0.2); padding: 8px 10px; text-align: left; }
.help-table th { background: rgba(0, 255, 255, 0.1); color: var(--cyan); font-family: 'Orbitron'; }
.help-table tr:nth-child(even) { background: rgba(0, 20, 40, 0.3); }
</style>
</head>
<body>

<div id="custom-tooltip"></div>

<div class="scan-line"></div>
<div class="corner c-tl"></div><div class="corner c-tr"></div>
<div class="corner c-bl"></div><div class="corner c-br"></div>

<div id="boot-screen">
  <div class="boot-avatar">
    <svg viewBox="0 0 100 100" style="width:100%; height:100%;" xmlns="http://www.w3.org/2000/svg">
        <g class="ear-left"><polygon points="25,45 10,10 45,30" fill="#f8fafc" stroke="#06b6d4" stroke-width="2"/><polygon points="25,38 16,18 38,30" fill="#f472b6"/></g>
        <g class="ear-right"><polygon points="75,45 90,10 55,30" fill="#f8fafc" stroke="#06b6d4" stroke-width="2"/><polygon points="75,38 84,18 62,30" fill="#f472b6"/></g>
        <circle cx="50" cy="55" r="38" fill="#f8fafc" stroke="#06b6d4" stroke-width="2.5"/>
        <path d="M 14 42 Q 50 25 86 42" fill="none" stroke="#334155" stroke-width="6" stroke-linecap="round"/>
        <circle cx="50" cy="33" r="12" fill="#cbd5e1" stroke="#06b6d4" stroke-width="2"/><circle cx="50" cy="33" r="4" fill="#020617"/><circle cx="44" cy="27" r="2" fill="#ffffff"/> 
        <g class="eye-left"><ellipse cx="35" cy="50" rx="5" ry="7" fill="#020617"/><circle cx="33" cy="48" r="2" fill="#ffffff"/><path d="M 28 45 Q 35 40 42 45" fill="none" stroke="#020617" stroke-width="1.5" stroke-linecap="round"/></g>
        <g class="eye-right"><ellipse cx="65" cy="50" rx="5" ry="7" fill="#020617"/><circle cx="63" cy="48" r="2" fill="#ffffff"/><path d="M 58 45 Q 65 40 72 45" fill="none" stroke="#020617" stroke-width="1.5" stroke-linecap="round"/></g>
        <ellipse cx="25" cy="62" rx="7" ry="4" fill="#f472b6" opacity="0.7"/><ellipse cx="75" cy="62" rx="7" ry="4" fill="#f472b6" opacity="0.7"/>
        <polygon points="47,60 53,60 50,64" fill="#f472b6"/>
        <path d="M 38 65 Q 44 72 50 66 Q 56 72 62 65" fill="none" stroke="#020617" stroke-width="2" stroke-linecap="round" id="boot-mouth"/>
    </svg>
  </div>
  <div class="boot-title orbitron text-glow">J.A.R.V.I.S CYBER CAT</div>
  <div class="boot-status mono" id="boot-step-text">INITIALIZING 3D CAT SUPERAGENT...</div>
  <div class="boot-bar-wrap"><div class="boot-bar-fill" id="boot-progress"></div></div>
  <div class="orbitron" style="font-size: 14px;" id="boot-percent">0%</div>
</div>

<div id="screensaver" onclick="stopScreensaver()">
  <div style="flex:1; display:flex; flex-direction:column; justify-content:center; align-items:center; width:100%;">
      <div class="atom-orbit-container" style="position:relative; width:200px; height:200px; margin-top:20px;">
        <div class="orbit-ring-3d ring-1"><div class="electron"></div></div>
        <div class="orbit-ring-3d ring-2"><div class="electron"></div></div>
        <div class="orbit-ring-3d ring-3"><div class="electron amber"></div></div>
        
        <div style="width:120px; height:120px; filter:drop-shadow(0 0 20px rgba(6,182,212,0.6)); position:absolute; z-index:10;">
          <svg viewBox="0 0 100 100" style="width:100%; height:100%;" xmlns="http://www.w3.org/2000/svg">
              <g class="ear-left"><polygon points="25,45 10,10 45,30" fill="#f8fafc" stroke="#06b6d4" stroke-width="2"/><polygon points="25,38 16,18 38,30" fill="#f472b6"/></g>
              <g class="ear-right"><polygon points="75,45 90,10 55,30" fill="#f8fafc" stroke="#06b6d4" stroke-width="2"/><polygon points="75,38 84,18 62,30" fill="#f472b6"/></g>
              <circle cx="50" cy="55" r="38" fill="#f8fafc" stroke="#06b6d4" stroke-width="2.5"/>
              <path d="M 14 42 Q 50 25 86 42" fill="none" stroke="#334155" stroke-width="6" stroke-linecap="round"/>
              <circle cx="50" cy="33" r="12" fill="#cbd5e1" stroke="#06b6d4" stroke-width="2"/><circle cx="50" cy="33" r="4" fill="#020617"/><circle cx="44" cy="27" r="2" fill="#ffffff"/> 
              <g class="eye-left"><ellipse cx="35" cy="50" rx="5" ry="7" fill="#020617"/><circle cx="33" cy="48" r="2" fill="#ffffff"/><path d="M 28 45 Q 35 40 42 45" fill="none" stroke="#020617" stroke-width="1.5" stroke-linecap="round"/></g>
              <g class="eye-right"><ellipse cx="65" cy="50" rx="5" ry="7" fill="#020617"/><circle cx="63" cy="48" r="2" fill="#ffffff"/><path d="M 58 45 Q 65 40 72 45" fill="none" stroke="#020617" stroke-width="1.5" stroke-linecap="round"/></g>
              <ellipse cx="25" cy="62" rx="7" ry="4" fill="#f472b6" opacity="0.7"/><ellipse cx="75" cy="62" rx="7" ry="4" fill="#f472b6" opacity="0.7"/>
              <polygon points="47,60 53,60 50,64" fill="#f472b6"/>
              <path d="M 38 65 Q 44 72 50 66 Q 56 72 62 65" fill="none" stroke="#020617" stroke-width="2" stroke-linecap="round" id="ss-mouth"/>
          </svg>
        </div>
      </div>
  </div>

  <div style="flex:1; display:flex; flex-direction:column; justify-content:center; align-items:center; width:100%;">
      <div class="ss-time orbitron" id="ss-clock">00:00:00</div>
      <div class="ss-date orbitron" id="ss-date">SENIN, 01 JAN 2026</div>
      <div class="main-quote-box" id="ss-quote-box" style="max-width: 600px; margin: 15px auto;">"Teknologi sejati adalah yang memberi manfaat bagi kemanusiaan."</div>
  </div>

  <div class="ss-hint orbitron" style="margin-top:20px;">TAP OR CLICK ANYWHERE TO RESUME HUD</div>
</div>

<div id="main-hud">
  
  <header class="header-bar">
    <div class="header-title orbitron text-glow" data-tip="Just A Rather Very Intelligent System - Cyber Cat Edition">
      <i class="fa-solid fa-cat fa-bounce" style="--fa-animation-duration: 3s; color: var(--pink);"></i>
      J.A.R.V.I.S <span style="font-size: 11px; color: rgba(0,255,255,0.6); font-family: 'Rajdhani';">v6.0 PRO CAT</span>
    </div>
    <div class="header-controls">
      <div class="orbitron mono" style="background: rgba(0,255,255,0.1); padding: 6px 12px; border-radius: 6px; border: var(--border);" id="live-clock-top">00:00:00</div>
      <button class="btn-hud" onclick="openModal('db-modal'); renderDatabase();" data-tip="Kelola Database 28+ Aplikasi Web">
        <i class="fa-solid fa-database"></i> DATABASE
      </button>
      <button class="btn-hud" onclick="openModal('apps-modal'); renderMyApps();" data-tip="Buka Daftar Aplikasi Web">
        <i class="fa-solid fa-grid-2"></i> MY APPS
      </button>
      <button class="btn-hud" onclick="openModal('ss-settings-modal')" data-tip="Pengaturan Screensaver & Waktu">
        <i class="fa-solid fa-desktop"></i> SETTING SS
      </button>
      <button class="btn-hud" onclick="openModal('credit-modal'); triggerCreditVoice();" data-tip="Informasi Kreator & Motto Bijak">
        <i class="fa-solid fa-user-astronaut"></i> KREDIT
      </button>
      <button class="btn-hud" style="border-color: var(--pink); color: #fff; background: rgba(255,0,127,0.2);" onclick="openModal('help-modal')" data-tip="Panduan Fitur & Cara Penggunaan J.A.R.V.I.S">
        <i class="fa-solid fa-circle-question"></i> HELP
      </button>
    </div>
  </header>

  <div class="hud-grid">
    
    <div class="panel">
      <div class="panel-title"><span><i class="fa-solid fa-bolt"></i> QUICK ACTIONS</span> <span>SYS_01</span></div>
      <div class="quick-action-list">
        <a href="https://adikds.github.io/GEOSTRUCT-PRO-20-FORMULA-GEOTECHNICAL/" target="_blank" class="action-item" onclick="quickAction('Opening GeoStruct Pro 20 Geotechnical Formulas...')" data-tip="Kalkulasi 20 Rumus Geoteknik & Bendungan">
          <div class="action-icon" style="color: #00ffaa;"><i class="fa-solid fa-calculator"></i></div>
          <div><div class="orbitron" style="font-size: 13px;">Geo-Struct Calc</div><div style="font-size: 11px; color: rgba(0,255,255,0.5);">20 Geotechnical Formulas</div></div>
        </a>
        <a href="https://adikds.github.io/SISTEM-MONITORING-SEISMIK-PERINGATAN-TSUNAMI/" target="_blank" class="action-item" onclick="quickAction('Opening Monitoring Sismic Tsunami Alert System...')" data-tip="Sistem Monitoring Gempa & Peringatan Tsunami">
          <div class="action-icon" style="color: #ffaa00;"><i class="fa-solid fa-wave-square"></i></div>
          <div><div class="orbitron" style="font-size: 13px;">Monitoring Sismic</div><div style="font-size: 11px; color: rgba(0,255,255,0.5);">Tsunami Early Warning</div></div>
        </a>
        <a href="https://prompts.chat/" target="_blank" class="action-item" onclick="quickAction('Opening ChatGPT Prompt Generator portal...')" data-tip="Generator & Koleksi Prompt AI Terbaik">
          <div class="action-icon" style="color: #ff007f;"><i class="fa-solid fa-wand-magic-sparkles"></i></div>
          <div><div class="orbitron" style="font-size: 13px;">Prompt Generator</div><div style="font-size: 11px; color: rgba(0,255,255,0.5);">Awesome AI Prompts</div></div>
        </a>
        <a href="https://adikds.github.io/MONITORING-PREDIKSI-ANGIN-MUSON-INDONESIA/" target="_blank" class="action-item" onclick="quickAction('Opening Weather & Monsoon Prediction System...')" data-tip="Monitoring Prediksi Angin Muson & Cuaca Indonesia">
          <div class="action-icon" style="color: #00ffff;"><i class="fa-solid fa-cloud-sun-rain"></i></div>
          <div><div class="orbitron" style="font-size: 13px;">Monitoring Cuaca</div><div style="font-size: 11px; color: rgba(0,255,255,0.5);">Prediksi Angin Muson ID</div></div>
        </a>
        <a href="https://www.f15library.com/" target="_blank" class="action-item" onclick="quickAction('Opening Perpustakaan (F15 Library)...')" data-tip="Membuka F15 Library Digital">
          <div class="action-icon" style="color: #ff00ff;"><i class="fa-solid fa-book-open-reader"></i></div>
          <div><div class="orbitron" style="font-size: 13px;">Perpustakaan</div><div style="font-size: 11px; color: rgba(0,255,255,0.5);">F15 Library Digital</div></div>
        </a>
      </div>

      <div class="panel-title" style="margin-top: 10px;"><span><i class="fa-solid fa-microchip"></i> SYSTEM METRICS</span></div>
      <div style="display: flex; flex-direction: column; gap: 6px; font-size: 11px; font-family: 'Orbitron';">
        <div>CPU LOAD <span style="float: right; color: #00ffaa;" id="cpu-val">34%</span></div>
        <div style="width:100%; height:4px; background:rgba(0,255,255,0.1);"><div id="cpu-bar" style="width:34%; height:100%; background:#00ffaa; box-shadow: 0 0 8px #00ffaa;"></div></div>
        <div>MEMORY <span style="float: right; color: var(--cyan);" id="ram-val">62%</span></div>
        <div style="width:100%; height:4px; background:rgba(0,255,255,0.1);"><div id="ram-bar" style="width:62%; height:100%; background:var(--cyan); box-shadow: var(--glow);"></div></div>
      </div>
    </div>

    <div class="panel" style="align-items: center; justify-content: space-between;">
      <div class="panel-title" style="width: 100%;"><span><i class="fa-solid fa-crosshairs"></i> 3D ATOMIC CORE & CYBER CAT</span> <span class="mono">ONLINE</span></div>
      
      <div class="center-stage">
        <div class="center-clock-wrap" onclick="openModal('ss-settings-modal')" data-tip="Klik untuk membuka Pengaturan Screensaver">
          <div class="center-time orbitron" id="center-clock-text">00:00:00</div>
          <div class="center-day orbitron" id="center-date-text">SENIN, 01 JAN 2026</div>
        </div>

        <div class="radar-ring r1"></div>
        <div class="radar-ring r2"></div>
        
        <div class="atom-orbit-container">
          <div class="orbit-ring-3d ring-1"><div class="electron"></div></div>
          <div class="orbit-ring-3d ring-2"><div class="electron"></div></div>
          <div class="orbit-ring-3d ring-3"><div class="electron amber"></div></div>
        </div>
        
        <div class="cat-avatar-wrap" onclick="speakJarvis('Meow! Halo Sir, saya J.A.R.V.I.S Cyber Cat. Seluruh sistem 3D orbit dan database aplikasi berjalan optimal. Ketik buka aplikasi pada prompt di bawah untuk bantuan.')" data-tip="Klik untuk Interaksi Suara Kucing J.A.R.V.I.S">
          <svg viewBox="0 0 100 100" style="width:100%; height:100%;" xmlns="http://www.w3.org/2000/svg">
              <g class="ear-left"><polygon points="25,45 10,10 45,30" fill="#f8fafc" stroke="#06b6d4" stroke-width="2"/><polygon points="25,38 16,18 38,30" fill="#f472b6"/></g>
              <g class="ear-right"><polygon points="75,45 90,10 55,30" fill="#f8fafc" stroke="#06b6d4" stroke-width="2"/><polygon points="75,38 84,18 62,30" fill="#f472b6"/></g>
              <circle cx="50" cy="55" r="38" fill="#f8fafc" stroke="#06b6d4" stroke-width="2.5"/>
              <path d="M 14 42 Q 50 25 86 42" fill="none" stroke="#334155" stroke-width="6" stroke-linecap="round"/>
              <circle cx="50" cy="33" r="12" fill="#cbd5e1" stroke="#06b6d4" stroke-width="2"/><circle cx="50" cy="33" r="4" fill="#020617"/><circle cx="44" cy="27" r="2" fill="#ffffff"/> 
              <g class="eye-left"><ellipse cx="35" cy="50" rx="5" ry="7" fill="#020617"/><circle cx="33" cy="48" r="2" fill="#ffffff"/><path d="M 28 45 Q 35 40 42 45" fill="none" stroke="#020617" stroke-width="1.5" stroke-linecap="round"/></g>
              <g class="eye-right"><ellipse cx="65" cy="50" rx="5" ry="7" fill="#020617"/><circle cx="63" cy="48" r="2" fill="#ffffff"/><path d="M 58 45 Q 65 40 72 45" fill="none" stroke="#020617" stroke-width="1.5" stroke-linecap="round"/></g>
              <ellipse cx="25" cy="62" rx="7" ry="4" fill="#f472b6" opacity="0.7"/><ellipse cx="75" cy="62" rx="7" ry="4" fill="#f472b6" opacity="0.7"/>
              <polygon points="47,60 53,60 50,64" fill="#f472b6"/>
              <path d="M 38 65 Q 44 72 50 66 Q 56 72 62 65" fill="none" stroke="#020617" stroke-width="2" stroke-linecap="round" id="hud-mouth"/>
          </svg>
        </div>

        <div class="visualizer-box" id="audio-vis">
          <div class="vis-bar"></div><div class="vis-bar"></div><div class="vis-bar"></div>
          <div class="vis-bar"></div><div class="vis-bar"></div><div class="vis-bar"></div>
          <div class="vis-bar"></div><div class="vis-bar"></div><div class="vis-bar"></div>
        </div>

        <div class="main-quote-box" id="hud-quote-box" onclick="readCurrentQuote()" data-tip="Klik untuk mendengarkan J.A.R.V.I.S membaca motto ini">
          "Teknologi sejati bukan hanya tentang algoritma, melainkan manfaat bagi kemanusiaan."
        </div>
      </div>

      <div class="command-box">
        <input type="text" class="cmd-input" id="cmd-input" placeholder="Ketik perintah panduan: 'perpustakaan', 'buka quran'..." onkeypress="if(event.key==='Enter') sendCommand()">
        <button class="mic-btn" id="mic-btn" onclick="toggleVoice()" data-tip="Perintah Suara (Voice Command)"><i class="fa-solid fa-microphone"></i></button>
      </div>
    </div>

    <div class="panel">
      <div class="panel-title"><span><i class="fa-solid fa-list-check"></i> ACTIVITY LOG</span> <span class="mono">LIVE</span></div>
      <div class="log-container mono" id="log-box">
        <div class="log-entry"><span class="log-time">[SYS]</span> <span class="log-text sys">Cyber Cat 3D Core initialized. Welcome Mohamad Hartadi.</span></div>
        <div class="log-entry"><span class="log-time">[SEC]</span> <span class="log-text sys">No Password mode active. Direct access granted.</span></div>
        <div class="log-entry"><span class="log-time">[AI]</span> <span class="log-text user">Smart NLP Ready. Ketik 'buka' pada prompt untuk panduan.</span></div>
      </div>
      <div style="display: flex; gap: 6px; margin-top: 5px;">
        <button class="btn-hud" style="flex: 1; justify-content: center; font-size: 10px;" onclick="addLog('System diagnostics nominal. 28+ apps linked in Database.', 'sys')">DIAGNOSTICS</button>
        <button class="btn-hud" style="flex: 1; justify-content: center; font-size: 10px;" onclick="document.getElementById('log-box').innerHTML=''">CLEAR LOG</button>
      </div>
    </div>

  </div>

  <footer class="footer-bar">
    <div class="dev-info">
      <i class="fa-solid fa-laptop-code dev-icon"></i>
      <div>
        <div class="orbitron" style="font-size: 13px; font-weight: bold; color: #fff;">MOHAMAD HARTADI (ADI)</div>
        <div style="font-size: 11px; color: rgba(0,255,255,0.6);">Civil Engineer | Software Engineer | Prompt Engineering Specialist</div>
      </div>
    </div>
    <div style="display: flex; gap: 10px; align-items: center; flex-wrap: wrap;">
      <span class="mono" style="font-size: 12px; color: #00ffaa;"><i class="fa-solid fa-circle fa-fade"></i> SERVER: CONNECTED</span>
      <button class="btn-hud" onclick="openModal('db-modal'); renderDatabase();" style="padding: 6px 12px;"><i class="fa-solid fa-database"></i> DATABASE APPS</button>
      <button class="btn-hud" onclick="openModal('credit-modal'); triggerCreditVoice();" style="padding: 6px 12px;"><i class="fa-solid fa-address-card"></i> PROFIL & MOTTO</button>
    </div>
  </footer>

</div>

<div class="modal-overlay" id="apps-modal" onclick="closeModalOutside(event, 'apps-modal')">
  <div class="modal-box">
    <button class="modal-close" onclick="closeModal('apps-modal')">&times;</button>
    <div style="display:flex; justify-content:space-between; align-items:center; flex-wrap:wrap; gap:10px; margin-bottom:5px;">
      <h2 class="orbitron text-glow" style="font-size: 18px;"><i class="fa-solid fa-grid-2"></i> MY APPLICATION ECOSYSTEM</h2>
      <button class="btn-hud" onclick="closeModal('apps-modal'); openModal('db-modal'); renderDatabase();" style="background: rgba(0,255,100,0.2); border-color:#00ffaa;"><i class="fa-solid fa-plus"></i> TAMBAH / EDIT APPS</button>
    </div>
    <p style="font-size: 13px; color: rgba(0,255,255,0.6);">Daftar aplikasi web berkinerja tinggi yang tersinkronisasi dengan Database J.A.R.V.I.S:</p>
    <div class="apps-grid" id="apps-grid-container"></div>
  </div>
</div>

<div class="modal-overlay" id="db-modal" onclick="closeModalOutside(event, 'db-modal')">
  <div class="modal-box">
    <button class="modal-close" onclick="closeModal('db-modal')">&times;</button>
    <h2 class="orbitron text-glow" style="font-size: 18px; margin-bottom: 5px;"><i class="fa-solid fa-database"></i> DATABASE APLIKASI WEB</h2>
    <p style="font-size: 13px; color: rgba(0,255,255,0.6); margin-bottom: 15px;">Kelola daftar aplikasi Anda. Data di sini langsung sinkron ke antarmuka <i>My Apps</i> dan sistem Command NLP.</p>
    
    <div style="background:rgba(0,10,20,0.8); border:1px solid var(--cyan); padding:12px; border-radius:8px; margin-bottom:15px;">
      <div class="orbitron" style="font-size:12px; color:#00ffaa; margin-bottom:8px;" id="form-db-title">TAMBAH APLIKASI BARU</div>
      <input type="hidden" id="db-edit-idx" value="-1">
      <div style="display:grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap:8px; margin-bottom:10px;">
        <input type="text" id="db-name" class="setting-input" placeholder="Nama Aplikasi (misal: AI Dokter)">
        <input type="text" id="db-url" class="setting-input" placeholder="URL Link (https://...)">
        <input type="text" id="db-desc" class="setting-input" placeholder="Deskripsi Singkat">
        <input type="text" id="db-icon" class="setting-input" placeholder="Icon FA (misal: fa-robot)" value="fa-globe">
      </div>
      <div style="display:flex; gap:8px;">
        <button class="btn-hud" style="background:rgba(0,255,100,0.3); border-color:#00ffaa; flex:1; justify-content:center;" onclick="saveAppToDb()"><i class="fa-solid fa-save"></i> SIMPAN / SINKRON KAN</button>
        <button class="btn-hud" style="background:rgba(255,50,50,0.2); border-color:#ff4444; display:none;" id="btn-cancel-db" onclick="resetDbForm()"><i class="fa-solid fa-times"></i> BATAL</button>
      </div>
    </div>

    <div style="overflow-x:auto;">
      <table class="help-table" id="db-table">
        <thead>
          <tr><th>No</th><th>Nama Aplikasi</th><th>Deskripsi</th><th>URL Link</th><th>Aksi</th></tr>
        </thead>
        <tbody id="db-table-body"></tbody>
      </table>
    </div>
  </div>
</div>

<div class="modal-overlay" id="credit-modal" onclick="closeModalOutside(event, 'credit-modal')">
  <div class="modal-box" style="max-width: 720px;">
    <button class="modal-close" onclick="closeModal('credit-modal')">&times;</button>
    
    <div class="credit-content">
      <div class="orbitron" style="font-size: 12px; color: #00ffaa; letter-spacing: 3px;">LEAD ARCHITECT & DEVELOPER</div>
      <h2 class="orbitron text-glow" style="font-size: 24px; color: #fff;">MOHAMAD HARTADI (ADI)</h2>
      
      <div class="orbitron mono" style="background: rgba(0,255,255,0.1); padding: 4px 16px; border-radius: 20px; font-size: 13px; border: var(--border);" id="credit-clock-display">
        SENIN, 01 JAN 2026 | 00:00:00
      </div>

      <div class="credit-robot-wrap" onclick="triggerCreditVoice()" data-tip="Klik untuk mendengarkan sambutan & motto dari J.A.R.V.I.S">
        <div class="orbit-ring-3d ring-1" style="width:100%; height:100%;"><div class="electron"></div></div>
        <svg viewBox="0 0 100 100" style="width:100%; height:100%; filter: drop-shadow(0 0 15px var(--cyan));" xmlns="http://www.w3.org/2000/svg">
            <g class="ear-left"><polygon points="25,45 10,10 45,30" fill="#f8fafc" stroke="#06b6d4" stroke-width="2"/><polygon points="25,38 16,18 38,30" fill="#f472b6"/></g>
            <g class="ear-right"><polygon points="75,45 90,10 55,30" fill="#f8fafc" stroke="#06b6d4" stroke-width="2"/><polygon points="75,38 84,18 62,30" fill="#f472b6"/></g>
            <circle cx="50" cy="55" r="38" fill="#f8fafc" stroke="#06b6d4" stroke-width="2.5"/>
            <path d="M 14 42 Q 50 25 86 42" fill="none" stroke="#334155" stroke-width="6" stroke-linecap="round"/>
            <circle cx="50" cy="33" r="12" fill="#cbd5e1" stroke="#06b6d4" stroke-width="2"/><circle cx="50" cy="33" r="4" fill="#020617"/><circle cx="44" cy="27" r="2" fill="#ffffff"/> 
            <g class="eye-left"><ellipse cx="35" cy="50" rx="5" ry="7" fill="#020617"/><circle cx="33" cy="48" r="2" fill="#ffffff"/><path d="M 28 45 Q 35 40 42 45" fill="none" stroke="#020617" stroke-width="1.5" stroke-linecap="round"/></g>
            <g class="eye-right"><ellipse cx="65" cy="50" rx="5" ry="7" fill="#020617"/><circle cx="63" cy="48" r="2" fill="#ffffff"/><path d="M 58 45 Q 65 40 72 45" fill="none" stroke="#020617" stroke-width="1.5" stroke-linecap="round"/></g>
            <ellipse cx="25" cy="62" rx="7" ry="4" fill="#f472b6" opacity="0.7"/><ellipse cx="75" cy="62" rx="7" ry="4" fill="#f472b6" opacity="0.7"/>
            <polygon points="47,60 53,60 50,64" fill="#f472b6"/>
            <path d="M 38 65 Q 44 72 50 66 Q 56 72 62 65" fill="none" stroke="#020617" stroke-width="2" stroke-linecap="round" id="credit-mouth"/>
        </svg>
      </div>

      <div class="quote-box" id="credit-quote-box" onclick="readCurrentQuote()" style="cursor:pointer;" data-tip="Klik untuk membaca audio kata bijak ini">
        "Teknologi sejati bukan hanya tentang kecerdasan buatan, melainkan tentang bagaimana kita memanfaatkannya untuk memitigasi bencana dan memberi manfaat tak terbatas bagi kemanusiaan."
      </div>
      <div style="font-size:11px; color:var(--pink); font-family:'Orbitron';">✨ Kata bijak berganti otomatis setiap 8 detik. Klik kotak di atas untuk membaca suara. ✨</div>

      <div style="width:100%; background:rgba(0,15,30,0.8); border:1px solid rgba(0,255,255,0.3); padding:12px; border-radius:8px; margin-top:5px; text-align:left;">
        <div class="orbitron" style="font-size:11px; color:#00ffaa; margin-bottom:6px;"><i class="fa-solid fa-pen-to-square"></i> TAMBAH / EDIT KATA BIJAK & MOTTO:</div>
        <div style="display:flex; gap:8px; flex-wrap:wrap;">
          <input type="text" id="new-quote-input" class="setting-input" style="flex:1; min-width:200px;" placeholder="Tulis kata bijak / motto baru di sini...">
          <button class="btn-hud" style="background:rgba(0,255,100,0.2); border-color:#00ffaa;" onclick="addNewQuote()"><i class="fa-solid fa-plus"></i> TAMBAH</button>
        </div>
        <div style="max-height:100px; overflow-y:auto; margin-top:8px; font-size:11px; display:flex; flex-direction:column; gap:4px;" id="quotes-list-container"></div>
      </div>

      <div style="font-family: 'Orbitron'; font-size: 11px; color: rgba(0,255,255,0.6); margin-top: 10px;">TERHUBUNG DENGAN PROGRAMMER:</div>
      <div class="social-links">
        <a href="https://www.facebook.com/m.hartadi" target="_blank" class="soc-btn soc-fb" data-tip="Kunjungi Profil Facebook M. Hartadi"><i class="fa-brands fa-facebook-f"></i> FACEBOOK</a>
        <a href="https://newbieonline7.blogspot.com/" target="_blank" class="soc-btn soc-blog" data-tip="Baca Artikel di Blog NewbieOnline7"><i class="fa-solid fa-globe"></i> BLOG NEWBIE</a>
        <a href="https://wa.me/6282231036047" target="_blank" class="soc-btn soc-wa" data-tip="Chat Langsung via WhatsApp"><i class="fa-brands fa-whatsapp"></i> WHATSAPP</a>
      </div>
    </div>

  </div>
</div>

<div class="modal-overlay" id="ss-settings-modal" onclick="closeModalOutside(event, 'ss-settings-modal')">
  <div class="modal-box" style="max-width: 500px;">
    <button class="modal-close" onclick="closeModal('ss-settings-modal')">&times;</button>
    <h2 class="orbitron text-glow" style="font-size: 16px; margin-bottom: 15px;"><i class="fa-solid fa-desktop"></i> PENGATURAN SCREENSAVER & WAKTU</h2>
    
    <div class="setting-row">
      <span>Waktu Otomatis Aktif (Idle):</span>
      <select class="setting-select" id="ss-timer-select" onchange="updateScreensaverTimer()">
        <option value="60">1 Menit</option>
        <option value="180" selected>3 Menit</option>
        <option value="300">5 Menit</option>
        <option value="0">Never (Nonaktif)</option>
      </select>
    </div>
    
    <div class="setting-row">
      <span>Suara Kucing di Screensaver:</span>
      <select class="setting-select" id="ss-voice-select">
        <option value="yes">Aktif (Berbicara & Membaca Quote)</option>
        <option value="no">Senyap (Mute)</option>
      </select>
    </div>

    <div class="setting-row">
      <span>Audio Baca Motto Otomatis di Dasbor:</span>
      <select class="setting-select" id="quote-auto-read">
        <option value="yes">Aktif (Bicara Tiap Ganti)</option>
        <option value="no" selected>Klik Manual (Hemat Audio)</option>
      </select>
    </div>

    <div style="display: flex; gap: 10px; margin-top: 20px; flex-wrap:wrap;">
      <button class="btn-hud" style="flex: 1; justify-content: center; background: rgba(0, 255, 100, 0.2); border-color: #00ffaa;" onclick="saveScreensaverSettings()">
        <i class="fa-solid fa-check"></i> SAVE SETTINGS
      </button>
      <button class="btn-hud" style="flex: 1; justify-content: center; background: rgba(0, 150, 255, 0.3);" onclick="testScreensaver()">
        <i class="fa-solid fa-play"></i> COBA SCREENSAVER
      </button>
    </div>
  </div>
</div>

<div class="modal-overlay" id="help-modal" onclick="closeModalOutside(event, 'help-modal')">
  <div class="modal-box" style="max-width: 850px;">
    <button class="modal-close" onclick="closeModal('help-modal')">&times;</button>
    <h2 class="orbitron text-glow" style="font-size: 18px; margin-bottom: 5px;"><i class="fa-solid fa-circle-question"></i> HELP SYSTEM & FITUR METRIK J.A.R.V.I.S</h2>
    <p style="font-size: 13px; color: rgba(0,255,255,0.6); margin-bottom: 15px;">Panduan lengkap spesifikasi antarmuka Cyber Cat Superagent HUD v6.0 karya Mohamad Hartadi:</p>
    
    <div style="overflow-x:auto;">
      <table class="help-table">
        <thead>
          <tr><th>Fitur / Panel</th><th>Fungsi & Kegunaan Utama</th><th>Cara Penggunaan / Interaksi</th></tr>
        </thead>
        <tbody>
          <tr>
            <td class="orbitron" style="color:#ff007f;">Cyber Cat Avatar</td>
            <td>Avatar 3D dengan animasi mata berkedip, telinga bergoyang, dan mulut sinkron audio.</td>
            <td>Klik pada avatar kucing di center stage atau screensaver untuk mendengarkan sapaan suara AI.</td>
          </tr>
          <tr>
            <td class="orbitron" style="color:#00ffaa;">Dynamic Quotes & Voice</td>
            <td>Menampilkan motto & kata bijak bergulir dengan animasi warna menarik serta pembacaan teks ke suara.</td>
            <td>Klik kotak motto di dasbor/kredit untuk mendengarkan audio. Masuk ke menu Kredit untuk tambah/edit motto.</td>
          </tr>
          <tr>
            <td class="orbitron" style="color:#00ffff;">28+ Apps Database</td>
            <td>Manajemen seluruh portofolio aplikasi web terintegrasi dengan fitur sinkronisasi live.</td>
            <td>Klik tombol DATABASE di atas untuk menambah atau mengedit URL link aplikasi. Otomatis sinkron ke menu My Apps.</td>
          </tr>
          <tr>
            <td class="orbitron" style="color:#f59e0b;">Smart NLP Command</td>
            <td>Pusat komando teks dan suara interaktif terintegrasi pada panel Terminal Log.</td>
            <td>Ketik "buka" atau "aplikasi" di prompt bawah untuk panduan otomatis, lalu Enter.</td>
          </tr>
          <tr>
            <td class="orbitron" style="color:#0088ff;">Interactive Clock</td>
            <td>Menampilkan waktu realtime WIB dan tanggal lengkap dengan efek warna bercahaya.</td>
            <td>Klik kotak jam di Dashboard Center untuk langsung membuka konfigurasi screensaver.</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div style="margin-top:15px; text-align:right;">
      <button class="btn-hud" onclick="closeModal('help-modal')" style="background:rgba(0,255,255,0.2);"><i class="fa-solid fa-check"></i> MENGERTI & TUTUP</button>
    </div>
  </div>
</div>

<script>
/* 1. DATABASE APLIKASI WEB (SINKRONISASI LIVE) */
let myApps = [
  { n: "JARVIS AI", u: "https://adikds.github.io/jarvis-ai/", i: "fa-cat", d: "Superagent HUD" },
  { n: "EduMarket Pro", u: "https://adikds.github.io/edu-market-pro/", i: "fa-graduation-cap", d: "E-Learning Market" },
  { n: "IPTV Terminal", u: "https://adikds.github.io/iptv-terminal/", i: "fa-tv", d: "Streaming TV ID" },
  { n: "TV Streaming Live", u: "https://adikds.github.io/TV-streaming-live/", i: "fa-signal", d: "Live Broadcast" },
  { n: "Al-Quran Karim", u: "https://adikds.github.io/Al-Quran-Karim/", i: "fa-book-quran", d: "Digital Quran" },
  { n: "Mega Atlas FKG", u: "https://adikds.github.io/-MEGA-ATLAS-FKG/", i: "fa-tooth", d: "Dental Atlas" },
  { n: "Monitoring Sismic", u: "https://adikds.github.io/SISTEM-MONITORING-SEISMIK-PERINGATAN-TSUNAMI/", i: "fa-wave-square", d: "Tsunami Warning" },
  { n: "El Nino La Nina", u: "https://adikds.github.io/MONITORING-PREDIKSI-STATUS-EI-NI-O-LA-NI-A/", i: "fa-temperature-half", d: "Climate Predict" },
  { n: "Monitoring Cuaca", u: "https://adikds.github.io/MONITORING-PREDIKSI-ANGIN-MUSON-INDONESIA/", i: "fa-wind", d: "Monsoon Predict" },
  { n: "Dam Analytics", u: "https://adikds.github.io/INTEGRATED-DAM-ANALYTICS-ASSESSMENT-SYSTEM/", i: "fa-water", d: "Dam Assessment" },
  { n: "Way Apu Dam", u: "https://adikds.github.io/WAY-APU-DAM/", i: "fa-building-shield", d: "Dam Analysis" },
  { n: "EDA AI Agents", u: "https://adikds.github.io/EVENT-DRIVEN-ARCHITECTURE-FOR-AI-AGENTS/", i: "fa-sitemap", d: "Event Architecture" },
  { n: "GeoStructPro 15", u: "https://adikds.github.io/GeoStructPro-15-Essential-Geotechnical-Formulas/", i: "fa-mountain", d: "Geo Formulas" },
  { n: "GeoStruct Pro 20", u: "https://adikds.github.io/GEOSTRUCT-PRO-20-FORMULA-GEOTECHNICAL/", i: "fa-layer-group", d: "20 Geo Formulas" },
  { n: "USCS Soil", u: "https://adikds.github.io/UNIFIED-SOIL-CLASSIFICATION-SYSTEM/", i: "fa-cubes", d: "Soil Classifier" },
  { n: "AeroRadar Pro", u: "https://adikds.github.io/AERORADAR-PRO/", i: "fa-plane", d: "Aviation Radar" },
  { n: "HydraCanal Pro", u: "https://adikds.github.io/HYDRACANAL-PRO-GEOMETRIC-DESIGN/", i: "fa-water-ladder", d: "Canal Design" },
  { n: "Financial Planner", u: "https://adikds.github.io/financial-planner/", i: "fa-chart-line", d: "OTW 1 Milyar" },
  { n: "Business Suite", u: "https://adikds.github.io/business-suite/", i: "fa-chart-bar", d: "AppSuite Manager" },
  { n: "Stock Manager", u: "https://adikds.github.io/stock-manager/", i: "fa-boxes-stacked", d: "Inventory System" },
  { n: "POS Terminal Pro", u: "https://adikds.github.io/Aplikasi_Point_of_Sale_-POS-_atau_sistem_kasir/", i: "fa-cash-register", d: "Cashier System" },
  { n: "Keuanganku", u: "https://adikds.github.io/KEUANGANKU/", i: "fa-wallet", d: "Finance Tracker" },
  { n: "DARUSSYIFA V.5.0", u: "https://adikds.github.io/DARUSSYIFA-MEDIKA/", i: "fa-hospital", d: "Klinik & Apotek" },
  { n: "DARUSSYIFA V.2.0", u: "https://adikds.github.io/DARUSSYIFA_MEDIKA/", i: "fa-file-medical", d: "Medical Record" },
  { n: "SKIN SYIFA AI", u: "https://adikds.github.io/SKIN_SYIFA_AI/", i: "fa-magnifying-glass-chart", d: "Skin Cancer AI" },
  { n: "NEURO-PSYCH AI", u: "https://adikds.github.io/NEURO-PSYCH_AI/", i: "fa-brain", d: "Psychological AI" },
  { n: "SMILE SYIFA AI", u: "https://adikds.github.io/SMILE-SYIFA-AI/", i: "fa-face-smile", d: "Dental AI" },
  { n: "DOKTER AI EXPERT", u: "https://adikds.github.io/DOKTER-AI/", i: "fa-user-doctor", d: "Medical AI" },
  { n: "Perpustakaan", u: "https://www.f15library.com/", i: "fa-book-open-reader", d: "F15 Library Digital" },
  { n: "Radio Online", u: "https://famelack.com/radio/id", i: "fa-radio", d: "Streaming Radio ID" },
  { n: "TV Online", u: "https://famelack.com/tv/id", i: "fa-tv", d: "Streaming TV Famelack" }
];

// Load Database dari LocalStorage jika ada
if (localStorage.getItem('jarvis_apps_db_v6')) {
  try { myApps = JSON.parse(localStorage.getItem('jarvis_apps_db_v6')); } catch(e){}
}

function renderMyApps() {
  const container = document.getElementById('apps-grid-container');
  container.innerHTML = '';
  myApps.forEach((app, idx) => {
    const card = document.createElement('div');
    card.className = 'app-card';
    card.setAttribute('data-tip', `Buka Aplikasi: ${app.n} (${app.d})`);
    card.innerHTML = `
      <i class="fa-solid ${app.i}"></i>
      <span>${app.n}</span>
      <div style="font-size:10px; color:rgba(0,255,255,0.5);">${app.d}</div>
      <div class="app-actions">
        <button class="btn-mini" onclick="editApp(${idx})" title="Edit App"><i class="fa-solid fa-pen"></i></button>
      </div>
    `;
    card.onclick = (e) => {
      if(!e.target.closest('.app-actions')) window.open(app.u, '_blank');
    };
    container.appendChild(card);
  });
}

function renderDatabase() {
  const tbody = document.getElementById('db-table-body');
  tbody.innerHTML = '';
  myApps.forEach((app, idx) => {
    const tr = document.createElement('tr');
    tr.innerHTML = `
      <td class="mono">${idx + 1}</td>
      <td class="orbitron" style="color:#fff;"><i class="fa-solid ${app.i}"></i> ${app.n}</td>
      <td>${app.d}</td>
      <td><a href="${app.u}" target="_blank" style="color:var(--cyan); font-size:11px;">${app.u.slice(0,35)}...</a></td>
      <td>
        <button class="btn-hud" style="padding:4px 8px; font-size:10px; background:rgba(0,150,255,0.3);" onclick="editApp(${idx})"><i class="fa-solid fa-pen"></i></button>
        <button class="btn-hud" style="padding:4px 8px; font-size:10px; background:rgba(255,50,50,0.3); border-color:#ff4444;" onclick="deleteApp(${idx})"><i class="fa-solid fa-trash"></i></button>
      </td>
    `;
    tbody.appendChild(tr);
  });
  localStorage.setItem('jarvis_apps_db_v6', JSON.stringify(myApps));
}

function saveAppToDb() {
  const name = document.getElementById('db-name').value.trim();
  const url = document.getElementById('db-url').value.trim();
  const desc = document.getElementById('db-desc').value.trim() || "Web Application";
  let icon = document.getElementById('db-icon').value.trim() || "fa-globe";
  if (!icon.startsWith('fa-')) icon = 'fa-' + icon;
  const idx = parseInt(document.getElementById('db-edit-idx').value);

  if (!name || !url) { alert("Nama Aplikasi dan URL wajib diisi!"); return; }

  if (idx >= 0) {
    myApps[idx] = { n: name, u: url, i: icon, d: desc };
    addLog(`Database updated: App "${name}" modified.`, 'sys');
  } else {
    myApps.push({ n: name, u: url, i: icon, d: desc });
    addLog(`Database updated: App "${name}" added to ecosystem.`, 'sys');
  }

  resetDbForm();
  renderDatabase();
  renderMyApps();
  speakJarvis(`Aplikasi ${name} berhasil disinkronisasi ke dalam database J.A.R.V.I.S.`);
}

function editApp(idx) {
  openModal('db-modal');
  document.getElementById('form-db-title').innerText = `EDIT APLIKASI #${idx + 1}: ${myApps[idx].n}`;
  document.getElementById('db-name').value = myApps[idx].n;
  document.getElementById('db-url').value = myApps[idx].u;
  document.getElementById('db-desc').value = myApps[idx].d;
  document.getElementById('db-icon').value = myApps[idx].i;
  document.getElementById('db-edit-idx').value = idx;
  document.getElementById('btn-cancel-db').style.display = 'inline-flex';
}

function deleteApp(idx) {
  if (confirm(`Hapus aplikasi "${myApps[idx].n}" dari database?`)) {
    const deletedName = myApps[idx].n;
    myApps.splice(idx, 1);
    renderDatabase();
    renderMyApps();
    addLog(`App deleted: "${deletedName}" removed.`, 'warn');
  }
}

function resetDbForm() {
  document.getElementById('form-db-title').innerText = "TAMBAH APLIKASI BARU";
  document.getElementById('db-name').value = "";
  document.getElementById('db-url').value = "";
  document.getElementById('db-desc').value = "";
  document.getElementById('db-icon').value = "fa-globe";
  document.getElementById('db-edit-idx').value = "-1";
  document.getElementById('btn-cancel-db').style.display = 'none';
}
renderMyApps();

/* 2. AUDIO VISUALIZER & TEXT TO SPEECH (SYNCHRONIZED CAT MOUTH) */
const synth = window.speechSynthesis;
let jarvisVoice = null;

function loadVoices() {
  const voices = synth.getVoices();
  jarvisVoice = voices.find(v => (v.name.includes('Indonesian') || v.name.includes('ID') || v.name.includes('Google ID') || v.name.includes('Female') || v.name.includes('Daniel'))) || voices[0];
}
if (synth.onvoiceschanged !== undefined) { synth.onvoiceschanged = loadVoices; }
loadVoices();

function toggleVisualizer(active) {
  const bars = document.querySelectorAll('.vis-bar');
  bars.forEach((bar, idx) => {
    if (active) {
      bar.classList.add('active');
      bar.style.animationDelay = (idx * 0.08) + 's';
    } else {
      bar.classList.remove('active');
      bar.style.height = '6px';
    }
  });
}

function speakJarvis(text, mouthElementId = 'hud-mouth') {
  if (!synth) return;
  synth.cancel();
  const utterance = new SpeechSynthesisUtterance(text);
  if (jarvisVoice) utterance.voice = jarvisVoice;
  utterance.rate = 0.96;
  utterance.pitch = 1.1; // Sedikit dinaikkan agar cocok dengan karakter Cyber Cat
  
  const mouth = document.getElementById(mouthElementId);
  utterance.onstart = () => { 
    if (mouth) mouth.style.animation = "cat-mouth-talk 0.18s infinite alternate"; 
    toggleVisualizer(true);
  };
  utterance.onend = () => { 
    if (mouth) mouth.style.animation = "none"; 
    toggleVisualizer(false);
  };
  
  synth.speak(utterance);
}

/* 3. MOTTO & KATA BIJAK DINAMIS (CRUD & AUTO-VOICE READER) */
let myQuotes = [
  "Teknologi sejati bukan hanya tentang algoritma, melainkan tentang bagaimana kita memanfaatkannya untuk memberi manfaat bagi kemanusiaan.",
  "Teruslah berinovasi tanpa batas untuk memitigasi bencana dan membangun peradaban masa depan!",
  "Keberhasilan adalah hasil dari konsistensi analisis keteknikan dan ketekunan yang pantang menyerah.",
  "Keamanan dan stabilitas infrastruktur adalah pondasi utama kemajuan sebuah bangsa. Bangun dengan hati dan presisi."
];
if (localStorage.getItem('jarvis_quotes_v6')) {
  try { myQuotes = JSON.parse(localStorage.getItem('jarvis_quotes_v6')); } catch(e){}
}

let currentQuoteIdx = 0;
function updateQuotesDisplay() {
  const qText = `"${myQuotes[currentQuoteIdx]}"`;
  const hudQ = document.getElementById('hud-quote-box');
  const creditQ = document.getElementById('credit-quote-box');
  const ssQ = document.getElementById('ss-quote-box');
  
  if (hudQ) { hudQ.innerText = qText; hudQ.style.animation = 'none'; void hudQ.offsetWidth; hudQ.style.animation = 'fade-slide 8s infinite, color-shift 8s infinite'; }
  if (creditQ) creditQ.innerText = qText;
  if (ssQ) ssQ.innerText = qText;

  // Cek apakah suara baca otomatis aktif
  const autoRead = document.getElementById('quote-auto-read') && document.getElementById('quote-auto-read').value === 'yes';
  if (autoRead && document.getElementById('main-hud').style.display === 'flex') {
    speakJarvis(myQuotes[currentQuoteIdx]);
  }

  currentQuoteIdx = (currentQuoteIdx + 1) % myQuotes.length;
}
setInterval(updateQuotesDisplay, 8000);

function readCurrentQuote() {
  const idx = (currentQuoteIdx === 0) ? myQuotes.length - 1 : currentQuoteIdx - 1;
  speakJarvis(myQuotes[idx]);
}

function renderQuotesList() {
  const container = document.getElementById('quotes-list-container');
  if(!container) return;
  container.innerHTML = '';
  myQuotes.forEach((q, idx) => {
    const div = document.createElement('div');
    div.style.display = 'flex'; div.style.justifyContent = 'space-between'; div.style.background = 'rgba(0,255,255,0.05)'; div.style.padding = '4px 8px'; div.style.borderRadius = '4px';
    div.innerHTML = `
      <span style="flex:1; color:#fff;">"${q.slice(0, 50)}..."</span>
      <button onclick="deleteQuote(${idx})" style="color:#ff4444; background:none; border:none; cursor:pointer;"><i class="fa-solid fa-trash"></i></button>
    `;
    container.appendChild(div);
  });
}

function addNewQuote() {
  const input = document.getElementById('new-quote-input');
  const val = input.value.trim();
  if(!val) return;
  myQuotes.push(val);
  input.value = '';
  localStorage.setItem('jarvis_quotes_v6', JSON.stringify(myQuotes));
  renderQuotesList();
  updateQuotesDisplay();
  speakJarvis("Kata bijak baru berhasil ditambahkan ke dalam memori.");
}

function deleteQuote(idx) {
  if(myQuotes.length <= 1) { alert("Minimal harus tersisa 1 kata bijak!"); return; }
  myQuotes.splice(idx, 1);
  localStorage.setItem('jarvis_quotes_v6', JSON.stringify(myQuotes));
  renderQuotesList();
  updateQuotesDisplay();
}
renderQuotesList();

/* 4. CLOCK & DATE HANDLER */
const daysID = ['MINGGU', 'SENIN', 'SELASA', 'RABU', 'KAMIS', 'JUMAT', 'SABTU'];
const monthsID = ['JAN', 'FEB', 'MAR', 'APR', 'MEI', 'JUN', 'JUL', 'AGU', 'SEP', 'OKT', 'NOV', 'DES'];

function updateAllClocks() {
  const now = new Date();
  const timeStr = now.toLocaleTimeString('id-ID', { hour12: false });
  const dayStr = daysID[now.getDay()];
  const dateStr = `${String(now.getDate()).padStart(2, '0')} ${monthsID[now.getMonth()]} ${now.getFullYear()}`;
  const fullDateStr = `${dayStr}, ${dateStr}`;

  document.getElementById('live-clock-top').innerText = timeStr;
  document.getElementById('ss-clock').innerText = timeStr;
  document.getElementById('ss-date').innerText = fullDateStr;
  document.getElementById('center-clock-text').innerText = timeStr;
  document.getElementById('center-date-text').innerText = fullDateStr;
  document.getElementById('credit-clock-display').innerText = `${fullDateStr} | ${timeStr} WIB`;
}
setInterval(updateAllClocks, 1000);
updateAllClocks();

/* 5. BOOTING SEQUENCE WITH CAT ANIMATION */
let bootProgress = 0;
const bootSteps = [
  "INITIALIZING CYBER CAT 3D CORE...",
  "CALIBRATING ORBITAL ELECTRON RINGS...",
  "BYPASSING SECURITY (NO PASSWORD MODE)...",
  "LOADING MOHAMAD HARTADI 28 APPS DATABASE...",
  "SYSTEM OPTIMAL. LAUNCHING CAT SUPERAGENT..."
];

const bootInterval = setInterval(() => {
  bootProgress += 2;
  document.getElementById('boot-progress').style.width = bootProgress + "%";
  document.getElementById('boot-percent').innerText = bootProgress + "%";
  
  const stepIdx = Math.min(Math.floor((bootProgress / 100) * bootSteps.length), bootSteps.length - 1);
  document.getElementById('boot-step-text').innerText = bootSteps[stepIdx];

  if (bootProgress >= 100) {
    clearInterval(bootInterval);
    setTimeout(() => {
      document.getElementById('boot-screen').style.display = 'none';
      document.getElementById('main-hud').style.display = 'flex';
      
      const now = new Date();
      const dayEn = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'][now.getDay()];
      const timeEn = now.toLocaleTimeString('en-US', { hour: '2-digit', minute: '2-digit' });
      
      speakJarvis(`Meow! System online. Selamat datang kembali, Bapak Mohamad Hartadi. Hari ini adalah hari ${daysID[now.getDay()]}, pukul ${timeEn}. Seluruh database aplikasi siap dijalankan.`);
      addLog("Boot sequence complete. Welcome Mohamad Hartadi (Adi).", "sys");
    }, 500);
  }
}, 35);

/* 6. MODAL & TOOLTIP HANDLER */
function openModal(id) { document.getElementById(id).classList.add('active'); if(id==='credit-modal') renderQuotesList(); }
function closeModal(id) { document.getElementById(id).classList.remove('active'); }
function closeModalOutside(e, id) { if (e.target.id === id) closeModal(id); }

const tooltip = document.getElementById('custom-tooltip');
document.addEventListener('mouseover', (e) => {
  const tipText = e.target.closest('[data-tip]')?.getAttribute('data-tip');
  if (tipText) {
    tooltip.innerText = tipText;
    tooltip.classList.add('show');
  } else {
    tooltip.classList.remove('show');
  }
});
document.addEventListener('mousemove', (e) => {
  if (tooltip.classList.contains('show')) {
    tooltip.style.left = Math.min(e.pageX + 15, window.innerWidth - 220) + 'px';
    tooltip.style.top = (e.pageY + 15) + 'px';
  }
});

/* 7. SCREENSAVER ENGINE */
let idleTimer = null;
let idleLimit = 180;

function resetIdleTimer() {
  clearTimeout(idleTimer);
  if (idleLimit > 0 && document.getElementById('screensaver').style.display !== 'flex') {
    idleTimer = setTimeout(startScreensaver, idleLimit * 1000);
  }
}
['mousemove', 'keydown', 'mousedown', 'touchstart'].forEach(evt => document.addEventListener(evt, resetIdleTimer));

function startScreensaver() {
  document.getElementById('screensaver').style.display = 'flex';
  const voiceActive = document.getElementById('ss-voice-select').value === 'yes';
  if (voiceActive) {
    const nowStr = new Date().toLocaleTimeString('id-ID');
    speakJarvis(`Screensaver mode aktif. Jam menunjukkan pukul ${nowStr}. Sentuh layar atau klik di mana saja untuk kembali ke antarmuka utama.`, 'ss-mouth');
  }
}

function stopScreensaver() {
  document.getElementById('screensaver').style.display = 'none';
  resetIdleTimer();
  speakJarvis("Meow! Kembali ke Dasbor J.A.R.V.I.S. Siap menerima perintah Anda, Sir.", 'hud-mouth');
}

function testScreensaver() {
  closeModal('ss-settings-modal');
  startScreensaver();
}

function updateScreensaverTimer() {
  idleLimit = parseInt(document.getElementById('ss-timer-select').value);
  resetIdleTimer();
}

function saveScreensaverSettings() {
  updateScreensaverTimer();
  closeModal('ss-settings-modal');
  speakJarvis("Pengaturan screensaver dan waktu berhasil disimpan.");
  addLog("Screensaver settings updated.", "sys");
}

/* 8. KREDIT PROGRAMMER VOICE TRIGGER */
function triggerCreditVoice() {
  const text = `Memperkenalkan Bapak Mohamad Hartadi, atau biasa dipanggil Adi. Civil Engineer, Analis Geoteknik, dan Spesialis Prompt Engineering. Motto beliau: Teknologi sejati harus memberi manfaat bagi kemanusiaan!`;
  speakJarvis(text, 'credit-mouth');
}

/* 9. ACTIVITY LOG & SMART COMMAND NLP DENGAN UI PANDUAN OTOMATIS */
function addLog(text, type = 'user') {
  const logBox = document.getElementById('log-box');
  const now = new Date().toLocaleTimeString('id-ID', { hour12: false });
  const entry = document.createElement('div');
  entry.className = 'log-entry';
  entry.innerHTML = `<span class="log-time">[${now}]</span> <span class="log-text ${type}">${text}</span>`;
  logBox.prepend(entry);
}

// Fungsi tambahan untuk memasukkan UI HTML langsung ke log-box
function addRichLog(htmlStr) {
  const logBox = document.getElementById('log-box');
  const now = new Date().toLocaleTimeString('id-ID', { hour12: false });
  const entry = document.createElement('div');
  entry.className = 'log-entry';
  entry.style.flexDirection = 'column';
  entry.style.alignItems = 'flex-start';
  entry.style.borderBottom = '1px solid rgba(0, 255, 255, 0.2)';
  entry.innerHTML = `<div style="margin-bottom:6px;"><span class="log-time">[${now}] [NLP ASSISTANT]</span></div> ${htmlStr}`;
  logBox.prepend(entry);
}

// Render UI Template untuk Aplikasi Spesifik
function getAppCardHtml(app) {
    return `
    <div style="background:rgba(0,30,50,0.8); border:1px solid var(--cyan); padding:12px; border-radius:8px; margin-top:4px; width:100%; box-shadow:0 0 10px rgba(0,255,255,0.1);">
        <span style="color:var(--cyan); font-weight:bold; font-family:'Orbitron'; font-size:13px; border-bottom:1px solid rgba(0,255,255,0.3); padding-bottom:6px; display:block; margin-bottom:8px;">
            <i class="fa-solid ${app.i}" style="color:var(--amber); margin-right:4px;"></i> ${app.n.toUpperCase()}
        </span>
        <p style="color:#d0f0ff; font-size:11px; margin-bottom:10px; line-height:1.4;">${app.d}</p>
        <a href="${app.u}" target="_blank" style="display:inline-block; background:linear-gradient(90deg, rgba(0,255,255,0.2), rgba(0,100,255,0.2)); border:1px solid var(--cyan); color:#fff; padding:6px 12px; border-radius:4px; text-decoration:none; font-size:10px; font-weight:bold; letter-spacing:1px; transition:0.3s;">
            <i class="fa-solid fa-arrow-up-right-from-square"></i> BUKA SEKARANG
        </a>
    </div>`;
}

function quickAction(msg) {
  addLog(`Action executed: ${msg}`, 'user');
  speakJarvis(msg);
}

function sendCommand() {
  const input = document.getElementById('cmd-input');
  const query = input.value.trim();
  if (!query) return;
  
  addLog(`Command: "${query}"`, 'user');
  input.value = '';
  const qLow = query.toLowerCase();

  // A1. Cek Pintasan Khusus Tanpa Kata "Buka"
  if (qLow === 'perpustakaan' || qLow === 'library') {
      const app = { n: "Perpustakaan", u: "https://www.f15library.com/", i: "fa-book-open-reader", d: "F15 Library Digital" };
      addRichLog(getAppCardHtml(app));
      speakJarvis(`Membuka panduan aplikasi ${app.n}.`);
      setTimeout(() => { window.open(app.u, '_blank'); }, 1500);
      return;
  }
  if (qLow === 'radio' || qLow === 'radio online') {
      const app = { n: "Radio Online", u: "https://famelack.com/radio/id", i: "fa-radio", d: "Streaming Radio ID" };
      addRichLog(getAppCardHtml(app));
      speakJarvis(`Membuka panduan aplikasi ${app.n}.`);
      setTimeout(() => { window.open(app.u, '_blank'); }, 1500);
      return;
  }
  if (qLow === 'tv' || qLow === 'tv online') {
      const app = { n: "TV Online", u: "https://famelack.com/tv/id", i: "fa-tv", d: "Streaming TV Famelack" };
      addRichLog(getAppCardHtml(app));
      speakJarvis(`Membuka panduan aplikasi ${app.n}.`);
      setTimeout(() => { window.open(app.u, '_blank'); }, 1500);
      return;
  }

  // A2. PANDUAN HELP TEKS OTOMATIS (Aplikasi & Ekosistem)
  if (qLow.includes('buka') || qLow === 'aplikasi' || qLow === 'app' || qLow === 'my app' || qLow.includes('daftar app') || qLow === 'help') {
      
      let matchedApp = null;
      let querySubject = qLow.replace('buka', '').replace('aplikasi', '').trim();
      
      if (querySubject.length > 2) {
          for (let app of myApps) {
              if (app.n.toLowerCase().includes(querySubject) || app.d.toLowerCase().includes(querySubject)) {
                  matchedApp = app;
                  break;
              }
          }
      }

      // Jika menemukan aplikasi spesifik (contoh: "buka quran")
      if (matchedApp) {
          addRichLog(getAppCardHtml(matchedApp));
          speakJarvis(`Membuka panduan aplikasi ${matchedApp.n}.`);
          setTimeout(() => { window.open(matchedApp.u, '_blank'); }, 1500);
      } 
      // Jika hanya "buka" atau "aplikasi", tampilkan daftar lengkap
      else {
          let appsListUI = `
          <div style="background:rgba(0,15,30,0.9); border:1px solid var(--amber); padding:12px; border-radius:8px; margin-top:4px; width:100%; box-shadow:0 0 10px rgba(245,158,11,0.1);">
              <span style="color:var(--amber); font-weight:bold; font-family:'Orbitron'; font-size:12px; border-bottom:1px dashed rgba(245,158,11,0.4); padding-bottom:6px; display:block; margin-bottom:8px;">
                  <i class="fa-solid fa-grid-2" style="margin-right:4px;"></i> PANDUAN EKOSISTEM APLIKASI
              </span>
              <p style="color:#bbb; font-size:10px; margin-bottom:8px;">Pilih aplikasi web karya Bapak Mohamad Hartadi di bawah ini untuk membukanya:</p>
              <div style="display:flex; flex-direction:column; gap:6px; max-height:180px; overflow-y:auto; padding-right:6px;" class="hide-scrollbar">
          `;
          
          myApps.forEach(app => {
              appsListUI += `
              <div style="background:rgba(0,30,60,0.5); padding:8px; border-radius:6px; border:1px solid rgba(0,255,255,0.15); cursor:pointer; display:flex; justify-content:space-between; align-items:center;" onclick="window.open('${app.u}', '_blank')" title="${app.d}">
                  <div style="display:flex; align-items:center; gap:8px;">
                      <div style="width:20px; text-align:center;"><i class="fa-solid ${app.i}" style="color:var(--cyan); font-size:14px;"></i></div>
                      <span style="color:#fff; font-size:11px; font-weight:bold;">${app.n}</span>
                  </div>
                  <span style="font-size:9px; background:rgba(0,255,255,0.15); color:var(--cyan); padding:3px 6px; border-radius:4px; font-weight:bold;">Buka &rarr;</span>
              </div>`;
          });
          
          appsListUI += `</div></div>`;
          addRichLog(appsListUI);
          speakJarvis("Menampilkan panduan ekosistem aplikasi di layar terminal log Anda.");
      }
      return;
  }

  // B. Topik Info Programmer
  if (qLow.includes('info') || qLow.includes('programmer') || qLow.includes('kreator') || qLow.includes('adi') || qLow.includes('hartadi') || qLow.includes('kontak') || qLow.includes('wa') || qLow.includes('fb') || qLow.includes('blog')) {
    openModal('credit-modal');
    triggerCreditVoice();
    addLog("[SYSTEM]: Menampilkan info Programmer (FB: m.hartadi, Blog: newbieonline7, WA: 082231036047).", "sys");
    return;
  }

  // C. Topik Database
  if (qLow.includes('database') || qLow.includes('db') || qLow.includes('kelola app')) {
    openModal('db-modal');
    renderDatabase();
    speakJarvis("Membuka antarmuka Database untuk mengelola daftar aplikasi Anda.");
    return;
  }

  // D. Cek Waktu / Jam
  if (qLow.includes('waktu') || qLow.includes('jam') || qLow.includes('hari') || qLow.includes('tanggal')) {
    const nowStr = new Date().toLocaleTimeString('id-ID');
    speakJarvis(`Waktu saat ini adalah pukul ${nowStr} Waktu Indonesia Barat, hari ${document.getElementById('center-date-text').innerText}.`);
    return;
  }

  // Default Fallback
  speakJarvis(`Meow! Saya mengerti perintah: "${query}". Untuk panduan aplikasi, silakan ketik kata "buka aplikasi".`);
}

let recognizing = false;
function toggleVoice() {
  const micBtn = document.getElementById('mic-btn');
  if (!('webkitSpeechRecognition' in window) && !('SpeechRecognition' in window)) {
    alert("Fitur Voice Recognition tidak didukung di browser ini. Gunakan Google Chrome atau Microsoft Edge terbaru.");
    return;
  }
  const SpeechRec = window.SpeechRecognition || window.webkitSpeechRecognition;
  const rec = new SpeechRec();
  rec.lang = 'id-ID';
  
  if (!recognizing) {
    rec.start();
    recognizing = true;
    micBtn.classList.add('listening');
    addLog("Mendengarkan perintah suara (Katakan: buka perpustakaan, info programmer, atau help)...", "warn");
  } else {
    rec.stop();
    recognizing = false;
    micBtn.classList.remove('listening');
  }

  rec.onresult = (e) => {
    const transcript = e.results[0][0].transcript;
    document.getElementById('cmd-input').value = transcript;
    sendCommand();
  };
  rec.onend = () => {
    recognizing = false;
    micBtn.classList.remove('listening');
  };
}

// Simulasi Metrik Sistem Dinamis
setInterval(() => {
  const cpu = Math.floor(Math.random() * 25) + 20;
  const ram = Math.floor(Math.random() * 10) + 58;
  document.getElementById('cpu-val').innerText = cpu + "%";
  document.getElementById('cpu-bar').style.width = cpu + "%";
  document.getElementById('ram-val').innerText = ram + "%";
  document.getElementById('ram-bar').style.width = ram + "%";
}, 3000);
</script>
</body>
</html>
