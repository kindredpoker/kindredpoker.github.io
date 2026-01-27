
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kindred</title>
  <meta name="description" content="Kindred – A private community for real connection." />
  <style>
    :root {
      --bg: #0f172a;
      --card: #111827;
      --text: #e5e7eb;
      --muted: #9ca3af;
      --accent: #38bdf8;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background: linear-gradient(180deg, #020617, var(--bg));
      color: var(--text);
    }
    header {
      padding: 3rem 1.5rem 2rem;
      text-align: center;
    }
    header h1 {
      font-size: 2.75rem;
      margin-bottom: 0.5rem;
      letter-spacing: -0.02em;
    }
    header p {
      color: var(--muted);
      max-width: 520px;
      margin: 0 auto 1.5rem;
    }
    .cta {
      display: inline-block;
      padding: 0.9rem 1.2rem;
      border-radius: 12px;
      background: var(--accent);
      color: #020617;
      font-weight: 700;
      text-decoration: none;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1.25rem;
      margin-top: 1.25rem;
    }
    nav a {
      color: var(--muted);
      text-decoration: none;
      font-size: 0.95rem;
    }
    section {
      padding: 3rem 1.5rem;
      max-width: 900px;
      margin: 0 auto;
    }
    .card {
      background: rgba(17, 24, 39, 0.85);
      border: 1px solid rgba(255,255,255,0.06);
      border-radius: 18px;
      padding: 2rem;
    }
    h2 {
      margin-top: 0;
      letter-spacing: -0.01em;
    }
    p, li {
      color: var(--muted);
      line-height: 1.6;
    }
    ul { padding-left: 1.2rem; }
    footer {
      padding: 2rem 1.5rem 3rem;
      text-align: center;
      color: var(--muted);
      font-size: 0.85rem;
    }
    .divider { height: 1px; background: rgba(255,255,255,0.06); margin: 3rem 0; }
  </style>
</head>
<body>

    <header>
  <img src="Github Logo.png" style="background:red; padding:10px;">

       style="width:96px;height:auto;margin-bottom:1rem;" />

  <h1>Kindred</h1>
  <p>A private community for real connection. Built with care, privacy, and intention.</p>

    <a class="cta" href="#" aria-label="Download Kindred on the App Store">Download on the App Store</a>
    <nav>
      <a href="#privacy">Privacy Policy</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="privacy">
    <div class="card">
      <h2>Privacy Policy</h2>
      <p><strong>Effective date:</strong> [Add date]</p>
      <p>Kindred respects your privacy. This app does not collect, store, or share any personal user data.</p>
      <ul>
        <li>No account creation required</li>
        <li>No tracking or analytics</li>
        <li>No data sold or shared with third parties</li>
      </ul>
      <p>If this changes in the future, this policy will be updated accordingly.</p>
    </div>
  </section>

  <section id="contact">
    <div class="card">
      <h2>Contact Us</h2>
      <p>If you have questions, feedback, or support requests, reach out anytime:</p>
      <p><strong>Email:</strong> <a href="mailto:kindredpokerteam@gmail.com" style="color: var(--accent);">kindredpokerteam@gmail.com</a></p>
    </div>
  </section>

  <footer>
    © <span id="year"></span> Kindred. All rights reserved.
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>

</body>
</html>
