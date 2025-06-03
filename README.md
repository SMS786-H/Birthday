# Birthday
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Happy Birthday!</title>
  <style>
    :root {
      --bg-gradient: linear-gradient(135deg, #f6d365 0%, #fda085 100%);
      --primary-color: #fff;
      --font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    body {
      margin: 0;
      padding: 0;
      font-family: var(--font-family);
      background: var(--bg-gradient);
      color: var(--primary-color);
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }
    h1 {
      font-size: 4rem;
      margin-bottom: 0.5rem;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.3);
    }
    p {
      font-size: 1.5rem;
      margin: 0 0 2rem 0;
      text-shadow: 1px 1px 5px rgba(0,0,0,0.2);
    }
    .cake {
      width: 150px;
      height: 150px;
      background: #ff6f91;
      border-radius: 0 0 20px 20px;
      position: relative;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      margin-bottom: 2rem;
    }
    .candle {
      width: 10px;
      height: 40px;
      background: #ffd166;
      border-radius: 3px;
      position: absolute;
      top: -40px;
      left: 50%;
      transform: translateX(-50%);
      box-shadow: 0 0 10px #ffd166;
      animation: flicker 1.5s infinite alternate;
    }
    @keyframes flicker {
      0% { box-shadow: 0 0 10px #ffd166; }
      100% { box-shadow: 0 0 20px #ffbe3f; }
    }
    footer {
      position: absolute;
      bottom: 10px;
      font-size: 0.8rem;
      opacity: 0.7;
    }
    @media (max-width: 600px) {
      h1 {
        font-size: 3rem;
      }
      .cake {
        width: 120px;
        height: 120px;
      }
    }
  </style>
</head>
<body>
  <div class="cake">
    <div class="candle"></div>
  </div>
  <h1>Happy Birthday!</h1>
  <p>Wishing you a day filled with love, joy, and cake.</p>
  <footer>Made with ❤️ on GitHub Pages</footer>
</body>
</html>

