<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CRIS — Coal Resource Intelligence System</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700;900&family=DM+Sans:wght@300;400;500&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --coal: #1a1a2e;
    --deep: #16213e;
    --purple: #7B2D8B;
    --purple-light: #a855f7;
    --gold: #f59e0b;
    --gold-light: #fcd34d;
    --white: #f8f7f4;
    --muted: #a0a0b8;
    --card-bg: rgba(255,255,255,0.04);
    --border: rgba(255,255,255,0.08);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: var(--coal);
    color: var(--white);
    font-family: 'DM Sans', sans-serif;
    min-height: 100vh;
    overflow-x: hidden;
  }

  /* Background pattern */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background:
      radial-gradient(ellipse 80% 50% at 20% 20%, rgba(123,45,139,0.15) 0%, transparent 60%),
      radial-gradient(ellipse 60% 40% at 80% 80%, rgba(245,158,11,0.08) 0%, transparent 60%);
    pointer-events: none;
    z-index: 0;
  }

  .container {
    max-width: 860px;
    margin: 0 auto;
    padding: 0 2rem 4rem;
    position: relative;
    z-index: 1;
  }

  /* Hero */
  .hero {
    padding: 5rem 0 3rem;
    border-bottom: 1px solid var(--border);
    margin-bottom: 3rem;
  }

  .badge {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    background: rgba(123,45,139,0.2);
    border: 1px solid rgba(168,85,247,0.3);
    color: var(--purple-light);
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    letter-spacing: 2px;
    text-transform: uppercase;
    padding: 6px 14px;
    border-radius: 100px;
    margin-bottom: 2rem;
    animation: fadeUp 0.6s ease both;
  }

  .hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(2.4rem, 6vw, 4rem);
    font-weight: 900;
    line-height: 1.1;
    letter-spacing: -1px;
    margin-bottom: 1rem;
    animation: fadeUp 0.7s ease 0.1s both;
  }

  .hero h1 span {
    background: linear-gradient(135deg, var(--gold), var(--gold-light));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .hero p {
    font-size: 1.1rem;
    color: var(--muted);
    font-weight: 300;
    max-width: 520px;
    line-height: 1.7;
    animation: fadeUp 0.7s ease 0.2s both;
  }

  /* Stats row */
  .stats-row {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1px;
    background: var(--border);
    border: 1px solid var(--border);
    border-radius: 16px;
    overflow: hidden;
    margin-bottom: 3rem;
    animation: fadeUp 0.7s ease 0.3s both;
  }

  .stat {
    background: var(--card-bg);
    padding: 1.5rem;
    text-align: center;
    backdrop-filter: blur(10px);
  }

  .stat-num {
    font-family: 'Playfair Display', serif;
    font-size: 2rem;
    font-weight: 700;
    color: var(--gold);
    display: block;
    margin-bottom: 4px;
  }

  .stat-label {
    font-size: 11px;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    color: var(--muted);
    font-family: 'DM Mono', monospace;
  }

  /* Section */
  section {
    margin-bottom: 2.5rem;
    animation: fadeUp 0.7s ease 0.4s both;
  }

  .section-label {
    font-family: 'DM Mono', monospace;
    font-size: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: var(--purple-light);
    margin-bottom: 1rem;
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .section-label::after {
    content: '';
    flex: 1;
    height: 1px;
    background: var(--border);
  }

  h2 {
    font-family: 'Playfair Display', serif;
    font-size: 1.6rem;
    font-weight: 700;
    margin-bottom: 1.2rem;
    color: var(--white);
  }

  /* Team card */
  .team-card {
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: 16px;
    padding: 1.5rem;
    display: flex;
    align-items: center;
    gap: 1rem;
    backdrop-filter: blur(10px);
    transition: border-color 0.2s;
  }

  .team-card:hover { border-color: rgba(168,85,247,0.4); }

  .avatar {
    width: 52px;
    height: 52px;
    border-radius: 50%;
    background: linear-gradient(135deg, var(--purple), var(--purple-light));
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: 'Playfair Display', serif;
    font-size: 1.2rem;
    font-weight: 700;
    flex-shrink: 0;
  }

  .team-info strong {
    display: block;
    font-size: 1rem;
    font-weight: 500;
    margin-bottom: 2px;
  }

  .team-info span {
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    color: var(--muted);
  }

  /* Dataset cards */
  .dataset-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 12px;
  }

  .dataset-card {
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 1.2rem;
    backdrop-filter: blur(10px);
    transition: all 0.2s;
    position: relative;
    overflow: hidden;
  }

  .dataset-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, var(--purple), var(--purple-light));
  }

  .dataset-card:hover {
    border-color: rgba(168,85,247,0.3);
    transform: translateY(-2px);
  }

  .dataset-icon {
    font-size: 1.4rem;
    margin-bottom: 8px;
    display: block;
  }

  .dataset-card h4 {
    font-size: 0.85rem;
    font-weight: 500;
    margin-bottom: 4px;
    line-height: 1.3;
  }

  .dataset-card p {
    font-size: 11px;
    color: var(--muted);
    font-family: 'DM Mono', monospace;
  }

  /* Pages */
  .pages-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
  }

  .page-card {
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 1.2rem 1.4rem;
    display: flex;
    align-items: flex-start;
    gap: 14px;
    backdrop-filter: blur(10px);
    transition: all 0.2s;
  }

  .page-card:hover {
    border-color: rgba(245,158,11,0.3);
    transform: translateY(-2px);
  }

  .page-num {
    font-family: 'Playfair Display', serif;
    font-size: 2rem;
    font-weight: 900;
    color: rgba(245,158,11,0.2);
    line-height: 1;
    flex-shrink: 0;
    width: 36px;
  }

  .page-info h4 {
    font-size: 0.9rem;
    font-weight: 500;
    margin-bottom: 6px;
  }

  .page-info ul {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 3px;
  }

  .page-info ul li {
    font-size: 11px;
    color: var(--muted);
    display: flex;
    align-items: center;
    gap: 6px;
  }

  .page-info ul li::before {
    content: '—';
    color: var(--purple-light);
    font-size: 10px;
  }

  /* KPIs */
  .kpi-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 10px;
  }

  .kpi-item {
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 1rem 1.2rem;
    display: flex;
    align-items: center;
    gap: 12px;
    backdrop-filter: blur(10px);
    transition: border-color 0.2s;
  }

  .kpi-item:hover { border-color: rgba(245,158,11,0.3); }

  .kpi-dot {
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: var(--gold);
    flex-shrink: 0;
    box-shadow: 0 0 8px var(--gold);
  }

  .kpi-item span {
    font-size: 0.85rem;
    font-weight: 400;
  }

  /* Source tag */
  .source-tag {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    background: rgba(245,158,11,0.1);
    border: 1px solid rgba(245,158,11,0.2);
    color: var(--gold-light);
    font-family: 'DM Mono', monospace;
    font-size: 11px;
    padding: 6px 12px;
    border-radius: 6px;
    margin-top: 1rem;
  }

  /* Footer */
  footer {
    border-top: 1px solid var(--border);
    padding-top: 2rem;
    margin-top: 3rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 1rem;
  }

  footer p {
    font-size: 12px;
    color: var(--muted);
    font-family: 'DM Mono', monospace;
  }

  .tech-stack {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
  }

  .tech-pill {
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: 100px;
    padding: 4px 12px;
    font-size: 11px;
    font-family: 'DM Mono', monospace;
    color: var(--muted);
  }

  /* Live Links */
  .links-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
  }

  .link-card {
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 1.2rem 1.4rem;
    display: flex;
    align-items: center;
    gap: 14px;
    text-decoration: none;
    color: var(--white);
    backdrop-filter: blur(10px);
    transition: all 0.25s;
    position: relative;
    overflow: hidden;
  }

  .link-card::before {
    content: '';
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, rgba(123,45,139,0.15), rgba(245,158,11,0.05));
    opacity: 0;
    transition: opacity 0.25s;
  }

  .link-card:hover {
    border-color: rgba(245,158,11,0.5);
    transform: translateY(-3px);
    box-shadow: 0 12px 30px rgba(0,0,0,0.3);
  }

  .link-card:hover::before { opacity: 1; }

  .link-icon {
    font-size: 1.6rem;
    flex-shrink: 0;
    position: relative;
    z-index: 1;
  }

  .link-info {
    flex: 1;
    position: relative;
    z-index: 1;
  }

  .link-info h4 {
    font-size: 0.9rem;
    font-weight: 500;
    margin-bottom: 3px;
  }

  .link-info span {
    font-family: 'DM Mono', monospace;
    font-size: 10px;
    color: var(--muted);
    letter-spacing: 0.5px;
  }

  .link-arrow {
    font-size: 1.1rem;
    color: var(--gold);
    flex-shrink: 0;
    position: relative;
    z-index: 1;
    transition: transform 0.2s;
  }

  .link-card:hover .link-arrow {
    transform: translate(3px, -3px);
  }

  /* Animations */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  /* Divider */
  hr {
    border: none;
    border-top: 1px solid var(--border);
    margin: 2rem 0;
  }
