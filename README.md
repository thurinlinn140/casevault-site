<!DOCTYPE html><html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Medical Case-Based Learning (CBL)</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap">
  <style>
    body { font-family: Inter, sans-serif; margin:0; background:#0b1020; color:#e8ecf8; line-height:1.6; }
    .container { max-width: 1100px; margin: auto; padding: 24px; }
    header { background:#11162b; position:sticky; top:0; padding:12px 24px; display:flex; justify-content:space-between; align-items:center; }
    header a { color:#b8c0e0; text-decoration:none; margin:0 10px; font-weight:600; }
    header a:hover { color:#fff; }
    h1,h2,h3 { color:#fff; }
    .section { padding:40px 24px; }
    .grid { display:grid; gap:20px; }
    .grid.cols-3 { grid-template-columns:repeat(auto-fit,minmax(260px,1fr)); }
    .card { background:#151b34; border-radius:16px; padding:20px; border:1px solid rgba(255,255,255,.1); }
    .card h3 { margin-top:0; }
    .muted { color:#b8c0e0; }
  </style>
</head>
<body>
  <header>
    <div><strong style="color:#5dd0ff">CBL</strong></div>
    <nav>
      <a href="#what">What</a>
      <a href="#cases">Cases</a>
      <a href="#books">Books</a>
      <a href="#history">History</a>
      <a href="#resources">Resources</a>
    </nav>
  </header>  <main>
    <section class="section container" id="what">
      <h2>What is Case-Based Learning?</h2>
      <p class="muted">CBL uses authentic clinical cases to integrate science, reasoning, and teamwork in medical education.</p>
    </section><section class="section container" id="cases">
  <h2>Sample Medical Cases</h2>
  <div class="grid cols-3">
    <div class="card">
      <h3>DKA in a 22-year-old</h3>
      <p class="muted">Polyuria, Kussmaul breathing, high anion gap. Explore insulin physiology and management.</p>
    </div>
    <div class="card">
      <h3>Oliguric AKI after Sepsis</h3>
      <p class="muted">Rising creatinine, muddy casts, hypotension. Differentiate pre-renal vs ATN.</p>
    </div>
    <div class="card">
      <h3>Fatigue & Pallor in Pregnancy</h3>
      <p class="muted">Microcytosis with normal ferritin. Distinguish iron deficiency vs thalassemia trait.</p>
    </div>
  </div>
</section>

<section class="section container" id="books">
  <h2>Recommended Books</h2>
  <div class="grid cols-3">
    <div class="card">
      <h3>Robbins & Cotran Pathologic Basis of Disease</h3>
      <p class="muted">Gold standard for understanding mechanisms of disease.</p>
    </div>
    <div class="card">
      <h3>Harrison’s Principles of Internal Medicine</h3>
      <p class="muted">Reference for clinical reasoning and management.</p>
    </div>
    <div class="card">
      <h3>Clinical Reasoning in the Health Professions</h3>
      <p class="muted">Frameworks for thinking like a clinician.</p>
    </div>
  </div>
</section>

<section class="section container" id="history">
  <h2>History of CBL</h2>
  <p class="muted">Case-Based Learning grew out of Problem-Based Learning (PBL) at McMaster University in the 1960s. It was designed to move away from lecture-heavy teaching and toward active, student-centered approaches. Today, CBL is widely used across medical schools, often blended with simulation and e-learning.</p>
</section>

<section class="section container" id="resources">
  <h2>Resources</h2>
  <div class="grid cols-3">
    <div class="card">
      <h3>Templates</h3>
      <p class="muted">Case storyboard, facilitator guide, and worksheets.</p>
    </div>
    <div class="card">
      <h3>Facilitator Cheatsheet</h3>
      <p class="muted">Quick prompts and tips for running smooth sessions.</p>
    </div>
    <div class="card">
      <h3>Reading List</h3>
      <p class="muted">Curated research on CBL and clinical reasoning.</p>
    </div>
  </div>
</section>

  </main>  <footer class="container" style="color:#b8c0e0; padding:20px; border-top:1px solid rgba(255,255,255,.1)">© <span id="year"></span> Medical Case-Based Learning</footer>  <script>document.getElementById('year').textContent = new Date().getFullYear();</script></body>
</html>
