<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Surprise for Sujal</title>
  <style>
    body {
      background: linear-gradient(to right, #ffecd2, #fcb69f);
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      text-align: center;
    }
    h1 {
      font-size: 2.5rem;
      color: #333;
    }
    p {
      font-size: 1.2rem;
      margin: 20px 0;
    }
    a.button {
      padding: 12px 24px;
      background: #ff6f61;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      border-radius: 10px;
      transition: background 0.3s;
    }
    a.button:hover {
      background: #e85c50;
    }
  </style>
</head>
<body>
  <h1>Finally! Fool is getting into his 20s 😆</h1>
  <p>Here’s something special for you...</p>
  <a class="button" href="birthday.html">Click to Begin the Madness!</a>
</body>
</html>
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Birthday Sujal</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #a1c4fd, #c2e9fb);
      padding: 20px;
      color: #222;
    }
    h1 {
      font-size: 3rem;
      text-align: center;
      margin-bottom: 10px;
      color: #ff6f61;
    }
    .quote {
      text-align: center;
      font-style: italic;
      margin-bottom: 30px;
    }
    .section {
      margin-bottom: 20px;
    }
    .section h2 {
      color: #444;
      border-bottom: 2px solid #ff6f61;
    }
    .memory {
      margin: 15px 0;
    }
    .signature {
      margin-top: 40px;
      padding: 20px;
      background: #fff6f0;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: center;
      font-weight: bold;
    }
    .confetti {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: 999;
    }
  </style>
</head>
<body>
  <canvas class="confetti" id="confetti-canvas"></canvas>  <h1>Happy Birthday Sujal! 🎉</h1>
  <p class="quote">May your 20s be as vibrant as your guitar riffs, as calm as a cat’s nap, and filled with melodies only you can create.</p>  <div class="section">
    <h2>Memories & Friendship</h2>
    <div class="memory">
      <strong>🛵 Long Drives:</strong> 
      Every journey felt infinite with you riding beside me — from random chai stops to late-night roads, you were always my permanent co-rider.
    </div>
    <div class="memory">
      <strong>🚲 Bike Riding Lessons:</strong> 
      You didn’t just teach me to balance on two wheels — you taught me confidence, patience, and how to laugh at falls.
    </div>
    <div class="memory">
      <strong>🍿 Late-Night Movies:</strong> 
      From horror marathons to emotional dramas, our late-night movie sessions turned into life talks and endless laughter.
    </div>
    <div class="memory">
      <strong>🌙 Overnight Talks:</strong> 
      Those 2 a.m. conversations were therapy — no topic was too deep, no secret left untold. Thank you for being the listener everyone needs.
    </div>
    <div class="memory">
      <strong>📚 Studying Together:</strong> 
      Whether I was teaching you or we were solving papers at midnight, it always ended in snacks, memes, and memories that made exams fun.
    </div>
    <div class="memory">
      <strong>😌 Therapist Vibes:</strong> 
      You never failed to calm the chaos in my mind. I’ve cried, ranted, and overthought around you — and you stayed, always.
    </div>
    <div class="memory">
      <strong>💃 Garba Partner:</strong> 
      We were never just dancing — we were vibing, spinning through music, lights, and dandiya madness. You match my energy like no one else.
    </div>
    <div class="memory">
      <strong>🐱 Cat Connection:</strong> 
      Every time I see a cat, I think of you. Two soft-hearted cat lovers in a not-so-soft world — that’s our bond.
    </div>
    <div class="memory">
      <strong>🎸 Your Music:</strong> 
      Your voice has magic, your guitar speaks, and your flute brings peace. Never stop making music — the world needs it, and so do I.
    </div>
  </div>  <div class="signature">
    I know I annoy you more than mosquito bites in summer,<br>
    but hey — you still haven’t thrown me out of your life! That counts, right? 😅<br><br>
    Thank you for being my safest place, my loudest laugh, and my quietest comfort.<br>
    Life threw glitter when it gave me a friend like you.<br><br>
    Keep being the incredible human you are. Your 20s are going to be unforgettable — just like our friendship.<br><br>
    — Kadva Patel 🤟<br>
    <small>(Don’t take it too serious, ChatGPT helped me 😄)</small>
  </div>  <script>
    const canvas = document.getElementById('confetti-canvas');
    const confetti = canvas.getContext('2d');
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
    const pieces = Array.from({ length: 100 }, () => ({
      x: Math.random() * canvas.width,
      y: Math.random() * canvas.height,
      size: Math.random() * 5 + 2,
      speedY: Math.random() * 3 + 1,
      color: `hsl(${Math.random() * 360}, 100%, 70%)`
    }));
    function draw() {
      confetti.clearRect(0, 0, canvas.width, canvas.height);
      for (const p of pieces) {
        confetti.fillStyle = p.color;
        confetti.fillRect(p.x, p.y, p.size, p.size);
        p.y += p.speedY;
        if (p.y > canvas.height) p.y = 0;
      }
      requestAnimationFrame(draw);
    }
    draw();
  </script></body>
</html>
