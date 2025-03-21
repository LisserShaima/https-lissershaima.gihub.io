# https-lissershaima.gihub.io
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Koko</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenue sur mon site</h1>
        <nav>
            <ul>
                <li><a href="#">Accueil</a></li>
                <li><a href="#about">À propos</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>À propos</h2>
        <p>Ce site est un exemple simple pour apprendre à coder une page web. Tu peux personnaliser son contenu et son style !</p>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Envoyez-moi un message à <a href="mailto:koko@example.com">koko@example.com</a>.</p>
    </section>
    <footer>
        <p>&copy; 2025 Site de Koko. Tous droits réservés.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 1rem 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 2rem;
    margin: 2rem auto;
    max-width: 800px;
    background: white;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    text-align: center;
    padding: 1rem 0;
    background-color: #333;
    color: white;
    margin-top: 2rem;
}
