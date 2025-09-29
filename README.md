# chocolate-com-pimentaa
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Meu Site com Vídeos e Link Amazon</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      text-align: center;
      margin-bottom: 40px;
    }
    main {
      max-width: 800px;
      margin: 0 auto;
    }
    .video-container {
      position: relative;
      padding-bottom: 56.25%; /* proporção 16:9 */
      height: 0;
      margin-bottom: 30px;
    }
    .video-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }
    .amazon-link {
      text-align: center;
      margin: 40px 0;
    }
    a.amazon-button {
      display: inline-block;
      padding: 12px 24px;
      background-color: #ff9900;
      color: #fff;
      text-decoration: none;
      border-radius: 4px;
      font-weight: bold;
    }
    a.amazon-button:hover {
      background-color: #e68a00;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bem-vindo ao meu site</h1>
    <p>Vídeos interessantes + link da Amazon</p>
  </header>

  <main>
    <!-- Link da Amazon -->
    <div class="amazon-link">
      <a class="amazon-button"
        href="https://www.amazon.com.br/b?ie=UTF8&node=7872687011&_encoding=UTF8&ref_=cct_cg_booktest_3d1&pf_rd_p=5a2cc5ca-9929-418c-8836-89f0f9d2a4e2&pf_rd_r=VSBZ1ZXJ2NFJ2Z0QKBRH"
        target="_blank" rel="noopener">
        Visitar por aqui (Amazon)
      </a>
    </div>

    <!-- Vídeos incorporados -->
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/yQFImndjBBw" frameborder="0" allowfullscreen></iframe>
    </div>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/04VkZNIy298" frameborder="0" allowfullscreen></iframe>
    </div>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/ZWvU8JuFxwA" frameborder="0" allowfullscreen></iframe>
    </div>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/-YmhWG1UtW4" frameborder="0" allowfullscreen></iframe>
    </div>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/0WKHu0bNXDY" frameborder="0" allowfullscreen></iframe>
    </div>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/ZU4Y2q9xK1I" frameborder="0" allowfullscreen></iframe>
    </div>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/HZ3315NPUI0?start=1226" frameborder="0" allowfullscreen></iframe>
    </div>
  </main>

  <footer style="text-align: center; margin-top: 60px;">
    &copy; 2025 — Meu Site de Vídeos
  </footer>
</body>
</html>
