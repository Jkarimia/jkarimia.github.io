<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Academic Website</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: #4CAF50;
            color: white;
        }

        h1 {
            font-size: 2em;
            margin: 5px 0;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 10px;
            margin: 0 10px;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #4CAF50;
        }

        main {
            margin-top: 20px;
            padding: 20px;
        }

        section {
            margin-bottom: 20px;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        img {
            display: block;
            margin: 20px auto;
            border-radius: 50%;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
        }

        form {
            max-width: 400px;
            margin: 20px auto;
            padding: 15px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        label {
            display: block;
            margin-bottom: 8px;
            color: #333;
        }

        input,
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }

        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <header>
        <img src="profile.jpg" alt="Your Profile Photo" width="150">
        <h1>Your Name, PhD</h1>
        <p>Assistant Professor, Department of [Your Department]</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#research">Research</a>
        <a href="#publications">Publications</a>
        <a href="#contact">Contact</a>
    </nav>

    <main>
        <!-- ... (existing sections) ... -->

        <section id="contact">
            <h2>Contact</h2>
            <form action="#" method="post">
                <label for="name">Your Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Your Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Your Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <input type="submit" value="Send Message">
            </form>
        </section>
    </main>

    <footer>
        &copy; 2023 Your Name - Academic Website
    </footer>

</body>
</html>
