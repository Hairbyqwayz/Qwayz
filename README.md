<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HairbyQwayz</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 1rem 0;
        }
        nav a {
            margin: 0 1rem;
            color: #4CAF50;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 2rem;
        }
        .services, .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
        }
        .service, .gallery-item {
            width: 250px;
            border: 1px solid #ddd;
            border-radius: 8px;
            text-align: center;
            padding: 1rem;
            background-color: #fff;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
        a.button {
            display: inline-block;
            padding: 0.5rem 1rem;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 1rem;
        }
    </style>
</head>
<body>

<header>
    <h1>HairbyQwayz</h1>
    <p>All Styles, All Genders. Braids, Haircuts & More!</p>
</header>

<nav>
    <a href="#services">Services</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
</nav>

<section id="services">
    <h2>Our Services</h2>
    <div class="services">
        <div class="service">
            <h3>Boho Braids</h3>
            <p>Effortless and chic braids with a bohemian flair.</p>
        </div>
        <div class="service">
            <h3>Knotless Braids</h3>
            <p>Comfortable, long-lasting braids with a natural look.</p>
        </div>
        <div class="service">
            <h3>Men's Cornrows</h3>
            <p>Clean, stylish cornrows for men of all ages.</p>
        </div>
        <div class="service">
            <h3>Box Braids</h3>
            <p>Classic and versatile box braids tailored to your style.</p>
        </div>
        <div class="service">
            <h3>Haircuts</h3>
            <p>Sharp, clean cuts to keep you looking your best.</p>
        </div>
    </div>
</section>

<section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
        <div class="gallery-item">
            <img src="https://via.placeholder.com/250" alt="Boho Braids" style="width:100%; border-radius: 8px;">
            <p>Boho Braids</p>
        </div>
        <div class="gallery-item">
            <img src="https://via.placeholder.com/250" alt="Knotless Braids" style="width:100%; border-radius: 8px;">
            <p>Knotless Braids</p>
        </div>
        <div class="gallery-item">
            <img src="https://via.placeholder.com/250" alt="Men's Cornrows" style="width:100%; border-radius: 8px;">
            <p>Men's Cornrows</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Follow us on Instagram for updates and bookings:</p>
    <a href="https://instagram.com/hairbyqwayz" target="_blank" class="button">Visit Instagram</a>
    <p>Or book directly on our website:</p>
    <a href="https://hairbyqwayz.square.site" target="_blank" class="button">Book Now</a>
</section>

<footer>
    <p>© 2024 HairbyQwayz. All Rights Reserved.</p>
</footer>

</body>
</html>
