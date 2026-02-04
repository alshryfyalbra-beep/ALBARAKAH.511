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
  min-height: 100%;
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

/* ===== إطار الشعار الدائري ===== */
.logo {
  width: 110px;
  height: 110px;
  border-radius: 50%;
  background: rgba(255,255,255,0.95);
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 18px;
  border: 1px solid rgba(0,0,0,0.06);
  box-shadow: 0 3px 10px rgba(0,0,0,0.12);
}

/* ===== غلاف داخلي يمنع القص ===== */
.logo-inner {
  width: 100%;
  height: 100%;
  padding: 14px;               /* أهم سطر */
  box-sizing: border-box;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* ===== صورة الشعار ===== */
.logo-inner img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
  display: block;
}

/* ===== العناوين ===== */
h1 {
  font-size: 26px;
  color: #ffffff;
  font-weight: 700;
  margin: 0 0 8px 0;
}

.subtitle {
  font-size: 14px;
  color: rgba(255,255,255
