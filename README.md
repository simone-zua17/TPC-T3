<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Layout</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav a {
            color: white;
            text-decoration: none;
        }
        main {
            display: flex;
            padding: 20px;
        }
        section {
            flex: 3;
            background-color: white;
            padding: 15px;
            margin-right: 10px;
        }
        aside {
            flex: 1;
            background-color: #ddd;
            padding: 15px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Meu Site</h1>
        <nav>
            <ul>
                <li><a href="#">Início</a></li>
                <li><a href="#">Sobre</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <article>
                <h2>Bem-vindo ao Meu Site</h2>
                <p>Este é um exemplo de layout bem estruturado com cabeçalho, navegação, seção, artigo, barra lateral e rodapé.</p>
            </article>
        </section>
        <aside>
            <h3>Últimas Notícias</h3>
            <p>Confira as atualizações e novidades mais recentes.</p>
        </aside>
    </main>
    <footer>
        <p>&copy; 2025 - Meu Site. Todos os direitos reservados.</p>
    </footer> 


</body>
</html>
