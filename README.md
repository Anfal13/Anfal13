<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anfal Ahamed | Portfolio</title>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <!-- Animate.css for animations -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
  <!-- Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <style>
    /* Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Roboto', sans-serif; }
    body { background: #f9f9f9; color: #333; line-height: 1.6; scroll-behavior: smooth; }
    a { color: #1e90ff; text-decoration: none; }
    a:hover { text-decoration: underline; }

    /* Container */
    .container { width: 90%; max-width: 1000px; margin: 0 auto; padding: 40px 0; }

    /* Header */
    header { text-align: center; padding: 60px 0; background: #1e90ff; color: #fff; }
    header h1 { font-size: 2.5rem; margin-bottom: 10px; }
    header p { font-size: 1.2rem; }

    /* Sections */
    section { margin: 60px 0; }
    h2 { font-size: 2rem; margin-bottom: 20px; color: #1e90ff; }
    ul { list-style: none; margin-top: 10px; }
    ul li { margin-bottom: 10px; }

    /* Cards */
    .card { background: #fff; border-radius: 10px; padding: 20px; margin-bottom: 20px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); transition: transform 0.3s; }
    .card:hover { transform: translateY(-5px); }

    /* Skills grid */
    .skills { display: flex; flex-wrap: wrap; gap: 15px; }
    .skill { background: #1e90ff; color: #fff; padding: 10px 20px; border-radius: 30px; font-weight: bold; }

    /* Contact */
    .contact a { display: inline-block; margin-right: 15px; color: #1e90ff; font-size: 1.2rem; }
    .contact a:hover { color: #0b61c1; }

    /* Footer */
    footer { text-align: center; padding: 40px 0; background: #222; color: #fff; }
  </style>
</head>
<body>

  <header class="animate__animated animate__fadeInDown">
    <h1>Anfal Ahamed</h1>
    <p>Software Engineering Undergraduate | Full-Stack Developer</p>
  </header>

  <div class="container">

    <!-- About -->
    <section id="about" class="animate__animated animate__fadeInUp">
      <h2>About Me</h2>
      <p>I'm an ambitious and dedicated software engineering student at London Metropolitan University (studying via Esoft Metro Campus) with hands-on experience in full-stack web development. I enjoy building clean, efficient code and constantly expanding my technical skills.</p>
    </section>

    <!-- Experience -->
    <section id="experience" class="animate__animated animate__fadeInUp">
      <h2>Experience</h2>
      <div class="card">
        <h3>Software Engineer Intern | FikrFution Technology, Qatar</h3>
        <p><strong>September 2024 - August 2024</strong></p>
        <ul>
          <li>Developed and maintained web applications using <strong>.NET (C#)</strong> and MVC architecture</li>
          <li>Enhanced front-end functionality with <strong>jQuery, HTML, CSS</strong></li>
          <li>Designed and managed databases using <strong>PostgreSQL</strong></li>
          <li>Collaborated with senior developers to debug and optimize applications</li>
        </ul>
      </div>
    </section>

    <!-- Education -->
    <section id="education" class="animate__animated animate__fadeInUp">
      <h2>Education</h2>
      <ul>
        <li>London Metropolitan University (2025) — BSc Hons in Software Engineering</li>
        <li>Esoft Metro Campus (2023) — Higher National Diploma in Software Engineering</li>
        <li>Zahira College Mawanella (2021) — G.C.E Advanced Level Examination</li>
        <li>Zahira College Mawanella (2019) — G.C.E Ordinary Level Examination</li>
      </ul>
    </section>

    <!-- Skills -->
    <section id="skills" class="animate__animated animate__fadeInUp">
      <h2>Technical Skills</h2>
      <div class="skills">
        <span class="skill">C#</span>
        <span class="skill">.NET MVC</span>
        <span class="skill">OOP</span>
        <span class="skill">jQuery</span>
        <span class="skill">HTML & CSS</span>
        <span class="skill">PostgreSQL</span>
        <span class="skill">Git</span>
        <span class="skill">Visual Studio</span>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="animate__animated animate__fadeInUp">
      <h2>Featured Projects</h2>
      <ul>
        <li><a href="https://github.com/Anfal13/StaySwift-Hotel-Reservation-System" target="_blank">StaySwift Hotel Reservation System</a></li>
        <li><a href="https://github.com/Anfal13/StarEvents-Online-Event-Ticketing-System" target="_blank">StarEvents Online Event Ticketing System</a></li>
      </ul>
    </section>

    <!-- Contact -->
    <section id="contact" class="animate__animated animate__fadeInUp">
      <h2>Contact Me</h2>
      <p class="contact">
        <a href="mailto:anfalahamed13@gmail.com"><i class="fas fa-envelope"></i> Email</a>
        <a href="tel:+94754243312"><i class="fas fa-phone"></i> Phone</a>
        <a href="https://www.linkedin.com/in/anfalahamed-b65811276/" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
      </p>
    </section>

  </div>

  <footer class="animate__animated animate__fadeInUp">
    <p>© 2026 Anfal Ahamed. All rights reserved.</p>
  </footer>

  <!-- Optional JS for scroll animations -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/wow/1.1.2/wow.min.js"></script>
  <script>
    new WOW().init();
  </script>

</body>
</html>MM
