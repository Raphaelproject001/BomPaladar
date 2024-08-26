
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bom Paladar - Restaurante e Lanchonete</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            color: #000;
            background-color: #FFD700; /* Cor amarela */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #000; /* Cor preta */
            color: #FFD700; /* Cor amarela */
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: #FFD700; /* Cor amarela */
            padding: 14px 20px;
            text-decoration: none;
            display: block;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        .map {
            width: 100%;
            height: 400px;
            border: 0;
        }
        .portfolio img {
            max-width: 100%;
            height: auto;
            display: block;
            margin-bottom: 10px;
        }
        footer {
            background-color: #000; /* Cor preta */
            color: #FFD700; /* Cor amarela */
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bom Paladar</h1>
        <p>Restaurante e Lanchonete - Juazeiro do Norte, Ceará</p>
    </header>
    
    <nav>
        <a href="#portfolio">Portfólio</a>
        <a href="#historico">Histórico</a>
        <a href="#anuncio">Anúncio</a>
        <a href="#map">Localização</a>
    </nav>
    
    <div class="container">
        <div class="section" id="portfolio">
            <h2>Portfólio</h2>
            <div class="portfolio">
                <img src="exemplo1.jpg" alt="Imagem do prato 1">
                <img src="exemplo2.jpg" alt="Imagem do prato 2">
                <img src="exemplo3.jpg" alt="Imagem do prato 3">
                <!-- Adicione mais imagens conforme necessário -->
            </div>
        </div>

        <div class="section" id="historico">
            <h2>Histórico</h2>
            <p>O Bom Paladar é uma referência em Juazeiro do Norte, oferecendo uma experiência culinária única desde sua fundação em [ano]. Nossa missão é proporcionar momentos inesquecíveis com uma comida deliciosa e um atendimento de excelência.</p>
        </div>

        <div class="section" id="anuncio">
            <h2>Anúncio</h2>
            <p>Venha conferir nossas ofertas especiais! Descontos imperdíveis em pratos selecionados durante todo o mês. Não perca!</p>
        </div>

        <div class="section" id="map">
            <h2>Localização</h2>
            <iframe class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2257.724440327951!2d-39.31803974242413!3d-7.212840447508208!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7c63d3a5692fef%3A0x726b4e2e97a057c8!2sBom%20Paladar%20Restaurante!5e0!3m2!1spt-BR!2sbr!4v1693168880746!5m2!1spt-BR!2sbr" allowfullscreen="" loading="lazy"></iframe>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Bom Paladar. Todos os direitos reservados.</p>
    </footer>
    
    <!-- Google Translate -->
    <div id="google_translate_element"></div>
    <script type="text/javascript">
        function googleTranslateElementInit() {
            new google.translate.TranslateElement({pageLanguage: 'pt'}, 'google_translate_element');
        }
    </script>
    <script type="text/javascript" src="https://translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
</body>
</html>
