<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kleiderverkauf</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #444;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .container {
            padding: 20px;
        }

        .product {
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 15px 0;
            padding: 15px;
            background-color: white;
        }

        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .product h2 {
            margin: 10px 0;
            font-size: 24px;
        }

        .product p {
            margin: 5px 0;
        }

        .edit-button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }

        .edit-button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mein Kleiderverkauf</h1>
        <p>Willkommen zu meinem Shop! Hier kannst du meine Produkte ansehen.</p>
    </header>

    <div class="container">
        <!-- Produkt 1 -->
        <div class="product">
            <img src="https://via.placeholder.com/400x300" alt="Produktbild">
            <h2>Rotes Kleid</h2>
            <p>Preis: 50 €</p>
            <p>Beschreibung: Elegantes rotes Kleid für besondere Anlässe.</p>
            <a href="#" class="edit-button">Bearbeiten</a>
        </div>

        <!-- Produkt 2 -->
        <div class="product">
            <img src="https://via.placeholder.com/400x300" alt="Produktbild">
            <h2>Schwarzes Kleid</h2>
            <p>Preis: 70 €</p>
            <p>Beschreibung: Klassisches schwarzes Kleid mit zeitlosem Stil.</p>
            <a href="#" class="edit-button">Bearbeiten</a>
        </div>
    </div>
</body>
</html>
