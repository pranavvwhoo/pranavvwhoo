<!-- README.md — Single-file animated GitHub profile for Pranav D. Vaghela -->

<!-- ========== Inline Animated Banner (dark) ========== -->
<!-- This is an inline SVG — GitHub renders inline SVG in READMEs -->
<div align="center">
  <!-- Banner SVG -->
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 300" width="100%" style="max-width:1200px;">
    <defs>
      <linearGradient id="g1" x1="0" x2="1">
        <stop offset="0" stop-color="#071428"/>
        <stop offset="1" stop-color="#0ea5a5"/>
      </linearGradient>

      <!-- Glow filter -->
      <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>

    </defs>

    <!-- background -->
    <rect width="1200" height="300" fill="url(#g1)"/>

    <!-- left accent shapes -->
    <g opacity="0.06">
      <circle cx="1020" cy="40" r="120" fill="#fff"/>
      <rect x="60" y="20" width="260" height="160" rx="18" transform="rotate(-10 60 20)" fill="#fff"/>
    </g>

    <!-- main name -->
    <text x="80" y="120" font-family="Segoe UI, Roboto, sans-serif" font-size="52" fill="#ffffff" font-weight="700">Pranav D. Vaghela</text>

    <!-- animated "typing" subheading built as tspans that fade in sequentially -->
    <text x="80" y="165" font-family="Segoe UI, Roboto, sans-serif" font-size="22" fill="#e6fffa">
      <tspan id="s1" opacity="0">Full Stack Dev</tspan>
      <tspan id="sep1" dx="12" opacity="0"> • </tspan>
      <tspan id="s2" dx="6" opacity="0">ML</tspan>
      <tspan id="sep2" dx="12" opacity="0"> • </tspan>
      <tspan id="s3" dx="6" opacity="0">AI</tspan>
      <tspan id="sep3" dx="12" opacity="0"> • </tspan>
      <tspan id="s4" dx="6" opacity="0">Open Source</tspan>

      <!-- show each tspan in sequence -->
      <animate xlink:href="#s1" attributeName="opacity" from="0" to="1" begin="0.2s" dur="0.5s" fill="freeze" />
      <animate xlink:href="#sep1" attributeName="opacity" from="0" to="1" begin="0.8s" dur="0.2s" fill="freeze" />
      <animate xlink:href="#s2" attributeName="opacity" from="0" to="1" begin="1s" dur="0.5s" fill="freeze" />
      <animate xlink:href="#sep2" attributeName="opacity" from="0" to="1" begin="1.6s" dur="0.2s" fill="freeze" />
      <animate xlink:href="#s3" attributeName="opacity" from="0" to="1" begin="1.8s" dur="0.5s" fill="freeze" />
      <animate xlink:href="#sep3" attributeName="opacity" from="0" to="1" begin="2.4s" dur="0.2s" fill="freeze" />
      <animate xlink:href="#s4" attributeName="opacity" from="0" to="1" begin="2.6s" dur="0.6s" fill="freeze" />
    </text>

    <!-- a subtle animated accent line / progress -->
    <rect x="80" y="185" width="0" height="6" rx="3" fill="#7ef9f2" >
      <animate attributeName="width" from="0" to="520" begin="0.8s" dur="1.8s" fill="freeze" />
      <animate attributeName="opacity" from="0.2" to="0.95" begin="0.8s" dur="1.8s" fill="freeze"/>
    </rect>

    <!-- small card with contact -->
    <g transform="translate(820,60)">
      <rect x="0" y="0" rx="10" ry="10" width="320" height="120" fill="#0b1620" opacity="0.85" filter="url(#glow)"/>
      <text x="24" y="36" font-family="Segoe UI, Roboto, sans-serif" font-size="14" fill="#a7f3d0">📫 pranavvaghela2101@gmail.com</text>
      <text x="24" y="64" font-family="Segoe UI, Roboto, sans-serif" font-size="14" fill="#c7f0ec">📍 Goregaon (West)</text>
      <a href="https://www.linkedin.com/in/pranav-vaghela-ba8b20244/" target="_blank">
        <text x="24" y="92" font-family="Segoe UI, Roboto, sans-serif" font-size="13" fill="#93f0e6">LinkedIn ↗</text>
      </a>
    </g>
  </svg>
</div>

