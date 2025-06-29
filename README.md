<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kova House – Homemade Sweets</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body { font-family: sans-serif; margin: 0; padding: 0; background: #fff8f0; }
    header { background: #c67c4e; color: white; padding: 20px; text-align: center; }
    .sweet-grid { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; padding: 20px; }
    .sweet-item { background: white; border: 1px solid #ddd; border-radius: 8px; padding: 10px; width: 200px; text-align: center; box-shadow: 2px 2px 10px rgba(0,0,0,0.1);}
    .sweet-item img { width: 100%; height: 150px; object-fit: cover; border-radius: 5px; }
    .price { font-weight: bold; color: #444; margin: 5px 0; }
    .order-btn { background: #25D366; color: white; padding: 8px 12px; text-decoration: none; border-radius: 5px; display: inline-block; margin-top: 8px;}
    footer { text-align: center; padding: 20px; background: #f8e6d2; margin-top: 20px; }
  </style>
</head>
<body>

<header>
  <h1>Welcome to Kova House</h1>
  <p>Delicious homemade sweets. Order via WhatsApp!</p>
</header>

<section class="sweet-grid">
  <!-- Sweet 1 -->
  <div class="sweet-item">
    <img src="images/kaju-katli.jpg" alt="Kaju Katli">
    <h3>Kaju Katli</h3>
    <div class="price">₹500/kg</div>
    <a class="order-btn" href="https://wa.me/91XXXXXXXXXX?text=I want to order Kaju Katli from Kova House">Order on WhatsApp</a>
  </div>

  <!-- Sweet 2 -->
  <div class="sweet-item">
    <img src="images/gulab-jamun.jpg" alt="Gulab Jamun">
    <h3>Gulab Jamun</h3>
    <div class="price">₹350/kg</div>
    <a class="order-btn" href="https://wa.me/91XXXXXXXXXX?text=I want to order Gulab Jamun from Kova House">Order on WhatsApp</a>
  </div>

  <!-- Add more items as needed -->
</section>

<footer>
  <p>📞 Order now via WhatsApp or Pay via <a href="https://your-payment-link.com" target="_blank">UPI/Online Payment</a></p>
  <p>&copy; 2025 Kova House. All rights reserved.</p>
</footer>

</body>
</html>
