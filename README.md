<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Promoções incríveis de panelas e utensílios de cozinha. Descubra ofertas especiais e produtos de alta qualidade.">
    <title>Loja de Panelas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #4CAF50;
            padding: 20px;
            color: white;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .hero {
            background-color: #e3f2fd;
            padding: 50px;
            text-align: center;
        }
        .hero h1 {
            margin: 0;
            font-size: 3em;
        }
        .promo-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 20px;
        }
        .promo-item {
            background-color: white;
            margin: 10px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: calc(33% - 40px);
            box-sizing: border-box;
            text-align: center;
        }
        .promo-item img {
            max-width: 100%;
            height: auto;
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
        @media (max-width: 768px) {
            .promo-item {
                width: calc(50% - 40px);
            }
        }
        @media (max-width: 500px) {
            .promo-item {
                width: 100%;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Promoções de Panelas</h1>
    <p>As melhores panelas para sua cozinha, com descontos imperdíveis!</p>
</header>

<nav>
    <a href="#">Início</a>
    <a href="#">Promoções</a>
    <a href="#">Contato</a>
</nav>

<section class="hero">
    <h1>Descubra Nossas Ofertas!</h1>
    <p>Compre panelas de qualidade com os melhores preços.</p>
</section>

<section class="promo-section">
    <div class="promo-item">
        <img src="https://via.placeholder.com/300" alt="Panela de Ferro">
        <h3>Panela de Ferro</h3>
        <p>De <s>R$ 199,90</s> por <strong>R$ 149,90</strong></p>
    </div>
    <div class="promo-item">
        <img src="https://via.placeholder.com/300" alt="Conjunto de Panelas Antiaderente">
        <h3>Conjunto Antiaderente</h3>
        <p>De <s>R$ 299,90</s> por <strong>R$ 199,90</strong></p>
    </div>
    <div class="promo-item">
        <img src="https://via.placeholder.com/300" alt="Frigideira">
        <h3>Frigideira</h3>
        <p>De <s>R$ 79,90</s> por <strong>R$ 59,90</strong></p>
    </div>
</section>

<footer>
    <p>© 2024 Loja de Panelas. Todos os direitos reservados.</p>
</footer>

</body>
</html>
