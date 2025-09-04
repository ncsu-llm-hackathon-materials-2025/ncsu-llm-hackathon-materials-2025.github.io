<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>LLM Hackathon — Materials Science & Chemistry @ NC State</title>
  <meta name="description" content="Join the NC State LLM Hackathon for Applications in Materials Science & Chemistry. 48 hours of building, mentoring, and prizes. Register now!"/>
  <link rel="icon" href="/favicon.ico" />

  <!-- Social cards -->
  <meta property="og:title" content="LLM Hackathon — Materials Science & Chemistry @ NC State"/>
  <meta property="og:description" content="48 hours of building, mentoring, and prizes. Register now!"/>
  <meta property="og:type" content="website"/>
  <meta property="og:image" content="/banner.png"/>
  <meta name="twitter:card" content="summary_large_image"/>

  <style>
    :root{
      --brand:#cc0000; /* NC State red */
      --brand-dark:#a40000;
      --ink:#111;
      --muted:#6b7280; /* gray-500 */
      --bg:#f6f7f8; /* light gray background */
      --card:#fff;
      --ring:rgba(204,0,0,0.2);
      --radius:16px;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;color:var(--ink);background:var(--bg);font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,"Noto Sans",sans-serif}
    a{color:var(--brand)}

    /* Top navbar */
    .nav{position:sticky;top:0;z-index:50;background:#fff;border-bottom:1px solid #e5e7eb}
    .container{max-width:1100px;margin:0 auto;padding:0 20px}
    .nav-inner{display:flex;align-items:center;justify-content:space-between;height:64px}
    .brand{display:flex;gap:12px;align-items:center;font-weight:800;letter-spacing:.2px}
    .brand img{height:28px}
    .nav a.btn{padding:10px 14px;border-radius:999px;background:var(--brand);color:#fff;text-decoration:none;font-weight:600}
    .nav a.btn:hover{background:var(--brand-dark)}

    /* Hero */
    .hero{background:#fff}
    .hero-grid{display:grid;grid-template-columns:1.4fr .9fr;gap:24px;padding:40px 0}
    .eyebrow{color:var(--brand);font-weight:700;text-transform:uppercase;font-size:.8rem;letter-spacing:.08em}
    h1{font-size:2.25rem;line-height:1.15;margin:.35rem 0 0}
    .meta{margin-top:10px;color:var(--muted);display:flex;flex-wrap:wrap;gap:14px;font-size:.95rem}
    .chip{display:inline-flex;align-items:center;gap:6px;padding:6px 10px;border:1px solid #e5e7eb;border-radius:999px;background:#fafafa}
    .cover{overflow:hidden;border-radius:var(--radius);border:1px solid #e5e7eb}
    .cover img{width:100%;display:block}

    /* Sidebar card (Register) */
    .card{background:var(--card);border:1px solid #e5e7eb;border-radius:var(--radius);box-shadow:0 1px 2px rgba(0,0,0,.03)}
    .sticky{position:sticky;top:88px}
    .card .pad{padding:18px}
    .price{font-size:1.8rem;font-weight:800}
    .btn-primary{display:block;text-align:center;background:var(--brand);color:#fff;text-decoration:none;padding:12px 16px;border-radius:12px;font-weight:700}
    .btn-primary:hover{background:var(--brand-dark)}

    /* Section */
    section{padding:36px 0}
    .grid-2{display:grid;grid-template-columns:1fr 1fr;gap:24px}
    .kpis{display:flex;gap:14px;flex-wrap:wrap}
    .kpi{flex:1;min-width:160px;background:#fff;border:1px solid #e5e7eb;border-radius:12px;padding:14px}
    .kpi b{font-size:1.4rem}

    /* Agenda */
    .timeline{display:grid;gap:12px}
    .slot{background:#fff;border:1px solid #e5e7eb;border-radius:12px;padding:14px;display:grid;grid-template-columns:110px 1fr;gap:14px}
    .time{color:var(--muted);font-weight:600}

    /* FAQ */
    details{background:#fff;border:1px solid #e5e7eb;border-radius:12px;padding:14px}
    details+details{margin-top:10px}
    summary{cursor:pointer;font-weight:700}

    /* Footer */
    footer{border-top:1px solid #e5e7eb;color:#6b7280;padding:32px 0;background:#fff}

    /* Responsive */
    @media (max-width: 960px){
      .hero-grid{grid-template-columns:1fr}
      .grid-2{grid-template-columns:1fr}
      .sticky{position:static}
    }
  </style>

  <!-- Schema.org: Event for rich results -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"Event",
    "name":"LLM Hackathon for Applications in Materials Science & Chemistry",
    "startDate":"2025-10-25T17:00:00-04:00",
    "endDate":"2025-10-27T16:00:00-04:00",
    "eventAttendanceMode":"https://schema.org/MixedEventAttendanceMode",
    "eventStatus":"https://schema.org/EventScheduled",
    "location":{
      "@type":"Place",
      "name":"NC State — Engineering Building III (EB3)",
      "address":"911 Partners Way, Raleigh, NC 27606"
    },
    "organizer":{
      "@type":"Organization",
      "name":"Yingling AIMS Research Group",
      "url":"https://www.mse.ncsu.edu/"
    },
    "image":["/banner.png"],
    "description":"48‑hour hackathon focused on LLM applications in materials science and chemistry. Mentors, workshops, and prizes.",
    "offers":{"@type":"Offer","price":"0","priceCurrency":"USD","availability":"https://schema.org/InStock"}
  }
  </script>
</head>
<body>
  <!-- NAV -->
  <div class="nav">
    <div class="container nav-inner">
      <div class="brand">
        <img src="/ncsu-mark.png" alt="NC State mark"/>
        <span>NC State LLM Hackathon</span>
      </div>
      <a class="btn" href="#register">Register</a>
    </div>
  </div>

  <!-- HERO -->
  <header class="hero">
    <div class="container hero-grid" style="padding-bottom:20px">
      <div>
        <div class="eyebrow">Materials Science • Chemistry • AI/LLMs</div>
        <h1>LLM Hackathon for Applications in Materials Science & Chemistry</h1>
        <div class="meta">
          <span class="chip" title="Dates">Oct 25–27, 2025</span>
          <span class="chip" title="Format">Hybrid (On‑site & Online)</span>
          <span class="chip" title="Location">NC State — EB3, Raleigh NC</span>
          <span class="chip" title="Cost">Free</span>
        </div>
        <p style="margin-top:14px;max-width:60ch;color:#374151">A 48‑hour build sprint to prototype research and teaching tools powered by large language models for discovery, simulation workflows, data curation, and scientific communication in materials science and chemistry.</p>
        <div class="kpis" style="margin-top:12px">
          <div class="kpi"><b>2–5</b><div class="muted">Team size</div></div>
          <div class="kpi"><b>$ Prizes</b><div class="muted">Awards for top teams</div></div>
          <div class="kpi"><b>Mentors</b><div class="muted">Industry & faculty</div></div>
        </div>
      </div>
      <aside class="sticky">
        <div class="card">
          <div class="cover"><img src="/banner.png" alt="Hackathon banner"></div>
          <div class="pad">
            <div class="price">Free</div>
            <p style="margin:.4rem 0 1rem;color:var(--muted)">Registration required • Limited spots</p>
            <a class="btn-primary" href="#register">Register on this page</a>
            <ul style="margin:14px 0 0 18px;color:#374151">
              <li>Beginner‑friendly workshops</li>
              <li>Mentor office hours</li>
              <li>Meals provided on‑site</li>
            </ul>
          </div>
        </div>
      </aside>
    </div>
  </header>

  <!-- WHAT YOU'LL DO / TRACKS -->
  <section>
    <div class="container grid-2">
      <div class="card" style="padding:18px">
        <h2 style="margin-top:0">Tracks & Ideas</h2>
        <ul style="line-height:1.7">
          <li>LLM copilots for **materials databases** and ELNs</li>
          <li>Workflow agents for **MD/DFT** setup, execution, and analysis</li>
          <li>Design tools for **polymers, soft & biomaterials**</li>
          <li>Education & outreach: interactive labs, grading aides</li>
          <li>Open science: dataset curation, metadata extraction</li>
        </ul>
      </div>
      <div class="card" style="padding:18px">
        <h2 style="margin-top:0">Judging Criteria</h2>
        <ul style="line-height:1.7">
          <li><b>Impact:</b> addresses a real research/education need</li>
          <li><b>Originality:</b> novel approach or integration</li>
          <li><b>Technical depth:</b> sound methods & evaluation</li>
          <li><b>Presentation:</b> clarity, demo quality, documentation</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- AGENDA -->
  <section>
    <div class="container">
      <h2>Agenda</h2>
      <div class="timeline" style="margin-top:12px">
        <div class="slot"><div class="time">Fri 5:00p</div><div>Check‑in, dinner & opening remarks</div></div>
        <div class="slot"><div class="time">Fri 6:00p</div><div>Problem pitches & team formation</div></div>
        <div class="slot"><div class="time">Sat 9:00a</div><div>Workshops & mentor office hours</div></div>
        <div class="slot"><div class="time">Sat 6:00p</div><div>Checkpoint demos</div></div>
        <div class="slot"><div class="time">Sun 1:00p</div><div>Submissions due</div></div>
        <div class="slot"><div class="time">Sun 2:00p</div><div>Final demos & judging</div></div>
        <div class="slot"><div class="time">Sun 4:00p</div><div>Awards & closing</div></div>
      </div>
    </div>
  </section>

  <!-- SPEAKERS / MENTORS (optional placeholder) -->
  <section>
    <div class="container">
      <h2>Speakers & Mentors</h2>
      <p style="color:#374151">TBA. Interested in mentoring? Email <a href="mailto:hackathon@example.edu">hackathon@example.edu</a>.</p>
    </div>
  </section>

  <!-- LOCATION + MAP -->
  <section>
    <div class="container grid-2">
      <div>
        <h2>Location</h2>
        <p><b>NC State — Engineering Building III (EB3)</b><br>911 Partners Way, Raleigh, NC 27606</p>
        <p>Hybrid participation is available for remote teams.</p>
      </div>
      <div class="card" style="overflow:hidden">
        <iframe title="Map to EB3" width="100%" height="300" loading="lazy" style="border:0" allowfullscreen
          src="https://www.google.com/maps?q=NC+State+Engineering+Building+III&output=embed"></iframe>
      </div>
    </div>
  </section>

  <!-- REGISTER (Google Form) -->
  <section id="register">
    <div class="container">
      <h2>Register</h2>
      <p style="color:#374151">Complete the form below. One submission per participant. Teams (2–7) may be formed after registration or bring your own.</p>
      <div class="card" style="padding:0;overflow:hidden">
       <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdhADJ6hzT-uZguO0JITpIpb1NrM0HYbh_ROxykZ5wkBdgzWg/viewform?embedded=true" width="640" height="970" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section>
    <div class="container">
      <h2>FAQ</h2>
      <details open>
        <summary>Do I need prior experience?</summary>
        <p>No. We’ll run beginner‑friendly workshops and provide mentors.</p>
      </details>
      <details>
        <summary>Is it free?</summary>
        <p>Yes, there’s no registration fee. Meals provided for on‑site attendees.</p>
      </details>
      <details>
        <summary>Can I participate remotely?</summary>
        <p>Yes, the event is hybrid. We’ll provide a virtual kickoff, Discord/Slack, and online submissions.</p>
      </details>
      <details>
        <summary>What should I build?</summary>
        <p>Anything aligned to the tracks and criteria above. Open‑source is encouraged.</p>
      </details>
    </div>
  </section>

  <footer>
    <div class="container" style="display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap">
      <div>© 2025 NC State University — Yingling AIMS Research Group</div>
      <div>Questions? <a href="mailto:groupyingling@gmail.com">groupyingling@gmail.com</a></div>
    </div>
  </footer>
</body>
</html>
