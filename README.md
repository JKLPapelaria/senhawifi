<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de Senha do Wi-Fi</title>
</head>
<body>

<script>
    // Verifica se o parâmetro 'followed' está presente na URL
    const urlParams = new URLSearchParams(window.location.search);
    const followed = urlParams.get('followed');

    // Se o usuário seguiu o Instagram, exibe a senha do Wi-Fi
    if (followed === 'true') {
        document.write('<h1>Seja bem-vindo! Aqui está a senha do Wi-Fi: jkl1234567</h1>');
    } else {
        document.write('<h1>Por favor, siga nosso Instagram para obter a senha do Wi-Fi.</h1>');
    }
</script>

</body>
</html>
