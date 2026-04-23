<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Grime Fighters | Ventura County Pressure Washing</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <nav class="navbar">
        <div class="nav-container">
            <div class="nav-left">
                <a href="#"><img src="logo.png" alt="The Grime Fighters" class="header-logo"></a>
            </div>
            
            <div class="nav-center">
                <ul class="nav-links">
                    <li><a href="#services">Services</a></li>
                    <li><a href="#quote">Free Estimate</a></li>
                    <li><a href="tel:8056603585">Call Now</a></li>
                </ul>
            </div>

            <div class="nav-right">
                <a href="#quote" class="nav-btn">Book Today</a>
            </div>
        </div>
    </nav>

    <section class="hero">
        <div class="hero-content">
            <h1>WE FIGHT THE <span class="highlight-blue">GRIME</span><br>YOU GET THE <span class="highlight-orange">SHINE</span></h1>
            <p>Professional Pressure Washing & Solar Panel Cleaning in Ventura County.</p>
            <a href="#quote" class="cta-main">Restore Your Property</a>
        </div>
    </section>

    <section class="services-section" id="services">
        <h2 class="section-title">Our Specialized Services</h2>
        <div class="grid">
            <div class="service-card">
                <div class="icon">🏠</div>
                <h3>House Siding</h3>
                <p>Gentle soft-wash techniques. Safe for pets and plants.</p>
            </div>
            <div class="service-card">
                <div class="icon">🚗</div>
                <h3>Driveways & Patios</h3>
                <p>Industrial-grade pressure for concrete and stone restoration.</p>
            </div>
            <div class="service-card">
                <div class="icon">☀️</div>
                <h3>Solar Panels</h3>
                <p>Maximize energy output with streak-free specialized cleaning.</p>
            </div>
        </div>
    </section>

    <section class="quote-section" id="quote">
        <div class="form-wrapper">
            <div class="form-text">
                <h2>Ready for a Refresh?</h2>
                <p>Contact <strong>Neal Chambers</strong> at <strong>(805) 660-3585</strong> or fill out the form for a free estimate.</p>
                <div class="guarantee-badge">🐾 Pet & Plant Safe Solutions</div>
            </div>
            <form action="https://formspree.io/f/xpqkylpd" method="POST" class="main-form">
                <input type="text" name="name" placeholder="Full Name" required>
                <input type="tel" name="phone" placeholder="Phone Number" required>
                <select name="service" required>
                    <option value="" disabled selected>Select Service</option>
                    <option value="Solar Panels">Solar Panels</option>
                    <option value="Residential">Residential Wash</option>
                    <option value="Driveway">Driveway/Concrete</option>
                    <option value="Other">Other</option>
                </select>
                <textarea name="message" placeholder="Property address or specific details..." rows="4"></textarea>
                <button type="submit">Send My Free Quote</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 The Grime Fighters | Serving Ventura County, CA</p>
    </footer>

</body>
</html>
