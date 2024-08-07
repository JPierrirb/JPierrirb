<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saúde e Emagrecimento</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 1em;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 2em;
        }
        .product {
            border: 1px solid #ddd;
            padding: 1em;
            margin: 1em 0;
            border-radius: 8px;
            background-color: white;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Saúde e Emagrecimento</h1>
    </header>
    <nav>
        <a href="#sobre">Sobre Mim</a>
        <a href="#produtos">Produtos</a>
        <a href="#contato">Contato</a>
    </nav>
    <div class="container">
        <section id="sobre">
            <h2>Sobre Mim</h2>
            <p>Bem-vindo ao meu site pessoal sobre saúde e emagrecimento! Aqui você encontrará dicas, informações e produtos que podem ajudar você a alcançar seus objetivos de perda de peso de forma saudável e eficaz.</p>
        </section>
        <section id="produtos">
            <h2>Produtos</h2>
            <div class="product">
                <h3>Secaps Black</h3>
                <p>O Secaps Black é um suplemento inovador que ajuda na perda de peso através da aceleração do metabolismo e redução do apetite. Feito com ingredientes naturais, ele é seguro e eficaz para quem busca emagrecer com saúde.</p>
            </div>
            <!-- Adicione mais produtos conforme necessário -->
        </section>
        <section id="contato">
            <h2>Contato</h2>
            <p>Para mais informações ou dúvidas sobre os produtos, entre em contato comigo através do formulário abaixo:</p>
            <form action="mailto:seuemail@exemplo.com" method="post" enctype="text/plain">
                <label for="name">Nome:</label><br>
                <input type="text" id="name" name="name"><br><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email"><br><br>
                <label for="message">Mensagem:</label><br>
                <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
                <input type="submit" value="Enviar">
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Saúde e Emagrecimento</p>
    </footer>
</body>
</html>
