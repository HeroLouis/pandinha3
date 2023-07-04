# pandinha3
Site de lojinha de acessórios em Porto Velho RO
+<!DOCTYPE html>
<html>
<head>
  <title>Pandinha Acessorios</title>

  <style>
    /* Importando a fonte Pacifico do Google Fonts */
    @import url('https://fonts.googleapis.com/css?family=Pacifico&display=swap');

    body {
      font-family: Arial, sans-serif;
      /* Usando um efeito de gradiente no fundo da página */
      background-image: linear-gradient(to right, pink, lightblue);
    }
    h1 {
      text-align: center;
      color: white;
      /* Aplicando a fonte Pacifico ao título */
      font-family: 'Pacifico', cursive;
    }
    .container {
      max-width: 800px;
      margin: 0 auto;
    }
    .product {
      display: flex;
      align-items: center;
      margin: 10px 0;
      /* Adicionando uma borda branca aos produtos */
      border: 2px solid white;
    }
    .product img {
      width: 200px;
      height: 200px;
      /* Adicionando uma borda arredondada e uma sombra às imagens */
      border-radius: 10px;
      box-shadow: 5px 5px 10px rgba(0,0,0,0.2);
    }
    /* Adicionando um efeito de hover às imagens */
    .product img:hover {
      /* Aumentando o tamanho da imagem em 10% */
      transform: scale(1.1);
    }
    .product-info {
      margin-left: 20px;
    }
    .product-name {
      font-size: 24px;
      font-weight: bold;
    }
    .product-price {
      font-size: 18px;
      color: green;
    }
    .product-description {
      font-size: 16px;
    }
    .buy-button {
      display: inline-block;
      padding: 10px 20px;
      background-color: green;
      color: white;
      text-decoration: none;
      /* Adicionando um efeito de transição ao botão */
      transition: background-color 0.3s ease-in-out;
    }
    /* Definindo uma cor diferente para o botão quando o usuário passar o mouse */
    .buy-button:hover {
      background-color: limegreen;
    }

    /* Adicionando algumas propriedades CSS para a imagem de panda */
    .panda {
      width: 250px;
      vertical-align: middle;
      margin-right: 10px;
      /* Adicionando uma borda circular em volta da imagem */
      border: 5px solid white;
      border-radius: 50%;
    }
  </style>
</head>
<body>
  <h1>
    Pandinha Acessorios
    <img src="https://i.imgur.com/MHkea85.png" alt="Panda" class="panda">
  </h1>

  <div class="container">
    <div class="product">
      <img src="https://www.dicasdemulher.com.br/wp-content/uploads/2021/05/pulseiras-de-micangas-01.jpg" alt="Missangas coloridas">
      <div class="product-info">
        <div class="product-name">Pulseiras de missanga</div>
        <div class="product-price">R$ 4,99</div>
        <div class="product-description">Pulseiras feitas de sua preferência.</div>
        <a href="https://wa.me/5569993660740?text=Esse%20produto%20Pulseiras%20de%20missanga%20est%C3%A1%20dispon%C3%ADvel%20ainda?" class="buy-button">Comprar</a>
      </div>
    </div>
    <div class="product">
      <img src="https://th.bing.com/th/id/OIP.jSJ5cu-wuFSkfznWvewCOAHaHa?pid=ImgDet&rs=1" alt="Missangas de madeira">
      <div class="product-info">
        <div class="product-name">Colar</div>
        <div class="product-price">R$ 15,00</div>
        <div class="product-description">Variedades de colares.</div>
        <a href="https://wa.me/5569993660740?text=Esse%20Colar%20est%C3%A1%20dispon%C3%ADvel%20ainda?" class="buy-button">Comprar</a>
      </div>
    </div>
    <div class="product">
      <img src="https://i.etsystatic.com/8657693/r/il/f3fdd3/3016196757/il_1588xN.3016196757_9azj.jpg" alt="Brincos personalizados">
      <div class="product-info">
        <div class="product-name">Brincos personalizados</div>
        <div class="product-price">R$ 3,99</div>
        <div class="product-description">Brincos de diversas variedades personalizadas.</div>
        <a href="https://wa.me/5569993660740?text=Brincos%20personalizados%20est%C3%A1%20dispon%C3%ADvel%20ainda?" class="buy-button">Comprar</a>
      </div>
    </div>
    <div class="product">
      <img src="https://i.etsystatic.com/5694277/r/il/1afc39/267571574/il_794xN.267571574.jpg" alt="Missangas de vidro">
      <div class="product-info">
        <div class="product-name">Pulseiras</div>
        <div class="product-price">R$ 4,99</div>
        <div class="product-description">Pulseira de linha.</div>
        <a href="https://wa.me/5569993660740?text=Essa%20Pulseira%20est%C3%A1%20dispon%C3%ADvel%20ainda?" class="buy-button">Comprar</a>
      </div>
    </div>
  </div>
</body>
</html>
