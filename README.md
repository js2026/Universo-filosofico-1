# Universo-filosofico-1
<!DOCTYPE html><html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Universo Filosófico</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: radial-gradient(ellipse at center, #0d0d2b 0%, #000000 100%);
      color: white;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-image: url('https://upload.wikimedia.org/wikipedia/commons/6/6f/ESO_-_Stars_in_the_Sky_%28by%29.jpg');
      background-size: cover;
      background-position: center;
      text-align: center;
    }h1 {
  font-size: 2em;
  margin: 0 20px 20px;
  text-shadow: 0 0 10px #ffffff88;
}

.choices button {
  background-color: #111;
  color: #fff;
  border: 2px solid #fff;
  padding: 15px 30px;
  margin: 10px;
  font-size: 1em;
  border-radius: 10px;
  cursor: pointer;
  transition: 0.3s;
}

.choices button:hover {
  background-color: #fff;
  color: #000;
}

  </style>
</head>
<body>
  <h1>Você está onde pensa ou pensa onde está?</h1>
  <div class="choices">
    <button onclick="nextStage('explorar')">Explorar</button>
    <button onclick="nextStage('refletir')">Refletir</button>
  </div>  <script>
    function nextStage(choice) {
      if (choice === 'explorar') {
        document.body.style.backgroundImage = "url('https://cdn.pixabay.com/photo/2020/04/21/20/17/universe-5073060_1280.jpg')";
        document.querySelector('h1').innerText = 'Explorar é sair de si ou mergulhar mais fundo?';
      } else {
        document.body.style.backgroundImage = "url('https://cdn.pixabay.com/photo/2016/11/29/04/17/space-1867616_1280.jpg')";
        document.querySelector('h1').innerText = 'Refletir é iluminar ou esconder?';
      }
      document.querySelector('.choices').innerHTML = '<p>Fase 2 em construção...</p>';
    }
  </script></body>
</html>
