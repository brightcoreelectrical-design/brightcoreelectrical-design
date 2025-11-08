<!-- Enhanced single-file bundle: home + about for Brightcore Electrical
     Save as: brightcore-enahnced.html and split into two pages if desired.
     Notes: replace placeholder images in /assets/images/, update contact details as needed.
--><!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Brightcore Electrical — Powering Safer Homes</title>
  <meta name="description" content="Brightcore Electrical — certified electricians offering residential, commercial and solar installations across Pretoria. Fast callouts and safety-first workmanship.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{--brand:#0b66ff;--accent:#ffb020;--muted:#6b7280;--bg:#f7f9fb;--card:#ffffff}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial;color:#0f1724;background:var(--bg)}
    .wrap{max-width:1100px;margin:0 auto;padding:1rem}
    header.site-header{background:#fff;box-shadow:0 2px 8px rgba(12,16,20,0.04);position:sticky;top:0;z-index:50}
    .site-header .wrap{display:flex;align-items:center;justify-content:space-between;padding:0.75rem 1rem}
    .brand{font-weight:700;color:var(--brand);margin:0;font-size:1.1rem}
    nav.main-nav{display:flex;gap:1rem}
    nav.main-nav a{color:var(--muted);text-decoration:none;padding:0.5rem;border-radius:6px}
    nav.main-nav a:hover{background:rgba(11,102,255,0.05);color:var(--brand)}
    /* Mobile nav */
    .menu-toggle{display:none;border:0;background:transparent}/* HERO */
.hero{display:grid;grid-template-columns:1fr 420px;gap:1.5rem;align-items:center;padding:2.2rem 0}
.hero-left h1{margin:0 0 0.6rem;font-size:1.6rem;color:#06102a}
.lead{color:var(--muted);margin:0 0 1rem}
.actions{display:flex;gap:0.75rem}
.btn{display:inline-flex;align-items:center;gap:0.5rem;padding:0.6rem 0.9rem;border-radius:8px;text-decoration:none;font-weight:600}
.btn.primary{background:var(--brand);color:#fff}
.btn.secondary{background:#f1f5f9;color:var(--brand)}
.hero-right{background:linear-gradient(180deg, rgba(11,102,255,0.06), rgba(255,176,32,0.04));padding:1rem;border-radius:12px;display:flex;justify-content:center;align-items:center}
.hero-image{width:100%;height:320px;object-fit:cover;border-radius:8px;max-width:420px}

/* features */
.features{display:grid;grid-template-columns:repeat(3,1fr);gap:1rem;margin:1.5rem 0}
.card{background:var(--card);padding:1rem;border-radius:10px;box-shadow:0 6px 18px rgba(12,16,20,0.06)}
.card h4{margin:0 0 0.5rem}
ul.clean{list-style:none;padding:0;margin:0;display:flex;flex-direction:column;gap:0.5rem}

/* contact snippet */
.contact-snippet{display:flex;gap:1rem;align-items:center;margin-top:1rem}
.contact-snippet a{color:var(--brand);font-weight:600}

footer.site-footer{padding:1rem 0;color:var(--muted);text-align:center;margin-top:2rem}

/* Floating action buttons */
.fab-group{position:fixed;right:18px;bottom:18px;display:flex;flex-direction:column;gap:0.6rem;z-index:60}
.fab{display:inline-flex;align-items:center;justify-content:center;width:48px;height:48px;border-radius:50%;box-shadow:0 6px 14px rgba(8,12,20,0.12);background:var(--brand);color:#fff;text-decoration:none}
.fab.whatsapp{background:#25D366}
.fab.email{background:#6b7280}

/* Responsive */
@media (max-width:900px){
  .hero{grid-template-columns:1fr;gap:1rem}
  .features{grid-template-columns:repeat(2,1fr)}
  nav.main-nav{display:none}
  .menu-toggle{display:inline-block}
}
@media (max-width:520px){
  .features{grid-template-columns:1fr}
  .hero-right{padding:0}
  .hero-image{height:200px}
}

/* Utilities */
.muted{color:var(--muted)}
.kicker{font-size:0.82rem;color:var(--accent);font-weight:700}

  </style>
</head>
<body>
  <header class="site-header">
    <div class="wrap">
      <div style="display:flex;align-items:center;gap:1rem">
        <a href="index.html" style="text-decoration:none"><div class="brand">Brightcore Electrical</div></a>
      </div>
      <nav>
        <button class="menu-toggle" aria-expanded="false" aria-controls="mainnav">Menu</button>
        <div id="mainnav" class="main-nav">
          <a href="#home">Home</a>
          <a href="#about">About</a>
          <a href="#services">Services</a>
          <a href="#gallery">Gallery</a>
          <a href="#contact">Contact</a>
        </div>
      </nav>
    </div>
  </header>  <main class="wrap" id="home">
    <section class="hero" aria-labelledby="hero-heading">
      <div class="hero-left">
        <div class="kicker">Certified electricians • Fast callouts</div>
        <h1 id="hero-heading">Fast. Safe. Reliable electrical work for homes and businesses.</h1>
        <p class="lead">From wiring and inspections to solar installations. We follow industry standards and provide clear, itemised quotes. Book a free site visit.</p>
        <p class="actions">
          <a class="btn primary" href="tel:+27722063340">Call 072 206 3340</a>
          <a class="btn secondary" href="https://wa.me/27722063340?text=Hello%20Brightcore%20Electrical%2C%20I%20need%20a%20quote" target="_blank">WhatsApp us</a>
        </p>
        <div style="margin-top:1rem;display:flex;gap:1rem;align-items:center">
          <div class="card" style="display:flex;gap:1rem;align-items:center;flex:1">
            <div style="min-width:44px;height:44px;border-radius:8px;background:#eef2ff;display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--brand)">✓</div>
            <div>
              <div style="font-weight:700">Safety first</div>
              <div class="muted" style="font-size:0.95rem">SANS-compliant inspections and certificates</div>
            </div>
          </div>
          <div class="card" style="display:flex;gap:1rem;align-items:center;flex:1">
            <div style="min-width:44px;height:44px;border-radius:8px;background:#fff7ed;display:flex;align-items:center;justify-content:center;font-weight:700;color:var(--accent)">⚡</div>
            <div>
              <div style="font-weight:700">Solar-ready</div>
              <div class="muted" style="font-size:0.95rem">Design and maintain hybrid systems</div>
            </div>
          </div>
        </div>
      </div><div class="hero-right" aria-hidden="false">
    <img src="assets/images/hero-solar-install.jpg" alt="Electrician installing solar panels" class="hero-image">
  </div>
</section>

<section id="services" class="features">
  <div class="card">
    <h4>Residential services</h4>
    <ul class="clean">
      <li>Full house rewiring</li>
      <li>RCDs, consumer units and fault finding</li>
      <li>Lighting upgrades and LED retrofits</li>
    </ul>
  </div>
  <div class="card">
    <h4>Commercial & industrial</h4>
    <ul class="clean">
      <li>New installations and maintenance contracts</li>
      <li>Safety audits and compliance certificates</li>
      <li>Planned maintenance for businesses</li>
    </ul>
  </div>
  <div class="card">
    <h4>Solar & energy</h4>
    <ul class="clean">
      <li>Site assessments and ROI estimates</li>
      <li>Inverter and battery integration</li>
      <li>Commissioning and ongoing maintenance</li>
    </ul>
  </div>
</section>

<section class="contact-snippet" id="contact">
  <div style="flex:1">
    <h3>Contact</h3>
    <p class="muted">Phone</p>
    <p><a href="tel:+27722063340">072 206 3340</a></p>
    <p class="muted">Email</p>
    <p><a href="mailto:brightcoreelectrical@gmail.com">brightcoreelectrical@gmail.com</a></p>
  </div>
  <div style="min-width:220px">
    <div class="card">
      <h4>Request a quote</h4>
      <p class="muted" style="margin-top:0.25rem">Send a short description via WhatsApp and we will respond within one business day.</p>
      <p style="margin-top:0.75rem"><a class="btn primary" href="https://wa.me/27722063340?text=Quote%20request%20-%20I%20need%20an%20electrical%20estimate" target="_blank">Message on WhatsApp</a></p>
    </div>
  </div>
</section>

<footer class="site-footer">
  <div>&copy; 2025 Brightcore Electrical. Registered electricians. All rights reserved.</div>
</footer>

<!-- Floating action buttons -->
<div class="fab-group" aria-hidden="false">
  <a class="fab call" href="tel:+27722063340" title="Call Brightcore">☎</a>
  <a class="fab whatsapp" href="https://wa.me/27722063340?text=Hello%20Brightcore%20Electrical%2C%20I%20need%20a%20quote" target="_blank" title="WhatsApp Brightcore">💬</a>
  <a class="fab email" href="mailto:brightcoreelectrical@gmail.com" title="Email Brightcore">✉</a>
</div>

  </main>  <!-- About section as a separate semantic fragment for quick split into about.html -->  <!-- Keep this in the same file while iterating. Remove if splitting pages. -->  <main class="wrap" id="about" style="margin-top:2rem">
    <section class="card">
      <h2>About Brightcore Electrical</h2>
      <p class="muted">Local, certified electricians focused on safety, transparency and long-term value.</p>
      <h3>Our mission</h3>
      <p>To deliver reliable electrical services that meet regulatory standards and protect customers’ property and people.</p>
      <h3>Our vision</h3>
      <p>To be the trusted electrical partner for homeowners and businesses across our region.</p>
      <h3>Why clients choose us</h3>
      <ul class="clean">
        <li>Transparent, itemised quotes</li>
        <li>SANS compliant certificates</li>
        <li>Experienced technicians and documented workmanship</li>
      </ul>
    </section>
  </main>  <script>
    // small mobile menu toggle
    const toggle = document.querySelector('.menu-toggle');
    const nav = document.getElementById('mainnav');
    if(toggle){
      toggle.addEventListener('click',()=>{
        const expanded = toggle.getAttribute('aria-expanded') === 'true';
        toggle.setAttribute('aria-expanded', String(!expanded));
        nav.style.display = expanded ? 'none' : 'block';
      });
    }
  </script></body>
</html>
