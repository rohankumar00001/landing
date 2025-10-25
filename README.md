
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Clothify - Clothing Brand</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      line-height: 1.6;
      color: #333;
      background: #f8f9fa;
    }

    /* Navbar */
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: black;
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 50px;
      z-index: 1000;
    }
    nav h2 {
      font-size: 1.5rem;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }
    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: 500;
    }
    nav ul li a:hover {
      color: #f04e23;
    }

    /* Hero Section */
    header {
      background: url('https://images.unsplash.com/photo-1521336575821-5f9636e71f1a') center/cover no-repeat;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: gray;
      padding: 0 20px;
    }
    header h1 {
      font-size: 3rem;
      letter-spacing: 2px;
    }
    header p {
      margin: 15px 0;
      font-size: 1.2rem;
    }
    header a {
      padding: 12px 25px;
      background: black;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 20px;
      transition: 0.3s;
    }
    header a:hover {
      background: #f04e23;
    }

    /* Section Common */
    section {
      padding: 80px 20px;
      max-width: 1100px;
      margin: auto;
    }

    /* About */
    .about {
      text-align: center;
    }
    .about img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 3px solid #f04e23;
      object-fit: cover;
      object-position: 60% 20%; /* Centered image */
      display: block;
      margin: 0 auto 20px;
    }
    .about h2 {
      margin-bottom: 15px;
      font-size: 2rem;
    }
    .about p {
      font-size: 1.1rem;
      max-width: 700px;
      margin: auto;
    }

    /* Projects */
    .projects .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .projects .card {
      background: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0px 3px 8px rgba(0,0,0,0.1);
      text-align: center;
      transition: 0.3s;
    }
    .projects .card:hover {
      transform: scale(1.05);
    }
    .projects img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 10px;
    }

    /* Contact */
    .contact {
      text-align: center;
    }
    .contact a {
      color: #f04e23;
      font-weight: bold;
      text-decoration: none;
    }

    /* Footer */
    footer {
      background: black;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav>
    <h2>GRIZLEE</h2>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#projects">Collections</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Hero / Landing -->
  <header>
    <h1>Welcome to My Portfolio & Brand</h1>
    <p>Hi, I'm <strong>Prashant kumar bhatt</strong> 👋 | Fashion Enthusiast & Web Developer</p>
    <a href="#about">Know More</a>
  </header>

  <!-- About -->
  <section id="about" class="about">
    <img src="WhatsApp Image 2025-09-29 at 19.25.58_914bad90.jpg" alt="My Photo">
    <h2>About Me</h2>
    <p>
      Hello! I am <strong>Prashant kumar bhatt</strong>, passionate about web development and fashion design. 
      I run a clothing brand that blends modern trends with comfort. Alongside, I also create digital 
      solutions and websites. This portfolio showcases both my personal journey and my brand.
    </p>
  </section>

  <!-- Projects / Collections -->
  <section id="projects" class="projects">
    <h2>My Latest Work & Collections</h2>
    <div class="grid">
      <div class="card">
        <img src="https://campussutra.com/cdn/shop/files/CSMAWJK7006_1_16f4dfdc-6977-4c0c-94b2-b7d3d587be07.jpg?v=1728547931" alt="Jacket">
        <h3>Winter Jackets</h3>
      </div>
      <div class="card">
        <img src="https://www.altart.in/cdn/shop/files/ArtistQuoteOversizedt-ShirtForMenModel4.png?v=1755527146" alt="T-Shirt">
        <h3>Graphic Tees</h3>
      </div>
      <div class="card">
        <img src="https://rukminim2.flixcart.com/image/480/640/xif0q/shoe/7/d/4/6-195-40-asteroid-black-original-imah7byzffjfevkg.jpeg?q=90" alt="Sneakers">
        <h3>Sneakers</h3>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:prashant@gmail.com">prashant@gmail.com</a></p>
    <p>Phone: +91 9875400000</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 MyBrand | Designed by Prashant</p>
  </footer>

</body>
</html>
# landing
