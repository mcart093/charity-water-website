<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Gen Z Water Campaign - Bringing Clean Water to Communities in Need" />
  <meta name="author" content="Charity Water Gen Z Team" />
  <meta name="keywords" content="clean water, Gen Z, charity, nonprofit, donation, water crisis">
  <title>Gen Z Water Campaign</title>
  <link rel="stylesheet" href="style.css">
  <style>
    :root {
      --jerry-yellow: #ffc907;
      --deep-black: #000000;
      --clean-white: #ffffff;
      --hope-blue: #00a6fb;
      --warm-beige: #f5f1e7;
      --sky-blue: #e3f4ff;
      --charcoal: #333333;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: var(--clean-white);
      color: var(--charcoal);
      line-height: 1.6;
    }

    nav {
      position: sticky;
      top: 0;
      background-color: var(--clean-white);
      display: flex;
      justify-content: space-around;
      padding: 1rem;
      border-bottom: 1px solid #ccc;
      z-index: 999;
    }

    nav a {
      color: var(--charcoal);
      text-decoration: none;
      font-weight: bold;
    }

    header.hero {
      background: url('https://i.imgur.com/4AiXzf8.jpeg') center/cover no-repeat;
      background-color: var(--sky-blue);
      background-blend-mode: overlay;
      color: var(--charcoal);
      text-align: center;
      padding: 5rem 2rem;
    }

    .hero-content {
      background: rgba(255, 255, 255, 0.85);
      display: inline-block;
      padding: 2rem;
      border-radius: 1rem;
      max-width: 600px;
    }

    h1, h2 {
      font-size: 2.5rem;
    }

    h3 {
      font-size: 1.8rem;
    }

    p {
      font-size: 1.2rem;
    }

    .cta-button {
      background-color: var(--jerry-yellow);
      color: var(--deep-black);
      padding: 1rem 2rem;
      text-decoration: none;
      font-weight: bold;
      border-radius: 0.5rem;
      display: inline-block;
      margin-top: 1rem;
      transition: background 0.3s;
    }

    .cta-button:hover {
      background-color: #e6b800;
    }

    section {
      padding: 4rem 2rem;
      background-color: var(--warm-beige);
    }

    .impact-cards {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }

    .card {
      background: var(--clean-white);
      padding: 1.5rem;
      border-radius: 1rem;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      max-width: 300px;
      text-align: center;
    }

    form {
      max-width: 600px;
      margin: 0 auto;
      background: var(--clean-white);
      padding: 2rem;
      border-radius: 1rem;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    form label {
      display: block;
      margin-bottom: 0.5rem;
      font-weight: bold;
    }

    form input, form textarea {
      width: 100%;
      padding: 0.75rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 0.5rem;
    }

    form button {
      width: 100%;
      background-color: var(--jerry-yellow);
      color: var(--deep-black);
      padding: 1rem;
      font-size: 1rem;
      font-weight: bold;
      border: none;
      border-radius: 0.5rem;
      cursor: pointer;
      transition: background 0.3s;
    }

    form button:hover {
      background-color: #e6b800;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: var(--hope-blue);
      color: var(--clean-white);
    }

    @media (max-width: 600px) {
      h1 {
        font-size: 1.8rem;
      }
      p {
        font-size: 1rem;
      }
      .hero-content {
        padding: 1.5rem;
      }
      .impact-cards {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#impact">Impact</a>
    <a href="#donate">Donate</a>
    <a href="#contact">Contact</a>
  </nav>

  <header class="hero" id="home">
    <div class="hero-content">
      <h1>Gen Z Leads, Clean Water Succeeds.</h1>
      <p>Clean water heals, protects, and grows. Gen Z makes sure it flows.</p>
      <a href="#donate" class="cta-button">Join Gen Z's Fight for Water Now!</a>
    </div>
  </header>

  <section id="about">
    <h2>About Our Mission</h2>
    <p>We believe clean water is a basic human right. The Gen Z Water Campaign unites students across the world to fund sustainable water projects in underserved communities. Every dollar raised brings us closer to health, education, and hope for all.</p>
  </section>

  <section id="impact">
    <h2>Our Global Impact</h2>
    <div class="impact-cards">
      <div class="card">
        <h3>150+ Projects Funded</h3>
        <p>Across Africa, Asia, and Latin America.</p>
      </div>
      <div class="card">
        <h3>50,000+ Lives Changed</h3>
        <p>Through access to safe drinking water.</p>
      </div>
      <div class="card">
        <h3>100+ Gen Z Teams</h3>
        <p>Mobilized on campuses worldwide.</p>
      </div>
    </div>
  </section>

  <section id="donate">
    <h2>Make a Difference Today</h2>
    <form>
      <label for="name">Full Name</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email Address</label>
      <input type="email" id="email" name="email" required>

      <label for="amount">Donation Amount ($)</label>
      <input type="number" id="amount" name="amount" required min="1" step="any">

      <label for="message">Leave a Message (optional)</label>
      <textarea id="message" name="message" rows="4"></textarea>

      <button type="submit">Donate Now</button>
    </form>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p style="text-align:center; max-width:600px; margin:auto;">Have a question or want to get your school involved? Email us at <a href="mailto:info@genzwater.org">info@genzwater.org</a> and follow us on social media to join the movement.</p>
  </section>

  <footer>
    <p>&copy; 2025 Gen Z Water Movement. All rights reserved.</p>
  </footer>
</body>
</html>
