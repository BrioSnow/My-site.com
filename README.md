# My-site.com<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nyangoso Construction Company - Nyamira Kenya</title>

<style>
    body {
        margin: 0;
        font-family: 'Segoe UI', sans-serif;
        background: #f4f6f8;
    }

    header {
        background: linear-gradient(to right, #1f2937, #374151);
        color: white;
        padding: 20px;
        text-align: center;
    }

    nav {
        background: #111827;
        text-align: center;
        padding: 10px;
    }

    nav a {
        color: white;
        margin: 0 15px;
        text-decoration: none;
        font-weight: bold;
    }

    nav a:hover {
        color: #f59e0b;
    }

    .hero {
        background: url('project1.jpg') center/cover no-repeat;
        color: white;
        padding: 90px 20px;
        text-align: center;
    }

    section {
        padding: 40px 20px;
        max-width: 1100px;
        margin: auto;
    }

    h2 {
        text-align: center;
        color: #1f2937;
    }

    .services ul {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        list-style: none;
        padding: 0;
    }

    .services li {
        background: white;
        margin: 10px;
        padding: 15px;
        border-radius: 8px;
        text-align: center;
        box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .gallery {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 15px;
    }

    .gallery img {
        width: 100%;
        border-radius: 10px;
    }

    .contact {
        text-align: center;
    }

    .whatsapp-btn {
        display: inline-block;
        margin-top: 15px;
        padding: 12px 20px;
        background: #25D366;
        color: white;
        text-decoration: none;
        border-radius: 6px;
        font-weight: bold;
    }

    iframe {
        width: 100%;
        height: 300px;
        border: 0;
        margin-top: 20px;
        border-radius: 10px;
    }

    footer {
        background: #111827;
        color: white;
        text-align: center;
        padding: 15px;
    }
</style>

</head>
<body>

<header>
    <h1>Nyangoso Construction Company</h1>
    <p>Building Excellence in Nyamira & Beyond</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero">
    <h1>Trusted Builders in Nyamira, Kenya</h1>
    <p>Quality Construction • Affordable Prices • Reliable Team</p>
</div>

<section id="about">
    <h2>About Us</h2>
    <p>
        Nyangoso Construction Company is based in Nyamira, Kenya. We specialize in modern
        residential and commercial construction, delivering strong, durable and beautiful
        buildings. Our team is committed to quality workmanship and customer satisfaction.
    </p>
</section>

<section id="services" class="services">
    <h2>Our Services</h2>
    <ul>
        <li>🏠 Residential Houses</li>
        <li>🏢 Commercial Buildings</li>
        <li>🔧 Renovation & Repairs</li>
        <li>🧱 Plastering & Finishing</li>
        <li>📐 Project Supervision</li>
    </ul>
</section>

<section id="projects">
    <h2>Completed Projects</h2>
    <div class="gallery">
        <img src="project1.jpg" alt="Modern house">
        <img src="project2.jpg" alt="Plastering work">
        <img src="project3.jpg" alt="Construction site">
    </div>
</section>

<section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>📍 Nyamira, Kenya</p>
    <p>📞 0799833744</p>

    <a class="whatsapp-btn" href="https://wa.me/254799833744" target="_blank">
        Chat on WhatsApp
    </a>

    <!-- Google Map -->
    <iframe 
        src="https://maps.google.com/maps?q=Nyamira%20Kenya&t=&z=13&ie=UTF8&iwloc=&output=embed">
    </iframe>
</section>

<footer>
    <p>&copy; 2026 Nyangoso Construction Company | Nyamira, Kenya</p>
</footer>

</body>
</html>
