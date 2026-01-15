tml<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Deepashree's GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0a0e27 0%, #1a0b2e 25%, #16213e 50%, #0f0f23 75%, #000000 100%);
            color: #e0e0ff;
            padding: 40px 20px;
            min-height: 100vh;
            position: relative;
            overflow-x: hidden;
        }

        .stars {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .star {
            position: absolute;
            width: 2px;
            height: 2px;
            background: white;
            border-radius: 50%;
            animation: twinkle 3s infinite;
        }

        @keyframes twinkle {
            0%, 100% { opacity: 0.3; }
            50% { opacity: 1; }
        }

        .nebula {
            position: fixed;
            width: 300px;
            height: 300px;
            border-radius: 50%;
            filter: blur(60px);
            opacity: 0.3;
            pointer-events: none;
            z-index: 0;
        }

        .nebula1 {
            top: 10%;
            right: 10%;
            background: radial-gradient(circle, rgba(138, 43, 226, 0.4), transparent);
        }

        .nebula2 {
            bottom: 20%;
            left: 5%;
            background: radial-gradient(circle, rgba(75, 0, 130, 0.4), transparent);
        }

        .nebula3 {
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: radial-gradient(circle, rgba(0, 100, 200, 0.3), transparent);
            width: 400px;
            height: 400px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: rgba(15, 15, 35, 0.7);
            border: 2px solid rgba(138, 43, 226, 0.3);
            border-radius: 20px;
            padding: 50px;
            backdrop-filter: blur(10px);
            box-shadow: 0 0 40px rgba(138, 43, 226, 0.2), inset 0 0 60px rgba(0, 0, 0, 0.5);
            position: relative;
            z-index: 2;
        }

        h1 {
            font-size: 2.5em;
            margin-bottom: 30px;
            background: linear-gradient(90deg, #00d4ff, #a78bfa, #ff00ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-shadow: 0 0 30px rgba(138, 43, 226, 0.5);
        }

        .intro {
            line-height: 1.8;
            margin-bottom: 30px;
            font-size: 1.1em;
            color: #c8d0ff;
        }

        .seeking {
            margin-top: 20px;
            font-weight: 600;
            color: #00d4ff;
            font-size: 1.05em;
        }

        h2 {
            font-size: 1.8em;
            margin: 40px 0 20px 0;
            color: #a78bfa;
            text-shadow: 0 0 20px rgba(167, 139, 250, 0.5);
        }

        .about-content {
            line-height: 2;
            font-size: 1.05em;
            color: #d0d8ff;
        }

        .skills-line {
            margin: 8px 0;
        }

        .tech-icons {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
            margin-top: 30px;
        }

        .tech-icons img {
            height: 40px;
            filter: drop-shadow(0 0 10px rgba(138, 43, 226, 0.6));
            transition: transform 0.3s ease, filter 0.3s ease;
        }

        .tech-icons img:hover {
            transform: translateY(-5px) scale(1.1);
            filter: drop-shadow(0 0 20px rgba(138, 43, 226, 1));
        }

        .data-particle {
            position: fixed;
            width: 4px;
            height: 4px;
            background: #00d4ff;
            border-radius: 50%;
            pointer-events: none;
            animation: float 15s infinite;
            z-index: 1;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0) translateX(0); }
            25% { transform: translateY(-30px) translateX(20px); }
            50% { transform: translateY(-60px) translateX(-10px); }
            75% { transform: translateY(-30px) translateX(30px); }
        }
    </style>
</head>
<body>
    <div class="stars" id="starsContainer"></div>
    <div class="nebula nebula1"></div>
    <div class="nebula nebula2"></div>
    <div class="nebula nebula3"></div>

    <div class="container">
        <h1>Deepashree Srinivasa Rao Rannore</h1>
        
        <div class="intro">
            I'm a passionate and driven Data Science student currently pursuing my Master's degree at Northeastern University's Khoury College of Computer Sciences with a strong passion for Data Analysis, Automation, and Generative AI. With a background in Infrastructure Automation and a degree in Information Science Engineering. I bring a unique combination of systems knowledge and analytical skills. Currently, I'm expanding my expertise in statistical modeling, NLP, and AI applications.
        </div>
        
        <div class="seeking">
            I'm actively seeking Data Science, Machine Learning, or Automation internships for Spring, Summer, and Fall 2025.
        </div>

        <h2>About me</h2>
        
        <div class="about-content">
            <div class="skills-line">Skills I have acquired Throughout my academic and professional journey, includes:</div>
            <div class="skills-line">Languages: Python, R, PowerShell, JavaScript, SQL</div>
            <div class="skills-line">Tools & Platforms: ServiceNow Integration Hub, Ansible Automation Platform, Jupyter Notebook, R Studio</div>
            <div class="skills-line">Skills: Machine Learning, Data Analysis, Automation, Cloud Technologies (Azure)</div>
            <div class="skills-line">Web Development: HTML, CSS, PHP, MySQL</div>
        </div>

        <h2>I code with</h2>
        
        <div class="tech-icons">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="javascript logo" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="pytorch logo" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/powershell/powershell-original.svg" alt="powershell logo" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ansible/ansible-original.svg" alt="ansible logo" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="pandas logo" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="mysql logo" />
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg" alt="r logo" />
        </div>
    </div>

    <script>
        const starsContainer = document.getElementById('starsContainer');
        for (let i = 0; i < 200; i++) {
            const star = document.createElement('div');
            star.className = 'star';
            star.style.left = Math.random() * 100 + '%';
            star.style.top = Math.random() * 100 + '%';
            star.style.animationDelay = Math.random() * 3 + 's';
            star.style.opacity = Math.random() * 0.7 + 0.3;
            starsContainer.appendChild(star);
        }

        for (let i = 0; i < 30; i++) {
            const particle = document.createElement('div');
            particle.className = 'data-particle';
            particle.style.left = Math.random() * 100 + '%';
            particle.style.top = Math.random() * 100 + '%';
            particle.style.animationDelay = Math.random() * 15 + 's';
            particle.style.animationDuration = (Math.random() * 10 + 10) + 's';
            document.body.appendChild(particle);
        }
    </script>
</body>
</html>
