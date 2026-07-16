<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>جمعية البركة الخيرية</title>

<link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700&display=swap" rel="stylesheet">

<style>

/* الخلفية أصبحت أنعم */
html, body {
  margin: 0;
  padding: 0;
  min-height: 100vh;
  font-family: 'Tajawal', system-ui, sans-serif;

  background: linear-gradient(
    135deg,
    #ffffff 0%,
    #e8f7f2 30%,
    #9fd8c9 70%,
    #0b6b6b 100%
  );

  display: flex;
  justify-content: center;
  align-items: center;
}

/* اللوح (انسيابي بدون قطع) */
.container {
  width: 90%;
  max-width: 360px;

  display: flex;
  flex-direction: column;
  align-items: center;

  padding: 40px 20px;

  background: linear-gradient(
    135deg,
    rgba(255,255,255,0.75) 0%,
    rgba(209,240,232,0.65) 50%,
    rgba(78,180,160,0.55) 100%
  );

  border-radius: 30px;

  border: 1px solid rgba(255,255,255,0.25);

  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);

  box-shadow:
    0 25px 60px rgba(0,0,0,0.08),
    inset 0 1px 0 rgba(255,255,255,0.5);

  text-align: center;
}

/* الشعار */
.logo {
  width: 65px;
  height: 65px;

  border-radius: 50%;
  background: #fff;

  display: flex;
  justify-content: center;
  align-items: center;

  margin-bottom: 20px;

  overflow: hidden;

  border: 1px solid rgba(0,0,0,0.05);
  box-shadow: 0 10px 25px rgba(0,0,0,0.08);
}

.logo img {
  width: 60%;
  height: 60%;
  object-fit: contain;
}

/* العنوان */
h1 {
  font-size: 30px;
  font-weight: 700;
  margin: 0 0 10px 0;
  color: #014848;
}

/* النص */
.subtitle {
  font-size: 15px;
  margin-bottom: 36px;
  color: #2f6660;
}

/* الروابط */
.links-container {
  width: 100%;
  display: flex;
  flex-direction: column;
  gap: 18px;
}

.link {
  display: flex;
  align-items: center;
  gap: 14px;

  padding: 18px 20px;
  border-radius: 18px;

  text-decoration: none;
  font-size: 16px;
  font-weight: 600;

  color: #014848;

  background: linear-gradient(135deg,#fff,#b9e6dc);

  border: 1px solid rgba(255,255,255,0.35);

  box-shadow: 0 8px 20px rgba(0,0,0,0.06);

  transition: all 0.3s ease;
}

.link:hover {
  transform: translateY(-4px);
  background: linear-gradient(135deg,#fff,#78cdbc);
  box-shadow: 0 12px 28px rgba(0,0,0,0.10);
}

/* الأيقونات */
.icon-box {
  width: 48px;
  height: 48px;
  border-radius: 14px;

  display: flex;
  justify-content: center;
  align-items: center;

  font-size: 22px;

  background: linear-gradient(135deg,#fff,#7fd2be);

  border: 1px solid rgba(255,255,255,0.4);

  box-shadow: 0 6px 14px rgba(0,0,0,0.06);
}

.text {
  flex: 1;
  text-align: right;
}

/* موبايل */
@media (max-width: 480px) {
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

<div class="container">

  <div class="logo">
    <img src="https://i.ibb.co/3mPcxTvg/cropped-917d57b8-a368-4791-bb0e-5b8d3bb3a9ff-1.png" alt="جمعية البركة الخيرية">
  </div>

  <h1>جمعية البركة الخيرية</h1>
  <p class="subtitle">نسعد بخدمتكم</p>

  <div class="links-container">

    <a href="https://www.albarkah.org/profile-request/" target="_blank" class="link">
      <div class="icon-box">📝</div>
      <div class="text">طلب تسجيل مستفيد جديد</div>
    </a>

    <a href="https://drive.google.com/file/d/1tgM7nlYtHCm0S_j5wWIDAik38PAKVcFA/view?usp=drive_link">
      <div class="icon-box">📂</div>
      <div class="text">الوثائق المطلوبة</div>
    </a>

    <a href="https://drive.google.com/file/d/1_ZSpfIPCoW8fTtFj7DSJyESUs5hqRsrP/view" target="_blank" class="link">
      <div class="icon-box">📄</div>
      <div class="text">طريقة استخراج الوثائق</div>
    </a>

  </div>

</div>

</body>
</html>
