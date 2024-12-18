<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>About Me</h2>
        <p>I'm an elite coder passionate about web development, AI/ML, and automation.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li>Project 1: Music Streaming App</li>
            <li>Project 2: AI Chatbot</li>
            <li>Project 3: Automation Tools</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form id="contactForm">
            <label for="name">Name:</label>
            <input type="text" id="name" placeholder="Your Name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" placeholder="Your Email" required>

            <button type="submit">Send</button>
        </form>
        <p id="formMessage"></p>
    </section>

    <script src="script.js"></script>
</body>
</html>
