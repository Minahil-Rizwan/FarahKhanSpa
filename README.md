<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Farah Khan Spa - Luxury Massage & Wellness Center</title>
    <link rel="icon" type="image/png" href="logo.png">
    <link rel="stylesheet" href="styles.css">
</head>
    <style>
        {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
}

/* Header & Navigation */
header {
    background: linear-gradient(135deg, #2c3e50 0%, #3d5a6c 100%);
    padding: 1rem 0;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

nav {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 2rem;
}

.logo {
    font-size: 1.8rem;
    font-weight: bold;
    color: #e8d4b8;
    display: flex;
    align-items: center;
    gap: 0.5rem;
}

.logo-img {
    height: 40px;
    width: 40px;
    object-fit: contain;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 2rem;
}

nav a {
    color: white;
    text-decoration: none;
    transition: color 0.3s;
    font-size: 1rem;
}

nav a:hover {
    color: #e8d4b8;
}

/* Hero Section */
.hero {
    background: linear-gradient(rgba(44, 62, 80, 0.7), rgba(52, 73, 94, 0.7)), 
                url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 600"><defs><pattern id="spa" x="0" y="0" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="50" cy="50" r="30" fill="%23e8d4b8" opacity="0.1"/></pattern></defs><rect width="1200" height="600" fill="%23f5f5f5"/><rect width="1200" height="600" fill="url(%23spa)"/></svg>');
    background-size: cover;
    background-position: center;
    color: white;
    text-align: center;
    padding: 150px 2rem;
    min-height: 600px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.hero h1 {
    font-size: 3.5rem;
    margin-bottom: 1rem;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
}

.hero p {
    font-size: 1.3rem;
    margin-bottom: 2rem;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
}

.cta-button {
    background: #e8d4b8;
    color: #2c3e50;
    padding: 1rem 2.5rem;
    font-size: 1.1rem;
    border: none;
    border-radius: 50px;
    cursor: pointer;
    transition: all 0.3s;
    font-weight: bold;
    display: inline-block;
    text-decoration: none;
}

.cta-button:hover {
    background: #d4c4a8;
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

/* Container */
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
}

/* Sections */
section {
    padding: 4rem 0;
}

section h2 {
    font-size: 2.5rem;
    text-align: center;
    margin-bottom: 3rem;
    color: #2c3e50;
    position: relative;
    padding-bottom: 1rem;
}

section h2::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    width: 60px;
    height: 3px;
    background: #e8d4b8;
}

/* Services Section */
#services {
    background: #f9f7f4;
}

.services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 2rem;
}

.service-card {
    background: white;
    padding: 2rem;
    border-radius: 10px;
    text-align: center;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    transition: transform 0.3s, box-shadow 0.3s;
}

.service-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.15);
}

.service-card h3 {
    font-size: 1.5rem;
    margin: 1rem 0;
    color: #2c3e50;
}

.service-card .price {
    font-size: 1.3rem;
    color: #e8d4b8;
    font-weight: bold;
    margin: 1rem 0;
}

.service-icon {
    font-size: 3rem;
    margin-bottom: 1rem;
}

/* About Section */
#about {
    background: white;
}

.about-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
    align-items: center;
}

.about-content img {
    width: 100%;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

.about-content h3 {
    color: #2c3e50;
    margin: 1rem 0;
    font-size: 1.8rem;
}

.about-content p {
    color: #666;
    margin-bottom: 1rem;
    line-height: 1.8;
}

/* Testimonials Section */
#testimonials {
    background: linear-gradient(135deg, #2c3e50 0%, #3d5a6c 100%);
    color: white;
}

#testimonials h2 {
    color: white;
}

#testimonials h2::after {
    background: #e8d4b8;
}

.testimonials-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.testimonial-card {
    background: rgba(255,255,255,0.1);
    padding: 2rem;
    border-radius: 10px;
    border: 1px solid rgba(255,255,255,0.2);
}

.testimonial-card p {
    margin-bottom: 1rem;
    font-style: italic;
}

.testimonial-author {
    font-weight: bold;
    color: #e8d4b8;
}

.stars {
    color: #ffc107;
    margin-bottom: 1rem;
}

/* Contact Section */
#contact {
    background: #f9f7f4;
}

.contact-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
}

.contact-info {
    background: white;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    max-width: 600px;
    margin: 0 auto;
}

.contact-info-only {
    display: flex;
    justify-content: center;
}

.contact-info h3 {
    color: #2c3e50;
    margin-bottom: 1.5rem;
}

.contact-info-item {
    margin-bottom: 1.5rem;
    display: flex;
    gap: 1rem;
    align-items: start;
}

