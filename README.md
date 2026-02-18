<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Yousif Nazeer | AI Enthusiast</title>
  <!-- Google Fonts & Font Awesome -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <!-- Particles.js -->
  <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      color: #f0f0f0;
      line-height: 1.6;
      overflow-x: hidden;
    }

    /* Particles background */
    #particles-js {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1;
      background: #0a0f1e; /* fallback dark color */
    }

    /* Main content container */
    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 2rem 1.5rem;
      position: relative;
      z-index: 1;
    }

    /* Glassmorphism cards */
    .glass-card {
      background: rgba(20, 30, 45, 0.6);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      border-radius: 24px;
      padding: 2rem;
      margin-bottom: 2rem;
      border: 1px solid rgba(255, 255, 255, 0.1);
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .glass-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 40px rgba(0, 0, 0, 0.5);
    }

    h1 {
      font-size: 3.5rem;
      font-weight: 700;
      letter-spacing: -0.02em;
      margin-bottom: 0.5rem;
    }

    h2 {
      font-size: 2rem;
      font-weight: 600;
      margin-bottom: 1.5rem;
      color: #fff;
      border-left: 6px solid #3b82f6;
      padding-left: 1rem;
    }

    h3 {
      font-size: 1.5rem;
      font-weight: 600;
      margin-bottom: 1rem;
      color: #fff;
    }

    .subhead {
      font-size: 1.3rem;
      color: #b0c4de;
      margin-bottom: 1.5rem;
      font-weight: 300;
    }

    .btn {
      display: inline-block;
      background: #3b82f6;
      color: white;
      padding: 0.8rem 2rem;
      border-radius: 50px;
      text-decoration: none;
      font-weight: 600;
      transition: background 0.3s, transform 0.2s;
      border: none;
      cursor: pointer;
      font-size: 1rem;
    }

    .btn:hover {
      background: #2563eb;
      transform: scale(1.05);
    }

    /* Skills tags */
    .skills-container {
      display: flex;
      flex-wrap: wrap;
      gap: 0.8rem;
      margin-top: 1rem;
    }

    .skill-tag {
      background: rgba(59, 130, 246, 0.2);
      border: 1px solid rgba(59, 130, 246, 0.5);
      color: #e2e8f0;
      padding: 0.5rem 1.2rem;
      border-radius: 40px;
      font-size: 0.95rem;
      font-weight: 500;
      backdrop-filter: blur(4px);
      transition: all 0.2s;
    }

    .skill-tag:hover {
      background: #3b82f6;
      color: white;
      transform: scale(1.05);
    }

    /* Project card */
    .project-card {
      background: rgba(30, 41, 59, 0.6);
      border-radius: 20px;
      padding: 1.8rem;
      border-left: 6px solid #3b82f6;
      transition: 0.3s;
    }

    .project-card p {
      margin: 1rem 0 1.5rem;
      color: #cbd5e1;
    }

    .project-icon {
      font-size: 2.5rem;
      color: #3b82f6;
      margin-bottom: 0.5rem;
    }

    /* Contact section */
    .contact-links {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      margin-top: 1.5rem;
    }

    .contact-item {
      display: flex;
      align-items: center;
      gap: 0.8rem;
      background: rgba(255, 255, 255, 0.05);
      padding: 0.8rem 1.5rem;
      border-radius: 60px;
      transition: 0.3s;
      border: 1px solid rgba(255, 255, 255, 0.1);
      text-decoration: none;
      color: #f0f0f0;
    }

    .contact-item i {
      font-size: 1.4rem;
      color: #3b82f6;
    }

    .contact-item:hover {
      background: rgba(59, 130, 246, 0.2);
      border-color: #3b82f6;
      transform: translateY(-3px);
    }

    /* Footer */
    footer {
      text-align: center;
      margin-top: 3rem;
      padding-top: 2rem;
      border-top: 1px solid rgba(255, 255, 255, 0.1);
      color: #94a3b8;
      font-size: 0.9rem;
    }

    /* Responsive */
    @media (max-width: 600px) {
      h1 { font-size: 2.5rem; }
      h2 { font-size: 1.8rem; }
      .container { padding: 1rem; }
      .glass-card { padding: 1.5rem; }
      .contact-links { flex-direction: column; gap: 1rem; }
    }

    /* Fade-in animation */
    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 0.8s ease forwards;
    }

    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <!-- Particles container -->
  <div id="particles-js"></div>

  <div class="container">
    <!-- Header -->
    <header class="glass-card fade-in" style="animation-delay: 0.1s;">
      <h1>Yousif Nazeer</h1>
      <div class="subhead">BS Mathematics | AI Enthusiast</div>
      <p style="max-width: 600px; margin-bottom: 1.5rem;">Passionate about developing intelligent AI agents and applying mathematical techniques to real-world problems.</p>
      <a href="#contact" class="btn">Contact Me</a>
    </header>

    <!-- About -->
    <section class="glass-card fade-in" style="animation-delay: 0.2s;">
      <h2>About Me</h2>
      <p style="font-size: 1.1rem;">I am a Mathematics student passionate about Artificial Intelligence. I love developing AI agents and learning new mathematical techniques to solve real-world problems.</p>
    </section>

    <!-- Skills -->
    <section class="glass-card fade-in" style="animation-delay: 0.3s;">
      <h2>Skills</h2>
      <div class="skills-container">
        <span class="skill-tag">Python</span>
        <span class="skill-tag">Machine Learning</span>
        <span class="skill-tag">Artificial Neural Networks</span>
        <span class="skill-tag">Optimization Theory</span>
        <span class="skill-tag">Mathematical Modeling</span>
      </div>
    </section>

    <!-- Projects -->
    <section class="glass-card fade-in" style="animation-delay: 0.4s;">
      <h2>Projects</h2>
      <div class="project-card">
        <div class="project-icon"><i class="fas fa-robot"></i></div>
        <h3>AI Agent</h3>
        <p>Developed an intelligent AI agent to understand and respond to inputs. This is my main project, showcasing natural language understanding and decision-making.</p>
        <span style="color: #3b82f6; font-weight: 500;">Built with Python & Neural Networks</span>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="glass-card fade-in" style="animation-delay: 0.5s;">
      <h2>Contact</h2>
      <div class="contact-links">
        <a href="mailto:yousifnazeer408@gmail.com" class="contact-item">
          <i class="fas fa-envelope"></i>
          <span>yousifnazeer408@gmail.com</span>
        </a>
        <a href="https://www.linkedin.com/in/yousifnazeer/" target="_blank" class="contact-item">
          <i class="fab fa-linkedin"></i>
          <span>View Profile</span>
        </a>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <p>© 2026 Yousif Nazeer | Built with GitHub Pages</p>
    </footer>
  </div>

  <script>
    // Particles configuration (from your screenshot, enhanced)
    particlesJS("particles-js", {
      particles: {
        number: { value: 80, density: { enable: true, value_area: 800 } },
        color: { value: "#3b82f6" },
        shape: { type: "circle" },
        opacity: { value: 0.6, random: true },
        size: { value: 3, random: true },
        line_linked: {
          enable: true,
          distance: 150,
          color: "#3b82f6",
          opacity: 0.4,
          width: 1
        },
        move: {
          enable: true,
          speed: 2,
          direction: "none",
          random: true,
          straight: false,
          out_mode: "out"
        }
      },
      interactivity: {
        detect_on: "canvas",
        events: {
          onhover: { enable: true, mode: "repulse" },
          onclick: { enable: true, mode: "push" }
        },
        modes: {
          repulse: { distance: 100, duration: 0.4 },
          push: { particles_nb: 4 }
        }
      },
      retina_detect: true
    });

    // Optional smooth scroll for anchor links
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
          target.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }
      });
    });
  </script>
