<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gravity Consultancy Services</title>
  <style>
    body { font-family: 'Segoe UI', Arial, sans-serif; margin:0; padding:0; line-height:1.6; }
    header { background:#1a1a2e; color:#fff; padding:20px; text-align:center; }
    nav a { color:#fff; margin:0 15px; text-decoration:none; font-weight:bold; }
    .hero { background:url('https://source.unsplash.com/1600x600/?laboratory,technology') no-repeat center center/cover; color:#fff; padding:80px 20px; text-align:center; }
    .hero h2 { font-size:2.5em; margin-bottom:20px; }
    .hero button { background:#e94560; color:#fff; border:none; padding:15px 30px; font-size:1em; cursor:pointer; border-radius:5px; }
    .section { padding:60px 20px; max-width:1000px; margin:auto; }
    .section h2 { color:#16213e; margin-bottom:20px; }
    .services { display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:20px; }
    .card { background:#f9f9f9; padding:20px; border-radius:8px; box-shadow:0 2px 5px rgba(0,0,0,0.1); }
    .card h3 { margin-top:0; color:#0f3460; }
    .contact p { margin:8px 0; }
    form { display:flex; flex-direction:column; gap:15px; }
    input, textarea { padding:10px; border:1px solid #ccc; border-radius:5px; font-size:1em; }
    button.submit { background:#0f3460; color:#fff; border:none; padding:12px; cursor:pointer; border-radius:5px; }
    button.submit:hover { background:#e94560; }
    footer { background:#1a1a2e; color:#fff; text-align:center; padding:20px; }
  </style>
</head>
<body>

<header>
  <h1>Gravity Consultancy Services</h1>
  <nav>
    <a href="#about">About Us</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <h2>Your Trusted Partner in Quality Testing & Consultancy</h2>
  <p>Delivering reliable, accurate, and timely results for industries and businesses.</p>
  <button onclick="window.location='#contact'">Request a Quote</button>
</section>

<section id="about" class="section">
  <h2>About Us</h2>
  <p>Gravity Consultancy Services specializes in testing, calibration, and analysis services. 
     We provide expertise in ISO/IEC 17025 and NABL compliance, helping businesses achieve 
     international quality standards with confidence.</p>
</section>

<section id="services" class="section">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">
      <h3>Beer Testing & Analysis</h3>
      <p>Chemical, heavy metal, and microbiology analysis for breweries and food industries.</p>
    </div>
    <div class="card">
      <h3>Calibration Services</h3>
      <p>Mechanical, thermal, electrical, and optical calibration with NABL compliance.</p>
    </div>
    <div class="card">
      <h3>Quality Consultancy</h3>
      <p>Support for NABL accreditation, ISO documentation, and internal audits.</p>
    </div>
    <div class="card">
      <h3>Training Programs</h3>
      <p>Workshops on internal audits, lab management, and quality assurance practices.</p>
    </div>
  </div>
</section>

<section id="contact" class="section contact">
  <h2>Contact Us</h2>
  <p><strong>Address:</strong> Raj Nagar Extension, Ghaziabad, India</p>
  <p><strong>Phone:</strong> <a href="tel:8492906359">8492906359</a></p>
  <p><strong>Email:</strong> <a href="mailto:info.gravityconsultancy@gmail.com">info.gravityconsultancy@gmail.com</a></p>

  <h3>Send us a message</h3>
  <form action="mailto:info.gravityconsultancy@gmail.com" method="post" enctype="text/plain">
    <input type="text" name="name" placeholder="Your Name" required>
    <input type="email" name="email" placeholder="Your Email" required>
    <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
    <button type="submit" class="submit">Submit</button>
  </form>
</section>

<footer>
  <p>© 2026 Gravity Consultancy Services | Privacy Policy | Terms & Conditions</p>
</footer>

</body>
</html>
