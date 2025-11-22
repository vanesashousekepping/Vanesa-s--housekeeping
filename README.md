[housekeeping_site (1).html](https://github.com/user-attachments/files/23685881/housekeeping_site.1.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Vanesa's Housekeeping</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f8f8f8;
      color: #333;
    }
    header {
      background: #ff69b4;
      color: white;
      padding: 30px;
      text-align: center;
    }
    nav {
      background: #fff;
      padding: 15px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #ff69b4;
      font-weight: bold;
    }
    .hero {
      padding: 60px 20px;
      text-align: center;
      background: #ffe4f1;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #ff69b4;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <div style="display:flex; flex-direction:column; align-items:center;">
      <div style="font-size:3rem; font-weight:bold; color:white; text-shadow:2px 2px #c0487c;">
        🧼 Vanesa's Housekeeping
      </div>
      <p>Reliable • Affordable • Professional</p>
      <p>Call/Text: <strong>760-844-8773</strong></p>
    </div>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
    <a href="#quote" style="background:#ff69b4; color:white; padding:8px 15px; border-radius:8px;">Get a Quote</a>
  </nav>

  <section class="hero">
    <img src="https://images.unsplash.com/photo-1581579188871-45ea61f2a0c8?auto=format&fit=crop&w=800&q=80" alt="Cleaning Photo" style="width:100%; max-width:600px; border-radius:15px; margin-bottom:20px;" />
    <h1>Your Home, Clean & Fresh</h1>
    <p>We take care of the cleaning so you can enjoy your day.</p>
  </section>

  <section id="services" class="section">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>Standard Cleaning</h3>
        <p>Dusting, mopping, vacuuming, and basic home cleanup.</p>
      </div>
      <div class="card">
        <h3>Deep Cleaning</h3>
        <p>Detailed cleaning for kitchens, bathrooms, and full home refresh.</p>
      </div>
      <div class="card">
        <h3>Move-In / Move-Out</h3>
        <p>Perfect for new homes or preparing to hand over keys.</p>
      </div>
      <div class="card">
        <h3>Custom Services</h3>
        <p>Tell us what you need and we’ll make it happen.</p>
      </div>
    </div>
  </section>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>Vanesa's Housekeeping provides top‑quality cleaning services with attention to detail and care. With years of experience, we bring professionalism and a personal touch to every home.</p>
  </section>

  <section id="quote" class="section">
    <h2>Get a Quote</h2>
    <p>Click below to request a free custom quote:</p>
    <a href="#contact" style="background:#ff69b4; color:white; padding:12px 20px; border-radius:10px; text-decoration:none; font-size:1.1rem;">Request Quote</a>
  </section>

  <section id="booking" class="section">
    <h2>Online Booking Calendar</h2>
    <p>Choose a date and time that works best for you:</p>

    <div style="margin:auto; max-width:600px; position:relative;">
      <iframe src="https://calendly.com/vanesashousekeeping/cleaning" width="100%" height="700" style="border:none; border-radius:15px;"></iframe>
      <a href="#booking" style="position:absolute; top:10px; right:10px; background:#ff69b4; color:white; padding:10px 20px; border-radius:8px; text-decoration:none; font-weight:bold;">Book Now</a>
    </div>
    <p style="margin-top:10px; font-style:italic; color:green;">After booking, you will receive a confirmation email with your appointment details.</p>
  </section>

  <section id="contact"" class="section">
    <h2>Contact</h2>
    <p>Ready to book? Fill out the form below:</p>

    <form style="background:white; padding:20px; border-radius:10px; box-shadow:0 2px 5px rgba(0,0,0,0.1); max-width:500px; margin:auto;">
      <label>Name</label><br>
      <input type="text" style="width:100%; padding:10px; margin:5px 0 15px;" required><br>

      <label>Phone</label><br>
      <input type="text" style="width:100%; padding:10px; margin:5px 0 15px;" required><br>

      <label>Service Needed</label><br>
      <select style="width:100%; padding:10px; margin:5px 0 15px;">
        <option>Standard Cleaning</option>
        <option>Deep Cleaning</option>
        <option>Move-In / Move-Out</option>
        <option>Custom Service</option>
      </select><br>

      <label>Message</label><br>
      <textarea style="width:100%; padding:10px; margin:5px 0 15px; height:100px;"></textarea><br>

      <button type="submit" style="background:#ff69b4; color:white; padding:12px 20px; border:none; border-radius:8px; font-size:1rem; cursor:pointer; width:100%;">Submit Booking</button>
    </form>
    <br>
    <p><strong>Phone:</strong> 760-844-8773 or 760-609-7140</p>
    <p><strong>Email:</strong> vanesashousekeeping@yahoo.com</p>
  </section>

  <section id="areas" class="section">
    <h2>Service Areas</h2>
    <p>We proudly serve the following locations:</p>
    <ul>
      <li>📍 Indio</li>
      <li>📍 Coachella</li>
      <li>📍 La Quinta</li>
      <li>📍 Palm Desert</li>
      <li>📍 Palm Springs</li>
      <li>📍 Thermal</li>
      <li>📍 Mecca</li>
      <li>📍 Cathedral City</li>
    </ul>

    <h3>Service Area Map</h3><img width="1024" height="1536" alt="6d4b38ec-86fe-440c-ad63-6bc81537a404" src="https://github.com/user-attachments/assets/2356e581-631d-4b9c-9594-ecd2eae70036" />

    <iframe src="https://www.google.com/maps/d/embed?mid=1mZrGQd6u0lC0Jw6z29pX9T0nC3U&ehbc=2E312F" width="100%" height="400" style="border-radius:15px; border:none;"></iframe>
  </section>

  <footer>
    <p>📞 <strong>Phone:</strong> 760-844-8773 • 760-609-7140</p>
    <p>📧 <strong>Email:</strong> vanesashousekeeping@yahoo.com</p>
    <p>📍 Serving Indio • Coachella • La Quinta • Palm Desert • Palm Springs • Thermal • Mecca • Cathedral City</p>
    <p>© 2025 Vanesa's Housekeeping. All rights reserved.</p>
  </footer>
</body>
</html>
