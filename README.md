<!DOCTYPE html>
<html lang="ar" dir="rtl">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>جمعية البركة الخيرية</title>

  <link
    href="https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700&display=swap"
    rel="stylesheet"
  >

  <style>

    * {
      box-sizing: border-box;
    }

    html,
    body {
      margin: 0;
      padding: 0;
      min-height: 100vh;
    }

    body {
      font-family: 'Tajawal', system-ui, sans-serif;

      display: flex;
      justify-content: center;
      align-items: center;

      padding: 20px;

      background:
        linear-gradient(
          135deg,
          #ffffff 0%,
          #e8f7f2 30%,
          #9fd8c9 70%,
          #0b6b6b 100%
        );
    }

    .container {
      width: 100%;
      max-width: 360px;

      display: flex;
      flex-direction: column;
      align-items: center;

      padding: 40px 20px;

      text-align: center;

      background:
        linear-gradient(
          135deg,
          rgba(255, 255, 255, 0.75) 0%,
          rgba(209, 240, 232, 0.65) 50%,
          rgba(78, 180, 160, 0.55) 100%
        );

      border: 1px solid rgba(255, 255, 255, 0.25);
      border-radius: 30px;

      backdrop-filter: blur(20px);
      -webkit-backdrop-filter: blur(20px);

      box-shadow:
        0 25px 60px rgba(0, 0, 0, 0.08),
        inset 0 1px 0 rgba(255, 255, 255, 0.5);
    }

    .logo {
      width: 65px;
      height: 65px;

      display: flex;
      justify-content: center;
      align-items: center;

      margin-bottom: 20px;

      overflow: hidden;

      background: #ffffff;

      border: 1px solid rgba(0, 0, 0, 0.05);
      border-radius: 50%;

      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
    }

    .logo img {
      width: 60%;
      height: 60%;

      object-fit: contain;
    }

    h1 {
      margin: 0 0 10px;

      color: #014848;

      font-size: 30px;
      font-weight: 700;
    }

    .subtitle {
      margin: 0 0 36px;

      color: #2f6660;

      font-size: 15px;
    }

    .links-container {
      width: 100%;

      display: flex;
      flex-direction: column;

      gap: 18px;
    }

    .link {
      width: 100%;

      display: flex;
      align-items: center;

      gap: 14px;

      padding: 18px 20px;

      color: #014848;

      font-size: 16px;
      font-weight: 600;

      text-decoration: none;

      background:
        linear-gradient(
          135deg,
          #ffffff,
          #b9e6dc
        );

      border: 1px solid rgba(255, 255, 255, 0.35);
      border-radius: 18px;

      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.06);

      transition:
        transform 0.3s ease,
        background 0.3s ease,
        box-shadow 0.3s ease;
    }

    .link:hover {
      transform: translateY(-4px);

      background:
        linear-gradient(
          135deg,
          #ffffff,
          #78cdbc
        );

      box-shadow: 0 12px 28px rgba(0, 0, 0, 0.10);
    }

    .link:active {
      transform: scale(0.98);
    }

    .icon-box {
      width: 48px;
      height: 48px;

      flex-shrink: 0;

      display: flex;
      justify-content: center;
      align-items: center;

      font-size: 22px;

      background:
        linear-gradient(
          135deg,
          #ffffff,
          #7fd2be
        );

      border: 1px solid rgba(255, 255, 255, 0.4);
      border-radius: 14px;

      box-shadow: 0 6px 14px rgba(0, 0, 0, 0.06);
    }

    .text {
      flex: 1;
      text-align: right;
    }

    @media (max-width: 480px) {

      body {
        padding: 16px;
      }

      .container {
        padding: 35px 18px;
      }

      h1 {
        font-size: 25px;
      }

      .subtitle {
        font-size: 14px;
      }

      .link {
        padding: 16px;
        font-size: 14px;
      }

      .icon-box {
        width: 44px;
        height: 44px;
        font-size: 20px;
      }

    }

  </style>
</head>

<body>

  <main class="container">

    <div class="logo">
      <img
        src="https://i.ibb.co/3mPcxTvg/cropped-917d57b8-a368-4791-bb0e-5b8d3bb3a9ff-1.png"
        alt="شعار جمعية البركة الخيرية"
      >
    </div>

    <h1>جمعية البركة الخيرية</h1>

    <p class="subtitle">
      نسعد بخدمتكم
    </p>

    <div class="links-container">

      <a
        href="https://www.albarkah.org/profile-request/"
        target="_blank"
        rel="noopener noreferrer"
        class="link"
      >
        <div class="icon-box">📝</div>
        <div class="text">
          طلب تسجيل مستفيد جديد
        </div>
      </a>

      <a
        href="https://drive.google.com/file/d/1tgM7nlYtHCm0S_j5wWIDAik38PAKVcFA/view?usp=drive_link"
        target="_blank"
        rel="noopener noreferrer"
        class="link"
      >
        <div class="icon-box">📂</div>
        <div class="text">
          الوثائق المطلوبة
        </div>
      </a>

      <a
        href="https://drive.google.com/file/d/1_ZSpfIPCoW8fTtFj7DSJyESUs5hqRsrP/view"
        target="_blank"
        rel="noopener noreferrer"
        class="link"
      >
        <div class="icon-box">📄</div>
        <div class="text">
          طريقة استخراج الوثائق
        </div>
      </a>

    </div>

  </main>

</body>

</html>
