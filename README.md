# StayWell-Guardian
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>StayWell Guardian – Smart Health Tools</title>
  <meta name="description" content="Trusted health tech for Nigerian families. Honest reviews. No hype.">
  
  <!-- Minimal, fast-loading styles -->
  <style>
    :root {
      --gold: #d4af37;
      --gold-light: #f9f3d0;
      --text: #1a1a1a;
      --muted: #666;
      --bg: #fafafa;
      --card-border: #eee;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
      min-height: 100vh;
    }
    .container { width: 90%; max-width: 1200px; margin: 0 auto; }
    header { text-align: center; padding: 2rem 0; }
    h1 { font-size: 2rem; margin-bottom: 1rem; }
    @media (min-width: 768px) { h1 { font-size: 2.5rem; } }

    .intro {
      text-align: center;
      max-width: 700px;
      margin: 0 auto 3rem;
      color: var(--muted);
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
      margin-bottom: 3rem;
    }

    .card {
      border: 2px solid var(--card-border);
      border-radius: 12px;
      overflow: hidden;
      transition: all 0.3s ease;
    }
    .card:hover {
      border-color: var(--gold);
      box-shadow: 0 4px 12px rgba(212, 175, 55, 0.2);
    }

    .image-placeholder {
      height: 160px;
      background: #f0f0f0;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #999;
      font-size: 0.8rem;
    }

    .card-content {
      padding: 1.25rem;
    }
    .card-title { font-weight: bold; font-size: 1.1rem; margin-bottom: 0.5rem; }
    .card-price { font-size: 1.4rem; font-weight: bold; color: var(--gold); margin: 0.5rem 0; }
    .card-desc { font-size: 0.9rem; color: var(--muted); margin: 0.75rem 0; }
    .card-hook { font-style: italic; font-weight: 600; font-size: 0.9rem; color: #222; }

    .btn {
      display: block;
      width: 100%;
      background: var(--gold);
      color: white;
      text-align: center;
      padding: 0.75rem;
      border-radius: 8px;
      font-weight: bold;
      text-decoration: none;
      margin-top: 1rem;
      transition: opacity 0.2s;
    }
    .btn:hover { opacity: 0.9; }

    .trust-box {
      background: var(--gold-light);
      border: 1px solid var(--gold);
      border-radius: 16px;
      padding: 2rem;
      text-align: center;
      max-width: 800px;
      margin: 0 auto 3rem;
    }
    .trust-box h3 { font-size: 1.5rem; margin-bottom: 1rem; }

    footer {
      text-align: center;
      padding: 2rem 0;
      font-size: 0.85rem;
      color: var(--muted);
      border-top: 1px solid #eee;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>🛒 Smart Health Tools We Recommend</h1>
    </header>

    <div class="intro">
      <p>These tech-powered tools help you track your health better — so you know what to do first.</p>
      <p style="margin-top: 0.5rem; font-size: 0.85rem;">
        When you buy through our links, you help us keep StayWell Guardian free for everyone.<br>
        (No extra cost to you.)
      </p>
    </div>

    <div class="grid">
      <!-- Product 1 -->
      <div class="card">
        <div class="image-placeholder">Image: Oura Ring Gen4</div>
        <div class="card-content">
          <div class="card-title">Oura Ring Gen4 – Sleep & Recovery Tracker</div>
          <div class="card-price">$299</div>
          <p class="card-desc">Tracks deep sleep, heart rate, body temperature — perfect for students and workers who feel tired all the time.</p>
          <p class="card-hook">"Sleep is your superpower. Measure it."</p>
          <a href="https://www.amazon.com/dp/B0FFMPGRWF?tag=valuevibes0d-20" target="_blank" rel="noopener noreferrer" class="btn">👉 Get on Amazon</a>
        </div>
      </div>

      <!-- Product 2 -->
      <div class="card">
        <div class="image-placeholder">Image: Fitbit Charge 6</div>
        <div class="card-content">
          <div class="card-title">Fitbit Charge 6 – Fitness & Heart Rate Tracker</div>
          <div class="card-price">$159</div>
          <p class="card-desc">Tracks steps, sleep, exercise, and stress — great for staying active and preventing burnout.</p>
          <p class="card-hook">"Your personal health coach on your wrist."</p>
          <a href="https://www.amazon.com/dp/B0CC62ZG1M?tag=valuevibes0d-20" target="_blank" rel="noopener noreferrer" class="btn">👉 Get on Amazon</a>
        </div>
      </div>

      <!-- Product 3 -->
      <div class="card">
        <div class="image-placeholder">Image: Blood Pressure Monitor</div>
        <div class="card-content">
          <div class="card-title">Automatic Upper Arm Blood Pressure Monitor</div>
          <div class="card-price">$49</div>
          <p class="card-desc">Accurate home device for checking pressure — ideal for parents and elders managing hypertension.</p>
          <p class="card-hook">"Check pressure at home. Prevent stroke."</p>
          <a href="https://www.amazon.com/dp/B0DKF33SP2?tag=valuevibes0d-20" target="_blank" rel="noopener noreferrer" class="btn">👉 Get on Amazon</a>
        </div>
      </div>

      <!-- Product 4 -->
      <div class="card">
        <div class="image-placeholder">Image: Xiaomi Smart Band 8</div>
        <div class="card-content">
          <div class="card-title">Xiaomi Smart Band 8 – Fitness & Sleep Tracker</div>
          <div class="card-price">$49</div>
          <p class="card-desc">Affordable fitness tracker with heart rate, sleep, and step monitoring — perfect for young Nigerians.</p>
          <p class="card-hook">"Fitness starts here — for less than ₦10,000."</p>
          <a href="https://www.amazon.com/dp/B0BYVZQ7XF?tag=valuevibes0d-20" target="_blank" rel="noopener noreferrer" class="btn">👉 Get on Amazon</a>
        </div>
      </div>
    </div>

    <div class="trust-box">
      <h3>💬 Why Trust These Picks?</h3>
      <p>We only recommend products that are accurate, useful, and trusted globally.</p>
      <p><strong>No fake gadgets. No hype.</strong></p>
      <p>And every purchase helps fund our mission to protect Nigerian families.</p>
    </div>
  </div>

  <footer>
    <div class="container">
      <p>© 2024 StayWell Guardian. Built with ❤️ for Nigerian families.</p>
      <p style="margin-top: 0.5rem;">This is educational information only. Not medical advice. Always see a doctor when needed.</p>
    </div>
  </footer>
</body>
</html>
