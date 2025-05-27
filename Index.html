<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Carta para Beatriz</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      background: linear-gradient(135deg, #ffe0f0, #ffb6d2);
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Arial', sans-serif;
      overflow: hidden;
    }

    .card-container {
      width: 400px;
      height: 300px;
      perspective: 1000px;
    }

    .card {
      width: 100%;
      height: 100%;
      position: relative;
      transform-style: preserve-3d;
      transition: transform 1s;
    }

    .card.open {
      transform: rotateY(180deg);
    }

    .face {
      position: absolute;
      width: 100%;
      height: 100%;
      border-radius: 20px;
      padding: 20px;
      box-sizing: border-box;
      backface-visibility: hidden;
      box-shadow: 0 4px 20px rgba(0,0,0,0.2);
    }

    .front {
      background: #ff8fb1;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .back {
      background: white;
      transform: rotateY(180deg);
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: #c2185b;
      font-size: 18px;
      line-height: 1.5;
      text-align: center;
    }

    .buttons {
      margin-top: 20px;
    }

    button {
      padding: 10px 20px;
      border: none;
      border-radius: 10px;
      margin: 0 10px;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }

    #aceitar {
      background-color: #d81b60;
      color: white;
      position: relative;
    }

    #recusar {
      background-color: #c51162;
      color: white;
      position: relative;
      overflow: hidden;
    }

    #recusar.break::before,
    #recusar.break::after {
      content: "";
      position: absolute;
      width: 50%;
      height: 100%;
      top: 0;
      background-color: #444;
      z-index: -1;
    }

    #recusar.break::before {
      left: 0;
      animation: break-left 0.5s forwards;
    }

    #recusar.break::after {
      right: 0;
      animation: break-right 0.5s forwards;
    }

    @keyframes break-left {
      to {
        transform: translateX(-100%);
        opacity: 0;
      }
    }

    @keyframes break-right {
      to {
        transform: translateX(100%);
        opacity: 0;
      }
    }
  </style>
</head>
<body>

<div class="card-container">
  <div class="card" id="card">
    <div class="face front">
      <h2>Você aceita abrir esta carta?</h2>
      <div class="buttons">
        <button id="aceitar">Aceitar</button>
        <button id="recusar">Recusar</button>
      </div>
    </div>
    <div class="face back">
      <p><strong>Beatriz,</strong><br>
      Desde que você entrou na minha vida, tudo ganhou cor e sentido.<br>
      Seu sorriso ilumina meus dias, e o simples som da sua voz me faz sorrir.<br>
      Gostaria de viver cada instante ao seu lado...<br><br>
      Você aceita namorar comigo? 💖</p>
    </div>
  </div>
</div>

<script>
  const aceitarBtn = document.getElementById('aceitar');
  const recusarBtn = document.getElementById('recusar');
  const card = document.getElementById('card');
  let clicks = 0;

  aceitarBtn.addEventListener('click', () => {
    if (clicks < 5) {
      moveButton();
      clicks++;
    } else {
      card.classList.add('open');
      aceitarBtn.style.display = 'none';
      recusarBtn.style.display = 'none';
    }
  });

  function moveButton() {
    const areaSize = 80; // movimentação mais próxima do centro
    const randomX = Math.random() * areaSize - areaSize / 2;
    const randomY = Math.random() * areaSize - areaSize / 2;
    aceitarBtn.style.transform = `translate(${randomX}px, ${randomY}px)`;
  }

  recusarBtn.addEventListener('click', () => {
    recusarBtn.classList.add('break');
    recusarBtn.disabled = true;
    recusarBtn.innerText = '💔';
  });
</script>

</body>
</html>
