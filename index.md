<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My GitHub Profile</title>
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Press Start 2P', cursive; /* Energetic retro gaming font */
      background-color: #222; /* Dark background */
      color: #0f0; /* Neon green text color */
    }
    a {
      color: #0ff; /* Electric blue link color */
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .container {
      max-width: 960px;
      margin: 0 auto;
      padding: 20px;
    }
    header {
      text-align: center;
      margin-bottom: 40px;
    }
    .avatar {
      border-radius: 50%;
      border: 5px solid #0f0; /* Neon green border */
      box-shadow: 0 0 10px #0f0; /* Neon green glow */
    }
    h1 {
      font-size: 2.5em;
      margin: 20px 0 10px;
    }
    .tagline {
      font-style: italic;
      color: #ff0; /* Yellow tagline */
    }
    .social-links {
      margin-top: 20px;
    }
    .social-links a {
      display: inline-block;
      margin: 0 10px;
      font-size: 1.5em;
    }
    section {
      margin-bottom: 40px;
    }
    h2 {
      font-size: 2em;
      border-bottom: 2px solid #0f0; /* Neon green underline */
      padding-bottom: 10px;
      margin-bottom: 20px;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    li {
      margin-bottom: 10px;
    }
    .project-image {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 0 10px #000;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <img class="avatar" src="your-profile-image.jpg" alt="My Avatar"> 
      <h1>John Doe</h1>
      <p class="tagline">Coding with Energy!</p>
      <div class="social-links">
        <a href="https://twitter.com/your_twitter"><i class="fab fa-twitter"></i></a>
        <a href="https://linkedin.com/in/your_linkedin"><i class="fab fa-linkedin"></i></a>
        <a href="https://github.com/your_github"><i class="fab fa-github"></i></a>
      </div>
    </header>

    <main>
      <section>
        <h2>About Me</h2>
        <p>I'm a passionate software engineer with a love for building cool things with code. I thrive on challenges and enjoy exploring new technologies. When I'm not coding, you can find me [your hobbies - e.g.,  rock climbing, playing video games, exploring new coffee shops].</p>
      </section>

      <section>
        <h2>Skills</h2>
        <ul>
          <li>Python</li>
          <li>JavaScript</li>
          <li>React</li>
          <li>HTML/CSS</li>
          <li>Node.js</li>
          <li>SQL</li>
        </ul>
      </section>

      <section>
        <h2>Experience</h2>
        <ul>
          <li>
            <h3>Software Engineer</h3>
            <p>Acme Corp (2020 - Present)</p>
            <p>Developing cutting-edge web applications using React and Node.js. Collaborating with a talented team to deliver high-quality products.</p>
          </li>
          <li>
            <h3>Web Developer Intern</h3>
            <p>XYZ Company (2019)</p>
            <p>Gained valuable experience in front-end development, working on various projects using HTML, CSS, and JavaScript.</p>
          </li>
        </ul>
      </section>

      <section>
        <h2>Projects</h2>
        <ul>
          <li>
            <a href="https://github.com/your_github/project1">
              <img class="project-image" src="https://source.unsplash.com/300x200/?website,design" alt="Project 1 Screenshot">
              <h3>Project 1</h3>
            </a>
            <p>A brief description of your project.  Built with [technologies used].</p>
          </li>
          <li>
            <a href="https://github.com/your_github/project2">
              <img class="project-image" src="https://source.unsplash.com/300x200/?mobile-app,technology" alt="Project 2 Screenshot">
              <h3>Project 2</h3>
            </a>
            <p>A brief description of your project. Built with [technologies used].</p>
          </li>
        </ul>
      </section>

      <section>
        <h2>Contact</h2>
        <p>Let's connect! You can reach me at <a href="mailto:your_email@example.com">your_email@example.com</a>.</p>
      </section>
    </main>

    <footer>
      <p>&copy; 2023 John Doe</p>
    </footer>
  </div>
</body>
</html>