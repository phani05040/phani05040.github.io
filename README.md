# phani05040.github.io
<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phani's Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&amp;family=Source+Code+Pro:wght@400;600&amp;display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #fdfaf7;
            --primary-accent: #896349;
            --secondary-accent: #cf9d7b;
            --text-dark: #2d2d2d;
            --text-light: #666;
            --card-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
            --transition: all 0.3s ease;
        }

        body {
            background-color: var(--bg-color);
            font-family: 'Inter', sans-serif;
            margin: 0;
            color: var(--text-dark);
            line-height: 1.6;
        }


        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 30px 8%;
            background: rgba(253, 250, 247, 0.9);
            backdrop-filter: blur(10px);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .navbar h1 {
            font-family: 'Source Code Pro', monospace;
            font-size: 1.5rem;
            margin: 0;
            color: var(--primary-accent);
        }

        .nav-links {
            display: flex;
            gap: 30px;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--text-dark);
            font-weight: 600;
            font-size: 0.9rem;
            transition: var(--transition);
        }

        .nav-links a:hover {
            color: var(--primary-accent);
        }

        .hero {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            padding: 80px 10% 100px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .profile-wrapper {
            margin-bottom: 40px;
        }

        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 30% 70% 70% 30% / 30% 30% 70% 70%;
            object-fit: cover;
            border: 5px solid white;
            box-shadow: var(--card-shadow);
            transition: var(--transition);
        }

        .profile-img:hover {
            border-radius: 50%;
        }

        .hero h2 {
            font-size: 1rem;
            text-transform: uppercase;
            letter-spacing: 3px;
            color: var(--secondary-accent);
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.2rem;
            color: var(--text-light);
            max-width: 700px;
        }

        .section-title {
            text-align: center;
            font-size: 2.2rem;
            margin: 80px 0 40px;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 50px;
            height: 4px;
            background: var(--secondary-accent);
            margin: 15px auto 0;
            border-radius: 2px;
        }

        .container {
            padding: 0 8% 80px;
            max-width: 1300px;
            margin: 0 auto;
        }

        .grid-box {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .card {
            background: white;
            padding: 40px 30px;
            border-radius: 24px;
            box-shadow: var(--card-shadow);
            transition: var(--transition);
            border: 1px solid rgba(0, 0, 0, 0.03);
            text-align: center;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.12);
        }

        .card h4 {
            font-size: 1.4rem;
            margin-bottom: 15px;
            color: var(--primary-accent);
        }

        .card p {
            font-size: 0.95rem;
            color: var(--text-light);
        }

        .tag {
            display: inline-block;
            background: #f0f0f0;
            padding: 4px 12px;
            border-radius: 50px;
            font-size: 0.75rem;
            font-weight: 700;
            margin: 5px;
            color: var(--primary-accent);
        }

        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 28px;
            background: var(--primary-accent);
            color: white;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            transition: var(--transition);
        }

        .btn:hover {
            background: var(--text-dark);
        }

        .contact-section {
            background: #1a1a1a;
            color: white;
            padding: 100px 8%;
            text-align: center;
            border-radius: 60px 60px 0 0;
        }

        .contact-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin: 40px 0;
        }

        .contact-item {
            background: rgba(255, 255, 255, 0.05);
            padding: 15px 25px;
            border-radius: 12px;
            font-family: 'Source Code Pro', monospace;
        }

        .footer-note {
            opacity: 0.5;
            font-size: 0.8rem;
            margin-top: 50px;
        }

        @media (max-width: 768px) {
            .navbar {
                flex-direction: column;
                gap: 20px;
            }

            .hero h1 {
                font-size: 2rem;
            }

            .grid-box {
                grid-template-columns: 1fr;
            }
        }
    </style>
<link rel="stylesheet" href="index.css">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="robots" content="none,noarchive">
<style type="text/css" id="mytempCss">._8mqQwQ { display: none; } ._1TWLMK.icF5zO { opacity: 0.01; }</style></head>

