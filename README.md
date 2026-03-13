<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      color: #333;
    }
    header {
      background-color: #4CAF50;
      padding: 20px;
      text-align: center;
      color: white;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 15px;
      margin-top: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 800px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    .skills, .projects {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
    }
    .card {
      background-color: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.15);
      flex: 1 1 150px;
      text-align: center;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px;
    }
    @media (max-width: 500px) {
      nav {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Hi, I'm Ehan</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm a student and an aspiring entrepreneur. I love creating projects and exploring new ideas. This is my small personal portfolio website.</p>
  </section>

  <section id="skills">
    <h2>My Skills</h2>
    <div class="skills">
      <div class="card">HTML</div>
      <div class="card">CSS</div>
      <div class="card">JavaScript</div>
       <div class="card">Promt Engineering</div>
       <div class="card">Graphic design</div>
       <div class="card">SMM</div>
    </div>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="card">Portfolio Website</div>
      <div class="card">Mini AI Chatbot</div>
      <div class="card">POD Brand Designs</div>
      <div class="card">Brand builder agency</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email studiovisionkraft@gmail.com</p>
    <p>Phone: +880123456789</p>
  </section>

  <footer>
    &copy; 2026 Ehan Chowdhury. All Rights Reserved.
  </footer>

</body>
</html>
