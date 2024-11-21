<!DOCTYPE html>
<html lang="en">

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>kuchbhi.ugc</title>
        <style>
            /* CSS Styles */
            body {
                font-family: Arial, sans-serif;
                margin: 0;
                padding: 0;
                background-color: #f4f4f9;
                color: #10375b;
                line-height: 1.6;
            }

            header {
                background-color: #0b2235;
                color: #a5d4e1;
                padding: 2rem;
                text-align: center;
            }

            header h1 {
                font-size: 3rem;
                margin-bottom: 0.5rem;
            }

            nav ul {
                list-style: none;
                padding: 0;
                display: flex;
                justify-content: center;
                gap: 2rem;
            }

            nav a {
                color: #a5d4e1;
                text-decoration: none;
                font-weight: bold;
                font-size: 1.2rem;
            }

            nav a:hover {
                color: #e1f5f9;
            }

            section {
                padding: 3rem 2rem;
                text-align: center;
            }

            section h2 {
                color: #0b2235;
                font-size: 2.5rem;
                margin-bottom: 1rem;
            }

            .bundle {
                border: 2px solid #10375b;
                padding: 1.5rem;
                margin: 1.5rem auto;
                max-width: 350px;
                background-color: #96bbd2;
                border-radius: 8px;
                transition: transform 0.3s;
            }

            .bundle:hover {
                transform: scale(1.05);
            }

            footer {
                background-color: #0b2235;
                color: #a5d4e1;
                text-align: center;
                padding: 2rem;
                margin-top: 3rem;
            }

            footer p a {
                color: #a5d4e1;
                text-decoration: none;
                font-weight: bold;
            }

            footer p a:hover {
                color: #e1f5f9;
            }

            .media {
                display: flex;
                flex-wrap: wrap;
                justify-content: center;
                gap: 2rem;
                margin-top: 2rem;
            }

            .media img,
            .media video {
                width: 280px;
                margin: 1rem;
                border-radius: 8px;
                border: 3px solid #10375b;
            }

            .profile-img {
                width: 150px;
                height: 150px;
                border-radius: 50%;
                margin-bottom: 2rem;
            }

            .about-text {
                max-width: 800px;
                margin: 0 auto;
            }
        </style>
    </head>

    <body>
        <header>
            <h1>kuchbhi.ugc</h1>
            <img src="profile pic.jpg" alt="Profile Picture" class="profile-img">
            <nav>
                <ul>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#benefits">Benefits</a></li>
                    <li><a href="#pricing">Pricing</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </header>

        <section id="about">
            <h2>About Us</h2>
            <div class="about-text">
                <p>At kuchbhi.ugc, we specialize in creating personalized, creative content. We believe in delivering
                    value to our clients with high-quality, engaging, and authentic UGC videos and images.</p>
                <p>Our mission is to craft content that resonates with your brand’s voice and audience while keeping
                    things creative and fresh.</p>
            </div>
        </section>

        <section id="benefits">
            <h2>Why Work With Us?</h2>
            <ul>
                <li>Affordable and value-driven services</li>
                <li>Unlimited revisions for satisfaction</li>
                <li>Tailored content based on your needs</li>
                <li>Professional, reliable service with quick turnaround</li>
            </ul>
        </section>

        <section id="pricing">
            <h2>Pricing</h2>
            <div class="bundle">
                <h3>Basic Bundle</h3>
                <p>1 video - ₹1000</p>
            </div>
            <div class="bundle">
                <h3>Standard Bundle</h3>
                <p>3 videos - ₹2500</p>
            </div>
            <div class="bundle">
                <h3>Premium Bundle</h3>
                <p>5 videos - ₹4000</p>
            </div>
            <p>*Prices are negotiable</p>
        </section>

        <section id="portfolio">
            <h2>Portfolio</h2>
            <div class="media">
                <h2>Images<h2>
                <img src="peterj/peterj.jpg"peter j perfumes">
                <img src="rosemary.jpg" alt="brillaire rosemary essential oil ">
                <img src="plum..jpg" alt="plum renewed clarity night gel">
                <img src="hilary rodha.jpg" alt="hilary rodha eyeshadow pallete">
                <img src="aualogica.jpg" alt="aqualogica illuminate+ gel moisturizer">
                <h2>Videos</h2>
                <video src="peterj.mp4" controls></video>
                <video src="brillsire.mp4" controls></video>
                <video src="]plumgel.mp4" controls></video>
                <video src="aqualogica moisturizer.mp4" controls></video>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>Email: kuchbhi.ugc@gmail.com</p>
            <p>Phone: +91-9778080355</p>
            <p>WhatsApp: +91-9861228564</p>
        </section>

        <footer>
            <p>Follow us:
                <a href="https://www.instagram.com/kuchbhi.ugc/?__pwa=1">Instagram</a> |
                <a href="">YouTube</a>http://www.youtube.com/@kuchbhi._ugc
            </p>
        </footer>

        <script>
            // JavaScript
            document.addEventListener('DOMContentLoaded', () => {
                console.log("Welcome to kuchbhi.ugc!");
            });
        </script>
    </body>

</html>
