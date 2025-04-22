# Raya<!Düfte>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>عطور راية Raya</title>
  <style>
    
    }body {
  font-family: 'Cairo', sans-serif;
  background-image: url('background.jpg');
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
  color: #fff;
  margin: 0;
  padding: 0;
}
    header {
      background-color: #8B4513;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 1.8em;
      letter-spacing: 1px;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
      padding: 30px;
    }
    .card {
      background-color: #fffaf0;
      border: 1px solid #eee;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.08);
      padding: 20px;
      text-align: center;
    }
    .card h2 {
      color: #4b2e1f;
    }
    .price {
      font-size: 1.2em;
      margin: 10px 0;
      color: #6b4c3b;
    }
    .buttons {
      display: flex;
      justify-content: space-around;
      margin-top: 15px;
    }
    .buttons a, .buttons button {
      padding: 8px 12px;
      border: none;
      border-radius: 8px;
      background-color: #8B4513;
      color: white;
      text-decoration: none;
      font-weight: bold;
      cursor: pointer;
    }
    .buttons a:hover, .buttons button:hover {
      background-color: #a05c2c;
    }
    @media (max-width: 600px) {
      .container {
        padding: 10px;
      }
    }
  </style>
</head>
<body>
  <header>عطور راية Raya</header>
  <div class="container">
    <div class="card">
      <h2>عطر راية 1 - صبايا</h2>
      <p class="price">10 يورو</p>
      <div class="buttons">
        <a href="https://www.paypal.me/yaserbak/10" target="_blank">PayPal</a>
        <button onclick="alert('تم اختيار Klarna. سيتم التواصل لإتمام الدفع.')">Klarna</button>
      </div>
    </div>
    <div class="card">
      <h2>عطر راية 2 - داكار رجالي</h2>
      <p class="price">10 يورو</p>
      <div class="buttons">
        <a href="https://www.paypal.me/yaserbak/10" target="_blank">PayPal</a>
        <button onclick="alert('تم اختيار Klarna. سيتم التواصل لإتمام الدفع.')">Klarna</button>
      </div>
    </div>
    <div class="card">
      <h2>عطر راية 3 - ياسمين</h2>
      <p class="price">10 يورو</p>
      <div class="buttons">
        <a href="https://www.paypal.me/yaserbak/10" target="_blank">PayPal</a>
        <button onclick="alert('تم اختيار Klarna. سيتم التواصل لإتمام الدفع.')">Klarna</button>
      </div>
    </div>
  </div>
</body>
</html>
