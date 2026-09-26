# NGO-WEBSITE-
NGo website project 
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Hope Foundation | NGO</title>

    <link rel="stylesheet" href="css/style.css">
</head>

<body>

<!-- NAVBAR -->
<header class="header">

    <a href="index.html" class="logo">
        Hope<span>Foundation</span>
    </a>

    <nav class="navbar" id="navbar">
        <a href="index.html" class="active">Home</a>
        <a href="about.html">About</a>
        <a href="projects.html">Projects</a>
        <a href="gallery.html">Gallery</a>
        <a href="reviews.html">Reviews</a>
        <a href="contact.html">Contact</a>
    </nav>

    <button class="menu-btn" id="menuBtn">☰</button>

</header>


<!-- HERO -->
<section class="hero">

    <div class="hero-content">

        <p class="small-title">TOGETHER WE CAN MAKE A DIFFERENCE</p>

        <h1>
            Building a Better
            <span>Tomorrow</span>
        </h1>

        <p>
            We work together to support communities, empower people
            and create opportunities for a brighter future.
        </p>

        <div class="hero-buttons">
            <a href="projects.html" class="btn">Our Projects</a>
            <a href="contact.html" class="btn btn-outline">Become a Volunteer</a>
        </div>

    </div>

</section>


<!-- ABOUT -->
<section class="section">

    <div class="section-title">
        <p>WHO WE ARE</p>
        <h2>Making a Difference Together</h2>
    </div>

    <div class="about-grid">

        <div class="about-text">

            <h3>We Believe in Humanity</h3>

            <p>
                Hope Foundation is a non-profit organization dedicated
                to improving lives through education, healthcare,
                community development and social welfare.
            </p>

            <p>
                Our mission is to create sustainable opportunities and
                help communities become stronger and independent.
            </p>

            <a href="about.html" class="text-btn">
                Learn More →
            </a>

        </div>

        <div class="about-card">

            <div class="icon">❤️</div>

            <h3>Our Mission</h3>

            <p>
                To serve people with compassion and create positive
                social change.
            </p>

        </div>

    </div>

</section>


<!-- SERVICES / CAUSES -->
<section class="section light">

    <div class="section-title">

        <p>WHAT WE DO</p>

        <h2>Our Causes</h2>

    </div>


    <div class="cards">

        <div class="card">

            <div class="card-icon">📚</div>

            <h3>Education</h3>

            <p>
                Supporting children with education and learning
                opportunities.
            </p>

            <a href="projects.html">Read More →</a>

        </div>


        <div class="card">

            <div class="card-icon">🏥</div>

            <h3>Healthcare</h3>

            <p>
                Helping communities access essential healthcare
                services.
            </p>

            <a href="projects.html">Read More →</a>

        </div>


        <div class="card">

            <div class="card-icon">🌱</div>

            <h3>Environment</h3>

            <p>
                Working towards a cleaner and sustainable environment.
            </p>

            <a href="projects.html">Read More →</a>

        </div>


        <div class="card">

            <div class="card-icon">🤝</div>

            <h3>Community</h3>

            <p>
                Empowering communities through social development.
            </p>

            <a href="projects.html">Read More →</a>

        </div>

    </div>

</section>


<!-- STATS -->
<section class="stats">

    <div class="stat">
        <h2>500+</h2>
        <p>Volunteers</p>
    </div>

    <div class="stat">
        <h2>10K+</h2>
        <p>People Helped</p>
    </div>

    <div class="stat">
        <h2>50+</h2>
        <p>Projects</p>
    </div>

    <div class="stat">
        <h2>15+</h2>
        <p>Years Experience</p>
    </div>

</section>


<!-- CTA -->
<section class="cta">

    <h2>Want to Make a Difference?</h2>

    <p>
        Join us as a volunteer and become part of our mission.
    </p>

    <a href="contact.html" class="btn">
        Join Us
    </a>

</section>


