# Nano-Scan
أشعة عادية على الصدر، الحوض، والركبتين. أشعة إكس راي على الفقرات، ومفصل الفخذ. موجات صوتية على البطن والحوض. دوبلر ودوبلكس للأوردة والشرايين. إيكو على القلب للأطفال والكبار. رسم قلب، ورسم مخ عادي ومطول.
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nano-Scan</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      direction: rtl;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }
    header, footer {
      background-color: #00509e;
      color: #fff;
      text-align: center;
      padding: 1rem 0;
    }
    nav {
      background-color: #d0e1f9;
      padding: 0.5rem;
      text-align: center;
    }
    nav a {
      margin: 0 1rem;
      color: #00509e;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      padding: 1rem;
      max-width: 1200px;
      margin: auto;
      background-color: #fff;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .section {
      margin: 2rem 0;
    }
    .services {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    .service {
      border: 1px solid #ccc;
      padding: 1rem;
      border-radius: 5px;
      text-align: center;
    }
    .service img {
      width: 100%;
      border-radius: 5px;
      margin-top: 0.5rem;
    }
    @media (min-width: 768px) {
      .services {
        flex-direction: row;
      }
      .service {
        flex: 1;
        margin: 0;
      }
    }
    form input, form button {
      width: 100%;
      padding: 0.5rem;
      margin: 0.5rem 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    form button {
      background-color: #00509e;
      color: #fff;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Nano-Scan</h1>
    <p>راحتكم أولويتنا في الفحص المنزلي</p>
  </header>

  <nav>
    <a href="#home">الرئيسية</a>
    <a href="#about">من نحن</a>
    <a href="#services">خدماتنا</a>
    <a href="#appointment">حجز موعد</a>
    <a href="#contact">اتصل بنا</a>
  </nav>

  <div class="container">
    <!-- الصفحة الرئيسية -->
    <section id="home" class="section">
      <h2>مرحباً بكم في Nano-Scan</h2>
      <p>نقدم لكم أفضل خدمات الأشعة المنزلية بجودة المستشفيات، لتوفير الراحة والتشخيص الدقيق.</p>
      <img src="https://via.placeholder.com/800x300?text=صورة+رئيسية+جديدة" alt="صورة رئيسية Nano-Scan">
    </section>

    <!-- قسم "من نحن" -->
    <section id="about" class="section">
      <h2>من نحن</h2>
      <p>يعتبر Nano-Scan أول مركز متخصص في تقديم خدمات الأشعة المنزلية باستخدام أحدث التقنيات وفريق من الأطباء الخبراء، لضمان تقديم فحص دقيق وتشخيص سريع في راحة منزلك.</p>
      <img src="https://via.placeholder.com/600x300?text=صورة+عن+المركز+جديدة" alt="صورة عن Nano-Scan">
    </section>

    <!-- قسم "خدماتنا" -->
    <section id="services" class="section">
      <h2>خدماتنا</h2>
      <div class="services">
        <div class="service">
          <h3>أشعة X-Ray ديجيتال</h3>
          <p>تشخيص دقيق لجميع أجزاء الجسم باستخدام أحدث الأجهزة.</p>
          <img src="https://via.placeholder.com/400x250?text=أشعة+X-Ray+جديدة" alt="صورة أشعة X-Ray">
        </div>
        <div class="service">
          <h3>سونار البطن والحوض</h3>
          <p>فحص شامل للأعضاء الداخلية لتحديد المشاكل مبكراً.</p>
          <img src="https://via.placeholder.com/400x250?text=صورة+سونار+جديدة" alt="صورة سونار">
        </div>
        <div class="service">
          <h3>دوبلكس الأوردة والشرايين</h3>
          <p>تحديد التجلطات أو الانسدادات في الأوعية الدموية بدقة عالية.</p>
          <img src="https://via.placeholder.com/400x250?text=صورة+دوبلكس+جديدة" alt="صورة دوبلكس">
        </div>
        <div class="service">
          <h3>إيكو على القلب</h3>
          <p>فحص القلب للكشف المبكر عن أية مشاكل صحية محتملة.</p>
          <img src="https://via.placeholder.com/400x250?text=صورة+إيكو+جديدة" alt="صورة إيكو">
        </div>
      </div>
    </section>

    <!-- قسم "حجز موعد" -->
    <section id="appointment" class="section">
      <h2>حجز موعد</h2>
      <form action="#" method="post">
        <label for="name">الاسم:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="phone">رقم الهاتف:</label>
        <input type="tel" id="phone" name="phone" required>
        
        <label for="date">تاريخ الموعد:</label>
        <input type="date" id="date" name="date" required>
        
        <button type="submit">احجز الآن</button>
      </form>
    </section>

    <!-- قسم "اتصل بنا" -->
    <section id="contact" class="section">
      <h2>اتصل بنا</h2>
      <p>للمزيد من المعلومات أو الاستفسارات، يرجى التواصل معنا عبر الهاتف أو البريد الإلكتروني.</p>
      <p>هاتف: 0123456789 | بريد إلكتروني: info@nano-scan.com</p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 Nano-Scan. جميع الحقوق محفوظة.</p>
  </footer>
</body>
</html>

