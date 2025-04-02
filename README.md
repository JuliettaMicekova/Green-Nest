# Green-Nest
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Green Nest - Sustainable Tiny Houses</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background: #4CAF50; color: white; text-align: center; padding: 1em; }
        nav { display: flex; justify-content: center; background: #333; padding: 0.5em; }
        nav a { color: white; text-decoration: none; padding: 0.5em 1em; }
        nav a:hover { background: #4CAF50; }
        .container { width: 80%; margin: auto; padding: 2em; }
        .section { background: white; padding: 1.5em; margin-bottom: 1.5em; border-radius: 10px; }
        .gallery img { width: 100%; max-width: 400px; margin: 10px; border-radius: 10px; }
        .gallery { display: flex; flex-wrap: wrap; justify-content: center; }
        footer { background: #333; color: white; text-align: center; padding: 1em; margin-top: 1.5em; }
        form { display: flex; flex-direction: column; width: 50%; margin: auto; background: white; padding: 1.5em; border-radius: 10px; }
        input, textarea { margin-bottom: 1em; padding: 0.5em; border: 1px solid #ccc; border-radius: 5px; }
        button { background: #4CAF50; color: white; padding: 0.7em; border: none; border-radius: 5px; cursor: pointer; }
        button:hover { background: #45a049; }
    </style>
</head>
<body>
    <header>
        <h1>Green Nest - Sustainable Tiny Houses</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#houses">Tiny Houses</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>
    
    <div class="container">
        <section id="about" class="section">
            <h2>About Green Nest</h2>
            <p>Green Nest is an innovative project focused on building sustainable, eco-friendly, and energy-efficient tiny houses.</p>
            <img src="images/about.jpg" alt="Sustainable tiny house">
        </section>

        <section id="houses" class="section">
            <h2>Our Tiny Houses</h2>
            <p>Our houses are built using sustainable materials like hempcrete, recycled wood, and eco-friendly insulation.</p>
            <img src="images/tiny-house.jpg" alt="Eco-friendly tiny house">
        </section>

        <section id="gallery" class="section">
            <h2>Gallery</h2>
            <div class="gallery">
                <img src="images/gallery1.jpg" alt="Tiny house interior">
                <img src="images/gallery2.jpg" alt="Tiny house exterior">
                <img src="images/gallery3.jpg" alt="Eco-friendly home design">
            </div>
        </section>

        <section id="contact" class="section">
            <h2>Contact Us</h2>
            <p>Email: info@greennest.com</p>
            <p>Phone: +420 123 456 789</p>
            <form action="mailto:info@greennest.com" method="post" enctype="text/plain">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Green Nest. All rights reserved.</p>
    </footer>
</body>
</html>
