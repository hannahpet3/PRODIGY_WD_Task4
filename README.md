<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Hannah Petrina - Portfolio</title>
  <style>
    :root {
      --primary: #4a90e2;
      --dark: #1c1c1c;
      --light: #f4f4f4;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background-color: var(--dark);
      color: var(--light);
      line-height: 1.6;
    }

    header {
      background: var(--primary);
      padding: 60px 20px;
      text-align: center;
      color: white;
    }

    header img {
      width: 120px;
      border-radius: 50%;
      border: 3px solid white;
      margin-bottom: 15px;
    }

    header h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2em;
      font-style: italic;
    }

    nav {
      background: #333;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      color: var(--primary);
      margin-bottom: 15px;
      font-size: 1.8em;
    }

    .skills ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .skills li {
      background: #2e2e2e;
      padding: 10px 15px;
      border-radius: 5px;
    }

    .projects .project {
      background: #2e2e2e;
      padding: 15px;
      border-radius: 8px;
      margin-bottom: 15px;
    }

    .projects a {
      color: #00c3ff;
      text-decoration: none;
    }

    footer {
      background: #111;
      color: #999;
      padding: 20px;
      text-align: center;
      font-size: 0.9em;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2em;
      }

      .skills ul {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

<header>
  <img src="https://via.placeholder.com/120" alt="Profile Picture">
  <h1>Hannah Petrina</h1>
  <p>Frontend Developer | Creative Thinker | Intern @ Prodigy InfoTech</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#skills">Skills</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About Me</h2>
  <p>I am a passionate frontend developer focused on building clean, user-friendly websites and applications. During my internship with Prodigy InfoTech, I created real-world projects like landing pages, games, and tools using HTML, CSS, and JavaScript.</p>
</section>

<section id="skills" class="skills">
  <h2>Skills</h2>
  <ul>
    <li>HTML5</li>
    <li>CSS3</li>
    <li>JavaScript</li>
    <li>Responsive Design</li>
    <li>Git & GitHub</li>
    <li>Basic React</li>
  </ul>
</section>

<section id="projects" class="projects">
  <h2>Projects</h2>

  <div class="project">
    <h3>Stopwatch App</h3>
    <p>A simple stopwatch with lap tracking. <a href="#">Live Demo</a> | <a href="https://github.com/hannahpet3/stopwatch-app">GitHub</a></p>
  </div>

  <div class="project">
    <h3>Tic Tac Toe Game</h3>
    <p>Classic game with 2-player and vs-computer modes. <a href="#">Live Demo</a> | <a href="https://github.com/hannahpet3/tic-tac-toe">GitHub</a></p>
  </div>

  <div class="project">
    <h3>Responsive Landing Page</h3>
    <p>A clean, scroll-animated web page. <a href="#">Live Demo</a> | <a href="https://github.com/hannahpet3/landing-page">GitHub</a></p>
  </div>

</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: hannahpetrina@gmail.com</p>
  <p>LinkedIn: <a href="https://www.linkedin.com/in/hannah-petrina-554889350/" target="_blank">linkedin.com/in/hannah-petrina</a></p>
  <p>GitHub: <a href="https://github.com/hannahpet3" target="_blank">github.com/hannahpet3</a></p>
</section>

<footer>
  <p>© 2024 Hannah Petrina — Built with 💙 using HTML & CSS</p>
</footer>

</body>
</html>
