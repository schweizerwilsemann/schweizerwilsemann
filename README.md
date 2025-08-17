<!-- Profile README for schweizerwilsemann -->

<div align="center">

<div align="center">
  
<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Animated gradient base -->
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1a1a2e">
        <animate attributeName="stop-color" values="#1a1a2e;#16213e;#0f3460;#533483;#1a1a2e" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#16213e">
        <animate attributeName="stop-color" values="#16213e;#0f3460;#533483;#1a1a2e;#16213e" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#0f3460">
        <animate attributeName="stop-color" values="#0f3460;#533483;#1a1a2e;#16213e;#0f3460" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    
    <!-- Cherry blossom pattern -->
    <g id="sakura">
      <path d="M0,0 Q2,-2 4,0 Q2,2 0,0 Q-2,-2 -4,0 Q-2,2 0,0" fill="#ffb7c5" opacity="0.7"/>
      <circle cx="0" cy="0" r="1" fill="#ff69b4"/>
    </g>
    
    <!-- Star pattern -->
    <g id="star">
      <path d="M0,-8 L2,-2 L8,-2 L3,1 L5,7 L0,4 L-5,7 L-3,1 L-8,-2 L-2,-2 Z" fill="#ffd700" opacity="0.8"/>
    </g>
    
    <!-- Anime speed lines -->
    <pattern id="speedLines" x="0" y="0" width="100" height="200" patternUnits="userSpaceOnUse">
      <line x1="0" y1="0" x2="100" y2="200" stroke="rgba(255,255,255,0.1)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.05;0.2;0.05" dur="2s" repeatCount="indefinite"/>
      </line>
      <line x1="20" y1="0" x2="120" y2="200" stroke="rgba(0,255,255,0.1)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.1;0.3;0.1" dur="1.5s" repeatCount="indefinite"/>
      </line>
      <line x1="40" y1="0" x2="140" y2="200" stroke="rgba(255,0,255,0.1)" stroke-width="1">
        <animate attributeName="stroke-opacity" values="0.05;0.25;0.05" dur="1.8s" repeatCount="indefinite"/>
      </line>
    </pattern>
    
    <!-- Geometric anime pattern -->
    <pattern id="animePattern" x="0" y="0" width="60" height="60" patternUnits="userSpaceOnUse">
      <circle cx="30" cy="30" r="2" fill="#00ffff" opacity="0.3">
        <animate attributeName="r" values="1;3;1" dur="3s" repeatCount="indefinite"/>
      </circle>
      <polygon points="15,15 45,15 30,45" fill="none" stroke="#ff69b4" stroke-width="1" opacity="0.2">
        <animateTransform attributeName="transform" type="rotate" values="0 30 30;360 30 30" dur="10s" repeatCount="indefinite"/>
      </polygon>
    </pattern>
    
    <!-- Neon glow filters -->
    <filter id="neonGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge> 
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    
    <filter id="textGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge> 
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    
    <!-- Holographic scan gradient -->
    <linearGradient id="scanGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="30%" style="stop-color:rgba(0,255,255,0.3)"/>
      <stop offset="70%" style="stop-color:rgba(255,0,255,0.3)"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
  </defs>
  
  <!-- Base background -->
  <rect width="100%" height="100%" fill="url(#bgGradient)"/>
  
  <!-- Anime speed lines background -->
  <rect width="100%" height="100%" fill="url(#speedLines)" opacity="0.4"/>
  
  <!-- Geometric anime pattern overlay -->
  <rect width="100%" height="100%" fill="url(#animePattern)" opacity="0.6"/>
  
  <!-- Floating cherry blossoms -->
  <g opacity="0.8">
    <use href="#sakura" x="100" y="50">
      <animateTransform attributeName="transform" type="translate" values="100,50; 120,30; 140,70; 100,50" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;1;0.5" dur="4s" repeatCount="indefinite"/>
    </use>
    <use href="#sakura" x="650" y="150">
      <animateTransform attributeName="transform" type="translate" values="650,150; 630,130; 670,170; 650,150" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;0.3;0.7" dur="5s" repeatCount="indefinite"/>
    </use>
    <use href="#sakura" x="200" y="30">
      <animateTransform attributeName="transform" type="translate" values="200,30; 220,50; 180,10; 200,30" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="3s" repeatCount="indefinite"/>
    </use>
    <use href="#sakura" x="550" y="40">
      <animateTransform attributeName="transform" type="translate" values="550,40; 570,60; 530,20; 550,40" dur="9s" repeatCount="indefinite"/>
    </use>
  </g>
  
  <!-- Floating anime stars -->
  <g opacity="0.9">
    <use href="#star" x="150" y="120" transform="scale(0.5)">
      <animateTransform attributeName="transform" type="rotate" values="0 150 120;360 150 120" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.3;1;0.3" dur="2s" repeatCount="indefinite"/>
    </use>
    <use href="#star" x="680" y="80" transform="scale(0.3)">
      <animateTransform attributeName="transform" type="rotate" values="360 680 80;0 680 80" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;0.8;0.5" dur="3s" repeatCount="indefinite"/>
    </use>
    <use href="#star" x="50" y="170" transform="scale(0.4)">
      <animateTransform attributeName="transform" type="rotate" values="0 50 170;360 50 170" dur="6s" repeatCount="indefinite"/>
    </use>
  </g>
  
  <!-- Large animated neon orbs -->
  <circle cx="150" cy="60" r="25" fill="#ff1493" filter="url(#neonGlow)" opacity="0.6">
    <animate attributeName="cy" values="60;40;80;60" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="r" values="25;35;20;25" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="fill" values="#ff1493;#00ffff;#ff69b4;#ff1493" dur="6s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="650" cy="140" r="20" fill="#00ffff" filter="url(#neonGlow)" opacity="0.7">
    <animate attributeName="cy" values="140;120;160;140" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="r" values="20;30;15;20" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="fill" values="#00ffff;#ff69b4;#ffd700;#00ffff" dur="4s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Anime-style energy particles -->
  <g opacity="0.8">
    <circle cx="100" cy="190" r="3" fill="#ff69b4">
      <animate attributeName="cy" values="190;-10" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;1;0" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="r" values="1;3;1" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="250" cy="190" r="4" fill="#00ffff">
      <animate attributeName="cy" values="190;-10" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;1;0" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="400" cy="190" r="2" fill="#ffd700">
      <animate attributeName="cy" values="190;-10" dur="7s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;1;0" dur="7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="550" cy="190" r="3" fill="#ff1493">
      <animate attributeName="cy" values="190;-10" dur="9s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;1;0" dur="9s" repeatCount="indefinite"/>
    </circle>
    <circle cx="700" cy="190" r="2" fill="#00ff7f">
      <animate attributeName="cy" values="190;-10" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;1;1;0" dur="5s" repeatCount="indefinite"/>
    </circle>
  </g>
  
  <!-- Anime-style energy beams -->
  <rect x="-300" y="70" width="200" height="3" fill="url(#laserGrad1)" opacity="0.9">
    <animate attributeName="x" values="-300;800" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;1;0" dur="3s" repeatCount="indefinite"/>
  </rect>
  
  <rect x="-250" y="130" width="150" height="2" fill="url(#laserGrad2)" opacity="0.8">
    <animate attributeName="x" values="-250;800" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0;1;1;0" dur="4s" repeatCount="indefinite"/>
  </rect>
  
  <!-- Energy beam gradients -->
  <defs>
    <linearGradient id="laserGrad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="50%" style="stop-color:#ff69b4"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
    <linearGradient id="laserGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:transparent"/>
      <stop offset="50%" style="stop-color:#00ffff"/>
      <stop offset="100%" style="stop-color:transparent"/>
    </linearGradient>
  </defs>
  
  <!-- Anime-style corner decorations -->
  <g stroke-width="2" fill="none" opacity="0.8">
    <!-- Top left corner -->
    <path d="M20,20 L50,20 M20,20 L20,50" stroke="#ff69b4">
      <animate attributeName="stroke" values="#ff69b4;#00ffff;#ffd700;#ff69b4" dur="4s" repeatCount="indefinite"/>
    </path>
    
    <!-- Top right corner -->
    <path d="M780,20 L750,20 M780,20 L780,50" stroke="#00ffff">
      <animate attributeName="stroke" values="#00ffff;#ffd700;#ff69b4;#00ffff" dur="4s" repeatCount="indefinite"/>
    </path>
    
    <!-- Bottom left corner -->
    <path d="M20,180 L50,180 M20,180 L20,150" stroke="#ffd700">
      <animate attributeName="stroke" values="#ffd700;#ff69b4;#00ffff;#ffd700" dur="4s" repeatCount="indefinite"/>
    </path>
    
    <!-- Bottom right corner -->
    <path d="M780,180 L750,180 M780,180 L780,150" stroke="#ff1493">
      <animate attributeName="stroke" values="#ff1493;#00ffff;#ffd700;#ff1493" dur="4s" repeatCount="indefinite"/>
    </path>
  </g>
  
  <!-- Rotating energy rings -->
  <circle cx="100" cy="100" r="30" fill="none" stroke="#ff69b4" stroke-width="1" opacity="0.5">
    <animateTransform attributeName="transform" type="rotate" values="0 100 100;360 100 100" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="stroke-opacity" values="0.2;0.8;0.2" dur="4s" repeatCount="indefinite"/>
  </circle>
  
  <circle cx="700" cy="100" r="40" fill="none" stroke="#00ffff" stroke-width="1" opacity="0.4">
    <animateTransform attributeName="transform" type="rotate" values="360 700 100;0 700 100" dur="10s" repeatCount="indefinite"/>
    <animate attributeName="stroke-opacity" values="0.1;0.7;0.1" dur="3s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Main text with anime-style glow -->
  <text x="400" y="110" text-anchor="middle" font-family="monospace, 'Courier New'" font-size="42" font-weight="bold" fill="#ffffff" filter="url(#textGlow)">
    NGUYEN DUC KHOA
    <animate attributeName="fill" values="#ffffff;#ff69b4;#00ffff;#ffd700;#ffffff" dur="5s" repeatCount="indefinite"/>
  </text>
  
  <!-- Anime-style subtitle -->
  <text x="400" y="140" text-anchor="middle" font-family="monospace, 'Courier New'" font-size="14" fill="#ff69b4" opacity="0.9">
    ◆ DEVELOPER ◆ CREATOR ◆ OTAKU ◆
    <animate attributeName="fill" values="#ff69b4;#00ffff;#ffd700;#ff69b4" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </text>
  
  <!-- Holographic scanning effect -->
  <rect x="-100" y="0" width="80" height="200" fill="url(#scanGrad)" opacity="0.4">
    <animate attributeName="x" values="-100;800" dur="6s" repeatCount="indefinite"/>
  </rect>
  
  <!-- Additional anime sparkles -->
  <g opacity="0.7">
    <circle cx="300" cy="60" r="1" fill="#ffffff">
      <animate attributeName="opacity" values="0;1;0" dur="1.5s" repeatCount="indefinite"/>
      <animate attributeName="r" values="1;3;1" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="500" cy="160" r="1" fill="#ff69b4">
      <animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="r" values="1;2;1" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="600" cy="50" r="1" fill="#00ffff">
      <animate attributeName="opacity" values="0;1;0" dur="1.8s" repeatCount="indefinite"/>
      <animate attributeName="r" values="1;2.5;1" dur="1.8s" repeatCount="indefinite"/>
    </circle>
  </g>
