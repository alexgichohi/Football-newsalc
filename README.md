<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Alex Gichohi News | Football Updates</title>
    <meta name="description"
        content="Alex Gichohi News delivers fast, accurate football news, transfers, match reports, and player features.">

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
        }

        header {
            background-color: #FFD700;
            color: #000;
            text-align: center;
            padding: 20px;
        }

        nav {
            background-color: #111;
            padding: 10px;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        nav a {
            color: #FFD700;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }

        h2 {
            color: #FFD700;
            margin-bottom: 10px;
        }

        .article {
            background-color: #111;
            padding: 15px;
            margin-bottom: 25px;
            border-radius: 8px;
        }

        .article img {
            width: 100%;
            max-height: 400px;
            object-fit: cover;
            border-radius: 8px;
            margin: 10px 0;
        }

        .share-buttons {
            margin-top: 10px;
            font-size: 14px;
        }

        .share-buttons a {
            color: #FFD700;
            text-decoration: none;
            font-weight: bold;
        }

        .share-buttons a:hover {
            text-decoration: underline;
        }

        footer {
            background-color: #111;
            text-align: center;
            padding: 20px;
            color: #FFD700;
            margin-top: 40px;
        }

        #popup {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background-color: #111;
            color: #FFD700;
            padding: 20px;
            border-radius: 10px;
            display: none;
            z-index: 1000;
            text-align: center;
            width: 90%;
            max-width: 400px;
        }

        #popup button {
            margin-top: 12px;
            padding: 8px 16px;
            border: none;
            background-color: #FFD700;
            color: #000;
            font-weight: bold;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>

<body>

    <!-- Welcome Popup -->
    <div id="popup">
        <h3>Welcome to Alex Gichohi News ⚽</h3>
        <p>Your trusted source for football news, transfers, and match reports.</p>
        <p style="font-size:12px; opacity:0.8;">Site Ref: J26-8676-2024</p>
        <button onclick="closePopup()">Enter Site</button>
    </div>

    <!-- Header -->
    <header>
        <h1>Alex Gichohi News</h1>
        <p>Fast • Accurate • Exciting Football News</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#matches">Matches</a>
        <a href="#transfers">Transfers</a>
        <a href="#opinions">Opinions</a>
    </nav>

    <!-- Main Content -->
    <div class="container">

        <!-- MATCH REPORT -->
        <section id="matches">
            <h2>Match Report</h2>

            <div class="article">
                <h3>Scott McTominay Strikes TWICE! 👊 | Man Utd 2-1 Chelsea</h3>
                <img src="mctominay-man-utd-chelsea.jpg" alt="Scott McTominay Man United vs Chelsea">
                <p>
                    Scott McTominay delivered a stunning performance, scoring twice as Manchester United defeated
                    Chelsea 2-1 in a thrilling Premier League clash.
                </p>
                <div class="share-buttons">
                    <a href="#">Facebook</a> | <a href="#">Twitter</a> | <a href="#">WhatsApp</a>
                </div>
            </div>
        </section>

        <!-- TRANSFER NEWS -->
        <section id="transfers">
            <h2>Transfer News</h2>

            <div class="article">
                <h3>Mbappé – Real Madrid: Transfer Almost Complete</h3>
                <img src="mbappe-real-madrid.jpg" alt="Kylian Mbappe Real Madrid">
                <p>
                    Kylian Mbappé is reportedly closing in on a long-awaited move to Real Madrid in one of football’s
                    biggest transfers.
                </p>
                <div class="share-buttons">
                    <a href="#">Facebook</a> | <a href="#">Twitter</a> | <a href="#">WhatsApp</a>
                </div>
            </div>

            <div class="article">
                <h3>Moisés Caicedo 💙: Chelsea’s Midfield Powerhouse</h3>
                <img src="moises-caicedo.jpg" alt="Moises Caicedo Chelsea">
                <p>
                    Moisés Caicedo continues to impress at Chelsea, providing strength, control, and discipline in
                    midfield.
                </p>
                <div class="share-buttons">
                    <a href="#">Facebook</a> | <a href="#">Twitter</a> | <a href="#">WhatsApp</a>
                </div>
            </div>
        </section>

        <!-- OPINIONS & FEATURES -->
        <section id="opinions">
            <h2>Opinions & Features</h2>

            <div class="article">
                <h3>Mo Salah 👑: A Ballon d’Or Worthy King</h3>
                <img src="mo-salah.jpg" alt="Mohamed Salah">
                <p>
                    Mohamed Salah’s consistency, leadership, and goals continue to place him among football’s elite.
                </p>
            </div>

            <div class="article">
                <h3>Messi and Ronaldo Could Line Up Together in UEFA All-Star Match</h3>
                <img src="messi-ronaldo-allstar.jpg" alt="Messi and Ronaldo All Star Match">
                <p>
                    Football fans worldwide could witness history as Lionel Messi and Cristiano Ronaldo play together.
                </p>
            </div>

            <div class="article">
                <h3>Cristiano Ronaldo: The Legend Still Writing History</h3>
                <img src="cristiano-ronaldo.jpg" alt="Cristiano Ronaldo">
                <p>
                    Cristiano Ronaldo continues to break records and inspire millions across the globe.
                </p>
            </div>
        </section>

    </div>

    <!-- Footer -->
    <footer>
        <p>© 2026 Alex Gichohi News</p>
        <p style="font-size:13px; opacity:0.8;">Reference ID: J26-8676-2024</p>
    </footer>

    <!-- Script -->
    <script>
        window.onload = function () {
            document.getElementById("popup").style.display = "block";
        };

        function closePopup() {
            document.getElementById("popup").style.display = "none";
        }
    </script>

</body>
</html>
