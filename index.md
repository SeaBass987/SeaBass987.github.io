
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[Grant Ryan] | Cybersecurity Portfolio</title>
    <style>
        /* HACKER MATRIX THEME STYLES */
        :root {
            --matrix-green: #00ff41;
            --terminal-black: #0a0a0a;
            --dark-green: #003b00;
            --light-green: #90ff90;
            --gray: #2a2a2a;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background-color: var(--terminal-black);
            color: var(--matrix-green);
            font-family: 'Courier New', monospace;
            line-height: 1.6;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        /* Glitch/Matrix Effect Header */
        .matrix-header {
            text-align: center;
            margin-bottom: 50px;
            padding: 30px;
            border-bottom: 2px solid var(--matrix-green);
            position: relative;
            overflow: hidden;
        }
        
        .glitch {
            font-size: 3.5rem;
            font-weight: bold;
            position: relative;
            animation: glitch 5s infinite;
        }
        
        @keyframes glitch {
            0%, 100% { text-shadow: 2px 2px 0px #ff00ff, -2px -2px 0px #00ffff; }
            50% { text-shadow: -2px -2px 0px #ff00ff, 2px 2px 0px #00ffff; }
        }
        
        .subtitle {
            color: var(--light-green);
            margin-top: 10px;
            font-size: 1.3rem;
        }
        
        /* Section Styles */
        section {
            margin: 40px 0;
            padding: 25px;
            background: rgba(0, 255, 65, 0.05);
            border: 1px solid var(--dark-green);
            border-radius: 5px;
            transition: all 0.3s;
        }
        
        section:hover {
            border-color: var(--matrix-green);
            box-shadow: 0 0 15px rgba(0, 255, 65, 0.2);
        }
        
        h2 {
            color: var(--light-green);
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 1px solid var(--dark-green);
            display: flex;
            align-items: center;
        }
        
        h2 i {
            margin-right: 15px;
        }
        
        /* Education & Certification Cards */
        .card-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 20px;
        }
        
        .card {
            background: var(--gray);
            padding: 20px;
            border-left: 4px solid var(--matrix-green);
            transition: transform 0.3s;
        }
        
        .card:hover {
            transform: translateY(-5px);
        }
        
        .card h3 {
            color: white;
            margin-bottom: 10px;
        }
        
        .date {
            color: #888;
            font-size: 0.9rem;
            margin: 5px 0;
        }
        
        /* Training Badges */
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 15px;
        }
        
        .badge {
            background: var(--dark-green);
            padding: 10px 20px;
            border-radius: 20px;
            border: 1px solid var(--matrix-green);
            display: inline-block;
        }
        
        /* Projects */
        .project {
            margin: 25px 0;
            padding: 20px;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 5px;
        }
        
        .project h3 {
            color: white;
            margin-bottom: 10px;
        }
        
        .tech-stack {
            margin-top: 15px;
        }
        
        .tech-tag {
            display: inline-block;
            background: var(--dark-green);
            color: var(--light-green);
            padding: 5px 15px;
            margin: 5px 5px 0 0;
            border-radius: 3px;
            font-size: 0.9rem;
        }
        
        /* Contact */
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 20px;
        }
        
        .contact-links a {
            color: var(--matrix-green);
            text-decoration: none;
            padding: 10px 20px;
            border: 1px solid var(--matrix-green);
            border-radius: 5px;
            transition: all 0.3s;
        }
        
        .contact-links a:hover {
            background: var(--matrix-green);
            color: black;
        }
        
        /* Matrix Rain Effect Container */
        #matrix-rain {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
            opacity: 0.1;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .card-grid {
                grid-template-columns: 1fr;
            }
            
            .contact-links {
                flex-direction: column;
                align-items: center;
            }
            
            .glitch {
                font-size: 2.5rem;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Matrix Rain Background -->
    <canvas id="matrix-rain"></canvas>
    
    <!-- Header -->
    <header class="matrix-header">
        <h1 class="glitch">[Grant Ryan]</h1>
        <p class="subtitle">Aspiring Cybersecurity Professional | Cloud Security Engineer</p>
        <p>>_ A 4.0 graduate with a Bachelors of Science in Cybersecurity from Bellevue University, Nebraska (August, 2025). Looking to begin my career and advance into a security engineer position with a focus on cloud security engineering and machine learning integration.</p>
    </header>
    
    <!-- Education -->
    <section id="education">
        <h2><i class="fas fa-graduation-cap"></i> Education</h2>
        <div class="card">
            <h3>Bachelor of Science in Cybersecurity</h3>
            <p class="date">[Bellevue University] | [2025] | [4.0 GPA]</p>
            <p><strong>Relevant Coursework:</strong> Network Security, Ethical Hacking, Cryptography, Digital Forensics, Risk Management, Database Management, Python Coding</p>
            
        </div>
    </section>
    
    <!-- Certifications -->
    <section id="certifications">
        <h2><i class="fas fa-certificate"></i> Certifications</h2>
        <div class="card-grid">
            <div class="card">
                <h3>Google Cybersecurity Professional Certificate</h3>
                <p class="date">Issued: [September, 2025] </p>
                <p>Validates baseline security skills and knowledge</p>
            </div>
            <div class="card">
                <h3>TryHackMe Cyber Security 101</h3>
                <p class="date">Completed: [December, 2025]</p>
                <p>Learned everything needed to embark on a cyber security career path</p>
            </div>
            <div class="card">
                <h3>[Other Certification]</h3>
                <p class="date">Issued: [Date]</p>
                <p>[Brief description]</p>
            </div>
        </div>
    </section>
    
    <!-- Training Experience -->
    <section id="training">
        <h2><i class="fas fa-laptop-code"></i> Hands-On Training</h2>
        
        <div class="project">
            <h3>TryHackMe</h3>
            <p><strong>Rank:</strong> [Mage] | <strong>Rooms Completed:</strong> [85]</p>
            <p><strong>Learning Paths:</strong> Pre Security, Cyber Security 101, Security Engineer </p>
            <iframe src="https://tryhackme.com/api/v2/badges/public-profile?userPublicId=3481474" style='border:none;'></iframe>
            <div class="badges">
                <span class="badge">Top 6%</span>
                <span class="badge">100+ Rooms</span>
                <span class="badge">Network Security</span>
            </div>
        </div>
        
        <div class="project">
            <h3>Hellbound Hacker</h3>
            <p><strong>Completed Challenges:</strong> Prerequisite Challenges | Prerequisite Challenges</p>
        </div>
        
    </section>
    
    <!-- Personal Projects -->
    <section id="projects">
        <h2><i class="fas fa-project-diagram"></i> Personal Projects</h2>
        
        <div class="project">
            <h3>Home Security Lab</h3>
            <p>Built a virtualized Linux environment with an assortment of tools for penetration testing and SOC operations.</p>
            <div class="tech-stack">
                <span class="tech-tag">Oracle Virtualbox</span>
                <span class="tech-tag">Burpsuite</span>
                <span class="tech-tag">Nmap</span>
                <span class="tech-tag">Metasploit</span>
                <span class="tech-tag">Wireshark</span>
                <span class="tech-tag">Snort</span>
                <span class="tech-tag">Splunk</span>
            </div>
        </div>
        
        <div class="project">
            <h3>Network Vulnerability Scanner</h3>
            <p>Developed a Python script that automates network reconnaissance and vulnerability detection using Nmap and custom modules.</p>
            <div class="tech-stack">
                <span class="tech-tag">Python</span>
                <span class="tech-tag">Nmap</span>
                <span class="tech-tag">Multithreading</span>
                <span class="tech-tag">Report Generation</span>
            </div>
        </div>
        
        <div class="project">
            <h3>SIEM Dashboard with ELK Stack</h3>
            <p>Configured Elasticsearch, Logstash, and Kibana to collect and visualize security events from multiple sources.</p>
            <div class="tech-stack">
                <span class="tech-tag">ELK Stack</span>
                <span class="tech-tag">Log Analysis</span>
                <span class="tech-tag">Dashboards</span>
                <span class="tech-tag">Alerting</span>
            </div>
        </div>
    </section>
    
    <!-- Skills -->
    <section id="skills">
        <h2><i class="fas fa-tools"></i> Technical Skills</h2>
        <div class="card-grid">
            <div class="card">
                <h3>Offensive Security</h3>
                <p>Penetration Testing · Vulnerability Assessment · Social Engineering · Exploit Development</p>
                <div class="tech-stack">
                    <span class="tech-tag">Metasploit</span>
                    <span class="tech-tag">Burp Suite</span>
                    <span class="tech-tag">Nmap</span>
                    <span class="tech-tag">John the Ripper</span>
                </div>
            </div>
            <div class="card">
                <h3>Defensive Security</h3>
                <p>SIEM · IDS/IPS · Firewall Configuration · Incident Response · Threat Hunting</p>
                <div class="tech-stack">
                    <span class="tech-tag">Wireshark</span>
                    <span class="tech-tag">Snort</span>
                    <span class="tech-tag">Splunk</span>
                    <span class="tech-tag">GRC Tools</span>
                </div>
            </div>
            <div class="card">
                <h3>Programming & Tools</h3>
                <p>Python · Bash · PowerShell · Git · Linux/Windows Administration · Virtualization</p>
                <div class="tech-stack">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Bash</span>
                    <span class="tech-tag">Docker</span>
                    <span class="tech-tag">Git</span>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Contact -->
    <section id="contact">
        <h2><i class="fas fa-envelope"></i> Contact & Links</h2>
        <p style="text-align: center; margin: 20px 0;">Available for security roles, internships, and collaboration</p>
        <div class="contact-links">
            <a href="mailto:your.email@example.com"><i class="fas fa-envelope"></i> Email</a>
            <a href="https://github.com/yourusername" target="_blank"><i class="fab fa-github"></i> GitHub</a>
            <a href="https://linkedin.com/in/yourprofile" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
            <a href="https://tryhackme.com/p/yourprofile" target="_blank"><i class="fas fa-terminal"></i> TryHackMe</a>
        </div>
    </section>
    
    <footer style="text-align: center; margin-top: 50px; padding: 20px; color: #666; border-top: 1px solid var(--dark-green);">
        <p>© [Year] [Your Name]. All rights reserved.</p>
        <p style="font-size: 0.9rem; margin-top: 10px;">Ethical Hacker | Security through transparency and continuous learning</p>
    </footer>
    
    <!-- Matrix Rain Animation -->
    <script>
        // Matrix Rain Effect
        const canvas = document.getElementById('matrix-rain');
        const ctx = canvas.getContext('2d');
        
        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;
        
        const letters = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789$+-*/=%"#&_()!?;:[]{}10';
        const fontSize = 14;
        const columns = canvas.width / fontSize;
        const drops = Array(Math.floor(columns)).fill(1);
        
        function drawMatrix() {
            ctx.fillStyle = 'rgba(0, 10, 0, 0.05)';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            
            ctx.fillStyle = '#00ff41';
            ctx.font = `${fontSize}px monospace`;
            
            for (let i = 0; i < drops.length; i++) {
                const text = letters.charAt(Math.floor(Math.random() * letters.length));
                ctx.fillText(text, i * fontSize, drops[i] * fontSize);
                
                if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) {
                    drops[i] = 0;
                }
                drops[i]++;
            }
        }
        
        // Update canvas on resize
        window.addEventListener('resize', function() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        });
        
        // Animate matrix rain
        setInterval(drawMatrix, 50);
        
        // Simple typewriter effect for header subtitle
        const subtitle = document.querySelector('.subtitle');
        if (subtitle) {
            const originalText = subtitle.textContent;
            subtitle.textContent = '';
            let i = 0;
            function typeWriter() {
                if (i < originalText.length) {
                    subtitle.textContent += originalText.charAt(i);
                    i++;
                    setTimeout(typeWriter, 50);
                }
            }
            setTimeout(typeWriter, 1000);
        }
    </script>
</body>
</html>
