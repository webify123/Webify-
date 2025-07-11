# Webify-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Webify</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Open+Sans&display=swap');

  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  body {
    font-family: 'Open Sans', sans-serif;
    background: linear-gradient(135deg, #1c1b18 0%, #d9cbb3 100%);
    color: #2a2a23;
    min-height: 100vh;
    line-height: 1.7;
    letter-spacing: 0.02em;
  }

  header {
    text-align: center;
    padding: 140px 20px 100px;
    color: #f5f1e7;
    font-family: 'Playfair Display', serif;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.6);
  }

  header h1 {
    font-size: 6rem;
    font-weight: 700;
    letter-spacing: 0.1em;
    margin-bottom: 15px;
  }

  header p {
    font-size: 1.8rem;
    font-weight: 400;
    max-width: 700px;
    margin: 0 auto;
    font-style: italic;
    color: #d4c9b6;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
  }

  main {
    max-width: 1100px;
    margin: -80px auto 60px;
    background: #f5f1e7;
    padding: 80px 60px;
    border-radius: 20px;
    box-shadow: 0 15px 50px rgba(0,0,0,0.3);
  }

  section {
    margin-bottom: 100px;
  }

  h2 {
    font-family: 'Playfair Display', serif;
    font-size: 3.6rem;
    font-weight: 700;
    color: #3b352a;
    border-bottom: 3px solid #a57c3c;
    padding-bottom: 14px;
    margin-bottom: 40px;
    letter-spacing: 0.06em;
  }

  p, ul {
    font-size: 1.3rem;
    color: #5a5446;
    max-width: 850px;
    margin-bottom: 25px;
  }

  ul.services-list {
    list-style-type: disc;
    padding-left: 30px;
    color: #6a614d;
  }

  ul.services-list li {
    margin-bottom: 18px;
  }

  .portfolio-list {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(320px,1fr));
    gap: 32px;
    max-width: 1000px;
    margin: 0 auto;
  }

  .portfolio-item {
    background: #d9cbb3;
    border-radius: 15px;
    padding: 28px 30px;
    box-shadow: 0 8px 25px rgba(165,124,60,0.3);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .portfolio-item:hover {
    transform: translateY(-10px);
    box-shadow: 0 18px 45px rgba(165,124,60,0.5);
  }

  .portfolio-item h3 {
    font-family: 'Playfair Display', serif;
    font-size: 1.9rem;
    color: #3b352a;
    margin-bottom: 14px;
  }

  .portfolio-item p {
    font-size: 1.15rem;
    color: #5a5446;
  }

  .contact-section {
    text-align: center;
  }

  .contact-link {
    display: inline-block;
    border: 3px solid #a57c3c;
    color: #3b352a;
    padding: 18px 50px;
    font-size: 1.6rem;
    font-weight: 700;
    border-radius: 40px;
    background: transparent;
    cursor: pointer;
    transition: background 0.3s ease, color 0.3s ease, box-shadow 0.3s ease;
    text-decoration: none;
    user-select: none;
    box-shadow: 0 0 0 transparent;
  }

  .contact-link:hover {
    background: #a57c3c;
    color: #f5f1e7;
    box-shadow: 0 0 15px #a57c3c;
  }

  footer {
    text-align: center;
    padding: 28px 15px;
    font-size: 1rem;
    color: #5a5446;
    letter-spacing: 0.06em;
  }

  @media (max-width: 720px) {
    header h1 {
      font-size: 3.8rem;
    }
    header p {
      font-size: 1.3rem;
      max-width: 90%;
    }
    main {
      margin: -60px 15px 40px;
      padding: 50px 25px;
    }
    h2 {
      font-size: 2.8rem;
      margin-bottom: 30px;
    }
    p, ul.services-list {
      font-size: 1.1rem;
    }
    .contact-link {
      font-size: 1.3rem;
      padding: 14px 35px;
    }
  }
</style>
</head>
<body>
  <header>
    <h1>WEBIFY</h1>
    <p>Elevate your online presence with timeless, elegant web design</p>
  </header>

  <main>
    <section id="about">
      <h2>About Us</h2>
      <p>Webify was founded with a single vision: to make luxury-quality websites accessible to passionate entrepreneurs, creatives, and small businesses who want to stand out. Our team blends old-world aesthetics with modern strategy to deliver stunning, memorable online experiences.</p>
      <p>We don’t just build websites — we craft brand identities. From concept to launch, every detail is refined with care and intention.</p>
    </section>

    <section id="services">
      <h2>Our Services</h2>
      <ul class="services-list">
        <li>Bespoke website design tailored to your brand</li>
        <li>Elegant landing pages and digital portfolios</li>
        <li>Smooth e-commerce experiences with clean, secure checkout</li>
        <li>Blog and content platforms optimized for engagement</li>
        <li>Search engine optimization (SEO) for higher visibility</li>
        <li>Fast turnaround times and ongoing support</li>
      </ul>
    </section>

    <section id="why-webify">
      <h2>Why Choose Webify?</h2>
      <p>The national average cost for a professionally designed website ranges from <strong>$1,000 to $10,000+</strong>. At Webify, we believe you deserve that level of quality — without the elite pricing.</p>
      <p>Our rates are deliberately lower than industry standards, with no shortcuts in quality, presentation, or performance. We serve individuals and businesses who want luxury-level design at smart, sustainable rates.</p>
      <ul class="services-list">
        <li>Save thousands without compromising on class or clarity</li>
        <li>Designed to help you convert, impress, and grow</li>
        <li>Perfect for launching, scaling, or rebranding</li>
      </ul>
    </section>

    <section id="portfolio">
      <h2>Portfolio</h2>
      <div class="portfolio-list">
        <div class="portfolio-item">
          <h3>Rose & Grind Café</h3>
          <p>A vintage-inspired site for a boutique café with elegant script fonts, menu highlights, and reservations.</p>
        </div>
        <div class="portfolio-item">
          <h3>Maison Élan Boutique</h3>
          <p>Luxury online store with minimalist product pages, high-end branding, and a seamless checkout flow.</p>
        </div>
        <div class="portfolio-item">
          <h3>Julien Avery Studio</h3>
          <p>Artist portfolio with layered visuals, embedded video, and an “old money” gallery feel that captivates.</p>
        </div>
      </div>
    </section>

    <section id="contact" class="contact-section">
      <h2>For Inquiries</h2>
      <p><a href="mailto:DGwebcrafted@gmail.com" class="contact-link">Contact Us</a></p>
    </section>
  </main>

  <footer>
    &copy; 2025 Webify. All rights reserved.
  </footer>
</body>
</html>
