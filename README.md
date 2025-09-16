<!DOCTYPE html>
<html lang="kk">
<head>
  <meta charset="UTF-8">
  <title>Менің портфолиом</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #0073e6;
      color: white;
      text-align: center;
      padding: 20px;
    }
    section {
      max-width: 800px;
      margin: 20px auto;
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
    h2 {
      color: #0073e6;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background: #0073e6;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background: #005bb5;
    }
    img {
      border-radius: 50%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Жалғас</h1>
    <p>Email: zhalgas.manap008@gmail.com | Тел: +7 747 014 6598</p>
  </header>

  <section id="about">
    <h2>Өзім жайлы</h2>
    <img src="https://ru-static.z-dn.net/files/d6b/d056d3496da92b9c7114a857bf74a435.jpeg" 
         alt="Менің суретім" width="150">
    <p>Мен веб-бағдарламалауға қызығатын студентпін. HTML, CSS, JavaScript үйреніп жүрмін.</p>
  </section>

  <section id="projects">
    <h2>Жобаларым</h2>
    <ul>
      <li>Жеке блог</li>
      <li>Интернет магазин</li>
      <li>Портфолио сайты</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Байланыс</h2>
    <form>
      <input type="text" placeholder="Атыңыз">
      <input type="email" placeholder="Email">
      <textarea placeholder="Хабарлама"></textarea>
      <button type="submit">Жіберу</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Жалғас</p>
  </footer>
</body>
</html>