</style>
</head>
<body>
<div class="container">

  <!-- Hero -->
  <div class="hero">
    <div class="badge">⬡ DABI Practical 10</div>
    <h1>Coal Resource<br><span>Intelligence System</span></h1>
    <p>A Power BI dashboard analyzing coal reserves, supply, and consumption patterns across Indian states using official NDAP datasets.</p>
  </div>

  <!-- Stats -->
  <div class="stats-row">
    <div class="stat">
      <span class="stat-num">3</span>
      <span class="stat-label">Datasets</span>
    </div>
    <div class="stat">
      <span class="stat-num">4</span>
      <span class="stat-label">Dashboard Pages</span>
    </div>
    <div class="stat">
      <span class="stat-num">7</span>
      <span class="stat-label">KPI Measures</span>
    </div>
  </div>

  <!-- Team -->
  <section>
    <div class="section-label">Team Member</div>
    <div class="team-card">
      <div class="avatar">TS</div>
      <div class="team-info">
        <strong>Tanu Sharma</strong>
        <span>Roll No. 161 &nbsp;·&nbsp; DABI Practical 10</span>
      </div>
    </div>
  </section>

  <!-- Datasets -->
  <section>
    <div class="section-label">Datasets</div>
    <div class="dataset-grid">
      <div class="dataset-card">
        <span class="dataset-icon">📊</span>
        <h4>Coal Consumption</h4>
        <p>2006 – 2020 · 2988 rows</p>
      </div>
      <div class="dataset-card">
        <span class="dataset-icon">🏭</span>
        <h4>Coal Supply by State</h4>
        <p>2006 – 2020 · 830 rows</p>
      </div>
      <div class="dataset-card">
        <span class="dataset-icon">⛏️</span>
        <h4>Coal Reserves by State</h4>
        <p>2021 · 5417 rows</p>
      </div>
    </div>
    <div class="source-tag">
      ◆ Source — NDAP · Ministry of Coal · Government of India
    </div>
  </section>

  <!-- Dashboard Pages -->
  <section>
    <div class="section-label">Dashboard Pages</div>
    <div class="pages-grid">
      <div class="page-card">
        <div class="page-num">01</div>
        <div class="page-info">
          <h4>Executive Summary</h4>
          <ul>
            <li>4 KPI Cards</li>
            <li>Consumption trend line chart</li>
            <li>India state map visual</li>
            <li>Year slicer</li>
          </ul>
        </div>
      </div>
      <div class="page-card">
        <div class="page-num">02</div>
        <div class="page-info">
          <h4>Consumption Analysis</h4>
          <ul>
            <li>Stacked bar by sector</li>
            <li>Top consuming states</li>
            <li>Donut chart by sector</li>
            <li>Coal type slicer</li>
          </ul>
        </div>
      </div>
      <div class="page-card">
        <div class="page-num">03</div>
        <div class="page-info">
          <h4>Supply Analysis</h4>
          <ul>
            <li>CIL / Private / Other bars</li>
            <li>60 companies table</li>
            <li>Coal type pie chart</li>
            <li>Supply trend by year</li>
          </ul>
        </div>
      </div>
      <div class="page-card">
        <div class="page-num">04</div>
        <div class="page-info">
          <h4>Reserves & Sustainability</h4>
          <ul>
            <li>129 coal fields stacked bar</li>
            <li>Depletion index gauge</li>
            <li>Reserves by depth bar</li>
            <li>State → field treemap</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- KPIs -->
  <section>
    <div class="section-label">KPI Measures</div>
    <div class="kpi-grid">
      <div class="kpi-item">
        <div class="kpi-dot"></div>
        <span>Total Coal Consumption</span>
      </div>
      <div class="kpi-item">
        <div class="kpi-dot"></div>
        <span>Total Coal Supplied</span>
      </div>
      <div class="kpi-item">
        <div class="kpi-dot"></div>
        <span>Supply to Consumption Ratio</span>
      </div>
      <div class="kpi-item">
        <div class="kpi-dot"></div>
        <span>Depletion Index</span>
      </div>
      <div class="kpi-item">
        <div class="kpi-dot"></div>
        <span>Company Yield %</span>
      </div>
      <div class="kpi-item">
        <div class="kpi-dot"></div>
        <span>Average Depth Factor</span>
      </div>
      <div class="kpi-item" style="grid-column: 1 / -1;">
        <div class="kpi-dot"></div>
        <span>Total Reserves (Million Tonnes)</span>
      </div>
    </div>
  </section>

  <!-- Live Links -->
  <section>
    <div class="section-label">Live Dashboard</div>
    <div class="links-grid">
      <a href="https://app.powerbi.com/groups/me/reports/929cf054-7ca0-4eff-883f-c18b2e4d567e/c3444fd79967033038c9?experience=power-bi" target="_blank" class="link-card">
        <div class="link-icon">📊</div>
        <div class="link-info">
          <h4>Reserves & Sustainability</h4>
          <span>CRIS · Power BI Report</span>
        </div>
        <div class="link-arrow">↗</div>
      </a>
      <a href="https://app.powerbi.com/groups/me/insights/7cb3825d-c8df-429b-8ce5-9532d795ca57?insightsSource=Desktop&experience=power-bi" target="_blank" class="link-card">
        <div class="link-icon">⚡</div>
        <div class="link-info">
          <h4>Power BI Insights</h4>
          <span>CRIS · Live Dashboard</span>
        </div>
        <div class="link-arrow">↗</div>
      </a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2026 · CRIS Dashboard · DABI Practical 10</p>
    <div class="tech-stack">
      <span class="tech-pill">Power BI</span>
      <span class="tech-pill">DAX</span>
      <span class="tech-pill">Power Query</span>
      <span class="tech-pill">NDAP Data</span>
    </div>
  </footer>

</div>
</body>
</html>
