<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>For Mehu 💞</title>
  <style>
    body {
      margin: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background: linear-gradient(135deg, #ffc0cb, #ffe4e1);
      color: #d63384;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      overflow: hidden;
    }
    h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 1rem 1.5rem;
    }
    button {
      background-color: #ff69b4;
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      border-radius: 25px;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    button:hover {
      background-color: #ff1493;
    }
    .surprise {
      display: none;
      margin-top: 2rem;
      animation: fadeIn 1s ease-in-out forwards;
    }
    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    .hearts {
      position: fixed;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      pointer-events: none;
      z-index: -1;
    }
    .heart {
      position: absolute;
      color: pink;
      font-size: 2rem;
      animation: floatUp 6s linear infinite;
    }
    @keyframes floatUp {
      0% { transform: translateY(100vh); opacity: 1; }
      100% { transform: translateY(-10vh); opacity: 0; }
    }
  </style>
</head>
<body>
  <h1>For Mehu 💞</h1>
  <p>Hi Mehu! 💖<br>
    You're the cutest part of my world.<br>
    I made this page just for you, because you deserve a little magic. ✨<br>
    I love you so much! 💌<br><br>
    I'm really sorry — sach mein, ab aur nahi hasunga.<br>
    You're everything to me, and I promise to always try my best for you. 🤍</p>

  <button onclick="showSurprise()">Click here for your surprise 🌟</button>

  <div id="surprise" class="surprise">
    <p>🎁 Surprise! You're my everything, forever and always. 💍💕</p>
    <img src="/mnt/data/photo_2025-05-04_22-39-27.jpg" alt="Cute Surprise" style="width: 200px; border-radius: 1rem; box-shadow: 0 4px 10px rgba(0,0,0,0.2);">
  </div>

  <div class="hearts">
    <span class="heart" style="left: 10%; animation-delay: 0s;">💗</span>
    <span class="heart" style="left: 30%; animation-delay: 2s;">💖</span>
    <span class="heart" style="left: 50%; animation-delay: 4s;">💘</span>
    <span class="heart" style="left: 70%; animation-delay: 1s;">💓</span>
    <span class="heart" style="left: 90%; animation-delay: 3s;">💕</span>
  </div>

  <script>
    function showSurprise() {
      document.getElementById('surprise').style.display = 'block';
    }
  </script>
</body>
</html>