</body>
</html>  text-align: center;
  padding: 150px 20px;
  background: linear-gradient(135deg, #1e3a8a, #2563eb);
  animation: gradient 10s ease infinite;
  clip-path: polygon(0 0,100% 0,100% 80%,0 100%);
  position: relative;
}

@keyframes gradient {
  0%{background: linear-gradient(135deg, #1e3a8a, #2563eb);}
  50%{background: linear-gradient(135deg, #2563eb, #1e40af);}
  100%{background: linear-gradient(135deg, #1e3a8a, #2563eb);}
}

header h1 { font-size:48px; text-shadow:0 0 20px #3b82f6; }
header p { margin-top:10px; font-size:18px; color:#cbd5e1; }
.header-btn { margin-top:25px; padding:12px 25px; border-radius:8px; background:#3b82f6; color:white; text-decoration:none; font-weight:bold; transition:0.3s transform; }
.header-btn:hover { transform: scale(1.1); }

/* Sections */
section { padding:70px 20px; max-width:900px; margin:auto; }
h2 { color:#3b82f6; font-size:32px; margin-bottom:30px; text-align:center; position:relative; }
h2::after { content:''; width:80px; height:3px; background:#3b82f6; display:block; margin:10px auto 0; border-radius:3px; }

/* Card */
.card { background:#1e293b; padding:25px; border-radius:15px; margin-bottom:25px; transition:0.3s transform,0.3s box-shadow; }
.card:hover { transform: translateY(-10px); box-shadow: 0 10px 30px rgba(59,130,246,0.6); }

/* Skills */
.skills span { display:inline-block; background:#2563eb; padding:10px 15px; margin:5px; border-radius:8px; font-size:14px; transition:0.3s all; cursor:pointer;}
.skills span:hover { background:#3b82f6; transform: scale(1.1); }

/* Footer */
footer { text-align:center; padding:40px 20px; background:#020617; color:#64748b; font-size:14px; }

/* Responsive */
@media(max-width:768px){ header h1{ font-size:36px; } h2{ font-size:28px; } }
</style>
</head>
<body>

<!-- Particles -->
<div id="particles-js"></div>

<!-- Header -->
<header>
  <h1>Yousif Nazeer</h1>
  <p>BS Mathematics | AI Enthusiast</p>
  <a href="#contact" class="header-btn">Contact Me</a>
</header>

<!-- About -->
<section id="about">
  <h2>About Me</h2>
  <div class="card">
    <p>
      I am a Mathematics student passionate about Artificial Intelligence.
      I love developing AI agents and learning new mathematical techniques
      to solve real-world problems.
    </p>
  </div>
</section>

<!-- Skills -->
<section id="skills">
  <h2>Skills</h2>
  <div class="skills">
    <span>Python</span>
    <span>Machine Learning</span>
    <span>Artificial Neural Networks</span>
    <span>Optimization Theory</span>
    <span>Mathematical Modeling</span>
  </div>
</section>

<!-- Projects -->
<section id="projects">
  <h2>Projects</h2>
  <div class="card">
    <h3>AI Agent</h3>
    <p>Developed an intelligent AI agent to understand and respond to inputs. This is my main project.</p>
  </div>
</section>

<!-- Contact -->
<section id="contact">
  <h2>Contact</h2>
  <div class="card">
    <p>Email: <a href="mailto:yousifnazeer408@gmail.com" style="color:#3b82f6;">yousifnazeer408@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/muhammad-yousif-nazeer-9a389137a?utm_source=share_via&utm_content=profile&utm_medium=member_android" target="_blank" style="color:#3b82f6;">View Profile</a></p>
    <p>GitHub: <a href="https://github.com/yousifnazeer" target="_blank" style="color:#3b82f6;">yousifnazeer</a></p>
  </div>
</section>

<!-- Footer -->
<footer>
  © 2026 Yousif Nazeer | Built with GitHub Pages
</footer>

<!-- Particles JS Initialization -->
<script>
particlesJS("particles-js", {
  "particles": {
    "number": { "value":60, "density": { "enable": true, "value_area": 800 } },
    "color": { "value": "#3b82f6" },
    "shape": { "type": "circle" },
    "opacity": { "value": 0.6 },
    "size": { "value": 3 },
    "line_linked": { "enable": true, "distance": 150, "color": "#3b82f6", "opacity": 0.4, "width": 1 },
    "move": { "enable": true, "speed": 2 }
  },
  "interactivity": {
    "detect_on": "canvas",
    "events": { "onhover": { "enable": true, "mode": "repulse" } }
  },
  "retina_detect": true
});
</script>

</body>
</html>
