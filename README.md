<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tobias Chyrek - Sportphysiotherapeut, Trainer & Athletiktrainer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }

        header {
            background: #003366; /* Dunkelblau (SHFV-Farbe) */
            color: white;
            padding: 1rem 0;
            text-align: center;
        }

        nav {
            background: #ffffff; /* Weiß */
            color: #333;
            padding: 0.5rem;
            text-align: center;
        }

        nav a {
            color: #003366;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }

        nav a:hover {
            color: #990000; /* Rot (SHFV-Farbe) */
        }

        .hero {
            background: #003366;
            color: white;
            text-align: center;
            padding: 2rem 0;
        }

        .hero h1 {
            font-size: 2.5rem;
        }

        section {
            padding: 2rem;
        }

        .card {
            background: #f4f4f4;
            margin: 1rem 0;
            padding: 1rem;
            border-radius: 5px;
        }

        footer {
            background: #003366;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tobias Chyrek</h1>
        <p>Sportphysiotherapeut | Trainer | Athletiktrainer</p>
    </header>
    <nav>
        <a href="#about">Über mich</a>
        <a href="#services">Leistungen</a>
        <a href="#contact">Kontakt</a>
    </nav>
    <div class="hero">
        <h1>Willkommen auf meiner Homepage!</h1>
        <p>Ich biete professionelle Unterstützung als Sportphysiotherapeut, Trainer und Athletiktrainer im Fußball.</p>
    </div>
    <section id="about">
        <h2>Über mich</h2>
        <div class="card">
            <p>Mein Name ist Tobias Chyrek. Mit jahrelanger Erfahrung im Bereich Sportphysiotherapie, Training und Athletiktraining unterstütze ich Fußballspieler und Teams dabei, ihre maximale Leistungsfähigkeit zu erreichen.</p>
        </div>
    </section>
    <section id="services">
        <h2>Leistungen</h2>
        <div class="card">
            <h3>Sportphysiotherapie</h3>
            <p>Individuelle Betreuung und Rehabilitation nach Verletzungen, um schnell und sicher zurück auf das Spielfeld zu kommen.</p>
        </div>
        <div class="card">
            <h3>Trainer</h3>
            <p>Erarbeitung von Trainingsplänen und individuelle Betreuung von Spielern und Teams.</p>
        </div>
        <div class="card">
            <h3>Athletiktraining</h3>
            <p>Steigerung der physischen Leistungsfähigkeit durch gezielte Athletikprogramme.</p>
        </div>
    </section>
    <section id="contact">
        <h2>Kontakt</h2>
        <form>
            <p>
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" required>
            </p>
            <p>
                <label for="email">E-Mail:</label><br>
                <input type="email" id="email" name="email" required>
            </p>
            <p>
                <label for="message">Nachricht:</label><br>
                <textarea id="message" name="message" rows="5" required></textarea>
            </p>
            <p>
                <button type="submit">Senden</button>
            </p>
        </form>
    </section>
    <footer>
        <p>&copy; 2025 Tobias Chyrek. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>
