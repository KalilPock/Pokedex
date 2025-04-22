<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pokémon Finder</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    body { font-family: Arial, sans-serif; text-align: center; margin: 20px; }
    input { padding: 5px; font-size: 16px; }
    button { padding: 10px; font-size: 16px; cursor: pointer; }
    #pokemon-container { margin-top: 20px; }
    img { width: 150px; height: 150px; }
  </style>
</head>
<body>
  <h1>Encontre um Pokémon! 🔍</h1>
  <input type="text" id="pokemon-name" placeholder="Digite um Pokémon (ex: pikachu)">
  <button onclick="buscarPokemon()">Buscar</button>
  
  <div id="pokemon-container">
    <h2 id="nome"></h2>
    <img id="imagem" src="" alt="">
    <p id="info"></p>
  </div>

  <script>
    function buscarPokemon() {
      const nome = document.getElementById("pokemon-name").value.toLowerCase();
      fetch(`https://pokeapi.co/api/v2/pokemon/${nome}`)
        .then(response => {
          if (!response.ok) {
            throw new Error("Pokémon não encontrado!");
          }
          return response.json();
        })
        .then(data => {
          document.getElementById("nome").innerText = data.name.toUpperCase();
          document.getElementById("imagem").src = data.sprites.front_default;
          document.getElementById("info").innerText = `Tipo: ${data.types.map(t => t.type.name).join(", ")}`;
        })
        .catch(error => {
          document.getElementById("nome").innerText = "Erro!";
          document.getElementById("imagem").src = "";
          document.getElementById("info").innerText = "Pokémon não encontrado. Tente outro nome.";
        });
    }
  </script>
</body>
</html>
