<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CaseVault | Medical Case Study Archive</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f8fb;
      color: #2c3e50;
    }
    header {
      background-color: #0077b6;
      color: white;
      padding: 1rem 2rem;
      text-align: center;
    }
    nav {
      background-color: #023e8a;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      padding: 2rem;
    }
    .card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      padding: 1.5rem;
      margin-bottom: 2rem;
    }
    footer {
      background-color: #0077b6;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 4rem;
    }
    .contact-form label {
      display: block;
      margin-top: 1rem;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 0.5rem;
      border: 1px solid #ccc;
      border-radius: 8px;
      margin-top: 0.5rem;
    }
    .contact-form button {
      margin-top: 1rem;
      padding: 0.7rem 2rem;
      background-color: #023e8a;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>CaseVault</h1>
    <p>A Curated Medical Case Study Archive</p>
  </header>
  <nav>
    <a href="#">Home</a>
    <a href="#cases">Case Studies</a>
    <a href="#contact">Contact</a>
  </nav>
  <div class="container">
    <section id="cases">
      <h2>Featured Case Studies</h2>
      <div class="card">
        <h3>Type 2 Diabetes in a 52-Year-Old Male</h3>
        <p>A classic presentation involving metabolic syndrome, newly diagnosed T2DM, and lifestyle management challenges.</p>
        <a href="case1.html">Read more</a>
      </div>
      <div class="card">
        <h3>Obesity and Metabolic Syndrome in a 50-Year-Old Woman</h3>
        <p>Multifactorial case of obesity, fatty liver, and degenerative joint disease complicating routine care.</p>
        <a href="case2.html">Read more</a>
      </div>
    </section>
    <section id="contact">
      <h2>Contact</h2>
      <div class="card contact-form">
        <p>Reach out for collaborations, questions, or to share your own cases.</p>
        <form>
          <label for="name">Name</label>
          <input type="text" id="name" name="name" required><label for="email">Email</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Message</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <button type="submit">Send</button>
    </form>
    <p><strong>Email:</strong> <a href="mailto:thurinlinn140@gmail.com">thurinlinn140@gmail.com</a></p>
    <p><strong>Phone:</strong> <a href="tel:+959652977448">+959652977448</a></p>
    <p><strong>TikTok:</strong> <a href="https://tiktok.com/@TachyTalk" target="_blank">@TachyTalk</a></p>
  </div>
</section>

  </div>
  <footer>
    <p>&copy; 2025 CaseVault by Rahaam. All rights reserved.</p>
  </footer>
</body>
</html>
