
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kritgya Saini's Portfolio</title>
    <style>
        body {
            background-color: #000;
            color: #fff;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            padding: 20px 0;
            border-bottom: 1px solid #333;
        }

        h1 {
            font-size: 3em;
            color: #ff4081;
        }

        p {
            font-size: 1.2em;
            color: #80d8ff;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 20px 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: #ff4081;
            font-size: 1.2em;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #80d8ff;
        }

        section {
            margin: 40px 0;
        }

        h2 {
            font-size: 2em;
            color: #ff4081;
            margin-bottom: 20px;
        }

        footer {
            padding: 20px 0;
            border-top: 1px solid #333;
            margin-top: 40px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            font-size: 1.2em;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Kritgya Saini</h1>
            <p>Cyber Security Enthusiast</p>
        </header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <section id="about">
            <h2>About Me</h2>
            <p>I am a hard-working and enthusiastic individual passionate about learning and growing in the field of Cyber Security. Currently, I am part of the National Service Scheme (NSS), where I volunteer in various events. I am committed to continuously improving my skills and knowledge to make significant contributions in the cybersecurity domain.</p>
        </section>
        <section id="education">
            <h2>Education</h2>
            <ul>
                <li><strong>B.Tech, Cyber Security</strong> - Graphic Era Deemed University (2021 - 2025)</li>
                <li><strong>Senior Secondary (XII), Science</strong> - Rainbow School, Saharanpur (2020)</li>
                <li><strong>Secondary (X)</strong> - Rainbow School, Saharanpur (2018)</li>
            </ul>
        </section>
        <section id="experience">
            <h2>Work Experience</h2>
            <p><strong>Cyber Security</strong> - The Website Makers, Virtual Internship (Feb 2024 - Mar 2024)</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li><strong>Library Management System</strong> (Nov 2023)</li>
                <li><strong>Number Plate Detection and Recognition</strong> (Aug 2023)</li>
            </ul>
        </section>
        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>Ethical Hacking - Beginner</li>
                <li>C Programming - Beginner</li>
                <li>Python - Beginner</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Email: shauryasaini51@gmail.com</p>
            <p>Phone: +91 6397846964</p>
            <p>Location: Dehradun</p>
        </section>
        <footer>
            <p>© 2024 Kritgya Saini</p>
        </footer>
    </div>
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const navLinks = document.querySelectorAll('nav ul li a');
            navLinks.forEach(link => {
                link.addEventListener('click', function(event) {
                    event.preventDefault();
                    const targetId = this.getAttribute('href').substring(1);
                    const targetSection = document.getElementById(targetId);
                    window.scrollTo({
                        top: targetSection.offsetTop,
                        behavior: 'smooth'
                    });
                });
            });
        });
    </script>
</body>
</html>
