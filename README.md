<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PERSONAL PORTFOLIO</title>
  <style>
    /* General Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #f9f7f7;
      background-color: #030303;
    }

    /* Navigation Bar */
    nav {
      background-color: #fff9f9;
      color: #fff;
      padding: 15px 0;
    }

    .nav-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 0 20px;
    }

    .nav-links {
      list-style-type: none;
    }

    .nav-links li {
      display: inline;
      margin-right: 20px;
    }

    .nav-links a {
      color: #fff;
      text-decoration: none;
    }

    .nav-links a:hover {
      text-decoration: underline;
    }

    /* Home Section */
    .home {
      background-color: #040404;
      padding: 60px 20px;
      text-align: center;
    }

    .home h1 {
      font-size: 3rem;
    }

    .home p {
      font-size: 1.2rem;
      color: #f4f2f2;
    }

    /* About Section */
    .about {
      padding: 50px 20px;
      text-align: center;
      background-color: #010000;
    }

    .about h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .about p {
      font-size: 1.2rem;
      color: #fbf8f8;
    }

    /* Work Section */
    .work {
      padding: 50px 20px;
      background-color: #070707;
    }

    .work h2 {
      font-size: 2.5rem;
      margin-bottom: 30px;
      text-align: center;
    }

    .work-gallery {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
    }

    .work-item {
      width: 30%;
      margin-bottom: 20px;
      text-align: center;
    }

    .work-item img {
      width: 100%;
      height: auto;
      border-radius: 8px;
      box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    }

    .work-item p {
      margin-top: 10px;
      font-size: 1rem;
      color: #fdfbfb;
    }

    /* Contact Section */
    .contact {
      padding: 50px 20px;
      background-color: #000000;
      text-align: center;
    }

    .contact h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .contact form {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .contact input,
    .contact textarea {
      width: 80%;
      padding: 10px;
      margin: 10px 0;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .contact button {
      padding: 10px 20px;
      background-color: #333;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .contact button:hover {
      background-color: #faf8f8;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px 0;
      background-color: #333;
      color: #fff;
    }

    footer p {
      font-size: 1rem;
    }

  </style>
</head>
<body>
  <!-- Navigation Bar -->
  <nav>
    <div class="nav-container">
      <a href="#home" class="logo">Your Name</a>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#work">Work</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Home Section -->
  <section id="home" class="home">
    <div class="home-content">
      <h1>Welcome to My Portfolio</h1>
      <p>Hi, I'm Loraine Joy M Casem, a passionate Security Engineer/Information Security Crime Investigator/Forensics Expert focused on delivering quality work.</p>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>I'm a Loraine Joy M Casem with experience in cyber security. I enjoy creating and helping to protect the confidentiality,integrity, and availability of computer system,network and data, against cyber-attack and unauthorized access.</p>
  </section>

  <!-- Work Section -->
  <section id="work" class="work">
    <h2>My Work</h2>
    <div class="work-gallery">
      <div class="work-item">
        <img src="image1.jpg" alt="Project 1">
        <p>Project 1:Network Vulnerability Assessment And Penetration Testing- Perform thorough vulnerability assessment and penetration test on a sample corporate network to indentify and exploit weakness, with a focus on improving network security. Perform a comprehensive network vulnerability assessment and penetration test on a corporate network. Identified several critical vulnerabilities,successfully exploited weak services, and provided detailed remediation steps to improve overall security plans</p>
      </div>
      <div class="work-item">
        <img src="image2.jpg" alt="Project 2">
        <p>Project 2: Building Secure Web Application-Developed and secured a web application by addressing the OWASP Top 10 vulnerabilities. Successfully mitigated risks like SQL injection, XSS, and weak authentication mechanisms using modern security practices. Provided a detailed report on the security measures implemented.".</p>
      </div>
      <div class="work-item">
        <img src="image3.jpg" alt="Project 3">
        <p>Project 3:Incident Response Simulation and Forensics Investigation-Simulated a cyberattack and executed an incident response scenario, including malware infection detection, forensic analysis of compromised systems, and containment. Provided actionable insights and security improvements to prevent future breaches.</p>
      </div>
    </div>;
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form id="contact-form">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2024 [Loraine Joy M Casem]. All rights reserved.</p>
  </footer>

  <
