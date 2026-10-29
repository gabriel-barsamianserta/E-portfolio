<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My ePortfolio | Career Project</title>
    <style>
        :root {
            --primary-color: #1e293b;
            --accent-color: #2563eb;
            --accent-hover: #1d4ed8;
            --bg-color: #f8fafc;
            --card-bg: #ffffff;
            --text-color: #334155;
            --heading-color: #0f172a;
            --border-color: #e2e8f0;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
            padding-bottom: 3rem;
        }

        header {
            background-color: var(--primary-color);
            color: white;
            padding: 4rem 1.5rem 3rem;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            color: white;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.15rem;
            color: #94a3b8;
        }

        .container {
            max-width: 1000px;
            margin: -2rem auto 0;
            padding: 0 1.5rem;
        }

        section {
            background: var(--card-bg);
            border-radius: 12px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05), 0 2px 4px -1px rgba(0, 0, 0, 0.03);
            border: 1px solid var(--border-color);
        }

        h2 {
            color: var(--heading-color);
            font-size: 1.5rem;
            padding-bottom: 0.75rem;
            border-bottom: 2px solid var(--border-color);
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        h3 {
            color: var(--heading-color);
            font-size: 1.15rem;
            margin: 1.25rem 0 0.75rem;
        }

        .subtitle {
            color: #64748b;
            font-size: 0.95rem;
            margin-top: -1rem;
            margin-bottom: 1.5rem;
        }

        .btn-group {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            background-color: var(--accent-color);
            color: white;
            padding: 0.75rem 1.25rem;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
            font-size: 0.95rem;
            transition: background-color 0.2s ease, transform 0.1s ease;
        }

        .btn:hover {
            background-color: var(--accent-hover);
            transform: translateY(-1px);
        }

        .btn-linkedin {
            background-color: #0a66c2;
        }

        .btn-linkedin:hover {
            background-color: #084e96;
        }

        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 aspect ratio */
            height: 0;
            overflow: hidden;
            border-radius: 8px;
            background: #000;
            margin: 1.5rem 0;
        }

        .video-container iframe,
        .video-container video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
        }

        .grid-3 {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin-top: 1rem;
        }

        .card {
            background-color: #f8fafc;
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 1.5rem;
        }

        .card h4 {
            color: var(--heading-color);
            font-size: 1.1rem;
            margin-bottom: 0.5rem;
        }

        .card p {
            font-size: 0.95rem;
            margin-bottom: 0.5rem;
        }

        .card p strong {
            color: var(--heading-color);
        }

        .structure-badge {
            display: inline-block;
            background-color: #e0e7ff;
            color: #3730a3;
            font-size: 0.8rem;
            font-weight: 600;
            padding: 0.25rem 0.6rem;
            border-radius: 4px;
            margin-bottom: 1rem;
        }

        footer {
            text-align: center;
            color: #64748b;
            font-size: 0.9rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Career Project ePortfolio</h1>
        <p>Professional Profile, Role Model Analysis & International Mobility</p>
    </header>

    <div class="container">

        <!-- SECTION 1: CV & LINKEDIN -->
        <section id="documents">
            <h2>📄 CVs & LinkedIn Profiles</h2>
            <p class="subtitle">Access my professional documents and social networks in English and French.</p>

            <h3>Curriculum Vitae</h3>
            <div class="btn-group">
                <a href="CV_EN.pdf" class="btn" target="_blank">📄 CV in English (PDF)</a>
                <a href="CV_FR.pdf" class="btn" target="_blank">📄 CV en Français (PDF)</a>
            </div>

            <h3>LinkedIn Profiles</h3>
            <div class="btn-group">
                <a href="https://linkedin.com/in/YOUR-PROFILE-EN" class="btn btn-linkedin" target="_blank">🔗 LinkedIn (English)</a>
                <a href="https://linkedin.com/in/YOUR-PROFILE-FR" class="btn btn-linkedin" target="_blank">🔗 LinkedIn (Français)</a>
            </div>
        </section>

        <!-- SECTION 2: ELEVATOR PITCH VIDEO -->
        <section id="pitch">
            <h2>🎥 Elevator Pitch Video</h2>
            <p class="subtitle">2-3 minute Unique Value Proposal in English.</p>

            <span class="structure-badge">Structure: Present + Brief Past + Future</span>

            <div class="video-container">
                <!-- Replace src with your YouTube embed URL, Vimeo link, or local video file -->
                <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" title="Elevator Pitch Video" allowfullscreen></iframe>
            </div>

            <h3>Summary of Unique Value Proposal</h3>
            <p><strong>Present:</strong> [Insert your current student/professional status and key skills]</p>
            <p><strong>Past:</strong> [Insert brief background, past experiences, or relevant academic focus]</p>
            <p><strong>Future:</strong> [Insert short/long term career objectives and aspirations]</p>
        </section>

        <!-- SECTION 3: ROLE MODEL PROFILES -->
        <section id="role-models">
            <h2>👥 Role Model Profiles Analyzed</h2>
            <p class="subtitle">Analysis of 3 inspiring professionals explored via My Job Glasses, alumni interviews, or professional research.</p>

            <div class="grid-3">
                <div class="card">
                    <h4>Role Model 1</h4>
                    <p><strong>Name / Position:</strong> [Name, Job Title]</p>
                    <p><strong>Company / Industry:</strong> [Company Name, Sector]</p>
                    <p><strong>Source:</strong> [My Job Glasses / Alumni / Other]</p>
                    <p><strong>Key Learnings:</strong> [Brief summary of career path, skills required, and insights gained from their experience.]</p>
                </div>

                <div class="card">
                    <h4>Role Model 2</h4>
                    <p><strong>Name / Position:</strong> [Name, Job Title]</p>
                    <p><strong>Company / Industry:</strong> [Company Name, Sector]</p>
                    <p><strong>Source:</strong> [My Job Glasses / Alumni / Other]</p>
                    <p><strong>Key Learnings:</strong> [Brief summary of career path, skills required, and insights gained from their experience.]</p>
                </div>

                <div class="card">
                    <h4>Role Model 3</h4>
                    <p><strong>Name / Position:</strong> [Name, Job Title]</p>
                    <p><strong>Company / Industry:</strong> [Company Name, Sector]</p>
                    <p><strong>Source:</strong> [My Job Glasses / Alumni / Other]</p>
                    <p><strong>Key Learnings:</strong> [Brief summary of career path, skills required, and insights gained from their experience.]</p>
                </div>
            </div>
        </section>

        <!-- SECTION 4: INTERNATIONAL MOBILITY PROJECTS -->
        <section id="mobility">
            <h2>🌍 Potential International Mobility Projects</h2>
            <p class="subtitle">3 international project options directly aligned with the 3 role model profiles.</p>

            <div class="grid-3">
                <div class="card">
                    <h4>Project 1 (Role Model 1)</h4>
                    <p><strong>Target Country/City:</strong> [Country/City]</p>
                    <p><strong>Target Position/Sector:</strong> [Role or Sector]</p>
                    <p><strong>Alignment:</strong> [Explain how this project connects with Role Model 1's profile and path.]</p>
                </div>

                <div class="card">
                    <h4>Project 2 (Role Model 2)</h4>
                    <p><strong>Target Country/City:</strong> [Country/City]</p>
                    <p><strong>Target Position/Sector:</strong> [Role or Sector]</p>
                    <p><strong>Alignment:</strong> [Explain how this project connects with Role Model 2's profile and path.]</p>
                </div>

                <div class="card">
                    <h4>Project 3 (Role Model 3)</h4>
                    <p><strong>Target Country/City:</strong> [Country/City]</p>
                    <p><strong>Target Position/Sector:</strong> [Role or Sector]</p>
                    <p><strong>Alignment:</strong> [Explain how this project connects with Role Model 3's profile and path.]</p>
                </div>
            </div>
        </section>

        <footer>
            <p>© ePortfolio - Career Project Module</p>
        </footer>

    </div>

</body>
</html>