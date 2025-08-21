<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Halo 👋</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: linear-gradient(135deg, #1d2b64, #f8cdda);
      font-family: 'Poppins', sans-serif;
      color: white;
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      font-weight: bold;
    }

    .typed-cursor {
      font-weight: bold;
      font-size: 2.5rem;
      color: #ffd700;
    }
  </style>
</head>
<body>
  <h1><span id="typing"></span></h1>

  <!-- Typed.js CDN -->
  <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
  <script>
    var typed = new Typed("#typing", {
      strings: [
        "Halo, saya Juliano 👋",
        "Seorang Pelajar & Developer Pemula 🚀",
        "Selamat datang di Website saya 🌐"
      ],
      typeSpeed: 60,
      backSpeed: 40,
      backDelay: 1500,
      startDelay: 500,
      loop: true,
      showCursor: true,
      cursorChar: "|"
    });
  </script>
</body>
</html>
