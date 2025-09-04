<!--
  KARAK - Company Welcome / Profile HTML
  Place this block into your README.md (GitHub renders inline HTML inside Markdown).
  Replace placeholder links, usernames and the logo image as needed.
-->

<style>
  /* Basic reset for GitHub README context */
  .karak-wrap { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial; color: #0f172a; line-height:1.5; }
  .karak-card { max-width: 980px; margin: 24px auto; background: #ffffff; border-radius: 12px; box-shadow: 0 6px 22px rgba(2,6,23,0.06); padding: 28px; }
  .hero { display: flex; gap: 24px; align-items: center; flex-wrap: wrap; }
  .logo { width: 110px; height: 110px; border-radius: 14px; object-fit: cover; box-shadow: 0 6px 18px rgba(2,6,23,0.06); }
  .title { font-size: 28px; margin: 0; color: #0b1220; font-weight: 700; letter-spacing: -0.2px; }
  .tagline { margin: 6px 0 0; color: #334155; font-size: 14px; }
  .cta { margin-top: 12px; }
  .services { display: grid; grid-template-columns: repeat(auto-fit,minmax(220px,1fr)); gap: 12px; margin-top: 18px; }
  .service { background:#f8fafc; padding:12px; border-radius:10px; box-shadow: inset 0 1px 0 rgba(255,255,255,0.6); }
  .service h4 { margin:0 0 6px 0; font-size:16px; }
  .socials { display:flex; gap:8px; flex-wrap:wrap; align-items:center; margin-top:12px; }
  .badge { display:inline-block; height:34px; }
  .tech-grid { display:flex; gap:12px; flex-wrap:wrap; margin-top:18px; }
  .tech-item { text-align:center; width:72px; font-size:12px; color:#475569; }
  .tech-item img { width:48px; height:48px; object-fit:contain; margin-bottom:6px; }
  .about { margin-top:18px; color:#334155; }
  .stats { margin-top:18px; display:flex; flex-direction:column; gap:12px; align-items:center; }
  .metrics img { max-width:100%; border-radius:10px; }
  .contact { margin-top:20px; padding:12px; border-radius:8px; background:#0f172a; color:#fff; display:flex; align-items:center; justify-content:space-between; gap:12px; flex-wrap:wrap; }
  .contact a { color:#fff; text-decoration:none; font-weight:600; }
  @media (max-width:620px){ .hero{flex-direction:column; align-items:flex-start} .logo{width:92px;height:92px} }
</style>

<div class="karak-wrap">
  <div class="karak-card">
    <div class="hero">
      <!-- Replace the src below with your KARAK logo or welcome image -->
      <img class="logo" src="https://user-images.githubusercontent.com/161917456/52802a87-c278-4c69-988a-486b1d7e4f00.png" alt="KARAK Logo / Welcome Image" />
      <div style="flex:1; min-width:220px;">
        <h1 class="title">KARAK — Software. Games. Stories.</h1>
        <p class="tagline">End-to-end software design & development — from enterprise systems and consumer applications to immersive games and personal projects.</p>

        <div class="cta">
          <!-- Update links -->
          <a href="https://www.karak.dev" target="_blank" rel="noreferrer" style="text-decoration:none;">
            <img class="badge" src="https://img.shields.io/badge/Website-Visit%20KARAK-0ea5a4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="KARAK Website" />
          </a>
          <a href="mailto:contact@karak.dev" style="text-decoration:none;">
            <img class="badge" src="https://img.shields.io/badge/Email-contact@karak.dev-111827?style=for-the-badge&logo=gmail&logoColor=white" alt="Email KARAK" />
          </a>
        </div>

        <div class="socials" aria-label="KARAK socials">
          <!-- Replace hrefs with your real social links -->
          <a href="#" target="_blank" rel="noreferrer"><img class="badge" src="https://img.shields.io/badge/LinkedIn-KARAK-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
          <a href="#" target="_blank" rel="noreferrer"><img class="badge" src="https://img.shields.io/badge/Twitter-@KARAKTech-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter/X" /></a>
          <a href="#" target="_blank" rel="noreferrer"><img class="badge" src="https://img.shields.io/badge/Instagram-@KARAK-EC4899?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
          <a href="#" target="_blank" rel="noreferrer"><img class="badge" src="https://img.shields.io/badge/YouTube-KARAK-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
        </div>
      </div>
    </div>

    <!-- Short company overview -->
    <div class="about" role="region" aria-labelledby="about-heading">
      <h3 id="about-heading" style="margin:12px 0 6px 0;">About KARAK</h3>
      <p>
        KARAK is a multidisciplinary software studio focused on building high-quality digital products:
        enterprise applications, bespoke web & mobile experiences, 2D/3D games, and personal publishing platforms.
        We combine strong engineering fundamentals with thoughtful design to deliver software that scales and delights.
      </p>
    </div>

    <!-- Services -->
    <div class="services" aria-label="Core services">
      <div class="service">
        <h4>Software Design & Development</h4>
        <p style="margin:6px 0 0;color:#475569;font-size:13px;">Architecture, web & backend systems, microservices, cloud deployments.</p>
      </div>
      <div class="service">
        <h4>Game Development</h4>
        <p style="margin:6px 0 0;color:#475569;font-size:13px;">2D/3D games, gameplay systems, performance optimisation, ports.</p>
      </div>
      <div class="service">
        <h4>Personal Blogs & Projects</h4>
        <p style="margin:6px 0 0;color:#475569;font-size:13px;">Static & dynamic sites, developer blogs, side-project incubator.</p>
      </div>
      <div class="service">
        <h4>Consulting & R&D</h4>
        <p style="margin:6px 0 0;color:#475569;font-size:13px;">Proof-of-concepts, tech evaluations, and design sprints.</p>
      </div>
    </div>

    <!-- Tech Stack -->
    <div style="margin-top:18px;">
      <h3 style="margin:0 0 8px 0;">Tech Stack — What we use</h3>
      <div class="tech-grid" aria-label="technologies">
        <!-- Icons from devicon / vectorlogo.zone / shields — replace or reorder to taste -->
        <div class="tech-item"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python"/><div>Python</div></div>
        <div class="tech-item"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java"/><div>Java</div></div>
        <div class="tech-item"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript"/><div>JavaScript</div></div>
        <div class="tech-item"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5"/><div>HTML5</div></div>
        <div class="tech-item"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3"/><div>CSS3</div></div>
        <div class="tech-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" alt="React"/><div>React</div></div>
        <div class="tech-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flutter/flutter-original.svg" alt="Flutter"/><div>Flutter</div></div>
        <div class="tech-item"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/godot/godot-original.svg" alt="Godot"/><div>Godot</div></div>
        <div class="tech-item"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker"/><div>Docker</div></div>
        <div class="tech-item"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" alt="MySQL"/><div>MySQL</div></div>
      </div>
    </div>

    <!-- GitHub Stats & Metrics -->
    <div class="stats">
      <h3 style="margin:6px 0 0 0;">Open Source & GitHub</h3>

      <!--
        Replace K A R A K_GITHUB_USER with your GitHub org/user.
        Example:
          https://github-readme-stats.vercel.app/api?username=KARAK&theme=algolia
      -->
      <div class="metrics" style="width:100%;">
        <!-- GitHub Streak / Stats images - be sure to change username -->
        <div style="display:flex;flex-direction:column;gap:10px;align-items:center;">
          <!-- Replace 'KARAK' with your GitHub org/user -->
          <img src="https://github-readme-stats.vercel.app/api?username=KARAK&show_icons=true&theme=algolia&hide_border=true" alt="KARAK GitHub Stats" class="metrics-img" style="max-width:880px;" />
          <img src="https://github-readme-streak-stats.herokuapp.com/?user=KARAK&theme=algolia&hide_border=true" alt="KARAK Streak" class="metrics-img" style="max-width:880px;" />
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KARAK&layout=compact&theme=algolia&hide_border=true" alt="Top Languages" class="metrics-img" style="max-width:880px;" />
        </div>
      </div>

      <!-- Trophies -->
      <div style="width:100%; margin-top:6px;">
        <img src="https://github-trophies.vercel.app/?username=KARAK&theme=algolia&no-frame=true&no-bg=true" alt="GitHub Trophies" style="max-width:100%;border-radius:10px;" />
      </div>

      <!-- Visitor count (optional) -->
      <div style="margin-top:10px;">
        <a href="#"><img src="https://visitcount.itsvg.in/api?id=KARAK&label=Profile%20Views&color=1&icon=6&pretty=true" alt="Profile views" /></a>
      </div>
    </div>

    <!-- Contact bar -->
    <div class="contact" role="contentinfo">
      <div>
        <div style="font-weight:700;">Contact KARAK</div>
        <div style="font-size:13px;margin-top:2px;">Email: <a href="mailto:contact@karak.dev">contact@karak.dev</a> · Location: Nairobi, Kenya</div>
      </div>
      <div>
        <!-- Call to action -->
        <a href="https://www.karak.dev" target="_blank" rel="noreferrer" style="background:#06b6d4;padding:10px 14px;border-radius:8px;color:#06202a;">Visit website</a>
      </div>
    </div>

    <p style="margin-top:16px;font-size:12px;color:#94a3b8;">© <strong>KARAK</strong> — Built with care. Replace the placeholder links and usernames above with your real company assets for full effect.</p>
  </div>
</div>
