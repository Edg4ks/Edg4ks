<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>0/Xdgxks — Offensive Security</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Share+Tech+Mono&family=Bebas+Neue&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
body{background:#07050d;font-family:'Share Tech Mono',monospace;color:#c8c8d8;padding:2rem}
 
.glitch{font-family:'Bebas Neue',cursive;font-size:4.5rem;letter-spacing:.15em;color:#fff;position:relative;display:inline-block;animation:glitchAnim 4s infinite}
.glitch::before,.glitch::after{content:attr(data-text);position:absolute;top:0;left:0;width:100%;font-family:'Bebas Neue',cursive;font-size:4.5rem;letter-spacing:.15em}
.glitch::before{color:#ff003c;clip:rect(0,900px,0,0);animation:glitch1 4s infinite}
.glitch::after{color:#00f0ff;clip:rect(0,900px,0,0);animation:glitch2 4s infinite;opacity:.5}
@keyframes glitchAnim{0%,90%,100%{transform:none}91%{transform:skewX(-1deg)}93%{transform:skewX(1.5deg)}95%{transform:skewX(0)}}
@keyframes glitch1{0%,85%,100%{clip:rect(0,0,0,0);transform:none}86%{clip:rect(12px,900px,24px,0);transform:translate(-3px)}88%{clip:rect(50px,900px,62px,0);transform:translate(3px)}90%{clip:rect(30px,900px,45px,0);transform:translate(-2px)}92%{clip:rect(0,0,0,0)}}
@keyframes glitch2{0%,87%,100%{clip:rect(0,0,0,0);transform:none}88%{clip:rect(40px,900px,52px,0);transform:translate(4px)}90%{clip:rect(8px,900px,20px,0);transform:translate(-3px)}92%{clip:rect(60px,900px,70px,0);transform:translate(2px)}94%{clip:rect(0,0,0,0)}}
 
.top{text-align:center;margin-bottom:2.5rem;position:relative;overflow:hidden}
.top::after{content:'';position:absolute;top:0;left:-100%;width:40%;height:100%;background:linear-gradient(90deg,transparent,rgba(204,34,68,.06),transparent);animation:sweep 3s linear infinite}
@keyframes sweep{to{left:160%}}
 
.subtitle{font-size:.72rem;color:#cc2244;letter-spacing:.3em;margin-top:.3rem}
.handle{font-size:.8rem;color:#6050a0;letter-spacing:.15em;margin-top:.2rem}
 
.divider{height:1px;background:linear-gradient(90deg,transparent,#cc2244,transparent);margin:2rem 0;position:relative}
.divider::after{content:'[ ARSENAL ]';position:absolute;left:50%;transform:translateX(-50%) translateY(-50%);background:#07050d;padding:0 1rem;font-size:.6rem;color:#cc2244;letter-spacing:.3em}
 
.console{background:#050308;border:1px solid #1e0a1a;border-radius:3px;padding:.9rem 1rem;margin-bottom:2rem;font-size:.7rem;line-height:1.9;color:#9090a8}
.c-red{color:#ff4060}.c-grn{color:#4ec94e}.c-blu{color:#5090e0}.c-wht{color:#ddd}
.blink{animation:blink 1s step-end infinite}
@keyframes blink{50%{opacity:0}}
 
.skills-wrap{display:grid;grid-template-columns:1fr 1fr 1fr;gap:1rem;margin-bottom:2rem}
.sk{background:#0c0814;border:1px solid #1e0a1a;border-radius:3px;padding:1rem}
.sk-title{font-size:.58rem;color:#cc2244;letter-spacing:.25em;text-transform:uppercase;margin-bottom:.8rem;padding-bottom:.5rem;border-bottom:1px solid #1e0a1a}
.item{display:flex;align-items:center;gap:.5rem;font-size:.72rem;color:#b0a8c8;padding:.25rem 0;border-bottom:1px solid #120810}
.item:last-child{border:none}
.item:hover{color:#ff4060}
.dot{width:5px;height:5px;border-radius:50%;flex-shrink:0;background:#cc2244;animation:dotPulse 2s ease-in-out infinite}
.dot.p{background:#8040c0;animation-delay:.3s}
.dot.g{background:#2ea043;animation-delay:.6s}
.dot.b{background:#378add;animation-delay:.9s}
@keyframes dotPulse{0%,100%{opacity:.4;transform:scale(1)}50%{opacity:1;transform:scale(1.4)}}
 
.langs-row{display:flex;gap:.6rem;flex-wrap:wrap;margin-bottom:2rem;justify-content:center}
.lang{display:flex;align-items:center;gap:.5rem;padding:.45rem 1rem;border:1px solid #2a1030;background:#0c0814;border-radius:2px;font-size:.72rem;color:#c0b8d8;transition:border-color .2s,color .2s}
.lang:hover{border-color:#cc2244;color:#fff}
.lc{width:9px;height:9px;border-radius:50%}
 
.bottom{text-align:center;padding-top:1.5rem;border-top:1px solid #1a0a18}
.bq{font-size:.78rem;color:#6050a0;line-height:2;letter-spacing:.05em}
.bq strong{color:#cc2244}
</style>
</head>
<body>
 
<div class="top">
  <div class="glitch" data-text="OFFENSIVE SEC">OFFENSIVE SEC</div>
  <div class="subtitle">// web penetration · red team · bug bounty</div>
  <div class="handle">0/Xdgxks &nbsp;·&nbsp; ethical hacker</div>
</div>
 
<div class="console">
  <span class="c-red">root@ghost</span><span class="c-wht">:</span><span class="c-blu">~/targets</span><span class="c-wht">$ </span><span class="c-grn">whoami</span><br>
  <span class="c-wht">&nbsp;→ web pentester · osint operator · rust toolsmith</span><br>
  <span class="c-red">root@ghost</span><span class="c-wht">:</span><span class="c-blu">~/targets</span><span class="c-wht">$ </span><span class="c-grn">cat mission.txt</span><br>
  <span class="c-wht">&nbsp;→ find the crack in every surface. leave no log.</span><br>
  <span class="c-red">root@ghost</span><span class="c-wht">:</span><span class="c-blu">~/targets</span><span class="c-wht">$ </span><span class="blink c-wht">_</span>
</div>
 
<div class="divider"></div>
 
<div class="skills-wrap">
 
  <div class="sk">
    <div class="sk-title">🕸 web hacking</div>
    <div class="item"><span class="dot"></span>Burp Suite Pro</div>
    <div class="item"><span class="dot"></span>Caido</div>
    <div class="item"><span class="dot"></span>SQLMap</div>
    <div class="item"><span class="dot"></span>Dalfox</div>
    <div class="item"><span class="dot"></span>XSStrike</div>
    <div class="item"><span class="dot"></span>ffuf</div>
    <div class="item"><span class="dot"></span>Nuclei</div>
    <div class="item"><span class="dot"></span>Arjun</div>
    <div class="item"><span class="dot"></span>Katana</div>
    <div class="item"><span class="dot"></span>JWT Tool</div>
  </div>
 
  <div class="sk">
    <div class="sk-title">💀 recon · osint</div>
    <div class="item"><span class="dot p"></span>Shodan</div>
    <div class="item"><span class="dot p"></span>Subfinder</div>
    <div class="item"><span class="dot p"></span>Amass</div>
    <div class="item"><span class="dot p"></span>httpx</div>
    <div class="item"><span class="dot p"></span>gau</div>
    <div class="item"><span class="dot p"></span>Waybackurls</div>
    <div class="item"><span class="dot p"></span>BBOT</div>
    <div class="item"><span class="dot p"></span>theHarvester</div>
    <div class="item"><span class="dot p"></span>Maltego</div>
    <div class="item"><span class="dot p"></span>ParamSpider</div>
  </div>
 
  <div class="sk">
    <div class="sk-title">⚔ vuln classes</div>
    <div class="item"><span class="dot b"></span>XSS · Stored · DOM</div>
    <div class="item"><span class="dot b"></span>SQL Injection</div>
    <div class="item"><span class="dot b"></span>SSRF</div>
    <div class="item"><span class="dot b"></span>IDOR</div>
    <div class="item"><span class="dot b"></span>SSTI</div>
    <div class="item"><span class="dot b"></span>XXE</div>
    <div class="item"><span class="dot b"></span>OAuth Abuse</div>
    <div class="item"><span class="dot b"></span>Cache Poisoning</div>
    <div class="item"><span class="dot b"></span>Proto Pollution</div>
    <div class="item"><span class="dot b"></span>Open Redirect</div>
  </div>
 
</div>
 
<div class="langs-row">
  <span class="lang"><span class="lc" style="background:#CE412B"></span>Rust</span>
  <span class="lang"><span class="lc" style="background:#4e4e4e"></span>Bash</span>
  <span class="lang"><span class="lc" style="background:#3776AB"></span>Python</span>
  <span class="lang"><span class="lc" style="background:#663399"></span>Obsidian</span>
  <span class="lang"><span class="lc" style="background:#2ea043"></span>GitHub</span>
</div>
 
<div class="bottom">
  <div class="bq">
    <strong>Every network has a shadow.</strong><br>
    I am that shadow.<br>
    <span style="font-size:.6rem;color:#3a1828;letter-spacing:.1em">ethical hacking only · all activities performed with authorization</span>
  </div>
</div>
 
</body>
</html>
