<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Your Name — Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Navigation -->
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#education">Education</a></li>
        <li><a href="#projects">Work</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Home Section -->
  <section id="home">
    <h1>Hi There,</h1>
    <h2>I'm Md.Meherab Hossen</h2>
    <p>i am into</p>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <h3>I'm Meherab Hossen</h3>
    <p>CFD Enthusiast</p>
    <p>I am a Mechanical Engineering Student based in [Location].</p>
    <p>Email: meherabhossen3085@gmail.com</p>
    <p>Phone: +8801538280009</p>
    <p>Place: Dhaka, Bangladesh</p>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>Skills & Abilities</h2>
    <div class="skills-list">
      <div class="skill"><img src="ansys-icon.png" alt="Ansys">Ansys</div>
      <div class="skill"><img src="matlab-icon.png" alt="Matlab">Matlab</div>
      <div class="skill"><img src="solidworks-icon.png" alt="SolidWorks">SolidWorks</div>
    </div>
  </section>

  <!-- Education Section -->
  <section id="education">
    <h2>My Education</h2>
    <div class="edu-item">
      <h3>Bachelor of Science in Mechanical Engineering</h3>
      <p>Ahsanullah University of Science & Technology — 2022-Present</p>
    </div>
    <div class="edu-item">
      <h3>HSC Science</h3>
      <p>Milestone College — 2018-2020</p>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>My Projects</h2>
    <div class="project">
      <h3>Water Filling Container Multiphase Flow</h3>
      <p>Simulation of multiphase flow focusing on air–water interaction and surface dynamics.</p>
      <a href="[video-link]" target="_blank">Watch Video</a>
    </div>
    <div class="project">
      <h3>Flow Analysis in a Centrifugal Pump</h3>
      <p>CFD analysis of fluid flow and pressure distribution under varying conditions.</p>
      <a href="[video-link]" target="_blank">Watch Video</a>
    </div>
    <div class="project">
      <h3>Thermal Analysis of Heat Exchanger</h3>
      <p>Design and analysis using Ansys to study temperature distribution and heat transfer.</p>
      <a href="[video-link]" target="_blank">Watch Video</a>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Reach me</h2>
    <form action="#" method="post">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message"></textarea>
      <button type="submit">Submit</button>
    </form>
    <p>Thank you for visiting my personal portfolio website. Connect with me over socials.</p>
  </section>

  <footer>
    <p>Keep Rising.</p>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>
