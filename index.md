<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Yusuf Öz - Game Developer Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
  <style>
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

    .container {
      width: 90%;
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 15px;
    }

    /* Header Styles */
    header {
      background-color: #1a1a1a;
      color: #fff;
      padding: 1rem 0;
      width: 100%;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    header .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 1.8rem;
      font-weight: 700;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 2rem;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s ease;
      font-size: 1.1rem;
    }

    nav ul li a:hover {
      color: #00b4d8;
    }

    /* Hero Section */
    .hero {
      background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://via.placeholder.com/1920x400') no-repeat center center/cover;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
    }

    .hero-content {
      max-width: 800px;
    }

    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 1rem;
      text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
    }

    /* Games Section */
    .games-section {
      padding: 3rem 0;
      background: #fff;
    }

    .games {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }

    .game {
      background: #ffffff;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }

    .game:hover {
      transform: translateY(-5px);
    }

    .game h3 {
      font-size: 1.5rem;
      margin: 1rem;
      color: #333;
    }

    /* 
      Burada .game-img default olarak %100 genişlik ve 200px yükseklik veriyordu.
      LashSalon için özel bir stil ekleyeceğiz (inline style).
    */
    .game-img {
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
    }

    .game p {
      padding: 1rem;
    }

    .game a {
      display: inline-block;
      background: #00b4d8;
      color: #fff;
      padding: 0.8rem 1.5rem;
      border-radius: 5px;
      margin: 1rem;
      transition: background 0.3s ease;
      text-decoration: none;
    }

    .game a:hover {
      background: #0077b6;
    }

    /* Contact Section */
    .contact {
      padding: 3rem 0;
      background: #f8f9fa;
    }

    .social-links {
      display: flex;
      justify-content: center;
      gap: 2rem;
      margin-top: 2rem;
    }

    .social-links a {
      color: #333;
      font-size: 2rem;
      transition: color 0.3s ease;
    }

    .social-links a:hover {
      color: #00b4d8;
    }

    .contact-info {
      text-align: center;
      margin-top: 2rem;
    }

    .contact-info p {
      margin: 1rem 0;
      font-size: 1.1rem;
    }

    /* Footer */
    footer {
      background: #1a1a1a;
      color: #fff;
      padding: 1.5rem 0;
      text-align: center;
    }

    /* Section Headers */
    .section-header {
      text-align: center;
      margin-bottom: 2rem;
    }

    .section-header h2 {
      font-size: 2rem;
      color: #333;
      margin-bottom: 0.5rem;
    }

    @media (max-width: 768px) {
      header .container {
        flex-direction: column;
        padding: 1rem;
      }

      nav ul {
        margin-top: 1rem;
        gap: 1rem;
      }

      .hero h2 {
        font-size: 2rem;
      }

      .hero p {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
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

  <section class="hero">
    <div class="hero-content">
      <h2>Game Developer</h2>
      <p>Crafting Immersive Gaming Experiences</p>
    </div>
  </section>

  <section id="about" class="section">
    <div class="container">
      <div class="section-header">
        <h2>About Me</h2>
      </div>
      <p style="text-align: center; max-width: 800px; margin: 0 auto;">
        With 5 years of experience in game development, I specialize in creating engaging mobile games using Unity and C#. My passion lies in crafting experiences that bring joy to players worldwide.
      </p>
    </div>
  </section>

  <section id="games" class="games-section">
    <div class="container">
      <div class="section-header">
        <h2>Featured Games</h2>
      </div>
      <div class="games">
        <!-- Lash Salon -->
        <div class="game">
          <!-- 512x512 boyut için inline style kullandık -->
          <div class="game-img"
               style="width: 512px; 
                      height: 512px; 
                      background-image: url('images/LashSalon.png'); 
                      background-size: cover; 
                      background-position: center; 
                      background-repeat: no-repeat;">
          </div>
          <h3>Lash Salon</h3>
          <p>A beauty salon management simulation game</p>
          <a href="https://apps.apple.com/us/app/lash-salon/id1602974261" target="_blank">
            <i class="fab fa-app-store-ios"></i> App Store
          </a>
        </div>

        <!-- Snake vs Block (örnek olarak eskisi gibi bıraktım) -->
        <div class="game">
          <div class="game-img" style="width: 100%; height: 200px; background-image: url('images/LashSalon.png');"></div>
          <h3>Snake vs Block</h3>
          <p>An addictive arcade game with a unique twist</p>
          <a href="https://apps.apple.com/us/app/snake-vs-block/id1233739175" target="_blank">
            <i class="fab fa-app-store-ios"></i> App Store
          </a>
        </div>

        <!-- Small Business (örnek olarak eskisi gibi bıraktım) -->
        <div class="game">
          <div class="game-img" style="width: 100%; height: 200px; background-image: url('images/LashSalon.png');"></div>
          <h3>Small Business</h3>
          <p>Build and manage your own business empire</p>
          <a href="https://play.google.com/store/apps/details?id=com.HalfBite.SmallBusiness" target="_blank">
            <i class="fab fa-google-play"></i> Play Store
          </a>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <div class="container">
      <div class="section-header">
        <h2>Get in Touch</h2>
      </div>
      <div class="social-links">
        <a href="mailto:yusufozjr@gmail.com" title="Email">
          <i class="fas fa-envelope"></i>
        </a>
        <a href="https://www.linkedin.com/in/yusuf-oz/" target="_blank" title="LinkedIn">
          <i class="fab fa-linkedin"></i>
        </a>
        <a href="https://www.instagram.com/yufisjr/" target="_blank" title="Instagram">
          <i class="fab fa-instagram"></i>
        </a>
        <a href="tel:+905362925089" title="Phone">
          <i class="fas fa-phone"></i>
        </a>
      </div>
      <div class="contact-info">
        <p>I'm always open to new opportunities and collaborations</p>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 Yusuf Öz. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
