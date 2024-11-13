"Abidjan Show " 

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abidjan Show</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1c1c1c;
            color: white;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            text-align: center;
            max-width: 800px;
            margin: 20px;
        }
        header {
            font-size: 2rem;
            margin-bottom: 20px;
        }
        .song {
            margin: 20px 0;
            background-color: #333;
            padding: 20px;
            border-radius: 8px;
        }
        .song-title {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }
        audio {
            width: 100%;
            margin-bottom: 10px;
        }
        .btn {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
        }
        .btn:hover {
            background-color: #45a049;
        }
        .news {
            margin-top: 40px;
            font-size: 1rem;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>Bienvenue sur Abidjan Show</header>

        <!-- Actualités Section -->
        <section class="news">
            <h2>Dernières Nouvelles</h2>
            <p>Je travaille sur de nouvelles chansons. Restez connecté pour les découvrir !</p>
        </section>

        <!-- Song Section -->
        <div class="song">
            <div class="song-title">Titre de la chanson</div>
            <audio controls>
                <source src="ton-chanson.mp3" type="audio/mp3">
                Votre navigateur ne supporte pas l'élément audio.
            </audio>
            <p>Écoutez ce morceau et découvrez son univers !</p>
            <a href="ton-chanson.mp3" class="btn" download>Télécharger</a>
        </div>

    </div>

</body>
</html>
