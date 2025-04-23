<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>PIX IDD Emanuel</title>
</head>
<body style="font-family: sans-serif; text-align: center; padding-top: 50px;">
  <h2>Chave PIX da Igreja</h2>
  <p id="chave">pix@iddemanuel.com.br</p>
  <button onclick="copiarChave()">Copiar chave PIX</button>

  <script>
    function copiarChave() {
      const chave = document.getElementById("chave").innerText;
      navigator.clipboard.writeText(chave).then(() => {
        alert("Chave PIX copiada!");
      });
    }
  </script>
</body>
</html>
