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
/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body
{
  font-family: 'Segoe UI', sans-serif;
  background: #f3f3f3;
  color: #333;
  line-height: 1.6;
  background-color:black;
}

header {
  background: linear-gradient(135deg, #1e90ff, #8a2be2);
  color: #f7f6f6;
  padding: 60px 20px;
  text-align: center;
}

nav {
  margin-top: 20px;
}

nav a {
  color: #fff;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}

nav a:hover {
  color: #ffd700;
}

section {
  padding: 40px 20px;
  max-width: 1000px;
  margin: auto;
}

h2 {
  text-align: center;
  margin-bottom: 20px;
  color: #1e90ff;
}

.service-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.card {
  background: #fff;
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s;
  text-align: center;
  font-size: 1.05rem;
  font-weight: bold;
  color: #444;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
}

form {
  max-width: 500px;
  margin: auto;
  display: flex;
  flex-direction: column;
  gap: 15px;
}

input, textarea {
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 8px;
  font-size: 1rem;
}

button {
  padding: 12px;
  background: #1e90ff;
  color: white;
  border: none;
  border-radius: 8px;
  font-size: 1rem;
  cursor: pointer;
  transition: background 0.3s;
}

button:hover {
  background: #005bb5;
}

footer {
  background: #222;
  color: #fff;
  text-align: center;
  padding: 15px;
}

