<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>TechStore - Cadastro</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">

    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Conteúdo aqui -->
</body>
</html>

<div class="container">
    <h1>Cadastro TechStore</h1>
    <p class="subtitulo">Cadastre-se para ofertas</p>

    <form id="formCadastro">
        <div class="campo">
            <label for="nome">Nome Completo *</label>
            <input
                type="text"
                id="nome"
                name="nome"
                placeholder="Ex: Maria da Silva"
                required
            >
        </div>

        <div class="campo">
            <label for="email">E-mail *</label>
            <input
                type="email"
                id="email"
                name="email"
                placeholder="Ex: maria@email.com"
                required
            >
        </div>

        <div class="campo">
            <label for="telefone">Telefone</label>
            <input
                type="tel"
                id="telefone"
                name="telefone"
                placeholder="Ex: (11) 99999-9999"
            >
        </div>

        <button type="submit">Cadastrar</button>
    </form>
</div>

    </form>

    <div id="mensagem"></div>
</div>
