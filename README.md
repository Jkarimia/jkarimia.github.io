<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Your Name - Academic Website</title>
</head>
<body>
    <header>
        <img src="yourphoto.jpg" alt="Your Name">
        <h1>Your Name</h1>
        <p>Welcome to my academic website!</p>
    </header>

    <nav>
        <ul>
            <li><a href="about.html">About</a></li>
            <li><a href="publications.html">Publications</a></li>
            <li><a href="projects.html">Projects</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>

    <section>
        <h2>Welcome</h2>
        <p>This is the home page of my academic website. Explore the tabs above for more information.</p>
    </section>

    <footer>
        <p>Contact me at: your@email.com</p>
    </footer>
</body>
</html>
/* style.css */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

header {
    background-color: #1a1a1a;
    color: #fff;
    text-align: center;
    padding: 2em;
}

header img {
    border-radius: 50%;
    max-width: 150px;
}

h1 {
    margin-top: 0.5em;
}

nav {
    text-align: center;
    margin-top: 1em;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav li {
    display: inline;
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
}

section, footer {
    background-color: #fff;
    color: #333;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    padding: 1em;
    margin: 2em auto;
    max-width: 800px;
}

footer {
    background-color: #1a1a1a;
    color: #fff;
    text-align: center;
    padding: 1em;
    position: fixed;
    bottom: 0;
    width: 100%;
}
