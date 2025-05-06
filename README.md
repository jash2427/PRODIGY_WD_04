# PRODIGY_WD_04
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Jashwanth's Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #1a1a1a;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      margin-top: 20px;
    }

    nav {
      background: #333;
      display: flex;
      justify-content: center;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      padding: 10px 20px;
      font-weight: bold;
    }

    nav a:hover {
      background: #555;
      border-radius: 5px;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }

    section {
      margin-bottom: 40px;
    }

    h2 {
      color: #222;
      margin-bottom: 15px;
      border-bottom: 2px solid #ccc;
      padding-bottom: 5px;
    }

    .skills, .projects, .experience {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
    }

    .card {
      background: white;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    @media(max-width: 768px) {
      .skills, .projects, .experience {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Hello, I'm Jashwanth</h1>
    <p>A Web Developer passionate about building fast, accessible, and beautiful web applications.</p>
    <img src="https://via.placeholder.com/150" alt="Profile Photo" />
  </header>

  <nav>
    <a href="#about">About Me</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#experience">Experience</a>
  </nav>

  <div class="container">
    <section id="about">
      <h2>About Me</h2>
      <p>I'm a dedicated web developer with a background in computer science. I hold a Bachelor's degree in Information Technology from <strong>GITAM University</strong> and have 3+ years of experience working with front-end and back-end web technologies. I enjoy turning complex problems into simple, beautiful, and intuitive designs.</p>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <div class="skills">
        <div class="card">HTML5 & CSS3</div>
        <div class="card">JavaScript (ES6+)</div>
        <div class="card">c,c++</div>
        <div class="card">python</div>
        <div class="card">VScode & MySQL</div>
        <div class="card">Git & GitHub</div>
      </div>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="projects">
        <div class="card">
          <h3>University Database Management System</h3>
          <p>Developed a University Database Management System with relational schemas</p>
        </div>
        <div class="card">
          <h3>E-commerce Store</h3>
          <p>Built with React and Firebase, supports login and real-time database updates.</p>
        </div>
      </div>
    </section>

    <section id="experience">
      <h2>Professional Experience</h2>
      <div class="experience">
        <div class="card">
          <h3>Frontend Developer – Tech Solutions Inc.</h3>
          <p>Hyderabad, India · Jan 2023 – Present</p>
          <p>Developed and maintained responsive web interfaces using HTML, CSS, and JavaScript (ES6+).
Optimized page performance and reduced load time by 30% through code refactoring and lazy loading</p>
        </div>
        <div class="card">
          <h3>Web Developer Intern – DevStudio</h3>
          <p>2022 - 2023</p>
          <p>Assisted in designing and developing responsive websites for clients.</p>
        </div>
      </div>
    </section>
  </div>

  <footer>
    <p>© 2025 Jashwanth. All rights reserved.</p>
  </footer>

</body>
</html>
