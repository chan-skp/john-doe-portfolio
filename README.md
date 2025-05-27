<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>John Doe Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #1e90ff;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #333;
    }
    nav a {
      color: white;
      padding: 1rem;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #555;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }
    .project-card {
      background: white;
      padding: 1rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 8px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #1e90ff;
      color: white;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>John Doe</h1>
    <p>Web Developer & Designer</p>
  </header>
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="about">
    <h2>About Me</h2>
    <p>I am a passionate web developer creating modern and responsive designs. I specialize in front-end development and love bringing ideas to life in the browser.</p>
  </section>
  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>Portfolio Website</h3>
        <p>A sleek and modern portfolio to showcase personal projects and skills.</p>
      </div>
      <div class="project-card">
        <h3>To-Do App</h3>
        <p>A simple JavaScript app to manage daily tasks and boost productivity.</p>
      </div>
    </div>
  </section>
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: johndoe@example.com</p>
    <p>LinkedIn: linkedin.com/in/johndoe</p>
  </section>
  <footer>
    <p>&copy; 2025 John Doe. All rights reserved.</p>
  </footer>
</body>
</html>
