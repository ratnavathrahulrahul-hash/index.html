
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rahul Ratnavath | Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: #f8fafc;
      line-height: 1.7;
    }

    header {
      background: #111827;
      padding: 18px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 12px;
    }

    header h2 { color: #38bdf8; }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 8px;
    }

    nav a:hover { color: #38bdf8; }

    section { padding: 65px 8%; }

    .hero {
      min-height: 75vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: flex-start;
    }

    .hero h1 {
      font-size: clamp(32px, 6vw, 52px);
      line-height: 1.2;
      margin: 15px 0;
    }

    .highlight { color: #38bdf8; }

    .button {
      display: inline-block;
      background: #38bdf8;
      color: #0f172a;
      padding: 10px 20px;
      margin-top: 20px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }

    h2.section-title {
      color: #38bdf8;
      margin-bottom: 20px;
    }

    .card {
      background: #1e293b;
      padding: 22px;
      border-radius: 12px;
      margin: 15px 0;
      border: 1px solid #334155;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .skills span {
      background: #1e293b;
      border: 1px solid #38bdf8;
      padding: 8px 16px;
      border-radius: 20px;
    }

    a { overflow-wrap: anywhere; }

    footer {
      text-align: center;
      background: #111827;
      padding: 22px;
      color: #cbd5e1;
    }
  </style>
</head>
<body>

  <header>
    <h2>Rahul.</h2>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <p>Hello, welcome to my portfolio!</p>
    <h1>I'm <span class="highlight">Rahul Ratnavath</span></h1>
    <h3>Aspiring Web Developer | B.Tech CSE Student</h3>
    <p>I create simple, responsive and user-friendly websites.</p>
    <a class="button" href="#projects">Explore My Projects</a>
  </section>

  <section id="about">
    <h2 class="section-title">About Me</h2>
    <div class="card">
      <p>
        I am Rahul Ratnavath, a Computer Science student passionate
        about web development and technology. I enjoy learning new
        skills, solving problems and building useful websites.
        My goal is to grow as a developer and contribute to real-world
        projects.
      </p>
      <p><strong>Education:</strong> Diploma in Computer Science & Engineering</p>
      <p><strong>College:</strong> Warangal Institute of Technology and Science</p>
      <p><strong>Percentage:</strong> 82.78%</p>
    </div>
  </section>

  <section id="skills">
    <h2 class="section-title">My Skills</h2>
    <div class="skills">
      <span>HTML</span>
      <span>CSS</span>
      <span>JavaScript</span>
      <span>Bootstrap</span>
      <span>Java</span>
      <span>Python</span>
      <span>C</span>
      <span>C++</span>
    </div>
  </section>

  <section id="projects">
    <h2 class="section-title">My Projects</h2>
    <div class="card">
      <h3>Event Management Website</h3>
      <p>
        A web design project focused on presenting events,
        attractive layouts and responsive user experiences.
      </p>
      <p><strong>Technologies:</strong> HTML, CSS, JavaScript</p>
    </div>
    <div class="card">
      <h3>Personal Portfolio Website</h3>
      <p>A personal website to showcase my skills, education and projects.</p>
      <p><strong>Technologies:</strong> HTML, CSS</p>
    </div>
  </section>

  <section id="contact">
    <h2 class="section-title">Contact Me</h2>
    <div class="card">
      <p>Email: ratnavathrahulrahul@gmail.com</p>
      <p>Location: Warangal, Telangana</p>
      <p>
        LinkedIn:
        <a href="https://www.linkedin.com/in/ratnavath-rahul-940911433"
           target="_blank" rel="noopener noreferrer">
          Visit my LinkedIn
        </a>
      </p>
      <p>
        GitHub:
        <a href="https://github.com/ratnavathrahulrahul-hash"
           target="_blank" rel="noopener noreferrer">
          Visit my GitHub
        </a>
      </p>
      <p>
        LeetCode:
        <a href="https://leetcode.com/u/Mr_rahul19/"
           target="_blank" rel="noopener noreferrer">
          Visit my LeetCode
        </a>
      </p>
    </div>
  </section>

  <footer>
    <p>© 2026 Rahul Ratnavath | Personal Portfolio</p>
  </footer>

</body>
</html>
