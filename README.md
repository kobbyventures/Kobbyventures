<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Kobbys Venture</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    header, footer {
      background: #1e1e1e;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    .hero {
      background: #f4f4f4;
      padding: 2rem;
      text-align: center;
    }
    .hero h1 {
      margin-bottom: 0.5rem;
    }
    .section {
      padding: 2rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .product {
      border: 1px solid #ccc;
      padding: 1rem;
      text-align: center;
      border-radius: 8px;
    }
    .contact-form {
      max-width: 400px;
      margin: auto;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 0.5rem;
      margin: 0.5rem 0;
    }
    @media (max-width: 600px) {
      .section {
        padding: 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Kobbys Venture</h1>
    <p>Quality Used Phones at Affordable Prices</p>
  </header>

  <div class="hero">
    <h2>Find the Best Deals on Used Phones</h2>
    <p>Tested, reliable, and affordable devices</p>
    <button onclick="document.getElementById('contact').scrollIntoView()">Contact Us</button>
  </div>

  <section class="section" id="about">
    <h2>About Us</h2>
    <p>Kobbys Venture is your trusted source for quality used smartphones. We ensure all devices are tested, functional, and offered at competitive prices.</p>
  </section>

  <section class="section" id="products">
    <h2>Featured Products</h2>
    <div class="products">
      <div class="product">
        <h3>iPhone 11</h3>
        <p>64GB - Excellent condition</p>
        <p>$350</p>
      </div>
      <div class="product">
        <h3>Samsung Galaxy S21</h3>
        <p>128GB - Like new</p>
        <p>$400</p>
      </div>
      <div class="product">
        <h3>iPhone XR</h3>
        <p>64GB - Good condition</p>
        <p>$250</p>
      </div>
    </div>
  </section>

  <section class="section" id="why">
    <h2>Why Choose Us?</h2>
    <ul>
      <li>Tested and verified devices</li>
      <li>Affordable prices</li>
      <li>Warranty on select items</li>
      <li>Trusted customer support</li>
    </ul>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <div class="contact-form">
      <input type="text" placeholder="Your Name" />
      <input type="email" placeholder="Your Email" />
      <textarea rows="4" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </div>
    <p>Phone/WhatsApp: +123 456 7890</p>
    <p>Email: kobbysventure@example.com</p>
    <p>Location: Accra, Ghana</p>
  </section>

  <footer>
    <p>© 2025 Kobbys Venture. All rights reserved.</p>
  </footer>
</body>
</html>
