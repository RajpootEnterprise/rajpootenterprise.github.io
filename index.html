<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Siddhant Singh Rajpoot — Professional Portfolio</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700;800&family=Inter:wght@400;500;600;700&family=Fira+Code:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #f8fafc;
    --glass-bg: rgba(255, 255, 255, 0.6);
    --glass-border: rgba(0, 0, 0, 0.08);
    --glass-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.04);
    --text: #0f172a;
    --text-dim: #475569;
    --accent-1: #0d9488;
    --accent-2: #2563eb;
    --accent-fire: #ff4500;
    --accent-glow: rgba(13, 148, 136, 0.15);
  }
  
  * { box-sizing: border-box; }
  html { scroll-behavior: smooth; cursor: none; /* Hide default cursor for custom snake cursor */ }
  body {
    margin: 0;
    background-color: var(--bg);
    color: var(--text);
    font-family: 'Inter', sans-serif;
    overflow-x: hidden;
  }
  
  ::selection { background: var(--accent-1); color: #fff; }

  /* Parallax Background Glow */
  .bg-glow {
    position: fixed; top: -10%; left: -10%;
    width: 60vw; height: 60vw;
    background: radial-gradient(circle, var(--accent-glow) 0%, transparent 60%);
    z-index: -1; pointer-events: none; transition: transform 0.1s ease-out;
  }
  .bg-glow.right {
    top: 40%; left: auto; right: -20%;
    background: radial-gradient(circle, rgba(255, 69, 0, 0.1) 0%, transparent 60%);
  }

  /* Custom Snake Cursor Trail */
  .cursor-dot {
    position: fixed; top: 0; left: 0;
    width: 12px; height: 12px;
    background: var(--accent-1);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9999;
    transform: translate(-50%, -50%);
    box-shadow: 0 0 10px var(--accent-1);
  }
  
  .wrap { max-width: 1000px; margin: 0 auto; padding: 0 24px; position: relative; z-index: 2;}

  /* Header */
  header {
    display: flex; justify-content: space-between; align-items: center;
    padding: 20px 0; border-bottom: 1px solid var(--glass-border);
    position: sticky; top: 0; z-index: 100;
    background: rgba(248, 250, 252, 0.8); backdrop-filter: blur(12px);
    transition: padding 0.3s ease; cursor: default;
  }
  .logo { font-family: 'JetBrains Mono', monospace; font-weight: 700; font-size: 18px; color: var(--text); }
  .logo span { color: var(--accent-fire); }

  /* Sound Toggle Button */
  #soundToggle {
    position: fixed; bottom: 30px; right: 30px; z-index: 1000;
    background: var(--glass-bg); backdrop-filter: blur(12px);
    border: 1px solid var(--accent-fire); border-radius: 50px;
    padding: 12px 24px; font-family: 'JetBrains Mono', monospace;
    font-size: 14px; font-weight: 600; color: var(--text);
    cursor: pointer; box-shadow: 0 8px 32px rgba(255, 69, 0, 0.2);
    transition: all 0.3s ease;
  }
  #soundToggle:hover { background: var(--accent-fire); color: #fff; transform: scale(1.05); }

  /* Hero Section */
  .hero { position: relative; padding: 100px 0; display: flex; align-items: center; min-height: 80vh; cursor: default; }
  .hero-content { position: relative; z-index: 2; max-width: 600px; }
  
  canvas#three-hero {
    position: absolute; top: 50%; right: -10%; transform: translateY(-50%);
    width: 600px !important; height: 600px !important; z-index: 1; pointer-events: none;
  }

  .role {
    font-family: 'Fira Code', monospace; font-size: 14px; color: var(--accent-1);
    letter-spacing: 1px; text-transform: uppercase; margin-bottom: 16px; display: block;
  }
  
  h1 {
    font-family: 'JetBrains Mono', monospace; font-size: clamp(40px, 6vw, 64px);
    margin: 0 0 20px; font-weight: 800; line-height: 1.1; letter-spacing: -1px;
    background: linear-gradient(90deg, #0f172a, #ff4500);
    -webkit-background-clip: text; -webkit-text-fill-color: transparent;
  }
  
  p.bio { font-size: 18px; color: var(--text-dim); line-height: 1.8; margin-bottom: 30px; }
  
  .glass-card {
    background: var(--glass-bg); backdrop-filter: blur(16px);
    border: 1px solid var(--glass-border); border-radius: 16px;
    padding: 30px; box-shadow: var(--glass-shadow);
    transition: transform 0.4s cubic-bezier(0.16, 1, 0.3, 1), box-shadow 0.4s ease, border-color 0.4s ease;
  }

  /* Tags */
  .tags { display: flex; flex-wrap: wrap; gap: 10px; }
  .tag {
    font-family: 'Fira Code', monospace; font-size: 13px; color: var(--text);
    background: rgba(0,0,0,0.04); border: 1px solid var(--glass-border);
    padding: 6px 14px; border-radius: 20px; font-weight: 500;
  }

  /* Section Styles & Animations */
  .section { padding: 100px 0; border-top: 1px solid var(--glass-border); cursor: default; }
  h2 { font-family: 'JetBrains Mono', monospace; font-size: 32px; font-weight: 700; margin: 0 0 40px; color: var(--text); }
  
  .reveal { opacity: 0; transform: translateY(60px) scale(0.95); transition: opacity 0.8s ease, transform 0.8s cubic-bezier(0.16, 1, 0.3, 1); }
  .reveal.in { opacity: 1; transform: translateY(0) scale(1); }

  .stack-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(140px, 1fr)); gap: 16px; }
  .stack-card {
    background: #fff; border: 1px solid var(--glass-border);
    padding: 16px; border-radius: 12px; text-align: center;
    font-family: 'JetBrains Mono', monospace; font-size: 14px; font-weight: 600; color: var(--text);
    box-shadow: var(--glass-shadow);
    opacity: 0; transform: scale(0.8) translateY(30px); transition: all 0.6s cubic-bezier(0.34, 1.56, 0.64, 1);
  }
  .stack-card.in { opacity: 1; transform: scale(1) translateY(0); }
  .stack-card:hover { border-color: var(--accent-fire); transform: translateY(-8px) scale(1.05) rotate(2deg); box-shadow: 0 15px 25px -10px rgba(255, 69, 0, 0.3); }

  /* Timeline */
  .timeline { border-left: 2px solid var(--glass-border); padding-left: 30px; margin-left: 10px; }
  .timeline-item { position: relative; margin-bottom: 50px; opacity: 0; transform: translateX(-60px) skewX(5deg); transition: all 0.7s cubic-bezier(0.16, 1, 0.3, 1); }
  .timeline-item.in { opacity: 1; transform: translateX(0) skewX(0); }
  .timeline-item:last-child { margin-bottom: 0; }
  .timeline-item::before {
    content: ''; position: absolute; left: -37px; top: 5px; width: 12px; height: 12px;
    border-radius: 50%; background: #fff; border: 3px solid var(--accent-1);
    box-shadow: 0 0 0 4px var(--bg); transition: background 0.3s ease;
  }
  .timeline-item:hover::before { background: var(--accent-fire); border-color: var(--accent-fire); box-shadow: 0 0 15px var(--accent-fire); }
  .date { font-family: 'Fira Code', monospace; font-size: 13px; color: var(--accent-1); margin-bottom: 8px; display: block; font-weight: 500; }
  .timeline-title { font-size: 20px; font-weight: 700; margin: 0 0 10px; color: var(--text); }
  .timeline-desc { color: var(--text-dim); line-height: 1.7; font-size: 15px; margin-bottom: 16px; }

  /* Stats Grid */
  .stats-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; }
  .stat-card:hover { transform: translateY(-8px) scale(1.02); box-shadow: 0 15px 35px -10px rgba(0,0,0,0.1); border-color: var(--accent-1); }
  .stat-num { font-family: 'JetBrains Mono', monospace; font-size: 48px; font-weight: 800; color: var(--accent-1); margin-bottom: 5px; transition: color 0.3s ease; }
  .stat-card:hover .stat-num { color: var(--accent-fire); }
  .stat-label { font-family: 'Fira Code', monospace; font-size: 13px; color: var(--text-dim); text-transform: uppercase; letter-spacing: 1px; font-weight: 600;}

  /* Connect Grid */
  .connect-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
  .connect-card { text-decoration: none; color: var(--text); display: flex; align-items: center; justify-content: space-between; background: #fff; }
  .connect-card:hover { border-color: var(--accent-2); transform: translateY(-5px); box-shadow: 0 12px 30px -10px rgba(37, 99, 235, 0.2); }
  .connect-card .label { font-family: 'Fira Code', monospace; font-size: 12px; color: var(--text-dim); margin-bottom: 4px; font-weight: 500;}
  .connect-card .value { font-family: 'JetBrains Mono', monospace; font-size: 15px; font-weight: 600; color: var(--text); }

  footer { padding: 40px 0; text-align: center; border-top: 1px solid var(--glass-border); font-family: 'Fira Code', monospace; font-size: 13px; color: var(--text-dim); }

  @media (max-width: 768px) {
    html { cursor: auto; } .cursor-dot { display: none; }
    .hero { flex-direction: column; text-align: center; padding: 60px 0; }
    canvas#three-hero { position: relative; top: 0; right: 0; transform: none; width: 100% !important; height: 300px !important; margin: 40px auto 0; }
  }
</style>
</head>
<body>

<!-- Cursor Elements generated via JS -->
<div id="cursor-container"></div>

<!-- Sound Control -->
<button id="soundToggle">🔊 Enable Audio & Fire</button>

<div class="bg-glow" id="glow1"></div>
<div class="bg-glow right" id="glow2"></div>

<div class="wrap">
  <header id="header">
    <div class="logo">Siddhant<span>.</span></div>
    <div class="logo" style="font-size: 14px; font-weight: 400; color: var(--text-dim);">// software developer</div>
  </header>

  <div class="hero">
    <div class="hero-content reveal in">
      <span class="role">Associate Software Developer</span>
      <h1>Siddhant Singh Rajpoot</h1>
      <p class="bio">I own the billing microservice for BroadNet.ai, a live production platform — building robust Spring Boot services wired into Kafka and Docker/Kubernetes, processing real payments through Stripe at scale.</p>
      <div class="tags">
        <div class="tag">Spring Boot</div>
        <div class="tag">Kafka</div>
        <div class="tag">Kubernetes</div>
        <div class="tag">Docker</div>
        <div class="tag">Stripe</div>
        <div class="tag">Microservices</div>
      </div>
    </div>
    <canvas id="three-hero"></canvas>
  </div>

  <section class="section reveal">
    <h2>Impact in Numbers</h2>
    <div class="stats-grid">
      <div class="glass-card stat-card"><div class="stat-num" data-target="1">0</div><div class="stat-label">Live Production Platform</div></div>
      <div class="glass-card stat-card"><div class="stat-num" data-target="8" data-suffix=".5">0</div><div class="stat-label">CGPA</div></div>
      <div class="glass-card stat-card"><div class="stat-num" data-target="2" data-suffix="+">0</div><div class="stat-label">Billing Workflows</div></div>
      <div class="glass-card stat-card"><div class="stat-num" data-target="100" data-suffix="%">0</div><div class="stat-label">Stripe Integrated</div></div>
    </div>
  </section>

  <section class="section stagger-container">
    <h2 class="reveal">Technical Arsenal</h2>
    <div class="stack-grid">
      <div class="stack-card stagger-item">Java</div>
      <div class="stack-card stagger-item">Spring Boot</div>
      <div class="stack-card stagger-item">REST APIs</div>
      <div class="stack-card stagger-item">Kafka</div>
      <div class="stack-card stagger-item">Kubernetes</div>
      <div class="stack-card stagger-item">Docker</div>
      <div class="stack-card stagger-item">Stripe</div>
      <div class="stack-card stagger-item">MySQL</div>
      <div class="stack-card stagger-item">AWS</div>
      <div class="stack-card stagger-item">CI/CD</div>
      <div class="stack-card stagger-item">System Design</div>
      <div class="stack-card stagger-item">Microservices</div>
    </div>
  </section>

  <section class="section stagger-container">
    <h2 class="reveal">Experience & Projects</h2>
    <div class="timeline">
      <div class="timeline-item stagger-item">
        <span class="date">June 2026 – Present</span>
        <h3 class="timeline-title">Associate Software Developer @ High Tech Infosystem</h3>
        <p class="timeline-desc">Converted from internship to full-time. Own the billing microservice for the live BroadNet.ai platform. Built and maintain a live, production-grade billing microservice, integrating Stripe for end-to-end payment processing inside a Kafka/Docker ecosystem.</p>
      </div>
      <div class="timeline-item stagger-item">
        <span class="date">Feb 2026 – May 2026</span>
        <h3 class="timeline-title">Software Development Intern @ High Tech Infosystem</h3>
        <p class="timeline-desc">Onboarded onto the live BroadNet.ai codebase. Built foundational understanding of microservices architecture, REST APIs, and payment gateway integration through hands-on production work.</p>
      </div>
      <div class="timeline-item stagger-item">
        <span class="date">Feb 2025 – June 2025</span>
        <h3 class="timeline-title">GMB @ MBG CARDS</h3>
        <p class="timeline-desc">Early production exposure to microservices architecture, REST APIs, and payment gateway integration.</p>
      </div>
      <div class="timeline-item stagger-item">
        <span class="date">Project</span>
        <h3 class="timeline-title">E-Learning Platform</h3>
        <p class="timeline-desc">Role-based e-learning platform with distinct access levels for students and mentors — video learning modules paired with a guided mentoring system utilizing Core Java, Servlets, JSP, and MySQL.</p>
      </div>
    </div>
  </section>

  <section class="section stagger-container">
    <h2 class="reveal">Let's Connect</h2>
    <div class="connect-grid">
      <a class="glass-card connect-card stagger-item" href="https://github.com/RajpootEnterprise" target="_blank">
        <div><div class="label">GITHUB</div><div class="value">@RajpootEnterprise</div></div>
        <div style="color:var(--accent-1);">↗</div>
      </a>
      <a class="glass-card connect-card stagger-item" href="https://linkedin.com/in/siddhantsinghrajpoot" target="_blank">
        <div><div class="label">LINKEDIN</div><div class="value">siddhantsinghrajpoot</div></div>
        <div style="color:var(--accent-1);">↗</div>
      </a>
      <a class="glass-card connect-card stagger-item" href="mailto:siddhantsinghrajpoot91@gmail.com">
        <div><div class="label">EMAIL</div><div class="value">siddhantsinghrajpoot91@gmail...</div></div>
        <div style="color:var(--accent-1);">↗</div>
      </a>
    </div>
  </section>

  <footer>
    &copy; 2026 Siddhant Singh Rajpoot. All rights reserved.
  </footer>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
<script>
// ---------- Snake Cursor Trail ----------
const cursorContainer = document.getElementById('cursor-container');
const cursorDots = [];
const numDots = 12;

for (let i = 0; i < numDots; i++) {
  const dot = document.createElement('div');
  dot.classList.add('cursor-dot');
  // Make tail smaller and change color to fire orange
  dot.style.transform = `scale(${1 - i / numDots})`;
  dot.style.opacity = 1 - (i / numDots);
  if(i > 3) dot.style.background = 'var(--accent-fire)';
  cursorContainer.appendChild(dot);
  cursorDots.push({ el: dot, x: 0, y: 0 });
}

let mouseX = window.innerWidth / 2;
let mouseY = window.innerHeight / 2;

document.addEventListener('mousemove', (e) => {
  mouseX = e.clientX;
  mouseY = e.clientY;
});

function animateCursor() {
  let prevX = mouseX;
  let prevY = mouseY;

  cursorDots.forEach((dot, index) => {
    // Lerp (smooth follow) physics
    dot.x += (prevX - dot.x) * 0.3;
    dot.y += (prevY - dot.y) * 0.3;
    dot.el.style.left = `${dot.x}px`;
    dot.el.style.top = `${dot.y}px`;
    prevX = dot.x;
    prevY = dot.y;
  });
  requestAnimationFrame(animateCursor);
}
animateCursor();

// ---------- Procedural Web Audio API (Fire & Snake Hiss) ----------
let audioCtx;
let isAudioPlaying = false;

document.getElementById('soundToggle').addEventListener('click', function() {
  if (isAudioPlaying) {
    audioCtx.suspend();
    this.innerText = "🔇 Audio Paused";
    this.style.background = "var(--glass-bg)";
    isAudioPlaying = false;
    return;
  }
  
  if (!audioCtx) {
    audioCtx = new (window.AudioContext || window.webkitAudioContext)();
    
    // 1. Create Crackling Fire Sound (White Noise through modulated lowpass filter)
    const bufferSize = audioCtx.sampleRate * 2; // 2 seconds
    const noiseBuffer = audioCtx.createBuffer(1, bufferSize, audioCtx.sampleRate);
    const output = noiseBuffer.getChannelData(0);
    for (let i = 0; i < bufferSize; i++) {
      output[i] = Math.random() * 2 - 1;
    }
    const noise = audioCtx.createBufferSource();
    noise.buffer = noiseBuffer;
    noise.loop = true;
    
    const filter = audioCtx.createBiquadFilter();
    filter.type = 'lowpass';
    filter.frequency.value = 600;
    
    // LFO to create crackling distortion effect
    const lfo = audioCtx.createOscillator();
    lfo.type = 'square';
    lfo.frequency.value = 15;
    const lfoGain = audioCtx.createGain();
    lfoGain.gain.value = 400;
    
    lfo.connect(lfoGain);
    lfoGain.connect(filter.frequency);
    lfo.start();
    
    const masterGain = audioCtx.createGain();
    masterGain.gain.value = 0.08; // Keep it ambient
    
    noise.connect(filter);
    filter.connect(masterGain);
    masterGain.connect(audioCtx.destination);
    noise.start();

    // 2. Subtle High-Pitch Hiss (Snake)
    const hissFilter = audioCtx.createBiquadFilter();
    hissFilter.type = 'highpass';
    hissFilter.frequency.value = 4000;
    const hissGain = audioCtx.createGain();
    hissGain.gain.value = 0.02;
    
    const hissNoise = audioCtx.createBufferSource();
    hissNoise.buffer = noiseBuffer;
    hissNoise.loop = true;
    
    hissNoise.connect(hissFilter);
    hissFilter.connect(hissGain);
    hissGain.connect(audioCtx.destination);
    hissNoise.start();
  }
  
  audioCtx.resume();
  this.innerText = "🔥 Audio Playing";
  this.style.background = "var(--accent-fire)";
  this.style.color = "#fff";
  isAudioPlaying = true;
});


// ---------- Scroll Parallax ----------
const glow1 = document.getElementById('glow1');
const glow2 = document.getElementById('glow2');
const header = document.getElementById('header');

window.addEventListener('scroll', () => {
  const scrolled = window.scrollY;
  glow1.style.transform = `translateY(${scrolled * 0.4}px) rotate(${scrolled * 0.05}deg)`;
  glow2.style.transform = `translateY(${scrolled * 0.2}px) rotate(${-scrolled * 0.02}deg)`;
  header.style.padding = scrolled > 50 ? '10px 0' : '20px 0';
});

// ---------- Staggered Child Animations ----------
const revealEls = document.querySelectorAll('.reveal');
const revealIO = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (e.isIntersecting) { e.target.classList.add('in'); revealIO.unobserve(e.target); }
  });
}, { threshold: 0.1 });
revealEls.forEach(el => revealIO.observe(el));

