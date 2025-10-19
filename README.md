
<div align="center" style="position: relative; overflow: hidden; border-radius: 14px; padding: 80px 0; background-color: #000;">

  <!-- Pulsing wave background -->
  <svg width="100%" height="100%" style="position:absolute; top:0; left:0; z-index:0; opacity:0.12;">
    <defs>
      <linearGradient id="waveGradient" x1="0" x2="1" y1="0" y2="0">
        <stop offset="0%" stop-color="#00ccff"/>
        <stop offset="100%" stop-color="#0066ff"/>
      </linearGradient>
    </defs>
    <path id="wave" d="M0,100 Q150,50 300,100 T600,100 T900,100 T1200,100" fill="none" stroke="url(#waveGradient)" stroke-width="4">
      <animateTransform attributeName="transform" type="translate" from="0 0" to="-300 0" dur="6s" repeatCount="indefinite" />
    </path>
    <use href="#wave" transform="translate(0, 20)" />
    <use href="#wave" transform="translate(0, 40)" />
  </svg>

  <!-- Animated circuit lines -->
  <svg width="100%" height="100%" style="position:absolute; top:0; left:0; z-index:0; opacity:0.25;">
    <defs>
      <linearGradient id="glow" x1="0" x2="1" y1="0" y2="1">
        <stop offset="0%" stop-color="#00ccff"/>
        <stop offset="100%" stop-color="#0066ff"/>
      </linearGradient>
    </defs>
    <g stroke="url(#glow)" stroke-width="2">
      <path d="M0 20 H100 V60 H200 V40 H300 V80 H400" stroke-dasharray="8 8">
        <animate attributeName="stroke-dashoffset" from="100" to="0" dur="4s" repeatCount="indefinite" />
      </path>
      <path d="M400 100 H300 V140 H200 V120 H100 V160 H0" stroke-dasharray="10 10">
        <animate attributeName="stroke-dashoffset" from="0" to="100" dur="6s" repeatCount="indefinite" />
      </path>
    </g>
  </svg>

  <!-- Neon text -->
  <h1 style="
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      font-size: 3em;
      color: #00ccff;
      text-shadow:
        0 0 6px #00ccff,
        0 0 20px #00ccff,
        0 0 40px #0066ff,
        0 0 80px #0066ff;
      z-index:1;
      position:relative;
      animation: flicker 3s infinite alternate, pulse 4s ease-in-out infinite;
    ">
    👋 Hi, I’m Jakob Rønn
  </h1>

  <p style="
      color: #88ddee;
      font-size: 1.1em;
      max-width: 700px;
      margin: auto;
      z-index:1;
      position:relative;
      line-height: 1.5;
      animation: textPulse 4s ease-in-out infinite;
    ">
    Software Engineering Student @ Aalborg University — passionate about low-level programming, systems design, and compiler development.
  </p>

</div>

<style>
@keyframes flicker {
  0%, 19%, 21%, 23%, 25%, 54%, 56%, 100% {
    text-shadow:
      0 0 6px #00ccff,
      0 0 20px #00ccff,
      0 0 40px #0066ff,
      0 0 80px #0066ff;
  }
  20%, 24%, 55% {
    text-shadow: none;
  }
}

@keyframes pulse {
  0%, 100% {
    text-shadow:
      0 0 6px #00ccff,
      0 0 20px #00ccff,
      0 0 40px #0066ff,
      0 0 80px #0066ff;
    transform: scale(1);
  }
  50% {
    text-shadow:
      0 0 12px #00eaff,
      0 0 30px #00eaff,
      0 0 60px #0099ff,
      0 0 100px #0099ff;
    transform: scale(1.05);
  }
}

@keyframes textPulse {
  0%, 100% { color: #88ddee; }
  50% { color: #aaffff; }
}
</style>


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