</svg>

</div>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=FF6B9D&center=true&vCenter=true&multiline=true&repeat=true&random=false&width=900&height=120&lines=Welcome+to+my+Digital+Playground;Backend+Wizard+DevOps+Ninja+AI+Whisperer;Milktea+Powered+Anime+Inspired+Dream+Builder" alt="Typing SVG" />

<br/>

<!-- Floating badges with glow effect -->
<p align="center">
  <a href="https://github.com/schweizerwilsemann">
    <img src="https://img.shields.io/badge/🌟_Profile_Views-FF1493?style=for-the-badge&logoColor=white&labelColor=000&color=FF69B4"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=schweizerwilsemann&style=for-the-badge&color=ff69b4&label=VISITORS" alt="Profile Views"/>
</p>

<p align="center">
  <a href="mailto:khoa.qianyingya@gmail.com">
    <img src="https://img.shields.io/badge/📧_Let's_Talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000" />
  </a>
  <a href="https://www.linkedin.com/in/khoa-nguyen-016280323/">
    <img src="https://img.shields.io/badge/💼_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=000" />
  </a>
</p>

</div>

---

<div align="center">

## 🌈 ✨ About This Digital Soul ✨ 🌈

</div>

<div align="center">
<table>
<tr>
<td width="50%">