const staggerContainers = document.querySelectorAll('.stagger-container');
const staggerIO = new IntersectionObserver((entries) => {
  entries.forEach(e => {
    if (e.isIntersecting) {
      const children = e.target.querySelectorAll('.stagger-item');
      children.forEach((child, index) => {
        setTimeout(() => { child.classList.add('in'); }, index * 100);
      });
      staggerIO.unobserve(e.target);
    }
  });
}, { threshold: 0.2 });
staggerContainers.forEach(container => staggerIO.observe(container));

// ---------- Number Counter Logic ----------
const counters = document.querySelectorAll('.stat-num');
const counterIO = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      const el = entry.target;
      const target = parseFloat(el.dataset.target);
      const suffix = el.dataset.suffix || '';
      let cur = 0;
      const step = target / 40;
      const tick = () => {
        cur += step;
        if (cur >= target) { el.textContent = target + suffix; }
        else { 
            el.textContent = (target % 1 !== 0 ? cur.toFixed(1) : Math.floor(cur)) + suffix; 
            requestAnimationFrame(tick); 
        }
      };
      tick();
      counterIO.unobserve(el);
    }
  });
}, { threshold: 0.4 });
counters.forEach(c => counterIO.observe(c));


// ---------- 3D Three.js: Core, Fire & Snakes ----------
(function initRealistic3D() {
  const canvas = document.getElementById('three-hero');
  if (!canvas || typeof THREE === 'undefined') return;

  const scene = new THREE.Scene();
  const camera = new THREE.PerspectiveCamera(45, 1, 0.1, 1000);
  camera.position.z = 30;

  const renderer = new THREE.WebGLRenderer({ canvas, alpha: true, antialias: true });
  renderer.setPixelRatio(Math.min(window.devicePixelRatio, 2));
  let rect = canvas.getBoundingClientRect();
  renderer.setSize(rect.width, rect.height);
  camera.aspect = rect.width / rect.height;
  camera.updateProjectionMatrix();

  // Lighting Setup
  const ambientLight = new THREE.AmbientLight(0xffffff, 1.5);
  scene.add(ambientLight);
  const directionalLight1 = new THREE.DirectionalLight(0x0d9488, 4); // Teal accent
  directionalLight1.position.set(10, 20, 15);
  scene.add(directionalLight1);
  const fireLight = new THREE.PointLight(0xff4500, 5, 50); // Fire glow from bottom
  fireLight.position.set(0, -10, 5);
  scene.add(fireLight);

  // Main Torus Knot Object
  const geometry = new THREE.TorusKnotGeometry(7, 2, 200, 32);
  const material = new THREE.MeshStandardMaterial({
    color: 0xffffff, metalness: 0.8, roughness: 0.15
  });
  const knotMesh = new THREE.Mesh(geometry, material);
  scene.add(knotMesh);

  // --- 1. Procedural 3D Slithering Snake ---
  const snakeSegments = [];
  const numSnakeNodes = 25;
  const snakeGeo = new THREE.SphereGeometry(0.7, 16, 16);
  const snakeMat = new THREE.MeshStandardMaterial({ color: 0x0d9488, metalness: 0.6, roughness: 0.1 });
  
  for (let i = 0; i < numSnakeNodes; i++) {
    const mesh = new THREE.Mesh(snakeGeo, snakeMat);
    // Taper the tail
    const scale = 1 - (i / numSnakeNodes) * 0.7;
    mesh.scale.set(scale, scale, scale);
    scene.add(mesh);
    snakeSegments.push(mesh);
  }

  // --- 2. 3D Fire Particle System ---
  const fireCount = 400;
  const fireGeometry = new THREE.BufferGeometry();
  const firePositions = new Float32Array(fireCount * 3);
  const fireLifetimes = new Float32Array(fireCount); // custom array to track fade out

  for (let i = 0; i < fireCount; i++) {
    firePositions[i * 3] = (Math.random() - 0.5) * 20; // x
    firePositions[i * 3 + 1] = -20 + Math.random() * 5; // y (start low)
    firePositions[i * 3 + 2] = (Math.random() - 0.5) * 10; // z
    fireLifetimes[i] = Math.random();
  }

  fireGeometry.setAttribute('position', new THREE.BufferAttribute(firePositions, 3));
  fireGeometry.setAttribute('lifetime', new THREE.BufferAttribute(fireLifetimes, 1));

  const fireMat = new THREE.PointsMaterial({
    color: 0xff4500, size: 0.5, transparent: true,
    opacity: 0.8, blending: THREE.AdditiveBlending, depthWrite: false
  });
  const fireParticles = new THREE.Points(fireGeometry, fireMat);
  scene.add(fireParticles);

  // Mouse Interaction Variables
  let targetX = 0, targetY = 0, mX = 0, mY = 0;
  const halfX = window.innerWidth / 2, halfY = window.innerHeight / 2;

  document.addEventListener('mousemove', (e) => {
    mX = (e.clientX - halfX) * 0.001;
    mY = (e.clientY - halfY) * 0.001;
  });

  window.addEventListener('resize', () => {
    const newRect = canvas.getBoundingClientRect();
    camera.aspect = newRect.width / newRect.height;
    camera.updateProjectionMatrix();
    renderer.setSize(newRect.width, newRect.height);
  });

  const clock = new THREE.Clock();
  
  function animate() {
    requestAnimationFrame(animate);
    const time = clock.getElapsedTime();

    // Rotate Main Knot
    knotMesh.rotation.y += 0.005;
    knotMesh.rotation.x += 0.002;
    knotMesh.position.y = Math.sin(time * 0.5) * 1.5;

    // Mouse Parallax for Main Object
    targetX = mX * 0.5; targetY = mY * 0.5;
    knotMesh.rotation.y += 0.05 * (targetX - knotMesh.rotation.y);
    knotMesh.rotation.x += 0.05 * (targetY - knotMesh.rotation.x);

    // --- Animate 3D Snake Slithering ---
    // Calculate new position for the head using sine/cosine waves mimicking wrapping
    const orbitRadius = 10;
    const snakeHeadX = Math.sin(time * 2) * orbitRadius;
    const snakeHeadY = Math.cos(time * 3) * 6 + knotMesh.position.y; // wave up and down
    const snakeHeadZ = Math.cos(time * 2) * orbitRadius;
    
    snakeSegments[0].position.set(snakeHeadX, snakeHeadY, snakeHeadZ);
    // Make body segments follow the leader
    for (let i = 1; i < numSnakeNodes; i++) {
      snakeSegments[i].position.lerp(snakeSegments[i-1].position, 0.35);
    }

    // --- Animate 3D Fire Particles ---
    const positions = fireGeometry.attributes.position.array;
    const lifetimes = fireGeometry.attributes.lifetime.array;

    for (let i = 0; i < fireCount; i++) {
      lifetimes[i] -= 0.015; // degrade life
      
      positions[i * 3 + 1] += 0.15; // move fire upwards
      positions[i * 3] += (Math.random() - 0.5) * 0.2; // flicker x
      
      // Reset particle to bottom if it dies
      if (lifetimes[i] < 0) {
        lifetimes[i] = 1.0;
        positions[i * 3] = (Math.random() - 0.5) * 15; // reset x
        positions[i * 3 + 1] = -15 + Math.random() * 2; // reset y (bottom)
      }
    }
    fireGeometry.attributes.position.needsUpdate = true;
    
    // Pulse fire light slightly
    fireLight.intensity = 5 + Math.sin(time * 15) * 1.5;

    renderer.render(scene, camera);
  }
  
  animate();
})();
</script>
</body>
</html>
