<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sajib - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <nav class="navbar">
        <div class="nav-content">
            <div class="logo">S</div> <!-- You can replace with your own logo image -->
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <section id="home" class="hero">
        <div class="hero-content">
            <div class="hero-image-wrapper">
                <img src="profile.jpg" alt="Sajib" class="hero-image">
            </div>
            <div class="hero-text">
                <h1>Sajib</h1>
                <p class="subtitle">Computer Science And Engineering Student & Aspiring Software Engineer</p>
                <div class="cta-buttons">
                    <a href="#contact" class="cta-primary">Get in Touch</a>
                    <a href="#about" class="cta-secondary">Learn More</a>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>I am a passionate Computer Science student dedicated to becoming a skilled software engineer. My journey in programming began with mastering C, C++, and Java, and I'm continuously expanding my knowledge by learning new and powerful programming languages.</p>
                    <p>I combine my technical skills with a strong work ethic to create innovative solutions and contribute to the ever-evolving world of technology.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="skills">
        <div class="container">
            <h2>Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <i class="fas fa-code"></i>
                    <h3>C/C++</h3>
                    <p>Proficient in system programming and algorithms</p>
                </div>
                <div class="skill-card">
                    <i class="fab fa-java"></i>
                    <h3>Java</h3>
                    <p>Object-oriented programming and application development</p>
                </div>
                <div class="skill-card">
                    <i class="fas fa-laptop-code"></i>
                    <h3>Web Development</h3>
                    <p>HTML, CSS, JavaScript</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Get in Touch</h2>
            <div class="contact-grid">
                <div class="contact-info">
                    <div class="contact-item">
                        <i class="fas fa-phone"></i>
                        <p>+880 1919444828</p>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <p>your.email@example.com</p> <!-- Replace with your real email -->
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <p>Boalmari, Faridpur, Bangladesh</p>
                    </div>
                </div>
                <div class="social-links">
                    <a href="https://github.com/gr-sajib01" target="_blank" class="social-icon"><i class="fab fa-github"></i></a>
                    <a href="https://www.linkedin.com/" target="_blank" class="social-icon"><i class="fab fa-linkedin"></i></a>
                    <a href="https://www.facebook.com/" target="_blank" class="social-icon"><i class="fab fa-facebook"></i></a>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Sajib. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
