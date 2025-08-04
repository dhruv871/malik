<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Malik Tech - Tech Services</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header>
    <div class="hero">
      <h1>Malik Tech</h1>
      <p>Your Smart Technology Partner</p>
      <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <section id="about">
    <h2>About Us</h2>
    <p>Malik Tech delivers innovative IT solutions to businesses and individuals. From websites to mobile apps, we turn your ideas into digital reality.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="service-grid">
      <div class="card">🌐 Website Development</div>
      <div class="card">📱 Mobile App Development</div>
      <div class="card">🛒 E-commerce Solutions</div>
      <div class="card">🎨 UI/UX Design</div>
      <div class="card">☁️ Cloud Services</div>
      <div class="card">📢 Digital Marketing</div>
      <div class="card">🔐 Cybersecurity</div>
      <div class="card">📊 Data Analytics</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form onsubmit="return sendMessage();">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Malik Tech. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
