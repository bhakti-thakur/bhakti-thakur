<div align="center" style="font-family:-apple-system,Inter,Segoe UI,Roboto,Helvetica,Arial,sans-serif;line-height:1.6;color:var(--text-color,#1a1a1a);padding:24px;max-width:900px;margin:auto;">
  <style>
    @media (prefers-color-scheme: dark) {
      :root {
        --bg-color: #0d1117;
        --text-color: #e6edf3;
        --card-bg: #161b22;
        --accent: #58a6ff;
      }
    }
    @media (prefers-color-scheme: light) {
      :root {
        --bg-color: #ffffff;
        --text-color: #1a1a1a;
        --card-bg: #f6f8fa;
        --accent: #0969da;
      }
    }

    div[align="center"] {
      background: var(--bg-color);
      color: var(--text-color);
    }

    h1, h2, h3 {
      font-weight: 600;
      margin-bottom: 0.4em;
    }

    h1 { font-size: 1.9em; }
    h2 { font-size: 1.3em; border-bottom: 1px solid var(--accent); display:inline-block; padding-bottom:3px; margin-top:1.8em;}
    p { margin: 0.4em 0; }

    .intro { font-size: 1.05em; color: var(--text-color); margin-bottom: 1.5em; }

    .badge {
      display: inline-flex;
      align-items: center;
      background: var(--card-bg);
      border: 1px solid rgba(100,100,100,0.2);
      border-radius: 9999px;
      padding: 6px 12px;
      margin: 4px;
      font-size: 0.85em;
      transition: transform 0.2s ease-out;
    }

    .badge img {
      width: 16px;
      height: 16px;
      margin-right: 6px;
    }

    .badge:hover {
      transform: scale(1.08);
    }

    .project-card {
      background: var(--card-bg);
      border-radius: 10px;
      padding: 16px;
      margin: 14px 0;
      text-align: left;
      transition: transform 0.25s cubic-bezier(0.25, 1.25, 0.5, 1);
      border: 1px solid rgba(100,100,100,0.2);
    }

    .project-card:hover {
      transform: translateY(-4px);
    }

    .project-card a {
      color: var(--accent);
      text-decoration: none;
      font-weight: 500;
    }

    footer {
      margin-top: 40px;
      padding-top: 20px;
      border-top: 1px solid rgba(120,120,120,0.3);
    }

    .footer-icons a {
      margin: 0 10px;
      display: inline-block;
      transition: transform 0.2s ease;
    }

    .footer-icons a:hover {
      transform: scale(1.15);
    }

    .footer-icons img {
      width: 22px;
      height: 22px;
      opacity: 0.85;
    }

  </style>

  <h1>Bhakti</h1>
  <p class="intro"><strong>Power Platform Developer & Dynamics 365 CRM Developer</strong><br>
  Exploring Data Science, Machine Learning, and Full Stack Development.<br>
  Turning ideas into intelligent, automated experiences.</p>

  <h2>About Me</h2>
  <p>I work at the intersection of low-code automation and full-code development.</p>
  <p>Experienced in Dynamics 365, Power Platform, and CRM workflows.</p>
  <p>Interested in how data, design, and automation can simplify human decisions.</p>
  <p>Currently building <strong>SynthData.ai</strong> for my BE project.</p>
  <p>Always learning and exploring new technologies.</p>

  <h2>Tech Stack</h2>
  <div>
    <div class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"/>Python</div>
    <div class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg"/>Java</div>
    <div class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg"/>React</div>
    <div class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg"/>Next.js</div>
    <div class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg"/>Node.js</div>
    <div class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg"/>MongoDB</div>
    <div class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg"/>Firebase</div>
    <div class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"/>Git</div>
    <div class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"/>GitHub</div>
    <div class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg"/>Google Cloud</div>
    <div class="badge"><img src="https://img.icons8.com/color/48/000000/power-bi.png"/>Power BI</div>
    <div class="badge"><img src="https://img.icons8.com/color/48/000000/salesforce.png"/>Salesforce</div>
  </div>

  <h2>Featured Projects</h2>

  <div class="project-card">
    <h3>SynthData.ai</h3>
    <p>Generates realistic synthetic data that protects privacy while maintaining structure and statistical behavior.</p>
    <p><strong>Tech:</strong> Python, CTGANs, FastAPI, React Native</p>
    <a href="https://github.com/bhakti-thakur/SynthData">View on GitHub</a>
  </div>

  <div class="project-card">
    <h3>Dine-o-saur</h3>
    <p>A group-based web app that helps friends or couples decide where to eat through an interactive, no-login experience.</p>
    <p><strong>Tech:</strong> Next.js, Tailwind CSS, Firebase Firestore</p>
    <a href="https://github.com/bhakti-thakur/Dine-o-saur">View on GitHub</a>
  </div>

  <div class="project-card">
    <h3>Naukri Automator</h3>
    <p>Automates Naukri profile updates using Puppeteer and Node.js for daily activity optimization.</p>
    <p><strong>Tech:</strong> Node.js, Puppeteer, Express, JSON storage</p>
    <a href="https://github.com/bhakti-thakur/naukriAutomator">View on GitHub</a>
  </div>

  <div class="project-card">
    <h3>InsuraTrack</h3>
    <p>Built CRM workflows to manage insurance and EMI tracking using Salesforce. Demonstrated scalable CRM design principles.</p>
    <p><strong>Tech:</strong> Salesforce (custom objects, dashboards, automations)</p>
    <p>Work in progress</p>
  </div>

  <h2>GitHub Stats</h2>
  <img src="https://github-readme-stats.vercel.app/api?username=bhakti-thakur&show_icons=true&theme=transparent&hide_border=true" width="49%">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=bhakti-thakur&theme=transparent&hide_border=true" width="49%">
  <br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhakti-thakur&layout=compact&theme=transparent&hide_border=true" width="60%">

  <footer>
    <div class="footer-icons">
      <a href="#" title="LinkedIn"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg"/></a>
      <a href="#" title="Email"><img src="https://img.icons8.com/fluency-systems-regular/48/000000/new-post.png"/></a>
      <a href="#" title="Resume"><img src="https://img.icons8.com/fluency-systems-regular/48/000000/open-resume.png"/></a>
    </div>
    <p style="font-size:0.85em;opacity:0.8;margin-top:12px;">Building systems that think clearly, so people can too.</p>
  </footer>
</div>
