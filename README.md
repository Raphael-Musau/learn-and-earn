# learn-and-earn
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smart Station - Learn & Earn</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#pricing">Pricing</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Home Section -->
    <header id="home">
        <h1>Welcome to Smart Station</h1>
        <p>Your one-stop solution for tutoring, study materials, and music lessons!</p>
    </header>

    <!-- Services Section -->
    <section id="services">
        <h2>Our Services</h2>
        <div>
            <h3>Tutoring Services</h3>
            <p>Get expert help with Math, Science, and more!</p>
        </div>
        <div>
            <h3>Study Materials</h3>
            <p>Download summarized notes, flashcards, and practice papers.</p>
        </div>
        <div>
            <h3>Music Lessons</h3>
            <p>Learn guitar, piano, and more at your pace.</p>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing">
        <h2>Pricing</h2>
        <ul>
            <li>Tutoring: KES 300 per session</li>
            <li>Study Materials: KES 100 per item</li>
            <li>Music Lessons: KES 500 per session</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Feel free to reach out via email or WhatsApp:</p>
        <p>Email: smartstation@example.com</p>
        <p>WhatsApp: +254 123 456 789</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Smart Station. All rights reserved.</p>
    </footer>

</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #2C3E50;
    color: white;
    text-align: center;
    padding: 50px 0;
}

h1 {
    margin: 0;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 10px;
    text-align: center;
    background-color: #34495E;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

section {
    padding: 30px;
    margin: 20px;
    background-color: white;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #34495E;
    color: white;
    text-align: center;
    padding: 15px 0;
}

footer p {
    margin: 0;
}
<!-- Contact Form -->
<section id="contact">
    <h2>Contact Us</h2>
    <form id="contact-form">
        <input type="text" id="name" placeholder="Your Name" required>
        <input type="email" id="email" placeholder="Your Email" required>
        <textarea id="message" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
    </form>
</section>

<script>
    document.getElementById('contact-form').addEventListener('submit', function(event) {
        event.preventDefault();
        alert('Thank you for reaching out!');
    });
</script>