<body>

    <nav class="navbar">
        <h1>Phani.Dev</h1>
        <div class="nav-links">
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#certificates">Certificates</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <header class="hero">
        <div class="profile-wrapper">
            <img src="https://media.licdn.com/dms/image/v2/D5622AQFTNKGH0jcLjQ/feedshare-shrink_2048_1536/B56Z3iJNlyJ0Ag-/0/1777615559251?e=1779321600&amp;v=beta&amp;t=YjxevN5Jbj8VNjiOpZdnkNHTCmRwI_K5vSZsJI_ADlg" class="profile-img" alt="Phani">
        </div>
        <h2>Welcome to My Portfolio</h2>
        <h1>Mr. Pamarthi Devi Phanindra</h1>
        <p>Exploring and mastering emerging technologies to build a strong professional foundation. Focused on excellence and continuous growth in the tech space.</p>
    </header>

    <section id="projects" class="container">
        <h3 class="section-title">Featured Projects</h3>
        <div class="grid-box">
            <!-- Project 1 -->
            <div class="card">
                <h4>Portfolio</h4>
                <div>
                    <span class="tag">HTML</span>
                    <span class="tag">CSS</span>
                    <span class="tag">JS</span>
                </div>
                <p>A sleek, professional personal brand platform showcasing my technical journey, skills, and project timeline using modern web standards.</p>
                <a href="https://github.com/phani05040/Portfolio.git" target="_blank" class="btn">View Project</a>
            </div>
            <!-- Project 2 -->
            <div class="card">
                <h4>Folder Locker</h4>
                <div><span class="tag">JAVA</span></div>
                <div><span class="tag">CMD</span></div>
                <p>A Java-based utility designed to secure directories through system-level commands, providing a lightweight privacy solution for local files.</p>
                <a href="https://github.com/phani05040" target="_blank" class="btn">View Project</a>
            </div>
            <!-- Project 3 -->
            <div class="card">
                <h4>AI Doctor</h4>
                <div>
                    <span class="tag">PYTHON</span>
                    <span class="tag">ML</span>
                </div>
                <p>A healthcare assistance tool developed to provide preliminary disease analysis and wellness advice using supervised machine learning models.</p>
                <a href="https://github.com/phani05040/Project_IBM_Doctor.git" target="_blank" class="btn">View Project</a>
            </div>
            <!-- Project 4 -->
            <div class="card">
                <h4>OrganicFruitsMarket</h4>
                <div>
                    <span class="tag">HTML</span>
                    <span class="tag">CSS</span>
                    <span class="tag">JS</span>
                    <span class="tag">Bootstrap</span>
                </div>
                <p>A Community Service Project aimed at empowering organic farmers by providing a digital marketplace to sell produce directly to consumers.</p>
                <a href="https://github.com/phani05040/Organic-Farming.git" target="_blank" class="btn">View Project</a>
            </div>
            <!-- Project 5 -->
            <div class="card">
                <h4>ZomatoClone</h4>
                <div>
                    <span class="tag">Python</span>
                    <span class="tag">Script</span>
                </div>
                <p>A functional recreation of the Zomato UI and logic, focusing on data scraping, restaurant listing features, and responsive design layouts.</p>
                <a href="https://github.com/phani05040/My_Zomato.git" target="_blank" class="btn">View Project</a>
            </div>
            <!-- Project 6 -->
            <div class="card">
                <h4>Vehicle Rental System</h4>
                <div>
                    <span class="tag">JAVA</span>
                    <span class="tag">JS</span>
                    <span class="tag">HTML</span>
                    <span class="tag">SpringBoot</span>
                    <span class="tag">DBMS</span>
                </div>
                <p>A robust bike-sharing architecture that manages fleet inventory, user bookings, and station availability through a centralized SpringBoot backend.</p>
                <a href="https://github.com/phani05040/MyVelib_Bike_Sharing_System.git" target="_blank" class="btn">View Project</a>
            </div>
            <!-- Project 7 -->
            <div class="card">
                <h4>Result Server</h4>
                <div>
                    <span class="tag">JAVA</span>
                    <span class="tag">PostMan</span>
                    <span class="tag">SpringBoot</span>
                    <span class="tag">DBMS</span>
                </div>
                <p>An end-to-end examination management system allowing educational institutions to securely store, process, and publish student results.</p>
                <a href="https://github.com/phani05040/result-server.git" target="_blank" class="btn">View Project</a>
            </div>
            <!-- Project 8 -->
            <div class="card">
                <h4>Result Server(BackEnd)</h4>
                <div>
                    <span class="tag">JAVA</span>
                    <span class="tag">PostMan</span>
                    <span class="tag">SpringBoot</span>
                    <span class="tag">DBMS</span>
                </div>
                <p>The core RESTful API infrastructure for result management, tested via Postman to ensure high availability and data integrity for school records.</p>
                <a href="https://github.com/phani05040/ResultServer.git" target="_blank" class="btn">View Project</a>
            </div>
            <!-- Project 9 -->
            <div class="card" style="background-color: yellow">
                <h4>Java Based App</h4>
                <div>
                    <span class="tag">JAVA</span>
                    <span class="tag">PostMan</span>
                    <span class="tag">cloudflared</span>
                    <span class="tag">DBMS</span>
                    <span class="tag">Android Studio</span>
                    <spam class="tag">Gradlew</spam>
                </div>
                <p>A Java Based Backend App where a very large techinical archecture is desined with complex connections and playes the game TRUTH OR DARE.</p>
                <a href="https://github.com/phani05040/PhanisApplication.git" target="_blank" class="btn">View Project</a>
            </div>
        </div>
    </section>

    <section id="certificates" class="container">
        <h3 class="section-title">Certificates</h3>
        <div class="grid-box">
            <div class="card">
                <h4>Quantum Computing</h4>
                <p><b>Issued by:</b> Smart Bridge</p>
                <p>Exploration of quantum algorithms and future computing paradigms.</p>
            </div>
            <div class="card">
                <h4>Industry 4.0 / IoT</h4>
                <p><b>Issued by:</b> NPTEL</p>
                <p>Specialization in Industrial Internet of Things and smart automation.</p>
            </div>
            <div class="card">
                <h4>Salesforce Developer</h4>
                <p><b>Issued by:</b> Salesforce</p>
                <p>Platform development and cloud architecture fundamentals.</p>
            </div>
            <div class="card">
                <h4>Java-Basics</h4>
                <p><b>Issued by:</b> Hacker Rank</p>
                <p>A qualified learner of complete Java-Basics.</p>
            </div>
            <div class="card">
                <h4>MongoDb</h4>
                <p><b>Issued by:</b> NPTEL</p>
                <p>Proof of completion of course of MongoDB.</p>
            </div>
        </div>
    </section>

    <footer id="contact" class="contact-section">
        <h2>Let's Collaborate</h2>
        <p>I'm always open to discussing new opportunities, creative projects, or technical innovations.</p>

        <!-- Academic & Technical Background -->
        <div style="max-width: 800px; margin: 0 auto 40px; text-align: left; background: rgba(255,255,255,0.05); padding: 30px; border-radius: 20px;">
            <h3 style="color: var(--secondary-accent); margin-top: 0;">Academic Journey</h3>
            <p style="margin-bottom: 20px;">
                <strong>B.Tech in Computer Science Engineering (2024 — 2027)</strong><br>
                Seshadri Rao Gudlavalleru Engineering College, Gudlavalleru<br>
                <em>Currently in Final Year | CGPA: 7.2</em>
            </p>
            <p style="margin-bottom: 20px;">
                <strong>Diploma in Computer Science Engineering (2021 — 2024)</strong><br>
                VKR, VNB &amp; AGK College of Engineering (Polytechnic), Gudivada<br>
                <em>Percentage: 80%</em>
            </p>

            <h3 style="color: var(--secondary-accent);">Technical Expertise</h3>
            <p>
                As a CSE professional, I have built a strong foundation in <strong>Software Development</strong> and <strong>System Architecture</strong>. My core technical competencies include:
            </p>
            <div style="display: flex; flex-wrap: wrap; gap: 10px; margin-top: 15px;">
                <span class="tag">Java &amp; Python</span>
                <span class="tag">SpringBoot &amp; Microservices</span>
                <span class="tag">Database Management (SQL/NoSQL)</span>
                <span class="tag">Web Technologies (HTML5, CSS3, JS, Bootstrap)</span>
                <span class="tag">Cloud &amp; DevOps (Docker, Salesforce)</span>
                <span class="tag">Artificial Intelligence &amp; ML</span>
            </div>
        </div>

        <!-- Contact Grid -->
        <div class="contact-grid">
            <div class="contact-item">dphani0504@gmail.com</div>
            <div class="contact-item">24485A0517@gecgudlavallerumic.in</div>
            <div class="contact-item">+91 6303195089</div>
            <div class="contact-item">GitHub: phani05040</div>
            <div class="contact-item">LinkedIn: devi-phanindra-pamarthi-26012b286</div>
        </div>

        <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
            <a href="mailto:dphani0504@gmail.com" class="btn" style="background: white; color: black;">Send a Message</a>
            <a href="https://www.linkedin.com/in/devi-phanindra-pamarthi-26012b286" target="_blank" class="btn" style="background: #0077b5; color: white;">LinkedIn Profile</a>
        </div>

        <p class="footer-note">Note: This portfolio is currently being updated with my latest engineering projects.</p>
    </footer>

<script src="index.js"></script>


</body></html>
