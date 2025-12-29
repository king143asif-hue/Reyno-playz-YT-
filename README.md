# Reyno-playz-YT-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reyno Playz Official - Gaming, BGMI, Shorts, and Live Streams</title>
    <meta name="description" content="Welcome to Reyno Playz Official! Dive into epic gaming content including BGMI gameplay, shorts, and live streams. Subscribe for the latest videos.">
    <meta name="keywords" content="Reyno Playz, gaming, BGMI, YouTube, shorts, live streams, esports">
    <meta name="author" content="Reyno Playz">
    <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>🎮</text></svg>"> <!-- Simple gaming icon -->
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <div class="nav-container">
                <h1 class="logo">Reyno Playz Official</h1>
                <ul class="nav-menu">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#videos">Videos</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <section id="home" class="hero">
            <div class="hero-content">
                <h2>Welcome to Reyno Playz</h2>
                <p>Gaming • BGMI • Shorts • Live</p>
                <button class="cta-button" onclick="openYouTube()">Subscribe on YouTube</button>
            </div>
            <div class="video-embed">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID_HERE?autoplay=0" title="Latest Reyno Playz Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen onclick="openYouTube()"></iframe>
                <p>Click to watch on YouTube</p>
            </div>
        </section>

        <section id="videos">
            <h2>Videos</h2>
            <p>Explore our latest gaming videos. <a href="https://youtube.com/@reyno_playz_yt" target="_blank" rel="noopener">View full channel</a></p>
            <!-- Additional embeds can be added here if needed -->
        </section>

        <section id="about">
            <h2>About Reyno Playz</h2>
            <p>Reyno Playz is your ultimate destination for high-energy gaming content! We specialize in Battlegrounds Mobile India (BGMI) gameplay, thrilling shorts, and live streams that keep you on the edge of your seat. Whether you're a casual gamer or a pro, join us for epic battles, tips, and entertainment. Subscribe to stay updated!</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Reyno Playz. All rights reserved.</p>
        <a href="https://youtube.com/@reyno_playz_yt" target="_blank" rel="noopener">Follow us on YouTube</a>
    </footer>

    <script src="script.js"></script>
</body>
</html>
