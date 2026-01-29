<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Figure One Bookkeeping</title>

  <style>
    :root {
      --navy: #0a1f44;
      --blue: #1f6fff;
      --light: #e9f0ff;
      --card: #122b5c;
      --accent: #4da3ff;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', Arial, sans-serif;
      background: linear-gradient(180deg, var(--navy), #07162f);
      color: white;
    }

    header {
      padding: 70px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 3.2em;
      margin: 0;
      color: var(--accent);
      letter-spacing: 1px;
    }

    header p {
      font-size: 1.2em;
      margin-top: 15px;
      color: var(--light);
      max-width: 750px;
      margin-left: auto;
      margin-right: auto;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 15px;
      background-color: rgba(0,0,0,0.25);
      backdrop-filter: blur(6px);
      position: sticky;
      top: 0;
    }

    nav a {
      color: white;
      font-weight: 600;
      text-decoration: none;
    }

    nav a:hover {
      color: var(--accent);
    }

    section {
      max-width: 1000px;
      margin: 0 auto;
      padding: 70px 20px;
    }

    h2 {
      text-align: center;
      color: var(--accent);
      font-size: 2.3em;
      margin-bottom: 40px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }

    .card {
      background-color: var(--card);
      border-radius: 14px;
      padding: 30px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.4);
    }

    .card h3 {
      margin-top: 0;
      color: var(--accent);
    }

    .card p {
      line-height: 1.6;
      color: var(--light);
    }

    ul {
      padding-left: 18px;
    }

    ul li {
      margin: 8px 0;
    }

    .price {
      font-size: 2.2em;
      font-weight: bold;
      color: var(--accent);
    }

    .contact-box {
      background: linear-gradient(135deg, #122b5c, #0b1d3a);
      border-radius: 16px;
      padding: 35px;
      text-align: center;
      box-shadow: 0 15px 40px rgba(0,0,0,0.5);
    }

    footer {
      text-align: center;
      padding: 25px;
      background-color: rgba(0,0,0,0.4);
      font-size: 0.9em;
      color: #cbd8ff;
    }
  </style>
</head>

<body>

<header>
  <h1>Figure One Bookkeeping</h1>
  <p>
    Simple, reliable tracking of income and expenses for individuals and small businesses.
    100% remote-friendly. No bank logins required.
  </p>
</header>

<nav>
  <a href="#services">Services</a>
  <a href="#process">How It Works</a>
  <a href="#pricing">Pricing</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</nav>

<section id="services">
  <h2>What I Do</h2>
  <div class="grid">
    <div class="card">
      <h3>Income Tracking</h3>
      <p>I track all sources of income so you know exactly how much money is coming in each month.</p>
    </div>
    <div class="card">
      <h3>Expense Tracking</h3>
      <p>Your expenses are organized into clear categories so you can see where your money is going.</p>
    </div>
    <div class="card">
      <h3>Monthly Reports</h3>
      <p>You receive a clean, easy-to-read summary of your income and expenses every month.</p>
    </div>
  </div>
</section>

<section id="process">
  <h2>How It Works</h2>
  <div class="card">
    <p>
      At the end of each month, you’ll send me your bank and payment app statements.
      I’ll organize your income and expenses into a clean, shared spreadsheet.
    </p>

    <h3>What You Send</h3>
    <ul>
      <li>Bank statements</li>
      <li>Cash App, Zelle, or PayPal statements</li>
      <li>Credit card statements</li>
    </ul>

    <p>
      Statements can be sent as <strong>PDFs, CSV files, or screenshots</strong>.
      No bank logins are ever required.
    </p>
  </div>
</section>

<section id="pricing">
  <h2>Pricing</h2>
  <div class="grid">
    <div class="card">
      <h3>Month 1 – Setup</h3>
      <div class="price">$50</div>
      <p>
        Initial setup and organization of your income and expenses.
      </p>
    </div>
    <div class="card">
      <h3>Ongoing Monthly Tracking</h3>
      <div class="price">$70 / month</div>
      <p>
        Continued monthly tracking with organized summaries.
      </p>
    </div>
  </div>
</section>

<section id="about">
  <h2>About</h2>
  <div class="card">
    <p>
      My name is <strong>James Cole</strong>, and I run Figure One Bookkeeping.
      I focus exclusively on tracking income and expenses.
      I am not a licensed accountant and do not provide tax filing or financial advisory services.
    </p>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <div class="contact-box">
    <p><strong>Phone:</strong> 737-990-8141</p>
    <p><strong>Email:</strong> FigureOneBookkeeping@gmail.com</p>
    <p><strong>Service Type:</strong> Remote services available</p>
  </div>
</section>

<footer>
  © 2026 Figure One Bookkeeping
</footer>

</body>
</html>
