<!DOCTYPE html>

<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Professional Portfolio | Şükran Kaya</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, sans-serif;
      background-color: #0d1117;
      color: #c9d1d9;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(135deg, #1f6feb, #0d1117);
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 42px;
      margin-bottom: 10px;
    }
    header p {
      font-size: 18px;
      opacity: 0.9;
    }
    section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 30px;
      background: #161b22;
      border-radius: 14px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.3);
    }
    h2 {
      color: #58a6ff;
      border-bottom: 1px solid #30363d;
      padding-bottom: 10px;
      margin-bottom: 20px;
    }
    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }
    .skills span {
      padding: 8px 16px;
      background: #21262d;
      border-radius: 30px;
      font-size: 14px;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .project {
      background: #0d1117;
      padding: 20px;
      border-radius: 12px;
      border: 1px solid #30363d;
    }
    .project h3 {
      margin-top: 0;
      color: #58a6ff;
    }
    a {
      color: #58a6ff;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 30px;
      color: #8b949e;
      font-size: 14px;
    }
  </style>
</head>
<body>

<header>
  <h1>Şükran Kaya</h1>
  <p>Frontend Developer Adayı • HTML • CSS • JavaScript</p>
  
</header>

<section>
  <h2>👩‍💻 Hakkımda</h2>
  <p>
    Frontend geliştirme alanında kendimi geliştiren bir yazılım öğrencisiyim.
    Modern ve kullanıcı odaklı web arayüzleri oluşturmayı hedefliyorum.
    Öğrenmeye açık, disiplinli ve proje üretmeyi seven bir yapıya sahibim.
  </p>
</section>

<section>
  <h2>🛠️ Teknik Yetkinlikler</h2>
  <div class="skills">
    <span>HTML5</span>
    <span>CSS3</span>
    <span>Flexbox</span>
    <span>Responsive Design</span>
    <span>JavaScript (Temel)</span>
    <span>Git & GitHub</span>
    <span>C#</span>
    <span>PYTHON</span>
  </div>
</section>

<section>
  <h2>📁 Projeler</h2>
  <div class="projects">
    <div class="project">
      <h3>🌦️ Hava Durumu Uygulaması</h3>
      <p>JavaScript ve API kullanılarak geliştirildi. Gerçek zamanlı veri gösterimi.</p>
    </div>
    <div class="project">
      <h3>📝 Not Defteri</h3>
      <p>HTML, CSS ve JS ile oluşturulan basit ve kullanışlı not uygulaması.</p>
    </div>
    <div class="project">
      <h3>🌐 Kişisel Portfolio</h3>
      <p>Responsive tasarım, sade arayüz ve modern görünüm.</p>
    </div>
  </div>
</section>

<section>
  <h2>🎯 Kariyer Hedefleri</h2>
  <ul>
    <li>Frontend alanında uzmanlaşmak</li>
    <li>Gerçek projelerde aktif rol almak</li>
    <li>Open-source projelere katkı sağlamak</li>
  </ul>
</section>

<section>
  <h2>📬 İletişim</h2>
  <p>
    GitHub: <a href="https://github.com/sukrankaya" target="_blank">github.com/username</a><br>
    Email: sukrankya06@gmail.com
  </p>
</section>

<footer>
  © 2025 • Şükran Kaya | Professional GitHub Portfolio
</footer>

</body>
</html>
