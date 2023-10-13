# Jacinta-Projects
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
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
            text-align: center;
            padding: 1rem;
        }

        nav {
            background-color: #530518;
            padding: 0.5rem;
        }

        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }

        .main {
            padding: 1rem;
        }

        .card {
            background-color: #8c7a8d;
            padding: 1rem;
            margin: 1rem 0;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(23, 14, 63, 0.1);
        }

        footer {
            background-color: #100347;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <h1>Jacinta Esi Amoawah Badu</h1>
        <p>Computer Engineering student & Data Analyst </p>
    </header>

    <nav>
        <div class="container">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <div class="container main">
        <section id="about" class="card">
            <h2>About Me</h2>
            <p>Jacinta Esi Amoawah Badu is my name</p>
        </section>

        <section id="portfolio" class="card">
            <h2>Portfolio</h2>
            <div class="portfolio-item">
                <h3>Graphic designing</h3>
                <p>I was tasked to design posters and flyers when i was interning at Benmarine
                    Offshore company and few are the things that i did when i was interning there
                </p>
                <img src="c:\Users\Jacinta Badu\OneDrive - Ashesi University\Courses\Personal Projects\Picture1.jpg" alt="Engineering photos"> <br>
                <img src="c:\Users\Jacinta Badu\OneDrive - Ashesi University\Courses\Personal Projects\Picture2.jpg" alt="lol">
            </div>
            <div class="portfolio-item">
                <h3>Project 2</h3>
                <p>Description of the project goes here.</p>
            </div>
            <!-- Add more portfolio items as needed -->
        </section>

        <section id="contact" class="card">
            <h2>Contact Me</h2>
            <p>Email: jacintaesi@example.com</p>
            <p>Phone: +233 57 413 7981 </p>
        </section>
    </div>

    <footer>
        <p>&copy; 2023 JacintaBadu. All rights reserved.</p>
    </footer>
</body>

</html>
