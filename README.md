<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>Página de Senha do Wi-Fi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
        }
        h1 {
            color: #333;
            text-align: center;
        }
        a {
            display: inline-block;
            padding: 10px 20px;
            margin-top: 20px;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        a:hover {
            background-color: #0056b3;
        }
        img {
            max-width: 150px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
 <img src="imagem_2024-03-12_112324447.png" alt="Logo da sua empresa">
    <h1>Bem-vindo! Para obter a senha do Wi-Fi, siga nosso Instagram:</h1>
    
    <!-- Link ou botão clicável para redirecionar para o Instagram -->
    <a href="https://www.instagram.com/jklpapelaria_/" target="_blank">Siga nosso Instagram</a>
    

    <script>
        // Função para verificar se o usuário seguiu o Instagram (chamada ao retornar da página do Instagram)
        function verificarSeguindoInstagram() {
            // Exiba a senha do Wi-Fi ou execute a lógica necessária
            alert('Senha do Wi-Fi: jkl1234567');
        }
    </script>
</body>
</html>
<a href="https://www.instagram.com/jklpapelaria_/" target="_blank" onclick="verificarSeguindoInstagram()">Senha aqui!</a>
