<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="home">
        <h2>Home</h2>
        <p>This is the homepage of my simple website.</p>
    </section>
    <section id="about">
        <h2>About</h2>
        <p>This section is about me.</p>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>You can contact me via email: <a href="mailto:example@example.com">example@example.com</a></p>
    </section>
    <footer>
        <p>Copyright © 2023 My Website</p>
    </footer>
</body>
</html

  
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background: #f4f4f4;
}

header, section, footer {
    background: #fff;
    padding: 20px;
    margin: 10px;
}

nav ul {
    list-style: none;
    background: #333;
    text-align: center;
    padding: 0;
}

nav ul li {
    display: inline;
}

nav ul li a {
    text-decoration: none;
    color: white;
    padding: 15px 20px;
    display: inline-block;
}

footer {
    text-align: center;
    padding: 10px 0;
}
