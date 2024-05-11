<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    
    
    
    <body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

.page {
    display: none;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 20px;
    position: fixed;
    bottom: 0;
    width: 100%;
}header>
        <h1>My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home" class="page">
            <h2>Welcome to My Website</h2>
            <p>This is the landing page of my website.</p>
        </section>

        <section id="about" class="page">
            <h2>About Us</h2>
            <p>This is the about page of our website.</p>
        </section>

        <section id="services" class="page">
            <h2>Our Services</h2>
            <p>Check out the services we offer.</p>
        </section>

        <section id="contact" class="page">
            <h2>Contact Us</h2>
            <p>Get in touch with us for any inquiries.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
