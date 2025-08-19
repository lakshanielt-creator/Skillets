# Skillets
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Skillets — GitHub Pages</title>
  <meta name="description" content=" Simple, mobile‑friendly website template with a purple background and left-aligned title." />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    : root{
      --bg: #4b0082; /* white background */
      --muted: #d1b3ff;
      --text: #ffffff;
      --accent: #ffccff;
      --shadow: 0 10px 30px rgba(0,0,0,.35);
      --radius: 16px;
      --maxw: 1100px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{margin:0; font-family: Inter,system-ui, Segoe UI, Roboto, Helvetica, Arial, sans-serif; color: var(--text); background: var(--bg)}
    a{color:var(--accent); text-decoration:none}
    .container{max-width:var(--maxw); margin-inline:auto; padding:0 20px}header{padding:20px; background:rgba(75,0,130,1)}
.brand-title{font-size:2rem; font-weight:700; text-align:left; color:var(--text)}

.hero{padding:64px 0 32px;}
.hero h1{font-size:clamp(28px, 6vw, 48px); line-height:1.1; margin:0 0 14px; text-align:left}
.hero p{max-width:720px; color:var(--muted); margin:0 0 22px}

footer{border-top:1px solid rgba(255,255,255,.2); padding:24px 0; color:var(--muted); text-align:center}

  </style>
</head>
<body>
  <header>
    <div class="container">
      <span class="brand-title">Skillets</span>
    </div>
  </header>  <main id="top">
    <section class="hero">
      <div class="container">
        <h1>Welcome to Skillets</h1>
        <p>Build and share skills through short courses, English programs, Bachelor’s and Master’s pathways.</p>
      </div>
    </section>
  </main>  <footer>
    <div class="container">
      <small>© <span id="year"></span> Skillets. Built for GitHub Pages.</small>
    </div>
  </footer>  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script></body>
</html>
