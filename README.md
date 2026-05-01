
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privacy Policy | Goalytics Football Tips</title>
    <style>
        /* CSS Variables to match Android App Colors */
        :root {
            --bg-main: #050810;
            --bg-card: #0D1425;
            --accent-cyan: #00E5FF;
            --accent-blue: #3D5AFE;
            --text-primary: #FFFFFF;
            --text-secondary: #94A3B8;
            --border: rgba(255, 255, 255, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-main);
            color: var(--text-secondary);
            line-height: 1.6;
            padding: 20px;
        }

        /* High-Tech Header */
        header {
            background-color: #0A0F1E;
            border-bottom: 2px solid var(--accent-blue);
            padding: 40px 20px;
            text-align: center;
            border-radius: 12px 12px 0 0;
            max-width: 900px;
            margin: 0 auto;
        }

        h1 {
            color: var(--text-primary);
            font-size: 2.2rem;
            letter-spacing: 2px;
            text-transform: uppercase;
            font-weight: 900;
        }

        .version-tag {
            color: var(--accent-cyan);
            font-family: monospace;
            font-size: 0.8rem;
            margin-top: 10px;
            display: block;
        }

        /* Content Container */
        main {
            max-width: 900px;
            margin: 0 auto;
            padding: 40px;
            background-color: var(--bg-card);
            border: 1px solid var(--border);
            border-top: none;
            border-radius: 0 0 12px 12px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }

        h2 {
            color: var(--accent-cyan);
            font-size: 1.4rem;
            margin-top: 35px;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Cyan dot before headers */
        h2::before {
            content: " ";
            display: inline-block;
            width: 8px;
            height: 8px;
            background-color: var(--accent-cyan);
            margin-right: 12px;
            border-radius: 50%;
            box-shadow: 0 0 10px var(--accent-cyan);
        }

        p {
            margin-bottom: 20px;
            font-size: 1rem;
        }

        a {
            color: var(--accent-blue);
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        a:hover {
            color: var(--accent-cyan);
            text-shadow: 0 0 8px var(--accent-cyan);
        }

        /* Disclaimer & Warning Box */
        .alert-box {
            background: rgba(61, 90, 254, 0.1);
            border-left: 4px solid var(--accent-blue);
            padding: 20px;
            margin: 30px 0;
            border-radius: 4px;
        }

        .alert-box strong {
            color: var(--text-primary);
            display: block;
            margin-bottom: 10px;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 40px 20px;
            font-size: 0.8rem;
            color: #475569;
            max-width: 900px;
            margin: 0 auto;
        }

        /* Responsiveness */
        @media (max-width: 768px) {
            main { padding: 20px; }
            h1 { font-size: 1.6rem; }
        }
    </style>
</head>
<body>

<header>
    <h1>Privacy Policy</h1>
    <span class="version-tag">DOCUMENT_REF: TPF-2026-V1</span>
</header>

<main>
    <h2>Introduction</h2>
    <p>Welcome to <strong>Goalytics Football Tips</strong>. We operate a "Privacy by Design" model. This document explains how we interact with data while providing professional match insights and analytical selections.</p>

    <h2>Data Collection & Firebase</h2>
    <p>We do not require user accounts, names, or phone numbers to function. However, our app utilizes <strong>Firebase Realtime Database</strong> to deliver live tip updates. Firebase may automatically process:</p>
    <ul style="margin-left: 20px; margin-bottom: 20px;">
        <li>Device Identification (UUID) for analytics.</li>
        <li>IP Addresses (for regional content delivery).</li>
        <li>App Interaction logs (to optimize tip performance).</li>
    </ul>
    <p>Review the <a href="https://firebase.google.com/support/privacy" target="_blank">Firebase Privacy Policy</a> for more details on Google's data handling.</p>

    <h2>No Personal Identifiable Information (PII)</h2>
    <p>Our internal algorithms do not track your personal identity. We provide a terminal-style experience where all analytical data is served via a one-way stream from our cloud servers to your device.</p>

    <h2>18+ Responsible Gaming</h2>
    <div class="alert-box">
        <strong>STRICT ADHERENCE TO AGE RESTRICTIONS</strong>
        Our app is strictly intended for users 18 years or older. Football tipping involves risk; we encourage all users to treat our insights as professional analysis and not financial guarantees.
    </div>

    <h2>Disclaimer & Risk</h2>
    <p>The contents of Goalytics Football Tips are provided "as is." We utilize historical data and algorithmic patterns to generate selections, but we do not guarantee specific outcomes. Users acknowledge that sports tipping involves inherent uncertainty.</p>

    <h2>Contact Technical Support</h2>
    <p>For questions regarding this policy or data interaction, reach our terminal experts at:<br>
    <a href="mailto:socceriqsport@gmail.com">socceriqsport@gmail.com</a></p>

    <p style="margin-top: 40px; font-size: 0.8rem; opacity: 0.5;">Last System Update: April 2026</p>
</main>

<footer>
    <p>&copy; 2026 GOALYTICS FOOTBALL TIPS TERMINAL. ALL RIGHTS RESERVED.</p>
</footer>

</body>
</html>
