# Telugu-candy.-github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Welcome to My GitHub</h1>
            <p>Developer | Designer | Creator</p>
            <div class="theme-toggle">
                <button id="theme-btn"><i class="fas fa-moon"></i></button>
            </div>
        </div>
    </header>

    <nav>
        <div class="container">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <main class="container">
        <section id="about">
            <h2>About Me</h2>
            <div class="about-content">
                <img src="https://via.placeholder.com/150" alt="Profile Picture" class="profile-img">
                <p>Hello! I'm a passionate developer who loves building innovative solutions. This is my GitHub portfolio where I showcase my projects and contributions to open source.</p>
                <p>When I'm not coding, you can find me reading tech blogs, contributing to open source, or exploring new technologies.</p>
            </div>
        </section>

        <section id="projects">
            <h2>Featured Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Project 1</h3>
                    <p>A brief description of what this project is about and the technologies used.</p>
                    <a href="#" class="btn">View on GitHub</a>
                </div>
                <div class="project-card">
                    <h3>Project 2</h3>
                    <p>A brief description of what this project is about and the technologies used.</p>
                    <a href="#" class="btn">View on GitHub</a>
                </div>
                <div class="project-card">
                    <h3>Project 3</h3>
                    <p>A brief description of what this project is about and the technologies used.</p>
                    <a href="#" class="btn">View on GitHub</a>
                </div>
            </div>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h3>Languages</h3>
                    <ul>
                        <li>JavaScript</li>
                        <li>Python</li>
                        <li>HTML/CSS</li>
                        <li>Java</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Frameworks</h3>
                    <ul>
                        <li>React</li>
                        <li>Node.js</li>
                        <li>Django</li>
                        <li>Bootstrap</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Tools</h3>
                    <ul>
                        <li>Git/GitHub</li>
                        <li>VS Code</li>
                        <li>Docker</li>
                        <li>Postman</li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Get In Touch</h2>
            <div class="contact-content">
                <p>Feel free to reach out for collaborations or just to say hi!</p>
                <div class="social-links">
                    <a href="https://github.com/yourusername" target="_blank"><i class="fab fa-github"></i></a>
                    <a href="https://linkedin.com/in/yourusername" target="_blank"><i class="fab fa-linkedin"></i></a>
                    <a href="mailto:youremail@example.com"><i class="fas fa-envelope"></i></a>
                    <a href="https://twitter.com/yourusername" target="_blank"><i class="fab fa-twitter"></i></a>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; <span id="year"></span> My GitHub Portfolio. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
:root {
    --primary-color: #2d3436;
    --secondary-color: #0984e3;
    --text-color: #333;
    --bg-color: #f5f6fa;
    --card-bg: #fff;
    --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    --transition: all 0.3s ease;
}

[data-theme="dark"] {
    --primary-color: #f5f6fa;
    --secondary-color: #74b9ff;
    --text-color: #f5f6fa;
    --bg-color: #2d3436;
    --card-bg: #1e272e;
    --shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: var(--text-color);
    background-color: var(--bg-color);
    transition: var(--transition);
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

header {
    background-color: var(--primary-color);
    color: white;
    padding: 60px 0;
    text-align: center;
    position: relative;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2rem;
    opacity: 0.9;
}

.theme-toggle {
    position: absolute;
    top: 20px;
    right: 20px;
}

#theme-btn {
    background: none;
    border: none;
    color: white;
    font-size: 1.5rem;
    cursor: pointer;
    transition: var(--transition);
}

#theme-btn:hover {
    transform: rotate(30deg);
}

nav {
    background-color: var(--secondary-color);
    position: sticky;
    top: 0;
    z-index: 100;
}

nav ul {
    display: flex;
    list-style: none;
    justify-content: center;
}

nav ul li a {
    color: white;
    text-decoration: none;
    padding: 15px 20px;
    display: inline-block;
    transition: var(--transition);
}

