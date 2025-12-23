<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MOFTECH Solution | Affordable Digital Services</title>
  <style>
    :root{
      --green:#0b3d2e;
      --green-2:#145a32;
      --gold:#ffd700;
      --bg:#f4f7f6;
      --card:#ffffff;
      --text:#1f2937;
    }
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,Arial,Helvetica,sans-serif;background:var(--bg);color:var(--text)}
    a{text-decoration:none;color:inherit}

    /* Header */
    header{background:linear-gradient(135deg,var(--green),var(--green-2));color:#fff}
    .container{max-width:1100px;margin:auto;padding:24px}
    .nav{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .nav-links a{margin-left:16px;font-weight:600}
    .btn{display:inline-block;background:var(--gold);color:#1b1b1b;padding:12px 18px;border-radius:8px;font-weight:700}

    /* Hero */
    .hero{display:grid;grid-template-columns:1.1fr .9fr;gap:24px;align-items:center;padding:40px 0}
    .hero h1{font-size:2.4rem;margin:0 0 12px}
    .hero p{font-size:1.1rem;opacity:.95}
    .hero-card{background:rgba(255,255,255,.08);border-radius:16px;padding:20px}

    /* Sections */
    section{padding:48px 0}
    h2{color:var(--green);margin:0 0 16px}
    .grid{display:grid;gap:20px}
    .grid-3{grid-template-columns:repeat(3,1fr)}
    .grid-4{grid-template-columns:repeat(4,1fr)}
    .card{background:var(--card);border-radius:14px;padding:20px;box-shadow:0 8px 24px rgba(0,0,0,.06)}
    .icon{width:44px;height:44px;border-radius:10px;background:rgba(11,61,46,.08);display:flex;align-items:center;justify-content:center;margin-bottom:10px;font-weight:900;color:var(--green)}

    /* Contact */
    .contact{background:#e9f3ef;border-radius:20px}

    /* Footer */
    footer{background:var(--green);color:#fff}

    /* Responsive */
    @media(max-width:900px){.hero{grid-template-columns:1fr}.grid-3,.grid-4{grid-template-columns:1fr 1fr}}
    @media(max-width:520px){.grid-3,.grid-4{grid-template-columns:1fr}}
  </style>
</head>
<body>

<header>
  <div class="container nav">
    <!-- Inline SVG Logo -->
    <div style="display:flex;align-items:center;gap:12px">
      <svg width="44" height="44" viewBox="0 0 64 64" aria-label="MOFTECH logo">
        <rect x="4" y="8" width="56" height="36" rx="6" fill="#ffffff"/>
        <circle cx="22" cy="26" r="4" fill="#0b3d2e"/>
        <circle cx="32" cy="26" r="4" fill="#0b3d2e"/>
        <circle cx="42" cy="26" r="4" fill="#0b3d2e"/>
        <path d="M20 52h24" stroke="#ffd700" stroke-width="4"/>
        <path d="M32 6c6 0 10 4 10 4" stroke="#ffd700" stroke-width="3" fill="none"/>
      </svg>
      <strong>MOFTECH Solution</strong>
    </div>
    <div class="nav-links">
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#why">Why Us</a>
      <a href="#contact" class="btn">WhatsApp</a>
    </div>
  </div>

  <div class="container hero">
    <div>
      <h1>Affordable Digital Services for Everyone</h1>
      <p>Fast, reliable ICT solutions for students, job seekers, and businesses in Kitengela.</p>
      <a class="btn" href="https://wa.me/254XXXXXXXX">Contact on WhatsApp</a>
    </div>
    <div class="hero-card">
      <h3>Open Today</h3>
      <p>Mon–Fri: 8am–6pm • Sat: 9am–5pm</p>
      <p>📍 Kitengela, Kenya</p>
    </div>
  </div>
</header>

<section id="about">
  <div class="container">
    <h2>About MOFTECH Solution</h2>
    <div class="grid grid-3">
      <div class="card"><div class="icon">👥</div><strong>Who We Are</strong><p>Community-focused digital service enterprise.</p></div>
      <div class="card"><div class="icon">💻</div><strong>What We Do</strong><p>ICT services, online support, and training.</p></div>
      <div class="card"><div class="icon">🎯</div><strong>Our Goal</strong><p>Bridge the digital gap affordably.</p></div>
    </div>
  </div>
</section>

<section id="services">
  <div class="container">
    <h2>Our Services</h2>
    <div class="grid grid-4">
      <div class="card"><div class="icon">🌐</div>Internet & Online Services</div>
      <div class="card"><div class="icon">🖨️</div>Printing, Scanning & Photocopy</div>
      <div class="card"><div class="icon">📄</div>CV Writing & Formatting</div>
      <div class="card"><div class="icon">📧</div>Email & Job Applications</div>
      <div class="card"><div class="icon">🏛️</div>eCitizen & KRA</div>
      <div class="card"><div class="icon">📱</div>Social Media Support</div>
      <div class="card"><div class="icon">🎓</div>Basic Computer Training</div>
      <div class="card"><div class="icon">🤝</div>Digital Consultancy</div>
    </div>
  </div>
</section>

<section id="why">
  <div class="container">
    <h2>Why Choose Us</h2>
    <div class="grid grid-3">
      <div class="card">Affordable pricing</div>
      <div class="card">Fast & reliable service</div>
      <div class="card">Trusted locally</div>
    </div>
  </div>
</section>

<section id="contact">
  <div class="container contact">
    <h2>Contact Us</h2>
    <p><strong>Location:</strong> Kitengela, Kenya</p>
    <p><strong>Phone / WhatsApp:</strong> +254 XXX XXX XXX</p>
    <p><strong>Email:</strong> info@moftechsolution.com</p>
    <a class="btn" href="https://wa.me/254XXXXXXXX">Chat on WhatsApp</a>
  </div>
</section>

<footer>
  <div class="container">
    <p>© 2025 MOFTECH Solution. All Rights Reserved.</p>
  </div>
</footer>

</body>
</html>
