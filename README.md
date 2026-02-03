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
    @keyframes pulse { 0%,100%{box-shadow:0 0 0 0 rgba(2,160,160,0.7);}50%{box-shadow:0 0 0 10px rgba(2,160,160,0);} }

    .container {
      width: 90%;
      max-width: 360px;
      height: 100%;           /* يملأ كامل ارتفاع الشاشة */
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center; /* يوسّط المحتوى طولياً */
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
      background: #ffffff;   /* خلفية بيضاء للوجو الشفاف */
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
      .link { padding:16px 18px; font-size:15px; }
      .logo { width:100px; height:100px; }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="logo-container">
      <div class="logo">
        <img src="https://drive.google.com/uc?export=view&id=19_3FiyicRfmQt3HSVJFLGfnTV97Us2Ot" alt="جمعية البركة الخيرية">
      </div>
    </div>
    <h1 id="org-name">جمعية البركة الخيرية</h1>
    <p class="subtitle" id="subtitle">نسعد بخدمتكم</p>
    <div class="links-container">
      <a href="https://www.albarkah.org/profile-request/" target="_blank" rel="noopener noreferrer" class="link">
        <div class="icon-box">📝</div>
        <div class="text" id="link1">طلب تسجيل مستفيد جديد</div>
      </a>
      <a href="https://drive.google.com/file/d/1CgMJ3AX6PQDpAaiRRuirkCuKBSAeJ9t-/view?usp=drive_link" target="_blank" rel="noopener noreferrer" class="link">
        <div class="icon-box">📄</div>
        <div class="text" id="link2">طريقة استخراج الوثائق</div>
      </a>
    </div>
  </div>

  <script>
    const defaultConfig = {
      organization_name: "جمعية البركة الخيرية",
      subtitle_text: "نسعد بخدمتكم",
      link1_text: "طلب تسجيل مستفيد جديد",
      link2_text: "طريقة استخراج الوثائق",
      link1_url: "https://www.albarkah.org/profile-request/",
      link2_url: "https://drive.google.com/file/d/1CgMJ3AX6PQDpAaiRRuirkCuKBSAeJ9t-/view?usp=drive_link",
      background_color: "#016b6b",
      primary_action: "#02a0a0",
      secondary_action: "#c5eded",
      text_color: "#ffffff",
      font_family: "Tajawal",
      font_size: 16
    };

    function onConfigChange(config) {
      document.getElementById('org-name').textContent = config.organization_name || defaultConfig.organization_name;
      document.getElementById('subtitle').textContent = config.subtitle_text || defaultConfig.subtitle_text;
      document.getElementById('link1').textContent = config.link1_text || defaultConfig.link1_text;
      document.getElementById('link2').textContent = config.link2_text || defaultConfig.link2_text;

      const links = document.querySelectorAll('.links-container a');
      links[0].href = config.link1_url || defaultConfig.link1_url;
      links[1].href = config.link2_url || defaultConfig.link2_url;

      document.body.style.background = `linear-gradient(135deg, ${config.background_color || defaultConfig.background_color} 0%, ${config.primary_action || defaultConfig.primary_action} 50%, ${config.secondary_action || defaultConfig.secondary_action} 100%)`;
      document.querySelectorAll('h1, .subtitle, .link').forEach(el => el.style.color = config.text_color || defaultConfig.text_color);
      document.body.style.fontFamily = `${config.font_family || defaultConfig.font_family}, 'Segoe UI', system-ui, sans-serif`;
    }
  </script>
</body>
</html>

