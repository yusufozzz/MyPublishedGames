<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Yusuf Öz - Game Developer Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <!-- Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" 
  integrity="sha512-Fo3rlrZj/k7ujTnH1O2O31HPe5Jw70k8nLRb+Y8afp+zw9SZF1Ly0v7pPQ2duhp1tT6aYp1sFf5F0UwL6rx1Q==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    /* Global Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
      background-color: #fff7f3;
      color: #333;
    }
    a {
      text-decoration: none;
      color: inherit;
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
    }
    /* Header */
    header {
      background: linear-gradient(135deg, #ff6f61, #ff9a9e);
      color: #fff;
      padding: 20px 0;
    }
    header .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      font-size: 1.8rem;
    }
    nav ul {
      list-style: none;
      display: flex;
    }
    nav ul li {
      margin-left: 20px;
    }
    nav ul li a {
      font-weight: bold;
      color: #fff;
      transition: color 0.3s ease;
    }
    nav ul li a:hover {
      color: #ffe0dc;
    }
    /* Hero Section */
    .hero {
      background: linear-gradient(135deg, #fad0c4, #ffd1ff);
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #333;
      padding: 0 20px;
    }
    .hero h2 {
      font-size: 2.8rem;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.2rem;
    }
    /* Section Styles */
    .section {
      padding: 60px 0;
    }
    .section h2 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 2.2rem;
    }
    /* About Section */
    .about p {
      font-size: 1.1rem;
      margin-top: 20px;
      text-align: center;
      max-width: 800px;
      margin-left: auto;
      margin-right: auto;
    }
    /* Games Section */
    .games {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      margin-top: 40px;
    }
    .game {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      flex: 1;
      min-width: 280px;
      max-width: 350px;
      text-align: center;
    }
    .game h3 {
      margin-bottom: 15px;
      font-size: 1.5rem;
    }
    .game p a {
      background: #ff6f61;
      color: #fff;
      padding: 10px 15px;
      border-radius: 4px;
      font-weight: bold;
      transition: background 0.3s ease;
    }
    .game p a:hover {
      background: #e65a50;
    }
    /* Contact Section */
    .contact {
      text-align: center;
      font-size: 1.1rem;
    }
    .contact p {
      margin-bottom: 10px;
    }
    .contact a {
      color: #ff6f61;
      font-weight: bold;
    }
    .contact .icons {
      display: flex;
      justify-content: center;
      gap: 20px;
      font-size: 1.5rem;
      margin-top: 20px;
    }
    .contact .icons a {
      color: #333;
      transition: color 0.3s ease;
    }
    .contact .icons a:hover {
      color: #ff6f61;
    }
    /* Footer */
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 20px 0;
      margin-top: 40px;
    }
    /* Responsive */
    @media (max-width: 768px) {
      header .container {
        flex-direction: column;
      }
      nav ul {
        margin-top: 10px;
      }
    }
  </style>
</head>
<body>
  <!-- Header Section -->
  <header>
    <div class="container">
      <h1>Yusuf Öz</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#games">Games</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h2>5-Year Game Developer</h2>
      <p>Creating immersive gaming experiences with passion and precision.</p>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="section about">
    <div class="container">
      <h2>About Me</h2>
      <p>Hello, I'm Yusuf Öz, a professional game developer with 5 years of experience in the gaming industry. I specialize in Unity development, C# programming, game design, and project management. My goal is to create immersive and engaging games that captivate players worldwide.</p>
    </div>
  </section>

  <!-- Published Games Section -->
  <section id="games" class="section games-section">
    <div class="container">
      <h2>Games</h2>
      <div class="games">
        <div class="game">
          <h3>Lash Salon</h3>
          <p><a href="https://apps.apple.com/us/app/lash-salon/id1602974261" target="_blank">Apple App Store</a></p>
        </div>
        <div class="game">
          <h3>Snake vs Block</h3>
          <p><a href="https://apps.apple.com/us/app/snake-vs-block/id1233739175" target="_blank">Apple App Store</a></p>
        </div>
        <div class="game">
          <h3>Small Business</h3>
          <p><a href="https://play.google.com/store/apps/details?id=com.HalfBite.SmallBusiness" target="_blank">Google Play Store</a></p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section contact">
    <div class="container">
      <h2>Contact</h2>
      <p>If you have any inquiries or opportunities, feel free to reach out.</p>
      <div class="icons">
        <a href="mailto:yusufozjr@gmail.com" title="Email"><i class="fas fa-envelope"></i></a>
        <a href="tel:+905362925089" title="Phone"><i class="fas fa-phone"></i></a>
        <a href="https://www.linkedin.com/in/yusuf-oz/" title="LinkedIn" target="_blank"><i class="fab fa-linkedin"></i></a>
        <a href="https://www.instagram.com/yufisjr/" title="Instagram" target="_blank"><i class="fab fa-instagram"></i></a>
      </div>
    </div>
  </section>

  <!-- Footer Section -->
  <footer>
    <div class="container">
      <p>&copy; 2025 Yusuf Öz. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
