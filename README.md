<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Alislamiah Search Console</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, Tahoma, sans-serif;
      min-height: 100vh;
      background: #06101f;
      color: #ffffff;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 20px;
    }

    .container {
      width: 100%;
      max-width: 720px;
      text-align: center;
    }

    /* الشعار */
    .logo {
      width: 82px;
      height: 82px;
      margin: 0 auto 24px;
      border-radius: 22px;
      object-fit: cover;
      box-shadow: 0 10px 35px rgba(0, 0, 0, 0.45);
    }

    .brand {
      font-size: 17px;
      color: #6fa8ff;
      font-weight: bold;
      letter-spacing: 0.5px;
      margin-bottom: 14px;
    }

    h1 {
      font-size: 32px;
      line-height: 1.4;
      margin-bottom: 18px;
      font-weight: 800;
    }

    .description {
      color: #aebdce;
      font-size: 17px;
      line-height: 1.9;
      max-width: 600px;
      margin: 0 auto 32px;
    }

    /* البطاقة */
    .card {
      background: #091a30;
      border: 1px solid #163252;
      border-radius: 24px;
      padding: 35px 28px;
      box-shadow: 0 18px 55px rgba(0, 0, 0, 0.35);
    }

    .icon {
      width: 64px;
      height: 64px;
      margin: 0 auto 20px;
      border-radius: 18px;
      background: #0d2948;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 30px;
    }

    .card h2 {
      font-size: 22px;
      margin-bottom: 13px;
    }

    .card p {
      color: #aebdce;
      font-size: 15px;
      line-height: 1.8;
      margin-bottom: 25px;
    }

    /* زر واتساب */
    .whatsapp {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      width: 100%;
      max-width: 420px;
      padding: 16px 25px;
      border-radius: 14px;
      background: #168f55;
      color: white;
      text-decoration: none;
      font-size: 17px;
      font-weight: bold;
      transition: 0.2s;
    }

    .whatsapp:hover {
      background: #20a965;
      transform: translateY(-2px);
    }

    .whatsapp-icon {
      font-size: 23px;
    }

    /* الفاصل */
    .divider {
      height: 1px;
      background: #17324f;
      margin: 32px 0;
    }

    /* الإنجليزية */
    .english {
      direction: ltr;
      text-align: center;
    }

    .english h2 {
      font-size: 21px;
      margin-bottom: 12px;
    }

    .english p {
      color: #aebdce;
      line-height: 1.8;
      font-size: 15px;
    }

    footer {
      margin-top: 25px;
      color: #61758d;
      font-size: 13px;
    }

    @media (max-width: 600px) {
      h1 {
        font-size: 26px;
      }

      .description {
        font-size: 15px;
      }

      .card {
        padding: 28px 20px;
      }
    }
  </style>
</head>

<body>

  <main class="container">

    <!-- ضع شعارك هنا إذا أردت -->
    <img
      src="icon.png"
      alt="Alislamiah AI"
      class="logo"
      onerror="this.style.display='none';"
    >

    <div class="brand">
      Alislamiah AI
    </div>

    <h1>
      مرحباً بك في مركز فهرسة المواقع
    </h1>

    <p class="description">
      لدى <strong>Alislamiah AI</strong><br>
      يمكنك إرسال طلب لإضافة موقعك إلى فهرس البحث الخاص بنا.
    </p>

    <section class="card">

      <div class="icon">
        🔎
      </div>

      <h2>
        طلب فهرسة موقعك
      </h2>

      <p>
        اضغط على الزر أدناه للانتقال إلى WhatsApp،
        ثم أرسل لنا <strong>رابط موقعك ووصفاً مختصراً عنه</strong>.
        سيقوم فريق Alislamiah AI بمراجعة طلبك.
      </p>

      <a
        class="whatsapp"
        href="https://wa.me/213777543015"
        target="_blank"
        rel="noopener noreferrer"
      >
        <span class="whatsapp-icon">💬</span>
        إرسال طلب الفهرسة عبر WhatsApp
      </a>

      <div class="divider"></div>

      <div class="english">

        <h2>
          Website Indexing Request
        </h2>

        <p>
          Welcome to the <strong>Alislamiah AI Website Indexing Center</strong>.
          To request the indexing of your website in our search index,
          click the button above and send us your
          <strong>website URL and a short description</strong> via WhatsApp.
        </p>

      </div>

    </section>

    <footer>
      © 2026 Alislamiah AI — Website Indexing Center
    </footer>

  </main>

</body>
</html>
