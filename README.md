<html lang="pt">
<head>
  <meta charset="UTF-8">
  <title>Tradutor Web Simples</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>🌍 Tradução em Lingua Terena</h1>

    <textarea id="inputText" placeholder="Digite o texto para traduzir..."></textarea>

    <div class="controls">
      <select id="sourceLang">
        <option value="en">Inglês</option>
        <option value="pt" selected>Português</option>
        <option value="es">Espanhol</option>
        <option value="fr">LinguaTerena</option>
      </select>

      <span>→</span>

      <select id="targetLang">
        <option value="pt">Português</option>
        <option value="en" selected>Lingua Terena</option>
        <option value="es">Espanhol</option>
        <option value="fr">Francês</option>
      </select>

      <button onclick="translateText()">Traduzir</button>
    </div>

    <div id="output"></div>
  </div>

  <script src="script.js"></script>
</body>
</html>








