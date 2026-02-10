<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Don Burguer – Promoções</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #f6f6f6;
      color: #222;
    }

    header {
      background: #ffffff;
      padding: 16px;
      font-weight: bold;
      font-size: 18px;
      border-bottom: 2px solid #e60023;
    }

    .tabs {
      display: flex;
      gap: 20px;
      padding: 12px 16px;
      background: #fff;
      font-size: 14px;
    }

    .tab-active {
      color: #e60023;
      border-bottom: 2px solid #e60023;
      padding-bottom: 6px;
      font-weight: bold;
    }

    .container {
      padding: 16px;
    }

    .burger-card {
      display: flex;
      gap: 12px;
      background: #fff;
      border-radius: 12px;
      padding: 12px;
      margin-bottom: 14px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }

    .burger-info {
      flex: 1;
    }

    .burger-info h3 {
      margin: 0 0 6px 0;
      font-size: 15px;
    }

    .burger-info p {
      margin: 0 0 8px 0;
      font-size: 13px;
      color: #666;
    }

    .price {
      font-size: 16px;
      font-weight: bold;
    }

    .old-price {
      text-decoration: line-through;
      color: #999;
      font-size: 13px;
      margin-left: 6px;
    }

    .discount {
      background: #22c55e;
      color: #fff;
      font-size: 12px;
      padding: 2px 6px;
      border-radius: 6px;
      margin-left: 6px;
    }

    .burger-image {
      width: 90px;
      height: 90px;
      border-radius: 10px;
      background: #eee;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 12px;
      color: #999;
    }

    .order-btn {
      margin-top: 8px;
      display: inline-block;
      padding: 8px 14px;
      background: #e60023;
      color: #fff;
      font-size: 13px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }

    .coupon {
      margin: 20px 16px;
      padding: 12px;
      background: #fff;
      border-radius: 12px;
      font-size: 14px;
      color: #7c3aed;
      display: flex;
      align-items: center;
      gap: 8px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }
  </style>
</head>

<body>

  <header>🍔 Don Burguer</header>

  <div class="tabs">
    <div class="tab-active">Top 5 Mais Vendidos na Promoção</div>
    <div>Lançamentos</div>
  </div>

  <div class="container">

    <div class="burger-card">
      <div class="burger-info">
        <h3>Burger Cheddar Bacon + Batata + Bebida Grátis</h3>
        <p>Combo com lanche, batata individual e refrigerante lata.</p>
        <div class="price">
          R$ 49,99
          <span class="old-price">R$ 69,99</span>
          <span class="discount">-29%</span>
        </div>
        <a href="#" class="order-btn">PEDIR AGORA</a>
      </div>
      <div class="burger-image">Imagem</div>
    </div>

    <div class="burger-card">
      <div class="burger-info">
        <h3>Burger Smash Big + Batata + Bebida Grátis</h3>
        <p>Pão brioche, triplo smash burger 90g cada.</p>
        <div class="price">
          R$ 59,99
          <span class="old-price">R$ 69,99</span>
          <span class="discount">-14%</span>
        </div>
        <a href="#" class="order-btn">PEDIR AGORA</a>
      </div>
      <div class="burger-image">Imagem</div>
    </div>

    <div class="burger-card">
      <div class="burger-info">
        <h3>Combo 2x Smash Salada + Batata + Bebidas</h3>
        <p>Dois smash burgers com queijo, batata e bebidas.</p>
        <div class="price">
          R$ 57,99
          <span class="old-price">R$ 69,99</span>
          <span class="discount">-17%</span>
        </div>
        <a href="#" class="order-btn">PEDIR AGORA</a>
      </div>
      <div class="burger-image">Imagem</div>
    </div>

    <div class="burger-card">
      <div class="burger-info">
        <h3>Burger Smash Duo Bacon + Batata + Bebida</h3>
        <p>Duplo smash burger 90g com bacon crocante.</p>
        <div class="price">
          R$ 47,99
          <span class="old-price">R$ 64,90</span>
          <span class="discount">-26%</span>
        </div>
        <a href="#" class="order-btn">PEDIR AGORA</a>
      </div>
      <div class="burger-image">Imagem</div>
    </div>

    <div class="burger-card">
      <div class="burger-info">
        <h3>Combo 2x Clássico Burger</h3>
        <p>Hambúrguer grelhado 160g no pão brioche.</p>
        <div class="price">
          R$ 49,99
          <span class="old-price">R$ 74,90</span>
          <span class="discount">-33%</span>
        </div>
        <a href="#" class="order-btn">PEDIR AGORA</a>
      </div>
      <div class="burger-image">Imagem</div>
    </div>

  </div>

  <div class="coupon">
    💜 Use cupom do Clube e ganhe até R$ 10 de desconto
  </div>

</body>
</html>
