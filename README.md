<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Art Portfolio</title>
    <style>
        /* Basic CSS for layout - you can expand this in a separate CSS file */
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin: 0 1em;
        }
        nav a {
            color: white;
            text-decoration: none;
        }
        .container {
            max-width: 960px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        #about {
            padding-bottom: 20px;
            border-bottom: 1px solid #eee;
            margin-bottom: 20px;
        }
        .artwork-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .artwork-item {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
        }
        .artwork-item img {
            max-width: 100%;
            height: auto;
            display: block;
            margin-bottom: 10px;
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #333;
            color: white;
            position: sticky;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#artwork">Artwork</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Write a compelling introduction about yourself and your artistic journey here. Talk about your inspirations, techniques, and what drives your creativity. You can also mention any exhibitions or achievements.</p>
        </section>

        <section id="artwork">
            <h2>My Artwork</h2>
            <div class="artwork-grid">
                <div class="artwork-item">
                    <img src="path/to/your/image1.jpg" alt="Artwork Title 1">
                    <h3>Artwork Title 1</h3>
                    <p>Brief description or details about this artwork (e.g., medium, size, year).</p>
                </div>
                <div class="artwork-item">
                    <img src="path/to/your/image2.jpg" alt="Artwork Title 2">
                    <h3>Artwork Title 2</h3>
                    <p>Brief description or details about this artwork.</p>
                </div>
                </div>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>
            <p>If you're interested in purchasing my work or have any inquiries, please feel free to reach out!</p>
            <ul>
                <li>Email: your.email@example.com</li>
                <li>Instagram: <a href="https://www.instagram.com/your_instagram_handle" target="_blank">@your_instagram_handle</a> (Optional)</li>
                <li>Other links (e.g., Etsy, Facebook): [Link Text](Your Link) (Optional)</li>
            </ul>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
