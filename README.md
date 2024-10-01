# mee

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Sonali Lenka - Personal Website">
    <title>Sonali Lenka</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #F2D6D1; /* Beige pink background */
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ffffff;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h1 {
            font-size: 2.5em;
            margin: 0;
            color: #333;
            position: relative;
        }
        h1::before,
        h1::after {
            content: '🌿'; /* Leaves emoji as a placeholder */
            position: absolute;
            font-size: 1.5em;
            top: 0;
        }
        h1::before {
            left: -30px; /* Position the left leaf */
        }
        h1::after {
            right: -30px; /* Position the right leaf */
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
            transition: color 0.3s;
            font-size: 1.2em; /* Slightly larger font size for navigation */
        }
        nav a:hover {
            color: #C36A9D; /* A pinkish hover color */
        }
        section {
            max-width: 900px;
            margin: 50px auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #C36A9D; /* Header color matching the hover color */
            font-size: 2em; /* Larger size for section headings */
        }
        .about, .portfolio, .contact, .blog {
            margin-bottom: 40px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #f5f5f5;
            color: #777;
            border-top: 1px solid #eaeaea;
        }
        .social-icons a {
            margin: 0 10px;
            text-decoration: none;
            color: #333;
            font-size: 1.5em;
            transition: color 0.3s;
        }
        .social-icons a:hover {
            color: #C36A9D; /* Matching hover color */
        }
        .divider {
            width: 100%;
            height: 1px;
            background-color: #eaeaea;
            margin: 20px 0;
        }
    </style>
</head>
<body>
 
<header>
    <h1>Sonali Lenka</h1>
    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
        <a href="#blog">Blog</a>
    </nav>
</header>
 
<section id="about" class="about">
    <h2>About Me</h2>
    <p>Hello! I'm Sonali Lenka, deeply passionate about both art and mathematics. From a very young age, I have been engaged in mathematics, which has shaped my logical thinking and problem-solving skills. Simultaneously, art has been a constant creative outlet, allowing me to explore ideas visually. Balancing my academic interests in mathematics with my artistic pursuits is a core part of who I am, and I strive to excel in both fields as I move forward in life.</p>
</section>
 
<div class="divider"></div>
 
<section id="portfolio" class="portfolio">
    <h2>Portfolio</h2>
    <p>Below are a few pieces from my portfolio, showcasing my passion for visual art. (Coming soon!)</p>
</section>
 
<div class="divider"></div>
 
<section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Feel free to reach out for collaborations, inquiries, or just to connect.</p>
    <p>Email: <a href="mailto:sonalilenka@example.com">sonalilenka@example.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/sonalilenka" target="_blank">linkedin.com/in/sonalilenka</a></p>
    <div class="social-icons">
        <a href="https://www.instagram.com/" target="_blank" class="fab fa-instagram"></a>
        <a href="https://www.linkedin.com/in/sonalilenka" target="_blank" class="fab fa-linkedin"></a>
        <a href="https://twitter.com/" target="_blank" class="fab fa-twitter"></a>
    </div>
</section>
 
<div class="divider"></div>
 
<section id="blog" class="blog">
    <h2>Blog</h2>
    <p>Welcome to my blog! Here I will share my thoughts on art, mathematics, and personal development. Stay tuned for updates!</p>
</section>
 
<footer>
    <p>&copy; 2024 Sonali Lenka. All rights reserved.</p>
</footer>
 
</body>
</html>
 
