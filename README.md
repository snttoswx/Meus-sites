<style>
  @keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
  }
  
  @keyframes glow {
    0%, 100% { filter: drop-shadow(0 0 5px rgba(255,255,255,0.3)); }
    50% { filter: drop-shadow(0 0 15px rgba(255,255,255,0.6)); }
  }
  
  @keyframes shake {
    0%, 100% { transform: rotate(0deg); }
    25% { transform: rotate(2deg); }
    75% { transform: rotate(-2deg); }
  }
  
  .animated-stats {
    animation: float 3s ease-in-out infinite;
  }
  
  .animated-gif {
    animation: shake 4s ease-in-out infinite, glow 2s ease-in-out infinite;
    border-radius: 20px;
    transition: all 0.3s ease;
  }
  
  .animated-gif:hover {
    transform: scale(1.05);
    animation: glow 1s ease-in-out infinite;
  }
  
  .tech-icon {
    transition: all 0.3s ease;
    animation: float 4s ease-in-out infinite;
    animation-delay: calc(var(--i) * 0.5s);
  }
  
  .tech-icon:hover {
    transform: scale(1.2) rotate(10deg);
    animation: none;
  }
  
  .social-badge {
    transition: all 0.3s ease;
    position: relative;
    overflow: hidden;
  }
  
  .social-badge::before {
    content: '';
    position: absolute;
    top: 0;
    left: -100%;
    width: 100%;
    height: 100%;
    background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
    transition: left 0.5s;
  }
  
  .social-badge:hover::before {
    left: 100%;
  }
  
  .social-badge:hover {
    transform: translateY(-3px);
    filter: brightness(1.2);
  }
  
  body {
    background: linear-gradient(135deg, #0d1117 0%, #161b22 100%);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
</style>

<h2 align="left" style="background: linear-gradient(45deg, #FF6B6B, #4ECDC4); -webkit-background-clip: text; -webkit-text-fill-color: transparent; animation: glow 2s ease-in-out infinite;">Hi 👋! My name is iago, from brazil</h2>

###

<div align="center">
  <div class="animated-stats">
    <img src="https://github-readme-stats.vercel.app/api?username=maurodesouza&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false" height="150" alt="stats graph" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=maurodesouza&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" height="150" alt="languages graph" />
  </div>
</div>

###

<img align="right" height="150" src="https://github.com/snttoswx/SaintsDeveloper/blob/main/download.gif" alt="gif do pinterest" class="animated-gif" />

###

<div align="left">
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="javascript logo" class="tech-icon" style="--i: 0" />
  </a>
  <img width="12" />
  <a href="https://www.typescriptlang.org/" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="30" alt="typescript logo" class="tech-icon" style="--i: 1" />
  </a>
  <img width="12" />
  <a href="https://reactjs.org/" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" alt="react logo" class="tech-icon" style="--i: 2" />
  </a>
  <img width="12" />
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo" class="tech-icon" style="--i: 3" />
  </a>
  <img width="12" />
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo" class="tech-icon" style="--i: 4" />
  </a>
  <img width="12" />
  <a href="https://www.python.org/" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="python logo" class="tech-icon" style="--i: 5" />
  </a>
  <img width="12" />
  <a href="https://learn.microsoft.com/en-us/dotnet/csharp/" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="30" alt="csharp logo" class="tech-icon" style="--i: 6" />
  </a>
</div>

###

<div align="left">
  <a href="https://www.instagram.com/rochwxs" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo" class="social-badge" />
  </a>
  <a href="https://discord.gg/snttoswx" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=7289DA&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="discord logo" class="social-badge" />
  </a>
</div>

###

<br clear="both">
