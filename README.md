<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>KINGS - T-shirt Brand</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f4f4;
      color: #222;
    }

    header {
      background-color: #000;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
      letter-spacing: 2px;
    }

    header p {
      margin-top: 0.5rem;
      font-size: 1.1rem;
      color: #ccc;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 2rem;
      gap: 2rem;
    }

    .product {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      width: 300px;
      transition: transform 0.3s ease;
    }

    .product:hover {
      transform: scale(1.03);
    }

    .product img {
      width: 100%;
      height: auto;
      display: block;
    }

    .product-info {
      padding: 1rem;
      text-align: center;
    }

    .product-info h2 {
      margin: 0.5rem 0;
      font-size: 1.4rem;
    }

    .product-info p {
      margin: 0.3rem 0;
      color: #666;
    }

    footer {
      background-color: #000;
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>KINGS</h1>
    <p>The Crown of Streetwear</p>
  </header>

  <section class="products">
    <div class="product">
      <img src="2988B0C3-80A6-439E-86C3-2E44300C334A.jpeg" alt="White KINGS T-shirt with RGB logo and crown" />
      <div class="product-info">
        <h2>White KINGS T-shirt</h2>
        <p>RGB Neon Logo & Crown</p>
        <p>$29.99</p>
      </div>
    </div>

    <div class="product">
      <img src="05211CDE-890D-400A-9184-FDD02793AF4F.jpeg" alt="Black KINGS T-shirt with RGB logo and crown" />
      <div class="product-info">
        <h2>Black KINGS T-shirt</h2>
        <p>RGB Neon Logo & Crown</p>
        <p>$29.99</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 KINGS. All rights reserved.</p>
  </footer>
</body>
</html>
