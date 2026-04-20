<div align="center">

<!-- ═══════════════════════════════ HEADER SVG ═══════════════════════════════ -->
<svg width="100%" height="220" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 220">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%"   style="stop-color:#0d0221"/>
      <stop offset="50%"  style="stop-color:#0a0a0a"/>
      <stop offset="100%" style="stop-color:#1a0533"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <style>
      .mc { font-family:'Courier New',monospace; font-size:13px; fill:#8A2BE2; opacity:0; }
      .mc.fast { animation:fall 2.5s linear infinite; }
      .mc.mid  { animation:fall 3.8s linear infinite; }
      .mc.slow { animation:fall 5.2s linear infinite; }
      @keyframes fall {
        0%   { transform:translateY(-30px); opacity:0; }
        10%  { opacity:0.9; }
        90%  { opacity:0.4; }
        100% { transform:translateY(240px); opacity:0; }
      }
      .nm {
        font-family:'Courier New',monospace; font-size:46px;
        font-weight:900; fill:#ffffff; filter:url(#glow); letter-spacing:4px;
      }
      .rl {
        font-family:'Courier New',monospace; font-size:15px;
        fill:#8A2BE2; letter-spacing:5px; filter:url(#glow);
      }
      .cur { fill:#00ffff; animation:blink 0.8s step-end infinite; filter:url(#glow); }
      @keyframes blink { 50% { opacity:0; } }
      .nl { stroke:#8A2BE2; stroke-width:1; fill:none; opacity:0; animation:pulse 3s ease-in-out infinite; }
      @keyframes pulse { 0%,100%{opacity:0.08;} 50%{opacity:0.5;} }
      .dot { fill:#8A2BE2; animation:twinkle 2s ease-in-out infinite; }
      @keyframes twinkle { 0%,100%{opacity:0.1;r:1.5;} 50%{opacity:1;r:3;} }
      .gr { font-family:'Courier New',monospace; font-size:46px; font-weight:900; letter-spacing:4px; }
      .gr-r { fill:#ff003c; opacity:0; animation:gr 4s infinite; }
      .gr-b { fill:#00ffff; opacity:0; animation:gb 4s infinite; }
      @keyframes gr { 0%,89%,91%,100%{opacity:0;transform:translate(0,0);} 90%{opacity:0.5;transform:translate(-4px,1px);} }
      @keyframes gb { 0%,87%,89%,100%{opacity:0;transform:translate(0,0);} 88%{opacity:0.5;transform:translate(4px,-1px);} }
      .sl { fill:rgba(138,43,226,0.06); animation:scan 3s linear infinite; }
      @keyframes scan { 0%{transform:translateY(-20px);} 100%{transform:translateY(240px);} }
    </style>
  </defs>
  <rect width="1200" height="220" fill="url(#bg)"/>
  <line x1="0" y1="55"  x2="1200" y2="55"  class="nl" style="animation-delay:0s"/>
  <line x1="0" y1="110" x2="1200" y2="110" class="nl" style="animation-delay:1s"/>
  <line x1="0" y1="165" x2="1200" y2="165" class="nl" style="animation-delay:2s"/>
  <line x1="300" y1="0" x2="300" y2="220"  class="nl" style="animation-delay:0.5s"/>
  <line x1="600" y1="0" x2="600" y2="220"  class="nl" style="animation-delay:1.5s"/>
  <line x1="900" y1="0" x2="900" y2="220"  class="nl" style="animation-delay:2.5s"/>
  <text x="40"   class="mc fast" style="animation-delay:0.1s">01</text>
  <text x="80"   class="mc slow" style="animation-delay:0.8s">10</text>
  <text x="120"  class="mc mid"  style="animation-delay:0.3s">11</text>
  <text x="160"  class="mc fast" style="animation-delay:1.2s">00</text>
  <text x="200"  class="mc slow" style="animation-delay:0.6s">01</text>
  <text x="950"  class="mc fast" style="animation-delay:0.4s">10</text>
  <text x="990"  class="mc mid"  style="animation-delay:1.0s">01</text>
  <text x="1030" class="mc slow" style="animation-delay:0.2s">11</text>
  <text x="1070" class="mc fast" style="animation-delay:1.5s">00</text>
  <text x="1110" class="mc mid"  style="animation-delay:0.7s">10</text>
  <circle cx="260"  cy="40"  r="1.5" class="dot" style="animation-delay:0.3s"/>
  <circle cx="500"  cy="20"  r="1.5" class="dot" style="animation-delay:1.1s"/>
  <circle cx="700"  cy="190" r="1.5" class="dot" style="animation-delay:0.7s"/>
  <circle cx="940"  cy="35"  r="1.5" class="dot" style="animation-delay:1.8s"/>
  <circle cx="1150" cy="150" r="1.5" class="dot" style="animation-delay:0.5s"/>
  <circle cx="80"   cy="180" r="1.5" class="dot" style="animation-delay:2.2s"/>
  <rect width="1200" height="4" class="sl"/>
  <text x="600" y="115" text-anchor="middle" class="gr gr-r">PRATHAM TAIKAR</text>
  <text x="600" y="115" text-anchor="middle" class="gr gr-b">PRATHAM TAIKAR</text>
  <text x="600" y="115" text-anchor="middle" class="nm">PRATHAM TAIKAR</text>
  <text x="898" y="115" class="nm cur" font-size="46px">_</text>
  <text x="600" y="155" text-anchor="middle" class="rl">&lt; FULL STACK WEB DEVELOPER / SDE &gt;</text>
  <rect x="200" y="178" width="800" height="2" rx="1" fill="#8A2BE2" opacity="0.5" filter="url(#glow)"/>
</svg>
<!-- ═══════════════════════════════════════════════════════════════════════════ -->

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



<div align="center">

<!-- ═══════════════════════════════ FOOTER SVG ═══════════════════════════════ -->
<svg width="100%" height="100" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 100">
  <defs>
    <linearGradient id="fbg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   style="stop-color:#0d0221"/>
      <stop offset="50%"  style="stop-color:#0a0a0a"/>
      <stop offset="100%" style="stop-color:#1a0533"/>
    </linearGradient>
    <filter id="glow2">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <style>
      .cp { stroke:#8A2BE2; stroke-width:1; fill:none; opacity:0; animation:light 4s ease-in-out infinite; }
      .cp.d1{animation-delay:0s;} .cp.d2{animation-delay:0.8s;}
      .cp.d3{animation-delay:1.6s;} .cp.d4{animation-delay:2.4s;} .cp.d5{animation-delay:3.2s;}
      @keyframes light {
        0%,100%{opacity:0.05; stroke:#8A2BE2;}
        50%    {opacity:0.9;  stroke:#00ffff;}
      }
      .nd { fill:#8A2BE2; animation:nodeGlow 3s ease-in-out infinite; }
      @keyframes nodeGlow {
        0%,100%{fill:#8A2BE2; r:3; opacity:0.4;}
        50%    {fill:#00ffff; r:5; opacity:1;}
      }
      .td { fill:#00ffff; filter:url(#glow2); animation:trav 3s linear infinite; }
      @keyframes trav { 0%{opacity:0;} 10%{opacity:1;} 90%{opacity:1;} 100%{opacity:0;} }
      .ft {
        font-family:'Courier New',monospace; font-size:11px;
        fill:#8A2BE2; letter-spacing:3px; opacity:0.7; filter:url(#glow2);
      }
    </style>
  </defs>
  <rect width="1200" height="100" fill="url(#fbg)"/>
  <rect x="0" y="0" width="1200" height="2" fill="#8A2BE2" opacity="0.6" filter="url(#glow2)"/>
  <polyline points="0,30 100,30 100,60 200,60"          class="cp d1"/>
  <polyline points="200,60 300,60 300,30 450,30"         class="cp d2"/>
  <polyline points="450,30 450,70 600,70 600,30"         class="cp d3"/>
  <polyline points="600,30 750,30 750,70 900,70"         class="cp d4"/>
  <polyline points="900,70 900,30 1000,30 1000,60 1200,60" class="cp d5"/>
  <line x1="0" y1="50" x2="1200" y2="50" stroke="#8A2BE2" stroke-width="0.5" opacity="0.2"/>
  <circle cx="100"  cy="30" r="3" class="nd" style="animation-delay:0s"/>
  <circle cx="200"  cy="60" r="3" class="nd" style="animation-delay:0.5s"/>
  <circle cx="300"  cy="30" r="3" class="nd" style="animation-delay:1s"/>
  <circle cx="450"  cy="70" r="3" class="nd" style="animation-delay:1.5s"/>
  <circle cx="600"  cy="30" r="3" class="nd" style="animation-delay:2s"/>
  <circle cx="750"  cy="70" r="3" class="nd" style="animation-delay:2.5s"/>
  <circle cx="900"  cy="30" r="3" class="nd" style="animation-delay:3s"/>
  <circle cx="1000" cy="60" r="3" class="nd" style="animation-delay:3.5s"/>
  <circle r="3" class="td" style="animation-delay:0s">
    <animateMotion dur="3s" repeatCount="indefinite" path="M0,50 L1200,50"/>
  </circle>
  <circle r="2" class="td" style="animation-delay:1.5s; fill:#8A2BE2">
    <animateMotion dur="3s" repeatCount="indefinite" path="M1200,50 L0,50"/>
  </circle>
  <text x="600" y="92" text-anchor="middle" class="ft">⚡ BUILT WITH PASSION BY PRATHAM TAIKAR ⚡</text>
</svg>


</div>

