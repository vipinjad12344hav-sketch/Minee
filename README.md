# Minee
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Propose Day ❤️</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #ffe3ec, #fff7fa);
      color: #4a1025;
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 70px 20px;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      color: #c2185b;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2rem;
    }
    .ring {
      font-size: 3rem;
      animation: float 3s ease-in-out infinite;
      display: inline-block;
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-12px); }
    }
    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
    }
    .card {
      background: #ffffffcc;
      border-radius: 18px;
      padding: 30px;
      margin-bottom: 35px;
      box-shadow: 0 12px 28px rgba(0,0,0,0.08);
    }
    .card h2 {
      font-family: 'Playfair Display', serif;
      color: #c2185b;
      margin-bottom: 12px;
    }
    .feelings-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .feel-box {
      border-radius: 16px;
      padding: 22px;
      text-align: center;
      background: linear-gradient(135deg, #ffe6f0, #fff);
    }
    .feel-box span {
      font-size: 2.3rem;
      display: block;
      margin-bottom: 10px;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 14px 28px;
      background: #c2185b;
      color: #fff;
      border-radius: 30px;
      text-decoration: none;
      font-weight: 600;
      transition: transform 0.2s ease, background 0.2s ease;
    }
    .btn:hover {
      background: #a3154c;
      transform: scale(1.05);
    }
    footer {
      text-align: center;
      padding: 35px 15px;
      background: #c2185b;
      color: #fff;
    }
    .heart {
      color: #ffd1e1;
      animation: pulse 1.4s infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
    .heart-fall {
      position: fixed;
      top: -10px;
      font-size: 20px;
      animation: fall linear infinite;
      color: #ff4d6d;
      pointer-events: none;
      z-index: 999;
    }
    @keyframes fall {
      to {
        transform: translateY(110vh);
        opacity: 0;
      }
    }
  </style>
</head>
<body>  <header>
    <div class="ring">💍</div>
    <h1>Happy Propose Day, Saeee ❤️</h1>
    <p>This isn’t just a page… it’s my heart asking <strong>you, Saeee</strong>, a question 💖</p>
  </header>  <section>
    <div class="card">
      <h2>Why I Choose You</h2>
      <p>
        From small smiles to deep conversations, every moment with you feels right.
        You make my ordinary days special and my special days unforgettable.
      </p>
    </div><div class="card">
  <h2>What You Mean to Me</h2>
  <div class="feelings-grid">
    <div class="feel-box">
      <span>❤️</span>
      <strong>My Love</strong>
      <p>You are the feeling my heart searched for.</p>
    </div>
    <div class="feel-box">
      <span>🤝</span>
      <strong>My Partner</strong>
      <p>With you, every journey feels easier.</p>
    </div>
    <div class="feel-box">
      <span>😊</span>
      <strong>My Happiness</strong>
      <p>Your smile is my favorite view.</p>
    </div>
    <div class="feel-box">
      <span>🌍</span>
      <strong>My World</strong>
      <p>You make my world complete.</p>
    </div>
  </div>
</div>

<div class="card">
  <h2>My Proposal 💍</h2>
  <p>
    I don’t promise perfection, but I promise honesty, care, and love.
    I promise to stand by you, support you, and choose you—every single day.
  </p>
  <p style="margin-top:15px; font-weight:600;">
    Will you be mine, today and always?
  </p>
  <div style="text-align:center;">
    <a href="#" class="btn" onclick="alert('You just made me the happiest person ❤️');">Yes 💖</a>
    &nbsp;&nbsp;
    <a href="#" class="btn" style="background:#999;" onclick="alert('I will still wait for you, Saeee ❤️');">Let me think 💭</a>
  </div>
</div>

  </section>  <footer>
    <p>Made with <span class="heart">❤️</span> only for you</p>
  </footer><script>
    const createHeart = () => {
      const heart = document.createElement('div');
      heart.classList.add('heart-fall');
      heart.innerText = '❤️';
      heart.style.left = Math.random() * 100 + 'vw';
      heart.style.animationDuration = (3 + Math.random() * 3) + 's';
      document.body.appendChild(heart);
      setTimeout(() => heart.remove(), 6000);
    };
    setInterval(createHeart, 400);
  </script></body>
</html>
