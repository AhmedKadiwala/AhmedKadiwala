<div align="center">

<!-- Animated Header with Interactive Elements -->
<div style="
  position: relative;
  padding: 2.5rem;
  margin: 2rem 0;
  border-radius: 24px;
  background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
  border: 1px solid rgba(0, 184, 148, 0.3);
  box-shadow: 0 10px 40px rgba(0, 184, 148, 0.2);
  overflow: hidden;
">
  <img src="car.gif" alt="Developer Banner" width="85%" style="border-radius: 12px; border: 2px solid rgba(255, 255, 255, 0.1);" />
  
  <!-- Profile View Counter -->
  <div style="
    position: absolute;
    top: 20px;
    right: 20px;
    background: rgba(0, 0, 0, 0.6);
    padding: 8px 16px;
    border-radius: 20px;
    font-size: 14px;
    color: white;
    display: flex;
    align-items: center;
    gap: 8px;
  ">
    <span id="profileViews">Loading...</span>
    <span>👁️ Views</span>
  </div>
</div>

<script>
// Profile view counter with click tracking
document.addEventListener('DOMContentLoaded', function() {
  // Simulate view count increment (replace with actual tracking in production)
  let views = localStorage.getItem('profileViews') || 1000;
  views = parseInt(views) + 1;
  localStorage.setItem('profileViews', views);
  document.getElementById('profileViews').textContent = views.toLocaleString();
  
  // Track all link clicks
  document.querySelectorAll('a').forEach(link => {
    link.addEventListener('click', function() {
      let clickViews = localStorage.getItem('clickViews') || 0;
      clickViews = parseInt(clickViews) + 1;
      localStorage.setItem('clickViews', clickViews);
      views = parseInt(views) + 1;
      localStorage.setItem('profileViews', views);
      document.getElementById('profileViews').textContent = views.toLocaleString();
    });
  });
});
</script>

