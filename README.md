<!-- FULL CODE STARTS HERE -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Gen Z Water Campaign - Bringing Clean Water to Communities in Need" />
  <meta name="author" content="Charity Water Gen Z Team" />
  <meta name="keywords" content="clean water, Gen Z, charity, nonprofit, donation, water crisis">
  <title>Gen Z Water Campaign</title>
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

    html {
      scroll-behavior: smooth;
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
      justify-content: space-between;
      align-items: center;
      padding: 1rem 2rem;
      border-bottom: 1px solid #ccc;
      z-index: 999;
    }

    .nav-left img {
      height: 40px;
    }

    .nav-links a {
      color: var(--charcoal);
      text-decoration: none;
      font-weight: bold;
      margin-left: 1rem;
    }

    header.hero {
      background: url('images/heroimage5.jpg') center/cover no-repeat, url('images/background-overlay.jpg') center/cover no-repeat;
      background-blend-mode: overlay;
      color: var(--charcoal);
      text-align: center;
      padding: 5rem 2rem;
      animation: fadeIn 2s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .hero-content {
      background: rgba(255, 255, 255, 0.85);
      display: inline-block;
      padding: 2rem;
      border-radius: 1rem;
      max-width: 600px;
      animation: slideUp 2s ease-in-out;
    }

    @keyframes slideUp {
      from { opacity: 0; transform: translateY(50px); }
      to { opacity: 1; transform: translateY(0); }
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
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    form {
      max-width: 600px;
      margin: 2rem auto;
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
      margin-bottom: 1.2rem;
      border: 1px solid #ccc;
      border-radius: 0.5rem;
    }

    form input[type="email"] {
      background-color: #f9fbff;
      border: 1px solid var(--hope-blue);
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
      nav {
        flex-direction: column;
        align-items: flex-start;
      }

      .nav-links {
        margin-top: 0.5rem;
        display: flex;
        flex-wrap: wrap;
        gap: 0.5rem;
      }

      h1 { font-size: 1.8rem; }
      p { font-size: 1rem; }
      .hero-content { padding: 1.5rem; }
      .impact-cards { flex-direction: column; align-items: center; }
    }
  </style>
</head>
<body>
  <nav>
    <div class="nav-left">
      <img src="images/logoimage.jpg" alt="Charity Water Logo">
    </div>
    <div class="nav-links">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#impact">Impact</a>
      <a href="#donate">Donate</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <header class="hero" id="home">
    <div class="hero-content">
      <h1>Gen Z Leads, Clean Water Succeeds.</h1>
      <p>Clean water heals, protects, and grows. Gen Z makes sure it flows.</p>
      <a href="#donate" class="cta-button">Join Gen Z's Fight for Water Now!</a>
    </div>
  </header>

  <section id="gallery">
    <h2 style="text-align:center; font-size:2rem; margin-bottom:1.5rem;">Our Work in Action</h2>
    <div style="display:flex; flex-wrap:wrap; justify-content:center; gap:1.5rem;">
      <img src="images/heroimage5.jpg" alt="Community clean water effort" style="width:300px; border-radius:1rem; box-shadow:0 2px 10px rgba(0,0,0,0.1);">
      <img src="images/heroimage1.jpg" alt="Youth engaging in water project" style="width:300px; border-radius:1rem; box-shadow:0 2px 10px rgba(0,0,0,0.1);">
      <img src="images/heroimage4.jpg" alt="Celebrating clean water access" style="width:300px; border-radius:1rem; box-shadow:0 2px 10px rgba(0,0,0,0.1);">
    </div>
  </section>

  <section id="donate">
    <h2 style="text-align:center; font-size:2rem; margin-bottom:1.5rem;">Make a Donation</h2>
    <form>
      <label for="name">Full Name</label>
      <input type="text" id="name" name="name" placeholder="Your Name" required />

      <label for="email">Email Address</label>
      <input type="email" id="email" name="email" placeholder="Your Email" required />

      <label for="amount">Donation Amount ($)</label>
      <input type="number" id="amount" name="amount" placeholder="e.g. 50" required />

      <label for="message">Message (Optional)</label>
      <textarea id="message" name="message" placeholder="Your message of support..." rows="4"></textarea>

      <button type="submit">Donate Now</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Gen Z Water Movement. All rights reserved.</p>
  </footer>
</body>
</html>