nav ul li a:hover {
    background-color: rgba(255, 255, 255, 0.2);
}

section {
    padding: 60px 0;
}

h2 {
    font-size: 2rem;
    margin-bottom: 30px;
    color: var(--primary-color);
    text-align: center;
    position: relative;
}

h2::after {
    content: '';
    display: block;
    width: 80px;
    height: 4px;
    background-color: var(--secondary-color);
    margin: 10px auto;
}

.about-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    max-width: 800px;
    margin: 0 auto;
}

.profile-img {
    border-radius: 50%;
    margin-bottom: 20px;
    border: 4px solid var(--secondary-color);
}

.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 30px;
    margin-top: 30px;
}

.project-card {
    background-color: var(--card-bg);
    border-radius: 8px;
    padding: 25px;
    box-shadow: var(--shadow);
    transition: var(--transition);
}

.project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
}

.project-card h3 {
    color: var(--secondary-color);
    margin-bottom: 10px;
}

.btn {
    display: inline-block;
    background-color: var(--secondary-color);
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    margin-top: 15px;
    transition: var(--transition);
}

.btn:hover {
    background-color: var(--primary-color);
}

.skills-container {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 30px;
    margin-top: 30px;
}

.skill-category {
    background-color: var(--card-bg);
    border-radius: 8px;
    padding: 25px;
    box-shadow: var(--shadow);
}

.skill-category h3 {
    color: var(--secondary-color);
    margin-bottom: 15px;
}

.skill-category ul {
    list-style: none;
}

.skill-category ul li {
    margin-bottom: 8px;
    position: relative;
    padding-left: 20px;
}

.skill-category ul li::before {
    content: '▹';
    position: absolute;
    left: 0;
    color: var(--secondary-color);
}

.contact-content {
    text-align: center;
    max-width: 600px;
    margin: 0 auto;
}

.social-links {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-top: 30px;
}

.social-links a {
    color: var(--primary-color);
    font-size: 2rem;
    transition: var(--transition);
}

.social-links a:hover {
    color: var(--secondary-color);
    transform: translateY(-3px);
}

footer {
    background-color: var(--primary-color);
    color: white;
    text-align: center;
    padding: 20px 0;
}

@media (max-width: 768px) {
    header h1 {
        font-size: 2rem;
    }
    
    nav ul {
        flex-direction: column;
        align-items: center;
    }
    
    .projects-grid {
        grid-template-columns: 1fr;
    }
}

// Theme toggle functionality
const themeBtn = document.getElementById('theme-btn');
const body = document.body;

// Check for saved theme preference or use preferred color scheme
const savedTheme = localStorage.getItem('theme') || 
                   (window.matchMedia('(prefers-color-scheme: dark)').matches ? 'dark' : 'light');

// Apply the saved theme
if (savedTheme === 'dark') {
    body.setAttribute('data-theme', 'dark');
    themeBtn.innerHTML = '<i class="fas fa-sun"></i>';
} else {
    body.removeAttribute('data-theme');
    themeBtn.innerHTML = '<i class="fas fa-moon"></i>';
}

// Theme toggle button click event
themeBtn.addEventListener('click', () => {
    if (body.getAttribute('data-theme') === 'dark') {
        body.removeAttribute('data-theme');
        localStorage.setItem('theme', 'light');
        themeBtn.innerHTML = '<i class="fas fa-moon"></i>';
    } else {
        body.setAttribute('data-theme', 'dark');
        localStorage.setItem('theme', 'dark');
        themeBtn.innerHTML = '<i class="fas fa-sun"></i>';
    }
});

// Smooth scrolling for navigation links
document.querySelectorAll('nav a').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
        e.preventDefault();
        
        const targetId = this.getAttribute('href');
        const targetElement = document.querySelector(targetId);
        
        window.scrollTo({
            top: targetElement.offsetTop - 70,
            behavior: 'smooth'
        });
    });
});

// Update copyright year
document.getElementById('year').textContent = new Date().getFullYear();
