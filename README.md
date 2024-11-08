Inserindo vídeos com HTML.

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vídeos com HTML5</title>
</head>
<body>
    <h1>Inserindo vídeos hospedagem localmente</h1>
    <p>Este vídeo está hospedado no meu próprio servidor.</p>
    <video width="200" poster="imagens/capa.png" controls autoplay loop>
         <source src="midia/meu-video.mp4" type="video/mp4">
         <source src="midia/meu.-video.mv4" type="video/mp4">
         <source src="midia/meu-video.ogv" type="video/ogg">
         <p>Seu navegador não tem compatibilidade com a reprodução do vídeo.</p>
    </video>

    <h1>Inserindo vídeos do YouTube</h1>
    <iframe width="400" height="300" src="https://www.youtube.com/embed/LW0bhKitRBk?si=g00ihxWtPvC5ZqX8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


</body>
</html>
