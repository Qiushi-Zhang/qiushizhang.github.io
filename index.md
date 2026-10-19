---
layout: null
title: "Qiushi Zhang | Robotics Research"
permalink: /
---
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#ffffff">
  <meta name="description" content="Qiushi Zhang — robotics researcher working on dexterous manipulation, force-aware robot hardware, teleoperation, and robot control.">
  <meta property="og:type" content="website">
  <meta property="og:title" content="Qiushi Zhang | Robotics Research">
  <meta property="og:description" content="Robot hardware, dexterous manipulation, force-aware control, and teleoperation.">
  <meta property="og:image" content="https://raw.githubusercontent.com/Qiushi-Zhang/qiushizhang.github.io/master/images/profile.jpg">
  <link rel="canonical" href="https://qiushi-zhang.github.io/qiushizhang.github.io/">
  <link rel="stylesheet" href="{{ '/assets/css/qiushi-home.css' | relative_url }}">
  <title>Qiushi Zhang | Robotics Research</title>
</head>
<body>
<div class="container">
  <header class="intro" id="about">
    <div class="intro-copy">
      <h1>Qiushi Zhang</h1>
      <p class="lead">I am a robotics researcher working at the intersection of <strong>robot hardware, control, and learning</strong>. My research focuses on force-aware dexterous manipulation, low-cost actuation, and human-to-robot teleoperation.</p>
      <p>I received my M.S. in Mechanical Engineering from <a href="https://www.cmu.edu/" target="_blank" rel="noopener noreferrer">Carnegie Mellon University</a>, where I worked with <a href="https://www.ri.cmu.edu/ri-faculty/jeffrey-ichnowski/" target="_blank" rel="noopener noreferrer">Prof. Jeff Ichnowski</a> on contact-rich robotic manipulation. I am interested in building robotic systems that combine mechanical design with accurate force control and data-driven methods.</p>
      <p class="links">
        <a href="mailto:qiushiz@cmu.edu">Email</a><span class="sep">/</span>
        <a href="https://github.com/Qiushi-Zhang" target="_blank" rel="noopener noreferrer">GitHub</a><span class="sep">/</span>
        <a href="https://qiushi-zhang.github.io/PropHand/" target="_blank" rel="noopener noreferrer">PropHand</a><span class="sep">/</span>
        <a href="#research">Research</a>
      </p>
    </div>
    <figure class="portrait"><img src="{{ '/images/profile.jpg' | relative_url }}" width="208" height="234" alt="Qiushi Zhang" loading="eager" decoding="async"></figure>
  </header>

  <main>
    <section id="news" aria-labelledby="news-heading">
      <h2 id="news-heading">News</h2>
      <ul class="news">
        <li><time datetime="2026-10">[Oct. 2026]</time><span>Launched the <a href="https://qiushi-zhang.github.io/PropHand/" target="_blank" rel="noopener noreferrer">PropHand project website</a>, featuring force-control experiments and manipulation demonstrations.</span></li>
        <li><time datetime="2026">[2026]</time><span><a href="https://qiushi-zhang.github.io/PropHand/" target="_blank" rel="noopener noreferrer">PropHand</a> was accepted to the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2026).</span></li>
      </ul>
    </section>

    <section id="research" aria-labelledby="research-heading">
      <h2 id="research-heading">Research</h2>
      <p class="section-note">Selected publications and research projects.</p>

      <article class="research-item">
        <a class="thumb" href="https://qiushi-zhang.github.io/PropHand/" target="_blank" rel="noopener noreferrer" aria-label="View the PropHand project website">
          <img src="https://qiushi-zhang.github.io/PropHand/grasp_cup.jpg" width="560" height="378" alt="PropHand grasping a flexible cup" loading="lazy">
        </a>
        <div class="research-body">
          <h3><a href="https://qiushi-zhang.github.io/PropHand/" target="_blank" rel="noopener noreferrer">PropHand: A Force-Aware Open-Source Dexterous Robot Hand</a></h3>
          <p class="research-authors"><strong>Qiushi Zhang</strong>, Xilin Zhang, Jeff Ichnowski</p>
          <p class="research-venue">IROS 2026</p>
          <p class="research-links">
            <a href="https://qiushi-zhang.github.io/PropHand/PropHand-IROS-2026.pdf" target="_blank" rel="noopener noreferrer">Paper</a><span class="slash">/</span>
            <a href="https://qiushi-zhang.github.io/PropHand/" target="_blank" rel="noopener noreferrer">Project page</a><span class="slash">/</span>
            <a href="https://github.com/Qiushi-Zhang/PropHand" target="_blank" rel="noopener noreferrer">GitHub</a>
          </p>
          <p class="research-description">An open-source tendon-driven hand designed for proprioceptive force estimation and compliant manipulation. A torque-transparent transmission and motor-current-based force sensing enable contact-force regulation without dedicated tactile sensors.</p>
        </div>
      </article>

      <article class="research-item">
        <div class="thumb" role="img" aria-label="Illustration of egocentric camera observation and three-dimensional target prediction">
          <div class="ego-art">
            <svg viewBox="0 0 236 150" aria-hidden="true" xmlns="http://www.w3.org/2000/svg">
              <rect x="26" y="26" width="116" height="90" rx="8" fill="#fff" stroke="#b2bfcb" stroke-width="2"/>
              <path d="M43 101 L75 69 L97 84 L129 53" fill="none" stroke="#91a4b7" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
              <circle cx="129" cy="53" r="7" fill="#3f87b8"/>
              <path d="M129 53 L181 29 M129 53 L187 102 M129 53 L158 132" stroke="#679bbf" stroke-width="2" stroke-dasharray="6 6"/>
              <circle cx="181" cy="29" r="5" fill="#b3c5d7"/>
              <circle cx="187" cy="102" r="5" fill="#b3c5d7"/>
              <circle cx="158" cy="132" r="5" fill="#b3c5d7"/>
              <circle cx="187" cy="102" r="10" fill="none" stroke="#3f87b8" stroke-width="2"/>
              <text x="43" y="18" fill="#718196" font-size="10" font-family="sans-serif">RGB observation</text>
              <text x="160" y="147" fill="#4b728e" font-size="10" font-family="sans-serif">3D target</text>
            </svg>
          </div>
        </div>
        <div class="research-body">
          <h3><a href="https://arxiv.org/abs/2403.05046" target="_blank" rel="noopener noreferrer">EgoPAT3Dv2: Predicting 3D Action Target from 2D Egocentric Vision for Human-Robot Interaction</a></h3>
          <p class="research-authors">Irving Fang, Yuzhong Chen, Yifan Wang, Jianghan Zhang, <strong>Qiushi Zhang</strong>, et al.</p>
          <p class="research-venue">ICRA 2024</p>
          <p class="research-links"><a href="https://arxiv.org/abs/2403.05046" target="_blank" rel="noopener noreferrer">Paper</a></p>
          <p class="research-description">Predicting three-dimensional interaction targets from egocentric video for human–robot collaboration and robot action planning.</p>
        </div>
      </article>
    </section>

    <section id="projects" aria-labelledby="projects-heading">
      <h2 id="projects-heading">Ongoing Work</h2>
      <article class="research-item">
        <div class="thumb" role="img" aria-label="Wearable hand teleoperation concept">
          <div class="exo-art"><span>EXO</span><small>HAND TELEOPERATION</small></div>
        </div>
        <div class="research-body">
          <h3>Wearable Hand Exoskeleton for Teleoperation</h3>
          <p class="project-note">Hardware development in progress</p>
          <p class="research-description">Developing an encoder-based wearable hand mechanism for dexterous teleoperation and demonstration collection, with an emphasis on precise joint tracking, low latency, and bilateral force feedback.</p>
        </div>
      </article>
    </section>

    <section id="contact" class="contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Contact</h2>
      <p>Feel free to reach out about robotic hardware, force-aware manipulation, and research collaboration. <a href="mailto:qiushiz@cmu.edu">qiushiz@cmu.edu</a></p>
    </section>
  </main>
  <footer>© 2026 Qiushi Zhang · Updated October 2026</footer>
</div>
</body>
</html>
