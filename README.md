<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Meu Site</title>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>

    <section id="home">
        <h2>Seção Home</h2>
        <p>Este é o conteúdo da seção Home.</p>
    </section>

    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Informações sobre a empresa ou pessoa.</p>
    </section>

    <section id="contato">
        <h2>Entre em Contato</h2>
        <form>
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>

            <input type="submit" value="Enviar">
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Meu Site. Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

nav {
    background-color: #eee;
    padding: 1em;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 1em;
}

section {
    margin: 2em;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em;
    position: absolute;
    bottom: 0;
    width: 100%;
}
