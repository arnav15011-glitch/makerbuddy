<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arnav Web Studio | Websites Made for You</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            background: #0f172a;
            color: white;
            line-height: 1.6;
        }

        header {
            padding: 20px 10%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: #0b1220;
            position: sticky;
            top: 0;
        }

        header h1 {
            color: #38bdf8;
        }

        header a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
        }

        .hero {
            padding: 80px 10%;
            text-align: center;
        }

        .hero h2 {
            font-size: 2.8rem;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.2rem;
            color: #cbd5e1;
            margin-bottom: 30px;
        }

        .btn {
            background: #38bdf8;
            color: black;
            padding: 12px 25px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
        }

        .section {
            padding: 60px 10%;
            text-align: center;
        }

        .dark {
            background: #1e293b;
        }

        .service-boxes, .pricing-boxes {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 40px;
        }

        .box {
            background: #0f172a;
            padding: 25px;
            border-radius: 8px;
        }

        .box h4 {
            margin-bottom: 15px;
            color: #38bdf8;
        }

        .price {
            font-size: 1.8rem;
            margin: 15px 0;
            color: #22c55e;
            font-weight: bold;
        }

        .contact a {
            display: block;
            margin-top: 10px;
            color: #38bdf8;
            font-weight: bold;
            text-decoration: none;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #0b1220;
            color: #94a3b8;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

<header>
    <h1>Arnav Web Studio</h1>
    <nav>
        <a href="#services">Services</a>
        <a href="#pricing">Pricing</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>I Build Professional Websites for Your Business</h2>
    <p>Custom, modern, mobile-friendly websites made to help you grow online.</p>
    <a href="#contact" class="btn">Order Your Website</a>
</section>

<section id="services" class="section dark">
    <h3>My Services</h3>
    <div class="service-boxes">
        <div class="box">
            <h4>Business Websites</h4>
            <p>Professional websites for shops, services, and companies.</p>
        </div>
        <div class="box">
            <h4>Portfolio Websites</h4>
            <p>Show your work as a designer, photographer, or freelancer.</p>
        </div>
        <div class="box">
            <h4>Landing Pages</h4>
            <p>Single-page sites focused on getting customers or sales.</p>
        </div>
    </div>
</section>

<section id="pricing" class="section">
    <h3>Pricing Plans</h3>
    <div class="pricing-boxes">
        <div class="box">
            <h4>Starter Website</h4>
            <p class="price">₹800</p>
            <p>1–3 pages<br>Mobile friendly<br>Basic design<br>Email support</p>
        </div>
        <div class="box">
            <h4>Business Website</h4>
            <p class="price">₹1,500</p>
            <p>Up to 6 pages<br>Modern design<br>Contact form<br>SEO basics</p>
        </div>
        <div class="box">
            <h4>Premium Website</h4>
            <p class="price">₹2,500</p>
            <p>Custom design<br>All pages needed<br>Priority support<br>Advanced features</p>
        </div>
    </div>
</section>

<section id="about" class="section dark">
    <h3>Why Choose Me?</h3>
    <p>I create fast, clean, and modern websites that work smoothly on phones, tablets, and computers.  
    Every site is designed to look professional and help you attract more customers.</p>
</section>

<section id="contact" class="section contact">
    <h3>Let’s Build Your Website</h3>
    <p>Contact me directly to get started:</p>
    
    <a href="mailto: arnav15042011@gmail.com">📧 arnav15042011@gmail.com</a>
    <a href="https://instagram.com/yourinstausername" target="_blank">📷 Instagram: @techbuddy_36</a>
</section>

<footer>
    © 2026 Arnav Web Studio. All rights reserved.
</footer>

</body>
</html>