```yaml
name: Nguyen Duc Khoa
located_in: somewhere between reality & code
currently_learning: 
  - "Rust & the art of clean APIs"
  - "AI/RAG magic & prompt wizardry"

interests: 
  - Backend and Frontend 🏗️
  - Currently learning Linux ☁️
  - Developer Experience 💫
  - Anime & Aesthetic Code 🌸

fun_fact: "I debug with printf and rubber ducks"
```

</td>
<td width="50%">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="100%" alt="coding"/>

</td>
</tr>
</table>
</div>

---

<div align="center">

## 🛠️ ✨ Tech Arsenal ✨ 🛠️

<img src="https://skillicons.dev/icons?i=linux,docker,postgres,mysql,react,nextjs,nodejs,typescript,python,nginx,jenkins,java,tailwind,dotnet,mongodb,bash,arch&perline=6" />

<br/><br/>

### 🖥️ **Operating Systems & Tools**
<img src="https://img.shields.io/badge/🐧_Linux-FCC624?style=for-the-badge&logo=linux&logoColor=000&labelColor=000"/>
<img src="https://img.shields.io/badge/🏹_Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=fff&labelColor=000"/>
<img src="https://img.shields.io/badge/💻_Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=fff&labelColor=000"/>

### 🐳 **DevOps & Infrastructure**
<img src="https://img.shields.io/badge/🐳_Docker-2496ED?style=for-the-badge&logo=docker&logoColor=fff&labelColor=000"/>
<img src="https://img.shields.io/badge/🔧_Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=fff&labelColor=000"/>
<img src="https://img.shields.io/badge/🌐_NGINX-009639?style=for-the-badge&logo=nginx&logoColor=fff&labelColor=000"/>

