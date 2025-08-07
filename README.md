# My-Personal-Portfolio-Website
Project Idea:

A personal website that displays information about you, such as:
 • Your name and profile picture
 • About Me section
 • Skills
 • Projects or Portfolio
 • Contact information

⸻

🎯 Project Objectives:
 • Learn how to design websites using HTML and CSS
 • Build a professional personal webpage that can be published
 • Practice user interface (UI) design and layout
 • Use it as part of your resume or job applications

⸻

🛠️ Tools Used:
 • HTML – for structuring the website
 • CSS – for styling and designing the layout

⸻

📁 Website Sections:
 1. Home
 • Your name
 • Your field or title
 2. About Me
 • A brief introduction about yourself
 3. Skills
 • Programming languages or technical skills
 4. Projects
 • Links to some of your previous projects
 5. Contact Me
 • Your email address

⸻

Code HTML:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Personal Website</title>

  <!-- Link to external CSS file -->
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Navigation Bar -->
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Me</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Home Section -->
  <section id="home">
    <h1>Hello, I'm <span>Aseel Alqurashi</span></h1>
    <p>Computer Engineer | CE</p>
  </section>

  <!-- About Me Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>This is a short introduction about myself. I have a passion for programming and creating simple projects. </p>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>Embedded System: Arduino & Raspberry Pi</li>
      <li>Programming:C++,Python,HTML</li>
      <li>Database Management:MySQL</li>
      <li>Operating System:Windows,Linux</li>
    </ul>
  </section>

 <!-- Projects Section -->
<section id="projects">
  <h2>Projects</h2>

  <div>
    <h3>Ultrasonic Sensor with Servo Motor</h3>
    <p>
      An embedded system project using an ultrasonic sensor and a servo motor. 
      The servo rotates based on the distance measured by the sensor. 
      Ideal for obstacle detection and smart robotics.
    </p>
    <a href="https://github.com/aseel-Q/Auto-Move-4x-and-Smart-Servo-Reaction-System" target="_blank">View on GitHub</a>
  </div>

  <div>
    <h3>Employee Management System</h3>
    <p>
      A web-based system to add, update, and manage employees using PHP and a MySQL database.
    </p>
    <a href="https://github.com/aseel-Q/Simple-Employee-Info-Manager" target="_blank">View on GitHub</a>
  </div>

  <div>
    <h3>Personal Portfolio Website</h3>
    <p>
      This responsive website (you're viewing it now) was designed and coded from scratch using HTML and CSS.
    </p>
  </div>
</section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: aseelalqurashi74@gmail.com</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 All Rights Reserved</p>
  </footer>

</body>
</html>

⸻

Code CSS:
/* Global settings */
body {
  font-family: sans-serif;
  background-color: #f9f9f9; /* Light background */
  color: #333; /* Dark text */
  margin: 0;
  padding: 0;
  line-height: 1.6;
}

/* Navigation bar styling */
nav {
  background: #ffffff;
  padding: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  position: sticky;
  top: 0;
  z-index: 1000;
}

nav ul {
  display: flex;
  justify-content: center;
  gap: 15px;
  list-style: none;
  margin: 0;
  padding: 0;
}

nav a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
}

/* Section layout */
section {
  padding: 40px 20px;
  text-align: center;
}

/* Header and footer style */
header, footer {
  text-align: center;
  padding: 20px;
  background: #ffffff;
}

/* Responsive design: for screens smaller than 768px */
@media (max-width: 768px) {
  nav ul {
    flex-direction: column; /* Stack menu items vertically */
  }
}

