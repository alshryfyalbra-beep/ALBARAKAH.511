<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
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

    @keyframes fadeInScale { from {opacity:0; transform:scale(0.95);} to {opacity:1; transform:scale(1);} }
    @keyframes float { 0%,100%{transform:translateY(0px);}50%{transform:translateY(-10px);} }

    .container {
      width: 90%;
      max-width: 360px;
      height: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 40px 20px;
      background: rgba(255,255,255,0.12);
      border-radius: 24px;
      backdrop-filter: blur(15px);
      border: 1px solid rgba(255,255,255,0.2);
      box-shadow: 0 20px 60px rgba(0,0,0,0.15);
      animation: fadeInScale 0.6s ease-out;
    }

    .logo-container { margin-bottom: 30px; animation: float 3s ease-in-out infinite; }
    .logo {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      background: #ffffff; /* خلفية بيضاء للوجو */
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 10px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.15);
    }
    .logo img { width: 100%; height: 100%; object-fit: contain; border-radius: 50%; }

    h1 { margin: 15px 0 10px; font-size:28px; color:#ffffff; font-weight:700; letter-spacing:0.5px; text-align:center; }
    .subtitle { font-size:14px; color:rgba(255,255,255,0.85); margin-bottom:40px; font-weight:400; line-height:1.6; text-align:center; }

    .links-container { display:flex; flex-direction:column; gap:16px; width: 100%; }
    .link {
      text-decoration:none;
      color:#ffffff;
      background: rgba(255,255,255,0.15);
      padding:18px 20px;
      border-radius:14px;
      font-size:16px;
      font-weight:500;
      border:1px solid rgba(255,255,255,0.2);
      transition: all 0.35s cubic-bezier(0.34, 1.56, 0.64, 1);
      display:flex;
      align-items:center;
      gap:14px;
      cursor:pointer;
    }
    .link:hover {
      background: rgba(255,255,255,0.25);
      transform: translateY(-6px);
      box-shadow: 0 15px 35px rgba(0,0,0,0.2);
      border:1px solid rgba(255,255,255,0.35);
    }
    .link:active { transform: translateY(-2px); }

    .icon-box {
      width:45px;
      height:45px;
      background: rgba(255,255,255,0.25);
      border-radius:10px;
      display:flex;
      align-items:center;
      justify-content:center;
      font-size:22px;
      flex-shrink:0;
      transition: all 0.3s ease;
    }
    .link:hover .icon-box { background: rgba(255,255,255,0.4); transform: scale(1.1); }
    .text { flex:1; text-align:right; }

    @media (max-width:480px){
      .container { max-width:100%; padding:30px 20px; }
      h1 { font-size:24px; }
