<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sill-Silk Stampa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        nav {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: #fff;
        }
        nav ul li a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        @media (max-width: 768px) {
            nav ul {
                display: none;
            }
            nav.active ul {
                display: block;
            }
            nav.active ul li {
                display: block;
                text-align: center;
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>
    <nav>
        <div class="container">
            <span onclick="toggleMenu()" class="menu-icon">&#9776;</span>
            <ul id="menu">
                <li><a href="#home">Página Inicial</a></li>
                <li><a href="#produtos">Produtos/Serviços</a></li>
                <li><a href="#sobre">Sobre nós</a></li>
                <li><a href="#portfolio">Portfólio</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </div>
    </nav>

    <div class="container">
        <div id="home">
            <h1>Bem-vindo à Sill-Silk Stampa</h1>
            <p>Sua fonte de roupas e artes gráficas elegantes!</p>
        </div>

        <div id="produtos">
            <h2>Produtos/Serviços</h2>
        </div>

        <div id="sobre">
            <h2>Sobre nós</h2>
        </div>

        <div id="portfolio">
            <h2>Portfólio</h2>
        </div>

        <div id="contato">
            <h2>Contato</h2>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Sill-Silk Stampa. Todos os direitos reservados.</p>
    </footer>

    <script>
        function toggleMenu() {
            var menu = document.getElementById("menu");
            menu.classList.toggle("active");
        }
    </script>
</body>
</html>
