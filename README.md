<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-7804275617401531"
     crossorigin="anonymous"></script>
    
   <style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
}

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
    flex-wrap: wrap;
}



nav ul {
    list-style: none;
    display: flex;
    gap: 2rem;
    flex-wrap: wrap;
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


.hero {
    background: linear-gradient(rgba(44, 62, 80, 0.7), rgba(52, 73, 94, 0.7));
    background-color: #3d5a6c;
    color: white;
    text-align: center;
    padding: 120px 2rem;
    min-height: 500px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.hero h1 {
    font-size: clamp(1.8rem, 5vw, 3.5rem);
    margin-bottom: 1rem;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
}

.hero p {
    font-size: clamp(1rem, 2.5vw, 1.3rem);
    margin-bottom: 2rem;
}

.cta-button {
    background: #e8d4b8;
    color: #2c3e50;
    padding: 1rem 2.5rem;
    font-size: 1.1rem;
    border-radius: 50px;
    font-weight: bold;
    display: inline-block;
    text-decoration: none;
    transition: all 0.3s;
}

.cta-button:hover {
    background: #d4c4a8;
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}


.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
}

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

/* ABOUT */
#about {
    background: white;
}

.about-content {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 3rem;
    align-items: center;
}

.about-content h3 {
    color: #2c3e50;
    margin-bottom: 1rem;
    font-size: 1.8rem;
}

.about-content p {
    color: #666;
    margin-bottom: 1rem;
    line-height: 1.8;
}

.about-content img {
    width: 100%;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

/* CONTACT */
#contact {
    background: #f9f7f4;
}

.contact-info-only {
    display: flex;
    justify-content: center;
}

.contact-info {
    background: white;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    max-width: 600px;
    width: 100%;
}

.contact-info h3 {
    color: #2c3e50;
    margin-bottom: 1.5rem;
}

.contact-info-item {
    margin-bottom: 1.5rem;
    display: flex;
    gap: 1rem;
    align-items: flex-start;
}

/* FOOTER */
footer {
    background: #2c3e50;
    color: white;
    text-align: center;
    padding: 2rem 0;
}

footer p {
    margin: 0.5rem 0;
}

/* MOBILE FIX */
@media (max-width: 768px) {
    nav {
        gap: 1rem;
    }

nav ul {
        justify-content: center;
        gap: 1rem;
    }

.hero {
        padding: 80px 1rem;
        min-height: 400px;
    }

section {
        padding: 2.5rem 0;
    }
 section h2 {
        font-size: 2rem;
    }

.about-content {
        grid-template-columns: 1fr;
        gap: 2rem;
    }
}

@media (max-width: 480px) {
    nav {
        flex-direction: column;
        padding: 0.75rem 1rem;
    }



.hero {
        padding: 60px 1rem;
        min-height: 300px;
    }

section h2 {
        font-size: 1.5rem;
    }

.container {
        padding: 0 1rem;
    }

.cta-button {
        padding: 0.7rem 1.5rem;
        font-size: 0.9rem;
    }
}
</style>
</head>
<body>

<header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

<section class="hero" id="home">
        <h1>Relax & Rejuvenate</h1>
        <p>Experience luxury spa treatments in a serene environment</p>
        <a href="#contact" class="cta-button">Book an Appointment</a>
    </section>

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
                    <img src="spa-about.jpeg" alt="Spa Interior">
                </div>
            </div>
        </div>
    </section>

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
                            DHA Phase-5, 07400,<br>Karachi, Pakistan
                        </div>
                    </div>

<div class="contact-info-item">
                        <div class="contact-icon">📞</div>
                        <div>
                            <strong>Phone</strong><br>
                            <a href="tel:+923245540898" style="color: #333; text-decoration: none;">+92324 5540898</a>
                        </div>
                    </div>

<div class="contact-info-item">
                        <div class="contact-icon">🕐</div>
                        <div>
                            <strong>Hours</strong><br>
                            Mon – Fri: 10am – 8pm<br>
                            Sat – Sun: 11am – 6pm
                        </div>
                    </div>
                </div>
            </div>
        </div>
</section>

<footer>
        <div class="container">
            <p>&copy; 2024 Farah Khan Spa. All rights reserved.</p>
            <p>Providing premium spa and wellness services</p>
        </div>
    </footer>

<script>
    async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-7804275617401531"
     crossorigin="anonymous">
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) target.scrollIntoView({ behavior: 'smooth' });
            });
        });
    </script>

</body>
</html>
