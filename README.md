<!--
  Professional single-file HTML portfolio suitable for GitHub README (or as index.html)
  - Replace placeholders (NAME, BIO, contact links, project entries) with your info
  - You can paste this into README.md as HTML or host it as index.html
-->
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Momen Al-Ali — GitHub Profile (index.html)</title>
  <style>
    /* Simple, self-contained styles for index.html preview (works in browser and GitHub Pages) */
    :root{--bg:#07111a;--card:#0b1420;--muted:#98a1b3;--accent:#06b6d4}
    *{box-sizing:border-box}
    body{margin:0;font-family:system-ui,Arial,Helvetica,sans-serif;background:linear-gradient(180deg,#04111a,#071724);color:#e6eef6}
    .wrap{max-width:880px;margin:28px auto;padding:22px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:12px;padding:22px;box-shadow:0 8px 30px rgba(2,6,23,0.6)}
    header{display:flex;gap:16px;align-items:center}
    .photo{width:96px;height:96px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;font-weight:800;font-size:28px;color:#02121a}
    h1{margin:0;font-size:24px}
    .muted{color:var(--muted)}
    .section{margin-top:18px}
    .skills{display:flex;flex-wrap:wrap;gap:12px;margin-top:12px}
    .skill{width:140px;height:110px;border-radius:10px;background:rgba(255,255,255,0.02);padding:10px;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center}
    .skill strong{font-size:16px}
    .timeline{margin-top:8px;border-left:3px solid rgba(255,255,255,0.03);padding-left:14px}
    .exp{margin-bottom:14px;padding-left:8px}
    .exp h4{margin:4px 0}
    footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px}
    .note{background:#0a1620;border-left:4px solid var(--accent);padding:10px;border-radius:8px;color:var(--muted);font-size:13px;margin-bottom:14px}
    @media (max-width:700px){header{flex-direction:column;align-items:flex-start}.skills{justify-content:center}}
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card">
      <div class="note"><strong>Important:</strong> If you paste this HTML into <code>README.md</code>, GitHub will remove CSS styles for security reasons and the preview won't match. To see the styled version use <strong>index.html</strong> hosted via <em>GitHub Pages</em> or open the file in a browser locally. A README-friendly Markdown version is included at the bottom of this file for convenience.</div>

      <header>
        <div class="photo">MA</div>
        <div>
          <h1>Hello — I’m <strong>Momen Al-Ali</strong></h1>
          <div class="muted">Data Analytics Engineer • Warehousing • ETL • Data Pipelines • Dashboards</div>
        </div>
        <div style="margin-left:auto;text-align:right">
          <div style="font-weight:700">Amman, Jordan</div>
          <div class="muted" style="margin-top:6px">momen@example.com</div>
        </div>
      </header>

      <div class="section">
        <h2>About me</h2>
        <p class="muted">I build reliable data warehouses and automated ETL pipelines. I turn messy data into trusted datasets, design semantic models for analytics, and create production-ready dashboards. I have hands-on experience at <strong>Nexus Ville</strong> and <strong>Altibbi</strong>, where I implemented ETL flows and delivered dashboards used by product and operations teams.</p>
      </div>

      <div class="section">
        <h2>Skills & Tech</h2>
        <div class="skills" role="list">
          <div class="skill" role="listitem"><div><strong>Python</strong></div><div class="muted" style="margin-top:6px">pandas, numpy</div></div>
          <div class="skill" role="listitem"><div><strong>SQL</strong></div><div class="muted" style="margin-top:6px">T-SQL, PostgreSQL</div></div>
          <div class="skill" role="listitem"><div><strong>ETL & Airflow</strong></div><div class="muted" style="margin-top:6px">pipelines & scheduling</div></div>
          <div class="skill" role="listitem"><div><strong>Data Warehousing</strong></div><div class="muted" style="margin-top:6px">Star schema & modeling</div></div>
          <div class="skill" role="listitem"><div><strong>Power BI</strong></div><div class="muted" style="margin-top:6px">DAX & reports</div></div>
          <div class="skill" role="listitem"><div><strong>Tableau</strong></div><div class="muted" style="margin-top:6px">viz & prep</div></div>
          <div class="skill" role="listitem"><div><strong>Looker</strong></div><div class="muted" style="margin-top:6px">LookML & explores</div></div>
          <div class="skill" role="listitem"><div><strong>DPT</strong></div><div class="muted" style="margin-top:6px">Data Processing</div></div>
        </div>
      </div>

      <div class="section">
        <h2>Experience</h2>
        <div class="timeline">
          <div class="exp">
            <h4>Data Analytics Engineer — <strong>Nexus Ville</strong></h4>
            <div class="muted">2023 — Present</div>
            <div class="muted">Built ETL pipelines, designed data models, and created operational dashboards that improved reporting speed and data reliability.</div>
          </div>

          <div class="exp">
            <h4>Analytics Specialist — <strong>Altibbi</strong></h4>
            <div class="muted">2021 — 2023</div>
            <div class="muted">Supported healthcare analytics, improved reporting pipelines, and delivered insights used by product and medical teams.</div>
          </div>

          <div class="exp">
            <h4>Certification</h4>
            <div class="muted">Certified Professional Data Analyst — DataCamp</div>
          </div>
        </div>
      </div>

      <footer>
        <div class="muted">Contact: <a href="mailto:momen@example.com" style="color:var(--accent);text-decoration:none">momen@example.com</a> • GitHub: <a href="https://github.com/yourusername" style="color:var(--accent);text-decoration:none">github.com/yourusername</a></div>
        <div style="margin-top:8px;color:var(--muted);font-size:13px">To preview this styled template: save as <code>index.html</code> and open in your browser or enable <em>GitHub Pages</em> for this repository.</div>
      </footer>

      <!--
        README.md (Markdown-friendly) version

        If you want a README.md that displays on your GitHub profile (without hosting), use the Markdown below
        GitHub strips CSS/style tags from README.md, so the styled HTML above won't render there.

        Copy everything between the lines and paste into README.md

-->

<pre style="margin-top:18px;padding:12px;background:#04131b;border-radius:8px;color:#bcd3df;overflow:auto"># Hello — I’m **Momen Al-Ali**

**Data Analytics Engineer** • Warehousing • ETL • Data Pipelines • Dashboards

**About me**
I build reliable data warehouses and automated ETL pipelines. I turn messy data into trusted datasets, design semantic models for analytics, and create production-ready dashboards. I have hands-on experience at **Nexus Ville** and **Altibbi**.

**Skills & Tech**
- Python (pandas, numpy)
- SQL (T-SQL, PostgreSQL)
- ETL & Airflow
- Data Warehousing (star schema)
- Power BI (DAX)
- Tableau
- Looker
- DPT

**Experience**
- **Nexus Ville** — Data Analytics Engineer (2023 — Present)
  - Built ETL pipelines, designed data models, and created operational dashboards.

- **Altibbi** — Analytics Specialist (2021 — 2023)
  - Supported healthcare analytics and improved reporting pipelines.

**Certification**
- Certified Professional Data Analyst — DataCamp

Contact: momen@example.com • github.com/yourusername
</pre>

    </div>
  </div>
</body>
</html>
