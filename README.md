# thespringstar
It's Asterina Mitchell's personal website where she uploads her roman or poetry's
<!DOCTYPE html>
<html lang="mn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ХАВРЫН ОД | THE SPRING STAR</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header -->
  <header class="header">
    <div class="logo">
      <h1>ХАВРЫН ОД</h1>
      <p>THE SPRING STAR</p>
    </div>

    <nav class="nav">
      <a href="#home">Нүүр</a>
      <a href="#books">Номууд</a>
      <a href="#stories">Зохиолууд</a>
      <a href="#about">Миний тухай</a>
      <a href="#contact">Холбоо барих</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <h2>Уран зохиолын ертөнцөд тавтай морил ✨</h2>
    <p>
      Энэ бол "ХАВРЫН ОД" — миний бичсэн романууд, өгүүллэгүүд, шүлгүүдийн цуглуулга.
    </p>
    <button class="btn" onclick="scrollToSection('books')">Номуудыг үзэх</button>
  </section>

  <!-- Books Section -->
  <section id="books" class="section">
    <h2 class="section-title">📚 Миний романууд</h2>

    <div class="grid">

      <div class="card">
        <h3>Роман #1</h3>
        <p class="desc">Энд романы товч тайлбар орно.</p>
        <button class="read-btn" onclick="openModal('Роман #1', 'Энд романы эхлэл эсвэл хэсэг текст орно...')">
          Унших
        </button>
      </div>

      <div class="card">
        <h3>Роман #2</h3>
        <p class="desc">Энд романы товч тайлбар орно.</p>
        <button class="read-btn" onclick="openModal('Роман #2', 'Энд романы эхлэл эсвэл хэсэг текст орно...')">
          Унших
        </button>
      </div>

      <div class="card">
        <h3>Роман #3</h3>
        <p class="desc">Энд романы товч тайлбар орно.</p>
        <button class="read-btn" onclick="openModal('Роман #3', 'Энд романы эхлэл эсвэл хэсэг текст орно...')">
          Унших
        </button>
      </div>

    </div>
  </section>

  <!-- Stories Section -->
  <section id="stories" class="section">
    <h2 class="section-title">🖋 Өгүүллэг, зохиолууд</h2>

    <div class="grid">

      <div class="card">
        <h3>Өгүүллэг #1</h3>
        <p class="desc">Энд өгүүллэгийн товч тайлбар орно.</p>
        <button class="read-btn" onclick="openModal('Өгүүллэг #1', 'Энд өгүүллэгийн текстийг оруулна...')">
          Унших
        </button>
      </div>

      <div class="card">
        <h3>Өгүүллэг #2</h3>
        <p class="desc">Энд өгүүллэгийн товч тайлбар орно.</p>
        <button class="read-btn" onclick="openModal('Өгүүллэг #2', 'Энд өгүүллэгийн текстийг оруулна...')">
          Унших
        </button>
      </div>

      <div class="card">
        <h3>Шүлэг #1</h3>
        <p class="desc">Энд шүлгийн товч тайлбар орно.</p>
        <button class="read-btn" onclick="openModal('Шүлэг #1', 'Энд шүлгийн текстийг оруулна...')">
          Унших
        </button>
      </div>

    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="section about">
    <h2 class="section-title">🌙 Миний тухай</h2>
    <p>
      Сайн байна уу? Намайг (Эгшиглэн) гэдэг.  
      Миний ном зохиол танд таалагдана гэдэгт итгэлтэй байна.
    </p>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section contact">
    <h2 class="section-title">📩 Холбоо барих</h2>
    <p>Санал хүсэлт, хамтран ажиллах бол доорх хэсгээр надтай холбогдоорой.</p>

    <form class="contact-form">
      <input type="text" placeholder="Нэр" required />
      <input type="email" placeholder="ast3rinaa@gmail.com" required />
      <textarea placeholder="Instagram: asterina_mi"..." required></textarea>
      <button type="submit" class="btn">Илгээх</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <p>© 2026 ХАВРЫН ОД | THE SPRING STAR. Зөвшөөрөлгүй хуулбарлахыг хориглоно.</p>
  </footer>

  <!-- Modal -->
  <div id="modal" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeModal()">&times;</span>
      <h2 id="modalTitle"></h2>
      <p id="modalText"></p>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
