<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Explorador Pokémon</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Explorador Pokémon ⚡</h1>
    <p>Digite o nome ou ID de um Pokémon para buscar suas informações.</p>
    
    <div class="search-box">
      <input type="text" id="campo-busca" placeholder="Ex: pikachu, ditto, 25...">
      <button id="botao-buscar">Buscar</button>
    </div>

    <div id="resultado" class="card-resultado">
      <p class="placeholder">Aguardando busca...</p>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
