<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Marc Realties Pvt. Ltd.</title>
  <link href="https://fonts.googleapis.com/css2?family=SF+Pro+Display:wght@400;600;700&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      background: #fff;
      color: #333;
      line-height: 1.6;
    }

    header {
      height: 100vh;
      background: url('https://via.placeholder.com/1920x1080?text=Marc+Realties') center/cover no-repeat;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }

    header h1 {
      font-size: 4em;
      color: #fff;
      font-weight: 700;
      text-shadow: 0 3px 10px rgba(0,0,0,0.3);
      margin-bottom: 20px;
    }

    header p {
      font-size: 1.5em;
      color: #eee;
      max-width: 700px;
      text-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }

    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(255, 255, 255, 0.9);
      padding: 15px 0;
      display: flex;
      justify-content: center;
      gap: 30px;
      z-index: 1000;
    }

    nav a {
      text-decoration: none;
      color: #333;
      font-weight: 600;
      font-size: 1em;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #0071e3;
    }

    section {
      padding: 100px 20px;
      max-width: 1100px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      font-size: 2.5em;
      font-weight: 700;
      margin-bottom: 30px;
      color: #111;
    }

    section p {
      text-align: center;
      max-width: 800px;
      margin: auto;
      font-size: 1.2em;
      color: #555;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 40px;
      margin-top: 50px;
    }

    .project-card {
      background: #f9f9f9;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .project-card:hover {
      transform: translateY(-10px);
    }

    .project-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .project-card h3 {
      padding: 20px;
      font-size: 1.5em;
      color: #111;
    }

    .project-card p {
      padding: 0 20px 20px;
      color: #555;
    }

    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 30px 10px;
    }

    .cta {
      margin-top: 50px;
      text-align: center;
    }

    .cta a {
      background: #0071e3;
      color: #fff;
      text-decoration: none;
      padding: 15px 30px;
      border-radius: 50px;
      font-weight: 600;
      transition: background 0.3s;
    }

    .cta a:hover {
      background: #005bb5;
    }
  </style>
</head>
<body>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <header>
    <h1>Marc Realties Pvt. Ltd.</h1>
    <p>Crafting Affordable Homes Today. Creating Luxurious Living for Tomorrow.</p>
  </header>

  <section id="about">
    <h2>About Us</h2>
    <p>Marc Realties Pvt. Ltd. blends innovation with affordability, bringing modern homes to life for the people of Raipur and beyond. With an eye on the future, we’re setting the stage for upscale developments while maintaining our commitment to quality, trust, and timely delivery.</p>
  </section>

  <section id="projects">
    <h2>Our Projects</h2>
    <div class="projects">
      <div class="project-card">
        <img src="https://via.placeholder.com/600x400?text=Heropur+Heights" alt="Heropur Heights">
        <h3>Heropur Heights</h3>
        <p>192 elegant apartments in Heropur, Raipur. Spacious layouts, modern amenities, and prices starting from ₹3000/sqft.</p>
      </div>
      <div class="project-card">
        <img src="https://via.placeholder.com/600x400?text=Raipur+Residency" alt="Raipur Residency">
        <h3>Raipur Residency</h3>
        <p>A modern residential community offering 2BHK and 3BHK configurations, designed for urban lifestyles and future luxury upgrades.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@marcrealties.com</p>
    <p>Phone: +91-XXXXXXXXXX</p>
    <div class="cta">
      <a href="mailto:info@marcrealties.com">Enquire Now</a>
    </div>
  </section>

  <footer>
    &copy; 2025 Marc Realties Pvt. Ltd. All rights reserved.
  </footer>

</body>
</html>
