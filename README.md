<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Subajit Majumder - Chess Player & Photographer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background: linear-gradient(90deg, #1e3c72, #2a5298);
            color: white;
            text-align: center;
            padding: 2rem;
        }
        nav {
            background-color: #222;
            text-align: center;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }
        nav a:hover {
            color: #ff9800;
        }
        section {
            padding: 2rem;
            max-width: 900px;
            margin: auto;
        }
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 10px;
        }
        .gallery-grid img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            transition: transform 0.3s;
        }
        .gallery-grid img:hover {
            transform: scale(1.05);
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #222;
            color: white;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Subajit Majumder</h1>
        <p>Chess Player | Travel Photographer | Adventurer</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#work">My Work</a>
        <a href="#gallery">Gallery</a>
        <a href="#links">Links</a>
    </nav>

    <section id="home">
        <h2>About Me</h2>
        <p>Hello! I am Subajit Majumder, a passionate chess player and travel photographer. I often travel 40–50 km a day by cycle, capturing nature and life through my lens. I completed my B.Sc. from <strong>Iswar Chandra Vidyasagar College</strong>. My hobby is traveling across the world.</p>
    </section>

    <section id="work">
        <h2>My Work</h2>
        <p>I work in service and dedicate my free time to playing chess and exploring photography.</p>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery-grid">
            <img src="https://source.unsplash.com/400x300/?nature" alt="Nature">
            <img src="https://source.unsplash.com/400x300/?chess" alt="Chess">
            <img src="https://source.unsplash.com/400x300/?cycling" alt="Cycling">
            <img src="https://source.unsplash.com/400x300/?travel" alt="Travel">
        </div>
    </section>

    <section id="links">
        <h2>Find Me Online</h2>
        <ul>
            <li><a href="https://maps.app.goo.gl/8tF6b6ZnbbVN2kLM9?g_st=ac" target="_blank">📍 Google Maps</a></li>
            <li><a href="https://www.chess.com/member/subajitm31" target="_blank">♟ Chess.com</a></li>
            <li><a href="#" target="_blank">📸 Instagram</a></li>
        </ul>
    </section>

    <footer>
        <p>© 2025 Subajit Majumder. All rights reserved.</p>
    </footer>

    <script>
        console.log("Website loaded successfully!");
    </script>

</body>
</html>
