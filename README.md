# www.inspiredesignglow.com
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inspire Design Glow</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #1e90ff; /* Bleu */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #gold; /* Doré */
        }
        .contact-form {
            background: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .contact-form button {
            background-color: #ffd700; /* Jaune */
            border: none;
            color: white;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<header>
    <h1>Inspire Design Glow</h1>
    <img src="URL_DU_LOGO" alt="Logo Inspire Design Glow" style="width: 200px;">
</header>

<div class="container">
    <h2>Nos Services</h2>
    <ul>
        <li>Création de logos</li>
        <li>Invitations</li>
        <li>Affiches</li>
        <li>Design des 7-shifts</li>
        <li>Et bien plus encore...</li>
    </ul>

    <h2>Contactez-nous</h2>
    <div class="contact-form">
        <form action="https://wa.me/243898940888" method="get" target="_blank">
            <label for="name">Votre Nom:</label>
            <input type="text" id="name" name="name" required>
            <label for="message">Votre Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Envoyer sur WhatsApp</button>
        </form>
    </div>
</div>

<footer>
    <p>&copy; 2023 Inspire Design Glow</p>
</footer>

</body>
</html>
