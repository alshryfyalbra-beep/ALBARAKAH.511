<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>جمعية البركة الخيرية</title>

<link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700&display=swap" rel="stylesheet">

<style>
html, body {
  margin: 0;
  padding: 0;
  height: 100%;
  font-family: 'Tajawal', 'Segoe UI', system-ui, sans-serif;

  /* الخلفية */
  background: linear-gradient(
    135deg,
    #ffffff 0%,
    #eefaf7 30%,
    #cdece5 70%,
    #a7ddd2 100%
  );

  display: flex;
  justify-content: center;
  align-items: center;
}

.container {
  width: 90%;
  max-width: 360px;
  min-height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  padding: 40px 20px;

  /* اللوحة الوسطى */
  background: linear-gradient(
    135deg,
    rgba(255,255,255,0.96) 0%,
    rgba(223,245,239,0.96) 45%,
    rgba(171,223,210,0.96) 100%
  );

  border-radius: 24px;

  backdrop-filter: blur(12px);

  border: 1px solid rgba(0,0,0,0.05);

  box-shadow: 0 18px 45px rgba(0,0,0,0.08);

  text-align: center;
}

.logo {
  width: 90px;
  height: 90px;

  border-radius: 50%;

  background: #ffffff;

  display: flex;
  justify-content: center;
  align-items: center;

  margin-bottom: 18px;

  border: 1px solid rgba(0,0,0,0.05);

  box-shadow: 0 4px 12px rgba(0,0,0,0.06);
}

.logo img {
  width: 50%;
  height: auto;
  object-fit: contain;
  display: block;
}

h1 {
  font-size: 26px;
  color: #0f3f3f;
  font-weight: 700;
  margin: 0 0 8px 0;
}

.subtitle {
  font-size: 14px;
  color: #466666;
  margin-bottom: 34px;
}

.links-container {
  display: flex;
  flex-direction: column;
  gap: 16px;
  width: 100%;
}

.link {
  display: flex;
  align-items: center;
  gap: 14px;

  padding: 18px 20px;

  border-radius: 16px;

  font-size: 16px;
  font-weight: 500;
  text-decoration: none;

  color: #154949;

  /* الأزرار */
  background: linear-gradient(
    135deg,
    rgba(255,255,255,0.98) 0%,
    rgba(214,242,234,0.98) 100%
  );

  border: 1px solid rgba(0,0,0,0.05);

  transition: all 0.3s ease;

  box-shadow: 0 4px 12px rgba(0,0,0,0.04);
}

.link:hover {
  transform: translateY(-3px);

  /* Hover */
  background: linear-gradient(
    135deg,
    rgba(255,255,255,1) 0%,
    rgba(186,232,220,1) 100%
  );

  box-shadow: 0 10px 20px rgba(0,0,0,0.08);
}

.icon-box {
  width: 44px;
  height: 44px;

  /* الأيقونات */
  background: linear-gradient(
    135deg,
    #ffffff 0%,
    #bfe7dc 100%
  );

  border-radius: 12px;

  display: flex;
  justify-content: center;
  align-items: center;

  font-size: 22px;

  border: 1px solid rgba(0,0,0,0.05);
}

.text {
  flex: 1;
  text-align: right;
}

@media (max-width: 480px) {

  .logo {
    width: 80px;
    height: 80px;
  }

  .logo img {
    width: 60%;
  }

  h1 {
    font-size: 22px;
  }

  .link {
    padding: 15px 16px;
    font-size: 14px;
  }
}
</style>
</head>

<body>

<div class="container">

  <div class="logo">
    <img src="https://i.ibb.co/qMStJd7d/logo.png" alt="جمعية البركة الخيرية">
  </div>

  <h1>جمعية البركة الخيرية</h1>

  <p class="subtitle">
    نسعد بخدمتكم
  </p>

  <div class="links-container">

    <a href="https://www.albarkah.org/profile-request/" target="_blank" class="link">
      <div class="icon-box">📝</div>
      <div class="text">طلب تسجيل مستفيد جديد</div>
    </a>

    <a href="https://drive.google.com/file/d/1-Ziyteb_n3ZjyRUOkC5SLXHTKVDJjzBM/view?usp=sharing" target="_blank" class="link">
      <div class="icon-box">📂</div>
      <div class="text">الوثائق المطلوبة</div>
    </a>

    <a href="https://drive.google.com/file/d/1_ZSpfIPCoW8fTtFj7DSJyESUs5hqRsrP/view?usp=drivesdk" target="_blank" class="link">
      <div class="icon-box">📄</div>
      <div class="text">طريقة استخراج الوثائق</div>
    </a>

  </div>

</div>

</body>
</html>
