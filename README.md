
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title> <!-- Empty so no browser tab title shows -->
  <style>
    :root {
      --bg: rgb(25,25,25);
      --card: #f9f9f9;
      --text: #111827;
      --muted: #6b7280;
      --accent: #38bdf8;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background-color: var(--bg);
      color: var(--text);
    }

    header {
      padding: 3rem 1.5rem 2rem;
      text-align: center;
    }

    header img {
      max-width: 120px;
      margin-bottom: 1rem;

      margin-left: auto;
      margin-right: auto;
    }

    header p {
      color: var(--muted);
      max-width: 520px;
      margin: 0 auto 1.5rem;
      font-size: 1rem;
      line-height: 1.6;
    }

    .cta {
      display: inline-block;
      padding: 1rem 1.5rem;
      border-radius: 12px;
      background: var(--accent);
      color: #020617;
      font-weight: 700;
      text-decoration: none;
      font-size: 1.1rem;
      transition: background 0.3s ease;
    }

    .cta:hover {
      background: #0ea5e9;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      margin-top: 1.5rem;
      flex-wrap: wrap;
    }

    nav a {
      color: var(--muted);
      text-decoration: none; /* removes blue underline */
      font-size: 1rem;
      padding: 0.5rem 0;
    }

    nav a:hover {
      color: var(--accent);
    }

    section {
      padding: 3rem 1.5rem;
      max-width: 900px;
      margin: 0 auto;
    }

    .card {
      background: var(--card);
      border: 1px solid #e5e7eb;
      border-radius: 18px;
      padding: 2rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
      margin-bottom: 2rem;
    }

    h2 {
      margin-top: 0;
      letter-spacing: -0.01em;
      font-size: 1.5rem;
    }

    p, li {
      color: var(--text); /* dark text */
      line-height: 1.6;
      font-size: 1rem;
    }

    ul { padding-left: 1.2rem; }

    footer {
      padding: 2rem 1.5rem 3rem;
      text-align: center;
      color: var(--muted);
      font-size: 0.85rem;
    }

    .divider { height: 1px; background: #e5e7eb; margin: 3rem 0; }

    @media (max-width: 600px) {
      header p { font-size: 0.95rem; }
      .cta { width: 100%; text-align: center; padding: 1rem; font-size: 1.05rem; }
      section { padding: 2rem 1rem; }
      nav { flex-direction: column; gap: 0.75rem; }
      nav a { font-size: 0.95rem; }
      .card { padding: 1.5rem; }
      h2 { font-size: 1.35rem; }
      p, li { font-size: 0.95rem; }
    }
  </style>
</head>
<body>

<header>
  <img src="Github Logo.png" alt="Kindred Logo">
  <p>A private community for real connection. Built with care, privacy, and intention.</p>
  <a href="#" class="cta">Download on the App Store</a>

  <nav>
    <a href="#">Privacy Policy</a>
    <a href="#">Contact</a>
  </nav>
</header>

<section>
  <div class="card">
    <h2>Privacy Policy</h2>
    <p>Effective date: Jan 1st, 2026</p>
    <p>Kindred respects your privacy. This app does not collect, store, or share any personal user data.</p>
    <ul>
      <li>No account creation required</li>
      <li>No tracking or analytics</li>
      <li>No data sold or shared with third parties</li>
    </ul>
    <p>If this changes in the future, this policy will be updated accordingly.</p>
  </div>

  <div class="card">
    <h2>Contact Us</h2>
    <p>If you have questions, feedback, or support requests, reach out anytime:</p>
    <p>Email: kindredpokerteam@gmail.com</p>
  </div>
</section>

<footer>
  &copy; <span id="year"></span> Kindred. All rights reserved.
</footer>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();
</script>

</body>


