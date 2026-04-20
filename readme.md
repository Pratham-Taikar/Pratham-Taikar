<div align="center">

<!-- HEADER SVG -->
<svg width="100%" height="220" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 220">
  <defs>
    <linearGradient id="hbg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   style="stop-color:#0d0221"/>
      <stop offset="50%"  style="stop-color:#0a0a0a"/>
      <stop offset="100%" style="stop-color:#1a0533"/>
    </linearGradient>
    <filter id="hglow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <style>
      .h-mc { font-family:'Courier New',monospace; font-size:13px; fill:#8A2BE2; opacity:0; }
      .h-mc.h-fast { animation:h-fall 2.5s linear infinite; }
      .h-mc.h-mid  { animation:h-fall 3.8s linear infinite; }
      .h-mc.h-slow { animation:h-fall 5.2s linear infinite; }
      @keyframes h-fall {
        0%   { transform:translateY(-30px); opacity:0; }
        10%  { opacity:0.9; }
        90%  { opacity:0.4; }
        100% { transform:translateY(240px); opacity:0; }
      }
      .h-nm {
        font-family:'Courier New',monospace; font-size:46px;
        font-weight:900; fill:#ffffff; filter:url(#hglow); letter-spacing:4px;
      }
      .h-rl {
        font-family:'Courier New',monospace; font-size:15px;
        fill:#8A2BE2; letter-spacing:5px; filter:url(#hglow);
      }
      .h-cur { fill:#00ffff; animation:h-blink 0.8s step-end infinite; filter:url(#hglow); }
      @keyframes h-blink { 50% { opacity:0; } }
      .h-nl { stroke:#8A2BE2; stroke-width:1; fill:none; opacity:0; animation:h-pulse 3s ease-in-out infinite; }
      @keyframes h-pulse { 0%,100%{opacity:0.08;} 50%{opacity:0.5;} }
      .h-dot { fill:#8A2BE2; animation:h-twinkle 2s ease-in-out infinite; }
      @keyframes h-twinkle { 0%,100%{opacity:0.1;} 50%{opacity:1;} }
      .h-gr { font-family:'Courier New',monospace; font-size:46px; font-weight:900; letter-spacing:4px; }
      .h-gr-r { fill:#ff003c; opacity:0; animation:h-gr 4s infinite; }
      .h-gr-b { fill:#00ffff; opacity:0; animation:h-gb 4s infinite; }
      @keyframes h-gr { 0%,89%,91%,100%{opacity:0;transform:translate(0,0);} 90%{opacity:0.5;transform:translate(-4px,1px);} }
      @keyframes h-gb { 0%,87%,89%,100%{opacity:0;transform:translate(0,0);} 88%{opacity:0.5;transform:translate(4px,-1px);} }
      .h-sl { fill:rgba(138,43,226,0.06); animation:h-scan 3s linear infinite; }
      @keyframes h-scan { 0%{transform:translateY(-20px);} 100%{transform:translateY(240px);} }
    </style>
  </defs>
  <rect width="1200" height="220" fill="url(#hbg)"/>
  <line x1="0" y1="55"  x2="1200" y2="55"  class="h-nl" style="animation-delay:0s"/>
  <line x1="0" y1="110" x2="1200" y2="110" class="h-nl" style="animation-delay:1s"/>
  <line x1="0" y1="165" x2="1200" y2="165" class="h-nl" style="animation-delay:2s"/>
  <line x1="300" y1="0" x2="300" y2="220"  class="h-nl" style="animation-delay:0.5s"/>
  <line x1="600" y1="0" x2="600" y2="220"  class="h-nl" style="animation-delay:1.5s"/>
  <line x1="900" y1="0" x2="900" y2="220"  class="h-nl" style="animation-delay:2.5s"/>
  <text x="40"   class="h-mc h-fast" style="animation-delay:0.1s">01</text>
  <text x="80"   class="h-mc h-slow" style="animation-delay:0.8s">10</text>
  <text x="120"  class="h-mc h-mid"  style="animation-delay:0.3s">11</text>
  <text x="160"  class="h-mc h-fast" style="animation-delay:1.2s">00</text>
  <text x="200"  class="h-mc h-slow" style="animation-delay:0.6s">01</text>
  <text x="950"  class="h-mc h-fast" style="animation-delay:0.4s">10</text>
  <text x="990"  class="h-mc h-mid"  style="animation-delay:1.0s">01</text>
  <text x="1030" class="h-mc h-slow" style="animation-delay:0.2s">11</text>
  <text x="1070" class="h-mc h-fast" style="animation-delay:1.5s">00</text>
  <text x="1110" class="h-mc h-mid"  style="animation-delay:0.7s">10</text>
  <circle cx="260"  cy="40"  r="1.5" class="h-dot" style="animation-delay:0.3s"/>
  <circle cx="500"  cy="20"  r="1.5" class="h-dot" style="animation-delay:1.1s"/>
  <circle cx="700"  cy="190" r="1.5" class="h-dot" style="animation-delay:0.7s"/>
  <circle cx="940"  cy="35"  r="1.5" class="h-dot" style="animation-delay:1.8s"/>
  <circle cx="1150" cy="150" r="1.5" class="h-dot" style="animation-delay:0.5s"/>
  <circle cx="80"   cy="180" r="1.5" class="h-dot" style="animation-delay:2.2s"/>
  <rect width="1200" height="4" class="h-sl"/>
  <text x="600" y="115" text-anchor="middle" class="h-gr h-gr-r">PRATHAM TAIKAR</text>
  <text x="600" y="115" text-anchor="middle" class="h-gr h-gr-b">PRATHAM TAIKAR</text>
  <text x="600" y="115" text-anchor="middle" class="h-nm">PRATHAM TAIKAR</text>
  <text x="898" y="115" class="h-nm h-cur" font-size="46px">_</text>
  <text x="600" y="155" text-anchor="middle" class="h-rl">&lt; FULL STACK WEB DEVELOPER / SDE &gt;</text>
  <rect x="200" y="178" width="800" height="2" rx="1" fill="#8A2BE2" opacity="0.5" filter="url(#hglow)"/>
</svg>

<!-- Profile Views Badge -->
<img src="https://komarev.com/ghpvc/?username=Pratham-Taikar&label=Profile%20Views&color=blueviolet&style=for-the-badge" alt="Profile Views" />
<img src="https://img.shields.io/github/followers/Pratham-Taikar?label=Followers&style=for-the-badge&color=blueviolet" />

</div>

---

<!-- About Me Section -->
<img align="right" alt="Rocket" width="380" src="https://user-images.githubusercontent.com/74038190/216649426-0c2ee152-84d8-4707-85c4-27a378d2f78a.gif" />

### 🧑‍💻 About Me

```yaml
Name       : Pratham Pravin Taikar
Role       : Full Stack Web Developer / SDE
Location   : Pune, India 📍
Languages  : English | Hindi | Marathi
Education  : B.Tech in IT @ VIT Pune (2024-2028)
Interests  : Web Dev | System Design | DSA
Contact    : prathamtaikar26@gmail.com
```

- 🔭 Currently exploring full-stack web development and scalable web applications.
- 🌱 Leveling up in **Next.js**, **TypeScript**, and backend architecture.
- 💡 Passionate about clean code, problem-solving, and sharing technical insights.
- 🏆 Active on **LeetCode** and **GeeksForGeeks**.
- 💬 Ask me about **Full Stack Dev**, **React**, **Node.js** & **C++**.
- ⚡ Fun fact: I debug with `console.log` and I'm proud of it 😄

<br clear="right"/>

---

<!-- Connect Section -->
## <img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" width="30" /> Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pratham-taikar/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prathamtaikar26@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/frustratedOutcast/)
[![GeeksForGeeks](https://img.shields.io/badge/GeeksForGeeks-0F9D58?style=for-the-badge&logo=geeksforgeeks&logoColor=white)](https://www.geeksforgeeks.org/profile/pratham15/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Pratham-Taikar)

</div>

---

<!-- Skills Section -->
## <img src="https://user-images.githubusercontent.com/74038190/212257467-871d32b7-e401-42e8-a166-fcfd7baa4c6b.gif" width="30" /> Tech Stack & Skills

### 🖥️ Languages
<div align="center">

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

</div>

### ⚛️ Frontend
<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logo=react&logoColor=white)

</div>

### 🔧 Backend
<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

</div>

### 🗄️ Databases
<div align="center">

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

</div>

### 🛠️ Tools & Platforms
<div align="center">

![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-121011?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white)

</div>

---

<!-- GitHub Stats -->
## <img src="https://user-images.githubusercontent.com/74038190/216121986-1c9f3b0e-d083-4abc-b456-af4df10dd448.png" width="30" /> GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Pratham-Taikar&show_icons=true&theme=midnight-purple&hide_border=true&include_all_commits=true" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=Pratham-Taikar&theme=midnight-purple&hide_border=true" />

<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Pratham-Taikar&layout=compact&theme=midnight-purple&hide_border=true&langs_count=8" />

</div>

<!-- Activity Graph -->
### 📈 Contribution Graph
<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Pratham-Taikar&bg_color=0d1117&color=9b59b6&line=8a2be2&point=ffffff&area=true&hide_border=true)](https://github.com/Pratham-Taikar)

</div>

<!-- Snake Animation -->
### 🐍 Contribution Snake
<div align="center">

![Snake animation](https://github.com/Pratham-Taikar/Pratham-Taikar/blob/output/github-contribution-grid-snake-dark.svg)

</div>

---

<!-- SNEAKY ROBOT -->
<div align="left">
<svg width="420" height="130" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 420 130">
  <defs>
    <filter id="r-glow">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <style>
      .r-body { animation: r-sneak 8s ease-in-out infinite; }
      @keyframes r-sneak {
        0%   { transform: translateX(-200px); }
        20%  { transform: translateX(0px); }
        75%  { transform: translateX(0px); }
        100% { transform: translateX(-200px); }
      }
      .r-eye-blink {
        animation: r-blink 8s ease-in-out infinite;
        transform-origin: inherit;
      }
      @keyframes r-blink {
        0%,15%,17%,40%,42%,74%,76%,100% { transform: scaleY(1); }
        16%,41%,75% { transform: scaleY(0.05); }
      }
      .r-eyeball-l { animation: r-lookL 8s ease-in-out infinite; }
      .r-eyeball-r { animation: r-lookR 8s ease-in-out infinite; }
      @keyframes r-lookL {
        0%,20%   { transform: translate(0,0); }
        30%      { transform: translate(2px,-1px); }
        45%      { transform: translate(-2px,1px); }
        60%      { transform: translate(0,-2px); }
        75%,100% { transform: translate(0,0); }
      }
      @keyframes r-lookR {
        0%,20%   { transform: translate(0,0); }
        30%      { transform: translate(2px,-1px); }
        45%      { transform: translate(-2px,1px); }
        60%      { transform: translate(0,-2px); }
        75%,100% { transform: translate(0,0); }
      }
      .r-antenna { animation: r-antPulse 1.2s ease-in-out infinite; filter: url(#r-glow); }
      @keyframes r-antPulse {
        0%,100% { fill:#ff003c; opacity:0.8; }
        50%     { fill:#ff6680; opacity:1; }
      }
      .r-arm { transform-origin: 10px 5px; animation: r-wave 8s ease-in-out infinite; }
      @keyframes r-wave {
        0%,19%,76%,100% { transform: rotate(0deg); }
        25% { transform: rotate(-30deg); }
        35% { transform: rotate(10deg); }
        45% { transform: rotate(-25deg); }
        55% { transform: rotate(10deg); }
        65% { transform: rotate(-15deg); }
        75% { transform: rotate(0deg); }
      }
      .r-leg-l { transform-origin: 5px 0px; animation: r-legL 0.5s ease-in-out infinite; }
      .r-leg-r { transform-origin: 5px 0px; animation: r-legR 0.5s ease-in-out 0.25s infinite; }
      @keyframes r-legL { 0%,100%{transform:rotate(0deg);} 50%{transform:rotate(15deg);} }
      @keyframes r-legR { 0%,100%{transform:rotate(0deg);} 50%{transform:rotate(-15deg);} }
      .r-puff { animation: r-puffOut 1.5s ease-out infinite; fill:#8A2BE2; opacity:0; }
      .r-puff.p2 { animation-delay:0.5s; }
      .r-puff.p3 { animation-delay:1s; }
      @keyframes r-puffOut {
        0%   { transform:translate(0,0) scale(0.5); opacity:0.7; }
        100% { transform:translate(-18px,-20px) scale(1.5); opacity:0; }
      }
      .r-bubble { animation: r-popBubble 8s ease-in-out infinite; opacity:0; }
      @keyframes r-popBubble {
        0%,28%,74%,100% { opacity:0; transform:scale(0.5); }
        35%,65%         { opacity:1; transform:scale(1); }
      }
      .r-screen { animation: r-flicker 0.8s step-end infinite; fill:#00ffff; }
      @keyframes r-flicker { 50%{opacity:0;} }
    </style>
  </defs>

  <g class="r-body" filter="url(#r-glow)">
    <circle cx="18" cy="88" r="5" class="r-puff"/>
    <circle cx="14" cy="85" r="4" class="r-puff p2"/>
    <circle cx="16" cy="83" r="3" class="r-puff p3"/>
    <g class="r-leg-l" transform="translate(55,105)">
      <rect x="0" y="0" width="10" height="22" rx="4" fill="#3a0080"/>
      <rect x="0" y="18" width="14" height="6" rx="3" fill="#5500bb"/>
    </g>
    <g class="r-leg-r" transform="translate(75,105)">
      <rect x="0" y="0" width="10" height="22" rx="4" fill="#3a0080"/>
      <rect x="0" y="18" width="14" height="6" rx="3" fill="#5500bb"/>
    </g>
    <rect x="40" y="60" width="60" height="50" rx="8" fill="#1a0533" stroke="#8A2BE2" stroke-width="1.5"/>
    <rect x="52" y="72" width="36" height="22" rx="4" fill="#0d0221" stroke="#00ffff" stroke-width="1"/>
    <text x="57" y="87" font-family="Courier New" font-size="9" class="r-screen">&lt;/dev&gt;</text>
    <circle cx="47" cy="67" r="2" fill="#8A2BE2" opacity="0.7"/>
    <circle cx="93" cy="67" r="2" fill="#8A2BE2" opacity="0.7"/>
    <g class="r-arm" transform="translate(100,68)">
      <rect x="0" y="0" width="22" height="9" rx="4" fill="#3a0080" stroke="#8A2BE2" stroke-width="1"/>
      <circle cx="22" cy="4.5" r="5" fill="#5500bb" stroke="#8A2BE2" stroke-width="1"/>
    </g>
    <rect x="18" y="68" width="22" height="9" rx="4" fill="#3a0080" stroke="#8A2BE2" stroke-width="1"/>
    <circle cx="18" cy="72.5" r="5" fill="#5500bb" stroke="#8A2BE2" stroke-width="1"/>
    <rect x="62" y="50" width="16" height="12" rx="3" fill="#2a0060" stroke="#8A2BE2" stroke-width="1"/>
    <rect x="42" y="16" width="56" height="38" rx="10" fill="#1a0533" stroke="#8A2BE2" stroke-width="2"/>
    <rect x="52" y="25" width="18" height="14" rx="5" fill="#0d0221" stroke="#8A2BE2" stroke-width="1"/>
    <g class="r-eyeball-l">
      <circle cx="61" cy="32" r="5" fill="#8A2BE2" class="r-eye-blink" style="transform-origin:61px 32px"/>
      <circle cx="62" cy="31" r="2" fill="#00ffff"/>
      <circle cx="63" cy="30" r="0.8" fill="white"/>
    </g>
    <rect x="75" y="25" width="18" height="14" rx="5" fill="#0d0221" stroke="#8A2BE2" stroke-width="1"/>
    <g class="r-eyeball-r">
      <circle cx="84" cy="32" r="5" fill="#8A2BE2" class="r-eye-blink" style="transform-origin:84px 32px"/>
      <circle cx="85" cy="31" r="2" fill="#00ffff"/>
      <circle cx="86" cy="30" r="0.8" fill="white"/>
    </g>
    <rect x="57" y="44" width="26" height="5" rx="2" fill="#0d0221" stroke="#8A2BE2" stroke-width="0.8"/>
    <rect x="59" y="45.5" width="4" height="2" rx="1" fill="#00ffff" opacity="0.9"/>
    <rect x="65" y="45.5" width="4" height="2" rx="1" fill="#00ffff" opacity="0.9"/>
    <rect x="71" y="45.5" width="4" height="2" rx="1" fill="#00ffff" opacity="0.9"/>
    <rect x="77" y="45.5" width="4" height="2" rx="1" fill="#00ffff" opacity="0.5"/>
    <line x1="70" y1="16" x2="70" y2="6" stroke="#8A2BE2" stroke-width="2"/>
    <circle cx="70" cy="4" r="3" class="r-antenna"/>
    <circle cx="42" cy="32" r="4" fill="#2a0060" stroke="#8A2BE2" stroke-width="1"/>
    <circle cx="98" cy="32" r="4" fill="#2a0060" stroke="#8A2BE2" stroke-width="1"/>
    <g class="r-bubble" transform="translate(108,5)">
      <rect x="0" y="0" width="90" height="32" rx="8" fill="#0d0221" stroke="#8A2BE2" stroke-width="1.5"/>
      <polygon points="0,16 -8,22 0,24" fill="#0d0221" stroke="#8A2BE2" stroke-width="1"/>
      <text x="8" y="13" font-family="Courier New" font-size="8" fill="#00ffff">psst... nice</text>
      <text x="8" y="25" font-family="Courier New" font-size="8" fill="#8A2BE2">README! 👀</text>
    </g>
  </g>
</svg>
</div>

<div align="center">

<!-- FOOTER SVG -->
<svg width="100%" height="100" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 100">
  <defs>
    <linearGradient id="fbg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   style="stop-color:#0d0221"/>
      <stop offset="50%"  style="stop-color:#0a0a0a"/>
      <stop offset="100%" style="stop-color:#1a0533"/>
    </linearGradient>
    <filter id="f-glow">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <style>
      .f-cp { stroke:#8A2BE2; stroke-width:1; fill:none; opacity:0; animation:f-light 4s ease-in-out infinite; }
      .f-cp.f-d1{animation-delay:0s;} .f-cp.f-d2{animation-delay:0.8s;}
      .f-cp.f-d3{animation-delay:1.6s;} .f-cp.f-d4{animation-delay:2.4s;} .f-cp.f-d5{animation-delay:3.2s;}
      @keyframes f-light {
        0%,100%{opacity:0.05; stroke:#8A2BE2;}
        50%    {opacity:0.9;  stroke:#00ffff;}
      }
      .f-nd { fill:#8A2BE2; animation:f-nodeGlow 3s ease-in-out infinite; }
      @keyframes f-nodeGlow {
        0%,100%{fill:#8A2BE2; opacity:0.4;}
        50%    {fill:#00ffff; opacity:1;}
      }
      .f-td { fill:#00ffff; filter:url(#f-glow); animation:f-trav 3s linear infinite; }
      @keyframes f-trav { 0%{opacity:0;} 10%{opacity:1;} 90%{opacity:1;} 100%{opacity:0;} }
      .f-txt {
        font-family:'Courier New',monospace; font-size:11px;
        fill:#8A2BE2; letter-spacing:3px; opacity:0.7; filter:url(#f-glow);
      }
    </style>
  </defs>
  <rect width="1200" height="100" fill="url(#fbg)"/>
  <rect x="0" y="0" width="1200" height="2" fill="#8A2BE2" opacity="0.6" filter="url(#f-glow)"/>
  <polyline points="0,30 100,30 100,60 200,60"            class="f-cp f-d1"/>
  <polyline points="200,60 300,60 300,30 450,30"           class="f-cp f-d2"/>
  <polyline points="450,30 450,70 600,70 600,30"           class="f-cp f-d3"/>
  <polyline points="600,30 750,30 750,70 900,70"           class="f-cp f-d4"/>
  <polyline points="900,70 900,30 1000,30 1000,60 1200,60" class="f-cp f-d5"/>
  <line x1="0" y1="50" x2="1200" y2="50" stroke="#8A2BE2" stroke-width="0.5" opacity="0.2"/>
  <circle cx="100"  cy="30" r="3" class="f-nd" style="animation-delay:0s"/>
  <circle cx="200"  cy="60" r="3" class="f-nd" style="animation-delay:0.5s"/>
  <circle cx="300"  cy="30" r="3" class="f-nd" style="animation-delay:1s"/>
  <circle cx="450"  cy="70" r="3" class="f-nd" style="animation-delay:1.5s"/>
  <circle cx="600"  cy="30" r="3" class="f-nd" style="animation-delay:2s"/>
  <circle cx="750"  cy="70" r="3" class="f-nd" style="animation-delay:2.5s"/>
  <circle cx="900"  cy="30" r="3" class="f-nd" style="animation-delay:3s"/>
  <circle cx="1000" cy="60" r="3" class="f-nd" style="animation-delay:3.5s"/>
  <circle r="3" class="f-td" style="animation-delay:0s">
    <animateMotion dur="3s" repeatCount="indefinite" path="M0,50 L1200,50"/>
  </circle>
  <circle r="2" class="f-td" style="animation-delay:1.5s; fill:#8A2BE2">
    <animateMotion dur="3s" repeatCount="indefinite" path="M1200,50 L0,50"/>
  </circle>
  <text x="600" y="92" text-anchor="middle" class="f-txt">⚡ BUILT WITH PASSION BY PRATHAM TAIKAR ⚡</text>
</svg>

</div>