.contact-icon {
    font-size: 1.5rem;
    color: #e8d4b8;
    margin-top: 0.2rem;
}

.contact-form {
    background: white;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

.form-group {
    margin-bottom: 1.5rem;
}

.form-group label {
    display: block;
    margin-bottom: 0.5rem;
    color: #2c3e50;
    font-weight: 500;
}

.form-group input,
.form-group textarea {
    width: 100%;
    padding: 0.8rem;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-family: inherit;
    font-size: 1rem;
    transition: border-color 0.3s;
}

.form-group input:focus,
.form-group textarea:focus {
    outline: none;
    border-color: #e8d4b8;
    box-shadow: 0 0 5px rgba(232, 212, 184, 0.3);
}

.form-group textarea {
    resize: vertical;
    min-height: 120px;
}

.submit-btn {
    background: #2c3e50;
    color: white;
    padding: 0.8rem 2rem;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 1rem;
    transition: background 0.3s;
    width: 100%;
}

.submit-btn:hover {
    background: #34495e;
}

/* Footer */
footer {
    background: #2c3e50;
    color: white;
    text-align: center;
    padding: 2rem 0;
    margin-top: 2rem;
}

footer p {
    margin: 0.5rem 0;
}

.social-links {
    margin-top: 1rem;
}

.social-links a {
    color: #e8d4b8;
    text-decoration: none;
    margin: 0 1rem;
    transition: color 0.3s;
}

.social-links a:hover {
    color: white;
}

/* Responsive */
@media (max-width: 768px) {
    .hero h1 {
        font-size: 2rem;
    }

    .hero p {
        font-size: 1rem;
    }

    nav ul {
        flex-direction: column;
        gap: 1rem;
    }

    section h2 {
        font-size: 2rem;
    }

    .about-content,
    .contact-content {
        grid-template-columns: 1fr;
    }

    .hero {
        padding: 100px 1rem;
    }

    section {
        padding: 2rem 0;
    }
}
    </style>
<body>
    <!-- Navigation -->
    <header>
        <nav>
            <div class="logo"><img src="logo.png" alt="Farah Khan Spa" class="logo-img"> Farah Khan Spa</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <h1>Relax & Rejuvenate</h1>
        <p>Experience luxury spa treatments in a serene environment</p>
        <a href="#contact" class="cta-button">Book an Appointment</a>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About Farah Khan Spa</h2>
            <div class="about-content">
                <div>
                    <h3>Welcome to Our Sanctuary</h3>
                    <p>Farah Khan Spa is dedicated to providing the highest quality massage and wellness services in a peaceful, luxurious environment. With over 15 years of experience, our team of certified therapists is committed to your wellbeing.</p>
                    <p>We use only premium, natural products and traditional techniques combined with modern spa practices to ensure you receive the best treatment possible.</p>
                    <p>Whether you're seeking relief from stress, muscle tension, or simply want to pamper yourself, our spa is your perfect getaway.</p>
                </div>
                <div>
                    <img src="spa-about.jpeg" alt="Spa Interior" style="width: 100%; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <div class="contact-info-only">
                <div class="contact-info">
                    <h3>Get in Touch</h3>
                    
                    <div class="contact-info-item">
                        <div class="contact-icon">📍</div>
                        <div>
                            <strong>Address</strong><br>
                            DHA Phase-5,07400, <br> Karachi,Pakistan
                        </div>
                    </div>

                    <div class="contact-info-item">
                        <div class="contact-icon">📞</div>
                        <div>
                            <strong>Phone</strong><br>
                            <a href="tel:+92324 5540898" style="color: #333; text-decoration: none;">+92324 5540898</a>
                        </div>
                    </div>

                    <!-- <div class="contact-info-item">
                        <div class="contact-icon">✉️</div>
                        <div>
                            <strong>Email</strong><br>
                            <a href="mailto:info@farahkhan-spa.com" style="color: #333; text-decoration: none;">info@farahkhan-spa.com</a>
                        </div>
                    </div> -->

                    <div class="contact-info-item">
                        <div class="contact-icon">🕐</div>
                        <div>
                            <strong>Hours</strong><br>
                            Mon - Fri: 10am - 8pm<br>
                            Sat - Sun: 11am - 6pm
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Farah Khan Spa. All rights reserved.</p>
            <p>Providing premium spa and wellness services</p>
            <!-- <div class="social-links">
                <a href="#" target="_blank">Facebook</a>
                <a href="#" target="_blank">Instagram</a>
                <a href="#" target="_blank">Twitter</a>
            </div> -->
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth' });
                }
            });
        });
    </script>
</body>
</html>
