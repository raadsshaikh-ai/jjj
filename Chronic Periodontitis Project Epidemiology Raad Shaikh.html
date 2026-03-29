<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Chronic Periodontitis Epidemiology Dashboard</title>
  <style>
    :root {
      --bg: #f6f7fb;
      --card: rgba(255,255,255,0.92);
      --ink: #1f2937;
      --muted: #5b6474;
      --line: #dde4ee;
      --accent: #0f766e;
      --accent-2: #0b5fa8;
      --accent-3: #c2410c;
      --soft: #edf7f6;
      --shadow: 0 14px 40px rgba(17,24,39,.08);
      --radius: 22px;
      --max: 1220px;
    }

    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      color: var(--ink);
      background:
        radial-gradient(circle at top left, rgba(15,118,110,.10), transparent 28%),
        radial-gradient(circle at top right, rgba(11,95,168,.10), transparent 22%),
        linear-gradient(180deg, #fbfcfe 0%, var(--bg) 100%);
      line-height: 1.6;
    }

    a { color: var(--accent-2); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .shell { width: min(var(--max), calc(100% - 32px)); margin: 0 auto; }

    .topbar {
      position: sticky;
      top: 0;
      z-index: 30;
      backdrop-filter: blur(16px);
      background: rgba(246,247,251,.82);
      border-bottom: 1px solid rgba(221,228,238,.75);
    }

    .topbar-inner {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 18px;
      padding: 14px 0;
    }

    .brand {
      font-weight: 800;
      letter-spacing: -.02em;
      font-size: 1rem;
    }

    .nav {
      display: flex;
      flex-wrap: wrap;
      justify-content: flex-end;
      gap: 8px;
    }

    .nav a {
      font-size: .9rem;
      color: var(--ink);
      padding: 8px 12px;
      border-radius: 999px;
      background: rgba(255,255,255,.72);
      border: 1px solid rgba(221,228,238,.92);
    }

    .hero { padding: 44px 0 30px; }

    .hero-grid {
      display: grid;
      grid-template-columns: 1.25fr .95fr;
      gap: 22px;
      align-items: stretch;
    }

    .hero-card, .card {
      background: var(--card);
      border: 1px solid rgba(221,228,238,.85);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
    }

    .hero-card {
      padding: 30px;
      min-height: 360px;
      position: relative;
      overflow: hidden;
    }

    .hero-card::after {
      content: "";
      position: absolute;
      right: -50px;
      top: -40px;
      width: 200px;
      height: 200px;
      border-radius: 50%;
      background: radial-gradient(circle, rgba(15,118,110,.16) 0%, rgba(15,118,110,0) 72%);
    }

    .eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 8px 12px;
      border-radius: 999px;
      font-size: .82rem;
      font-weight: 700;
      color: var(--accent);
      background: var(--soft);
      border: 1px solid rgba(15,118,110,.14);
      margin-bottom: 14px;
    }

    h1, h2, h3, h4 { line-height: 1.15; margin: 0 0 12px; letter-spacing: -.03em; }
    h1 { font-size: clamp(2.1rem, 5vw, 3.5rem); }
    h2 { font-size: clamp(1.5rem, 3vw, 2.2rem); }
    h3 { font-size: 1.1rem; }
    p { margin: 0 0 12px; color: var(--muted); }

    .lede { font-size: 1.05rem; max-width: 62ch; }

    .hero-metrics {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 12px;
      margin-top: 22px;
    }

    .metric {
      padding: 15px;
      border-radius: 18px;
      background: #fff;
      border: 1px solid var(--line);
    }

    .metric strong {
      display: block;
      font-size: 1.55rem;
      color: var(--ink);
      line-height: 1;
      margin-bottom: 6px;
    }

    .metric span { font-size: .88rem; color: var(--muted); }

    .art-panel {
      padding: 22px;
      display: grid;
      gap: 16px;
      grid-template-rows: 1fr auto;
    }

    .mini-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 12px;
    }

    .mini {
      border-radius: 18px;
      padding: 14px;
      background: linear-gradient(180deg, #ffffff 0%, #f9fbfd 100%);
      border: 1px solid var(--line);
      min-height: 140px;
    }

    .mini h4 { margin-bottom: 8px; font-size: .98rem; }
    .mini p { font-size: .9rem; }

    .svg-wrap {
      display: grid;
      place-items: center;
      background: linear-gradient(180deg, rgba(15,118,110,.05), rgba(11,95,168,.02));
      border-radius: 20px;
      border: 1px solid var(--line);
      min-height: 220px;
      padding: 10px;
    }

    section { padding: 16px 0 8px; }

    .section-head {
      display: flex;
      align-items: end;
      justify-content: space-between;
      gap: 14px;
      margin: 18px 0 16px;
    }

    .section-head p { max-width: 68ch; }

    .grid-2, .grid-3, .grid-4 {
      display: grid;
      gap: 18px;
    }

    .grid-2 { grid-template-columns: repeat(2, minmax(0,1fr)); }
    .grid-3 { grid-template-columns: repeat(3, minmax(0,1fr)); }
    .grid-4 { grid-template-columns: repeat(4, minmax(0,1fr)); }

    .card { padding: 22px; }

    .pill {
      display: inline-block;
      font-size: .8rem;
      font-weight: 700;
      padding: 6px 10px;
      border-radius: 999px;
      background: #eff6ff;
      color: var(--accent-2);
      border: 1px solid rgba(11,95,168,.12);
      margin-bottom: 10px;
    }

    ul { margin: 0; padding-left: 18px; color: var(--muted); }
    li + li { margin-top: 8px; }

    .table-wrap {
      overflow-x: auto;
      border-radius: 18px;
      border: 1px solid var(--line);
      background: #fff;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      min-width: 820px;
    }

    th, td {
      padding: 14px 16px;
      border-bottom: 1px solid var(--line);
      text-align: left;
      vertical-align: top;
      font-size: .95rem;
    }

    th {
      background: #f8fbfd;
      color: #334155;
      font-size: .85rem;
      text-transform: uppercase;
      letter-spacing: .04em;
    }

    tr:last-child td { border-bottom: 0; }

    .callout {
      border-left: 4px solid var(--accent);
      background: #fbfffe;
      padding: 16px 18px;
      border-radius: 0 18px 18px 0;
    }

    .timeline {
      display: grid;
      gap: 14px;
      position: relative;
      margin-top: 8px;
    }

    .step {
      position: relative;
      padding: 16px 18px 16px 22px;
      border-radius: 18px;
      border: 1px solid var(--line);
      background: #fff;
    }

    .step::before {
      content: "";
      position: absolute;
      left: 10px;
      top: 22px;
      width: 8px;
      height: 8px;
      border-radius: 50%;
      background: var(--accent);
      box-shadow: 0 0 0 5px rgba(15,118,110,.12);
    }

    .bars {
      display: grid;
      gap: 14px;
      margin-top: 8px;
    }

    .bar-row { display: grid; gap: 6px; }
    .bar-label { display: flex; justify-content: space-between; gap: 12px; font-size: .92rem; }
    .bar-track {
      height: 12px;
      border-radius: 999px;
      background: #e9eef5;
      overflow: hidden;
    }
    .bar-fill {
      height: 100%;
      border-radius: 999px;
      background: linear-gradient(90deg, var(--accent) 0%, var(--accent-2) 100%);
    }

    .policy {
      padding: 18px;
      border-radius: 20px;
      background: linear-gradient(180deg, #ffffff 0%, #fbfdff 100%);
      border: 1px solid var(--line);
    }

    .policy h3 { margin-bottom: 8px; }
    .policy .sub { font-size: .87rem; color: var(--accent-3); font-weight: 700; margin-bottom: 8px; }

    .refs ol { margin: 0; padding-left: 22px; }
    .refs li {
      color: var(--muted);
      margin-bottom: 10px;
      word-break: break-word;
    }

    .cite {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-width: 20px;
      height: 20px;
      padding: 0 6px;
      margin-left: 3px;
      border-radius: 999px;
      font-size: .72rem;
      font-weight: 700;
      line-height: 1;
      vertical-align: super;
      color: var(--accent-2);
      background: #eff6ff;
      border: 1px solid rgba(11,95,168,.18);
      text-decoration: none;
    }

    .cite:hover {
      background: #dbeafe;
      text-decoration: none;
    }

    .backref {
      margin-left: 8px;
      font-size: .82rem;
      white-space: nowrap;
    }

    .small { font-size: .92rem; }

    .flow-grid {
      display: grid;
      grid-template-columns: minmax(180px, 1fr) 44px minmax(180px, 1fr) 44px minmax(180px, 1fr) 44px minmax(180px, 1fr);
      gap: 12px;
      align-items: center;
      margin-top: 8px;
    }

    .flow-box {
      position: relative;
      padding: 16px;
      border-radius: 18px;
      border: 1px solid var(--line);
      background: linear-gradient(180deg, #ffffff 0%, #f9fbfd 100%);
      min-height: 184px;
      display: grid;
      align-content: start;
      gap: 10px;
    }

    .flow-box h4 {
      font-size: .98rem;
      margin-bottom: 0;
    }

    .flow-icon {
      width: 52px;
      height: 52px;
      border-radius: 50%;
      display: grid;
      place-items: center;
      background: linear-gradient(180deg, rgba(15,118,110,.12), rgba(11,95,168,.08));
      border: 1px solid rgba(11,95,168,.14);
    }

    .flow-arrow {
      display: grid;
      place-items: center;
      font-size: 1.8rem;
      color: var(--accent-2);
      font-weight: 800;
    }

    .chart-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0,1fr));
      gap: 18px;
      margin-top: 18px;
    }

    .chart-card {
      padding: 18px;
      border-radius: 20px;
      background: linear-gradient(180deg, #ffffff 0%, #fbfdff 100%);
      border: 1px solid var(--line);
    }

    .chart-card h4 { margin-bottom: 6px; font-size: 1rem; }
    .chart-note { font-size: .82rem; color: var(--muted); margin-top: 10px; }

    .vbars {
      display: flex;
      align-items: end;
      justify-content: space-between;
      gap: 12px;
      height: 220px;
      padding: 10px 8px 0;
      border-bottom: 1px solid var(--line);
      border-left: 1px solid var(--line);
      margin-top: 12px;
    }

    .vbar-col {
      flex: 1;
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 8px;
    }

    .vbar {
      width: 100%;
      max-width: 42px;
      border-radius: 10px 10px 0 0;
      background: linear-gradient(180deg, var(--accent-2) 0%, var(--accent) 100%);
    }

    .vbar-lite {
      background: linear-gradient(180deg, rgba(11,95,168,.4) 0%, rgba(15,118,110,.45) 100%);
    }

    .vbar-label {
      font-size: .74rem;
      color: var(--muted);
      text-align: center;
      line-height: 1.2;
    }

    .line-chart {
      margin-top: 12px;
      border: 1px solid var(--line);
      border-radius: 18px;
      background: linear-gradient(180deg, #ffffff 0%, #f9fbfd 100%);
      padding: 10px;
    }

    .chart-legend {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 10px;
      font-size: .8rem;
      color: var(--muted);
    }

    .legend-item {
      display: inline-flex;
      align-items: center;
      gap: 6px;
    }

    .legend-swatch {
      width: 14px;
      height: 14px;
      border-radius: 4px;
      background: var(--accent-2);
    }

    .legend-swatch.alt { background: var(--accent); }

    footer {
      padding: 28px 0 48px;
      color: var(--muted);
      font-size: .92rem;
    }

    @media (max-width: 1100px) {
      .chart-grid { grid-template-columns: 1fr; }
      .flow-grid { grid-template-columns: 1fr; }
      .flow-arrow { transform: rotate(90deg); }
    }

    @media (max-width: 980px) {
      .hero-grid, .grid-2, .grid-3, .grid-4 { grid-template-columns: 1fr; }
      .hero-metrics { grid-template-columns: repeat(2, 1fr); }
      .section-head { display: block; }
      .topbar-inner { align-items: flex-start; flex-direction: column; }
      .nav { justify-content: flex-start; }
    }

    @media (max-width: 640px) {
      .shell { width: min(var(--max), calc(100% - 20px)); }
      .hero-card, .card { padding: 18px; border-radius: 18px; }
      .hero-metrics { grid-template-columns: 1fr 1fr; }
      .nav a { font-size: .83rem; padding: 7px 10px; }
      .mini-grid { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>
  <header class="topbar">
    <div class="shell topbar-inner">
      <div class="brand">Chronic Periodontitis Epidemiology Dashboard</div>
      <nav class="nav">
        <a href="#summary">Summary</a>
        <a href="#etiology">Etiology</a>
        <a href="#burden">Burden</a>
        <a href="#history">Natural History</a>
        <a href="#prevention">Interventions</a>
        <a href="#policy">Policy</a>
        <a href="#methods">Methods</a>
        <a href="#references">References</a>
      </nav>
    </div>
  </header>

  <main class="shell">
    <section class="hero">
      <div class="hero-grid">
        <div class="hero-card">
          <div class="eyebrow">Epidemiology • Equity • Prevention</div>
          <h1>Chronic Periodontitis</h1>
          <p style="font-weight:700; color: var(--accent-2); margin-bottom: 12px;">Raad Shaikh</p>
          <p class="lede">
            An interactive epidemiology dashboard examining the causes, burden, progression, prevention, and policy implications of chronic periodontitis.<a class="cite" href="#ref1">1</a><a class="cite" href="#ref2">2</a><a class="cite" href="#ref3">3</a>
          </p>
          <div class="hero-metrics">
            <div class="metric">
              <strong>1.07B</strong>
              <span>estimated global cases in 2021</span>
            </div>
            <div class="metric">
              <strong>89.6M</strong>
              <span>estimated incident cases in 2021</span>
            </div>
            <div class="metric">
              <strong>55 to 59</strong>
              <span>age range with peak prevalence and years lived with disability (YLD) burden</span>
            </div>
            <div class="metric">
              <strong>Equity gap</strong>
              <span>greater burden in lower Socio-Demographic Index (SDI) settings and groups with reduced dental access</span>
            </div>
          </div>
        </div>

        <div class="hero-card art-panel">
          <div class="svg-wrap" aria-label="Stylized periodontal disease illustration">
            <svg viewBox="0 0 520 260" width="100%" height="100%" role="img">
              <defs>
                <linearGradient id="gum" x1="0" y1="0" x2="0" y2="1">
                  <stop offset="0%" stop-color="#f7b6c2"/>
                  <stop offset="100%" stop-color="#eb8fa1"/>
                </linearGradient>
                <linearGradient id="bone" x1="0" y1="0" x2="0" y2="1">
                  <stop offset="0%" stop-color="#fff3cd"/>
                  <stop offset="100%" stop-color="#f6df9b"/>
                </linearGradient>
              </defs>
              <rect x="30" y="120" width="460" height="80" rx="24" fill="url(#gum)" opacity=".95"/>
              <rect x="50" y="180" width="420" height="45" rx="18" fill="url(#bone)" opacity=".95"/>
              <g>
                <path d="M80 40 q30 0 30 28 v82 q0 18 -15 27 q-15 -9 -15 -27 V68 q0 -28 0 -28z" fill="#ffffff" stroke="#d8dee8" stroke-width="3"/>
                <path d="M150 30 q34 0 34 30 v92 q0 18 -17 29 q-17 -11 -17 -29 V60 q0 -30 0 -30z" fill="#ffffff" stroke="#d8dee8" stroke-width="3"/>
                <path d="M230 42 q28 0 28 26 v79 q0 18 -14 28 q-14 -10 -14 -28 V68 q0 -26 0 -26z" fill="#ffffff" stroke="#d8dee8" stroke-width="3"/>
                <path d="M300 28 q35 0 35 32 v90 q0 19 -17.5 30 q-17.5 -11 -17.5 -30 V60 q0 -32 0 -32z" fill="#ffffff" stroke="#d8dee8" stroke-width="3"/>
                <path d="M382 38 q31 0 31 29 v83 q0 18 -15.5 28 q-15.5 -10 -15.5 -28 V67 q0 -29 0 -29z" fill="#ffffff" stroke="#d8dee8" stroke-width="3"/>
              </g>
              <path d="M55 118 C120 102, 160 112, 225 102 S350 118, 465 100" fill="none" stroke="#b91c1c" stroke-width="5" stroke-dasharray="10 7" opacity=".65"/>
              <g opacity=".92">
                <circle cx="108" cy="107" r="5" fill="#0f766e"/>
                <circle cx="165" cy="97" r="5" fill="#0f766e"/>
                <circle cx="245" cy="108" r="5" fill="#0f766e"/>
                <circle cx="320" cy="96" r="5" fill="#0f766e"/>
                <circle cx="395" cy="104" r="5" fill="#0f766e"/>
              </g>
              <text x="36" y="244" font-size="15" fill="#5b6474">Stylized schematic: plaque-associated inflammation, pocketing, and bone loss</text>
            </svg>
          </div>
          <div class="mini-grid">
            <div class="mini">
              <h4>Disease pattern</h4>
              <p>Slowly progressive inflammatory destruction of the tooth supporting tissues, typically accumulating over years rather than appearing after a single short incubation period.</p>
            </div>
            <div class="mini">
              <h4>Public health lens</h4>
              <p>Burden reflects biology and behavior, but also insurance status, health literacy, smoking exposure, diabetes control, and access to routine dental care.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="summary">
      <div class="section-head">
        <div>
          <div class="pill">Executive Summary</div>
          <h2>Why this disease matters</h2>
        </div>
      </div>
      <div class="card">
        <p>Chronic periodontitis is a common inflammatory disease of the tooth supporting tissues that develops when a dysbiotic bacterial biofilm triggers a persistent host inflammatory response. The disease is not evenly distributed, with a heavier burden among older adults, smokers, people with diabetes, and populations facing low socioeconomic status or limited access to dental care. Globally, periodontal disease affected roughly 1.07 billion people in 2021, showing that it is a major source of disability rather than a rare dental problem. Its progression is often gradual and initially painless, which means missed opportunities for prevention are common unless early screening and maintenance care are accessible. The strongest public health response combines individual prevention such as plaque control and tobacco cessation with system-level interventions such as expanded adult dental coverage, community access, and integration of periodontal risk screening into routine care. Because inequities in access and risk factor exposure shape who gets diagnosed late and who loses teeth, policy solutions must explicitly address equity rather than rely only on individual behavior change.<a class="cite" href="#ref7">7</a><a class="cite" href="#ref10">10</a><a class="cite" href="#ref11">11</a></p>
      </div>
    </section>

    <section id="etiology">
      <div class="section-head">
        <div>
          <div class="pill">Objective 1</div>
          <h2>Etiology of disease</h2>
          <p>Definition, mechanisms, risk factors, and causal framing.</p>
        </div>
      </div>

      <div class="grid-2">
        <div class="card">
          <h3>Case definition</h3>
          <p>Chronic periodontitis is a chronic inflammatory disease of the supporting structures of the teeth initiated by plaque-associated bacterial biofilm, leading to attachment loss, periodontal pocket formation, and alveolar bone loss affecting two or more teeth. Common ICD-10-CM codes include K05.30 for unspecified periodontitis, K05.31 for localized periodontitis, and K05.32 for generalized periodontitis.<a class="cite" href="#ref1">1</a><a class="cite" href="#ref2">2</a><a class="cite" href="#ref3">3</a></p>
          <div class="callout small">
            A practical epidemiologic distinction is that gingivitis involves reversible gingival inflammation, while periodontitis includes irreversible loss of attachment and supporting bone.
          </div>
        </div>
        <div class="card">
          <h3>Known and suspected mechanisms</h3>
          <ul>
            <li><strong>Agent or exposure:</strong> plaque-associated bacterial biofilm, especially in the setting of poor oral hygiene and prolonged plaque retention.</li>
            <li><strong>Biologic mechanism:</strong> a dysbiotic biofilm provokes a prolonged host inflammatory response that increases inflammatory mediators and leads to connective tissue destruction and alveolar bone resorption.<a class="cite" href="#ref3">3</a><a class="cite" href="#ref4">4</a></li>
            <li><strong>Latency pattern:</strong> there is no classic short incubation period. Disease usually develops gradually over time and accelerates with persistent exposure and uncontrolled risk factors.</li>
          </ul>
        </div>
      </div>

      <div class="card" style="margin-top:18px;">
        <h3>Simple disease pathway</h3>
        <div class="flow-grid">
          <div class="flow-box">
            <div class="flow-icon" aria-hidden="true">
              <svg viewBox="0 0 48 48" width="30" height="30">
                <circle cx="24" cy="24" r="16" fill="#0f766e" opacity=".12"></circle>
                <circle cx="19" cy="20" r="5" fill="#0f766e"></circle>
                <circle cx="28" cy="18" r="4" fill="#0b5fa8"></circle>
                <circle cx="29" cy="28" r="5" fill="#0f766e"></circle>
                <circle cx="17" cy="29" r="3.5" fill="#0b5fa8"></circle>
              </svg>
            </div>
            <h4>1. Plaque biofilm</h4>
            <p>Bacterial plaque accumulates along the gingival margin when oral hygiene is inadequate.</p>
          </div>
          <div class="flow-arrow">→</div>
          <div class="flow-box">
            <div class="flow-icon" aria-hidden="true">
              <svg viewBox="0 0 48 48" width="30" height="30">
                <path d="M24 10 C17 18, 15 22, 15 27 a9 9 0 0 0 18 0 c0-5-2-9-9-17z" fill="#c2410c"></path>
                <circle cx="24" cy="29" r="4" fill="#fb923c"></circle>
              </svg>
            </div>
            <h4>2. Persistent inflammation</h4>
            <p>The host immune response becomes chronic rather than resolving the microbial challenge.</p>
          </div>
          <div class="flow-arrow">→</div>
          <div class="flow-box">
            <div class="flow-icon" aria-hidden="true">
              <svg viewBox="0 0 48 48" width="30" height="30">
                <rect x="12" y="24" width="24" height="8" rx="4" fill="#d1d5db"></rect>
                <path d="M15 20 L33 20" stroke="#0f766e" stroke-width="4" stroke-linecap="round"></path>
                <path d="M18 15 L30 15" stroke="#0b5fa8" stroke-width="3" stroke-linecap="round" opacity=".9"></path>
              </svg>
            </div>
            <h4>3. Tissue destruction</h4>
            <p>Inflammatory mediators promote connective tissue breakdown and alveolar bone resorption.</p>
          </div>
          <div class="flow-arrow">→</div>
          <div class="flow-box">
            <div class="flow-icon" aria-hidden="true">
              <svg viewBox="0 0 48 48" width="30" height="30">
                <path d="M18 8 q6 0 6 6 v18 q0 4-3 6 q-3-2-3-6 V14 q0-6 0-6z" fill="#ffffff" stroke="#94a3b8" stroke-width="2"></path>
                <path d="M24 8 q6 0 6 6 v18 q0 4-3 6 q-3-2-3-6 V14 q0-6 0-6z" fill="#ffffff" stroke="#94a3b8" stroke-width="2"></path>
                <path d="M12 30 C18 26, 30 28, 36 23" stroke="#b91c1c" stroke-width="3" fill="none"></path>
              </svg>
            </div>
            <h4>4. Clinical disease</h4>
            <p>Pocketing, attachment loss, recession, mobility, and eventual tooth loss can follow over time.</p>
          </div>
        </div>
      </div>

      <div class="card" style="margin-top:18px;">
        <h3>Risk factors and determinants</h3>
        <div class="table-wrap">
          <table>
            <thead>
              <tr>
                <th>Domain</th>
                <th>Factor</th>
                <th>How it influences risk</th>
                <th>Interpretation</th>
              </tr>
            </thead>
            <tbody>
              <tr><td>Biological</td><td>Diabetes mellitus</td><td>Hyperglycemia amplifies inflammation and impairs host response</td><td>One of the strongest and most consistent clinical risk factors</td></tr>
              <tr><td>Biological</td><td>Older age</td><td>Reflects cumulative exposure and gradual tissue destruction over time</td><td>Burden rises sharply in later adulthood</td></tr>
              <tr><td>Biological</td><td>Genetic susceptibility</td><td>Immune variation affects inflammatory response to plaque</td><td>Helps explain why not all plaque exposure produces the same severity</td></tr>
              <tr><td>Biological</td><td>Vitamin D deficiency</td><td>May impair immune regulation and bone metabolism</td><td>Supportive but less central than smoking or diabetes</td></tr>
              <tr><td>Behavioral</td><td>Poor oral hygiene</td><td>Allows plaque accumulation and persistent gingival inflammation</td><td>Most direct modifiable behavioral determinant</td></tr>
              <tr><td>Behavioral</td><td>Cigarette smoking</td><td>Promotes dysbiosis, immune dysfunction, and worse healing</td><td>High-risk exposure closely tied to progression and severity</td></tr>
              <tr><td>Behavioral</td><td>Alcohol use</td><td>May contribute through oral dryness, immune effects, and poorer self-care</td><td>Often interacts with other behavioral and social risks</td></tr>
              <tr><td>Social and structural</td><td>Low socioeconomic status</td><td>Associated with lower prevention access, lower health literacy, and delayed treatment</td><td>Important driver of inequity rather than a biologic cause</td></tr>
              <tr><td>Healthcare</td><td>Limited dental access</td><td>Reduces screening, cleanings, early diagnosis, and maintenance care</td><td>Converts preventable disease into late-stage burden</td></tr>
              <tr><td>Environmental</td><td>Secondhand smoke and inflammatory exposures</td><td>Add to systemic inflammatory burden and oral risk environments</td><td>Best viewed as contributory rather than primary</td></tr>
            </tbody>
          </table>
        </div>
      </div>

      <div class="grid-4" style="margin-top:18px;">
        <div class="card"><h3>Upstream</h3><p>Socioeconomic disadvantage, low health literacy, limited insurance, and low dental service access.</p></div>
        <div class="card"><h3>Intermediate</h3><p>Reduced cleanings, poor plaque control, tobacco exposure, and worse diabetes management.</p></div>
        <div class="card"><h3>Proximate</h3><p>Dysbiotic plaque biofilm and persistent gingival inflammation.</p></div>
        <div class="card"><h3>Outcome</h3><p>Attachment loss, periodontal pocketing, alveolar bone loss, tooth mobility, and eventual tooth loss.</p></div>
      </div>
    </section>

    <section id="burden">
      <div class="section-head">
        <div>
          <div class="pill">Objective 2</div>
          <h2>Distribution and burden of disease</h2>
          <p>Person, place, time, and core epidemiologic measures with an equity lens.</p>
        </div>
      </div>

      <div class="grid-3">
        <div class="card"><h3>Person</h3><p>Global burden begins rising from adolescence and early adulthood, with incident cases peaking in midlife and prevalence plus years lived with disability peaking later, especially between ages 55 and 59. Burden is slightly higher in males for prevalence and disability.</p></div>
        <div class="card"><h3>Place</h3><p>Lower Socio-Demographic Index (SDI) regions carry the greatest burden. High SDI regions generally show lower incidence and prevalence, while under-resourced settings face larger prevention and treatment gaps.<a class="cite" href="#ref7">7</a></p></div>
        <div class="card"><h3>Time</h3><p>Rates have been relatively stable over the past decade, but the total number of affected people is expected to grow as populations age.<a class="cite" href="#ref7">7</a> The disease therefore represents a persistent chronic burden rather than a short-lived outbreak.</p></div>
      </div>

      <div class="chart-grid">
        <div class="chart-card">
          <h4>Age pattern of burden</h4>
          <p class="small">Relative pattern showing incidence peaking in midlife and prevalence or disability burden peaking later.<a class="cite" href="#ref7">7</a></p>
          <div class="vbars" aria-label="Relative age pattern chart">
            <div class="vbar-col"><div class="vbar vbar-lite" style="height: 58px;"></div><div class="vbar-label">15 to 24</div></div>
            <div class="vbar-col"><div class="vbar vbar-lite" style="height: 88px;"></div><div class="vbar-label">25 to 34</div></div>
            <div class="vbar-col"><div class="vbar" style="height: 132px;"></div><div class="vbar-label">35 to 44</div></div>
            <div class="vbar-col"><div class="vbar" style="height: 178px;"></div><div class="vbar-label">45 to 49</div></div>
            <div class="vbar-col"><div class="vbar" style="height: 202px;"></div><div class="vbar-label">55 to 59</div></div>
            <div class="vbar-col"><div class="vbar vbar-lite" style="height: 168px;"></div><div class="vbar-label">65 to 74</div></div>
          </div>
          <p class="chart-note">Designed to show the pattern described in the global burden analysis rather than exact age-specific rates.</p>
        </div>

        <div class="chart-card">
          <h4>Burden across SDI groups</h4>
          <p class="small">Lower and low-middle SDI groups carry the greatest burden, while high SDI regions show lower rates.<a class="cite" href="#ref7">7</a></p>
          <div class="vbars" aria-label="Relative burden by SDI chart">
            <div class="vbar-col"><div class="vbar" style="height: 208px;"></div><div class="vbar-label">Low SDI</div></div>
            <div class="vbar-col"><div class="vbar" style="height: 190px;"></div><div class="vbar-label">Low-middle</div></div>
            <div class="vbar-col"><div class="vbar vbar-lite" style="height: 142px;"></div><div class="vbar-label">Middle</div></div>
            <div class="vbar-col"><div class="vbar vbar-lite" style="height: 104px;"></div><div class="vbar-label">High-middle</div></div>
            <div class="vbar-col"><div class="vbar vbar-lite" style="height: 74px;"></div><div class="vbar-label">High SDI</div></div>
          </div>
          <p class="chart-note">This chart supports the equity interpretation in the burden section.</p>
        </div>

        <div class="chart-card">
          <h4>Long-term burden trend</h4>
          <p class="small">Illustrative trend showing a persistently high burden from 1990 to 2021 with relative stability in recent years.<a class="cite" href="#ref7">7</a></p>
          <div class="line-chart">
            <svg viewBox="0 0 320 220" width="100%" height="220" role="img" aria-label="Long-term burden trend chart">
              <line x1="42" y1="20" x2="42" y2="186" stroke="#cbd5e1" stroke-width="2" />
              <line x1="42" y1="186" x2="300" y2="186" stroke="#cbd5e1" stroke-width="2" />
              <line x1="42" y1="54" x2="300" y2="54" stroke="#eef2f7" stroke-width="1" />
              <line x1="42" y1="96" x2="300" y2="96" stroke="#eef2f7" stroke-width="1" />
              <line x1="42" y1="138" x2="300" y2="138" stroke="#eef2f7" stroke-width="1" />
              <polyline points="42,154 86,144 130,132 174,118 218,108 260,102 300,100" fill="none" stroke="#0b5fa8" stroke-width="4" stroke-linecap="round" stroke-linejoin="round" />
              <polyline points="42,164 86,150 130,136 174,120 218,108 260,104 300,103" fill="none" stroke="#0f766e" stroke-width="4" stroke-linecap="round" stroke-linejoin="round" opacity=".78" />
              <circle cx="42" cy="154" r="4" fill="#0b5fa8" />
              <circle cx="86" cy="144" r="4" fill="#0b5fa8" />
              <circle cx="130" cy="132" r="4" fill="#0b5fa8" />
              <circle cx="174" cy="118" r="4" fill="#0b5fa8" />
              <circle cx="218" cy="108" r="4" fill="#0b5fa8" />
              <circle cx="260" cy="102" r="4" fill="#0b5fa8" />
              <circle cx="300" cy="100" r="4" fill="#0b5fa8" />
              <text x="36" y="202" font-size="12" fill="#64748b">1990</text>
              <text x="110" y="202" font-size="12" fill="#64748b">2000</text>
              <text x="184" y="202" font-size="12" fill="#64748b">2010</text>
              <text x="278" y="202" font-size="12" fill="#64748b">2021</text>
              <text x="12" y="58" font-size="11" fill="#64748b">High</text>
              <text x="10" y="182" font-size="11" fill="#64748b">Low</text>
            </svg>
          </div>
          <div class="chart-legend">
            <span class="legend-item"><span class="legend-swatch"></span>Estimated prevalence burden</span>
            <span class="legend-item"><span class="legend-swatch alt"></span>Estimated disability burden</span>
          </div>
        </div>
      </div>

      <div class="card" style="margin-top:18px;">
        <h3>Core measures</h3>
        <div class="table-wrap">
          <table>
            <thead>
              <tr><th>Measure</th><th>2021 value</th><th>Interpretation</th><th>Notes</th></tr>
            </thead>
            <tbody>
              <tr><td>Prevalence</td><td>1,066,953,744 cases<br>12,498 per 100,000</td><td>Very high global burden of existing disease<a class="cite" href="#ref7">7</a></td><td>Reflects cumulative chronic disease and aging populations</td></tr>
              <tr><td>Incidence</td><td>89,613,534 new cases<br>1,069 per 100,000</td><td>Substantial ongoing emergence of disease<a class="cite" href="#ref7">7</a></td><td>Incident burden peaks earlier than prevalence burden</td></tr>
              <tr><td>Disability-adjusted life years (DALYs)</td><td>About 6.9 million</td><td>Large disability burden at the population level<a class="cite" href="#ref7">7</a></td><td>Driven almost entirely by years lived with disability rather than premature death</td></tr>
              <tr><td>Years of potential life lost (YPLL)</td><td>Not routinely emphasized</td><td>Periodontitis is usually not modeled as a direct fatal disease</td><td>This is a better choice than presenting a large YPLL figure without a clear direct mortality basis</td></tr>
              <tr><td>Mortality rate</td><td>Minimal direct mortality</td><td>Public health importance comes from disability, tooth loss, and quality-of-life effects</td><td>Also relevant because periodontal disease clusters with systemic risk and chronic inflammation</td></tr>
            </tbody>
          </table>
        </div>
      </div>

      <div class="grid-2" style="margin-top:18px;">
        <div class="card">
          <h3>Inequities and priority populations</h3>
          <ul>
            <li>People in low and middle Socio-Demographic Index (SDI) settings with reduced preventive dental access</li>
            <li>Older adults with accumulated exposure and delayed diagnosis</li>
            <li>Current smokers and people exposed to tobacco environments</li>
            <li>People with diabetes, especially when glycemic control is poor</li>
            <li>Groups with low income, limited insurance, transportation barriers, or lower health literacy</li>
          </ul>
        </div>
        <div class="card">
          <h3>Visual summary of burden pattern</h3>
          <div class="bars">
            <div class="bar-row"><div class="bar-label"><span>Lower SDI regions</span><strong>Highest burden</strong></div><div class="bar-track"><div class="bar-fill" style="width: 92%;"></div></div></div>
            <div class="bar-row"><div class="bar-label"><span>Middle SDI regions</span><strong>Moderately high</strong></div><div class="bar-track"><div class="bar-fill" style="width: 74%;"></div></div></div>
            <div class="bar-row"><div class="bar-label"><span>High SDI regions</span><strong>Lower burden</strong></div><div class="bar-track"><div class="bar-fill" style="width: 42%;"></div></div></div>
            <div class="bar-row"><div class="bar-label"><span>Adults 55 to 59</span><strong>Peak prevalence</strong></div><div class="bar-track"><div class="bar-fill" style="width: 88%;"></div></div></div>
          </div>
          <p class="small" style="margin-top:14px;">This simplified graphic is meant to communicate the relative pattern described in the literature rather than provide exact between-region counts.</p>
        </div>
      </div>
    </section>

    <section id="history">
      <div class="section-head">
        <div>
          <div class="pill">Objective 3</div>
          <h2>Natural history and progression</h2>
          <p>Stages, progression data, intervention windows, and equity implications.</p>
        </div>
      </div>

      <div class="grid-2">
        <div class="card">
          <h3>Stages of disease</h3>
          <div class="timeline">
            <div class="step"><strong>Pre-clinical phase</strong><p>Plaque accumulation leads to gingival inflammation. Bleeding may appear before clinically important attachment loss or radiographic bone loss becomes obvious.</p></div>
            <div class="step"><strong>Early symptomatic disease</strong><p>Red or swollen gums, bleeding on brushing or probing, halitosis, recession, and early pocketing may appear. This is often where screening can still prevent major destruction.</p></div>
            <div class="step"><strong>Established periodontitis</strong><p>Progressive attachment loss and alveolar bone loss become evident. Stages I and II reflect earlier destruction, while Stages III and IV represent severe disease and functional consequences.</p></div>
            <div class="step"><strong>Complications and advanced outcomes</strong><p>Tooth mobility, chewing difficulty, recurrent inflammation, tooth loss, and substantial quality-of-life effects emerge in advanced disease.</p></div>
          </div>
        </div>
        <div class="card">
          <h3>Progression data and interpretation</h3>
          <p>Progression is not perfectly linear. Many sites remain stable for periods of time, while others worsen depending on smoking, glycemic control, oral hygiene, and maintenance care. One progression study reported that only about 3 percent of healthy sites developed chronic periodontitis within 2 years, but risk rose in higher-risk groups.</p>
          <p>Population-level data support this pattern. In U.S. adults age 30 years and older, current smokers had markedly higher periodontitis prevalence, and adults age 65 years and older had especially high levels of moderate and severe disease.<a class="cite" href="#ref8">8</a><a class="cite" href="#ref9">9</a><a class="cite" href="#ref11">11</a> Together, these findings suggest cumulative exposure plus modifiable risk factors shape both progression and severity.</p>
          <div class="callout small">Best intervention point: before or during the earliest attachment loss stage, when behavior change, professional cleaning, and systematic maintenance still have a high chance of preventing long-term damage.</div>
        </div>
      </div>

      <div class="grid-3" style="margin-top:18px;">
        <div class="card"><h3>Window 1</h3><p><strong>Before attachment loss</strong><br>Daily plaque control, smoking prevention, diabetes optimization, and routine prophylactic care.</p></div>
        <div class="card"><h3>Window 2</h3><p><strong>At early periodontitis</strong><br>Periodontal probing, radiographs when indicated, scaling and root planing, and structured risk counseling.<a class="cite" href="#ref12">12</a></p></div>
        <div class="card"><h3>Window 3</h3><p><strong>After established disease</strong><br>Supportive periodontal therapy, periodontal reevaluation, retreatment of recurrent sites, and preservation of function.</p></div>
      </div>

      <div class="card" style="margin-top:18px;">
        <h3>Equity considerations in progression</h3>
        <p>Late presentation and worse progression are not purely biologic. Patients with lower socioeconomic status, limited dental coverage, transportation barriers, and lower oral health literacy are more likely to miss the preventive window and enter care only after bone loss or tooth mobility has begun. This means the natural history of the disease is partly shaped by structural barriers. Populations with diabetes and tobacco exposure carry additional risk on top of these barriers, making progression both a clinical and equity issue.</p>
      </div>
    </section>

    <section id="prevention">
      <div class="section-head">
        <div>
          <div class="pill">Objective 4</div>
          <h2>Interventions and prevention</h2>
          <p>Primary, secondary, and tertiary prevention with attention to effectiveness and equity.</p>
        </div>
      </div>

      <div class="grid-3">
        <div class="card"><h3>Primary prevention</h3><p>Prevent disease before irreversible attachment loss occurs through daily plaque control, regular professional cleanings, tobacco avoidance, and improved control of diabetes and related risk factors. Because gingivitis is reversible, this is the most efficient public health stage for intervention.</p></div>
        <div class="card"><h3>Secondary prevention</h3><p>Detect disease early using periodontal probing, bleeding assessment, risk review, and radiographs when indicated. Education, plaque control coaching, and early nonsurgical therapy can limit major tissue destruction.</p></div>
        <div class="card"><h3>Tertiary prevention</h3><p>Preserve teeth and function after established disease with scaling and root planing, supportive periodontal therapy, surgery when necessary, and long-term maintenance to reduce recurrence and tooth loss.<a class="cite" href="#ref12">12</a></p></div>
      </div>

      <div class="grid-2" style="margin-top:18px;">
        <div class="card"><h3>What works best in practice</h3><ul><li>Repeated maintenance and follow-up matter because periodontitis is chronic and relapse-prone.</li><li>Smoking cessation support and diabetes management improve outcomes beyond dental treatment alone.</li><li>Prevention succeeds most when self-care expectations are paired with realistic access to cleanings, evaluation, and affordable treatment.</li></ul></div>
        <div class="card"><h3>Why prevention still fails</h3><ul><li>Early disease may be painless, so patients delay care.</li><li>Cost barriers reduce routine dental visits and maintenance adherence.</li><li>Behavioral advice alone is less effective when patients lack insurance, transportation, or time off work.</li><li>High-risk patients such as smokers or adults with uncontrolled diabetes need more intensive support than standard messaging provides.</li></ul></div>
      </div>
    </section>

    <section id="policy">
      <div class="section-head">
        <div>
          <div class="pill">Objective 5</div>
          <h2>Policy recommendations and equity</h2>
          <p>Evidence-based proposals tied to prevention, access, and structural inequities.</p>
        </div>
      </div>

      <div class="grid-3">
        <div class="policy"><div class="sub">Policy 1</div><h3>Expand adult dental coverage and preventive benefits</h3><p>Coverage for routine cleanings, periodontal screening, and early nonsurgical therapy should be strengthened so patients are not forced to wait until disease becomes destructive and more expensive to treat.<a class="cite" href="#ref12">12</a><a class="cite" href="#ref13">13</a></p></div>
        <div class="policy"><div class="sub">Policy 2</div><h3>Integrate periodontal risk screening into diabetes and primary care pathways</h3><p>Because diabetes is a major determinant of periodontitis severity, screening and referral pathways should be built into chronic disease management rather than leaving oral health isolated from the rest of healthcare.<a class="cite" href="#ref6">6</a><a class="cite" href="#ref11">11</a></p></div>
        <div class="policy"><div class="sub">Policy 3</div><h3>Target underserved communities with community-based dental access</h3><p>Mobile clinics, school and community education, and support for safety-net dental systems can reduce geographic and financial barriers in low-access populations.</p></div>
      </div>

      <div class="grid-2" style="margin-top:18px;">
        <div class="policy"><div class="sub">Policy 4</div><h3>Pair oral health policy with tobacco control and cessation support</h3><p>Smoking is a powerful modifiable risk factor. Policy should go beyond warning messages and connect periodontal prevention programs with cessation counseling, pharmacologic support, and high-risk patient outreach.<a class="cite" href="#ref6">6</a><a class="cite" href="#ref11">11</a></p></div>
        <div class="policy"><div class="sub">Policy 5</div><h3>Design policy around equity, not just individual behavior</h3><p>Educational campaigns alone often benefit people who already have access to care. Equity-focused policy must address affordability, transportation, language access, health literacy, and community-specific barriers to sustained prevention.</p></div>
      </div>

      <div class="card" style="margin-top:18px;">
        <h3>Evidence-based justification</h3>
        <p>The policy case is strong because chronic periodontitis has a very large global prevalence burden, predictable risk clustering, and meaningful opportunities for prevention before irreversible destruction occurs. The epidemiology supports targeting smokers, older adults, people with diabetes, and lower-access populations. The literature also shows that disease progression is shaped not just by plaque biology but by whether patients can obtain screening, follow-up, and maintenance. That is why the most defensible recommendations combine prevention, treatment access, and structural equity rather than focusing on personal responsibility alone.</p>
      </div>
    </section>

    <section id="methods">
      <div class="section-head">
        <div>
          <div class="pill">Methods</div>
          <h2>Methods</h2>
        </div>
      </div>

      <div class="grid-2">
        <div class="card">
          <h3>Primary data sources and timeframe</h3>
          <ul>
            <li>Global burden estimates from a 1990 to 2021 analysis with projections to 2050</li>
            <li>Centers for Disease Control and Prevention (CDC) and National Institute of Dental and Craniofacial Research (NIDCR) materials for U.S. burden, risk, and oral health equity framing</li>
            <li>Clinical and consensus sources for staging, grading, and prevention strategies</li>
            <li>Systematic review evidence for vitamin D and periodontal disease association</li>
          </ul>
        </div>
        <div class="card">
          <h3>Definitions and limitations</h3>
          <ul>
            <li>Prevalence is the number of existing cases and incidence is the number of new cases in a defined period.</li>
            <li>DALY estimates for periodontitis are largely driven by years lived with disability rather than years of life lost.</li>
            <li>Cross-country estimates depend on data quality and may be less stable in lower-resource settings.</li>
            <li>Some determinants, such as vitamin D deficiency or alcohol use, are better treated as contributory and context dependent rather than universally dominant drivers.</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="references" class="refs">
      <div class="section-head">
        <div>
          <div class="pill">References</div>
          <h2>Selected sources</h2>
          <p>Formatted in an AMA-style list with live links.</p>
        </div>
      </div>
      <div class="card">
        <ol>
          <li id="ref1">Centers for Disease Control and Prevention. Gum (periodontal) disease. Updated May 15, 2024. <a href="https://www.cdc.gov/oral-health/about/gum-periodontal-disease.html" target="_blank">https://www.cdc.gov/oral-health/about/gum-periodontal-disease.html</a><a class="backref" href="#summary">↩</a></li>
          <li id="ref2">Nazir MA. Chronic periodontitis. In: StatPearls. StatPearls Publishing. Updated July 24, 2024. <a href="https://www.ncbi.nlm.nih.gov/books/NBK554590/" target="_blank">https://www.ncbi.nlm.nih.gov/books/NBK554590/</a><a class="backref" href="#summary">↩</a></li>
          <li id="ref3">Papapanou PN, Sanz M, Buduneli N, et al. Periodontitis: Consensus report of workgroup 2 of the 2017 World Workshop on the Classification of Periodontal and Peri-Implant Diseases and Conditions. J Periodontol. 2018;89(suppl 1):S173-S182. <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC6122115/" target="_blank">https://pmc.ncbi.nlm.nih.gov/articles/PMC6122115/</a><a class="backref" href="#etiology">↩</a></li>
          <li id="ref4">Kinane DF, Attström R. Advances in the pathogenesis of periodontitis. J Clin Periodontol. 2005;32(suppl 6):130-137. <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC1351013/" target="_blank">https://pmc.ncbi.nlm.nih.gov/articles/PMC1351013/</a><a class="backref" href="#etiology">↩</a></li>
          <li id="ref5">Machado V, Botelho J, Proença L, et al. Vitamin D and periodontitis: A systematic review and meta-analysis. Nutrients. 2020;12(8):2177. <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC7468917/" target="_blank">https://pmc.ncbi.nlm.nih.gov/articles/PMC7468917/</a><a class="backref" href="#etiology">↩</a></li>
          <li id="ref6">American Academy of Periodontology. Gum disease risk factors. <a href="https://www.perio.org/for-patients/gum-disease-information/gum-disease-risk-factors/" target="_blank">https://www.perio.org/for-patients/gum-disease-information/gum-disease-risk-factors/</a><a class="backref" href="#policy">↩</a></li>
          <li id="ref7">Feng Y, Xiao L, Fu LL, et al. Global, regional and national burden of edentulism and periodontal diseases from 1990 to 2021: analysis of risk factors and prediction of trends in 2050. In Vivo. <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC11884469/" target="_blank">https://pmc.ncbi.nlm.nih.gov/articles/PMC11884469/</a><a class="backref" href="#burden">↩</a></li>
          <li id="ref8">Mdala I, Olsen I, Haffajee AD, Socransky SS, Thoresen M, de Blasio BF. Multistate Markov models for periodontal disease progression in sites with known initial status. BMC Oral Health. 2014. <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC4139458/" target="_blank">https://pmc.ncbi.nlm.nih.gov/articles/PMC4139458/</a><a class="backref" href="#history">↩</a></li>
          <li id="ref9">National Institute of Dental and Craniofacial Research. Periodontal disease in adults. <a href="https://www.nidcr.nih.gov/research/data-statistics/periodontal-disease/adults" target="_blank">https://www.nidcr.nih.gov/research/data-statistics/periodontal-disease/adults</a><a class="backref" href="#history">↩</a></li>
          <li id="ref10">Centers for Disease Control and Prevention. Oral health equity. <a href="https://www.cdc.gov/oral-health/health-equity/index.html" target="_blank">https://www.cdc.gov/oral-health/health-equity/index.html</a><a class="backref" href="#summary">↩</a></li>
          <li id="ref11">Eke PI, Thornton-Evans GO, Wei L, Borgnakke WS, Dye BA, Genco RJ. Periodontitis in US adults: National Health and Nutrition Examination Survey 2009 to 2014. Published 2021. <a href="https://stacks.cdc.gov/view/cdc/105956" target="_blank">https://stacks.cdc.gov/view/cdc/105956</a><a class="backref" href="#history">↩</a></li>
          <li id="ref12">European Federation of Periodontology. S3 level clinical practice guideline for the treatment of stage I to III periodontitis. <a href="https://www.efp.org/education/continuing-education/clinical-guidelines/guideline-on-treatment-of-stage-i-iii-periodontitis/" target="_blank">https://www.efp.org/education/continuing-education/clinical-guidelines/guideline-on-treatment-of-stage-i-iii-periodontitis/</a><a class="backref" href="#prevention">↩</a></li>
          <li id="ref13">World Health Organization. Oral health fact sheet. <a href="https://www.who.int/news-room/fact-sheets/detail/oral-health" target="_blank">https://www.who.int/news-room/fact-sheets/detail/oral-health</a><a class="backref" href="#policy">↩</a></li>
          <li id="ref14">Cleveland Clinic. Gum (periodontal) disease. Reviewed September 6, 2023. <a href="https://my.clevelandclinic.org/health/diseases/21482-gum-periodontal-disease" target="_blank">https://my.clevelandclinic.org/health/diseases/21482-gum-periodontal-disease</a><a class="backref" href="#summary">↩</a></li>
        </ol>
      </div>
    </section>

    <footer>
      <div class="shell" style="width:100%; padding:0;">
        
      </div>
    </footer>
  </main>
</body>
</html>
