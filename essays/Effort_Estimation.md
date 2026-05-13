---
layout: essay
type: essay
title: "Effort Estimation"
date: 2026-05-11
published: true
labels:
  - Software Engineering
  - Learning
---

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Effort Estimation — Portfolio Essay</title>
<link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,600;1,400&family=DM+Mono:wght@400;500&family=Outfit:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --ink:       #1a1a2e;
    --muted:     #5a5a7a;
    --accent:    #c0392b;
    --accent2:   #e67e22;
    --bg:        #faf9f6;
    --rule:      #e2e0da;
    --card:      #f2f0eb;
    --mono:      'DM Mono', monospace;
    --serif:     'Lora', Georgia, serif;
    --sans:      'Outfit', sans-serif;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: var(--bg);
    color: var(--ink);
    font-family: var(--serif);
    font-size: 18px;
    line-height: 1.8;
    min-height: 100vh;
  }

  /* ── Header ── */
  header {
    border-bottom: 1px solid var(--rule);
    padding: 3rem 0 2rem;
    text-align: center;
    position: relative;
    overflow: hidden;
  }

  header::before {
    content: '';
    position: absolute;
    inset: 0;
    background: repeating-linear-gradient(
      0deg,
      transparent,
      transparent 39px,
      var(--rule) 39px,
      var(--rule) 40px
    );
    opacity: 0.35;
    pointer-events: none;
  }

  .label-row {
    display: flex;
    gap: .5rem;
    justify-content: center;
    margin-bottom: 1.2rem;
    position: relative;
  }

  .label {
    font-family: var(--mono);
    font-size: .7rem;
    letter-spacing: .12em;
    text-transform: uppercase;
    color: var(--accent);
    border: 1px solid var(--accent);
    padding: .2rem .55rem;
    border-radius: 2px;
  }

  .label.alt { color: var(--accent2); border-color: var(--accent2); }

  h1 {
    font-family: var(--sans);
    font-size: clamp(2rem, 5vw, 3.2rem);
    font-weight: 700;
    letter-spacing: -.02em;
    line-height: 1.1;
    margin-bottom: .6rem;
    position: relative;
  }

  .byline {
    font-family: var(--mono);
    font-size: .75rem;
    color: var(--muted);
    letter-spacing: .08em;
    position: relative;
  }

  /* ── Layout ── */
  main {
    max-width: 720px;
    margin: 0 auto;
    padding: 3.5rem 1.5rem 6rem;
  }

  /* ── Section headings ── */
  .q-block {
    margin: 3.5rem 0 1.2rem;
    display: flex;
    align-items: baseline;
    gap: .9rem;
  }

  .q-num {
    font-family: var(--mono);
    font-size: .7rem;
    font-weight: 500;
    color: var(--accent);
    letter-spacing: .1em;
    white-space: nowrap;
    padding-top: .15rem;
  }

  h2 {
    font-family: var(--sans);
    font-size: 1.15rem;
    font-weight: 600;
    letter-spacing: -.01em;
    line-height: 1.3;
    color: var(--ink);
    border-bottom: 2px solid var(--accent);
    padding-bottom: .3rem;
    flex: 1;
  }

  /* ── Body copy ── */
  p {
    margin-bottom: 1.1rem;
    color: #2b2b3d;
  }

  /* ── Pull quote ── */
  .pull {
    margin: 2.2rem 0;
    padding: 1.2rem 1.6rem;
    border-left: 3px solid var(--accent);
    background: var(--card);
    font-family: var(--serif);
    font-style: italic;
    font-size: 1.05rem;
    color: var(--ink);
    line-height: 1.65;
    border-radius: 0 4px 4px 0;
  }

  /* ── Insight card ── */
  .insight {
    margin: 2rem 0;
    padding: 1.3rem 1.5rem;
    background: var(--card);
    border-radius: 6px;
    border: 1px solid var(--rule);
    display: grid;
    grid-template-columns: auto 1fr;
    gap: .8rem 1rem;
    align-items: start;
  }

  .insight-icon {
    font-size: 1.4rem;
    line-height: 1;
    padding-top: .1rem;
  }

  .insight-text {
    font-family: var(--sans);
    font-size: .92rem;
    line-height: 1.6;
    color: var(--muted);
    margin: 0;
  }

  .insight-text strong {
    color: var(--ink);
    font-weight: 600;
  }

  /* ── Divider ── */
  hr {
    border: none;
    border-top: 1px solid var(--rule);
    margin: 4rem 0;
  }

  /* ── Footer note ── */
  .footer-note {
    margin-top: 4rem;
    padding-top: 2rem;
    border-top: 1px solid var(--rule);
    font-family: var(--mono);
    font-size: .72rem;
    color: var(--muted);
    letter-spacing: .06em;
    text-align: center;
  }

  /* ── Fade-in on scroll ── */
  .fade-in {
    opacity: 0;
    transform: translateY(18px);
    transition: opacity .55s ease, transform .55s ease;
  }
  .fade-in.visible { opacity: 1; transform: none; }
</style>
</head>
<body>

<header>
  <div class="label-row">
    <span class="label">Software Engineering</span>
    <span class="label alt">Learning</span>
  </div>
  <h1>Effort Estimation &amp; Tracking</h1>
  <p class="byline">May 11, 2026 &nbsp;·&nbsp; Team Project Reflection</p>
