
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Andualem Guchi | Professional Portfolio</title>
    <!-- Font Awesome 6 (free) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />
    <style>
        /* ===== RESET & BASE ===== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #f0f4fb;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            padding: 2rem 1.5rem;
            color: #0b1e33;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            line-height: 1.6;
        }

        .portfolio-wrapper {
            max-width: 1200px;
            width: 100%;
        }

        /* ===== MAIN CARD ===== */
        .main-card {
            background: #ffffff;
            border-radius: 2.5rem;
            padding: 2.8rem 3rem;
            box-shadow: 0 30px 60px -20px rgba(0, 20, 40, 0.2);
            transition: all 0.25s ease;
            opacity: 1; /* always visible, no fade on load */
        }

        @media (max-width: 700px) {
            .main-card {
                padding: 1.8rem 1.2rem;
                border-radius: 1.8rem;
            }
        }

        /* ===== TOP BAR ===== */
        .top-bar {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 2rem;
            gap: 1rem 1.5rem;
        }

        .brand h1 {
            font-size: 1.8rem;
            font-weight: 700;
            letter-spacing: -0.02em;
            color: #0b1e33;
        }
        .brand h1 i {
            color: #2563eb;
            margin-right: 0.4rem;
        }
        .brand .sub {
            font-size: 0.95rem;
            color: #475569;
            margin-top: 0.1rem;
        }

        .status-badge {
            background: #e6f0ff;
            padding: 0.4rem 1.2rem;
            border-radius: 40px;
            color: #1d4ed8;
            font-weight: 600;
            font-size: 0.9rem;
            border: 1px solid #bdd3ff;
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
        }
        .status-badge i {
            font-size: 0.7rem;
            color: #22c55e;
        }

        /* ===== HERO / INTRO ===== */
        .hero {
            background: linear-gradient(145deg, #f8fcff, #eef4fa);
            border-radius: 2rem;
            padding: 2rem 2.5rem;
            margin-bottom: 2.5rem;
            border: 1px solid #dce6f0;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
        }

        .hero-text {
            flex: 2;
        }
        .hero-text h2 {
            font-size: 2rem;
            font-weight: 700;
            color: #0b1e33;
        }
        .hero-text h2 i {
            color: #2563eb;
            margin-right: 0.3rem;
        }
        .hero-text p {
            font-size: 1.05rem;
            color: #334155;
            margin-top: 0.3rem;
            max-width: 550px;
        }
        .hero-text .location {
            font-size: 0.95rem;
            color: #475569;
            margin-top: 0.4rem;
        }
        .hero-text .location i {
            color: #2563eb;
            width: 1.4rem;
        }

        .hero-actions {
            display: flex;
            flex-wrap: wrap;
            gap: 0.8rem 1.2rem;
            margin-top: 1rem;
        }

        .btn {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            padding: 0.6rem 1.6rem;
            border-radius: 60px;
            font-weight: 600;
            font-size: 0.95rem;
            text-decoration: none;
            transition: 0.15s;
            border: none;
            cursor: pointer;
        }
        .btn-primary {
            background: #0b1e33;
            color: white;
        }
        .btn-primary:hover {
            background: #1a2f4a;
            transform: translateY(-2px);
            box-shadow: 0 8px 16px rgba(0,0,0,0.06);
        }
        .btn-outline {
            background: transparent;
            color: #0b1e33;
            border: 1.5px solid #cbd5e1;
        }
        .btn-outline:hover {
            background: #f1f5f9;
            border-color: #94a3b8;
        }
        .btn-cta {
            background: #2563eb;
            color: white;
        }
        .btn-cta:hover {
            background: #1d4ed8;
            transform: translateY(-2px);
        }

        /* ===== SECTION TITLES ===== */
        .section-title {
            font-size: 1.6rem;
            font-weight: 700;
            margin: 2.5rem 0 1.2rem 0;
            display: flex;
            align-items: center;
            gap: 0.6rem;
            border-bottom: 2px solid #e9edf4;
            padding-bottom: 0.6rem;
        }
        .section-title i {
            color: #2563eb;
            font-size: 1.5rem;
        }

        /* ===== GRID (expertise) ===== */
        .grid-2col {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1.5rem;
        }
        @media (max-width: 650px) {
            .grid-2col {
                grid-template-columns: 1fr;
            }
        }

        .expertise-card {
            background: #fafcff;
            padding: 1.2rem 1.5rem;
            border-radius: 20px;
            border: 1px solid #eef2f8;
            transition: 0.15s;
        }
        .expertise-card:hover {
            border-color: #bdd3ff;
            background: #f5f9ff;
            transform: translateY(-5px);
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.06);
        }
        .expertise-card h3 {
            font-size: 1.1rem;
            margin-bottom: 0.2rem;
            display: flex;
            align-items: center;
            gap: 0.4rem;
        }
        .expertise-card h3 i {
            color: #2563eb;
            width: 1.6rem;
        }
        .expertise-card p {
            color: #334155;
            font-size: 0.95rem;
        }

        /* ===== PROJECT CARDS ===== */
        .project-card {
            background: #fafcff;
            border-radius: 20px;
            padding: 1.5rem 1.8rem;
            border: 1px solid #eef2f8;
            margin-bottom: 1.5rem;
            transition: 0.15s;
        }
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.06);
            border-color: #bdd3ff;
        }
        .project-card h3 {
            font-size: 1.2rem;
            display: flex;
            align-items: center;
            gap: 0.6rem;
        }
        .project-card h3 i {
            color: #2563eb;
        }
        .project-card .label {
            font-weight: 600;
            color: #2563eb;
            font-size: 0.8rem;
            text-transform: uppercase;
            letter-spacing: 0.3px;
            margin-top: 0.5rem;
        }
        .project-card ul {
            padding-left: 1.2rem;
            list-style-type: '▹ ';
            color: #334155;
            margin-top: 0.3rem;
        }
        .project-card ul li {
            margin-bottom: 0.2rem;
            padding-left: 0.3rem;
        }

        /* ===== CERTIFICATES ===== */
        .cert-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
            gap: 1.5rem;
            margin: 1rem 0 0.5rem;
        }

        .cert-card {
            background: #f8fafc;
            border-radius: 20px;
            padding: 1rem 1rem 1.2rem;
            border: 1px solid #e2eaf0;
            text-align: center;
            transition: 0.15s;
        }
        .cert-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.06);
            border-color: #bdd3ff;
        }
        .cert-card img {
            width: 100%;
            height: auto;
            border-radius: 12px;
            border: 1px solid #dce3ed;
            background: white;
            max-height: 110px;
            object-fit: cover;
            margin-bottom: 0.5rem;
        }
        .cert-card .cert-name {
            font-weight: 600;
            font-size: 0.95rem;
        }
        .cert-card .cert-issuer {
            font-size: 0.8rem;
            color: #475569;
        }
        .cert-card .cert-id {
            font-size: 0.7rem;
            color: #64748b;
            background: #eef2f8;
            padding: 0.1rem 0.7rem;
            border-radius: 30px;
            display: inline-block;
            margin-top: 0.3rem;
        }

        /* ===== CREDENTIALS PILLS ===== */
        .credential-pills {
            display: flex;
            flex-wrap: wrap;
            gap: 0.6rem 1.2rem;
            background: #f8fafd;
            padding: 1rem 1.8rem;
            border-radius: 60px;
            margin: 0.5rem 0 0.2rem;
        }
        .credential-pills span {
            display: flex;
            align-items: center;
            gap: 0.4rem;
            font-size: 0.95rem;
        }
        .credential-pills i {
            color: #2563eb;
            width: 1.2rem;
        }

        /* ===== CONTACT + SIGNATURE ===== */
        .contact-section {
            background: #f8fafd;
            border-radius: 2rem;
            padding: 2rem 2.2rem;
            margin-top: 2rem;
            border: 1px solid #e2eaf5;
        }
        .contact-section h2 {
            font-size: 1.6rem;
        }
        .contact-section h2 i {
            color: #2563eb;
            margin-right: 0.4rem;
        }

        .social-row {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem 1.8rem;
            margin: 0.8rem 0 1.2rem;
        }
        .social-row a {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            background: white;
            padding: 0.3rem 1.2rem 0.3rem 0.8rem;
            border-radius: 60px;
            border: 1px solid #dce3ed;
            text-decoration: none;
            color: #0b1e33;
            font-weight: 500;
            transition: 0.15s;
        }
        .social-row a i {
            color: #2563eb;
            font-size: 1.2rem;
        }
        .social-row a:hover {
            background: #f1f5f9;
            transform: translateY(-2px);
        }

        .signature-box {
            background: #eef4fa;
            border-radius: 18px;
            padding: 1.2rem 1.8rem;
            margin-top: 1.5rem;
            border-left: 4px solid #2563eb;
            font-size: 0.95rem;
            line-height: 1.7;
        }
        .signature-box strong {
            color: #0b1e33;
        }
        .signature-box i {
            color: #2563eb;
            width: 1.6rem;
        }
        .signature-box a {
            color: #2563eb;
            text-decoration: none;
        }
        .signature-box a:hover {
            text-decoration: underline;
        }

        /* ===== FOOTER ===== */
        .footer-note {
            text-align: center;
            color: #64748b;
            font-size: 0.8rem;
            margin-top: 2rem;
            border-top: 1px solid #e9edf4;
            padding-top: 1.2rem;
        }
        .footer-note i {
            margin: 0 0.3rem;
            color: #94a3b8;
        }

        /* ===== RESPONSIVE TWEAKS ===== */
        @media (max-width: 600px) {
            .hero {
                padding: 1.5rem;
            }
            .hero-text h2 {
                font-size: 1.6rem;
            }
            .section-title {
                font-size: 1.3rem;
            }
            .credential-pills {
                border-radius: 28px;
                padding: 0.8rem 1.2rem;
                gap: 0.4rem 0.8rem;
            }
        }
    </style>
