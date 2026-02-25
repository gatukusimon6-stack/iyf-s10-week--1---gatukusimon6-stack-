<!DOCTYPE html>
<html lang="en">
<head>
    <title>Simon Gatuku | Web Developer</title>
    <link rel="stylesheet" href="style.css">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
}

body {
    background: #f8f9fc;
    color: #333;
    line-height: 1.6;
}

/* NAVIGATION */
nav {
    background: #111827;
    color: white;
    padding: 20px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav h1 {
    font-size: 22px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 25px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: 500;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #38bdf8;
}

/* HERO SECTION */
#about {
    padding: 80px 8%;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 50px;
    background: white;
}

#about img{
        width: 300px;
        border-radius: 15px;
        box-shadow: 0 8px 25px rgba(0,0,0,0.08);
}

.hero-text h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

.hero-text p {
    max-width: 600px;
    color: #555;
}

/* SKILLS */
.skills {
    padding: 80px 8%;
    text-align: center;
}

.skills h2 {
    font-size: 32px;
    margin-bottom: 50px;
}

.skills-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
}

.skill-card {
    background: rgb(255, 255, 255);
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 8px 25px rgba(0,0,0,0.08);
    transition: 0.3s;
}

.skill-card:hover {
    transform: translateY(-10px);
}

.skill-card .icon {
    font-size: 40px;
    margin-bottom: 15px;
}

.skill-card h3 {
    margin-bottom: 10px;
}

/* CONTACT */
#contact {
    padding: 80px 8%;
    background: rgb(255, 255, 255);
}

#contact h2 {
    text-align: center;
    margin-bottom: 40px;
}

form {
    max-width: 600px;
    margin: auto;
}

form div {
    margin-bottom: 20px;
}

form label {
    display: block;
    margin-bottom: 5px;
    font-weight: 500;
}

form input, form textarea {
    width: 100%;
    padding: 12px;
    border-radius: 8px;
    border: 1px solid #ccc;
    outline: none;
}

form input:focus, form textarea:focus {
    border-color: #38bdf8;
}

form button {
    width: 100%;
    padding: 14px;
    background: #111827;
    color: white;
    border: none;
    border-radius: 8px;
    font-size: 16px;
    cursor: pointer;
    transition: 0.3s;
}

form button:hover {
    background: #38bdf8;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 20px;
    background: #111827;
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
