<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tunar Cəfərli</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #5D9FFF, #B8DCFF);
      color: #fff;
      text-align: center;
      margin: 0;
      padding: 0;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      animation: fadeIn 1.5s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }

    p {
      font-size: 18px;
      color: #f5f5f5;
      margin-bottom: 30px;
    }

    .card {
      background: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(5px);
      padding: 20px;
      border-radius: 15px;
      width: 80%;
      max-width: 500px;
      margin: 0 auto 30px auto;
      box-shadow: 0 4px 20px rgba(0,0,0,0.2);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: scale(1.05);
    }

    button {
      background-color: white;
      color: #5D9FFF;
      border: none;
      padding: 10px 20px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
      transition: all 0.3s ease;
    }

    button:hover {
      background-color: #5D9FFF;
      color: white;
    }

    footer {
      margin-top: 40px;
      font-size: 14px;
      color: #eee;
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Salam, mən Tunar Cəfərliyəm 👋</h1>
    <p>Bu mənim ilk şəxsi saytımdır! Hazırda kodlaşdırma öyrənirəm 💻</p>
    <button onclick="alert('Tunarla əlaqə üçün: example@gmail.com')">Əlaqə</button>
  </div>

  <footer>
    <p>© 2025 Tunar Cəfərli | GitHub Pages ilə yaradılıb</p>
  </footer>
</body>
</html>