</head>
<body>
<div class="portfolio-wrapper">
    <div class="main-card">

        <!-- ===== TOP BAR ===== -->
        <div class="top-bar">
            <div class="brand">
                <h1><i class="fas fa-code"></i> Andualem Guchi</h1>
                <div class="sub">Digital Specialist · Developer · Creative</div>
            </div>
            <div class="status-badge">
                <i class="fas fa-circle"></i> open for work
            </div>
        </div>

        <!-- ===== HERO ===== -->
        <div class="hero">
            <div class="hero-text">
                <h2><i class="fas fa-rocket"></i> Code · Design · Localize</h2>
                <p>From Python automation to mobile UI and bilingual content — helping businesses connect with Ethiopian and global audiences.</p>
                <div class="location">
                    <i class="fas fa-map-pin"></i> Addis Ababa, Ethiopia · <i class="fas fa-globe"></i> Global reach
                </div>
                <div class="hero-actions">
                    <a href="#" class="btn btn-primary" download><i class="fas fa-file-pdf"></i> Download CV</a>
                    <a href="#contact" class="btn btn-cta"><i class="fas fa-paper-plane"></i> Hire me</a>
                    <a href="https://t.me/Andualem_digital" target="_blank" class="btn btn-outline"><i class="fab fa-telegram"></i> Telegram</a>
                </div>
            </div>
        </div>

        <!-- ===== CORE EXPERTISE ===== -->
        <h2 class="section-title"><i class="fas fa-th-large"></i> Core Expertise</h2>
        <div class="grid-2col">
            <div class="expertise-card">
                <h3><i class="fas fa-code"></i> Software Development</h3>
                <p>Python scripting, C++ logic design, data structures, automation.</p>
            </div>
            <div class="expertise-card">
                <h3><i class="fas fa-mobile-alt"></i> Mobile & UI Design</h3>
                <p>Responsive Android layouts, user flow mapping, visual asset design.</p>
            </div>
            <div class="expertise-card">
                <h3><i class="fas fa-video"></i> Creative Content</h3>
                <p>Video editing, social media assets, persuasive copywriting.</p>
            </div>
            <div class="expertise-card">
                <h3><i class="fas fa-globe"></i> Digital Operations</h3>
                <p>Cybersecurity, AI prompt literacy, translation & localization.</p>
            </div>
        </div>

        <!-- ===== PROJECTS ===== -->
        <h2 class="section-title"><i class="fas fa-folder-open"></i> Project Case Studies</h2>

        <div class="project-card">
            <h3><i class="fas fa-robot"></i> Automated Data Management & Scripts</h3>
            <div class="label">Objective</div>
            <p>Streamline repetitive corporate tasks and workflows using optimized code.</p>
            <div class="label">Execution</div>
            <ul>
                <li>Built custom Python automation scripts aligned with university structures.</li>
                <li>Automates bulk spreadsheet parsing, data sorting, and file management.</li>
            </ul>
            <div class="label">Outcome</div>
            <p>Drastically reduces manual data-entry errors and cuts processing time.</p>
        </div>

        <div class="project-card">
            <h3><i class="fas fa-paint-brush"></i> Mobile Interface Design & Assets</h3>
            <div class="label">Objective</div>
            <p>Craft clean, professional user experiences for digital products.</p>
            <div class="label">Execution</div>
            <ul>
                <li>High-fidelity mobile interfaces using Udacity's Android Fundamentals.</li>
                <li>Original vector icon sets optimized across screens.</li>
            </ul>
            <div class="label">Outcome</div>
            <p>Stunning, intuitive mockups ready for engineering deployment.</p>
        </div>

        <div class="project-card">
            <h3><i class="fas fa-pen-fancy"></i> Tech Copywriting, Video & Localization</h3>
            <div class="label">Objective</div>
            <p>Produce accessible digital guides and media to scale engagement.</p>
            <div class="label">Execution</div>
            <ul>
                <li>Authored tech explainers, localized copy, and short-form videos.</li>
                <li>Applied Meta's digital communication framework.</li>
            </ul>
            <div class="label">Outcome</div>
            <p>Drives consumer reach with high-converting, readable technical content.</p>
        </div>

        <!-- ===== CERTIFICATES ===== -->
        <h2 class="section-title"><i class="fas fa-certificate"></i> Certificates & Credentials</h2>
        <div class="cert-grid">
            <div class="cert-card">
                <img src="20260823_d0aae0.png" alt="Digital Literacy" />
                <div class="cert-name">Digital Literacy</div>
                <div class="cert-issuer">Zega Digital · OMNI</div>
                <div class="cert-id">ZEGA-958BYQ4B</div>
            </div>
            <div class="cert-card">
                <img src="20260823_df15e5.png" alt="Python Essentials" />
                <div class="cert-name">Python Programming</div>
                <div class="cert-issuer">HU · CS Dept.</div>
                <div class="cert-id">May 25–26, 2026</div>
            </div>
            <div class="cert-card">
                <img src="20260823_7c823c.png" alt="Android Fundamentals" />
                <div class="cert-name">Android Fundamentals</div>
                <div class="cert-issuer">Udacity</div>
                <div class="cert-id">job-ready</div>
            </div>
            <div class="cert-card">
                <img src="20260823_9a719e.png" alt="C++ for Beginners" />
                <div class="cert-name">C++ for Beginners</div>
                <div class="cert-issuer">Bishal Khadka</div>
                <div class="cert-id">completion</div>
            </div>
            <div class="cert-card">
                <img src="20260823_113459.png" alt="Additional Certificate" />
                <div class="cert-name">Additional Credential</div>
                <div class="cert-issuer">Verified</div>
                <div class="cert-id">2026</div>
            </div>
        </div>

        <!-- ===== ACADEMIC ===== -->
        <div class="credential-pills">
            <span><i class="fas fa-university"></i> B.Sc. Natural Science (ongoing) · Haramaya Univ. · CGPA 3.92 · GD</span>
            <span><i class="fas fa-file-alt"></i> Year I Sem I: A, A, A+, A-, A- · SGPA 3.91</span>
        </div>

        <!-- ===== CONTACT + SIGNATURE ===== -->
        <div class="contact-section" id="contact">
            <h2><i class="fas fa-paper-plane"></i> Work With Me</h2>
            <p style="color: #475569; margin-bottom: 0.5rem;">Have a project in mind? Let's connect directly.</p>

            <div class="social-row">
                <a href="https://t.me/Andualem_digital" target="_blank"><i class="fab fa-telegram"></i> @Andualem_digital</a>
                <a href="mailto:andualemandualem25@gmail.com"><i class="fas fa-envelope"></i> andualemandualem25</a>
                <a href="https://www.upwork.com/freelancers/~your-upwork-id" target="_blank"><i class="fab fa-upwork"></i> Upwork</a>
            </div>

            <!-- form (simple, no backend) -->
            <form action="https://formspreet.com" method="post" style="max-width: 500px; margin-top: 1rem;">
                <input type="text" name="name" placeholder="Your name" required style="width:100%; padding:0.7rem 1.2rem; border-radius:40px; border:1px solid #d1d9e6; margin-bottom:0.7rem; font-size:1rem;" />
                <input type="email" name="email" placeholder="Email address" required style="width:100%; padding:0.7rem 1.2rem; border-radius:40px; border:1px solid #d1d9e6; margin-bottom:0.7rem; font-size:1rem;" />
                <textarea name="message" placeholder="Tell me about your project..." rows="3" style="width:100%; padding:0.7rem 1.2rem; border-radius:24px; border:1px solid #d1d9e6; margin-bottom:0.7rem; font-size:1rem; resize:vertical;"></textarea>
                <button type="submit" class="btn btn-cta"><i class="fas fa-rocket"></i> Send message</button>
            </form>

            <!-- Professional Email Signature with COMPLETED URL -->
            <div class="signature-box">
                <strong>Andualem Guchi Gezahegn</strong><br />
                <i class="fas fa-briefcase"></i> Digital Specialist &amp; Developer<br />
                <i class="fas fa-phone"></i> +251 983693486<br />
                <i class="fab fa-telegram"></i> @Andualem_digital<br />
                <i class="fas fa-link"></i> Interactive Resume &amp; Case Studies: <a href="https://andualemguchigezahegn.github.io/-Andualem-_portfolio_page/" target="_blank">https://andualemguchigezahegn.github.io/-Andualem-_portfolio_page/</a><br />
                <span style="font-size:0.85rem; color:#475569;">
                    <i class="fas fa-graduation-cap"></i> Haramaya University Natural Science | CGPA: 3.9<br />
                    <i class="fas fa-certificate"></i> Certified by Meta (Digital Literacy) &amp; Udacity
                </span>
            </div>
        </div>

        <!-- ===== FOOTER ===== -->
        <div class="footer-note">
            <i class="fas fa-code"></i> Andualem Guchi · built with <i class="fas fa-heart" style="color:#ef4444;"></i> · portfolio
        </div>

    </div>
</div>
</body>
</html>
