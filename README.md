<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            padding: 14px 20px;
            color: white;
            text-align: center;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to pel's  Website</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="home">
            <h2>Home</h2>
            <p>This is the home section of my simple website. Here, I will introduce you to my content.</p>
        </section>

        <section id="about">
            <h2>About</h2>
            <p>This section tells you a bit about the website or the person behind it. I'm passionate about web development and learning new technologies!</p>
            <img src="https://via.placeholder.com/400" alt="Placeholder Image" width="400" />
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>If you'd like to reach out, feel free to <a href="mailto:someone@example.com">email me</a>.</p>
        </section>
    </div>

    <footer>
        <p>Copyright © 2025 Your Website</p>
    </footer>
</body>
</html>
