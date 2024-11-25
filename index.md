<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My GitHub Profile</title>
  <link rel="stylesheet" href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css">
</head>
<body>
  <div class="container mx-auto px-4">
    <header class="flex flex-col items-center justify-center py-8 mb-8">
      <img class="w-20 h-20 rounded-full" src="https://avatars.githubusercontent.com/u/123456789?v=4" alt="My Avatar">
      <h1 class="text-3xl font-bold text-center">John Doe</h1>
      <p class="text-gray-500 text-center">Software Engineer</p>
      <div class="flex flex-row justify-center mt-4">
        <a href="https://twitter.com/johndoe" class="text-gray-500 hover:text-blue-500 mr-4">
          <i class="fab fa-twitter"></i>
        </a>
        <a href="https://www.linkedin.com/in/johndoe" class="text-gray-500 hover:text-blue-500 mr-4">
          <i class="fab fa-linkedin"></i>
        </a>
        <a href="https://github.com/johndoe" class="text-gray-500 hover:text-blue-500">
          <i class="fab fa-github"></i>
        </a>
      </div>
    </header>
    <main class="mb-8">
      <section class="border-b pb-4">
        <h2 class="text-2xl font-bold mb-2">About Me</h2>
        <p>I am a passionate software engineer with X years of experience in building web applications. I am skilled in a variety of technologies, including Python, JavaScript, and React. I am always looking for new challenges and opportunities to learn and grow.</p>
      </section>
      <section class="border-b pb-4">
        <h2 class="text-2xl font-bold mb-2">Skills</h2>
        <ul class="list-disc ml-4">
          <li>Python</li>
          <li>JavaScript</li>
          <li>React</li>
          <li>HTML</li>
          <li>CSS</li>
        </ul>
      </section>
      <section class="border-b pb-4">
        <h2 class="text-2xl font-bold mb-2">Experience</h2>
        <div class="mb-4">
          <h3 class="font-bold">Software Engineer</h3>
          <p>Acme Inc.</p>
          <p>2020 - Present</p>
          <ul class="list-disc ml-4">
            <li>Developed and maintained web applications using Python and React.</li>
            <li>Designed and implemented new features.</li>
            <li>Collaborated with a team of engineers to deliver projects on time and within budget.</li>
          </ul>
        </div>
        <div class="mb-4">
          <h3 class="font-bold">Software Engineer Intern</h3>
          <p>XYZ Company</p>
          <p>2019</p>
          <ul class="list-disc ml-4">
            <li>Developed and tested web applications using JavaScript and HTML.</li>
            <li>Gained experience working in a fast-paced environment.</li>
          </ul>
        </div>
      </section>
      <section class="border-b pb-4">
        <h2 class="text-2xl font-bold mb-2">Education</h2>
        <div class="mb-4">
          <h3 class="font-bold">Bachelor of Science in Computer Science</h3>
          <p>University of California, Berkeley</p>
          <p>2015 - 2019</p>
        </div>
      </section>
      <section class="border-b pb-4">
        <h2 class="text-2xl font-bold mb-2">Projects</h2>
        <ul class="list-disc ml-4">
          <li><a href="https://github.com/johndoe/project1">Project 1</a></li>
          <li><a href="https://github.com/johndoe/project2">Project 2</a></li>
          <li><a href="https://github.com/johndoe/project3">Project 3</a></li>
        </ul>
      </section>
      <section class="border-b pb-4">
        <h2 class="text-2xl font-bold mb-2">Contact</h2>
        <p>Feel free to contact me via email at johndoe@example.com or on any of my social media profiles.</p>
      </section>
    </main>
    <footer class="text-center text-gray-500 py-4">
      <p>Made with ❤️ by John Doe</p>
    </footer>
  </div>
</body>
</html>