<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Klass Phones</title>
  <style>
    body { font-family: Arial; margin: 0; padding: 0; background: #f5f5f5; }
    header { background: #333; color: white; text-align: center; padding: 1em; }
    .phones { display: flex; flex-wrap: wrap; justify-content: center; padding: 10px; }
    .card { background: white; margin: 10px; padding: 10px; border-radius: 5px; width: 300px; box-shadow: 0 0 5px #ccc; }
    .card img { width: 100%; border-radius: 5px; }
    .card h3 { margin: 10px 0 5px; }
    .card p { margin: 0; }
    .contact-btn { margin-top: 10px; display: inline-block; padding: 8px 12px; background: green; color: white; border-radius: 4px; text-decoration: none; }
  </style>
</head>
<body>
  <header>
    <h1>Klass Phones</h1>
    <p>Best Deals on Smartphones in Ghana</p>
  </header>

  <div class="phones">
    <div class="card">
      <img src="phone1.jpg" alt="iPhone 13" />
      <h3>iPhone 13</h3>
      <p>₵4,500 • 128GB • 5G</p>
      <a class="contact-btn" href="https://wa.me/233xxxxxxxxx">Order Now</a>
    </div>
    
    <div class="card">
      <img src="phone2.jpg" alt="Samsung A32" />
      <h3>Samsung A32</h3>
      <p>₵1,850 • 64GB • 4G</p>
      <a class="contact-btn" href="tel:+233xxxxxxxxx">Call to Order</a>
    </div>
    
    <!-- Add more phone cards here -->
  </div>
</body>
</html>
