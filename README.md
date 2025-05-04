<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Portfolio Website</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f9f9f9; }
    header, nav, section, footer { padding: 20px; }
    nav a { margin: 0 10px; text-decoration: none; color: #0073e6; }
    section { border-bottom: 1px solid #ccc; background: white; }
    h2 { color: #333; }
    img.profile { width: 150px; border-radius: 50%; }
    .project, .post { margin-bottom: 20px; }
    footer { text-align: center; font-size: 14px; background: #eee; }
    a.button { background: #0073e6; color: white; padding: 8px 12px; text-decoration: none; border-radius: 4px; }
  </style>
</head>
<body>

<header>
  <h1>Welcome to My Website</h1>
  <p>This site showcases who I am and what I do.</p>
  <nav>
    <a href="#about">About Me</a>
    <a href="#portfolio">Projects</a>
    <a href="#blog">Blog</a>
    <a href="#resume">Resume</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="about">
  <h2>About Me</h2>
  <img src="your-photo.jpg" alt="Your Photo" class="profile">
  <p>Hi, I'm [Your Name]. I'm passionate about [your interests] and currently [your background or role].</p>
</section>

<section id="portfolio">
  <h2>Portfolio / Projects</h2>
  <div class="project">
    <h3>Project One</h3>
    <p>Description: A brief explanation of what the project does.</p>
    <p>Tools Used: HTML, CSS, JavaScript</p>
    <a href="https://link-to-project.com" class="button">View Project</a>
  </div>
  <div class="project">
    <h3>Project Two</h3>
    <p>Description: Another awesome project.</p>
    <p>Tools Used: React, Firebase</p>
    <a href="https://link-to-project.com" class="button">View Project</a>
  </div>
</section>

<section id="blog">
  <h2>Blog / Reflection</h2>
  <div class="post">
    <h3>Post 1: My Learning Journey</h3>
    <p>I started learning web development and it's been amazing...</p>
  </div>
  <div class="post">
    <h3>Post 2: Challenges in My First Project</h3>
    <p>Building my first site taught me a lot about problem-solving...</p>
  </div>
</section>

<section id="resume">
  <h2>Resume / CV</h2>
  <p>You can <a href="resume.pdf" download>download my resume here</a>.</p>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: yourname@example.com</p>
  <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile">linkedin.com/in/yourprofile</a></p>
  <p>Twitter: <a href="https://twitter.com/yourhandle">@yourhandle</a></p>
</section>

<footer>
  <p>&copy; 2025 Your Name. All rights reserved.</p>
</footer>

</body>
</html>
