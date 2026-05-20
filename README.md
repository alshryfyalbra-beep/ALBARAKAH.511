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
  background: linear-gradient(135deg, #ffffff 0%, #f7f7f7 50%, #ececec 100%);
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
  background: rgba(255,255,255,0.88);
  border-radius: 24px;
  backdrop-filter: blur(14px);
  border: 1px solid rgba(0,0,0,0.05);
  box-shadow: 0 15px 40px rgba(0,0,0,0.08);
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
  border: 1px solid rgba(0,0,0,0.06);
  box-shadow: 0 3px 10px rgba(0,0,0,0.08);
}

.logo img {
  width: 50%;
  height: auto;
  object-fit: contain;
  display: block;
}

h1 {
  font-size: 26px;
  color: #1a1a1a;
  font-weight: 700;
  margin: 0 0 8px 0;
}

.subtitle {
  font-size: 14px;
  color: #666666;
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
  color: #1b1b1b;
  background: rgba(255,255,255,0.85);
  border: 1px solid rgba(0,0,0,0.06);
  transition: all 0.3s ease;
  box-shadow: 0 4px 12px rgba(0,0,0,0.04);
}

.link:hover {
  background: #ffffff;
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.08);
}

.icon-box {
  width: 44px;
  height: 44px;
  background: linear-gradient(135deg, #ffffff 0%, #f0f0f0 100%);
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
  <p class="subtitle">نسعد بخدمتكم</p>

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
