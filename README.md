<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Muditha Bathiya — About</title>
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --muted:#9aa4b2;
      --accent:#60a5fa;
      --glass: rgba(255,255,255,0.03);
      --radius:12px;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }

    body{
      margin:0;
      min-height:100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      background:linear-gradient(180deg, #071029 0%, #0b1220 100%);
      color:#e6eef6;
      padding:32px;
    }

    .card{
      max-width:1000px;
      width:100%;
      display:grid;
      grid-template-columns: 320px 1fr;
      gap:28px;
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:var(--radius);
      padding:28px;
      box-shadow: 0 8px 30px rgba(2,6,23,0.7);
      align-items:start;
    }

    .avatar {
      background:var(--glass);
      border-radius:12px;
      padding:18px;
      display:flex;
      flex-direction:column;
      gap:12px;
      align-items:center;
      text-align:center;
    }

    .avatar img{
      width:120px;
      height:120px;
      object-fit:cover;
      border-radius:50%;
      border:2px solid rgba(255,255,255,0.06);
      background:linear-gradient(90deg, rgba(255,255,255,0.03), rgba(255,255,255,0.01));
    }

    h1{ margin:0; font-size:20px; }
    p.lead{ margin:0; color:var(--muted); font-size:14px; }

    .cta {
      margin-top:6px;
      display:flex;
      gap:8px;
      flex-wrap:wrap;
    }

    .btn {
      background:transparent;
      border:1px solid rgba(255,255,255,0.06);
      color:inherit;
      padding:8px 12px;
      border-radius:8px;
      text-decoration:none;
      font-size:13px;
    }

    .content{
      padding:6px 4px;
    }

    .section{
      margin-bottom:18px;
      background:rgba(255,255,255,0.01);
      padding:12px;
      border-radius:10px;
    }

    .section h2{
      margin:0 0 8px 0;
      font-size:16px;
      color:#fff;
    }

    .badges { display:flex; flex-wrap:wrap; gap:8px; }
    .badge {
      background:rgba(255,255,255,0.03);
      padding:8px 10px;
      border-radius:8px;
      font-size:13px;
      color:var(--muted);
      border:1px solid rgba(255,255,255,0.02);
    }

    .skills-grid{
      display:grid;
      grid-template-columns:repeat(auto-fit, minmax(160px,1fr));
      gap:8px;
    }

    footer.note { color:var(--muted); font-size:13px; margin-top:6px; }

    @media (max-width:820px){
      .card{ grid-template-columns: 1fr; padding:20px; }
      .avatar{ flex-direction:row; gap:14px; align-items:center; justify-content:flex-start; }
      .avatar img{ width:84px; height:84px; }
    }
  </style>
</head>
<body>
  <main class="card" role="main" aria-labelledby="name-heading">
    <aside class="avatar" aria-label="profile">
      <img src="https://via.placeholder.com/240" alt="Muditha Bathiya — profile photo">
      <div>
        <h1 id="name-heading">Muditha Bathiya</h1>
        <p class="lead">IT Professional · Full-Stack Web Developer</p>
        <div class="cta">
          <a class="btn" href="#" aria-label="View portfolio">Portfolio</a>
          <a class="btn" href="#" aria-label="Contact me">Contact</a>
        </div>
      </div>
    </aside>

    <section class="content" aria-label="About">
      <div class="section">
        <h2>About</h2>
        <p>
          I combine deep infrastructure expertise with full-stack web development to deliver end-to-end digital solutions. I manage networks, troubleshoot systems, and build modern web platforms that are both reliable and visually polished.
        </p>
      </div>

      <div class="section" aria-labelledby="skills-title">
        <h2 id="skills-title">Key Skills</h2>
        <div class="badges">
          <span class="badge">Network & System Admin</span>
          <span class="badge">Hardware Troubleshooting</span>
          <span class="badge">IT Asset Management</span>
          <span class="badge">HTML • CSS • JavaScript</span>
          <span class="badge">PHP • Python • C# • Java</span>
          <span class="badge">MySQL</span>
          <span class="badge">WordPress • Shopify • WooCommerce</span>
          <span class="badge">Photoshop • Illustrator</span>
        </div>
      </div>

      <div class="section" aria-labelledby="approach-title">
        <h2 id="approach-title">Approach</h2>
        <p>
          I deliver solutions that balance technical stability and user experience. I enjoy collaborating with stakeholders and designers to produce high-quality, maintainable systems.
        </p>
        <footer class="note">Available for freelance & full-time opportunities. Email: your.email@example.com</footer>
      </div>
    </section>
  </main>
</body>
</html>
