# HTML
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>HTML teste</title>
    <style>
        body{
            font-family: Arial;
        }
        h1 {
            font-size: 50pt;
            color:#6495ED;
        }
        button {
            padding: 10px;
            font-size: 16px;
            cursor: pointer;
        }
    
    </style>
    <link rel="icon" href="icons/android-chrome-192x192.png" type="image/x-icon">

</head>
<body>
    <h1>Olá, meu site </h1>
    <h2>Bora toma uma</h2>
    <p>Aprendendo a programar</p>

    <img src="img/Gatinho.jpg" width="300" height="300"
    alt="Gatinho de fone">

    <h2>Alternativas</h2>
    <input type="checkbox" id="opcao1" name="opcao1">
    <label for="opcao1">Batata</label>

    <input type="checkbox" id="opcao2" name="opcao2">
    <label for="opcao2">Arroz</label>

    <input type="checkbox" id="opcao3" name="opcao3">
    <label for="opcao3">Feijão</label>

    <a href="https://www.youtube.com/">
        <button type="button">Youtube</button>
    </a>

    <button onclick="alert('Botão Clicado!')">Clique-me</button>

    <button onclick="mudarTexto()">Mudar Texto</button>
    <p id="paragrafo">Texto inicial</p>

    <script>
        function mudarTexto() {
            document.getElementById('paragrafo').innerHTML = 'Novo Texto!';
        }
    </script>
    
    <button onclick="window.open('https://www.youtube.com/')">Abrir Exemplo.com em Nova Janela</button>

    <button onclick="alternarVisibilidade()">Alternar Visibilidade</button>
    <div id="elemento" style="display: block;">Conteúdo visível</div>
    <script>
    function alternarVisibilidade() {
        var elemento = document.getElementById('elemento');
        elemento.style.display = (elemento.style.display === 'none') ? 'block' : 'none';
    }
</script>

</body>
</html>
