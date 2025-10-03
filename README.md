<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>For My Rini</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
    }

    h1 {
      font-size: 3em;
      color: white;
      animation: fadeIn 2s ease-in-out;
    }

    p {
      font-size: 1.5em;
      color: white;
      margin-top: 10px;
    }

    .btn {
      margin-top: 30px;
      padding: 15px 30px;
      font-size: 1.2em;
      background: #ff4e50;
      color: white;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: #fc6076;
      transform: scale(1.1);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .heart {
      color: red;
      font-size: 2em;
      animation: pulse 1s infinite;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
  </style>
</head>
<body>
  <h1>Hello My Debosmita ❤️</h1>
  <p>From the day I met you, my world has been brighter.</p>
  <p>And today, I want to ask you...</p>
  <h1 class="heart">💍 Will You Be With Me Forever? 💍</h1>
  <button class="btn" onclick="sayYes()">Yes, Forever 💕</button>
   <button class="btn" id="noBtn" onclick="sayNo()">No 😢</button>

  <script>
    function sayYes() {
      document.body.innerHTML = `
        <h1>Yay!! 💖</h1>
        <p>I LOVE YOU MY RINI</p>
        <h2>Forever Yours ❤️</h2>
      `;
    }
       function sayNo() {
      document.body.innerHTML = `
        <h1>I Know You Love me</h1>
        <p>I will be with you forever ❤️</p>
        <h2>You’ll always be special to me 💕</h2>
      `;
    }
  </script>
</body>
</html>
