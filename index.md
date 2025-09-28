<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>ScanQuiz – Snap notes. Quiz smarter.</title>
  <meta name="description" content="Turn any page of notes into instant practice quizzes. ScanQuiz helps you study faster with auto-generated questions, flashcards, and progress tracking." />
  <!-- Optional: Smart App Banner (replace YOUR_APP_ID when live) -->
  <!-- <meta name="apple-itunes-app" content="app-id=YOUR_APP_ID"> -->
  <style>
    html,body{margin:0;padding:0;font-family:-apple-system,system-ui,Segoe UI,Roboto,Helvetica,Arial,sans-serif;color:#0b1220;background:#ffffff}
    .wrap{max-width:960px;margin:0 auto;padding:40px 20px}
    header{display:flex;align-items:center;gap:14px}
    .logo{width:44px;height:44px;border-radius:10px;background:#111;display:inline-block}
    h1{font-size:40px;margin:0}
    .tag{margin:6px 0 0 0;color:#4b5563}
    .hero{display:grid;grid-template-columns:1.1fr 0.9fr;gap:24px;margin-top:36px}
    .card{border:1px solid #e5e7eb;border-radius:14px;padding:18px}
    .cta{display:inline-block;margin-top:16px;padding:12px 16px;border-radius:10px;border:1px solid #e5e7eb;text-decoration:none}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:24px}
    .ft{margin-top:40px;color:#6b7280;font-size:14px}
    @media (max-width:900px){.hero{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="logo"></div>
      <div>
        <h1>ScanQuiz</h1>
        <p class="tag">Snap notes. Quiz smarter.</p>
      </div>
    </header>

    <section class="hero">
      <div class="card">
        <h2>Turn pages into quizzes</h2>
        <p>Take a photo of your textbook or notes and get instant practice questions. No manual typing, no busywork—just focused studying.</p>
        <ul>
          <li>AI-generated multiple choice & flashcards</li>
          <li>Quick reviews and spaced repetition</li>
          <li>Track progress by chapter or topic</li>
        </ul>
        <a class="cta" href="https://apps.apple.com/app/idYOUR_APP_ID">Download on the App&nbsp;Store</a>
      </div>
      <div class="card">
        <h3>How it works</h3>
        <ol>
          <li><strong>Scan:</strong> Snap a page of your notes or a textbook.</li>
          <li><strong>Generate:</strong> ScanQuiz creates quizzes and flashcards.</li>
          <li><strong>Practice:</strong> Review, track streaks, and master faster.</li>
        </ol>
      </div>
    </section>

    <section>
      <div class="grid">
        <div class="card"><strong>Fast</strong><br/>From photo to practice in seconds.</div>
        <div class="card"><strong>Accurate</strong><br/>Built for textbooks and class notes.</div>
        <div class="card"><strong>Focused</strong><br/>Quizzes by chapter and topic.</div>
      </div>
    </section>

    <footer class="ft">
      © <span id="y"></span> ScanQuiz ·
      <a href="/privacy">Privacy</a> ·
      <a href="/terms">Terms</a> ·
      <a href="mailto:support@scanquiz.app">Support</a>
    </footer>
  </div>
  <script>document.getElementById('y').textContent = new Date().getFullYear()</script>
</body>
</html>
