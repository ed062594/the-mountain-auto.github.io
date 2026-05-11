<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Mountain Auto</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: url('https://images.unsplash.com/photo-1503376780353-7e6692767b70') center/cover no-repeat;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 6px black;
        }
        header h1 {
            font-size: 4rem;
            margin: 0;
        }
        nav {
            background: #222;
            padding: 15px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
        }
        .section {
            padding: 50px 10%;
        }
        .inventory-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }
        .car-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        .car-card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .car-card h3 {
            margin: 15px;
        }
        .car-card p {
            margin: 0 15px 20px;
        }
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>The Mountain Auto</h1>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#inventory">Inventory</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about" class="section">
    <h2>About Us</h2>
    <p>
        At <strong>The Mountain Auto</strong>, we specialize in rugged, reliable vehicles built for the mountains, the trails, and the open road. 
        Based in the heart of Colorado, we bring adventure‑ready performance to every driver.
    </p>
</section>

<section id="inventory" class="section">
    <h2>Featured Inventory</h2>
    <div class="inventory-grid">
        <div class="car-card">
            <img src="https://images.unsplash.com/photo-1504215680853-026ed2a45def" alt="SUV">
            <h3>2024 TrailMaster SUV</h3>
            <p>Perfect for off‑road adventures and mountain terrain.</p>
        </div>
        <div class="car-card">
            <img src="https://images.unsplash.com/photo-1517948430535-1e246ba55c3b" alt="Truck">
            <h3>2023 Summit Pickup</h3>
            <p>High torque, high durability, built for hauling and climbing.</p>
        </div>
        <div class="car-card">
            <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70" alt="Sports Car">
            <h3>2024 RidgeRunner Sport</h3>
            <p>Mountain‑grade performance with sports‑car agility.</p>
        </div>
    </div>
</section>

<section id="services" class="section">
    <h2>Our Services</h2>
    <ul>
        <li>Full automotive repair & diagnostics</li>
        <li>Off‑road customization packages</li>
        <li>Vehicle inspections & maintenance</li>
        <li>Financing assistance</li>
    </ul>
</section>

<section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Email: info@themountainauto.com</p>
    <p>Phone: (555) 123‑4567</p>
    <p>Location: Denver, Colorado</p>
</section>

<footer>
    © 2026 The Mountain Auto — Built for the Climb
</footer>

</body>
</html>
