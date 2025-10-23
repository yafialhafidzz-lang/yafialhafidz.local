<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Toko Donat Lezat 🍩</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fff7ee;
      color: #333;
      text-align: center;
    }
    header {
      background: #ff9f43;
      color: white;
      padding: 40px 15px;
    }
    header h1 {
      margin: 0;
      font-size: 2em;
    }
    header p {
      margin: 5px 0 0;
      font-size: 1.1em;
    }
    main {
      padding: 30px 20px;
    }
    .donat-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 25px;
    }
    .donat {
      background: white;
      border-radius: 15px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      padding: 15px;
      transition: 0.3s;
    }
    .donat:hover {
      transform: scale(1.05);
    }
    .donat img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      background: #ff9f43;
      color: white;
      padding: 15px;
      font-size: 0.9em;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Toko Donat Lezat 🍩</h1>
    <p>Manis, lembut, dan bikin nagih setiap gigitan!</p>
  </header>

  <main>
    <h2>Varian Favorit Kami</h2>
    <div class="donat-list">
      <div class="donat">
        <img src="https://images.unsplash.com/photo-1606312619349-67dbe4b14e0d?w=500" alt="Donat Cokelat">
        <h3>Donat Cokelat</h3>
        <p>Lumer dan menggoda, cocok untuk pecinta cokelat sejati.</p>
      </div>
      <div class="donat">
        <img src="https://images.unsplash.com/photo-1627308595229-7830a5c91f9f?w=500" alt="Donat Stroberi">
        <h3>Donat Stroberi</h3>
        <p>Segar dan manis alami dari buah stroberi pilihan.</p>
      </div>
      <div class="donat">
        <img src="https://images.unsplash.com/photo-1512058564366-c9e3e0464b81?w=500" alt="Donat Keju">
        <h3>Donat Keju</h3>
        <p>Lelehan keju lembut berpadu dengan adonan empuk.</p>
      </div>
    </div>
  </main>

  <footer>
    © 2025 Toko Donat Lezat | Dibuat dengan ❤️ untuk pecinta donat
  </footer>
</body>
</html>
