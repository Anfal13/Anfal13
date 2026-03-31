<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Anfal Ahamed | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <style>
    body { font-family: 'Roboto', sans-serif; background: #f9f9f9; margin: 0; padding: 0; line-height: 1.6; }
    header { text-align: center; padding: 60px 0; background: #1e90ff; color: #fff; }
    header h1 { font-size: 2.5rem; margin-bottom: 10px; }
    header p { font-size: 1.2rem; }
    .container { width: 90%; max-width: 1000px; margin: auto; padding: 40px 0; }
    section { margin: 60px 0; }
    h2 { color: #1e90ff; margin-bottom: 20px; }
    ul { list-style: none; padding: 0; }
    ul li { margin-bottom: 10px; }
    .card { background: #fff; padding: 20px; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); margin-bottom: 20px; transition: transform 0.3s; }
    .card:hover { transform: translateY(-5px); }
    .skills { display: flex; flex-wrap: wrap; gap: 15px; }
    .skill { background: #1e90ff; color: #fff; padding: 10px 20px; border-radius: 30px; font-weight: bold; }
    .contact a { margin-right: 15px; color: #1e90ff; font-size: 1.2rem; }
    .contact a:hover { color: #0b61c1; }
    footer { text-align: center; padding: 40px 0; background: #222; color: #fff; }
  </style>
</head>
<body>

<header class="animate__animated animate__fadeInDown">
  <h1>Anfal Ahamed</h1>
  <p>Software Engineering Undergraduate | Full-Stack Developer</p>
</header>

<div class="container">

  <section id="about" class="animate__animated animate__fadeInUp">
    <h2>About Me</h2>
    <p>I'm an ambitious software engineering student at London Metropolitan University with hands-on full-stack development experience. I enjoy building clean, efficient code and improving my skills.</p>
  </section>

  <section id="experience" class="animate__animated animate__fadeInUp">
    <h2>Experience</h2>
    <div class="card">
      <h3>Software Engineer Intern | FikrFution Technology, Qatar</h3>
      <p><strong>Sept 2024 - Aug 2024</strong></p>
      <ul>
        <li>Developed web apps using .NET (C#) and MVC</li>
        <li>Enhanced front-end with jQuery, HTML, CSS</li>
        <li>Managed PostgreSQL databases</li>
      </ul>
    </div>
  </section>

  <section id="skills" class="animate__animated animate__fadeInUp">
    <h2>Skills</h2>
    <div class="skills">
      <span class="skill">C#</span>
      <span class="skill">.NET MVC</span>
      <span class="skill">jQuery</span>
      <span class="skill">HTML & CSS</span>
      <span class="skill">PostgreSQL</span>
    </div>
  </section>

  <section id="projects" class="animate__animated animate__fadeInUp">
    <h2>Projects</h2>
    <ul>
      <li><a href="https://github.com/Anfal13/StaySwift-Hotel-Reservation-System" target="_blank">StaySwift Hotel Reservation System</a></li>
      <li><a href="https://github.com/Anfal13/StarEvents-Online-Event-Ticketing-System" target="_blank">StarEvents Online Event Ticketing System</a></li>
    </ul>
  </section>

  <section id="contact" class="animate__animated animate__fadeInUp">
    <h2>Contact</h2>
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

</body>
</html>
