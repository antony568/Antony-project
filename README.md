<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Antony High School</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f2f2f2;
    }
    header {
      background: #003366;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #0059b3;
      overflow: hidden;
    }
    nav a {
      float: left;
      display: block;
      color: white;
      text-align: center;
      padding: 14px 20px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #003366;
    }
    section {
      padding: 20px;
    }
    .card {
      background: white;
      margin: 15px 0;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background: #003366;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 30px;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
    }
    form button {
      background: #0059b3;
      color: white;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
    }
    form button:hover {
      background: #004080;
    }
  </style>
</head>
<body>

<header>
  <h1>Antony High School</h1>
  <p>Inspiring Excellence and Leadership</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#subjects">Subjects</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</nav>

<section id="home">
  <div class="card">
    <h2>Welcome to Antony High School!</h2>
    <p>We provide quality education and empower our students for a bright future.</p>
    <img src="https://via.placeholder.com/600x200?text=School+Banner" style="width:100%; border-radius:8px;">
  </div>
</section>

<section id="subjects">
  <div class="card">
    <h2>Subjects Offered</h2>
    <ul>
      <li>Mathematics</li>
      <li>English</li>
      <li>Biology</li>
      <li>Chemistry</li>
      <li>Physics</li>
      <li>History</li>
      <li>Geography</li>
      <li>Computer Studies</li>
    </ul>
  </div>
</section>

<section id="about">
  <div class="card">
    <h2>About Us</h2>
    <p>Founded in 2005, Antony High School has grown into one of the top performing schools in the region. We focus on academics, discipline, talent development, and digital learning.</p>
  </div>
</section>

<section id="contact">
  <div class="card">
    <h2>Contact Us</h2>
    <form>
      <label>Name:</label>
      <input type="text" placeholder="Your name" required>
      <label>Email:</label>
      <input type="email" placeholder="Your email" required>
      <label>Message:</label>
      <textarea placeholder="Write your message..." rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>
</section>

<footer>
  <p>&copy; 2025 Antony High School. All rights reserved.</p>
</footer>

</body>
</html>
