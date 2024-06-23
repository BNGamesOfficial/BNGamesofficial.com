<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BN GAMES</title>
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
    <style>
        body {
            background: #1a1a1a;
            color: #eaeaea;
            font-family: 'Press Start 2P', cursive;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        header {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px 40px;
            background: #111;
            border-bottom: 2px solid #00b0f0;
            position: relative;
        }

        header img {
            width: 200px;
            position: absolute;
            left: 40px;
        }

        h1 {
            font-size: 2.5em;
            color: #00b0f0;
            margin: 0;
        }

        .section {
            padding: 40px 20px;
            text-align: center;
            position: relative;
        }

        .section:nth-child(odd) {
            background: #222;
        }

        .section:nth-child(even) {
            background: #333;
        }

        h2 {
            font-size: 2em;
            margin-bottom: 20px;
            position: relative;
            display: inline-block;
        }

        h2:after {
            content: '';
            width: 50px;
            height: 4px;
            background: #00b0f0;
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
            bottom: -10px;
        }

        p {
            font-size: 1.1em;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
        }

        button {
            background: #00b0f0;
            color: #fff;
            border: none;
            padding: 10px 20px;
            font-size: 1em;
            cursor: pointer;
            transition: background 0.3s, transform 0.3s;
            border-radius: 5px;
            margin-top: 20px;
        }

        button:hover {
            background: #4cc3ff;
            transform: translateY(-3px);
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #111;
            color: #777;
            border-top: 2px solid #00b0f0;
        }

        .social-icons {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-top: 20px;
        }

        .social-icons img {
            width: 24px;
            height: 24px;
            transition: transform 0.3s;
        }

        .social-icons img:hover {
            transform: scale(1.1);
        }

        .social-icons .youtube {
            width: 32px; /* Slightly larger width for YouTube */
            height: 24px; /* Keep height consistent */
        }

        .parallax {
            background: url('https://source.unsplash.com/1600x900/?gaming') no-repeat center center/cover;
            height: 400px;
            position: relative;
            background-attachment: fixed;
        }

        .overlay {
            background: rgba(0, 0, 0, 0.5);
            height: 100%;
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .overlay h2 {
            color: #fff;
            font-size: 2.5em;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.6);
        }

        .section .content {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .games-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .games-grid img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            transition: transform 0.3s;
        }

        .games-grid img:hover {
            transform: scale(1.05);
        }

        .game-item {
            background: #222;
            padding: 20px;
            border-radius: 10px;
            text-align: left;
        }

        .game-item h3 {
            color: #00b0f0;
            margin: 0 0 10px;
        }

        .contact-email {
            font-size: 1.2em;
            color: #00b0f0;
            margin-top: 20px;
        }

        .contact-email a {
            color: #00b0f0;
            text-decoration: none;
            transition: color 0.3s;
        }

        .contact-email a:hover {
            color: #4cc3ff;
        }
    </style>
</head>

<body>
    <header>
        <img src="/mnt/data/New_file-removebg-preview.png" alt="BN GAMES Logo">
        <h1>BN GAMES</h1>
    </header>
    <div class="parallax">
        <div class="overlay">
            <h2>Welcome to BN GAMES!</h2>
        </div>
    </div>
    <div class="section">
        <h2>About Us</h2>
        <div class="content">
            <p>BN GAMES is your portal to an electrifying world of gaming. We are dedicated to bringing you the latest and greatest in video games, immersive experiences, and cutting-edge technology. Our passion for gaming drives us to deliver content that keeps you on the edge of your seat.</p>
        </div>
    </div>
    <div class="section">
        <h2>Featured Games</h2>
        <div class="games-grid">
            <div class="game-item">
                <h3>Game 1</h3>
                <p>Explore the abandoned workspace to find the whereabouts of your missing friend.</p>
                <img src="https://source.unsplash.com/800x600/?game" alt="Game 1">
            </div>
            <div class="game-item">
                <h3>Game 2</h3>
                <p>Battle fierce opponents in this fast-paced action game.</p>
                <img src="https://source.unsplash.com/800x600/?action-game" alt="Game 2">
            </div>
            <div class="game-item">
                <h3>Game 3</h3>
                <p>Solve intricate puzzles in this mind-bending puzzle game.</p>
                <img src="https://source.unsplash.com/800x600/?puzzle-game" alt="Game 3">
            </div>
        </div>
    </div>
    <div class="section">
        <h2>Latest News</h2>
        <div class="content">
            <p>Stay updated with the latest news in the gaming world. From game releases to exclusive interviews with top developers, we've got you covered.</p>
        </div>
    </div>
    <div class="section">
        <h2>Community</h2>
        <div class="content">
            <p>Join our vibrant community of gamers. Share your experiences, discuss your favorite games, and connect with like-minded enthusiasts.</p>
        </div>
    </div>
    <div class="section">
        <h2>Contact Us</h2>
        <div class="content">
            <p>Have questions or feedback? We would love to hear from you. Reach out to us through our contact page.</p>
            <p class="contact-email">Email: <a href="mailto:dev.bngames@gmail.com">dev.bngames@gmail.com</a></p>
        </div>
    </div>
    <div class="section">
        <h2>Follow Us</h2>
        <div class="social-icons">
            <a href="#"><img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook"></a>
            <a href="https://www.youtube.com/channel/UC7ajpXhTEkgE7wPIaoqovZg"><img class="youtube" src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube"></a>
            <a href="#"><img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram"></a>
        </div>
    </div>
    <footer>
        <p>© 2024 BN GAMES. All rights reserved.</p>
    </footer>
</body>

</html>
