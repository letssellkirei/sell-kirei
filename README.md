<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sell Kirei</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  
  <!-- AOS Animation CSS -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

  <!-- Favicon -->
  <link rel="icon" href="sell-kirei-logo.png" type="image/png">

  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background: repeating-linear-gradient(
        45deg,
        #e3f2fd,
        #e3f2fd 20px,
        #bbdefb 20px,
        #bbdefb 40px
      );
    }

    header {
      background: radial-gradient(circle at top left, #64b5f6, #e3f2fd);
      color: #003366;
      padding: 30px 20px;
      text-align: center;
      border-bottom-left-radius: 30px;
      border-bottom-right-radius: 30px;
      position: relative;
    }

    .logo-container {
      max-width: 180px;
      margin: 0 auto 15px;
      animation: float 3s ease-in-out infinite;
    }

    .logo-container img {
      width: 100%;
      height: auto;
      transition: transform 0.3s ease;
    }

    .logo-container img:hover {
      transform: rotate(2deg) scale(1.05);
    }

    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-8px); }
      100% { transform: translateY(0); }
    }

    header h1 {
      font-family: 'Pacifico', cursive;
      font-size: 48px;
      margin: 0;
    }

    header p {
      font-size: 18px;
      font-weight: 300;
    }

    h2 {
      text-align: center;
      margin-top: 40px;
      color: #003366;
      font-weight: 600;
    }

    .container {
      width: 90%;
      margin: auto;
    }

    .product {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 30px;
      gap: 20px;
    }

    .product-item {
      background-color: #ffffff;
      box-shadow: 0 10px 20px rgba(0,0,0,0.1);
      width: 280px;
      border-radius: 25px;
      text-align: center;
      padding: 15px;
      transition: all 0.3s ease;
    }

    .product-item:hover {
      transform: translateY(-7px) scale(1.03);
      box-shadow: 0 12px 25px rgba(0, 0, 0, 0.15);
    }

    .product-item img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 20px;
      margin-bottom: 10px;
    }

    .product-item h3 {
      font-size: 20px;
      color: #0d47a1;
      margin: 5px 0;
    }

    .product-item p {
      font-size: 14px;
      color: #555;
      margin: 5px 0;
    }

    .btn {
      background-color: #f06292;
      color: #fff;
      padding: 8px 16px;
      border: none;
      border-radius: 20px;
      cursor: pointer;
      text-decoration: none;
      font-size: 14px;
      margin-top: 10px;
      display: inline-block;
      transition: all 0.3s ease;
      font-weight: 600;
    }

    .btn:hover {
      background-color: #ec407a;
      transform: scale(1.05);
    }

    #titip-produk {
      margin: 50px auto;
      padding: 20px;
      background-color: #ffffff;
      border-radius: 20px;
      width: 80%;
      text-align: center;
    }

    .contact {
      font-size: 16px;
      color: #555;
      margin: 5px 0;
    }

    .socials {
      margin-top: 10px;
    }

    .socials a {
      color: #1976d2;
      text-decoration: none;
      margin: 0 8px;
      font-weight: bold;
    }

    .socials a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #e3f2fd;
      color: #555;
      border-top: 1px solid #ccc;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header data-aos="fade-down">
    <div class="logo-container">
      <img src="logo-sell-kirei.png" alt="Logo Sell Kirei">
    </div>
    <h1>Sell Kirei</h1>
    <p>Heyy yoo! Kamu Bisa Titip Produk Di Sini ✨ <br/> Let's connect!</p>
  </header>

  <div class="container">
    <section id="jual-produk">
      <h2 data-aos="zoom-in">Kategori Produk</h2>
      <div class="product">

        <!-- Fashion -->
        <div class="product-item" data-aos="fade-up" data-aos-delay="100">
          <img src="sepatu-fashion.png" alt="Fashion">
          <h3>Fashion</h3>
          <p>Punya produk fashion seperti sepatu, hoodie, kaos, atau totebag? Yuk titipkan di Sell Kirei!</p>
          <a href="https://wa.me/6282240237713?text=Halo%2C%20saya%20ingin%20titip%20produk%20fashion%20di%20Sell%20Kirei" class="btn" target="_blank">Hubungi via WhatsApp</a>
        </div>

        <!-- Elektronik -->
        <div class="product-item" data-aos="fade-up" data-aos-delay="200">
          <img src="elektronik-elektronik.png" alt="Elektronik">
          <h3>Elektronik</h3>
          <p>Punya produk elektronik seperti smartwatch, lampu LED, atau speaker mini? Bisa juga titip di sini!</p>
          <a href="https://wa.me/6282240237713?text=Halo%2C%20saya%20ingin%20titip%20produk%20elektronik%20di%20Sell%20Kirei" class="btn" target="_blank">Hubungi via WhatsApp</a>
        </div>

      </div>
    </section>

    <section id="titip-produk" data-aos="fade-up">
      <h2>Titip Produk Kamu di Sini</h2>
      <p>Ingin menitipkan produk kamu di Sell Kirei? Hubungi kami melalui:</p>
      <p class="contact">📞 WhatsApp: <strong>0822-4023-7713</strong></p>
      <p class="contact">📧 Email: <strong>sellkirei@gmail.com</strong></p>
      <div class="socials">
        <p>🔗 Sosial Media:</p>
        <a href="https://instagram.com/sellkirei" target="_blank">Instagram</a> |
        <a href="https://tiktok.com/@sellkirei" target="_blank">TikTok</a> |
        <a href="https://facebook.com/sellkirei" target="_blank">Facebook</a>
      </div>
    </section>
  </div>

  <footer>
    &copy; 2025 Sell Kirei. All rights reserved.
  </footer>

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init({ duration: 1000, once: true });
  </script>
</body>
</html>
