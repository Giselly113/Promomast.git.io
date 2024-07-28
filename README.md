<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PROMOMASTT</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
            font-weight: 700; /* Fonte em negrito */
        }
        .search-bar {
            margin: 20px auto;
            text-align: center;
        }
        .search-bar input {
            padding: 10px;
            width: 80%;
            max-width: 600px;
        }
        .banner {
            width: 100%;
            max-height: 300px;
        }
        .banner img {
            width: 100%;
            height: auto;
            display: block;
        }
        .product-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between; /* Distribui os itens uniformemente */
            margin: 20px;
        }
        .product {
            border: 1px solid #ccc;
            border-radius: 5px;
            margin: 10px;
            padding: 10px;
            width: 22%; /* Ajuste para caber 4 produtos por linha */
            height: 290px; /* Altura fixa */
            display: flex;
            flex-direction: column;
            justify-content: space-between; /* Alinha o conteúdo verticalmente */
            text-align: center;
            box-sizing: border-box; /* Garante que padding e border sejam incluídos nas dimensões */
        }
        .product img {
            width: 100%;
            height: 190px; /* Altura fixa para as imagens */
            object-fit: cover; /* Mantém a proporção da imagem e cobre o espaço */
            border-radius: 1px; /* Arredonda as bordas das imagens */
            margin-bottom: 0px; /* Espaço abaixo da imagem */
        }
        .product h3 {
            font-weight: 700; /* Fonte em negrito */
            margin: 10px 0; /* Espaço ao redor do título */
            font-size: 1.1em; /* Ajuste o tamanho do texto conforme necessário */
        }
        .product .price-button {
            background-color: rgb(161, 11, 11);
            color: #fff;
            padding: 0px;
            border: none;
            cursor: pointer;
            text-decoration: none;
            display: block;
            text-align: center
        
        }
        .product .price-button:hover {
            background-color: darkblue;
        }
        .footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .footer a {
            color: #fff;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>PROMOMASTT</h1>
</header>

<div class="search-bar">
    <input type="text" id="search-input" placeholder="Pesquisar produtos...">
</div>

<div class="banner">
    <a href="link-do-banner" target="_blank">
        <img src="" alt="Banner Promocional">
    </a>
</div>

<div class="product-grid" id="product-grid">
    <!-- Produtos existentes -->
    <div class="product">
        <img src="https://m.media-amazon.com/images/I/714LrMhCGJL._AC_SY679_.jpg" alt="Produto 1">
        <h3>Hering, Camisa Básica Masculina Polo</h3>
        <a href="link-de-afiliado1" class="price-button" onclick="showAlert('Produto 1')">R$ 59,00</a>
    </div>
    <div class="product">
        <img src="https://m.media-amazon.com/images/I/71mBtg8WsvL.__AC_SY300_SX300_QL70_ML2_.jpg" alt="Produto 2">
        <h3>Kit Sabonete em Barra Pom Pom Loção Hidratante com 5 unidades </h3>
        <a href="https://amzn.to/3LGFq4V" class="price-button" onclick="showAlert('Produto 2')">R$ 12,00</a>
    </div>
    <div class="product">
        <img src="https://m.media-amazon.com/images/I/61gQETlUa4L.__AC_SX300_SY300_QL70_ML2_.jpg" alt="Produto 3">
        <h3>Intimus Gel Absorvente Noturno </h3>
        <a href=" https://amzn.to/3yfw0u6" class="price-button" onclick="showAlert('Produto 3')">R$ 200,00</a>
    </div>
    <!-- Adicionando mais 20 produtos -->
    <div class="product">
        <img src="https://m.media-amazon.com/images/I/51WD3KUSgyL.__AC_SX300_SY300_QL70_ML2_.jpg" alt="Produto 4">
        <h3>Produto 4</h3>
        <a href="link-de-afiliado4" class="price-button" onclick="showAlert('Produto 4')">R$ 250,00</a>
    </div>
    <div class="product">
        <img src="https://down-tx-br.img.susercontent.com/br-11134207-7r98o-ln7bjtxole8303.webp" alt="Produto 5">
        <h3>Kit 1600 lenço umidecido</h3>
        <a href="https://s.shopee.com.br/6KkM8qJFuE" class="price-button" onclick="showAlert('Produto 5')">R$ 79,90</a>
    </div>
    <div class="product">
        <img src="produto6.jpg" alt="Produto 6">
        <h3>Produto 6</h3>
        <a href="link-de-afiliado6" class="price-button" onclick="showAlert('Produto 6')">R$ 350,00</a>
    </div>
    <div class="product">
        <img src="produto7.jpg" alt="Produto 7">
        <h3>Produto 7</h3>
        <a href="link-de-afiliado7" class="price-button" onclick="showAlert('Produto 7')">R$ 400,00</a>
    </div>
    <div class="product">
        <img src="produto8.jpg" alt="Produto 8">
        <h3>Produto 8</h3>
        <a href="link-de-afiliado8" class="price-button" onclick="showAlert('Produto 8')">R$ 450,00</a>
    </div>
    <div class="product">
        <img src="produto9.jpg" alt="Produto 9">
        <h3>Produto 9</h3>
        <a href="link-de-afiliado9" class="price-button" onclick="showAlert('Produto 9')">R$ 500,00</a>
    </div>
    <div class="product">
        <img src="produto10.jpg" alt="Produto 10">
        <h3>Produto 10</h3>
        <a href="link-de-afiliado10" class="price-button" onclick="showAlert('Produto 10')">R$ 550,00</a>
    </div>
    <div class="product">
        <img src="produto11.jpg" alt="Produto 11">
        <h3>Produto 11</h3>
        <a href="link-de-afiliado11" class="price-button" onclick="showAlert('Produto 11')">R$ 600,00</a>
    </div>
    <div class="product">
        <img src="produto12.jpg" alt="Produto 12">
        <h3>Produto 12</h3>
        <a href="link-de-afiliado12" class="price-button" onclick="showAlert('Produto 12')">R$ 650,00</a>
    </div>
    <div class="product">
        <img src="produto13.jpg" alt="Produto 13">
        <h3>Produto 13</h3>
        <a href="link-de-afiliado13" class="price-button" onclick="showAlert('Produto 13')">R$ 700,00</a>
    </div>
    <div class="product">
        <img src="produto14.jpg" alt="Produto 14">
        <h3>Produto 14</h3>
        <a href="link-de-afiliado14" class="price-button" onclick="showAlert('Produto 14')">R$ 750,00</a>
    </div>
    <div class="product">
        <img src="produto15.jpg" alt="Produto 15">
        <h3>Produto 15</h3>
        <a href="link-de-afiliado15" class="price-button" onclick="showAlert('Produto 15')">R$ 800,00</a>
    </div>
    <div class="product">
        <img src="produto16.jpg" alt="Produto 16">
        <h3>Produto 16</h3>
        <a href="link-de-afiliado16" class="price-button" onclick="showAlert('Produto 16')">R$ 850,00</a>
    </div>
    <div class="product">
        <img src="produto17.jpg" alt="Produto 17">
        <h3>Produto 17</h3>
        <a href="link-de-afiliado17" class="price-button" onclick="showAlert('Produto 17')">R$ 900,00</a>
    </div>
    <div class="product">
        <img src="produto18.jpg" alt="Produto 18">
        <h3>Produto 18</h3>
        <a href="link-de-afiliado18" class="price-button" onclick="showAlert('Produto 18')">R$ 950,00</a>
    </div>
    <div class="product">
        <img src="produto19.jpg" alt="Produto 19">
        <h3>Produto 19</h3>
        <a href="link-de-afiliado19" class="price-button" onclick="showAlert('Produto 19')">R$ 1000,00</a>
    </div>
    <div class="product">
        <img src="produto20.jpg" alt="Produto 20">
        <h3>Produto 20</h3>
        <a href="link-de-afiliado20" class="price-button" onclick="showAlert('Produto 20')">R$ 1050,00</a>
    </div>
    <div class="product">
        <img src="produto21.jpg" alt="Produto 21">
        <h3>Produto 21</h3>
        <a href="link-de-afiliado21" class="price-button" onclick="showAlert('Produto 21')">R$ 1100,00</a>
    </div>
    <div class="product">
        <img src="produto22.jpg" alt="Produto 22">
        <h3>Produto 22</h3>
        <a href="link-de-afiliado22" class="price-button" onclick="showAlert('Produto 22')">R$ 1150,00</a>
    </div>
    <div class="product">
        <img src="produto23.jpg" alt="Produto 23">
        <h3>Produto 23</h3>
        <a href="link-de-afiliado23" class="price-button" onclick="showAlert('Produto 23')">R$ 1200,00</a>
    </div>
    <div class="product">
        <img src="produto24.jpg" alt="Produto 24">
        <h3>Produto 24</h3>
        <a href="link-de-afiliado24" class="price-button" onclick="showAlert('Produto 24')">R$ 1250,00</a>
    </div>
    <div class="product">
        <img src="produto25.jpg" alt="Produto 25">
        <h3>Produto 25</h3>
        <a href="link-de-afiliado25" class="price-button" onclick="showAlert('Produto 25')">R$ 1300,00</a>
    </div>
</div>

<div class="footer">
    <p><a href="#">Termos de Uso</a> | <a href="#">Política de Privacidade</a></p>
</div>

<script>
    // Mensagem de boas-vindas
    window.onload = function() {
        alert('Bem-vindo ao Promomastt!');
    };

    // Filtragem de produtos
    document.getElementById('search-input').addEventListener('input', function() {
        var query = this.value.toLowerCase();
        var products = document.querySelectorAll('.product');
        products.forEach(function(product) {
            var productName = product.querySelector('h3').textContent.toLowerCase();
            if (productName.includes(query)) {
                product.style.display = 'block';
            } else {
                product.style.display = 'none';
            }
        });
    });

    // Alerta de produto
    function showAlert(productName) {
        alert('Você clicou em: ' + productName);
    }
</script>

</body>
</html>
