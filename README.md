!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yousif Nazeer | AI Portfolio</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">

<!-- Particles.js CDN -->
<script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>

<style>
/* Global */
* { box-sizing: border-box; margin:0; padding:0; scroll-behavior:smooth; font-family: 'Roboto', sans-serif;}
body { background:#0f172a; color:#fff; overflow-x:hidden; }

/* Particles background */
#particles-js { position: fixed; width: 100%; height: 100%; z-index: -1; }

/* Header */
header {
  text-align: center;
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
