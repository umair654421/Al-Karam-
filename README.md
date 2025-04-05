<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Al Karam Mart</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }
    body {
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #008080;
      padding: 1rem 2rem;
      color: white;
      text-align: center;
    }
    .container {
      padding: 2rem;
      max-width: 1200px;
      margin: auto;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .card {
      background: white;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .card:hover {
      transform: scale(1.03);
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }
    .card h3 {
      font-size: 1.1rem;
      margin: 0.5rem 0;
    }
    .card p {
      font-size: 0.9rem;
      color: #666;
    }
    .card .price {
      color: #008080;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>Al Karam Mart</h1>
    <p>One-Stop Shop for Sports, Grocery & More</p>
  </header>
  <div class="container">
    <div class="grid">
      <!-- Sample Product Cards -->
      <div class="card">
        <img src="https://source.unsplash.com/featured/?football" alt="Football">
        <h3>Football</h3>
        <p>High quality match ball</p>
        <p class="price">Rs. 1500</p>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/featured/?dumbbell" alt="Dumbbell">
        <h3>Dumbbell Set</h3>
        <p>5kg x 2 with rubber grip</p>
        <p class="price">Rs. 2500</p>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/featured/?apple" alt="Apple">
        <h3>Fresh Apples</h3>
        <p>Sweet and juicy red apples</p>
        <p class="price">Rs. 200/kg</p>
      </div>
      <!-- More products to be added... -->
    </div>
  </div>
</body>
</html>