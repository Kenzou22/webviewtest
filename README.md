<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Webview Pop-up</title>
  <style>
    /* Style de base pour le corps */
    body, html {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: rgba(0, 0, 0, 0.7); /* Fond semi-transparent */
      font-family: Arial, sans-serif;
    }
    /* Pop-up container */
    .popup {
      width: 90vw; /* Adaptation au format mobile */
      max-width: 360px; /* Largeur max */
      height: 90vh; /* Format 9/16 */
      background-color: white;
      border-radius: 20px;
      box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
      padding: 20px;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    /* Titre centré */
    .popup h1 {
      font-size: 24px;
      margin: 0;
      padding: 10px 0;
    }

    /* Texte centré */
    .popup p {
      font-size: 16px;
      margin: 0;
      padding: 10px 0;
    }

    /* Conteneur pour la vidéo format stories */
    .video-container {
      width: 100%;
      flex-grow: 1; /* Laisse la vidéo prendre le plus d'espace possible */
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .video-container video {
      width: 100%;
      height: auto;
      border-radius: 15px;
    }

  </style>
</head>
<body>

  <div class="popup">
    <h1>Christophe te dit tout</h1>
    <p>Impossible de stresser pour le permis avec nos enseignants>
    <div class="video-container">
      <!-- Format vidéo intégré (format stories) -->
      <video controls autoplay muted>
        <source src="https://www.youtube.com/shorts/L97EJEZNGRw" type="video/mp4">
        Votre navigateur ne supporte pas la vidéo.
      </video>
    </div>
  </div>

</body>
</html>
