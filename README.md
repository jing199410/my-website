# my-website

<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>拾藝未央｜藝術顧問</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <nav class="navbar">
    <div class="nav-container">
      <a href="#" class="logo">拾藝未央</a>
      <ul class="nav-links">
        <li><a href="#home">首頁</a></li>
        <li><a href="#about">關於</a></li>
        <li><a href="#services">服務</a></li>
        <li><a href="#contact">聯絡</a></li>
      </ul>
    </div>
  </nav>

  <section id="home" class="section home">
    <h1>拾藝未央</h1>
    <p>溫柔而堅定，藝術與靈魂的同行者</p>
  </section>

  <section id="about" class="section about">
    <h2>關於我們</h2>
    <p>我們專注於藝術策展、品牌顧問與創意整合，致力於將藝術深植生活每一刻。</p>
  </section>

  <section id="services" class="section services">
    <h2>服務項目</h2>
    <ul>
      <li>藝術策展</li>
      <li>藝術顧問諮詢</li>
      <li>品牌視覺設計</li>
    </ul>
  </section>

  <section id="contact" class="section contact">
    <h2>聯絡我們</h2>
    <p>信箱：hello@example.com</p>
    <p>IG：@yourbrand</p>
  </section>

  <footer>
    <p>&copy; 2025 拾藝未央 | All Rights Reserved</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: "Noto Sans TC", sans-serif;
  background-color: #fefcf9;
  color: #333;
  line-height: 1.6;
}

.navbar {
  position: fixed;
  top: 0;
  width: 100%;
  background: white;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  z-index: 1000;
}

.nav-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 960px;
  margin: auto;
  padding: 1rem;
}

.logo {
  font-weight: bold;
  font-size: 1.4rem;
  color: #333;
  text-decoration: none;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1rem;
}

.nav-links a {
  text-decoration: none;
  color: #333;
  transition: color 0.3s ease;
}

.nav-links a:hover {
  color: #72a579;
}

.section {
  padding: 100px 20px;
  max-width: 800px;
  margin: 0 auto;
}

.home {
  background-color: #eaf3ea;
  text-align: center;
  padding-top: 120px;
}

.about, .services, .contact {
  background-color: #fff;
  margin-top: 30px;
}

footer {
  text-align: center;
  background: #f2f2f2;
  padding: 1rem;
  font-size: 0.9rem;
  margin-top: 50px;
}

/* 手機響應 */
@media (max-width: 768px) {
  .nav-links {
    flex-direction: column;
    gap: 0.5rem;
  }
}
