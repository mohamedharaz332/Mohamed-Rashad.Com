<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mohamed Rashad</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #000;
      color: #fff;
      font-family: Arial, sans-serif;
      overflow: hidden;
    }

    h1 {
      font-size: 4rem;
      text-transform: uppercase;
      text-align: center;
      color: #fff;
      text-shadow: 0 0 10px #00ffcc, 0 0 20px #00ffcc, 0 0 30px #00ffcc, 0 0 40px #00ffcc;
      animation: glow 2s infinite alternate;
    }

    p {
      margin-top: 20px;
      font-size: 1.5rem;
      color: #aaa;
      text-transform: uppercase;
      animation: fadeIn 2s infinite alternate;
    }

    @keyframes glow {
      0% {
        text-shadow: 0 0 10px #00ffcc, 0 0 20px #00ffcc, 0 0 30px #00ffcc, 0 0 40px #00ffcc;
      }
      100% {
        text-shadow: 0 0 20px #00ffcc, 0 0 30px #00ffcc, 0 0 40px #00ffcc, 0 0 50px #00ffcc;
      }
    }

    @keyframes fadeIn {
      0% {
        opacity: 0.5;
      }
      100% {
        opacity: 1;
      }
    }
  </style>
</head>
<body>
  <h1>Mohamed Rashad</h1>
  <p>قريباً</p>
</body>
</html>
