<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>GitHub Profile README Preview</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap');
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body { background: #0d1117; color: #c9d1d9; font-family: 'Inter', -apple-system, sans-serif; padding: 40px 20px; }
  .container { max-width: 860px; margin: 0 auto; }
  h1, h2, h3 { color: #f0f6fc; }
  h1 { font-size: 28px; text-align: center; margin: 20px 0; }
  h3 { font-size: 18px; margin: 30px 0 16px; border-bottom: 1px solid #21262d; padding-bottom: 10px; }
  hr { border: none; border-top: 1px solid #21262d; margin: 30px 0; }
  p, li { line-height: 1.7; font-size: 15px; }
  ul { padding-left: 24px; }
  a { color: #58a6ff; text-decoration: none; }
  a:hover { text-decoration: underline; }
  img { max-width: 100%; }
  .center { text-align: center; }
  .about-table { display: flex; gap: 30px; align-items: flex-start; }
  .about-text { flex: 1.4; }
  .about-gif { flex: 1; text-align: center; }
  .about-gif img { border-radius: 12px; width: 100%; }
  .orbit-wrapper { text-align: center; margin: 20px 0; }
  .orbit-wrapper svg { width: 90%; max-width: 750px; height: auto; display: inline-block; }
  .badge-row { display: flex; flex-wrap: wrap; gap: 8px; margin: 10px 0 20px; }
  .badge-row img { height: 28px; }
  details { margin-bottom: 12px; }
  summary { cursor: pointer; font-size: 16px; font-weight: 700; color: #f0f6fc; padding: 8px 0; }
  .projects-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
  .project-card { border: 1px solid #30363d; border-radius: 10px; padding: 20px; background: #161b22; }
  .project-card h4 { font-size: 16px; color: #f0f6fc; margin-bottom: 8px; }
  .project-card p { font-size: 13px; color: #8b949e; margin-bottom: 12px; line-height: 1.6; }
  .project-card a { font-weight: 700; font-size: 13px; }
  .stats-row { display: flex; flex-wrap: wrap; justify-content: center; gap: 16px; margin: 20px 0; }
  .stats-row img { height: 195px; border-radius: 8px; }
  .socials { display: flex; justify-content: center; gap: 12px; margin: 20px 0; }
  .socials img { height: 32px; }
</style>
</head>
<body>
<div class="container">

  <!-- BANNER -->
  <div class="center">
    <img src="https://myweb2002.w3spaces.com/New-PNC-Animated-Banners.gif" alt="Banner" style="border-radius:12px; width:100%;"/>
  </div>

  <h1>Hi 👋, I'm Prabhat Kumar Shah</h1>
  <p class="center" style="margin-bottom:30px;">
    <img src="https://readme-typing-svg.herokuapp.com?font=Outfit&size=24&duration=2500&pause=1000&color=00F2FE&center=true&vCenter=true&width=500&lines=Full+Stack+%26+GenAI+Engineer;Building+Smarter+AI+Workflows;Solving+DSA+in+C%2B%2B+%26+Python" alt="Typing SVG"/>
  </p>

  <!-- ABOUT -->
  <div class="about-table">
    <div class="about-text">
      <h3 style="border:none;padding:0;">💫 About Me</h3>
      <p>I am a passionate <b>Full Stack Web & Generative AI Developer</b> dedicated to building intelligent solutions, automated agentic pipelines, and interactive user interfaces.</p>
      <ul>
        <li>🔭 <b>Currently Working On:</b> Advanced GenAI solutions including RAG pipelines, LLMs, LangChain, and LangGraph.</li>
        <li>🌱 <b>Data Intelligence:</b> Learning NumPy, Pandas, Seaborn, Matplotlib.</li>
        <li>🎓 <b>Problem Solving:</b> Daily DSA practice for clean, optimized code.</li>
        <li>⚡ <b>Aspirations:</b> Acquiring new skills and building innovative products.</li>
      </ul>
    </div>
    <div class="about-gif">
      <img src="https://cdn.dribbble.com/users/730703/screenshots/6581243/avento.gif"/>
    </div>
  </div>

  <hr/>

  <!-- ORBIT -->
  <h3>🌌 Interactive Skill Orbit Map</h3>
  <div class="orbit-wrapper">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 600" width="800" height="600">
      <defs>
        <radialGradient id="cg" cx="50%" cy="50%" r="50%">
          <stop offset="0%" stop-color="#38bdf8"/>
          <stop offset="100%" stop-color="#6366f1"/>
        </radialGradient>
        <radialGradient id="bg" cx="50%" cy="50%" r="65%">
          <stop offset="0%" stop-color="#111827"/>
          <stop offset="100%" stop-color="#030712"/>
        </radialGradient>
        <filter id="gl">
          <feGaussianBlur stdDeviation="3" result="b"/>
          <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
        </filter>
        <filter id="gl2">
          <feGaussianBlur stdDeviation="5" result="b"/>
          <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
        </filter>
      </defs>

      <!-- Background -->
      <rect width="800" height="600" rx="16" ry="16" fill="url(#bg)"/>

      <!-- Stars -->
      <circle cx="55" cy="40" r="1.2" fill="#e2e8f0"><animate attributeName="opacity" values="0.1;0.7;0.1" dur="3s" repeatCount="indefinite"/></circle>
      <circle cx="745" cy="55" r="1.4" fill="#e2e8f0"><animate attributeName="opacity" values="0.15;0.8;0.15" dur="2.5s" repeatCount="indefinite"/></circle>
      <circle cx="150" cy="85" r="0.9" fill="#e2e8f0"><animate attributeName="opacity" values="0.1;0.5;0.1" dur="4s" repeatCount="indefinite"/></circle>
      <circle cx="680" cy="120" r="1.1" fill="#e2e8f0"><animate attributeName="opacity" values="0.2;0.65;0.2" dur="3.3s" repeatCount="indefinite"/></circle>
      <circle cx="90" cy="480" r="1.3" fill="#e2e8f0"><animate attributeName="opacity" values="0.1;0.6;0.1" dur="2.8s" repeatCount="indefinite"/></circle>
      <circle cx="720" cy="510" r="1" fill="#e2e8f0"><animate attributeName="opacity" values="0.15;0.55;0.15" dur="3.6s" repeatCount="indefinite"/></circle>
      <circle cx="200" cy="555" r="0.8" fill="#e2e8f0"><animate attributeName="opacity" values="0.1;0.45;0.1" dur="4.5s" repeatCount="indefinite"/></circle>
      <circle cx="600" cy="560" r="1.2" fill="#e2e8f0"><animate attributeName="opacity" values="0.2;0.7;0.2" dur="2.2s" repeatCount="indefinite"/></circle>
      <circle cx="400" cy="30" r="1" fill="#e2e8f0"><animate attributeName="opacity" values="0.1;0.6;0.1" dur="3.8s" repeatCount="indefinite"/></circle>
      <circle cx="50" cy="300" r="0.9" fill="#e2e8f0"><animate attributeName="opacity" values="0.15;0.5;0.15" dur="4.2s" repeatCount="indefinite"/></circle>
      <circle cx="760" cy="300" r="1.1" fill="#e2e8f0"><animate attributeName="opacity" values="0.1;0.55;0.1" dur="3.1s" repeatCount="indefinite"/></circle>
      <circle cx="300" cy="570" r="0.7" fill="#e2e8f0"><animate attributeName="opacity" values="0.2;0.4;0.2" dur="5s" repeatCount="indefinite"/></circle>

      <!-- RING 1: Inner (r=110) -->
      <g transform="translate(400,300)">
        <g><animateTransform attributeName="transform" type="rotate" from="0 0 0" to="360 0 0" dur="45s" repeatCount="indefinite"/>
          <circle r="110" fill="none" stroke="#38bdf8" stroke-width="0.8" stroke-dasharray="4 8" opacity="0.25"/>
        </g>
      </g>
      <!-- RING 2: Middle (r=185) -->
      <g transform="translate(400,300)">
        <g><animateTransform attributeName="transform" type="rotate" from="0 0 0" to="-360 0 0" dur="60s" repeatCount="indefinite"/>
          <circle r="185" fill="none" stroke="#a78bfa" stroke-width="1" stroke-dasharray="5 10" opacity="0.22"/>
        </g>
      </g>
      <!-- RING 3: Outer (r=260) -->
      <g transform="translate(400,300)">
        <g><animateTransform attributeName="transform" type="rotate" from="0 0 0" to="360 0 0" dur="80s" repeatCount="indefinite"/>
          <circle r="260" fill="none" stroke="#fb7185" stroke-width="1.2" stroke-dasharray="6 12" opacity="0.2"/>
        </g>
      </g>

      <!-- CORE -->
      <g transform="translate(400,300)" filter="url(#gl2)">
        <circle r="48" fill="url(#cg)" opacity="0.95"/>
        <circle r="56" fill="none" stroke="#38bdf8" stroke-width="1.2">
          <animate attributeName="r" values="56;64;56" dur="3s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.45;0.1;0.45" dur="3s" repeatCount="indefinite"/>
        </circle>
        <circle r="60" fill="none" stroke="#818cf8" stroke-width="0.6">
          <animate attributeName="r" values="62;72;62" dur="4.5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.25;0.03;0.25" dur="4.5s" repeatCount="indefinite"/>
        </circle>
        <text x="0" y="-4" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="16" font-weight="800" fill="#ffffff" letter-spacing="1.5">PRABHAT</text>
        <text x="0" y="16" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="9" font-weight="700" fill="#bae6fd" letter-spacing="3">SKILLS</text>
      </g>

      <!-- INNER ORBIT NODES (r=110, CW, 28s) -->
      <!-- DSA @ 0° -->
      <g transform="translate(400,300)"><g>
        <animateTransform attributeName="transform" type="rotate" from="0 0 0" to="360 0 0" dur="28s" repeatCount="indefinite"/>
        <g transform="translate(110,0)"><g>
          <animateTransform attributeName="transform" type="rotate" from="0 0 0" to="-360 0 0" dur="28s" repeatCount="indefinite"/>
          <rect x="-22" y="-14" width="44" height="28" rx="8" fill="#111827" stroke="#34d399" stroke-width="1.5" filter="url(#gl)"/>
          <text x="0" y="5" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="11" font-weight="700" fill="#34d399">DSA</text>
        </g></g>
      </g></g>
      <!-- C++ @ 120° -->
      <g transform="translate(400,300)"><g>
        <animateTransform attributeName="transform" type="rotate" from="120 0 0" to="480 0 0" dur="28s" repeatCount="indefinite"/>
        <g transform="translate(110,0)"><g>
          <animateTransform attributeName="transform" type="rotate" from="-120 0 0" to="-480 0 0" dur="28s" repeatCount="indefinite"/>
          <rect x="-22" y="-14" width="44" height="28" rx="8" fill="#111827" stroke="#38bdf8" stroke-width="1.5" filter="url(#gl)"/>
          <text x="0" y="5" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="11" font-weight="700" fill="#38bdf8">C++</text>
        </g></g>
      </g></g>
      <!-- SQL @ 240° -->
      <g transform="translate(400,300)"><g>
        <animateTransform attributeName="transform" type="rotate" from="240 0 0" to="600 0 0" dur="28s" repeatCount="indefinite"/>
        <g transform="translate(110,0)"><g>
          <animateTransform attributeName="transform" type="rotate" from="-240 0 0" to="-600 0 0" dur="28s" repeatCount="indefinite"/>
          <rect x="-22" y="-14" width="44" height="28" rx="8" fill="#111827" stroke="#22d3ee" stroke-width="1.5" filter="url(#gl)"/>
          <text x="0" y="5" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="11" font-weight="700" fill="#22d3ee">SQL</text>
        </g></g>
      </g></g>

      <!-- MIDDLE ORBIT NODES (r=185, CCW, 38s) -->
      <!-- React @ 0° -->
      <g transform="translate(400,300)"><g>
        <animateTransform attributeName="transform" type="rotate" from="0 0 0" to="-360 0 0" dur="38s" repeatCount="indefinite"/>
        <g transform="translate(185,0)"><g>
          <animateTransform attributeName="transform" type="rotate" from="0 0 0" to="360 0 0" dur="38s" repeatCount="indefinite"/>
          <rect x="-28" y="-14" width="56" height="28" rx="8" fill="#111827" stroke="#a78bfa" stroke-width="1.5" filter="url(#gl)"/>
          <text x="0" y="5" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="11" font-weight="700" fill="#a78bfa">React</text>
        </g></g>
      </g></g>
      <!-- Python @ 120° -->
      <g transform="translate(400,300)"><g>
        <animateTransform attributeName="transform" type="rotate" from="120 0 0" to="-240 0 0" dur="38s" repeatCount="indefinite"/>
        <g transform="translate(185,0)"><g>
          <animateTransform attributeName="transform" type="rotate" from="-120 0 0" to="240 0 0" dur="38s" repeatCount="indefinite"/>
          <rect x="-30" y="-14" width="60" height="28" rx="8" fill="#111827" stroke="#c084fc" stroke-width="1.5" filter="url(#gl)"/>
          <text x="0" y="5" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="11" font-weight="700" fill="#c084fc">Python</text>
        </g></g>
      </g></g>
      <!-- JavaScript @ 240° -->
      <g transform="translate(400,300)"><g>
        <animateTransform attributeName="transform" type="rotate" from="240 0 0" to="-120 0 0" dur="38s" repeatCount="indefinite"/>
        <g transform="translate(185,0)"><g>
          <animateTransform attributeName="transform" type="rotate" from="-240 0 0" to="120 0 0" dur="38s" repeatCount="indefinite"/>
          <rect x="-40" y="-14" width="80" height="28" rx="8" fill="#111827" stroke="#e879f9" stroke-width="1.5" filter="url(#gl)"/>
          <text x="0" y="5" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="11" font-weight="700" fill="#e879f9">JavaScript</text>
        </g></g>
      </g></g>

      <!-- OUTER ORBIT NODES (r=260, CW, 55s) -->
      <!-- LLMs @ 0° -->
      <g transform="translate(400,300)"><g>
        <animateTransform attributeName="transform" type="rotate" from="0 0 0" to="360 0 0" dur="55s" repeatCount="indefinite"/>
        <g transform="translate(260,0)"><g>
          <animateTransform attributeName="transform" type="rotate" from="0 0 0" to="-360 0 0" dur="55s" repeatCount="indefinite"/>
          <rect x="-26" y="-15" width="52" height="30" rx="9" fill="#111827" stroke="#fb7185" stroke-width="1.5" filter="url(#gl)"/>
          <text x="0" y="5" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="11" font-weight="700" fill="#fb7185">LLMs</text>
        </g></g>
      </g></g>
      <!-- RAG @ 72° -->
      <g transform="translate(400,300)"><g>
        <animateTransform attributeName="transform" type="rotate" from="72 0 0" to="432 0 0" dur="55s" repeatCount="indefinite"/>
        <g transform="translate(260,0)"><g>
          <animateTransform attributeName="transform" type="rotate" from="-72 0 0" to="-432 0 0" dur="55s" repeatCount="indefinite"/>
          <rect x="-22" y="-15" width="44" height="30" rx="9" fill="#111827" stroke="#f472b6" stroke-width="1.5" filter="url(#gl)"/>
          <text x="0" y="5" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="11" font-weight="700" fill="#f472b6">RAG</text>
        </g></g>
      </g></g>
      <!-- LangChain @ 144° -->
      <g transform="translate(400,300)"><g>
        <animateTransform attributeName="transform" type="rotate" from="144 0 0" to="504 0 0" dur="55s" repeatCount="indefinite"/>
        <g transform="translate(260,0)"><g>
          <animateTransform attributeName="transform" type="rotate" from="-144 0 0" to="-504 0 0" dur="55s" repeatCount="indefinite"/>
          <rect x="-40" y="-15" width="80" height="30" rx="9" fill="#111827" stroke="#fda4af" stroke-width="1.5" filter="url(#gl)"/>
          <text x="0" y="5" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="11" font-weight="700" fill="#fda4af">LangChain</text>
        </g></g>
      </g></g>
      <!-- LangGraph @ 216° -->
      <g transform="translate(400,300)"><g>
        <animateTransform attributeName="transform" type="rotate" from="216 0 0" to="576 0 0" dur="55s" repeatCount="indefinite"/>
        <g transform="translate(260,0)"><g>
          <animateTransform attributeName="transform" type="rotate" from="-216 0 0" to="-576 0 0" dur="55s" repeatCount="indefinite"/>
          <rect x="-42" y="-15" width="84" height="30" rx="9" fill="#111827" stroke="#ff7eb3" stroke-width="1.5" filter="url(#gl)"/>
          <text x="0" y="5" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="11" font-weight="700" fill="#ff7eb3">LangGraph</text>
        </g></g>
      </g></g>
      <!-- VectorDB @ 288° -->
      <g transform="translate(400,300)"><g>
        <animateTransform attributeName="transform" type="rotate" from="288 0 0" to="648 0 0" dur="55s" repeatCount="indefinite"/>
        <g transform="translate(260,0)"><g>
          <animateTransform attributeName="transform" type="rotate" from="-288 0 0" to="-648 0 0" dur="55s" repeatCount="indefinite"/>
          <rect x="-38" y="-15" width="76" height="30" rx="9" fill="#111827" stroke="#fca5a5" stroke-width="1.5" filter="url(#gl)"/>
          <text x="0" y="5" text-anchor="middle" font-family="Segoe UI,Arial,sans-serif" font-size="11" font-weight="700" fill="#fca5a5">VectorDB</text>
        </g></g>
      </g></g>
    </svg>
  </div>

  <hr/>

  <!-- TECH STACK -->
  <h3>🛠️ Tech Stack & Toolkit</h3>

  <details open>
    <summary>🧠 Generative AI & Large Language Models</summary>
    <div class="badge-row">
      <img src="https://img.shields.io/badge/LLMs-00F2FE?style=for-the-badge&logo=openai&logoColor=black"/>
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white"/>
      <img src="https://img.shields.io/badge/LangGraph-FF6F00?style=for-the-badge&logo=graph&logoColor=white"/>
      <img src="https://img.shields.io/badge/RAG_Pipeline-4FACFE?style=for-the-badge&logo=micro-strategy&logoColor=white"/>
      <img src="https://img.shields.io/badge/Vector_DB-00C9FF?style=for-the-badge&logo=databricks&logoColor=white"/>
    </div>
  </details>
  <details open>
    <summary>💻 Languages & Core CS</summary>
    <div class="badge-row">
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
      <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/DSA-00E676?style=for-the-badge&logo=hackerrank&logoColor=white"/>
    </div>
  </details>
  <details open>
    <summary>🌐 Frontend & Data Libraries</summary>
    <div class="badge-row">
      <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
      <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
      <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
    </div>
  </details>

  <hr/>

  <!-- PROJECTS -->
  <h3>🏆 Featured Projects</h3>
  <div class="projects-grid">
    <div class="project-card">
      <h4>⌁ Visual Pipeline Builder</h4>
      <p>A professional node-based workflow editor built on React Flow and FastAPI with dynamic handle rendering and DFS validation.</p>
      <div class="badge-row">
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      </div>
      <a href="https://github.com/Prabhat12112002/Pipeline-Builder">🔗 Repository →</a>
    </div>
    <div class="project-card">
      <h4>📄 Lease Assistant AI</h4>
      <p>An intelligent RAG lease advisor on Streamlit that searches documents and answers clause-level queries instantly.</p>
      <div class="badge-row">
        <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
        <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white"/>
        <img src="https://img.shields.io/badge/VectorDB-00D2FF?style=flat-square"/>
      </div>
      <a href="https://github.com/Prabhat12112002/Strealit_Lease_Agent">🔗 Repository →</a>
    </div>
    <div class="project-card">
      <h4>✉️ Email Automation Desktop App</h4>
      <p>A smart automation desktop dashboard that monitors mailbox activities, categorizes content, and auto-drafts replies.</p>
      <div class="badge-row">
        <img src="https://img.shields.io/badge/Desktop_App-333?style=flat-square"/>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
        <img src="https://img.shields.io/badge/LLMs-00F2FE?style=flat-square&logo=openai&logoColor=black"/>
      </div>
      <a href="https://github.com/Prabhat12112002/Email-automation-desktop-app">🔗 Repository →</a>
    </div>
    <div class="project-card">
      <h4>🔬 Pathological Image Classification</h4>
      <p>Deep learning classification framework targeting high-resolution pathological medical images to identify tissue anomalies.</p>
      <div class="badge-row">
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
        <img src="https://img.shields.io/badge/CNN-00599C?style=flat-square"/>
        <img src="https://img.shields.io/badge/Medical_AI-00E676?style=flat-square"/>
      </div>
      <a href="https://github.com/Prabhat12112002/Pathelogical-Image-Classification_final">🔗 Repository →</a>
    </div>
  </div>

  <hr/>

  <!-- STATS -->
  <h3>📊 GitHub Stats & Metrics</h3>
  <div class="stats-row">
    <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=Prabhat12112002&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="GitHub Stats"/>
    <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=Prabhat12112002&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top Languages"/>
  </div>
  <div class="stats-row">
    <img src="https://streak-stats.demolab.com?user=Prabhat12112002&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak"/>
  </div>

  <hr/>

  <!-- SOCIALS -->
  <h3>🌐 Connect & Collaborate</h3>
  <div class="socials">
    <a href="https://linkedin.com/in/prabhat-kumar-shah-8a8563162"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
    <a href="https://facebook.com/Prabhat12112002"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/></a>
    <a href="https://instagram.com/prabhat_shah12"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
  </div>

</div>
</body>
</html>
