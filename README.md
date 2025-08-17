
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Md. Fazla Rabbi - Portfolio</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: "Poppins", sans-serif; }

    body { background: #f5f6fa; color: #2c3e50; line-height: 1.6; }

    header {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: white; padding: 60px 20px; text-align: center;
    }
    header h1 { font-size: 2.5rem; }
    header p { font-size: 1.1rem; margin-top: 10px; }

    nav {
      display: flex; justify-content: center; gap: 20px;
      background: #2c3e50; padding: 15px;
    }
    nav a { color: white; text-decoration: none; font-weight: bold; transition: 0.3s; }
    nav a:hover { color: #f39c12; }

    section { padding: 60px 20px; max-width: 1000px; margin: auto; }
    section h2 { text-align: center; margin-bottom: 30px; font-size: 2rem; color: #34495e; }

    .about { text-align: center; }
    .about img { width: 150px; height: 150px; border-radius: 50%; margin-bottom: 20px; }

    .skills, .languages { display: flex; flex-wrap: wrap; justify-content: center; gap: 15px; }
    .skill, .lang {
      background: #203a43; color: white; padding: 10px 20px; border-radius: 20px; font-size: 0.9rem;
    }

    .projects, .education, .activities, .research {
      display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px;
    }
    .card {
      background: white; padding: 20px; border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1); transition: 0.3s;
    }
    .card:hover { transform: translateY(-5px); }
    .card h3 { margin-bottom: 10px; color: #2c3e50; }

    .contact { text-align: center; }
    .contact a {
      display: inline-block; margin: 10px; text-decoration: none;
      color: #203a43; font-weight: bold; border: 2px solid #203a43;
      padding: 10px 20px; border-radius: 25px; transition: 0.3s;
    }
    .contact a:hover { background: #203a43; color: white; }

    footer { background: #2c3e50; color: white; text-align: center; padding: 20px; margin-top: 30px; }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Md. Fazla Rabbi</h1>
    <p>📍 Kuril, Dhaka, Bangladesh</p>
    <p>📞 +8801601699066 | 📧 <a href="mailto:fazlarabbiabirbd@gmail.com" style="color:white;">fazlarabbiabirbd@gmail.com</a></p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#research">Research</a>
    <a href="#activities">Activities</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>BSc student in Computer Science & Engineering at AIUB, passionate about Artificial Intelligence, Data Science, and Cybersecurity. Active in research and extracurricular activities, aiming to build impactful digital solutions.</p>
  </section>

  <!-- Education -->
  <section id="education">
    <h2>Education</h2>
    <div class="education">
      <div class="card">
        <h3>BSc in CSE</h3>
        <p>American International University – Bangladesh (AIUB)</p>
        <p>Expected Graduation: Jan 2027</p>
      </div>
      <div class="card">
        <h3>HSC</h3>
        <p>Noakhali Government College</p>
        <p>Cumilla Board – 2021</p>
      </div>
      <div class="card">
        <h3>SSC</h3>
        <p>Al-Farooq Academy</p>
        <p>Cumilla Board – 2019</p>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2>Technical Skills</h2>
    <div class="skills">
      <span class="skill">C</span>
      <span class="skill">C++</span>
      <span class="skill">C#</span>
      <span class="skill">Python</span>
      <span class="skill">Java</span>
      <span class="skill">HTML</span>
      <span class="skill">CSS</span>
      <span class="skill">JavaScript</span>
      <span class="skill">PHP</span>
      <span class="skill">MySQL</span>
      <span class="skill">MongoDB</span>
      <span class="skill">AWS</span>
      <span class="skill">GitHub/GitLab</span>
      <span class="skill">Jupyter</span>
      <span class="skill">MATLAB</span>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Online Tech Shop Management System</h3>
        <p>Developed in Java to revolutionize management & user experience of virtual tech stores.</p>
      </div>
    </div>
  </section>

  <!-- Research -->
  <section id="research">
    <h2>Research & Coursework</h2>
    <div class="research">
      <div class="card">
        <h3>Relevant Coursework</h3>
        <p>Artificial Intelligence, Data Structures, Algorithms, Database Systems</p>
      </div>
      <div class="card">
        <h3>Research Interests</h3>
        <p>Artificial Intelligence, Data Science, Machine Learning, Cybersecurity</p>
      </div>
    </div>
  </section>

  <!-- Activities -->
  <section id="activities">
    <h2>Extracurricular Activities</h2>
    <div class="activities">
      <div class="card"><h3>AIUB R&D Club</h3><p>Researcher</p></div>
      <div class="card"><h3>AIUB English Club</h3><p>Organizer</p></div>
      <div class="card"><h3>AIUB Drama Club</h3><p>Member</p></div>
    </div>
  </section>

  <!-- Languages -->
  <section>
    <h2>Languages</h2>
    <div class="languages">
      <span class="lang">Bengali – Native</span>
      <span class="lang">English – Intermediate</span>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <a href="mailto:fazlarabbiabirbd@gmail.com">Email</a>
    <a href="https://github.com/fazla-rabbi-abir" target="_blank">GitHub</a>
    <a href="https://www.linkedin.com/in/fazla-rabbi-abir/" target="_blank">LinkedIn</a>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Md. Fazla Rabbi | All Rights Reserved</p>
  </footer>
</body>
</html>
