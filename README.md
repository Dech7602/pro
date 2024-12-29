# pro
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .profile-pic {
            display: block;
            margin: 0 auto;
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
        }
        h1, h2 {
            text-align: center;
        }
        .skills, .hobbies, .portfolio {
            margin: 20px 0;
        }
        .social-links {
            text-align: center;
            margin-top: 20px;
        }
        .social-links a {
            margin: 0 10px;
            color: #4CAF50;
            text-decoration: none;
            font-size: 1.2em;
        }
        .social-links a:hover {
            color: #333;
        }
        @media (max-width: 600px) {
            .container {
                margin: 10px;
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>My Personal Profile</h1>
    </header>

    <div class="container">
        <img src="C:/Users/deeks/Downloads/profile-pic (1).jpg" alt="Profile Picture" class="Profile-pic">
        <h2>Dechamma C.S</h2>
        <p>Hello! I'm Dechamma, a passionate individual interested in web development. I love creating and learning new things!</p>

        <section class="contact">
            <h2>Contact Information</h2>
            <p>Email: dechamma799@gmail.com</p>
            <p>Phone: 7892425612</p>
        </section>

        <section class="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
            </ul>
        </section>

        <section class="hobbies">
            <h2>Hobbies & Interests</h2>
            <p>I enjoy playing BasketBall, reading books, and exploring new things in my free time.</p>
        </section>

        <section class="portfolio">
            <h2>Portfolio</h2>
            <p>Check out some of my projects:</p>
            <ul>
                <li><a href="#" target="_blank">Metagenomics Paper</a></li>
                <li><a href="#" target="_blank">Lung Cancer prediction using streamlit</a></li>
                <li><a href="#" target="_blank">web development</a></li>
            </ul>
        </section>

        <div class="social-links">
            <h2>Connect with Me</h2>
            <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
            <a href="https://github.com" target="_blank">GitHub</a>
            <a href="https://twitter.com" target="_blank">Twitter</a>
        </div>
    </div>
</body>
</html>
