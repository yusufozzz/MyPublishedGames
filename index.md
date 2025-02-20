<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Yusuf Öz - Game Developer Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
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
      background-color: #f4f4f4;
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
      background-color: #333;
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
      color: #00b4d8;
    }
    /* Hero Section */
    .hero {
      background: url('https://via.placeholder.com/1200x600') no-repeat center center/cover;
      height: 10vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
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
      background: #00b4d8;
      color: #fff;
      padding: 10px 15px;
      border-radius: 4px;
      font-weight: bold;
      transition: background 0.3s ease;
    }
    .game p a:hover {
      background: #0077b6;
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
      color: #00b4d8;
      font-weight: bold;
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
          <li><a href="#games">My Published Games</a></li>
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
      <h2>My Published Games</h2>
      <div class="games">
        <div class="game">
          <h3>Lash Salon</h3>
          <p><a href="https://apps.apple.com/us/app/lash-salon/id1602974261" target="_blank">Download on Apple App Store</a></p>
        </div>
        <div class="game">
          <h3>Snake vs Block</h3>
          <p><a href="https://apps.apple.com/us/app/snake-vs-block/id1233739175" target="_blank">Download on Apple App Store</a></p>
        </div>
        <div class="game">
          <h3>Small Business</h3>
          <p><a href="https://play.google.com/store/apps/details?id=com.HalfBite.SmallBusiness" target="_blank">Download on Google Play Store</a></p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section contact">
    <div class="container">
      <h2>Contact</h2>
      <p>If you have any inquiries or opportunities, please feel free to reach out.</p>
      <p>Email: <a href="mailto:yusufozjr@gmail.com">yusufozjr@gmail.com</a></p>
      <p>Phone: <a href="tel:+905362925089">+905362925089</a></p>
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
