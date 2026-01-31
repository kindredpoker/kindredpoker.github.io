
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Smart App Banner (iPhone only) -->
  <meta name="apple-itunes-app" content="app-id=6758220871">

  <title></title> <!-- intentionally empty -->

  <style>
    :root {
      --bg: #ffffff;
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
      padding: 3rem 1.5rem 2.5rem;
      text-align: center;
    }

    header img.logo {
      max-width: 180px;
      margin-bottom: 1rem;
    }

    header p {
      color: var(--muted);
      max-width: 520px;
      margin: 0 auto 1.75rem;
      font-size: 1rem;
      line-height: 1.6;
    }

    .cta-wrapper {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 1rem;
      margin-bottom: 1.5rem;
    }

    .cta {
      padding: 1rem 1.6rem;
      border-radius: 14px;
      background: var(--accent);
      color: #020617;
      font-weight: 700;
      text-decoration: none;
      font-size: 1.1rem;
      transition: transform 0.2s ease, box-shadow 0.2s ease, background 0.3s ease;
      box-shadow: 0 10px 20px rgba(56,189,248,0.35);
    }

    .cta:hover {
      background: #0ea5e9;
      transform: translateY(-2px);
      box-shadow: 0 14px 28px rgba(56,189,248,0.45);
    }

    .app-store-badge img {
      height: 52px;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      flex-wrap: wrap;
    }

    nav a {
      color: var(--muted);
      text-decoration: none;
      font-size: 1rem;
    }

    nav a:hover { color: var(--accent); }

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
      font-size: 1.5rem;
      letter-spacing: -0.01em;
    }

    p, li {
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

    @media (max-width: 600px) {
      .cta { width: 100%; max-width: 320px; }
      nav { flex-direction: column; gap: 0.75rem; }
    }

    /* Dark mode */
    @media (prefers-color-scheme: dark) {
      :root {
        --bg: #111827;
        --card: #1f2937;
        --text: #f9fafb;
        --muted: #9ca3af;
        --accent: #3b82f6;
      }
    }
  </style>
</head>

<body>

<header>
  <img src="Github Logo.png" alt="Kindred Logo" class="logo">

  <p>
    A private community for real connection.
    Built with care, privacy, and intention.
  </p>

  <div class="cta-wrapper">
    <a
      href="https://apps.apple.com/app/id6758220871"
      class="cta"
      target="_blank"
      rel="noopener"
    >
      Download on the App Store
    </a>

    <a
      href="https://apps.apple.com/app/id6758220871"
      class="app-store-badge"
      target="_blank"
      rel="noopener"
    >
      <img
        src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg"
        alt="Download on the App Store"
      >
    </a>
  </div>

  <nav>
    <a href="#privacy">Privacy Policy</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section>
  <div class="card" id="privacy">
    <h2>Privacy Policy</h2>
    <p>Effective date: Jan 1, 2026</p>
    <p>
      Kindred respects your privacy. This app does not collect,
      store, or share any personal user data.
    </p>
    <ul>
      <li>No account creation required</li>
      <li>No tracking or analytics</li>
      <li>No data sold or shared</li>
    </ul>
    <p>This policy will be updated if practices change.</p>
  </div>

  <div class="card" id="contact">
    <h2>Contact Us</h2>
    <p>
      Questions, feedback, or support?
      Reach out anytime:
    </p>
    <p><strong>Email:</strong> kindredpokerteam@gmail.com</p>
  </div>
</section>

<footer>
  &copy; <span id="year"></span> Kindred. All rights reserved.
</footer>

<script>
  document.getElementById("year").textContent = new Date().getFullYear();
</script>

</body>
</html>


