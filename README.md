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
      color: white;
      text-align: center;
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      animation: fadeIn 1.5s ease-in-out;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    p {
      font-size: 18px;
      margin-bottom: 20px;
    }

    button {
      background-color: white;
      color: #5D9FFF;
      border: none;
      padding: 10px 20px;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background-color: #5D9FFF;
      color: white;
    }

    footer {
      position: absolute;
      bottom: 10px;
      font-size: 14px;
      color: #f0f0f0;
    }
  </style>
</head>
<body>
  <h1>Salam, mən Tunar Cəfərliyəm 👋</h1>
  <p>Bu mənim ilk şəxsi saytımdır — kodlaşdırma öyrənirəm 💻</p>
  <button onclick="alert('Əlaqə: tunar@example.com')">Əlaqə üçün</button>

  <footer>© 2025 Tunar Cəfərli | GitHub Pages</footer>
</body>
</html>
