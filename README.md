<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <title>Tunar Cəfərli</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #74ABE2, #5563DE);
      color: white;
      text-align: center;
      margin: 0;
      padding: 0;
      animation: fadeIn 1s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    header {
      padding: 50px 20px;
    }

    h1 {
      font-size: 46px;
      margin-bottom: 10px;
    }

    p {
      font-size: 18px;
      color: #f0f0f0;
    }

    .card {
      background-color: rgba(255, 255, 255, 0.15);
      margin: 30px auto;
      padding: 20px;
      border-radius: 12px;
      width: 80%;
      max-width: 600px;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: scale(1.05);
    }

    button {
      background-color: white;
      color: #5563DE;
      border: none;
      padding: 10px 20px;
      border-radius: 8px;
      cursor: pointer;
      transition: 0.3s;
      font-size: 16px;
    }

    button:hover {
      background-color: #5563DE;
      color: white;
    }

    footer {
      margin-top: 40px;
      padding: 15px;
      font-size: 14px;
      color: #ddd;
    }
  </style>
</head>
<body>
  <header>
    <h1>Salam, mən Tunar Cəfərliyəm 👋</h1>
    <p>Hazırda proqramlaşdırma və sayt yaratma öyrənirəm 🚀</p>
  </header>

  <div class="card">
    <h2>Haqqımda</h2>
    <p>Mən IT sahəsinə marağı olan bir gəncəm və öz şəxsi saytımı hazırlayıram.</p>
  </div>

  <div class="card">
    <h2>Əlaqə</h2>
    <p>Email: example@gmail.com</p>
    <button onclick="alert('Təşəkkürlər! Mənimlə əlaqə saxlaya bilərsiniz.')">Mesaj Göndər</button>
  </div>

  <footer>
    <p>© 2025 Tunar Cəfərli | GitHub Pages ilə hazırlanıb</p>
  </footer>
</body>
</html>
