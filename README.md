<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shopping Gems</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">Shopping Gems</div>
        <nav>
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#produits">Produits</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#a-propos">À Propos</a></li>
            </ul>
        </nav>
    </header>

    <section id="accueil" class="hero">
        <h1>Bienvenue sur Shopping Gems</h1>
        <p>Découvrez les meilleurs vêtements et accessoires en ligne.</p>
        <a href="#produits" class="btn">Voir nos produits</a>
    </section>

    <section id="produits" class="products">
        <h2>Nos Produits</h2>
        <div class="product-list">
            <div class="product">
                <img src="product1.jpg" alt="Produit 1">
                <h3>Blouson Varsity</h3>
                <p>Prix : 79,99 €</p>
                <button class="buy-btn">Acheter</button>
            </div>
            <div class="product">
                <img src="product2.jpg" alt="Produit 2">
                <h3>T-shirt Casual</h3>
                <p>Prix : 19,99 €</p>
                <button class="buy-btn">Acheter</button>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contactez-nous</h2>
        <form>
            <input type="text" placeholder="Nom" required>
            <input type="email" placeholder="Email" required>
            <textarea placeholder="Message" required></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>

    <section id="a-propos" class="about">
        <h2>À propos</h2>
        <p>Shopping Gems, c'est votre boutique en ligne dédiée à la mode moderne et accessible. Explorez nos collections dès aujourd'hui !</p>
    </section>

    <footer>
        <p>&copy; 2024 Shopping Gems. Tous droits réservés.</p>
    </footer>
</body>
</html>
