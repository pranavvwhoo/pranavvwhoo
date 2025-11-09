<!-- README.md — Single-file profile with per-character typewriter SVG animation -->

<div align="center">

<!-- ================= Animated Dark Banner (per-character typewriter subtitle) ================= -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 340" width="100%" style="max-width:1200px;">
  <defs>
    <linearGradient id="g1" x1="0" x2="1">
      <stop offset="0" stop-color="#071428"/>
      <stop offset="1" stop-color="#0ea5a5"/>
    </linearGradient>

    <filter id="soft" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>

    <!-- cursor rectangle used for blinking effect -->
    <linearGradient id="cursorGrad" x1="0" x2="0">
      <stop offset="0" stop-color="#7ef9f2"/>
      <stop offset="1" stop-color="#6de4d9"/>
    </linearGradient>
  </defs>

  <!-- background -->
  <rect width="1200" height="340" fill="url(#g1)"/>

  <!-- name -->
  <text x="80" y="128" font-family="Segoe UI, Roboto, Inter, sans-serif" font-size="56" fill="#ffffff" font-weight="700">
    Pranav D. Vaghela
  </text>

  <!-- typing subtitle group -->
  <!-- We'll render each character as a separate <tspan> with incremental animation begin times -->
  <g transform="translate(80, 180)">
    <text font-family="Segoe UI, Roboto, Inter, sans-serif" font-size="22" fill="#e6fffa">
      <!-- We'll display the typed characters here. Each tspan is positioned via dx -->
      <!-- Phrase to type: "Full Stack Dev • ML • AI • Open Source" -->
      <!-- We construct tspans with relative dx spacing of 0 or 6 to keep monospace-like spacing -->
      <!-- Characters are grouped; adjust dx for spacing between characters and words -->

      <!-- F u l l -->
      <tspan id="c0" opacity="0">F</tspan><tspan id="c1" opacity="0" dx="6">u</tspan>
      <tspan id="c2" opacity="0" dx="6">l</tspan><tspan id="c3" opacity="0" dx="6">l</tspan>
      <tspan id="c4" opacity="0" dx="12"> </tspan>

      <!-- S t a c k -->
      <tspan id="c5" opacity="0" dx="6">S</tspan><tspan id="c6" opacity="0" dx="6">t</tspan>
      <tspan id="c7" opacity="0" dx="6">a</tspan><tspan id="c8" opacity="0" dx="6">c</tspan>
      <tspan id="c9" opacity="0" dx="6">k</tspan>
      <tspan id="c10" opacity="0" dx="12"> </tspan>

      <!-- D e v -->
      <tspan id="c11" opacity="0" dx="6">D</tspan><tspan id="c12" opacity="0" dx="6">e</tspan>
      <tspan id="c13" opacity="0" dx="6">v</tspan>
      <tspan id="c14" opacity="0" dx="12"> </tspan>

      <!-- • -->
      <tspan id="c15" opacity="0" dx="6">•</tspan>
      <tspan id="c16" opacity="0" dx="12"> </tspan>

      <!-- M L -->
      <tspan id="c17" opacity="0" dx="6">M</tspan><tspan id="c18" opacity="0" dx="6">L</tspan>
      <tspan id="c19" opacity="0" dx="12"> </tspan>

      <!-- • -->
      <tspan id="c20" opacity="0" dx="6">•</tspan>
      <tspan id="c21" opacity="0" dx="12"> </tspan>

      <!-- A I -->
      <tspan id="c22" opacity="0" dx="6">A</tspan><tspan id="c23" opacity="0" dx="6">I</tspan>
      <tspan id="c24" opacity="0" dx="12"> </tspan>

      <!-- • -->
      <tspan id="c25" opacity="0" dx="6">•</tspan>
      <tspan id="c26" opacity="0" dx="12"> </tspan>

      <!-- O p e n   S o u r c e -->
      <tspan id="c27" opacity="0" dx="6">O</tspan><tspan id="c28" opacity="0" dx="6">p</tspan>
      <tspan id="c29" opacity="0" dx="6">e</tspan><tspan id="c30" opacity="0" dx="6">n</tspan>
      <tspan id="c31" opacity="0" dx="8"> </tspan>
      <tspan id="c32" opacity="0" dx="6">S</tspan><tspan id="c33" opacity="0" dx="6">o</tspan>
      <tspan id="c34" opacity="0" dx="6">u</tspan><tspan id="c35" opacity="0" dx="6">r</tspan>
      <tspan id="c36" opacity="0" dx="6">c</tspan><tspan id="c37" opacity="0" dx="6">e</tspan>
    </text>

    <!-- animate each character's opacity in sequence to create typing -->
    <!-- base delay between characters -->
    <animate xlink:href="#c0" attributeName="opacity" from="0" to="1" begin="0.20s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c1" attributeName="opacity" from="0" to="1" begin="0.28s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c2" attributeName="opacity" from="0" to="1" begin="0.36s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c3" attributeName="opacity" from="0" to="1" begin="0.44s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c4" attributeName="opacity" from="0" to="1" begin="0.52s" dur="0.02s" fill="freeze"/>

    <animate xlink:href="#c5" attributeName="opacity" from="0" to="1" begin="0.62s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c6" attributeName="opacity" from="0" to="1" begin="0.70s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c7" attributeName="opacity" from="0" to="1" begin="0.78s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c8" attributeName="opacity" from="0" to="1" begin="0.86s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c9" attributeName="opacity" from="0" to="1" begin="0.94s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c10" attributeName="opacity" from="0" to="1" begin="1.02s" dur="0.02s" fill="freeze"/>

    <animate xlink:href="#c11" attributeName="opacity" from="0" to="1" begin="1.12s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c12" attributeName="opacity" from="0" to="1" begin="1.20s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c13" attributeName="opacity" from="0" to="1" begin="1.28s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c14" attributeName="opacity" from="0" to="1" begin="1.36s" dur="0.02s" fill="freeze"/>

    <animate xlink:href="#c15" attributeName="opacity" from="0" to="1" begin="1.46s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c16" attributeName="opacity" from="0" to="1" begin="1.54s" dur="0.02s" fill="freeze"/>

    <animate xlink:href="#c17" attributeName="opacity" from="0" to="1" begin="1.62s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c18" attributeName="opacity" from="0" to="1" begin="1.70s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c19" attributeName="opacity" from="0" to="1" begin="1.78s" dur="0.02s" fill="freeze"/>

    <animate xlink:href="#c20" attributeName="opacity" from="0" to="1" begin="1.88s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c21" attributeName="opacity" from="0" to="1" begin="1.96s" dur="0.02s" fill="freeze"/>

    <animate xlink:href="#c22" attributeName="opacity" from="0" to="1" begin="2.04s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c23" attributeName="opacity" from="0" to="1" begin="2.12s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c24" attributeName="opacity" from="0" to="1" begin="2.20s" dur="0.02s" fill="freeze"/>

    <animate xlink:href="#c25" attributeName="opacity" from="0" to="1" begin="2.30s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c26" attributeName="opacity" from="0" to="1" begin="2.38s" dur="0.02s" fill="freeze"/>

    <animate xlink:href="#c27" attributeName="opacity" from="0" to="1" begin="2.46s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c28" attributeName="opacity" from="0" to="1" begin="2.54s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c29" attributeName="opacity" from="0" to="1" begin="2.62s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c30" attributeName="opacity" from="0" to="1" begin="2.70s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c31" attributeName="opacity" from="0" to="1" begin="2.78s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c32" attributeName="opacity" from="0" to="1" begin="2.86s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c33" attributeName="opacity" from="0" to="1" begin="2.94s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c34" attributeName="opacity" from="0" to="1" begin="3.02s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c35" attributeName="opacity" from="0" to="1" begin="3.10s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c36" attributeName="opacity" from="0" to="1" begin="3.18s" dur="0.02s" fill="freeze"/>
    <animate xlink:href="#c37" attributeName="opacity" from="0" to="1" begin="3.26s" dur="0.02s" fill="freeze"/>

    <!-- blinking cursor positioned after the last character -->
    <rect x="540" y="-16" width="8" height="26" rx="2" fill="url(#cursorGrad)">
      <animate attributeName="opacity" values="0;1;0;1" dur="1s" begin="3.26s" repeatCount="indefinite" />
    </rect>

  </g>

  <!-- contact card on the right -->
  <g transform="translate(820,40)" filter="url(#soft)">
    <rect x="0" y="0" rx="12" width="340" height="140" fill="#071828" opacity="0.9"/>
    <text x="24" y="36" font-family="Segoe UI, Roboto, Inter, sans-serif" font-size="14" fill="#a7f3d0">📫 pranavvaghela2101@gmail.com</text>
    <text x="24" y="64" font-family="Segoe UI, Roboto, Inter, sans-serif" font-size="14" fill="#c7f0ec">📍 Goregaon (West)</text>
    <a href="https://www.linkedin.com/in/pranav-vaghela-ba8b20244/" target="_blank">
      <text x="24" y="96" font-family="Segoe UI, Roboto, Inter, sans-serif" font-size="13" fill="#93f0e6">LinkedIn ↗</text>
    </a>
  </g>

