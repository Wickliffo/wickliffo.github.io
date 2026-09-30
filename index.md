<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wickliff Orina | Data Engineer & Linux SysAdmin</title>
    <meta name="description" content="Portfolio of Wickliff Orina - Data Engineer, Analytics Engineer, and Linux Systems Administrator based in Kakamega, Kenya.">
    <style>
        :root {
            --bg-primary: #0d1117;
            --bg-card: #161b22;
            --border-color: #30363d;
            --text-main: #c9d1d9;
            --text-muted: #8b949e;
            --accent: #58a6ff;
            --accent-green: #3fb950;
            --accent-orange: #f7931e;
        }
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-primary);
            color: var(--text-main);
            line-height: 1.6;
            padding: 40px 20px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: var(--bg-card);
            border: 1px solid var(--border-color);
            border-radius: 16px;
            padding: 48px;
            box-shadow: 0 12px 36px rgba(0, 0, 0, 0.6);
        }
        header {
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 24px;
            margin-bottom: 32px;
        }
        h1 {
            font-size: 2.5rem;
            color: #ffffff;
            margin-bottom: 8px;
        }
        .tagline {
            font-size: 1.25rem;
            color: var(--accent);
            font-weight: 600;
            margin-bottom: 12px;
        }
        .location {
            color: var(--text-muted);
            font-size: 0.95rem;
            margin-bottom: 16px;
        }
        .bio {
            font-size: 1.05rem;
            color: var(--text-main);
            margin-top: 12px;
        }
        .highlight {
            color: var(--accent-orange);
            font-weight: 600;
        }
        section {
            margin-bottom: 36px;
        }
        h2 {
            font-size: 1.5rem;
            color: #ffffff;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 8px;
            margin-bottom: 20px;
        }
        .skills-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }
        .skill-badge {
            background: #21262d;
            border: 1px solid var(--border-color);
            color: var(--text-main);
            padding: 6px 12px;
            border-radius: 8px;
            font-size: 0.85rem;
            font-weight: 500;
            display: inline-flex;
            align-items: center;
            gap: 6px;
        }
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 16px;
        }
        .project-card {
            background: #0d1117;
            border: 1px solid var(--border-color);
            border-radius: 10px;
            padding: 20px;
            transition: transform 0.2s ease, border-color 0.2s ease;
        }
        .project-card:hover {
            transform: translateY(-3px);
            border-color: var(--accent);
        }
        .project-card h3 a {
            color: var(--accent);
            text-decoration: none;
            font-size: 1.1rem;
        }
        .project-card h3 a:hover {
            text-decoration: underline;
        }
        .project-card p {
            color: var(--text-muted);
            font-size: 0.9rem;
            margin-top: 8px;
            margin-bottom: 12px;
        }
        .tech-tag {
            background: #161b22;
            border: 1px solid var(--border-color);
            color: var(--accent-green);
            font-size: 0.75rem;
            padding: 3px 8px;
            border-radius: 4px;
            display: inline-block;
            margin-right: 4px;
            margin-top: 4px;
        }
        ul {
            padding-left: 20px;
            color: var(--text-muted);
        }
        ul li {
            margin-bottom: 8px;
        }
        ul li strong {
            color: var(--text-main);
        }
        .footer {
            text-align: center;
            border-top: 1px solid var(--border-color);
            padding-top: 24px;
            margin-top: 40px;
            color: var(--text-muted);
            font-size: 0.9rem;
        }
        .footer a {
            color: var(--accent);
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
        .quote {
            font-style: italic;
            color: var(--text-muted);
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Wickliff Orina</h1>
            <div class="tagline">🚀 Aspiring Analytical Engineer | Data Engineer & Linux SysAdmin</div>
            <div class="location">📍 Kakamega, Kenya | Student at Masinde Muliro University of Science and Technology (MMUST)</div>
            <p class="bio">
                I sit at the intersection of Data Engineering, Linux Systems Administration, and Analytics, building robust pipelines and hardening infrastructure. Known as the <span class="highlight">"Walking Database"</span>, I am obsessed with data integrity, automation, and reliable enterprise systems.
            </p>
        </header>

        <section>
            <h2>🛠️ Technical Core Stack</h2>
            <div class="skills-grid">
                <span class="skill-badge">🐍 Python</span>
                <span class="skill-badge">📊 SQL</span>
                <span class="skill-badge">⚡ Polars & Pandas</span>
                <span class="skill-badge">🐧 Linux (RHEL 9 / Ubuntu)</span>
                <span class="skill-badge">🔄 Apache Kafka</span>
                <span class="skill-badge">🐳 Kubernetes & Docker</span>
                <span class="skill-badge">⚙️ Jenkins CI/CD</span>
                <span class="skill-badge">☁️ AWS Cloud</span>
                <span class="skill-badge">🗄️️ PostgreSQL & SQL Server</span>
                <span class="skill-badge">📈 Power BI & Streamlit</span>
                <span class="skill-badge">🌐 FastAPI</span>
            </div>
        </section>

        <section>
            <h2>🏆 Featured Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3><a href="https://github.com/Wickliffo/linux-network-engineering-labs" target="_blank">Linux Network Labs</a></h3>
                    <p>Hardened RHEL 9 network configurations, static IP provisioning, and automated auditing scripts.</p>
                    <span class="tech-tag">RHEL 9</span><span class="tech-tag">Bash</span><span class="tech-tag">NetworkManager</span>
                </div>
                <div class="project-card">
                    <h3><a href="https://github.com/Wickliffo/RetailFlux-Walmart-Sales-Pipeline" target="_blank">RetailFlux Pipeline</a></h3>
                    <p>End-to-end automated ETL pipeline built with Polars and Python to streamline retail data processing.</p>
                    <span class="tech-tag">Polars</span><span class="tech-tag">Python</span><span class="tech-tag">ETL</span>
                </div>
                <div class="project-card">
                    <h3><a href="https://github.com/Wickliffo/Sowing-Success-ML-Driven-Crop-Selection" target="_blank">Sowing Success ML</a></h3>
                    <p>Multi-class classification model using Scikit-Learn to optimize crop suitability based on soil measures.</p>
                    <span class="tech-tag">Scikit-Learn</span><span class="tech-tag">Random Forest</span>
                </div>
                <div class="project-card">
                    <h3><a href="https://github.com/Wickliffo/Swiggy-sql-analytic-data-warehouse" target="_blank">Swiggy Delivery DWH</a></h3>
                    <p>Star schema data warehouse designed to isolate bottlenecks and streamline business analytics.</p>
                    <span class="tech-tag">SQL Server</span><span class="tech-tag">Data Warehousing</span>
                </div>
            </div>
        </section>

        <section>
            <h2>🏛️ Professional Experience & Background</h2>
            <ul>
                <li><strong>Research Data Attaché — Kenya Medical Research Institute (KEMRI):</strong> Executed analytical engineering, data validation workflows, and data processing in high-compliance research environments.</li>
                <li><strong>Academic Foundation:</strong> Pursuing Bachelor of Science in Information Technology at <strong>Masinde Muliro University of Science and Technology (MMUST)</strong>.</li>
            </ul>
        </section>

        <div class="quote">
            "Data is a precious thing and will last longer than the systems themselves."
        </div>

        <div class="footer">
            <p>Connect with me on <a href="https://github.com/Wickliffo" target="_blank">GitHub @Wickliffo</a></p>
        </div>
    </div>
</body>
</html>
