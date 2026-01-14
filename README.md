<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Al-Wadaq | About - شركة الودق</title>
  <meta name="description" content="About Al-Wadaq Wallpaper Manufacturing Co. Ltd in Babel, Iraq." />
  <link rel="stylesheet" href="assets/css/style.css" />
</head>
<body>
  <a class="skip-link" href="#main">Skip to content</a>

  <header class="nav">
    <div class="container">
      <div class="navbar">
        <a class="brand" href="index.html" aria-label="Al-Wadaq"><img src="assets/img/logo.svg" alt="Al-Wadaq logo" /><span class="brand-text"><strong>Al-Wadaq</strong><span data-i18n="city">Babel, Iraq</span></span></a>
        <button id="menuBtn" class="btn menu-btn" type="button">Menu</button>

        <nav id="navLinks" class="links">
          <a class="link" data-nav href="index.html" data-i18n="nav_home">Home</a>
          <a class="link" data-nav href="about.html" data-i18n="nav_about">About</a>
          <a class="link" data-nav href="products.html" data-i18n="nav_products">Products</a>
          <a class="link" data-nav href="contact.html" data-i18n="nav_contact">Contact</a>
          <a class="link" data-nav href="auth.html" data-i18n="nav_auth">Account</a>
          <a class="link" data-nav href="visualizer.html" data-i18n="viz_badge">Visualizer</a>
        </nav>

        <div class="nav-actions">
          <button id="langBtn" class="btn" type="button">English</button>
          <div id="sessionSlot"></div>
          <a class="btn primary" href="contact.html" data-i18n="home_cta_quote">Request a Quote</a>
        </div>
      </div>
    </div>
  </header>

  <main id="main">
    <section class="section">
      <div class="container grid" style="grid-template-columns:1.1fr .9fr; align-items:start;">
        <div class="card">
          <span class="badge" data-i18n="about_badge">About</span>
          <h1 style="margin-top:10px;" data-i18n="about_title">Local manufacturing with dependable quality and stable supply.</h1>
          <p style="color:var(--muted);" data-i18n="about_p">
            Al-Wadaq Wallpaper Manufacturing Co. Ltd operates in Babel Province, Iraq...
          </p>

          <div class="hr"></div>

          <h2 style="margin:0 0 10px;" data-i18n="about_vision_t">Our Vision</h2>
          <p style="color:var(--muted);margin-top:0;" data-i18n="about_vision_p">
            To be Iraq’s leading locally manufactured wallpaper brand...
          </p>

          <h2 style="margin:18px 0 10px;" data-i18n="about_values_t">Our Values</h2>
          <ul style="color:var(--muted);margin:0; padding-inline-start:18px;">
            <li data-i18n="about_val1">Quality and operational discipline.</li>
            <li data-i18n="about_val2">Specification and order transparency.</li>
            <li data-i18n="about_val3">Innovation in design and materials.</li>
            <li data-i18n="about_val4">Customer service and supply partnerships.</li>
          </ul>
        </div>

        <div class="card">
          <h2 style="margin-top:0;" data-i18n="contact_info_title">Company Details</h2>
          <div class="small" style="margin-top:10px;">
            <div><strong data-i18n="address_label">Address</strong>: <span data-i18n="city">Babel, Iraq</span></div>
            <div style="margin-top:6px;"><strong data-i18n="phone_label">Phone</strong>: +964 7XX XXX XXXX</div>
            <div><strong data-i18n="email_label">Email</strong>: info@alwadaq-wallpaper.com</div>
          </div>

          <div class="hr"></div>

          <div class="notice">
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container">
      <div class="row">
        <div>
          <div class="brand" style="margin-bottom:8px;"><img src="assets/img/logo.svg" alt="Al-Wadaq logo" /><span class="brand-text"><strong>Al-Wadaq</strong><span data-i18n="city">Babel, Iraq</span></span></div>
          <div class="small" data-i18n="footer_tagline">Al-Wadaq Wallpaper Manufacturing Co. Ltd — Babel, Iraq</div>
        </div>
        <div class="small">© <span id="year"></span> Al-Wadaq — <span data-i18n="footer_rights">All rights reserved</span></div>
      </div>
    </div>
  </footer>

  <div id="toast" class="toast" role="status" aria-live="polite"></div>
  <script src="assets/js/i18n.js"></script>
  <script type="module" src="assets/js/main.js"></script>
</body>
</html>