<!-- ========== Name + Waving Hand (inline animated SVG) ========== -->
<h1 align="center" style="margin-top: 18px;">
  Hi 👋, I'm <strong>Pranav Vaghela</strong>
  <!-- inline waving hand svg -->
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 120 120" width="28" height="28" style="vertical-align:middle; margin-left:6px;">
    <g>
      <circle cx="60" cy="60" r="56" fill="#0f172a" />
      <g transform="translate(24,20)">
        <!-- stylized hand -->
        <path id="hand" d="M14 44 C 22 12, 48 12, 54 44 L54 58 C46 68, 22 70, 14 58 Z" fill="#ffcc00"/>
        <!-- wave rotation -->
        <animateTransform xlink:href="#hand" attributeName="transform" attributeType="XML" type="rotate"
                          from="-12 40 45" to="12 40 45" dur="0.9s" repeatCount="indefinite"/>
      </g>
    </g>
  </svg>
</h1>

<p align="center">🚀 Passionate Full Stack Developer • ML Enthusiast • Building products that scale</p>

---

<!-- ========== Badges (static external images — common in READMEs) ========== -->
<p align="center">
  <img src="https://img.shields.io/badge/Status-Open%20to%20work-0ea5a5" alt="status" />
  <img src="https://img.shields.io/badge/GPA-9.18-ffb703" alt="gpa" />
  <img src="https://img.shields.io/badge/Topper-Diploma-06b6d4" alt="diploma" />
  <img src="https://img.shields.io/github/followers/pranavvwhoo?label=Follow&style=social" alt="follow" />
</p>

---

### 🔭 About me
- 🎓 B.Tech (Computer Engineering), D. J. Sanghavi College of Engineering (CGPA: **9.18**).  
- 🏆 Diploma: **94.33%** from Shri Bhagubhai Mafatlal Polytechnic (President of Math Club).  
- 💼 Web Developer at **Mavericks Racing (TCET)** — built the team’s full-stack website (React, Tailwind, TypeScript, Express).  
- 🤖 Interested in **ML, AI, Full Stack**, and building product-focused open-source projects.

---

### 💼 Experience (highlights)
- **Web Developer — Mavericks Racing (TCET)** (May 2024 – Present)  
  Built the official team website, optimized performance and real-time updates.  
  Live: https://mavericksracing.netlify.app

- **Machine Learning Engineer — Prerak Shah** (May 2023 – Jul 2023)  
  Sales forecasting across multiple categories.

- **Python Developer — Zentechs** (Dec 2023 – Jan 2024)  
  Built a web scraper for an e-commerce book site.

---

### 🏆 Achievements
- 🥈 1st Runner Up — TechVanza ’25 Hackathon  
- 🏅 Top 8 — VJTI CodeOdyssey TechnoVanza ’24  
- 💡 Technical paper presentation — Tech Fair ’24

---

### 🚀 Featured Projects
- **HealthBuddy** — Healthcare app (appointments, lab tests, AI chatbot).  
  Repo: https://github.com/CodeCrusaderr/healthbuddy

- **Mavericks Racing Official Website** — React + Tailwind + Express.  
  Live: https://mavericksracing.netlify.app

- **Demand Sales Forecasting** — ML pipeline for demand prediction.  
  Repo: https://github.com/pranavvwhoo/Demand-Sales-Forecasting

- **FuelFrenzy** — Stock market simulation platform.  
  Repo: https://github.com/pranavvwhoo/FuelFrenzy

---

### 🛠 Tech & Tools
C++ · Java · Python · JavaScript · TypeScript · React · Node.js · Express · Tailwind · Flutter · Dart · Firebase · Supabase · Postgres · NumPy · pandas · scikit-learn · Matplotlib · OpenAI / LLMs

---

### 📊 GitHub & Activity
<p align="center">
  <!-- Stats cards (external images from services) — make sure the username is correct -->
  <img src="https://github-readme-stats.vercel.app/api?username=pranavvwhoo&show_icons=true&theme=tokyonight" alt="github-stats" width="48%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=pranavvwhoo&theme=tokyonight" alt="streak" width="48%"/>
</p>

---

### 📫 Connect
- Email: [pranavvaghela2101@gmail.com](mailto:pranavvaghela2101@gmail.com)  
- LinkedIn: https://www.linkedin.com/in/pranav-vaghela-ba8b20244/  
- GitHub: https://github.com/pranavvwhoo

---

<p align="center">✨ <em>Building tech that matters — one repo at a time.</em> ✨</p>

<!-- End of README.md -->
