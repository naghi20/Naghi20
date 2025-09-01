<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DevOps Engineer Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0d1117 0%, #161b22 100%);
            color: #c9d1d9;
            line-height: 1.6;
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .container {
            display: flex;
            flex-direction: column;
            gap: 2rem;
        }
        
        header {
            text-align: center;
            padding: 2rem 0;
            border-bottom: 1px solid #30363d;
            margin-bottom: 1rem;
        }
        
        h1 {
            font-size: 2.5rem;
            color: #58a6ff;
            margin-bottom: 1rem;
        }
        
        .tagline {
            font-size: 1.2rem;
            color: #8b949e;
            margin-bottom: 1.5rem;
        }
        
        .intro {
            font-size: 1.1rem;
            max-width: 800px;
            margin: 0 auto 1.5rem;
            text-align: center;
            line-height: 1.8;
        }
        
        .section {
            background: #161b22;
            border-radius: 10px;
            padding: 1.5rem;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }
        
        .section-title {
            font-size: 1.5rem;
            color: #58a6ff;
            margin-bottom: 1.5rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #30363d;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .tools-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(80px, 1fr));
            gap: 1.5rem;
            justify-items: center;
        }
        
        .tool-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 0.5rem;
            transition: transform 0.3s ease;
        }
        
        .tool-item:hover {
            transform: translateY(-5px);
        }
        
        .tool-icon {
            font-size: 2.5rem;
            color: #58a6ff;
        }
        
        .tool-name {
            font-size: 0.85rem;
            text-align: center;
            color: #8b949e;
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin-top: 1rem;
        }
        
        .contact-link {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            color: #58a6ff;
            text-decoration: none;
            padding: 0.5rem 1rem;
            border: 1px solid #30363d;
            border-radius: 6px;
            transition: all 0.3s ease;
        }
        
        .contact-link:hover {
            background: #1a5ebb;
            color: #fff;
        }
        
        @media (max-width: 768px) {
            .tools-grid {
                grid-template-columns: repeat(auto-fill, minmax(70px, 1fr));
                gap: 1rem;
            }
            
            .contact-links {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>DevOps Engineer</h1>
            <p class="tagline">Passionate about Cloud, DevOps, and Open Source</p>
            <p class="intro">Passionate DevOps Engineer from Bahrain, working on Cloud and DevOps for 3+ years now. Feel free to reach out for any Freelance Projects.</p>
        </header>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-code"></i> Languages and Tools</h2>
            <div class="tools-grid">
                <div class="tool-item">
                    <i class="fab fa-dev tool-icon"></i>
                    <span class="tool-name">DevOps</span>
                </div>
                <div class="tool-item">
                    <i class="fas fa-project-diagram tool-icon"></i>
                    <span class="tool-name">Microservices</span>
                </div>
                <div class="tool-item">
                    <i class="fas fa-cube tool-icon"></i>
                    <span class="tool-name">Containers</span>
                </div>
                <div class="tool-item">
                    <i class="fab fa-linux tool-icon"></i>
                    <span class="tool-name">Linux</span>
                </div>
                <div class="tool-item">
                    <i class="fab fa-ubuntu tool-icon"></i>
                    <span class="tool-name">Ubuntu</span>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-terminal"></i> Programming Languages</h2>
            <div class="tools-grid">
                <div class="tool-item">
                    <i class="fab fa-bash tool-icon"></i>
                    <span class="tool-name">Bash</span>
                </div>
                <div class="tool-item">
                    <i class="fab fa-python tool-icon"></i>
                    <span class="tool-name">Python</span>
                </div>
                <div class="tool-item">
                    <i class="fas fa-code tool-icon"></i>
                    <span class="tool-name">Groovy</span>
                </div>
                <div class="tool-item">
                    <i class="fab fa-java tool-icon"></i>
                    <span class="tool-name">Java</span>
                </div>
                <div class="tool-item">
                    <i class="fab fa-golang tool-icon"></i>
                    <span class="tool-name">Go</span>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-cloud"></i> DevOps Stack</h2>
            <div class="tools-grid">
                <div class="tool-item">
                    <i class="fab fa-aws tool-icon"></i>
                    <span class="tool-name">AWS</span>
                </div>
                <div class="tool-item">
                    <i class="fab fa-ansible tool-icon"></i>
                    <span class="tool-name">Ansible</span>
                </div>
                <div class="tool-item">
                    <i class="fas fa-server tool-icon"></i>
                    <span class="tool-name">Terraform</span>
                </div>
                <div class="tool-item">
                    <i class="fab fa-docker tool-icon"></i>
                    <span class="tool-name">Docker</span>
                </div>
                <div class="tool-item">
                    <i class="fas fa-ship tool-icon"></i>
                    <span class="tool-name">Kubernetes</span>
                </div>
                <div class="tool-item">
                    <i class="fas fa-network-wired tool-icon"></i>
                    <span class="tool-name">Nginx</span>
                </div>
                <div class="tool-item">
                    <i class="fas fa-chart-line tool-icon"></i>
                    <span class="tool-name">Prometheus</span>
                </div>
                <div class="tool-item">
                    <i class="fas fa-chart-bar tool-icon"></i>
                    <span class="tool-name">Grafana</span>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-tasks"></i> Project Management</h2>
            <div class="tools-grid">
                <div class="tool-item">
                    <i class="fab fa-git tool-icon"></i>
                    <span class="tool-name">Git</span>
                </div>
                <div class="tool-item">
                    <i class="fab fa-github tool-icon"></i>
                    <span class="tool-name">GitHub</span>
                </div>
                <div class="tool-item">
                    <i class="fab fa-bitbucket tool-icon"></i>
                    <span class="tool-name">Bitbucket</span>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-code"></i> Editor</h2>
            <div class="tools-grid">
                <div class="tool-item">
                    <i class="fab fa-vscode tool-icon"></i>
                    <span class="tool-name">VS Code</span>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2 class="section-title"><i class="fas fa-envelope"></i> Connect with Me</h2>
            <p style="text-align: center; margin-bottom: 1rem;">📫 How to reach me: naghi@live.com</p>
            <div class="contact-links">
                <a href="mailto:naghi@live.com" class="contact-link">
                    <i class="fas fa-envelope"></i>
                    <span>Email</span>
                </a>
                <a href="https://github.com/naghi20" class="contact-link">
                    <i class="fab fa-github"></i>
                    <span>GitHub</span>
                </a>
                <a href="https://linkedin.com/in/naghi20" class="contact-link">
                    <i class="fab fa-linkedin"></i>
                    <span>LinkedIn</span>
                </a>
            </div>
        </section>
    </div>
</body>
</html>
