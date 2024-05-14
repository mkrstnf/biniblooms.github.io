<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biniblooms' Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet);
            padding: 20px;
            text-align: center;
            color: white;
        }
        header h1 {
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            padding: 14px 20px;
            display: block;
            color: white;
            text-align: center;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        section {
            padding: 20px;
            margin: 10px;
        }
        .about, .content, .experiences {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin-bottom: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Biniblooms</h1>
        <p>Welcome to my personal webpage!</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#content">Content</a>
        <a href="#experiences">Experiences</a>
    </nav>
    <section id="about" class="about">
        <h2>About</h2>
        <p>Hi, I'm Biniblooms! Welcome to my personal webpage. Here you'll find information about my interests, my work, and my experiences. I'm passionate about creating vibrant and colorful content that brings joy and inspiration to others.</p>
    </section>
    <section id="content" class="content">
        <h2>Content</h2>
        <p>Explore my portfolio of work. From creative writing to digital art, I love to express myself in various forms. Check back often for new updates and projects!</p>
    </section>
    <section id="experiences" class="experiences">
        <h2>Experiences</h2>
        <p>I've had the opportunity to work on a variety of exciting projects. Here, I'll share some of my most memorable experiences and what I've learned along the way. Stay tuned for stories and insights from my journey.</p>
    </section>
    <footer>
        <p>&copy; 2024 Biniblooms. All rights reserved.</p>
    </footer>
</body>
</html>