</header>

<main>

  <!-- Q1 -->
  <div class="q-block fade-in">
    <span class="q-num">01 —</span>
    <h2>How did you make your effort estimates?</h2>
  </div>
  <p class="fade-in">Our team's estimation process was a blend of gut feeling, task decomposition, and informal team discussion. At the start of each phase, we would break down the work into individual features or components — separating the frontend UI, REST API endpoints, and database schema into distinct tasks — then assign rough hour ranges to each. These ranges were largely driven by personal intuition and whatever prior experience team members had with similar technologies.</p>
  <p class="fade-in">We did not rely on any formal historical data, since this was a class project and we had no prior logs to reference. Instead, "historical data" meant individual memory — recalling roughly how long a similar feature took in a past assignment or side project. When estimates varied significantly between members, we'd briefly discuss and land on a consensus. It was lightweight, more conversational than systematic.</p>

  <!-- Q2 -->
  <div class="q-block fade-in">
    <span class="q-num">02 —</span>
    <h2>Even though estimates were often off, did estimating in advance provide any benefit?</h2>
  </div>
  <p class="fade-in">Honestly, the direct benefits of our estimates were limited. Because we consistently overestimated — giving ourselves more time than tasks actually required — the estimates rarely created urgency or helped us prioritize. That said, the act of estimating did force us to think through the full scope of work before diving in.</p>

  <div class="pull fade-in">
    "By breaking the project into discrete tasks just to size them, we caught a few things we might have forgotten to plan for — deployment setup, writing tests — things that would have blindsided us later."
  </div>

  <p class="fade-in">One indirect benefit was team alignment. When everyone estimated independently and we compared, disagreements revealed different assumptions about what a feature actually entailed. One member estimated the search feature at two hours; another said six. That gap surfaced a real disagreement about whether filters and pagination were in scope. The conversation was valuable, even if the resulting number was still a guess.</p>

  <!-- Q3 -->
  <div class="q-block fade-in">
    <span class="q-num">03 —</span>
    <h2>Was tracking actual effort useful?</h2>
  </div>
  <p class="fade-in">In our case, tracking actual effort provided minimal actionable benefit during the project. Because we did not track consistently in real time — relying on rough recollections after the fact — the data we had was imprecise enough that drawing firm conclusions felt unreliable. Most project decisions were driven by deadlines and feature completeness, not by effort data.</p>
  <p class="fade-in">That said, reflecting on actual effort at the end did improve our intuition for future sizing. Knowing that a feature we estimated at three hours took closer to one hour helped recalibrate our mental benchmarks. The lessons were qualitative rather than quantitative — more "UI tasks go faster than we expect" than "UI tasks take exactly 1.2× our estimate."</p>

  <!-- Q4 -->
  <div class="q-block fade-in">
    <span class="q-num">04 —</span>
    <h2>How did you track your actual effort?</h2>
  </div>
  <p class="fade-in">We tracked effort informally, relying primarily on memory at the end of each week or project phase. There was no dedicated time-tracking tool — no Toggl, Jira time logs, or shared spreadsheet running in the background. Each team member would mentally reconstruct how much time they spent, occasionally anchoring recollections to commit timestamps or file modification dates.</p>

  <div class="insight fade-in">
    <span class="insight-icon">⚠️</span>
    <p class="insight-text"><strong>Accuracy estimate: ~60–70%.</strong> Memory is notoriously poor for time. Without logging in the moment, it's easy to forget short work sessions, undercount context-switching overhead, or conflate time spent <em>thinking</em> about a problem with time spent actively working on it. Our retrospective tracking introduced systematic bias toward round numbers and underestimates.</p>
  </div>

  <!-- Q5 -->
  <div class="q-block fade-in">
    <span class="q-num">05 —</span>
    <h2>Reflection: what would you change next time?</h2>
  </div>
  <p class="fade-in">The most impactful change I would make is logging effort in real time rather than reconstructing it from memory. Even a simple habit — starting a timer when sitting down to work and stopping it when done — would dramatically improve accuracy. A lightweight tool like Toggl or even a shared spreadsheet with daily entries would be sufficient. The goal is not perfect granularity, but data reliable enough to notice when estimates and actuals consistently diverge.</p>
  <p class="fade-in">I would also invest more time in task decomposition upfront. Our breakdowns were useful but sometimes too coarse — grouping "backend" as a single task obscured which specific pieces were taking longer than expected. Finer-grained tasks make both estimation and tracking more meaningful, and make it easier to spot where team skills or tooling choices are creating unexpected friction.</p>

  <hr>

  <!-- Q6 -->
  <div class="q-block fade-in">
    <span class="q-num">06 —</span>
    <h2>AI Tool Use</h2>
  </div>
  <p class="fade-in">No AI tools were used for effort estimation or tracking during this project. All estimates were produced through team discussion and individual judgment, and all tracking was done manually through memory and retrospective reconstruction.</p>

  <div class="footer-note fade-in">
    ICS 314 · Software Engineering · University of Hawaiʻi at Mānoa
  </div>

</main>

<script>
  const els = document.querySelectorAll('.fade-in');
  const io = new IntersectionObserver(entries => {
    entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('visible'); io.unobserve(e.target); } });
  }, { threshold: 0.08 });
  els.forEach(el => io.observe(el));
</script>

</body>
</html>
