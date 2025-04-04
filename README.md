# tweakfn
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Tweak by Nxzy</title>
  <!-- Google Fonts per logo e titoli -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <!-- Font per il logo "Tweak FN" -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap" rel="stylesheet">
  <!-- Font per il resto del testo -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <style>
    /* Reset e stile base */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #121212;
      color: #f0f0f0;
      line-height: 1.6;
    }
    a {
      color: inherit;
      text-decoration: none;
    }
    /* Header */
    header {
      background: #1e1e1e;
      padding: 20px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 10;
    }
    .logo {
      font-family: 'Orbitron', sans-serif;
      font-size: 48px;
      color: #00ffea;
      text-transform: uppercase;
      letter-spacing: 2px;
      text-shadow: 
         0 0 10px #00ffea,
         0 0 20px #00ffea,
         0 0 40px #00ffea,
         0 0 80px #00ffea;
    }
    /* Hero Section */
    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 40vh;
      background: url('https://via.placeholder.com/1500x600?text=Gaming+Background') center/cover no-repeat;
      text-align: center;
      padding: 20px;
    }
    .hero h1 {
      font-size: 48px;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 20px;
      max-width: 600px;
    }
    /* Prodotti */
    .products {
      padding: 40px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }
    .products h2 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 36px;
    }
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .product-card {
      background: #1e1e1e;
      padding: 20px;
      border-radius: 8px;
      text-align: center;
      transition: transform 0.3s;
    }
    .product-card:hover {
      transform: scale(1.02);
    }
    .product-card h3 {
      margin-bottom: 10px;
      font-size: 24px;
    }
    .product-card p {
      margin-bottom: 20px;
      font-size: 18px;
    }
    .price {
      font-size: 28px;
      margin-bottom: 20px;
      color: #00ffea;
    }
    .buy-btn {
      display: inline-block;
      background: #00ffea;
      color: #121212;
      padding: 10px 20px;
      border-radius: 4px;
      font-weight: bold;
      transition: background 0.3s;
      cursor: default;
    }
    .buy-btn:hover {
      background: #00cccc;
    }
    .warning-text {
      margin-top: 10px;
      font-size: 14px;
      color: #ff3b3b;
      font-weight: bold;
    }
    /* Footer */
    footer {
      background: #1e1e1e;
      padding: 20px;
      text-align: center;
      font-size: 14px;
    }
    @media (max-width: 768px) {
      .hero h1 {
        font-size: 36px;
      }
      .hero p {
        font-size: 18px;
      }
    }
  </style>
</head>
<body>
  <!-- Header con logo -->
  <header>
    <div class="logo">Tweak FN</div>
  </header>
  
  <!-- Sezione Hero -->
  <section class="hero">
    <h1>Tweak by Nxzy</h1>
    <p>Migliora le prestazioni di Fortnite con i nostri tweak per PC e console. Ottimizzazione garantita per un'esperienza di gioco al top!</p>
  </section>
  
  <!-- Sezione Prodotti -->
  <section class="products">
    <h2>I nostri Tweak</h2>
    <div class="product-grid">
      <!-- Prodotto: Riduzione di input delay -->
      <div class="product-card">
        <h3>Riduzione Input Delay</h3>
        <p>Migliora la reattività del tuo dispositivo e riduci il ritardo degli input.</p>
        <div class="price">20€</div>
        <div class="buy-btn">PayPal: @NxzyRty</div>
        <p class="warning-text">⚠️ (Pagamento solo amici e familiari - In descrizione inserisci il tuo nome Discord, altrimenti annullato!) ⚠️</p>
      </div>
      <!-- Prodotto: Ottimizzazione Wi-Fi -->
      <div class="product-card">
        <h3>Ottimizzazione Wi-Fi</h3>
        <p>Configura al meglio la tua connessione per una stabilità e velocità superiori.</p>
        <div class="price">15€</div>
        <div class="buy-btn">PayPal: @NxzyRty</div>
        <p class="warning-text">⚠️ (Pagamento solo amici e familiari - In descrizione inserisci il tuo nome Discord, altrimenti annullato!) ⚠️</p>
      </div>
      <!-- Prodotto: Aumento di FPS -->
      <div class="product-card">
        <h3>Aumento di FPS</h3>
        <p>Ottimizza le prestazioni grafiche per raggiungere il massimo degli FPS.</p>
        <div class="price">25€</div>
        <div class="buy-btn">PayPal: @NxzyRty</div>
        <p class="warning-text">⚠️ (Pagamento solo amici e familiari - In descrizione inserisci il tuo nome Discord, altrimenti annullato!) ⚠️</p>
      </div>
      <!-- Prodotto: Riduzione latenza -->
      <div class="product-card">
        <h3>Riduzione Latenza</h3>
        <p>Riduci i tempi di risposta per un'esperienza di gioco fluida e reattiva.</p>
        <div class="price">15€</div>
        <div class="buy-btn">PayPal: @NxzyRty</div>
        <p class="warning-text">⚠️ (Pagamento solo amici e familiari - In descrizione inserisci il tuo nome Discord, altrimenti annullato!) ⚠️</p>
      </div>
    </div>
  </section>
  
  <!-- Footer -->
  <footer>
    &copy; 2025 Tweak by Nxzy - Tutti i diritti riservati.
  </footer>
</body>
</html>
