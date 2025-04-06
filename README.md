html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ffh4xff | Aimbots</title>
  <style>
    body {
      background-color: #000;
      color: #0f0;
      font-family: "Courier New", monospace;
      padding: 20px;
    }
    h1, h2 {
      border-bottom: 1px solid #0f0;
      padding-bottom: 5px;
    }
    .highlight {
      border: 2px solid #f00;
      padding: 20px;
      margin-bottom: 30px;
      background-color: #111;
    }
    .aimbot {
      margin-bottom: 20px;
    }
    .button {
      background-color: transparent;
      border: 1px solid #0f0;
      color: #0f0;
      padding: 5px 10px;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
      margin-top: 10px;
    }
    .button:hover {
      background-color: #0f0;
      color: #000;
    }
    #ativarAimbot {
      display: none;
      margin-top: 15px;
    }
    #mensagem {
      margin-top: 20px;
      white-space: pre;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <h1>ffh4xff</h1>
  <p>Bem-vindo ao mundo dos aimbots. Escolha sua arma.</p>

  <div class="highlight">
    <h2>HEADTRICK</h2>
    <p>Precisão insana. Mira automática com foco exclusivo em headshots.  
       Ultra agressivo. Ideal para dominância total.</p>
    <button class="button" onclick="mostrarBotao()">Quero o Headtrick</button>
    <div id="ativarAimbot">
      <button class="button" onclick="ativarAimbot()">Ativar Aimbot</button>
      <div id="mensagem"></div>
    </div>
  </div>

  <div class="headtrick"
    <h2>Aimbot v1.0</h2>
    <p>Para jogos FPS clássicos. Disparo automático, mira suave.</p>
    <a href="#" class="button">Download</a>
  </div>

  <div class="aimbot">
    <h2>Aimbot v2.5 (Stealth)</h2>
    <p>Indetectável, com anti-ban. Ideal para uso competitivo.</p>
    <a href="#" class="button">Download</a>
  </div>

  <div class="aimbot">
    <h2>Aimbot Pro+</h2>
    <p>Suporte multi-jogo, configuração via painel externo.</p>
    <a href="#" class="button">Saiba mais</a>
  </div>

  <script>
    function mostrarBotao() {
      document.getElementById("ativarAimbot").style.display = "block";
    }

    function ativarAimbot() {
      const mensagem = ">> Aimbot Ativado com Sucesso.";
      const elemento = document.getElementById("mensagem");
      elemento.textContent = "";
      let i = 0;
      const efeito = setInterval(() => {
        elemento.textContent += mensagem.charAt(i);
        i++;
        if (i > mensagem.length) {
          clearInterval(efeito);
        }
      }, 50);
    }
</script>
</body>
</html>
