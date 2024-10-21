<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="NIARE-INOVA, spécialiste dans la vente d'équipements informatiques et la prestation de services pour les entreprises et les particuliers.">
    <meta name="keywords" content="informatique, équipement, service, vente, installation, réparation, formation">
    <meta name="author" content="NIARE-INOVA">
    <title>NIARE-INOVA</title>
    <link rel="stylesheet" href="/css/normalize.css">
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="scripts.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .site-header {
            background: #007BFF;
            color: #fff;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: relative;
            z-index: 1000;
        }

        .site-header h1 {
            margin: 0;
        }

        .site-nav ul {
            list-style: none;
            padding: 0;
            display: flex;
        }

        .site-nav li {
            margin: 0 15px;
        }

        .site-nav a {
            color: #fff;
            text-decoration: none;
            transition: color 0.3s;
        }

        .site-nav a:hover {
            color: #ffeb3b;
        }

        .section {
            padding: 20px;
            margin: 20px;
            background: white;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1s forwards;
        }

        h2 {
            color: #007BFF;
        }

        @keyframes spinImage {
            0% {
                transform: rotate(0deg);
            }

            100% {
                transform: rotate(360deg);
            }
        }

        .produit img,
        .service img {
            transition: transform 0.2s;
            animation: spinImage 5s infinite linear;
            display: inline-block;
            transform-origin: center;
            max-width: 100%;
            height: auto;
        }

        .produit img:hover,
        .service img:hover {
            transform: scale(1.1);
        }

        footer {
            text-align: center;
            padding: 10px;
            background: #007BFF;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        .slogan {
            font-size: 1.2em;
            color: #555;
            text-align: center;
            margin: 20px 0;
        }

        @keyframes fadeIn {
            0% {
                opacity: 0;
            }

            100% {
                opacity: 1;
            }
        }

        form {
            display: flex;
            flex-direction: column;
            max-width: 400px;
            margin: auto;
        }

        label {
            margin-top: 10px;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            margin-top: 5px;
            transition: border-color 0.3s;
        }

        input[type="text"]:focus,
        input[type="email"]:focus,
        textarea:focus {
            border-color: #007BFF;
            outline: none;
        }

        input[type="submit"] {
            margin-top: 10px;
            padding: 10px;
            background: #007BFF;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            transition: background 0.3s;
        }

        input[type="submit"]:hover {
            background: #0056b3;
        }

        .hamburger {
            font-size: 30px;
            cursor: pointer;
        }

        ul.show {
            display: block;
        }
    </style>
</head>

<body>
    <header class="site-header" id="top">
        <div class="logo">
            <img src="logos.jpg" alt="Logo NIARE-INOVA" width="200" height="100">
        </div>
        <nav class="site-nav" aria-label="Menu principal">
            <button class="menu-toggle" aria-label="Ouvrir le menu">
                <span class="hamburger">☰</span>
            </button>
            <ul>
                <li><a href="#prestations">Prestations</a></li>
                <li><a href="#produits">Produits</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main class="site-main">
        <!-- Section Prestations -->
        <section id="prestations" class="section">
            <h1>NIARE-INOVA</h1>
            <p class="slogan">Votre partenaire en solutions informatiques.</p>
            <p>Spécialiste dans la vente d'équipements informatiques et la prestation de services pour les entreprises et les particuliers.</p>
            <p><strong>REGISTRE DU COMMERCE :</strong> MA.KTI.2021.B.2110</p>
            <p><strong>Numéro Fiscal :</strong> 025038837V</p>
        </section>

        <!-- Section Produits -->
        <section id="produits" class="section">
            <h2>Nos Produits</h2>

            <article class="produit">
                <h3>Ordinateur Portable</h3>
                <figure>
                    <img src="OIP (1).jpg" alt="Ordinateur portable performant et polyvalent">
                    <figcaption>Un ordinateur portable performant et polyvalent.</figcaption>
                </figure>
            </article>

            <article class="produit">
                <h3>Ordinateur de Bureau</h3>
                <figure>
                    <img src="OIP (2).jpg" alt="Ordinateur de bureau puissant et personnalisable">
                    <figcaption>Un ordinateur de bureau puissant et personnalisable.</figcaption>
                </figure>
            </article>

            <article class="produit">
                <h3>Imprimante Photo</h3>
                <figure>
                    <img src="imprimante-photo.jpg" alt="Imprimante photo de haute qualité">
                    <figcaption>Imprimante photo de haute qualité pour vos souvenirs.</figcaption>
                </figure>
            </article>
        </section>

        <!-- Section Services -->
        <section id="services" class="section">
            <h2>Nos Services</h2>

            <article class="service">
                <h3>Installation et Configuration</h3>
                <figure>
                    <img src="installation_logiciel-scaled.jpeg" alt="Installation et Configuration">
                    <figcaption>Nous installons et configurons vos équipements informatiques pour une utilisation optimale.</figcaption>
                </figure>
                <ul>
                    <li>Installation de logiciels</li>
                    <li>Configuration de réseau</li>
                    <li>Installation de matériel</li>
                </ul>
            </article>

            <article class="service">
                <h3>Caméras de Surveillance</h3>
                <figure>
                    <img src="camera-surveillance.jpg" alt="Caméras de surveillance">
                    <figcaption>La caméra qui simplifie le partage.</figcaption>
                </figure>
            </article>

            <article class="service">
                <h3>Maintenance et Réparation</h3>
                <figure>
                    <img src="R.jpg" alt="Maintenance et Réparation">
                    <figcaption>Nous effectuons des diagnostics, des réparations et des mises à jour.</figcaption>
                </figure>
                <ul>
                    <li>Diagnostic de problèmes</li>
                    <li>Réparation de matériel</li>
                    <li>Mise à jour de logiciels</li>
                    <li>Développement web</li>
                </ul>
            </article>
        </section>

        <!-- Section Contact -->
        <section id="contact" class="section">
            <h2>Contactez-nous</h2>
            <form action="#" method="post" aria-labelledby="contact">
                <label for="name">Nom :</label>
                <input type="text" id="name" name="name" required placeholder="Votre nom">

                <label for="email">Email :</label>
                <input type="email" id="email" name="email" required placeholder="Votre email">

                <label for="message">Message :</label>
                <textarea id="message" name="message" rows="4" required placeholder="Votre message"></textarea>

                <input type="submit" value="Envoyer">
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 NIARE-INOVA. Tous droits réservés.</p>
        <p>Nous sommes spécialisés dans la vente de produits informatiques et la prestation de services pour entreprises et particuliers.</p>
    </footer>

    <script>
        $(document).ready(function() {
            $('.menu-toggle').on('click', function() {
                $('ul').toggleClass('show');
            });
        });
    </script>
</body>

</html>
