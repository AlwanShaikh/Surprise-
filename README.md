<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Girlfriend's Day Affi</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to top, #ffcccc, #ff99cc);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      overflow: hidden;
      color: #fff;
      text-align: center;
    }
    .hearts {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      z-index: 0;
      pointer-events: none;
    }
    .typewriter {
      font-size: 2em;
      margin-top: 100px;
      width: 90%;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
      overflow: hidden;
      white-space: nowrap;
      border-right: .15em solid white;
      animation: typing 4s steps(40, end), blink-caret .75s step-end infinite;
    }
    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }
    @keyframes blink-caret {
      from, to { border-color: transparent }
      50% { border-color: white; }
    }
    .btn {
      margin-top: 30px;
      padding: 12px 25px;
      font-size: 1em;
      border: none;
      border-radius: 30px;
      background-color: #ff66a3;
      color: white;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background-color: #ff3385;
    }
    .popup {
      display: none;
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background: white;
      color: #333;
      padding: 30px;
      border-radius: 15px;
      max-width: 90%;
      max-height: 80%;
      overflow-y: auto;
      z-index: 999;
    }
    .popup p {
      white-space: pre-line;
    }
    .close {
      background: #ff3399;
      color: white;
      border: none;
      padding: 8px 15px;
      border-radius: 8px;
      margin-top: 15px;
      cursor: pointer;
    }
    .candle {
      margin-top: 50px;
      font-size: 3em;
      animation: flicker 1s infinite;
    }
    @keyframes flicker {
      0% { opacity: 1; }
      50% { opacity: 0.5; }
      100% { opacity: 1; }
    }
  </style>
</head>
<body>
  <div class="hearts"></div>
  <div class="typewriter">Happy Girlfriend's Day, Affi.</div>
  <button class="btn" onclick="showLetter()">Open Love Letter</button>
  <div class="popup" id="letterPopup">
    <p>
      The first time I saw u in real life not as a friend but as someone more important than that someone who literally changed my life was during college registration day and the eye contact we made at book store was like it was meant to happen as if the world paused just for us and then the first day of college came when we both goes in the auto rickshaw holding hands for the very first time my heart was racing like never before and the way you put your head on my shoulder made me feel like i was home we ate tiffin together every lunch break like it was a daily date and you gifted me a jacket hoodie which i still treasure because it holds your love in every thread i loved seeing you smile when you wore it because it was mine but you made it yours you made everything beautiful just by being there and even today every moment with you feels like a gift you are my peace my chaos my magic and my reality i never want to let go of your hand no matter what this life brings because i promised you i will never leave you and i stand by that forever and always you are the softest chapter in my loudest story the calm in my storm the light in my darkest nights you’re not just my girlfriend affi you are the heartbeat that gives rhythm to my life and when you smile my world feels perfect when you cry my soul breaks so i vow to always protect that smile always hold that hand and walk beside you through every season every sunset every tomorrow we’ve written a love story and it’s only the beginning and i can’t wait for all the chapters ahead with you
    </p>
    <button class="close" onclick="closeLetter()">Close</button>
  </div>
  <div class="candle">🕯️</div>
  <script>
    function showLetter() {
      document.getElementById("letterPopup").style.display = "block";
    }
    function closeLetter() {
      document.getElementById("letterPopup").style.display = "none";
    }const heartsContainer = document.querySelector('.hearts');
for (let i = 0; i < 50; i++) {
  const heart = document.createElement('div');
  heart.textContent = '💖';
  heart.style.position = 'absolute';
  heart.style.left = Math.random() * 100 + 'vw';
  heart.style.top = Math.random() * 100 + 'vh';
  heart.style.fontSize = (Math.random() * 2 + 1) + 'em';
  heart.style.animation = `float ${Math.random() * 5 + 5}s ease-in infinite`;
  heartsContainer.appendChild(heart);
}

  </script>
</body>
</html>
