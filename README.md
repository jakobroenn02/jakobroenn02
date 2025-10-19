<div align="center">
  <svg viewBox="0 0 1200 320" width="100%" height="auto" role="img" aria-label="Neon banner">
    <defs>
      <!-- Blue gradient -->
      <linearGradient id="blueGrad" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%"  stop-color="#00ccff"/>
        <stop offset="100%" stop-color="#0066ff"/>
      </linearGradient>

      <!-- Neon glow filter (animated blur) -->
      <filter id="neonGlow">
        <feGaussianBlur in="SourceGraphic" stdDeviation="2">
          <animate attributeName="stdDeviation" values="2;5;2" dur="4s" repeatCount="indefinite"/>
        </feGaussianBlur>
        <feMerge>
          <feMergeNode/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>

      <!-- Softer outer glow -->
      <filter id="outerGlow">
        <feGaussianBlur stdDeviation="8">
          <animate attributeName="stdDeviation" values="6;12;6" dur="4s" repeatCount="indefinite"/>
        </feGaussianBlur>
        <feColorMatrix type="matrix" values="
          0 0 0 0 0
          0 0 0 0 0.6
          1 0 0 0 1
          0 0 0 0.9 0">
          <animate attributeName="values"
                   dur="4s" repeatCount="indefinite"
                   values="
          0 0 0 0 0   0 0 0 0 0.6   1 0 0 0 1   0 0 0 0.6 0;
          0 0 0 0 0   0 0 0 0 0.8   1 0 0 0 1   0 0 0 0.9 0;
          0 0 0 0 0   0 0 0 0 0.6   1 0 0 0 1   0 0 0 0.6 0"/>
        </feColorMatrix>
        <feMerge>
          <feMergeNode/>
        </feMerge>
      </filter>

      <!-- Subtle scanline gradient for background -->
      <linearGradient id="bgFade" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%"   stop-color="#05070c"/>
        <stop offset="100%" stop-color="#000000"/>
      </linearGradient>
    </defs>

    <!-- Background -->
    <rect x="0" y="0" width="1200" height="320" fill="url(#bgFade)" rx="16"/>

    <!-- Pulsing waves -->
    <g opacity="0.18" stroke="url(#blueGrad)" fill="none" stroke-width="4">
      <path id="wave1" d="M0,160 Q150,120 300,160 T600,160 T900,160 T1200,160"/>
      <use href="#wave1">
        <animateTransform attributeName="transform" type="translate"
                           from="0 0" to="-300 0" dur="6s" repeatCount="indefinite"/>
      </use>
      <use href="#wave1" transform="translate(0,20)">
        <animateTransform attributeName="transform" type="translate"
                           from="0 0" to="-450 0" dur="9s" repeatCount="indefinite"/>
      </use>
      <use href="#wave1" transform="translate(0,40)">
        <animateTransform attributeName="transform" type="translate"
                           from="0 0" to="-600 0" dur="12s" repeatCount="indefinite"/>
      </use>
    </g>

    <!-- Circuit traces -->
    <g opacity="0.28" stroke="url(#blueGrad)" stroke-width="2" fill="none">
      <path d="M20 40 H160 V70 H240 V55 H330 V85 H420" stroke-dasharray="8 8">
        <animate attributeName="stroke-dashoffset" from="100" to="0" dur="4s" repeatCount="indefinite"/>
      </path>
      <path d="M1180 260 H1040 V230 H960 V245 H870 V215 H780" stroke-dasharray="10 10">
        <animate attributeName="stroke-dashoffset" from="0" to="100" dur="6s" repeatCount="indefinite"/>
      </path>
    </g>

    <!-- Title (outer glow copy) -->
    <text x="50%" y="145" text-anchor="middle" font-size="44"
          font-family="Segoe UI, Tahoma, Geneva, Verdana, sans-serif"
          fill="#00ccff" filter="url(#outerGlow)">👋 Hi, I’m Jakob Rønn</text>

    <!-- Title (neon breathing) -->
    <text x="50%" y="145" text-anchor="middle" font-size="44"
          font-family="Segoe UI, Tahoma, Geneva, Verdana, sans-serif"
          fill="#00ccff" filter="url(#neonGlow)">
      👋 Hi, I’m Jakob Rønn
    </text>

    <!-- Subtitle (pulsing fill-opacity) -->
    <text x="50%" y="195" text-anchor="middle" font-size="18"
          font-family="Segoe UI, Tahoma, Geneva, Verdana, sans-serif"
          fill="#a8eaff" fill-opacity="0.8">
      Software Engineering Student @ Aalborg University — low-level, systems, compiler dev.
      <animate attributeName="fill-opacity" values="0.7;1;0.7" dur="4s" repeatCount="indefinite"/>
    </text>
  </svg>
</div>



🎓 **Software Engineering Student @ Aalborg University**  
💻 Passionate about **low-level programming**, **systems design**, and **compiler development**  
🌱 Currently working on:  
🧠 **RPL (Robot Programming Language)** – a custom compiler and toolchain in C  
🧩 **GIRAF VTA** – full-stack project using **Flutter**, **.NET 8**, and **MySQL**

---

## 🧰 Tech Stack

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-68217A?style=for-the-badge&logo=csharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=mysql&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly-525252?style=for-the-badge)

---

## ⚙️ Tools & Frameworks

![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F1502F?style=for-the-badge&logo=git&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![VSCode](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=jakobroenn02&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165em" src="https://github-readme-streak-stats.herokuapp.com/?user=jakobroenn02&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jakobroenn02&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

## 🌍 About Me

💡 I’m curious about how things work — from **life** to **operating systems**.  
🎮 When I’m not coding, I enjoy **Fortnite**, **Arma 3 modding**, and **DCS**.  

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/jakob-roenn/)
[![GitHub](https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github)](https://github.com/jakobroenn02)

---

⭐️ *“Build things that teach you something new.”*
