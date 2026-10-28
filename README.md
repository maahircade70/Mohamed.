<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jamaal Cade | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #0f172a;
            color: white;
            line-height: 1.6;
        }

        header {
            background: #111827;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            color: #38bdf8;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }

        nav a:hover {
            color: #38bdf8;
        }

        .hero {
            text-align: center;
            padding: 80px 20px;
        }

        .hero h2 {
            font-size: 35px;
            margin-bottom: 15px;
        }

        .hero span {
            color: #38bdf8;
        }

        .hero p {
            color: #cbd5e1;
            margin-bottom: 25px;
        }

        .button {
            display: inline-block;
            background: #38bdf8;
            color: #0f172a;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
        }

        section {
            padding: 45px 20px;
            max-width: 900px;
            margin: auto;
        }

        section h2 {
            text-align: center;
            color: #38bdf8;
            margin-bottom: 25px;
        }

        .card {
            background: #1e293b;
            padding: 25px;
            border-radius: 12px;
            margin-bottom: 20px;
        }

        .card h3 {
            color: #38bdf8;
            margin-bottom: 10px;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 12px;
        }

        .skills span {
            background: #1e293b;
            border: 1px solid #38bdf8;
            padding: 10px 18px;
            border-radius: 8px;
        }

        #contact {
            text-align: center;
        }

        footer {
            background: #111827;
            padding: 20px;
            text-align: center;
            color: #cbd5e1;
        }
    </style>
</head>

<body>

    <header>
        <h1>Jamaal Cade</h1>

        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="hero" id="home">
        <h2>Hello, I'm <span>Jamaal Cade</span></h2>
        <p>Beginner Web Developer | HTML Learner | Future Programmer</p>
        <a href="#projects" class="button">View My Work</a>
    </div>

    <section id="about">
        <h2>About Me</h2>

        <div class="card">
            <p>
                Hello! My name is Jamaal Cade.
                I am learning web development and programming.
                I enjoy creating websites and improving my coding skills.
                My goal is to become a professional web developer.
            </p>
        </div>
    </section>

    <section id="skills">
        <h2>My Skills</h2>

        <div class="skills">
            <span>HTML</span>
            <span>CSS</span>
            <span>Web Design</span>
            <span>GitHub</span>
            <span>Learning JavaScript</span>
        </div>
    </section>

    <section id="projects">
        <h2>My Projects</h2>

        <div class="card">
            <h3>Project 1: My First Website</h3>
            <p>A simple website created using HTML and CSS.</p>
        </div>

        <div class="card">
            <h3>Project 2: Portfolio Website</h3>
            <p>A personal website to showcase my skills and projects.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>

        <div class="card">
            <p>Want to work with me? Contact me below.</p>
            <br>

            <a href="mailto:your@email.com" class="button">
                Send Me an Email
            </a>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Jamaal Cade. All Rights Reserved.</p>
    </footer>

</body>
</html>
