<!DOCTYPE html>
<html lang="de-CH">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Helvetic Invest AG – Coming Soon</title>
  <meta name="description" content="Helvetic Invest AG – Schweizer Immobilieninvestments und Projektentwicklung. Neuer Webauftritt folgt in Kuerze. Kontakt: ardin.fatjani@helvetic-invest.ch" />
  <meta name="theme-color" content="#ffffff" />
  <link rel="icon" type="image/png" href="data:image/png;base64,iVBORw0KGgo="> <!-- Fallback tiny icon; real icon injected below via JS -->
  <style>
    :root{
      --bg:#0a0a0a;
      --text:#0f172a; /* slate-900 */
      --muted:#475569; /* slate-600 */
      --brand:#e11d48; /* rose-600 (Logo-rot Anmutung) */
      --card:#ffffff;
      --border:#e5e7eb; /* gray-200 */
      --radius:18px;
    }
    html,body{height:100%}
    body{
      margin:0; font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans", "Apple Color Emoji", "Segoe UI Emoji";
      color:var(--text); background:#fff; -webkit-font-smoothing:antialiased; line-height:1.5;
    }
    .container{width:min(1100px, 92vw); margin-inline:auto}
    header{position:sticky; top:0; z-index:20; backdrop-filter:saturate(180%) blur(8px); background:rgba(255,255,255,.7); border-bottom:1px solid var(--border)}
    .nav{display:flex; align-items:center; justify-content:space-between; padding:14px 0}
    .brand{display:flex; align-items:center; gap:14px; text-decoration:none; color:inherit}
    .brand img{height:38px; width:auto}
    .brand h1{font-size:18px; margin:0; letter-spacing:.04em; font-weight:700; text-transform:uppercase}
    .cta{display:inline-flex; align-items:center; gap:10px; padding:10px 14px; border:1px solid var(--border); border-radius:999px; text-decoration:none; color:var(--text); font-weight:600}
    .cta:hover{border-color:#cbd5e1}

    .hero{position:relative; min-height:72vh; display:grid; place-items:center; overflow:hidden}
    .hero:before{content:""; position:absolute; inset:0; background:url('data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/') center/cover no-repeat; transform:scale(1.03)}
    .hero:after{content:""; position:absolute; inset:0; background:linear-gradient(180deg, rgba(255,255,255,.85) 0%, rgba(255,255,255,.92) 40%, rgba(255,255,255,.98) 100%)}
    .hero-inner{position:relative; z-index:1; width:100%}
    .pill{display:inline-flex; align-items:center; gap:10px; font-size:12px; padding:8px 12px; border:1px solid var(--border); border-radius:999px; background:#fff}
    .pill .dot{width:8px; height:8px; border-radius:50%; background:var(--brand); box-shadow:0 0 0 4px rgba(225,29,72,.12)}
    .headline{margin:14px 0 10px; font-size: clamp(30px, 6vw, 54px); line-height:1.05; letter-spacing:-.02em}
    .sub{font-size: clamp(15px, 2.6vw, 18px); color:var(--muted); max-width:60ch}
    .actions{margin-top:22px; display:flex; gap:12px; flex-wrap:wrap}
    .btn{display:inline-flex; align-items:center; gap:10px; padding:12px 18px; border-radius:12px; font-weight:700; text-decoration:none}
    .btn.primary{background:var(--brand); color:#fff}
    .btn.ghost{border:1px solid var(--border); color:var(--text); background:#fff}

    .cards{display:grid; grid-template-columns:1fr; gap:16px; margin:36px 0}
    @media(min-width:768px){.cards{grid-template-columns:repeat(3,1fr)}}
    .card{background:var(--card); border:1px solid var(--border); border-radius:var(--radius); padding:20px}
    .card h3{margin:4px 0 8px; font-size:16px}
    .card p{margin:0; color:var(--muted)}

    .contact{margin:30px 0 70px; display:grid; grid-template-columns:1fr; gap:18px; align-items:center}
    @media(min-width:900px){.contact{grid-template-columns:1.4fr .6fr}}
    .contact-box{border:1px solid var(--border); border-radius:var(--radius); padding:22px}
    .contact-box h4{margin:0 0 10px; font-size:15px; color:var(--muted)}
    .contact-box a{font-weight:700; font-size:20px; color:var(--text); text-decoration:none}
    .contact-box a:hover{text-decoration:underline}

    footer{border-top:1px solid var(--border); padding:16px 0; color:var(--muted); font-size:13px}

    /* Subtle fade-in */
    [data-animate]{opacity:0; transform:translateY(8px); animation:fadeUp .75s ease forwards;}
    [data-animate].d2{animation-delay:.1s} [data-animate].d3{animation-delay:.2s} [data-animate].d4{animation-delay:.3s}
    @keyframes fadeUp{to{opacity:1; transform:none}}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <a class="brand" href="#" aria-label="Helvetic Invest AG">
        <img id="logo" alt="Helvetic Invest AG Logo" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR42mP8/x8AAwMB/akO0t4AAAAASUVORK5CYII=" />
        <h1>Helvetic Invest AG</h1>
      </a>
      <a class="cta" href="mailto:ardin.fatjani@helvetic-invest.ch" aria-label="E-Mail an Helvetic Invest AG">Kontakt</a>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-inner">
        <span class="pill" data-animate><span class="dot" aria-hidden="true"></span> Neuer Webauftritt in Kuerze</span>
        <h2 class="headline" data-animate class="d2">Schweizer Immobilieninvestments & Projektentwicklung</h2>
        <p class="sub" data-animate class="d3">Wir arbeiten aktuell an einer neuen Online-Praesenz. In der Zwischenzeit sind wir wie gewohnt fuer Sie da und freuen uns auf den Austausch.</p>
        <div class="actions" data-animate class="d4">
          <a class="btn primary" href="mailto:ardin.fatjani@helvetic-invest.ch">Kontakt aufnehmen</a>
          <a class="btn ghost" href="#kontakt">E-Mail kopieren</a>
        </div>
      </div>
    </section>

    <section class="container" aria-label="Kurzinfo">
      <div class="cards">
        <div class="card" data-animate>
          <h3>Investieren mit Substanz</h3>
          <p>Fokus auf nachhaltige, wertstabile Wohn- und Mischimmobilien in der Schweiz.</p>
        </div>
        <div class="card" data-animate class="d2">
          <h3>Ganzheitlicher Ansatz</h3>
          <p>Von der Akquise ueber die Entwicklung bis zur Bewirtschaftung – wir begleiten den gesamten Lebenszyklus.</p>
        </div>
        <div class="card" data-animate class="d3">
          <h3>Partnerschaftlich & Diskret</h3>
          <p>Direkter Zugang zum Management, kurze Entscheidungswege und hoechste Vertraulichkeit.</p>
        </div>
      </div>

      <div id="kontakt" class="contact">
        <div class="contact-box" data-animate>
          <h4>Kontakt</h4>
          <a href="mailto:ardin.fatjani@helvetic-invest.ch">ardin.fatjani@helvetic-invest.ch</a>
        </div>
        <div class="contact-box" data-animate class="d2">
          <h4>Unternehmen</h4>
          <div style="display:flex; align-items:center; gap:12px">
            <img alt="Logo klein" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR42mP8/x8AAwMB/akO0t4AAAAASUVORK5CYII=" style="height:26px"/>
            <strong>Helvetic Invest AG</strong>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      © <span id="year"></span> Helvetic Invest AG · Schweiz
    </div>
  </footer>

  <script>
    // Inject real favicon from logo
    (function(){
      var link = document.querySelector('link[rel="icon"]');
      if(link){ link.href = 'data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR42mP8/x8AAwMB/akO0t4AAAAASUVORK5CYII='; }
      document.getElementById('year').textContent = new Date().getFullYear();
      // Helper: copy email on ghost button
      var ghost = document.querySelector('.btn.ghost');
      ghost.addEventListener('click', function(e){
        e.preventDefault();
        var email = 'ardin.fatjani@helvetic-invest.ch';
        navigator.clipboard.writeText(email).then(function(){
          ghost.textContent = 'E-Mail kopiert';
          setTimeout(function(){ ghost.textContent = 'E-Mail kopieren'; }, 1800);
        });
      });
    })();
  </script>
</body>
</html>