### 🗄️ **Databases**
<img src="https://img.shields.io/badge/🐘_PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=fff&labelColor=000"/>
<img src="https://img.shields.io/badge/🐬_MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=fff&labelColor=000"/>
<img src="https://img.shields.io/badge/🍃_MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=fff&labelColor=000"/>

### 💻 **Programming Languages**
<img src="https://img.shields.io/badge/💚_Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=fff&labelColor=000"/>
<img src="https://img.shields.io/badge/🔷_TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=fff&labelColor=000"/>
<img src="https://img.shields.io/badge/🐍_Python-3776AB?style=for-the-badge&logo=python&logoColor=fff&labelColor=000"/>
<img src="https://img.shields.io/badge/☕_Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=fff&labelColor=000"/>
<img src="https://img.shields.io/badge/🟦_.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=fff&labelColor=000"/>

### ⚛️ **Frontend & Frameworks**
<img src="https://img.shields.io/badge/⚛️_React-61DAFB?style=for-the-badge&logo=react&logoColor=000&labelColor=000"/>
<img src="https://img.shields.io/badge/🚀_Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=fff&labelColor=000"/>
<img src="https://img.shields.io/badge/🎨_Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=fff&labelColor=000"/>

</div>

---

<div align="center">

## 📊 ✨ GitHub Magic Stats ✨ 📊

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=schweizerwilsemann&custom_title=Contribution%20Graph&bg_color=0D1117&color=FF69B4&line=FF1493&point=FFFFFF&area=true&hide_border=true"/>

<br/>

<table>
<tr>
<td width="50%">
<img src="https://github-readme-stats.vercel.app/api?username=schweizerwilsemann&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=FF69B4&icon_color=FF1493&text_color=FFFFFF&rank_icon=github" alt="GitHub Stats"/>
</td>
<td width="50%">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=schweizerwilsemann&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=FF69B4&text_color=FFFFFF" alt="Top Languages"/>
</td>
</tr>
</table>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=schweizerwilsemann&theme=tokyonight&hide_border=true&background=0D1117&stroke=FF69B4&ring=FF1493&fire=FF69B4&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=FF69B4&sideLabels=FF69B4&dates=FFFFFF" alt="GitHub Streak"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=schweizerwilsemann&theme=tokyonight&no-bg=true&no-frame=true&row=1&column=7" alt="GitHub Trophies"/>

</div>

---

<div align="center">

## 🌸 ✨ Daily Inspiration ✨ 🌸

<table>
<tr>
<td width="60%">

### 💭 Philosophy of Code
```javascript
const life = {
  milktea: '🧋 Essential fuel',
  anime: '🌸 Creative inspiration', 
  code: '💻 Digital poetry',
  dreams: '✨ Infinite possibilities'
};

function createMagic() {
  return life.milktea + life.anime + life.code + life.dreams;
}
```

</td>
<td width="40%">

<img src="https://media.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif" width="100%" alt="anime coding"/>

</td>
</tr>
</table>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight&bg_color=0D1117&border_color=FF69B4" alt="Random Dev Quote"/>

</div>

---

<div align="center">

## 🎯 ✨ Current Adventures ✨ 🎯

<table>
<tr>
<td align="center" width="33%">

### 🚀 **Building**
Learning to scalable 
Database  

</td>
<td align="center" width="33%">

### 🧠 **Learning**
AI-powered development  
tools & automation

</td>
<td align="center" width="33%">

### 🌟 **Exploring**
Next-gen DevOps  
& cloud architectures

</td>
</tr>
</table>

</div>

---

<div align="center">

## 📬 ✨ Let's Connect & Create Magic ✨ 📬

<a href="mailto:khoa.qianyingya@gmail.com">
  <img src="https://img.shields.io/badge/📧_Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000"/>
</a>
<a href="https://t.me/schweizerwilsemann">
  <img src="https://img.shields.io/badge/💬_Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white&labelColor=000"/>
</a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer"/>

---

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2000&pause=1000&color=FF69B4&center=true&vCenter=true&width=600&lines=Thanks+for+visiting!;Star+some+repos+if+you+like+them!;Let's+build+something+amazing+together!" alt="Footer"/>
</div>

</div>
