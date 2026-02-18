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
  background: linear-gradient(135deg, #016b6b 0%, #02a0a0 50%, #c5eded 100%);
  display: flex;
  justify-content: center;
  align-items: center;
}
.container {
  width: 90%;
  max-width: 360px;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 40px 20px;
  background: rgba(255,255,255,0.12);
  border-radius: 24px;
  backdrop-filter: blur(15px);
  border: 1px solid rgba(255,255,255,0.2);
  box-shadow: 0 20px 60px rgba(0,0,0,0.15);
  text-align: center;
}

.logo {
  width: 120px;
  margin-bottom: 18px;
}

.logo img {
  width: 100%;
  height: auto;
  display: block;
}

/* الجوال */
@media (max-width: 480px) {
  .logo { width: 95px; }     /* فقط تصغير بسيط */
  h1 { font-size: 22px; }
  .link { padding: 15px 16px; font-size: 14px; }
}

</style>
</head>

<body>

<div class="container">

  <div class="logo">
    <img src="https://i.ibb.co/CKqrJ7Qr/cover.png" alt="جمعية البركة الخيرية">
  </div>

  <h1>جمعية البركة الخيرية</h1>
  <p class="subtitle">نسعد بخدمتكم</p>

  <div class="links-container">
    <a href="https://www.albarkah.org/profile-request/" target="_blank" class="link">
      <div class="icon-box">📝</div>
      <div class="text">طلب تسجيل مستفيد جديد</div>
    </a>

    <a href="https://drive.google.com/file/d/1CgMJ3AX6PQDpAaiRRuirkCuKBSAeJ9t-/view" target="_blank" class="link">
      <div class="icon-box">📄</div>
      <div class="text">طريقة استخراج الوثائق</div>
    </a>
  </div>

</div>

</body>
</html>