<!-- FOOTER -->
<footer class="footer">

    <div class="footer-grid">

        <div>

            <h3>Hope Foundation</h3>

            <p>
                Working together for a better and brighter future.
            </p>

        </div>


        <div>

            <h3>Quick Links</h3>

            <a href="about.html">About</a>
            <a href="projects.html">Projects</a>
            <a href="gallery.html">Gallery</a>

        </div>


        <div>

            <h3>Contact</h3>

            <p>📍 Varanasi, India</p>
            <p>📞 +91 98765 43210</p>
            <p>✉️ info@hopefoundation.org</p>

        </div>

    </div>


    <div class="copyright">

        © 2026 Hope Foundation. All Rights Reserved.

    </div>

</footer>


<script src="js/script.js"></script>

</body>
</html>
style.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    color: #222;
    background: #fff;
    line-height: 1.6;
}


/* HEADER */

.header {
    width: 100%;
    height: 75px;

    display: flex;
    align-items: center;
    justify-content: space-between;

    padding: 0 7%;

    background: #ffffff;

    position: sticky;
    top: 0;
    z-index: 1000;

    box-shadow: 0 2px 12px rgba(0,0,0,0.08);
}


.logo {
    font-size: 25px;
    font-weight: 800;

    text-decoration: none;

    color: #222;
}

.logo span {
    color: #0a8f5b;
}


.navbar {
    display: flex;
    gap: 28px;
}

.navbar a {
    text-decoration: none;
    color: #333;
    font-weight: 600;
    transition: 0.3s;
}

.navbar a:hover,
.navbar a.active {
    color: #0a8f5b;
}


.menu-btn {
    display: none;

    border: none;
    background: none;

    font-size: 28px;

    cursor: pointer;
}


/* HERO */

.hero {

    min-height: 650px;

    display: flex;
    align-items: center;

    padding: 80px 7%;

    background:
        linear-gradient(
            90deg,
            rgba(0,0,0,0.72),
            rgba(0,0,0,0.30)
        ),
        url("../images/hero.jpg");

    background-size: cover;
    background-position: center;

    color: white;
}


.hero-content {
    max-width: 650px;
}


.small-title {
    color: #70e1ad;

    font-weight: bold;

    letter-spacing: 2px;

    margin-bottom: 15px;
}


.hero h1 {

    font-size: 60px;

    line-height: 1.1;

    margin-bottom: 25px;
}


.hero h1 span {
    color: #70e1ad;
}


.hero p {
    font-size: 18px;

    margin-bottom: 30px;
}


.hero-buttons {
    display: flex;

    gap: 15px;

    flex-wrap: wrap;
}


/* BUTTON */

.btn {

    display: inline-block;

    padding: 13px 25px;

    background: #0a8f5b;

    color: white;

    text-decoration: none;

    border-radius: 6px;

    font-weight: bold;

    transition: 0.3s;
}


.btn:hover {
    background: #067447;

    transform: translateY(-2px);
}


.btn-outline {

    background: transparent;

    border: 2px solid white;
}


.btn-outline:hover {
    background: white;
    color: #0a8f5b;
}


/* SECTIONS */

.section {

    padding: 80px 7%;
}


.light {
    background: #f6faf8;
}


.section-title {

    text-align: center;

    max-width: 700px;

    margin: 0 auto 50px;
}


.section-title p {

    color: #0a8f5b;

    font-weight: bold;

    letter-spacing: 2px;

    margin-bottom: 8px;
}


.section-title h2 {

    font-size: 38px;

    color: #222;
}


/* ABOUT */

.about-grid {

    max-width: 1100px;

    margin: auto;

    display: grid;

    grid-template-columns: 1.5fr 1fr;

    gap: 50px;

    align-items: center;
}


.about-text h3 {

    font-size: 30px;

    margin-bottom: 18px;
}


.about-text p {

    margin-bottom: 15px;

    color: #666;
}


.text-btn {

    display: inline-block;

    margin-top: 10px;

    color: #0a8f5b;

    font-weight: bold;

    text-decoration: none;
}