<!-- Dynamic Typing Intro with Interactive Background -->
<div style="
  background: linear-gradient(145deg, #0f2027, #203a43, #2c5364);
  padding: 2.5rem;
  border-radius: 18px;
  margin: 3rem 0;
  border-left: 5px solid #00b894;
  box-shadow: 0 10px 30px rgba(0, 184, 148, 0.15);
  position: relative;
  overflow: hidden;
">
  <div style="
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: radial-gradient(circle at 20% 30%, rgba(0, 184, 148, 0.1) 0%, transparent 50%);
    z-index: 0;
  "></div>
  
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=1200&pause=800&color=00B894&background=FFFFFF00&center=true&vCenter=true&multiline=true&width=900&height=300&lines=Hello+World!+👋;I'm+Ahmed+Kadiwala;Data+Science+Specialist;AI%2FML+Engineer;Full-Stack+Developer;Open-Source+Contributor" alt="Typing SVG" style="position: relative; z-index: 1;" />
  </a>
</div>

<!-- Section Divider with Animation -->
<div style="
  height: 4px;
  width: 80%;
  margin: 3rem auto;
  background: linear-gradient(90deg, transparent, #00b894, #0984e3, transparent);
  background-size: 200% 100%;
  animation: gradientMove 3s ease infinite;
  border-radius: 3px;
"></div>

<!-- GitHub Stats with Interactive Cards -->
<h2 style="
  color: #00b894;
  font-size: 2.2rem;
  margin: 2.5rem 0;
  text-shadow: 0 2px 10px rgba(0, 184, 148, 0.3);
">
  📊 GitHub Analytics
</h2>

<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 25px;
  margin: 2.5rem auto;
  max-width: 1200px;
">
  <!-- Stats Card with Click Tracking -->
  <a href="https://github.com/AhmedKadiwala" target="_blank" style="
    text-decoration: none;
    color: inherit;
  ">
    <div style="
      background: rgba(25, 25, 45, 0.9);
      backdrop-filter: blur(12px);
      border-radius: 18px;
      padding: 1.8rem;
      border: 1px solid rgba(255,255,255,0.15);
      box-shadow: 0 10px 35px rgba(0,0,0,0.25);
      transition: all 0.3s ease;
      &:hover {
        transform: translateY(-5px);
        box-shadow: 0 15px 40px rgba(0, 184, 148, 0.3);
      }
    ">
      <img src="https://github-readme-stats.vercel.app/api?username=AhmedKadiwala&show_icons=true&include_all_commits=true&count_private=true&theme=dark&hide_border=true&bg_color=00000000&title_color=00b894&icon_color=0984e3&text_color=ffffff" width="100%" alt="GitHub Stats" />
    </div>
  </a>
  
  <!-- Languages Card -->
  <a href="https://github.com/AhmedKadiwala?tab=repositories" target="_blank" style="
    text-decoration: none;
    color: inherit;
  ">
    <div style="
      background: rgba(25, 25, 45, 0.9);
      backdrop-filter: blur(12px);
      border-radius: 18px;
      padding: 1.8rem;
      border: 1px solid rgba(255,255,255,0.15);
      box-shadow: 0 10px 35px rgba(0,0,0,0.25);
      transition: all 0.3s ease;
      &:hover {
        transform: translateY(-5px);
        box-shadow: 0 15px 40px rgba(155, 89, 182, 0.3);
      }
    ">
      <img src="https://github-readme-stats.vercel.app/api/top-langs?username=AhmedKadiwala&layout=compact&langs_count=8&theme=dark&hide_border=true&bg_color=00000000&title_color=9b59b6&text_color=ffffff" width="100%" alt="Top Languages" />
    </div>
  </a>
  
  <!-- Streak Card -->
  <a href="https://github.com/AhmedKadiwala" target="_blank" style="
    text-decoration: none;
    color: inherit;
  ">
    <div style="
      background: rgba(25, 25, 45, 0.9);
      backdrop-filter: blur(12px);
      border-radius: 18px;
      padding: 1.8rem;
      border: 1px solid rgba(255,255,255,0.15);
      box-shadow: 0 10px 35px rgba(0,0,0,0.25);
      transition: all 0.3s ease;
      &:hover {
        transform: translateY(-5px);
        box-shadow: 0 15px 40px rgba(46, 204, 113, 0.3);
      }
    ">
      <img src="https://streak-stats.demolab.com?user=AhmedKadiwala&theme=dark&hide_border=true&background=00000000&ring=00b894&fire=00b894&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=ffffff&sideLabels=ffffff&dates=9e9e9e" width="100%" alt="GitHub Streak" />
    </div>
  </a>
</div>

<!-- Power BI Analytics Dashboard Section -->
<h2 style="
  color: #00b894;
  font-size: 2.2rem;
  margin: 3rem 0 2rem;
  text-shadow: 0 2px 10px rgba(0, 184, 148, 0.3);
">
  📈 Power BI Dashboards
</h2>

<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 25px;
  margin: 2rem auto;
  max-width: 1200px;
">
  <!-- Sales Dashboard -->
  <div style="
    background: rgba(30, 30, 50, 0.9);
    backdrop-filter: blur(10px);
    border-radius: 16px;
    padding: 1.5rem;
    border: 1px solid rgba(52, 152, 219, 0.3);
    box-shadow: 0 10px 30px rgba(52, 152, 219, 0.2);
    transition: transform 0.3s ease;
    &:hover {
      transform: translateY(-5px);
    }
  ">
    <h3 style="color: #3498db; margin-top: 0; font-size: 1.4rem;">📊 Sales Analytics</h3>
    <img src="https://raw.githubusercontent.com/microsoft/PowerBI-Icons/main/SVG/Dashboard.svg" width="80" style="display: block; margin: 0 auto 1rem; filter: invert(48%) sepia(79%) saturate(2476%) hue-rotate(176deg) brightness(118%) contrast(119%);" />
    <p style="text-align: center; margin-bottom: 1rem;">Interactive sales performance dashboard with regional breakdowns</p>
    <a href="#" target="_blank" style="
      display: block;
      text-align: center;
      padding: 10px;
      background: rgba(52, 152, 219, 0.2);
      border-radius: 8px;
      color: white;
      text-decoration: none;
      transition: all 0.3s ease;
      &:hover {
        background: rgba(52, 152, 219, 0.3);
      }
    ">
      View Dashboard
    </a>
  </div>

  <!-- Financial Dashboard -->
  <div style="
    background: rgba(30, 30, 50, 0.9);
    backdrop-filter: blur(10px);
    border-radius: 16px;
    padding: 1.5rem;
    border: 1px solid rgba(46, 204, 113, 0.3);
    box-shadow: 0 10px 30px rgba(46, 204, 113, 0.2);
    transition: transform 0.3s ease;
    &:hover {
      transform: translateY(-5px);
    }
  ">
    <h3 style="color: #2ecc71; margin-top: 0; font-size: 1.4rem;">💰 Financial Metrics</h3>
    <img src="https://raw.githubusercontent.com/microsoft/PowerBI-Icons/main/SVG/Report.svg" width="80" style="display: block; margin: 0 auto 1rem; filter: invert(48%) sepia(79%) saturate(2476%) hue-rotate(86deg) brightness(118%) contrast(119%);" />
    <p style="text-align: center; margin-bottom: 1rem;">Comprehensive financial reporting with predictive analytics</p>
    <a href="#" target="_blank" style="
      display: block;
      text-align: center;
      padding: 10px;
      background: rgba(46, 204, 113, 0.2);
      border-radius: 8px;
      color: white;
      text-decoration: none;
      transition: all 0.3s ease;
      &:hover {
        background: rgba(46, 204, 113, 0.3);
      }
    ">
      View Dashboard
    </a>
  </div>

  <!-- HR Dashboard -->
  <div style="
    background: rgba(30, 30, 50, 0.9);
    backdrop-filter: blur(10px);
    border-radius: 16px;
    padding: 1.5rem;
    border: 1px solid rgba(155, 89, 182, 0.3);
    box-shadow: 0 10px 30px rgba(155, 89, 182, 0.2);
    transition: transform 0.3s ease;
    &:hover {
      transform: translateY(-5px);
    }
  ">
    <h3 style="color: #9b59b6; margin-top: 0; font-size: 1.4rem;">👥 HR Analytics</h3>
    <img src="https://raw.githubusercontent.com/microsoft/PowerBI-Icons/main/SVG/Visual.svg" width="80" style="display: block; margin: 0 auto 1rem; filter: invert(48%) sepia(79%) saturate(2476%) hue-rotate(236deg) brightness(118%) contrast(119%);" />
    <p style="text-align: center; margin-bottom: 1rem;">Employee performance and retention analysis dashboard</p>
    <a href="#" target="_blank" style="
      display: block;
      text-align: center;
      padding: 10px;
      background: rgba(155, 89, 182, 0.2);
      border-radius: 8px;
      color: white;
      text-decoration: none;
      transition: all 0.3s ease;
      &:hover {
        background: rgba(155, 89, 182, 0.3);
      }
    ">
      View Dashboard
    </a>
  </div>
</div>

<!-- Tech Stack Section -->
<h2 style="
  color: #00b894;
  font-size: 2.2rem;
  margin: 3rem 0 2rem;
  text-shadow: 0 2px 10px rgba(0, 184, 148, 0.3);
">
  🛠️ Tech Stack
</h2>

<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 25px;
  margin: 2rem auto;
  max-width: 1200px;
">
  <!-- Web Development Card -->
  <div style="
    background: rgba(30, 30, 50, 0.9);
    backdrop-filter: blur(10px);
    border-radius: 16px;
    padding: 1.5rem;
    border: 1px solid rgba(0, 184, 148, 0.3);
    box-shadow: 0 10px 30px rgba(0, 184, 148, 0.2);
  ">
    <h3 style="color: #00b894; margin-top: 0; font-size: 1.4rem;">🌐 Web Development</h3>
    <div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/JavaScript.svg" height="45" title="JavaScript" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/React-Dark.svg" height="45" title="React" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/NextJS-Light.svg" height="45" title="Next.js" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/HTML.svg" height="45" title="HTML5" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/CSS.svg" height="45" title="CSS3" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/TailwindCSS-Light.svg" height="45" title="Tailwind CSS" />
    </div>
  </div>

  <!-- Data Science Card -->
  <div style="
    background: rgba(30, 30, 50, 0.9);
    backdrop-filter: blur(10px);
    border-radius: 16px;
    padding: 1.5rem;
    border: 1px solid rgba(155, 89, 182, 0.3);
    box-shadow: 0 10px 30px rgba(155, 89, 182, 0.2);
  ">
    <h3 style="color: #9b59b6; margin-top: 0; font-size: 1.4rem;">🧠 Data Science & AI</h3>
    <div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/Python-Dark.svg" height="45" title="Python" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="45" title="NumPy" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/TensorFlow-Dark.svg" height="45" title="TensorFlow" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/PyTorch-Light.svg" height="45" title="PyTorch" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" height="45" title="Pandas" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/openapi/openapi-original.svg" height="45" title="OpenAI" />
    </div>
  </div>

  <!-- Mobile & Backend Card -->
  <div style="
    background: rgba(30, 30, 50, 0.9);
    backdrop-filter: blur(10px);
    border-radius: 16px;
    padding: 1.5rem;
    border: 1px solid rgba(52, 152, 219, 0.3);
    box-shadow: 0 10px 30px rgba(52, 152, 219, 0.2);
  ">
    <h3 style="color: #3498db; margin-top: 0; font-size: 1.4rem;">📱 Mobile & Backend</h3>
    <div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/AndroidStudio-Light.svg" height="45" title="Android" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/Flutter-Light.svg" height="45" title="Flutter" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/NodeJS-Dark.svg" height="45" title="Node.js" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/ExpressJS-Light.svg" height="45" title="Express" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/Django.svg" height="45" title="Django" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original-wordmark.svg" height="45" title="FastAPI" />
    </div>
  </div>

  <!-- Databases & Tools Card -->
  <div style="
    background: rgba(30, 30, 50, 0.9);
    backdrop-filter: blur(10px);
    border-radius: 16px;
    padding: 1.5rem;
    border: 1px solid rgba(46, 204, 113, 0.3);
    box-shadow: 0 10px 30px rgba(46, 204, 113, 0.2);
  ">
    <h3 style="color: #2ecc71; margin-top: 0; font-size: 1.4rem;">🗄️ Databases & Tools</h3>
    <div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/MongoDB.svg" height="45" title="MongoDB" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/MySQL-Dark.svg" height="45" title="MySQL" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kaggle/kaggle-original-wordmark.svg" height="45" title="SQLite" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/Git.svg" height="45" title="Git" />
      <img src="https://cdn.jsdelivr.net/gh/tandpfun/skill-icons/icons/Github-Light.svg" height="45" title="GitHub" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postman/postman-original.svg" height="45" title="Postman" />
    </div>
  </div>
</div>

<!-- Connect Section with Interactive Elements -->
<h2 style="
  color: #00b894;
  font-size: 2.2rem;
  margin: 3rem 0 2rem;
  text-shadow: 0 2px 10px rgba(0, 184, 148, 0.3);
">
  🤝 Connect With Me
</h2>

<div style="
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  margin: 2rem auto;
  max-width: 1000px;
">
  <!-- Left Side: Animated GIF -->
  <div style="
    flex: 1;
    min-width: 300px;
    border-radius: 18px;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(0, 184, 148, 0.2);
  ">
    <img src="cart.gif" alt="Coding Animation" width="100%" style="display: block;" />
  </div>

  <!-- Right Side: Social Links with Hover Effects -->
  <div style="
    flex: 1;
    min-width: 300px;
    background: rgba(25, 25, 45, 0.9);
    backdrop-filter: blur(10px);
    border-radius: 18px;
    padding: 2rem;
    border: 1px solid rgba(255, 255, 255, 0.1);
    box-shadow: 0 10px 35px rgba(0, 0, 0, 0.25);
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 15px;
  ">
    <!-- LinkedIn -->
    <a href="https://www.linkedin.com/in/ahmed-kadiwala-789831265/" target="_blank" style="
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      padding: 12px;
      background: rgba(0, 119, 181, 0.1);
      border-radius: 10px;
      border: 1px solid rgba(0, 119, 181, 0.3);
      color: white;
      text-decoration: none;
      transition: all 0.3s ease;
    ">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="24" />
      <span>LinkedIn</span>
    </a>

    <!-- GitHub -->
    <a href="https://github.com/AhmedKadiwala" target="_blank" style="
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      padding: 12px;
      background: rgba(36, 41, 46, 0.1);
      border-radius: 10px;
      border: 1px solid rgba(36, 41, 46, 0.3);
      color: white;
      text-decoration: none;
      transition: all 0.3s ease;
    ">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="24" />
      <span>GitHub</span>
    </a>

    <!-- LeetCode -->
    <a href="https://leetcode.com/u/kadiwalaahmed7864/" target="_blank" style="
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      padding: 12px;
      background: rgba(255, 161, 22, 0.1);
      border-radius: 10px;
      border: 1px solid rgba(255, 161, 22, 0.3);
      color: white;
      text-decoration: none;
      transition: all 0.3s ease;
    ">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/leetcode/leetcode-original.svg" width="24" />
      <span>LeetCode</span>
    </a>

    <!-- Coding Ninjas -->
    <a href="https://www.naukri.com/code360/profile/42e53f5a-6b3f-4019-b0f8-2b398f69f48c" target="_blank" style="
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      padding: 12px;
      background: rgba(255, 87, 34, 0.1);
      border-radius: 10px;
      border: 1px solid rgba(255, 87, 34, 0.3);
      color: white;
      text-decoration: none;
      transition: all 0.3s ease;
    ">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" width="24" style="filter: brightness(0) invert(1);" />
      <span>Coding Ninjas</span>
    </a>

    <!-- Instagram -->
    <a href="https://www.instagram.com/sopln_apoorv.mehrotra/" target="_blank" style="
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      padding: 12px;
      background: rgba(228, 64, 95, 0.1);
      border-radius: 10px;
      border: 1px solid rgba(228, 64, 95, 0.3);
      color: white;
      text-decoration: none;
      transition: all 0.3s ease;
    ">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/instagram/instagram-original.svg" width="24" />
      <span>Instagram</span>
    </a>

    <!-- Medium -->
    <a href="https://medium.com/@be.uniqu..e" target="_blank" style="
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      padding: 12px;
      background: rgba(0, 0, 0, 0.1);
      border-radius: 10px;
      border: 1px solid rgba(0, 0, 0, 0.3);
      color: white;
      text-decoration: none;
      transition: all 0.3s ease;
    ">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/medium/medium-original.svg" width="24" />
      <span>Medium</span>
    </a>
  </div>
</div>

<!-- Dev Playground Section -->
<h2 style="
  color: #00b894;
  font-size: 2.2rem;
  margin: 3rem 0 2rem;
  text-shadow: 0 2px 10px rgba(0, 184, 148, 0.3);
">
  🚀 My Dev Playground
</h2>

<div style="
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  margin: 2rem auto;
  max-width: 1000px;
">
  <div style="
    flex: 1;
    min-width: 300px;
    border-radius: 18px;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(0, 184, 148, 0.2);
  ">
    <img src="dev.gif" alt="Development Animation" width="100%" />
  </div>
  <div style="
    flex: 1;
    min-width: 300px;
    background: rgba(25, 25, 45, 0.9);
    backdrop-filter: blur(10px);
    border-radius: 18px;
    padding: 2rem;
    border: 1px solid rgba(255, 255, 255, 0.1);
    box-shadow: 0 10px 35px rgba(0, 0, 0, 0.25);
    display: flex;
    flex-direction: column;
    justify-content: center;
  ">
    <img src="https://leetcode-badge-showcase.vercel.app/api?username=kadiwalaahmed7864&theme=dark&animated=true" width="100%" alt="LeetCode Stats" />
  </div>
</div>

<!-- Quote Section with Animated Border -->
<div style="
  margin: 4rem auto;
  max-width: 900px;
  position: relative;
  padding: 3px;
  border-radius: 18px;
  background: linear-gradient(45deg, #00b894, #0984e3, #9b59b6, #00b894);
  background-size: 300% 300%;
  animation: gradient 6s ease infinite;
">
  <div style="
    background: rgba(20, 20, 40, 0.9);
    border-radius: 16px;
    padding: 2rem;
    backdrop-filter: blur(8px);
  ">
    <h2 style="
      color: #f1c40f;
      font-size: 1.8rem;
      margin-top: 0;
      text-align: center;
      text-shadow: 0 2px 5px rgba(241, 196, 15, 0.3);
    ">
      💡 Daily Inspiration
    </h2>
    <a href="https://github.com/piyushsuthar/github-readme-quotes" target="_blank">
      <img 
        src="https://github-readme-quotes-bay.vercel.app/quote?theme=blueberry-dark&animation=default&layout=churchill&font=PixelifySans&quoteType=quote-for-the-day&bgColor=00000000&fontColor=f1c40f" 
        alt="Daily Quote"
        width="100%"
        style="border-radius: 12px;"
      />
    </a>
  </div>
</div>

<!-- Footer with View Counter -->
<div style="
  margin-top: 4rem;
  padding: 1.5rem;
  background: rgba(20, 20, 40, 0.7);
  border-top: 1px solid rgba(255, 255, 255, 0.1);
">
  <p align="center" style="margin: 0;">
    <img src="https://komarev.com/ghpvc/?username=AhmedKadiwala&label=Profile+Views&color=00b894&style=flat" alt="Profile Views" />
    <span style="margin: 0 10px;">•</span>
    Made with ❤️ using Markdown & GitHub
    <span style="margin: 0 10px;">•</span>
    Last updated: July 2024
  </p>
</div>

<style>
  @keyframes gradient {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  @keyframes gradientMove {
    0% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  
  /* Hover effects for all links */
  a:hover {
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0, 184, 148, 0.3);
  }
</style>
</div>
