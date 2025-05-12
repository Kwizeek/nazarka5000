<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ShakillPvPClub - Minecraft Сервер</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to bottom, #0d47a1, #ffffff);
      color: #000;
    }

    header {
      background-color: rgba(0, 0, 0, 0.8);
      text-align: center;
      padding: 60px 20px;
      color: white;
    }

    header h1 {
      font-size: 3em;
      margin: 0;
      color: #4CAF50;
    }

    nav {
      background: #111;
      text-align: center;
      padding: 12px 0;
    }

    nav a {
      color: #4CAF50;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
    }

    .container {
      background-color: rgba(255, 255, 255, 0.9);
      padding: 40px;
      max-width: 1000px;
      margin: 30px auto;
      border-radius: 10px;
      color: #000;
    }

    .btn {
      background-color: #4CAF50;
      border: none;
      padding: 10px 20px;
      color: white;
      font-size: 18px;
      cursor: pointer;
      border-radius: 5px;
    }

    .btn:hover {
      background-color: #45a049;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: rgba(0, 0, 0, 0.7);
      font-size: 14px;
      color: white;
      margin-top: 40px;
    }

    section {
      margin-bottom: 40px;
    }

    ul {
      list-style-type: "✓ ";
      padding-left: 20px;
    }

    iframe {
      border-radius: 10px;
    }

    a {
      color: #0d47a1;
    }
  </style>
</head>
<body>

  <header>
    <h1>ShakillPvPClub</h1>
    <p>Копия Hypixel для русскоязычного сообщества. Все режимы — на одном сервере!</p>
    <button class="btn" onclick="copyIP()">Играть сейчас</button>
    <p id="copied" style="display:none; color:lightgreen; margin-top:10px;">IP скопирован: shakillpvpclub.minefort.com</p>
  </header>

  <nav>
    <a href="#about">О сервере</a>
    <a href="#modes">Режимы</a>
    <a href="#donate">Донат</a>
    <a href="#media">Медиа</a>
    <a href="#team">Создатели</a>
    <a href="#contacts">Контакты</a>
  </nav>

  <div class="container">
    <section id="about">
      <h2>О сервере</h2>
      <p><strong>ShakillPvPClub</strong> — Minecraft-сервер на версии от <strong>1.8.9 до последней</strong>, вдохновлённый Hypixel. Множество режимов, пвп, ивенты и активное комьюнити.</p>
    </section>

    <section id="modes">
      <h2>Доступные режимы</h2>
      <ul>
        <li>PvP-арены и дуэли</li>
        <li>BedWars / SkyWars</li>
        <li>SMP (выживание с друзьями)</li>
        <li>Мини-игры</li>
        <li>Анархия</li>
      </ul>
    </section>

    <section id="donate">
      <h2>Донат</h2>
      <p>Скоро появится магазин с рангами и бонусами. Поддержи проект — получай преимущества!</p>
      <p><em>Следи за новостями в Discord.</em></p>
    </section>

    <section id="media">
      <h2>Медиа</h2>
      <p>🎬 <strong>Трейлер скоро появится!</strong></p>
      <iframe width="100%" height="400" src="https://www.youtube.com/embed/" allowfullscreen></iframe>
      <p>🖼️ Скриншоты сервера — скоро здесь!</p>
    </section>

    <section id="team">
      <h2>Создатели сервера</h2>
      <p><strong>Создатель:</strong> SadKill001</p>
      <p><strong>Админ:</strong> ShaMel0_0</p>
    </section>

    <section id="contacts">
      <h2>Контакты</h2>
      <p><strong>IP:</strong> shakillpvpclub.minefort.com</p>
      <p><strong>Discord:</strong> <a href="https://discord.com/channels/1371476409565843561/1371476410035736730" target="_blank">Присоединяйся к серверу</a></p>
      <p>Email: shakillpvpclub@gmail.com</p>
    </section>
  </div>

  <footer>
    &copy; 2025 ShakillPvPClub. Все права защищены.
  </footer>

  <script>
    function copyIP() {
      navigator.clipboard.writeText("shakillpvpclub.minefort.com");
      document.getElementById("copied").style.display = "block";
    }
  </script>

</body>
</html>
