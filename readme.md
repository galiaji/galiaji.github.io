---
layout: null
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#080d18">
  <meta name="description" content="Galih Aji Syafaat — Informatics graduate, backend and web developer. Explore projects, experience, skills, and contact information.">
  <meta property="og:title" content="Galih Aji Syafaat | Developer Portfolio">
  <meta property="og:description" content="Backend development, web applications, and database engineering.">
  <title>Galih Aji Syafaat | Developer Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=Manrope:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="ambient ambient-one"></div><div class="ambient ambient-two"></div>
  <header class="site-header">
    <nav class="nav container" aria-label="Main navigation">
      <a class="brand" href="#home"><span class="brand-mark">G<span>.</span></span><span>GALIH AJI SYAFAAT</span></a>
      <button class="menu-toggle" id="menuToggle" aria-label="Toggle navigation" aria-expanded="false"><span></span><span></span></button>
      <div class="nav-links" id="navLinks">
        <a href="#about">About</a><a href="#skills">Skills</a><a href="#projects">Projects</a><a href="#experience">Experience</a><a href="#education">Education</a><a href="#contact" class="nav-contact">Contact <span>↗</span></a>
      </div>
    </nav>
  </header>

  <main>
    <section class="hero container" id="home">
      <div class="hero-copy">
        <div class="eyebrow"><span class="status-dot"></span> OPEN TO OPPORTUNITIES <span class="eyebrow-line"></span></div>
        <p class="hero-intro">Hello, I'm</p>
        <h1>Galih Aji<br><span>Syafaat.</span></h1>
        <h2>Junior Backend Developer <b>·</b> Web Developer</h2>
        <p class="hero-description">Informatics graduate who enjoys building practical web applications, designing reliable databases, and turning real-world needs into maintainable software solutions.</p>
        <div class="hero-actions">
          <a class="button button-primary" href="#projects">Explore my work <span>↗</span></a>
          <a class="button button-ghost" href="assets/CV_Galih_Aji_Syafaat.pdf" target="_blank" rel="noreferrer">View CV <span>↗</span></a>
        </div>
        <div class="hero-socials">
          <a href="https://github.com/galiaji" target="_blank" rel="noreferrer">GitHub ↗</a><span class="social-separator">/</span>
          <a href="https://www.linkedin.com/in/galihaji12" target="_blank" rel="noreferrer">LinkedIn ↗</a><span class="social-separator">/</span>
          <a href="mailto:syafaatg76@gmail.com">Email ↗</a>
        </div>
      </div>
      <div class="hero-visual">
        <div class="profile-orbit orbit-a"></div><div class="profile-orbit orbit-b"></div>
        <div class="profile-card">
          <div class="profile-image-wrap">
            <img src="assets/profile.jpg" alt="Galih Aji Syafaat" class="profile-image" onerror="this.style.display='none';this.nextElementSibling.style.display='grid'">
            <div class="profile-placeholder">G<span>.</span></div>
          </div>
          <div class="profile-caption"><span class="status-dot"></span><div><strong>Galih Aji Syafaat</strong><small>Informatics Graduate · Developer</small></div></div>
          <div class="profile-tags"><span>Laravel</span><span>PHP</span><span>MySQL</span></div>
        </div>
        <div class="floating-chip chip-top"><span class="chip-icon">⌘</span><span><b>Backend</b><small>Logic & APIs</small></span></div>
        <div class="floating-chip chip-bottom"><span class="chip-icon chip-db">▤</span><span><b>Database</b><small>Structure & data</small></span></div>
      </div>
      <a class="scroll-cue" href="#about"><span></span> SCROLL TO EXPLORE</a>
    </section>

    <section class="section container" id="about">
      <div class="section-heading"><p class="section-kicker">01 / ABOUT</p><h2>Building with <span>purpose.</span></h2></div>
      <div class="about-grid">
        <div class="about-main">
          <p class="lead">I'm an Informatics graduate from <strong>Diponegoro University</strong> with a GPA of <strong>3.46 / 4.00</strong>, with a foundation in programming, computational logic, and database systems.</p>
          <p>I have experience leading projects and coordinating with non-technical stakeholders, from gathering requirements to delivering working systems. I enjoy backend and web development, database design, problem-solving, and continuously learning new technologies. I am also interested in teaching coding and computational thinking.</p>
          <a class="text-link" href="https://github.com/galiaji" target="_blank" rel="noreferrer">Explore my GitHub <span>↗</span></a>
        </div>
        <div class="about-facts">
          <div class="fact-card"><span class="fact-number">2026</span><span class="fact-label">Graduation year</span></div>
          <div class="fact-card"><span class="fact-number">3.46<span class="fact-small">/4.00</span></span><span class="fact-label">Grade point average</span></div>
          <div class="fact-card fact-wide"><span class="fact-label">AREAS OF INTEREST</span><strong>Backend development · Web applications · Database design · Coding education</strong></div>
        </div>
      </div>
    </section>

    <section class="section section-muted" id="skills">
      <div class="container">
        <div class="section-heading"><p class="section-kicker">02 / TOOLKIT</p><h2>Technical <span>skills.</span></h2><p class="section-subtitle">Technologies and capabilities developed through academic, organizational, and project experience.</p></div>
        <div class="skills-grid">
          <article class="skill-card"><div class="skill-icon">01</div><h3>Programming</h3><div class="skill-tags"><span>PHP</span><span>JavaScript</span><span>HTML</span><span>CSS</span><span>SQL</span><span>Python (Basic)</span><span>Scratch (Basic)</span></div></article>
          <article class="skill-card"><div class="skill-icon">02</div><h3>Frameworks & Web</h3><div class="skill-tags"><span>Laravel</span><span>Bootstrap</span><span>Tailwind CSS</span><span>Filament</span></div></article>
          <article class="skill-card"><div class="skill-icon">03</div><h3>Database</h3><div class="skill-tags"><span>MySQL</span><span>Relational Database Design</span><span>PL/SQL</span></div></article>
          <article class="skill-card"><div class="skill-icon">04</div><h3>Tools & Workflow</h3><div class="skill-tags"><span>Git</span><span>GitHub</span><span>VS Code</span><span>Composer</span><span>NPM</span></div></article>
        </div>
        <div class="soft-skills"><span>CORE STRENGTHS</span><p>Programming logic · Algorithms · Debugging · Testing · Communication · Project management · Teamwork · Time management</p></div>
      </div>
    </section>

    <section class="section container" id="projects">
      <div class="section-heading"><p class="section-kicker">03 / SELECTED WORK</p><h2>Projects that solve <span>problems.</span></h2><p class="section-subtitle">Selected academic, organizational, internship, and personal work.</p></div>
      <div class="projects-list">
        <article class="project-card">
          <div class="project-visual visual-warehouse"><div class="mock-top"><span>UD. TPKS</span><span>WAREHOUSE SYSTEM</span></div><div class="mock-dashboard"><aside><i></i><i></i><i></i><i></i></aside><div class="mock-main"><small>WAREHOUSE OVERVIEW</small><div class="mock-stats"><i></i><i></i><i></i></div><div class="mock-chart"><span></span><span></span><span></span><span></span><span></span><span></span><span></span></div></div></div><span class="visual-caption">WEB APPLICATION / 01</span></div>
          <div class="project-info"><div class="project-meta"><span>FINAL PROJECT · 2026</span><span>01 — 04</span></div><h3>Warehouse Management System</h3><p>A web application for recording wood stock and managing purchase and sales transactions at UD. Tiga Putra Karya Sentosa.</p><ul><li>Stock, purchase, sales, and stock opname management</li><li>Relational database design with 27 migrations</li><li>Role-based access, PDF receipts, and reports</li><li>Database transactions and automated PHPUnit tests</li></ul><div class="project-stack"><span>Laravel 12</span><span>PHP</span><span>MySQL</span><span>ICONIX</span></div><a class="project-link" href="https://github.com/galiaji/gudang-kayu" target="_blank" rel="noreferrer">View repository ↗</a></div>
        </article>
        <article class="project-card project-reverse">
          <div class="project-visual visual-village"><div class="village-window"><div class="village-top">DESA MUNDING <span>COMMUNITY WEBSITE</span></div><div class="village-hero"><small>DISCOVER THE VILLAGE</small><b>Tourism · Local Business · Culture</b></div><div class="village-cards"><i></i><i></i><i></i></div></div><span class="visual-caption">VILLAGE PROMOTION / 02</span></div>
          <div class="project-info"><div class="project-meta"><span>FREELANCE PROJECT · 2024</span><span>02 — 04</span></div><h3>Desa Munding Promotion Website</h3><p>A promotional website presenting the village's tourism potential, local businesses, and culture.</p><ul><li>Led project planning and team coordination</li><li>Managed requirements and delivery schedule</li><li>Designed the database and built an admin panel</li><li>Enabled non-technical administrators to manage content</li></ul><div class="project-stack"><span>Web Development</span><span>Database</span><span>Project Management</span></div></div>
        </article>
        <article class="project-card">
          <div class="project-visual visual-wedomartani"><div class="temple-window"><div class="temple-sun"></div><div class="temple-shape"></div><div class="temple-label">WEDOMARTANI <small>VILLAGE WEBSITE</small></div></div><span class="visual-caption">INTERNSHIP / 03</span></div>
          <div class="project-info"><div class="project-meta"><span>INTERNSHIP · 2024</span><span>03 — 04</span></div><h3>Desa Wedomartani Promotion Website</h3><p>Contributed to the development of a village promotional website for Wedomartani, Sleman, featuring the Candi Gebang area.</p><ul><li>Developed website features using Laravel</li><li>Worked with MySQL for data management</li></ul><div class="project-stack"><span>Laravel</span><span>MySQL</span><span>Web Development</span></div><p class="project-context">Sevenpion by PT Semesta Ruang Kreasi · Yogyakarta</p></div>
        </article>
        <article class="project-card project-reverse">
          <div class="project-visual visual-village-service"><div class="service-window"><div class="service-head">DESA TEGALONTAR <small>ONLINE SERVICES</small></div><div class="service-body"><div class="service-icon">▤</div><b>Surat-Menyurat</b><span>Permohonan layanan administrasi desa</span><div class="service-button">AJUKAN SURAT</div></div></div><span class="visual-caption">COMMUNITY SERVICE / 04</span></div>
          <div class="project-info"><div class="project-meta"><span>KKN PROJECT · 2024</span><span>04 — 04</span></div><h3>Village Correspondence Service Website</h3><p>A village service website built to simplify administrative requests and correspondence services for residents of Desa Tegalontar, Sragi, Pekalongan.</p><ul><li>Developed an online channel for correspondence requests</li><li>Focused on improving access to village administration services</li></ul><div class="project-stack"><span>Web Development</span><span>Village Information System</span></div></div>
        </article>
      </div>
    </section>

    <section class="section section-muted" id="experience">
      <div class="container">
        <div class="section-heading"><p class="section-kicker">04 / EXPERIENCE</p><h2>Working with <span>people.</span></h2></div>
        <div class="timeline">
          <article class="timeline-item"><div class="timeline-date">JUL — AUG 2024</div><div class="timeline-card"><p class="experience-type">FREELANCE</p><h3>Project Manager & Back-End Developer</h3><h4>BEM FEB Universitas Diponegoro · Semarang</h4><ul><li>Led the development of the Desa Munding promotional website.</li><li>Coordinated requirements, schedules, and communication between the team and village officials.</li><li>Designed the database and developed an admin panel for non-technical content managers.</li><li>Delivered and launched the website within two months.</li></ul></div></article>
          <article class="timeline-item"><div class="timeline-date">2024</div><div class="timeline-card"><p class="experience-type">INTERNSHIP</p><h3>Web Developer</h3><h4>Sevenpion by PT Semesta Ruang Kreasi · Yogyakarta</h4><ul><li>Developed the Desa Wedomartani promotional website, featuring the Candi Gebang area, using Laravel and MySQL.</li></ul></div></article>
          <article class="timeline-item"><div class="timeline-date">2024</div><div class="timeline-card"><p class="experience-type">COMMUNITY PROJECT</p><h3>Website Layanan Surat-Menyurat Desa</h3><h4>KKN Universitas Diponegoro · Desa Tegalontar, Pekalongan</h4><ul><li>Built a village correspondence service website to support residents' administrative requests.</li></ul></div></article>
        </div>
      </div>
    </section>

    <section class="section container" id="education">
      <div class="section-heading"><p class="section-kicker">05 / EDUCATION</p><h2>Academic <span>background.</span></h2></div>
      <div class="education-card"><div class="education-year">2021 — 2026</div><div><h3>Universitas Diponegoro</h3><p>Bachelor of Informatics · Semarang</p><span class="education-gpa">GPA 3.46 / 4.00</span><p class="thesis">Final project: Warehouse Management System (WMS) for recording wood stock and transactions at UD TPKS.</p></div></div>
    </section>

    <section class="section section-muted" id="credentials">
      <div class="container">
        <div class="section-heading"><p class="section-kicker">06 / CREDENTIALS</p><h2>Learning and <span>growing.</span></h2></div>
        <div class="credential-grid">
          <article class="credential-card"><div class="credential-logo microsoft">▦</div><div><p class="credential-label">CERTIFICATION</p><h3>Microsoft Power Platform Developer</h3><p>Microsoft</p></div></article>
          <article class="credential-card"><div class="credential-logo oracle">O</div><div><p class="credential-label">CERTIFICATION</p><h3>PL/SQL</h3><p>Oracle Academy</p></div></article>
        </div>
        <p class="language-note"><strong>Languages:</strong> Indonesian (Native) · English (TOEFL Prediction 503)</p>
      </div>
    </section>

    <section class="section container" id="github">
      <div class="section-heading"><p class="section-kicker">07 / GITHUB</p><h2>Code, commit, <span>repeat.</span></h2><p class="section-subtitle">Explore my repositories and development activity.</p></div>
      <div class="github-panel"><div class="github-profile"><div class="github-avatar">G</div><div><h3>galiaji</h3><p>GitHub profile</p></div><a class="text-link" href="https://github.com/galiaji" target="_blank" rel="noreferrer">View profile ↗</a></div><div class="github-stats"><img src="https://github-readme-stats.vercel.app/api?username=galiaji&show_icons=true&theme=transparent&hide_border=true&title_color=60a5fa&text_color=cbd5e1&icon_color=60a5fa" alt="GitHub statistics for galiaji" loading="lazy"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=galiaji&layout=compact&theme=transparent&hide_border=true&title_color=60a5fa&text_color=cbd5e1" alt="Most used programming languages" loading="lazy"></div></div>
    </section>

    <section class="contact-section" id="contact"><div class="container contact-inner"><p class="section-kicker">08 / GET IN TOUCH</p><h2>Let's build something<br><span>meaningful.</span></h2><p>I'm open to opportunities, collaboration, and conversations about web development, backend engineering, and coding education.</p><a class="button button-primary" href="mailto:syafaatg76@gmail.com">Let's talk <span>↗</span></a><div class="contact-links"><a href="mailto:syafaatg76@gmail.com">syafaatg76@gmail.com</a><a href="https://github.com/galiaji" target="_blank" rel="noreferrer">GitHub ↗</a><a href="https://www.linkedin.com/in/galihaji12" target="_blank" rel="noreferrer">LinkedIn ↗</a></div></div></section>
  </main>
  <footer class="footer"><div class="container footer-inner"><a class="brand" href="#home"><span class="brand-mark">G<span>.</span></span><span>GALIH AJI SYAFAAT</span></a><p>Designed & built with care. © <span id="year"></span> Galih Aji Syafaat.</p><a href="#home" class="back-top">BACK TO TOP ↑</a></div></footer>
  <script src="script.js"></script>
</body>
</html>