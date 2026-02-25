<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Simon Gatuku | Web Developer</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f6f9;
            color: #333;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-top: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }

        section {
            padding: 40px 20px;
            max-width: 900px;
            margin: auto;
        }

        h2 {
            color: #1f2937;
            border-bottom: 3px solid #2563eb;
            display: inline-block;
            padding-bottom: 5px;            
        }

        .skill-card {
            background: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: 0.3s ease;
        }
        .skill-card:hover {
            transform: translateY(-5px);
            
        }

        form {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 20px;
        }

        input, textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            padding: 10px ;
            background-color: #2563eb;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            
        }

        button:hover {
            background-color: #1e40af;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #1f2937;
            color: white;
            margin-top: 40px;
        }
    </style>

</head>

<body>

    <header>
        <h1>Simon Gatuku</h1>
        <img src="Simon.jpg.jpg" alt="Simon Gatuku sitting on   a gray couch wearing a black Under Armour cap, dark hoodie with white text reading 'IS OUR QUARANTINE', and white sleeves with tattoos. He is looking downward in a contemplative, relaxed pose. Black and white photograph." class="profile-img">
        </header>

        
<!-- NAV -->
<nav>
    <h1>Simon Gatuku</h1>
    <ul>
        <li><a href="#about">Home</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<!-- HERO -->
<section id="about">
    <img src="simon.jpg" alt="Simon Gatuku">
    <div class="hero-text">
        <h2>Hi, I'm Simon 👋</h2>
        <p>
            I'm a passionate web developer who builds clean, responsive, and modern websites.
            I specialize in front-end development and enjoy turning complex problems into simple,
            beautiful, and intuitive designs. When I'm not coding, I explore new technologies
            and continuously improve my skills.
        </p>
    </div>
</section>

<!-- SKILLS -->
<section class="skills" id="skills">
    <h2>My Skills</h2>
    <div class="skills-container">

        <div class="skill-card">
            <div class="icon">🐍</div>
            <h3>Python</h3>
            <p>Used for automation, AI, backend development and problem solving.</p>
        </div>

        <div class="skill-card">
            <div class="icon">☕</div>
            <h3>JavaScript</h3>
            <p>Makes websites interactive and dynamic with modern web features.</p>
        </div>

        <div class="skill-card">
            <div class="icon">💻</div>
            <h3>HTML</h3>
            <p>Structures and organizes content on the web.</p>
        </div>

        <div class="skill-card">
            <div class="icon">⚡</div>
            <h3>CSS</h3>
            <p>Designs and styles web pages to look professional and modern.</p>
        </div>

    </div>
</section>

<!-- CONTACT -->
<section id="contact">
    <h2>Contact Me</h2>
    <form>
        <div>
            <label>Name</label>
            <input type="text" placeholder="Your name">
        </div>

        <div>
            <label>Email</label>
            <input type="email" placeholder="Your email">
        </div>

        <div>
            <label>Message</label>
            <textarea rows="5" placeholder="Write your message here"></textarea>
        </div>

        <button type="submit">Send Message</button>
    </form>
</section>

<!-- FOOTER -->
<footer>
    <p>© 2026 Simon Gatuku. All rights reserved.</p>
</footer>

</body>
</html>
