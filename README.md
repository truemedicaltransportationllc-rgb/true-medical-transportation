<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SafeRide NEMT Services</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f7f7f7;
            color: #333;
        }

        header {
            background: #0066cc;
            color: white;
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            margin: 0;
            font-size: 28px;
        }

        nav a {
            color: white;
            margin-left: 20px;
            text-decoration: none;
            font-weight: bold;
        }

        .hero {
            background: url('https://images.unsplash.com/photo-1584433144859-1fc3ab64a957?auto=format&fit=crop&w=1500&q=80') center/cover;
            height: 350px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
        }

        .hero h2 {
            font-size: 40px;
            margin: 0;
        }

        .section {
            padding: 50px 40px;
        }

        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            flex: 1;
            min-width: 260px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .card h3 {
            margin-top: 0;
        }

        .contact-form {
            background: white;
            padding: 30px;
            border-radius: 10px;
            max-width: 500px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        form input, form textarea {
            width: 100%;
            padding: 12px;
            margin-top: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 6px;
            font-size: 16px;
        }

        form button {
            background: #0066cc;
            color: white;
            padding: 12px 20px;
            border: none;
            cursor: pointer;
            border-radius: 6px;
            font-size: 16px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #222;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>

<body>

<header>
    <h1>SafeRide NEMT</h1>
    <nav>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
        <a href="#about">About</a>
    </nav>
</header>

<section class="hero">
    <h2>Reliable, Comfortable Non-Emergency Medical Transportation</h2>
</section>

<section id="about" class="section">
    <h2>About Us</h2>
    <p>
        SafeRide NEMT provides dependable and compassionate non-emergency medical transportation
        for seniors, people with disabilities, and anyone needing safe, on-time transport to medical appointments.
    </p>
</section>

<section id="services" class="section">
    <h2>Our Services</h2>

    <div class="services">
        <div class="card">
            <h3>Wheelchair Transport</h3>
            <p>Fully equipped vehicles for safe and comfortable wheelchair-accessible transportation.</p>
        </div>

        <div class="card">
            <h3>Stretcher Transport</h3>
            <p>Professional stretcher services for patients needing non-emergency lying transport.</p>
        </div>

        <div class="card">
            <h3>Doctor Appointments</h3>
            <p>Reliable rides to medical appointments, therapy sessions, and check-ups.</p>
        </div>

        <div class="card">
            <h3>Hospital Discharge</h3>
            <p>Safe, timely pickups after hospital discharge with full assistance.</p>
        </div>
    </div>
</section>

<section id="contact" class="section">
    <h2>Contact Us</h2>

    <div class="contact-form">
        <form>
            <label>Your Name</label>
            <input type="text" placeholder="Enter your name">

            <label>Phone Number</label>
            <input type="text" placeholder="Enter your phone number">

            <label>Message</label>
            <textarea rows="4" placeholder="How can we assist you?"></textarea>

            <button type="submit">Submit</button>
        </form>
    </div>
</section>

<footer>
    © 2025 SafeRide NEMT — All Rights Reserved
</footer>

</body>
</html>
