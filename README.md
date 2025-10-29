<!doctype html>
<html lang="az">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Tunar Cəfərli — IT Mütəxəssisi</title>
  <meta name="description" content="Tunar Cəfərli — IT mütəxəssisi portfolio səhifəsi. Frontend, backend, DevOps, və daha çox." />
  <style>
    :root{
      --blue-900:#012A4A;
      --blue-700:#0366A6;
      --blue-500:#0B84FF;
      --muted:#667085;
      --glass: rgba(255,255,255,0.06);
      --card: rgba(255,255,255,0.03);
      --radius:14px;
      --max-width:1100px;
      --fw-medium:600;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; background: linear-gradient(180deg,var(--blue-900) 0%, #001f3f 100%); color:#EAF2FF; -webkit-font-smoothing:antialiased;}
    a{color:inherit;text-decoration:none}
    .container{width:94%;max-width:var(--max-width);margin:0 auto;padding:28px 0}

    /* Header */
    header{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--blue-700),var(--blue-500));display:flex;align-items:center;justify-content:center;font-weight:800;color:white;font-size:20px;flex-shrink:0}
    nav{display:flex;gap:18px;align-items:center}
    .nav-link{padding:8px 12px;border-radius:10px;font-weight:500;color:rgba(234,242,255,0.9)}
    .nav-link:hover{background:rgba(255,255,255,0.04)}
    .cta{background:linear-gradient(90deg,var(--blue-500),var(--blue-700));padding:10px 14px;border-radius:12px;font-weight:700;color:white}

    /* Hero */
    .hero{display:grid;grid-template-columns:1fr 420px;gap:30px;align-items:center;padding:40px 0}
    .hero-card{background:linear-gradient(180deg,rgba(255,255,255,0.03),rgba(255,255,255,0.02));padding:28px;border-radius:var(--radius);box-shadow:0 6px 30px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03)}
    .title{font-size:28px;margin:0 0 8px;line-height:1.05}
    .subtitle{color:var(--muted);margin:0 0 18px}
    .badges{display:flex;gap:8px;flex-wrap:wrap}
    .badge{background:rgba(255,255,255,0.03);padding:8px 10px;border-radius:999px;font-weight:600}

    /* Profile box */
    .profile{display:flex;flex-direction:column;gap:12px;align-items:center}
    .avatar{width:100%;max-width:320px;border-radius:16px;overflow:hidden;border:2px solid rgba(255,255,255,0.04);background:linear-gradient(135deg,var(--blue-700),var(--blue-500));display:flex;align-items:center;justify-content:center;padding:26px}
    .avatar svg{width:140px;height:140px;opacity:0.95}
    .contact{display:flex;gap:8px;flex-wrap:wrap;justify-content:center}
    .chip{background:var(--card);padding:8px 12px;border-radius:999px;font-weight:600;color:#EAF2FF}

    /* Sections */
    section{margin-top:26px}
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .card{background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(255,255,255,0.01));padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    h3{margin:0 0 10px}
    p{margin:0;color:var(--muted);line-height:1.5}

    /* Footer */
    footer{padding:28px 0;color:var(--muted);text-align:center}

    /* Responsive */
    @media (max-width:980px){
      .hero{grid-template-columns:1fr;}
      .grid-3{grid-template-columns:repeat(2,1fr)}
    }
    @media (max-width:600px){
      header{padding-bottom:8px}
      nav{display:none}
      .hero{gap:18px}
      .grid-3{grid-template-columns:1fr}
      .title{font-size:22px}
    }

    /* Utility */
    .muted{color:var(--muted)}
    .skills{display:flex;gap:8px;flex-wrap:wrap}
    .skill{background:rgba(255,255,255,0.03);padding:7px 10px;border-radius:8px;font-weight:600}

    /* small text fit helpers to ensure "yazılar tam düşür" */
    .fit{word-wrap:break-word;overflow-wrap:break-word}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">TC</div>
        <div>
          <div style="font-weight:800">Tunar Cəfərli</div>
          <div style="font-size:13px;color:var(--muted);margin-top:2px">Gələcəkdə IT mütəxəssisi</div>
        </div>
      </div>

      <nav aria-label="Əsas menyu">
        <a class="nav-link" href="#about">Haqqımda</a>
        <a class="nav-link" href="#skills">Bacarıqlar</a>
        <a class="nav-link" href="#work">Layihələr</a>
        <a class="nav-link" href="#contact">Əlaqə</a>
        <a class="cta" href="#contact">Əlaqə saxla</a>
      </nav>
    </header>

    <main>
      <section class="hero">
        <div class="hero-card">
          <h1 class="title">Salam, mən <span style="color:var(--blue-500)">Tunar Cəfərli</span><br/><small style="font-weight:600;color:var(--muted);font-size:15px">— gələcək IT mütəxəssisi</small></h1>
          <p class="subtitle fit">Mən öyrənməyə və praktiki layihələr yaratmağa böyük həvəsli gəncəm. Frontend, backend, və infrastruktur üzrə biliklər qazanmaq istəyirəm. Bu səhifə mənim portfolio və əlaqə nöqtəmdir.</p>

          <div style="margin-top:18px" class="badges">
            <div class="badge">HTML</div>
            <div class="badge">CSS</div>
            <div class="badge">JavaScript</div>
            <div class="badge">Git</div>
            <div class="badge">Linux</div>
          </div>

          <div style="margin-top:22px;display:flex;gap:10px;flex-wrap:wrap">
            <a class="cta" href="#work">Layihələrə bax</a>
            <a class="nav-link" href="#contact">CV yüklə</a>
          </div>
        </div>

        <aside class="profile">
          <div class="avatar">
            <!-- Simple SVG avatar placeholder -->
            <svg viewBox="0 0 120 120" xmlns="http://www.w3.org/2000/svg" aria-hidden>
              <defs>
                <linearGradient id="g" x1="0" x2="1">
                  <stop offset="0" stop-color="#0B84FF"/>
                  <stop offset="1" stop-color="#0366A6"/>
                </linearGradient>
              </defs>
              <rect width="120" height="120" rx="18" fill="url(#g)" />
              <g transform="translate(18,18)" fill="#fff" opacity="0.95">
                <circle cx="42" cy="34" r="20" />
                <rect x="6" y="72" width="72" height="22" rx="8" />
              </g>
            </svg>
          </div>

          <div class="contact">
            <div class="chip">Bakı, Azərbaycan</div>
            <div class="chip">tunar@example.com</div>
            <div class="chip">+994 XX XXX XX XX</div>
          </div>
        </aside>
      </section>

      <section id="about" class="hero-card" style="margin-top:18px">
        <h3>Haqqımda</h3>
        <p class="fit">Mənim məqsədim güclü texniki bacarıqlarla həm frontend, həm backend layihələrində iştirak etməkdir. Hal-hazırda HTML, CSS və JavaScript üzərində təməl biliklər üzərində işləyirəm və Git, Linux ilə tanışam. Gələcəkdə DevOps və bulud xidmətlərində ixtisaslaşmaq istəyirəm.</p>
      </section>

      <section id="skills" style="margin-top:18px">
        <h3>Bacarıqlar</h3>
        <div class="grid-3" style="margin-top:12px">
          <div class="card">
            <h4>Frontend</h4>
            <p class="muted">HTML, CSS, JavaScript, responsive dizayn, Bootstrap/