</svg>

</div>

<!-- ================= Name + Animated Waving Hand ================= -->
<h1 align="center" style="margin-top: 18px;">
  Hi 👋, I'm <strong>Pranav Vaghela</strong>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 120 120" width="28" height="28" style="vertical-align:middle; margin-left:6px;">
    <g>
      <circle cx="60" cy="60" r="56" fill="#0f172a" />
      <g transform="translate(24,20)">
        <path id="hand" d="M14 44 C 22 12, 48 12, 54 44 L54 58 C46 68, 22 70, 14 58 Z" fill="#ffcc00"/>
        <animateTransform xlink:href="#hand" attributeName="transform" attributeType="XML" type="rotate"
                          from="-12 40 45" to="12 40 45" dur="0.9s" repeatCount="indefinite"/>
      </g>
    </g>
  </svg>
</h1>

<p align="center">🚀 Passionate Full Stack Developer • ML Enthusiast • Building products that scale</p>

---

### 🔧 Quick Summary
- Paste this file into `README.md` of your profile repo (`/USERNAME/USERNAME`).
- The SVG typing animation runs using inline `<animate>` elements — no external JS or CSS required.
- If you want the typing speed slower/faster, tell me and I’ll adjust the `begin` times and the cursor timing.

---

### 📌 Tip
If you ever want the typed phrase changed (or multiple lines typed sequentially), tell me what exact text to animate and whether you want pauses or loops — I’ll update the file and provide a fresh copy.

---

**Done ✅** — paste it, commit, and check your profile page: `https://github.com/pranavvwhoo` (it should show the new animated banner and typing subtitle).
