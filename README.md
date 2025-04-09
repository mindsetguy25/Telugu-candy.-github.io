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
