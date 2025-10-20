# world-workers-hub
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>World Workers Hub</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1 class="logo">World Workers Hub</h1>
    <p>Interior Design & Banquet Hall Construction Experts</p>
    <nav>
      <a href="#services">Services</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="hero">
    <h2>Design Your Dream Space</h2>
    <p>Modern interior designs & elegant banquet halls tailored for your vision.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li><strong>Interior Design:</strong> Homes, Offices, Restaurants</li>
      <li><strong>Banquet Hall Construction:</strong> Design & Turnkey Execution</li>
      <li><strong>3D Design & Layout:</strong> Visual mockups before execution</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Recent Projects</h2>
    <p>Our latest interiors and banquet hall creations will be added here soon.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Address:</strong> 104A, Gali No. 1, Phase 5, E Block, Aya Nagar, Delhi – 110047</p>
    <p><strong>Phone:</strong><br>
      +91 90454 03696<br>
      +91 88812 53887<br>
      +91 98196 12589
    </p>
    <p><strong>Email:</strong> contact@worldworkershub.com (optional – if you have an email)</p>
    
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 World Workers Hub. All rights reserved.</p>
  </footer>

</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
  color: #333;
}

header {
  background-color: #2c3e50;
  color: white;
  padding: 30px 20px;
  text-align: center;
}

.logo {
  font-size: 36px;
  font-weight: bold;
  letter-spacing: 2px;
  color: #ffcc00;
}

nav a {
  color: #ffffff;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

#hero {
  background-color: #ecf0f1;
  padding: 60px 20px;
  text-align: center;
}

#hero h2 {
  font-size: 32px;
  margin-bottom: 10px;
}

#services, #projects, #contact {
  padding: 40px 20px;
  max-width: 800px;
  margin: auto;
}

ul {
  list-style: square;
  padding-left: 20px;
}

form {
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin-top: 20px;
}

form input, form textarea {
  padding: 12px;
  font-size: 1rem;
  border: 1px solid #ccc;
  border-radius: 4px;
}

form button {
  background-color: #2c3e50;
  color: white;
  padding: 12px;
  border: none;
  cursor: pointer;
  font-size: 1rem;
}

form button:hover {
  background-color: #1a252f;
}

footer {
  background-color: #2c3e50;
  color: white;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
}
