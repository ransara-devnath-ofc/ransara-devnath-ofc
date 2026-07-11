<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&family=Space+Mono:wght@400;700&display=swap');
  
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  :root {
    --primary: #cba6f7;
    --secondary: #89b4fa;
    --tertiary: #581c87;
    --dark-bg: #0f172a;
    --card-bg: #1e1b4b;
    --text-primary: #cbd5e1;
    --text-secondary: #94a3b8;
    --accent: #7c3aed;
  }

  @keyframes fadeInDown {
    from {
      opacity: 0;
      transform: translateY(-30px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes fadeInUp {
    from {
      opacity: 0;
      transform: translateY(30px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes slideInLeft {
    from {
      opacity: 0;
      transform: translateX(-50px);
    }
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }

  @keyframes slideInRight {
    from {
      opacity: 0;
      transform: translateX(50px);
    }
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }

  @keyframes glow {
    0%, 100% {
      box-shadow: 0 0 20px rgba(203, 166, 247, 0.3), 0 0 40px rgba(137, 180, 250, 0.2);
    }
    50% {
      box-shadow: 0 0 30px rgba(203, 166, 247, 0.5), 0 0 60px rgba(137, 180, 250, 0.3);
    }
  }

  @keyframes float {
    0%, 100% {
      transform: translateY(0px);
    }
    50% {
      transform: translateY(-15px);
    }
  }

  @keyframes pulse {
    0%, 100% {
      opacity: 1;
    }
    50% {
      opacity: 0.7;
    }
  }

  @keyframes shimmer {
    0% {
      background-position: -1000px 0;
    }
    100% {
      background-position: 1000px 0;
    }
  }

  @keyframes rotateGradient {
    0% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
    100% {
      background-position: 0% 50%;
    }
  }

  @keyframes bounce {
    0%, 100% {
      transform: translateY(0);
    }
    50% {
      transform: translateY(-10px);
    }
  }

  @keyframes blinkGlow {
    0%, 100% {
      opacity: 1;
      filter: drop-shadow(0 0 10px rgba(203, 166, 247, 0.5));
    }
    50% {
      opacity: 0.8;
      filter: drop-shadow(0 0 20px rgba(203, 166, 247, 0.8));
    }
  }
</style>

<!-- ========== ANIMATED HEADER ========== -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=cba6f7,89b4fa,581c87&height=300&section=header&text=👋%20Welcome%20Aboard!&fontSize=70&fontColor=cbd5e1&animation=fadeIn&rotate=-5&fontAlignY=40&descAlign=70&desc=Full%20Stack%20Developer%20%7C%20AI%20Explorer%20%7C%20Creative%20Coder"/>
    <img alt="Header" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=cba6f7,89b4fa,581c87&height=300&section=header&text=👋%20Welcome%20Aboard!&fontSize=70&fontColor=cbd5e1&animation=fadeIn"/>
  </picture>
</div>

---

<!-- ========== HERO PROFILE SECTION ========== -->
<div align="center" style="animation: fadeInDown 0.8s ease-out;">
  <table border="0" cellpadding="0" cellspacing="0" width="100%" style="max-width: 1000px; margin: 0 auto;">
    <tr>
      <td width="40%" align="center" valign="middle" style="animation: slideInLeft 1s ease-out;">
        <div style="position: relative; display: inline-block; animation: float 3s ease-in-out infinite;">
          <div style="
            position: absolute;
            inset: -8px;
            background: linear-gradient(135deg, #cba6f7, #89b4fa, #7c3aed);
            border-radius: 25px;
            opacity: 0.5;
            animation: rotateGradient 6s ease-in-out infinite;
            background-size: 300% 300%;
            blur: 20px;
          "></div>
          <img 
            src="https://github.com/ransara-devnath-ofc.png" 
            width="200" 
            height="200" 
            alt="Ransara Devnath" 
            style="
              border-radius: 25px;
              border: 4px solid #cba6f7;
              box-shadow: 0 0 40px rgba(203, 166, 247, 0.4);
              position: relative;
              z-index: 1;
              animation: glow 2s ease-in-out infinite;
              transition: transform 0.3s ease;
            "
            onmouseover="this.style.transform='scale(1.05)'"
            onmouseout="this.style.transform='scale(1)'"
          />
        </div>
      </td>
      
      <td width="60%" valign="middle" style="padding: 30px 50px; animation: slideInRight 1s ease-out;">
        <div align="left">
          <h1 style="
            margin: 0;
            font-size: 3.2em;
            font-weight: 800;
            background: linear-gradient(135deg, #cba6f7 0%, #89b4fa 50%, #7c3aed 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            font-family: 'Poppins', sans-serif;
            letter-spacing: -1px;
            animation: fadeInDown 1s ease-out;
          ">
            Ransara Devnath
          </h1>
          
          <p style="
            font-size: 1.4em;
            background: linear-gradient(90deg, #89b4fa 0%, #cba6f7 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin: 15px 0;
            font-weight: 600;
            animation: fadeInUp 1.2s ease-out;
            font-family: 'Poppins', sans-serif;
          ">
            🚀 Full Stack Developer × 🤖 AI Explorer × ✨ UI/UX Enthusiast
          </p>
          
          <p style="
            font-size: 1em;
            color: #cbd5e1;
            line-height: 1.8;
            margin-top: 20px;
            animation: fadeInUp 1.4s ease-out;
            font-family: 'Poppins', sans-serif;
          ">
            <strong>16-year-old developer</strong> from <strong style="color: #cba6f7;">Matara, Sri Lanka 🇱🇰</strong> crafting <strong>high-performance interfaces</strong> and exploring <strong>cutting-edge AI technologies</strong>. Passionate about turning <strong>ideas into reality</strong> with elegant code and creative design.
          </p>
          
          <div style="
            margin-top: 25px;
            animation: fadeInUp 1.6s ease-out;
          ">
            <img 
              src="https://komarev.com/ghpvc/?username=ransara-devnath-ofc&label=Profile%20Views&color=cba6f7&style=flat-square" 
              alt="Profile Views"
              style="animation: pulse 2s ease-in-out infinite;"
            />
          </div>
        </div>
      </td>
    </tr>
  </table>
</div>

---

<!-- ========== ANIMATED CTA BUTTONS ========== -->
<div align="center" style="margin: 40px 0; animation: fadeInUp 1.8s ease-out;">
  <style>
    .cta-btn {
      display: inline-block;
      padding: 14px 32px;
      margin: 10px 12px;
      border-radius: 50px;
      font-weight: 700;
      font-size: 1.05em;
      text-decoration: none;
      transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
      font-family: 'Poppins', sans-serif;
      border: 2px solid transparent;
      position: relative;
      overflow: hidden;
      animation: bounce 2s ease-in-out infinite;
    }

    .cta-btn::before {
      content: '';
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
      transition: left 0.5s;
      z-index: 1;
    }

    .cta-btn:hover::before {
      left: 100%;
    }

    .cta-primary {
      background: linear-gradient(135deg, #cba6f7 0%, #89b4fa 100%);
      color: #0f172a;
      box-shadow: 0 10px 30px rgba(203, 166, 247, 0.3);
    }

    .cta-primary:hover {
      transform: translateY(-4px);
      box-shadow: 0 20px 50px rgba(203, 166, 247, 0.5);
    }

    .cta-secondary {
      background: rgba(203, 166, 247, 0.1);
      color: #cba6f7;
      border: 2px solid #cba6f7;
      backdrop-filter: blur(10px);
    }

    .cta-secondary:hover {
      background: rgba(203, 166, 247, 0.2);
      transform: translateY(-4px);
      box-shadow: 0 15px 40px rgba(203, 166, 247, 0.2);
    }
  </style>

  <a href="https://ransara-devnath.vercel.app/" target="_blank" class="cta-btn cta-primary">
    🌐 View Portfolio
  </a>
  <a href="https://ransgpt-v3-ai.netlify.app/" target="_blank" class="cta-btn cta-primary">
    🤖 Try RansGPT AI
  </a>
  <a href="https://github.com/ransara-devnath-ofc" target="_blank" class="cta-btn cta-secondary">
    💻 GitHub Profile
  </a>
</div>

---

<!-- ========== ABOUT ME SECTION ========== -->
<div align="center" style="animation: fadeInUp 2s ease-out; margin-bottom: 50px;">
  <h2 style="
    font-size: 2.8em;
    color: #cba6f7;
    margin-bottom: 40px;
    font-family: 'Poppins', sans-serif;
    font-weight: 800;
  ">
    ✨ About Me
  </h2>

  <style>
    .about-card {
      background: linear-gradient(135deg, rgba(30, 27, 75, 0.8) 0%, rgba(45, 27, 78, 0.8) 100%);
      border: 1px solid rgba(203, 166, 247, 0.2);
      border-radius: 20px;
      padding: 40px;
      margin: 20px auto;
      max-width: 500px;
      backdrop-filter: blur(10px);
      box-shadow: 0 8px 32px rgba(203, 166, 247, 0.1);
      transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
      animation: fadeInUp 2.2s ease-out;
    }

    .about-card:hover {
      transform: translateY(-8px);
      border-color: rgba(203, 166, 247, 0.5);
      box-shadow: 0 20px 60px rgba(203, 166, 247, 0.2);
      background: linear-gradient(135deg, rgba(30, 27, 75, 0.95) 0%, rgba(45, 27, 78, 0.95) 100%);
    }

    .about-card h3 {
      color: #cba6f7;
      font-size: 1.6em;
      margin-bottom: 20px;
      font-family: 'Poppins', sans-serif;
      font-weight: 700;
    }

    .about-card p {
      color: #cbd5e1;
      line-height: 1.8;
      font-size: 1.05em;
      font-family: 'Poppins', sans-serif;
    }
  </style>

  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 30px; max-width: 1100px; margin: 0 auto;">
    <div class="about-card">
      <h3>🎯 My Mission</h3>
      <p>
        Building elegant, performant web experiences with modern technologies while constantly exploring AI possibilities to create innovative solutions that matter.
      </p>
    </div>
    
    <div class="about-card" style="animation-delay: 0.2s;">
      <h3>🌟 Focus Areas</h3>
      <p>
        <strong style="color: #89b4fa;">Frontend Mastery:</strong> React, Tailwind CSS<br/><br/>
        <strong style="color: #89b4fa;">Backend Power:</strong> Node.js, Express<br/><br/>
        <strong style="color: #89b4fa;">AI Integration:</strong> OpenAI APIs, ML Models
      </p>
    </div>
  </div>
</div>

---

<!-- ========== TECH STACK SECTION ========== -->
<div align="center" style="animation: fadeInUp 2.4s ease-out; margin: 50px 0;">
  <h2 style="
    font-size: 2.8em;
    color: #cba6f7;
    margin-bottom: 40px;
    font-family: 'Poppins', sans-serif;
    font-weight: 800;
  ">
    🛠️ Tech Stack
  </h2>

  <style>
    .tech-container {
      background: linear-gradient(135deg, rgba(15, 23, 42, 0.9) 0%, rgba(30, 27, 75, 0.9) 100%);
      border: 1px solid rgba(203, 166, 247, 0.2);
      border-radius: 25px;
      padding: 50px;
      max-width: 1000px;
      margin: 0 auto;
      backdrop-filter: blur(10px);
      box-shadow: 0 8px 32px rgba(203, 166, 247, 0.1);
      animation: glow 3s ease-in-out infinite;
    }

    .tech-category {
      margin-bottom: 40px;
      animation: fadeInUp 2.6s ease-out;
    }

    .tech-category h3 {
      color: #89b4fa;
      font-size: 1.3em;
      margin-bottom: 20px;
      font-family: 'Poppins', sans-serif;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    .tech-badge {
      display: inline-block;
      margin: 8px 6px;
      transition: all 0.3s ease;
      animation: fadeInUp 2.8s ease-out;
    }

    .tech-badge:hover {
      transform: translateY(-5px) scale(1.08);
      filter: drop-shadow(0 10px 20px rgba(203, 166, 247, 0.4));
    }

    .tech-badge img {
      border-radius: 8px;
      transition: all 0.3s ease;
    }

    .tech-badge:hover img {
      filter: brightness(1.2) drop-shadow(0 0 15px rgba(203, 166, 247, 0.5));
    }
  </style>

  <div class="tech-container">
    <div class="tech-category">
      <h3>💻 Languages & Frameworks</h3>
      <div>
        <span class="tech-badge"><img src="https://img.shields.io/badge/HTML5-E34C26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/></span>
      </div>
    </div>

    <div class="tech-category" style="animation-delay: 0.2s;">
      <h3>⚙️ Backend & Tools</h3>
      <div>
        <span class="tech-badge"><img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/MongoDB-13AA52?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/></span>
      </div>
    </div>

    <div class="tech-category" style="animation-delay: 0.4s;">
      <h3>🎨 Design & Deployment</h3>
      <div>
        <span class="tech-badge"><img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel"/></span>
        <span class="tech-badge"><img src="https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Netlify"/></span>
      </div>
    </div>
  </div>
</div>

---

<!-- ========== GITHUB STATS SECTION ========== -->
<div align="center" style="animation: fadeInUp 2.6s ease-out; margin: 50px 0;">
  <h2 style="
    font-size: 2.8em;
    color: #cba6f7;
    margin-bottom: 40px;
    font-family: 'Poppins', sans-serif;
    font-weight: 800;
  ">
    📊 GitHub Analytics
  </h2>

  <style>
    .stats-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 30px;
      max-width: 1100px;
      margin: 0 auto 40px;
      animation: fadeInUp 2.8s ease-out;
    }

    .stats-card {
      background: linear-gradient(135deg, rgba(30, 27, 75, 0.8) 0%, rgba(45, 27, 78, 0.8) 100%);
      border: 1px solid rgba(203, 166, 247, 0.2);
      border-radius: 20px;
      padding: 25px;
      backdrop-filter: blur(10px);
      transition: all 0.4s ease;
      animation: fadeInUp 2.8s ease-out;
    }

    .stats-card:hover {
      transform: translateY(-8px);
      border-color: rgba(203, 166, 247, 0.5);
      box-shadow: 0 20px 60px rgba(203, 166, 247, 0.2);
    }

    .stats-card img {
      width: 100%;
      border-radius: 15px;
      transition: filter 0.3s ease;
    }

    .stats-card:hover img {
      filter: drop-shadow(0 0 20px rgba(203, 166, 247, 0.3));
    }

    @media (max-width: 768px) {
      .stats-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>

  <div class="stats-grid">
    <div class="stats-card">
      <img src="https://github-readme-stats.vercel.app/api?username=ransara-devnath-ofc&show_icons=true&theme=tokyonight&hide_border=true&border_radius=16&bg_color=0f172a00&text_color=cbd5e1&title_color=cba6f7&icon_color=89b4fa" alt="GitHub Stats"/>
    </div>
    <div class="stats-card" style="animation-delay: 0.2s;">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ransara-devnath-ofc&layout=compact&theme=tokyonight&hide_border=true&border_radius=16&bg_color=0f172a00&text_color=cbd5e1&title_color=cba6f7" alt="Top Languages"/>
    </div>
  </div>

  <div style="animation: fadeInUp 3s ease-out;">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=ransara-devnath-ofc&theme=tokyonight&hide_border=true&background=0f172a00&stroke=cba6f7&ring=89b4fa&fire=cba6f7&currStreakNum=cbd5e1&sideNums=cbd5e1" alt="GitHub Streak"/>
  </div>
</div>

---

<!-- ========== CONTRIBUTION ACTIVITY ========== -->
<div align="center" style="animation: fadeInUp 3.2s ease-out; margin: 50px 0;">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ransara-devnath-ofc&custom_title=Contribution%20Graph&bg_color=0f172a&color=cba6f7&line=89b4fa&point=89b4fa&area_color=cba6f7&area=true" alt="Contribution Graph"/>
</div>

---

<!-- ========== FEATURED PROJECTS ========== -->
<div align="center" style="animation: fadeInUp 3.4s ease-out; margin: 60px 0;">
  <h2 style="
    font-size: 2.8em;
    color: #cba6f7;
    margin-bottom: 50px;
    font-family: 'Poppins', sans-serif;
    font-weight: 800;
  ">
    💼 Featured Projects
  </h2>

  <style>
    .projects-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 35px;
      max-width: 1100px;
      margin: 0 auto;
    }

    .project-card {
      background: linear-gradient(135deg, rgba(30, 27, 75, 0.9) 0%, rgba(45, 27, 78, 0.9) 100%);
      border: 1px solid rgba(203, 166, 247, 0.2);
      border-radius: 20px;
      padding: 40px 30px;
      backdrop-filter: blur(10px);
      box-shadow: 0 8px 32px rgba(203, 166, 247, 0.1);
      transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
      position: relative;
      overflow: hidden;
      animation: fadeInUp 3.4s ease-out;
    }

    .project-card::before {
      content: '';
      position: absolute;
      top: -50%;
      right: -50%;
      width: 100%;
      height: 100%;
      background: radial-gradient(circle, rgba(203, 166, 247, 0.1) 0%, transparent 70%);
      transition: all 0.6s ease;
      opacity: 0;
    }

    .project-card:hover::before {
      opacity: 1;
      top: -25%;
      right: -25%;
    }

    .project-card:hover {
      transform: translateY(-12px) scale(1.02);
      border-color: rgba(203, 166, 247, 0.5);
      box-shadow: 0 25px 70px rgba(203, 166, 247, 0.25);
    }

    .project-icon {
      font-size: 3.5em;
      margin-bottom: 20px;
      animation: bounce 2s ease-in-out infinite;
    }

    .project-card:nth-child(2) .project-icon {
      animation-delay: 0.5s;
    }

    .project-card h3 {
      color: #cba6f7;
      font-size: 1.6em;
      margin: 20px 0;
      font-family: 'Poppins', sans-serif;
      font-weight: 700;
      position: relative;
      z-index: 1;
    }

    .project-card p {
      color: #cbd5e1;
      line-height: 1.8;
      font-size: 1em;
      min-height: 80px;
      margin: 20px 0;
      font-family: 'Poppins', sans-serif;
      position: relative;
      z-index: 1;
    }

    .project-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin: 20px 0;
      justify-content: center;
      position: relative;
      z-index: 1;
    }

    .project-tag {
      background: linear-gradient(135deg, rgba(92, 28, 135, 0.4) 0%, rgba(124, 58, 237, 0.4) 100%);
      border: 1px solid rgba(203, 166, 247, 0.3);
      color: #89b4fa;
      padding: 6px 14px;
      border-radius: 20px;
      font-size: 0.85em;
      font-weight: 600;
      backdrop-filter: blur(5px);
      transition: all 0.3s ease;
      font-family: 'Poppins', sans-serif;
    }

    .project-tag:hover {
      border-color: rgba(203, 166, 247, 0.6);
      background: linear-gradient(135deg, rgba(92, 28, 135, 0.6) 0%, rgba(124, 58, 237, 0.6) 100%);
      transform: translateY(-2px);
    }

    .project-link {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 28px;
      background: linear-gradient(135deg, #cba6f7 0%, #89b4fa 100%);
      color: #0f172a;
      text-decoration: none;
      border-radius: 25px;
      font-weight: 700;
      font-family: 'Poppins', sans-serif;
      transition: all 0.3s ease;
      position: relative;
      z-index: 2;
      box-shadow: 0 8px 20px rgba(203, 166, 247, 0.3);
    }

    .project-link:hover {
      transform: translateY(-4px);
      box-shadow: 0 15px 35px rgba(203, 166, 247, 0.4);
      letter-spacing: 1px;
    }

    @media (max-width: 768px) {
      .projects-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>

  <div class="projects-grid">
    <div class="project-card">
      <div class="project-icon">🤖</div>
      <h3>RansGPT AI</h3>
      <p>Advanced AI-powered chatbot with real-time responsiveness, custom modules, and seamless OpenAI integration. Built with modern React and styled with Tailwind CSS for optimal UX.</p>
      <div class="project-tags">
        <span class="project-tag">React</span>
        <span class="project-tag">OpenAI</span>
        <span class="project-tag">Tailwind</span>
        <span class="project-tag">Node.js</span>
      </div>
      <a href="https://ransgpt-v3-ai.netlify.app/" target="_blank" class="project-link">
        Explore Project →
      </a>
    </div>

    <div class="project-card" style="animation-delay: 0.2s;">
      <div class="project-icon">🌐</div>
      <h3>Portfolio Website</h3>
      <p>Professional portfolio website showcasing projects, skills, and achievements with smooth animations and modern design. Fully responsive with dark mode support and performance optimized.</p>
      <div class="project-tags">
        <span class="project-tag">Next.js</span>
        <span class="project-tag">Tailwind</span>
        <span class="project-tag">Framer</span>
        <span class="project-tag">Vercel</span>
      </div>
      <a href="https://ransara-devnath.vercel.app/" target="_blank" class="project-link">
        Explore Project →
      </a>
    </div>
  </div>
</div>

---

<!-- ========== CALL TO ACTION ========== -->
<div align="center" style="animation: fadeInUp 3.6s ease-out; margin: 60px 0;">
  <style>
    .cta-section {
      background: linear-gradient(135deg, rgba(30, 27, 75, 0.95) 0%, rgba(45, 27, 78, 0.95) 100%);
      border: 2px solid rgba(203, 166, 247, 0.3);
      border-radius: 25px;
      padding: 50px 40px;
      max-width: 900px;
      margin: 0 auto;
      backdrop-filter: blur(10px);
      box-shadow: 0 8px 32px rgba(203, 166, 247, 0.15);
      animation: glow 3s ease-in-out infinite;
    }

    .cta-section:hover {
      border-color: rgba(203, 166, 247, 0.6);
      box-shadow: 0 15px 50px rgba(203, 166, 247, 0.3);
    }

    .cta-section h2 {
      color: #cba6f7;
      font-size: 2.2em;
      margin-bottom: 15px;
      font-family: 'Poppins', sans-serif;
      font-weight: 800;
    }

    .cta-section p {
      color: #cbd5e1;
      font-size: 1.15em;
      margin-bottom: 30px;
      font-family: 'Poppins', sans-serif;
      line-height: 1.6;
    }

    .social-links {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .social-icon {
      display: inline-block;
      width: 50px;
      height: 50px;
      border-radius: 50%;
      background: linear-gradient(135deg, rgba(203, 166, 247, 0.1) 0%, rgba(137, 180, 250, 0.1) 100%);
      border: 2px solid rgba(203, 166, 247, 0.3);
      display: flex;
      align-items: center;
      justify-content: center;
      transition: all 0.3s ease;
      font-size: 1.5em;
      backdrop-filter: blur(5px);
    }

    .social-icon:hover {
      transform: translateY(-8px) scale(1.15);
      border-color: rgba(203, 166, 247, 0.8);
      background: linear-gradient(135deg, rgba(203, 166, 247, 0.2) 0%, rgba(137, 180, 250, 0.2) 100%);
      box-shadow: 0 10px 30px rgba(203, 166, 247, 0.3);
    }
  </style>

  <div class="cta-section">
    <h2>🤝 Let's Connect & Create!</h2>
    <p>Always open to collaborate on exciting projects, discuss innovative ideas, and build something amazing together. Let's turn your vision into reality! 🚀</p>
    
    <div class="social-links">
      <a href="https://wa.me/message/XQZHYHBQ3E47I1" target="_blank" class="social-icon" title="WhatsApp">
        <img src="https://img.shields.io/badge/💬-white?style=flat" alt="WhatsApp" style="width: 25px; height: 25px;"/>
      </a>
      <a href="mailto:ransaramax87@gmail.com" target="_blank" class="social-icon" title="Email">
        <img src="https://img.shields.io/badge/📧-white?style=flat" alt="Email" style="width: 25px; height: 25px;"/>
      </a>
      <a href="https://github.com/ransara-devnath-ofc" target="_blank" class="social-icon" title="GitHub">
        <img src="https://img.shields.io/badge/💻-white?style=flat" alt="GitHub" style="width: 25px; height: 25px;"/>
      </a>
      <a href="https://linkedin.com/in/ransara-devnath" target="_blank" class="social-icon" title="LinkedIn">
        <img src="https://img.shields.io/badge/🔗-white?style=flat" alt="LinkedIn" style="width: 25px; height: 25px;"/>
      </a>
      <a href="https://twitter.com/ransara_dev" target="_blank" class="social-icon" title="Twitter">
        <img src="https://img.shields.io/badge/𝕏-white?style=flat" alt="Twitter" style="width: 25px; height: 25px;"/>
      </a>
    </div>
  </div>
</div>

---

<!-- ========== ANIMATED FOOTER ========== -->
<div align="center" style="animation: fadeInUp 3.8s ease-out; margin-top: 50px;">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=cba6f7,89b4fa,581c87&height=120&section=footer&animation=fadeIn&rotate=180"/>
    <img alt="Footer" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=cba6f7,89b4fa,581c87&height=120&section=footer&animation=fadeIn"/>
  </picture>

  <p style="
    color: #94a3b8;
    font-family: 'Poppins', sans-serif;
    font-size: 1.1em;
    margin-top: 30px;
    margin-bottom: 15px;
    font-weight: 700;
  ">
    © 2026 Ransara Devnath • All Rights Reserved
  </p>

  <p style="
    color: #64748b;
    font-family: 'Poppins', sans-serif;
    font-size: 0.95em;
    margin: 10px 0;
    line-height: 1.8;
  ">
    Crafted with 💜 <strong>passion</strong> • Designed for 🚀 <strong>impact</strong> • Built with ⚡ <strong>precision</strong>
  </p>

  <p style="
    color: #475569;
    font-family: 'Space Mono', monospace;
    font-size: 0.9em;
    font-style: italic;
    margin: 15px 0;
    animation: blinkGlow 3s ease-in-out infinite;
  ">
    <i>"Continuous growth through code, creativity, and curiosity" 🌟</i>
  </p>
</div>

---

<div align="center" style="
  margin-top: 40px;
  padding: 30px;
  border-top: 1px solid rgba(203, 166, 247, 0.2);
  animation: fadeInUp 4s ease-out;
">
  <p style="
    color: #cbd5e1;
    font-family: 'Poppins', sans-serif;
    font-size: 0.95em;
    margin: 0;
  ">
    ✨ <strong>Last Updated:</strong> 2026 • <strong>Status:</strong> <span style="color: #89b4fa;">🟢 Active & Growing</span>
  </p>
</div>