<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KinglessNews | Throne and Liberty</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background-color: #0f1115;
      color: #eaeaea;
    }
    header {
      background: linear-gradient(90deg, #6a0dad, #3b1c5a);
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      letter-spacing: 2px;
    }
    nav {
      background-color: #181b22;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
      flex-wrap: wrap;
    }
    nav a {
      color: #cfa9ff;
      text-decoration: none;
      font-weight: bold;
    }
    main {
      max-width: 1100px;
      margin: 30px auto;
      padding: 0 20px;
    }
    .news {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .card {
      background-color: #1c1f27;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
    }
    footer {
      margin-top: 40px;
      background-color: #181b22;
      text-align: center;
      padding: 15px;
      font-size: 0.85em;
    }
  </style>
</head>
<body>

<header>
  <h1>KinglessNews</h1>
  <p>Onde o patch bate forte e a treta vem primeiro</p>
</header>

<nav>
  <a href="#">Notícias</a>
  <a href="#">Patch Notes</a>
  <a href="#">Balanceamento</a>
  <a href="#">Eventos</a>
  <a href="#">Guildas</a>
  <a href="#">Tretas 🔥</a>
</nav>

<main>
  <section class="news">
    <article class="card">
      <h2>Resumo da Semana</h2>
      <p>Guerras de guilda, boss disputado e muita treta no chat global.</p>
    </article>

    <article class="card">
      <h2>Patch Notes</h2>
      <p>Última manutenção trouxe mudanças importantes no balanceamento.</p>
    </article>
  </section>
</main>

<footer>
  <p>© 2026 KinglessNews</p>
</footer>

</body>
</html>
