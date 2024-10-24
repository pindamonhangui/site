<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Planktonflix</title>
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
  <style>
    body {
      background-color: #4B0082; /* Roxo */
      color: white;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #4B0082; /* Roxo */
      text-align: center;
      padding: 20px;
    }

    header h1 {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 48px;
      color: white;
      margin: 0;
    }

    main {
      display: flex;
      justify-content: space-around;
      padding: 20px;
    }

    .movie {
      text-align: center;
      margin: 20px;
    }

    .movie img {
      width: 100%;
      max-width: 300px;
      border: 2px solid white;
    }

    .movie a {
      display: inline-block;
      margin-top: 10px;
      text-decoration: none;
      color: white;
      font-weight: bold;
      background-color: #8A2BE2; /* Roxo mais claro */
      padding: 10px 20px;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }

    .movie a:hover {
      background-color: #9370DB; /* Cor roxa mais clara ao passar o mouse */
    }

    footer {
      background-color: #4B0082;
      text-align: center;
      padding: 10px;
      color: white;
    }
  </style>
</head>
<body>

  <header>
    <h1>Planktonflix</h1>
  </header>

  <main>
    <div class="movie">
      <h2>Coringa</h2>
      <img src="https://m.media-amazon.com/images/I/71px4oDqT8L._AC_SY679_.jpg" alt="Coringa Poster">
      <br>
      <a href="https://www.youtube.com/watch?v=t433PEQGErc" target="_blank">Assistir Coringa</a>
    </div>

    <div class="movie">
      <h2>Corra!</h2>
      <img src="https://m.media-amazon.com/images/I/81E6cQ-wKmL._AC_SY679_.jpg" alt="Corra! Poster">
      <br>
      <a href="https://www.youtube.com/watch?v=DzfpyUB60YY" target="_blank">Assistir Corra!</a>
    </div>

    <div class="movie">
      <h2>Atividade Paranormal 2</h2>
      <img src="https://m.media-amazon.com/images/I/71DhxWYY19L._AC_SY679_.jpg" alt="Atividade Paranormal 2 Poster">
      <br>
      <a href="https://www.youtube.com/watch?v=07XbSk7Rjt4" target="_blank">Assistir Atividade Paranormal 2</a>
    </div>
  </main>

  <footer>
    <p>&copy; 2024 Planktonflix - Todos os direitos reservados.</p>
  </footer>

</body>
</html>
