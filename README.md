<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kalyani Portfolio</title>
  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
</head>
<body>
  <header id="header">
    <nav class="navbar">
      <div class="logo">Kalyani Varpe</div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#certificates">Certificates</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
      <button id="theme-toggle" aria-label="Toggle light/dark mode">🌙</button>
      <div class="menu-toggle" id="mobile-menu">
        <span></span><span></span><span></span>
      </div>
    </nav>
  </header>
  <main>
    <section id="home" class="section home-section">
      <div class="banner">
        <h1>Hello, I'm Kalyani Varpe</h1>
        <p class="tagline">Building elegant solutions with code.</p>
      </div>
    </section>
    <section id="about" class="section about-section">
      <h2>About Me</h2>
        <p>Hello! I'm Kalyani Varpe, a passionate and dedicated Computer Engineering student with a strong interest in web development, machine learning, and programming. I enjoy turning ideas into functional, user-friendly projects using clean code and creativity.
          Over time, I've built several projects using HTML, CSS, JavaScript, and Python—including AI-powered tools, responsive websites, and ML models. I love learning new technologies and applying them to real-world problems. My goal is to build impactful tech solutions while constantly improving my skills.
      </p>
    </section>
    <!-- Fun Facts Section -->
    <section id="fun-facts" class="section fun-facts-section">
      <h2>Fun Facts</h2>
      <ul class="fun-facts-list">
        <li>I can solve a Rubik's cube in under 2 minutes!</li>
        <li>I love painting and digital art.</li>
        <li>I'm a big fan of science fiction novels.</li>
        <li>I enjoy hiking and exploring nature trails.</li>
      </ul>
    </section>
    <section id="skills" class="section skills-section">
      <h2>Skills</h2>
      <ul class="skills-list">
        <li><span class="skill-icon">🐍</span> Python
          <div class="skill-bar"><div class="skill-level" style="width: 90%"></div></div>
        </li>
        <li><span class="skill-icon">🌐</span> HTML
          <div class="skill-bar"><div class="skill-level" style="width: 95%"></div></div>
        </li>
        <li><span class="skill-icon">🎨</span> CSS
          <div class="skill-bar"><div class="skill-level" style="width: 90%"></div></div>
        </li>
        <li><span class="skill-icon">⚡</span> JavaScript
          <div class="skill-bar"><div class="skill-level" style="width: 80%"></div></div>
        </li>
        <li><span class="skill-icon">🤖</span> Machine Learning
          <div class="skill-bar"><div class="skill-level" style="width: 75%"></div></div>
        </li>
        <li><span class="skill-icon">💻</span> C++
          <div class="skill-bar"><div class="skill-level" style="width: 70%"></div></div>
        </li>
      </ul>
    </section>
    <section id="certificates" class="section certificates-section">
      <h2>Certificates</h2>
      <div class="certificates-grid">
        <div class="certificate-thumb"><a href="D:\kalyani\kalyani\certificates\1-5af8a9c8-83c0-4746-8185-d2e651700731.pdf" target="_blank"><img src="C:\Users\DELL\Pictures\quality1.png" alt="Certificate 1"></a></div>
        <div class="certificate-thumb"><a href="D:\kalyani\kalyani\certificates\1749825506112-certificate.png" target="_blank"><img src="C:\Users\DELL\Pictures\quality1.png" alt="Certificate 2"></a></div>
        <div class="certificate-thumb"><a href="D:\kalyani\kalyani\certificates\aws forage.pdf" target="_blank"><img src="C:\Users\DELL\Pictures\quality1.png" alt="Certificate 3"></a></div>
        <div class="certificate-thumb"><a href="D:\kalyani\kalyani\certificates\certificate-icon.png" target="_blank"><img src="C:\Users\DELL\Pictures\quality1.png" alt="Certificate 4"></a></div>
        <div class="certificate-thumb"><a href="D:\kalyani\kalyani\certificates\deliotte forage.pdf" target="_blank"><img src="C:\Users\DELL\Pictures\quality1.png" alt="Certificate 4"></a></div>
        <div class="certificate-thumb"><a href="D:\kalyani\kalyani\certificates\Edureka - Internship Certificate.pdf" target="_blank"><img src="C:\Users\DELL\Pictures\quality1.png" alt="Certificate 4"></a></div>
        <div class="certificate-thumb"><a href="D:\kalyani\kalyani\certificates\Forage accenture.pdf" target="_blank"><img src="C:\Users\DELL\Pictures\quality1.png" alt="Certificate 4"></a></div>
        <div class="certificate-thumb"><a href="D:\kalyani\kalyani\certificates\natioon building certificate.pdf" target="_blank"><img src="C:\Users\DELL\Pictures\quality1.png" alt="Certificate 4"></a></div>
        <div class="certificate-thumb"><a href="D:\kalyani\kalyani\certificates\No-Code_AI_Bootcamp_Completion_certificate.pdf" target="_blank"><img src="C:\Users\DELL\Pictures\quality1.png" alt="Certificate 4"></a></div>
        <div class="certificate-thumb"><a href="D:\kalyani\kalyani\certificates\simplilearn AI certificate.pdf" target="_blank"><img src="C:\Users\DELL\Pictures\quality1.png" alt="Certificate 4"></a></div>
        <div class="certificate-thumb"><a href="D:\kalyani\kalyani\certificates\sppu .pdf" target="_blank"><img src="C:\Users\DELL\Pictures\quality1.png" alt="Certificate 4"></a></div>
        <div class="certificate-thumb"><a href="D:\kalyani\kalyani\certificates\tata forage.pdf" target="_blank"><img src="C:\Users\DELL\Pictures\quality1.png" alt="Certificate 4"></a></div>
        
      </div>

    </section>
    <section id="contact" class="section contact-section">
      <h2>Contact</h2>
      <form id="contact-form">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
      <div class="contact-icons">
        <a href="https://github.com/" target="_blank" aria-label="GitHub">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub">
        </a>
        <a href="https://www.linkedin.com/in/kalyani-varpe-7724a6319?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank" aria-label="LinkedIn">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="LinkedIn">
        </a>
        <a href="mailto:varpekalyani7@gmail.com" aria-label="Email">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" alt="Email">
        </a>
      </div>
    </section>
  </main>
  <footer>
    <p>&copy; 2024 Kalyani. All rights reserved.</p>
  </footer>
  <script src="script.js"></script>
</body>
</html> 
