# alif-cleaning-site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alif Cleaning Services</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #e6f7ff; }
    header { background: #1a8cff; color: white; padding: 20px; text-align: center; }
    nav ul { list-style: none; padding: 0; display: flex; justify-content: center; gap: 20px; }
    nav ul li { display: inline; }
    nav ul li a { color: white; text-decoration: none; font-weight: bold; }
    .hero { display: flex; align-items: center; justify-content: space-around; padding: 40px; background: #ffffff; }
    .hero-text { max-width: 50%; }
    .hero-text h1 { color: #003d66; font-size: 36px; }
    .hero-text p { font-size: 18px; color: #333; }
    .hero-text button { padding: 10px 20px; margin-right: 10px; background: #1a8cff; color: white; border: none; cursor: pointer; border-radius: 5px; }
    .hero-img img { max-width: 300px; border-radius: 10px; }
    .section { padding: 40px; text-align: center; }
    .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; }
    .service-box { background: #f2fbff; padding: 20px; border-radius: 10px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); color: #003d66; font-weight: bold; }
    footer { background: #003d66; color: white; text-align: center; padding: 20px; }
    .social-links a { color: white; margin: 0 10px; text-decoration: none; }
  </style>
</head>
<body>
  <header>
    <h1>Alif Cleaning Services</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#join">Join Us</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-text">
      <h1>Professional Cleaning Services</h1>
      <p>Trusted, Efficient & Affordable Solutions for Homes and Offices</p>
      <button>Book Now</button>
      <button>Explore Services</button>
    </div>
    <div class="hero-img">
      <img src="https://via.placeholder.com/300x300" alt="Cleaning Service">
    </div>
  </section>

  <section id="services" class="section">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service-box">House Cleaning</div>
      <div class="service-box">Office Cleaning</div>
      <div class="service-box">Commercial Cleaning</div>
      <div class="service-box">Deep Cleaning</div>
      <div class="service-box">Special Occasion Cleaning</div>
    </div>
  </section>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>Alif Cleaning Services is a reliable name in residential and commercial cleaning. With a dedicated team and eco-friendly methods, we ensure your space is spotless and safe.</p>
  </section>

  <section id="join" class="section">
    <h2>Join Our Team</h2>
    <p>Looking for a rewarding job in cleaning services? Join Alif Cleaning Services today!</p>
    <button>Apply Now</button>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Email: zahidhasandc96@gmail.com | Phone & WhatsApp: +971 552301807</p>
    <p>Location: Dubai, UAE</p>
    <p>
      <a href="https://wa.me/971552301807" target="_blank">Chat on WhatsApp</a> |
      <a href="https://www.facebook.com/profile.php?id=61573053465835" target="_blank">Visit our Facebook Page</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Alif Cleaning Services. All rights reserved.</p>
    <div class="social-links">
      <a href="https://wa.me/971552301807" target="_blank">WhatsApp</a>
      |
      <a href="https://www.facebook.com/profile.php?id=61573053465835" target="_blank">Facebook</a>
    </div>
  </footer>
</body>
</html>