.about-card {

    padding: 45px 35px;

    background: white;

    border-radius: 12px;

    box-shadow: 0 10px 30px rgba(0,0,0,0.08);

    text-align: center;
}


.icon {

    font-size: 50px;

    margin-bottom: 15px;
}


.about-card h3 {
    margin-bottom: 10px;
}


/* CARDS */

.cards {

    max-width: 1200px;

    margin: auto;

    display: grid;

    grid-template-columns: repeat(4, 1fr);

    gap: 22px;
}


.card {

    background: white;

    padding: 30px 22px;

    border-radius: 10px;

    box-shadow: 0 5px 20px rgba(0,0,0,0.06);

    transition: 0.3s;
}


.card:hover {

    transform: translateY(-7px);

    box-shadow: 0 12px 30px rgba(0,0,0,0.12);
}


.card-icon {

    font-size: 40px;

    margin-bottom: 15px;
}


.card h3 {

    font-size: 21px;

    margin-bottom: 10px;
}


.card p {

    color: #666;

    margin-bottom: 15px;
}


.card a {

    color: #0a8f5b;

    text-decoration: none;

    font-weight: bold;
}


/* STATS */

.stats {

    background: #0a8f5b;

    color: white;

    display: grid;

    grid-template-columns: repeat(4, 1fr);

    text-align: center;

    padding: 55px 7%;
}


.stat h2 {

    font-size: 40px;

    margin-bottom: 5px;
}


/* CTA */

.cta {

    padding: 90px 7%;

    text-align: center;

    background: #e9f8f1;
}


.cta h2 {

    font-size: 38px;

    margin-bottom: 10px;
}


.cta p {

    margin-bottom: 25px;

    color: #666;
}


/* FOOTER */

.footer {

    background: #151b19;

    color: white;

    padding: 60px 7% 20px;
}


.footer-grid {

    display: grid;

    grid-template-columns: 2fr 1fr 1fr;

    gap: 40px;

    max-width: 1200px;

    margin: auto;
}


.footer h3 {

    margin-bottom: 15px;
}


.footer p {

    color: #bbb;

    margin-bottom: 8px;
}


.footer a {

    display: block;

    color: #bbb;

    text-decoration: none;

    margin-bottom: 8px;
}


.footer a:hover {

    color: white;
}


.copyright {

    border-top: 1px solid #333;

    text-align: center;

    color: #999;

    margin-top: 40px;

    padding-top: 20px;
}


/* MOBILE */

@media (max-width: 900px) {

    .navbar {

        position: absolute;

        top: 75px;
        left: 0;

        width: 100%;

        background: white;

        display: none;

        flex-direction: column;

        padding: 20px 7%;

        box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }


    .navbar.show {
        display: flex;
    }


    .menu-btn {
        display: block;
    }


    .hero h1 {
        font-size: 45px;
    }


    .cards {

        grid-template-columns: repeat(2, 1fr);
    }


    .about-grid {

        grid-template-columns: 1fr;
    }


    .stats {

        grid-template-columns: repeat(2, 1fr);

        gap: 30px;
    }


    .footer-grid {

        grid-template-columns: 1fr 1fr;
    }
}


@media (max-width: 600px) {

    .header {
        padding: 0 5%;
    }


    .hero {

        min-height: 600px;

        padding: 60px 5%;
    }


    .hero h1 {

        font-size: 38px;
    }


    .hero p {

        font-size: 16px;
    }


    .section {

        padding: 60px 5%;
    }


    .section-title h2 {

        font-size: 30px;
    }


    .cards {

        grid-template-columns: 1fr;
    }


    .stats {

        grid-template-columns: 1fr 1fr;

        padding: 40px 5%;
    }


    .stat h2 {

        font-size: 30px;
    }


    .footer {

        padding: 50px 5% 20px;
    }


    .footer-grid {

        grid-template-columns: 1fr;
    }
}


