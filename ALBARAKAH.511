
<!doctype html>
<html lang="ar" dir="rtl">
 <head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>جمعية البركة الخيرية</title>
  <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700&amp;display=swap" rel="stylesheet">
  <script src="/_sdk/element_sdk.js"></script>
  <style>
    body {
      box-sizing: border-box;
    }

    html, body {
      height: 100%;
      margin: 0;
      padding: 0;
      font-family: 'Tajawal', 'Segoe UI', system-ui, sans-serif;
      background: linear-gradient(135deg, #016b6b 0%, #02a0a0 50%, #c5eded 100%);
      display: flex;
      align-items: center;
      justify-content: center;
      overflow-x: hidden;
      overflow-y: auto;
    }

    @keyframes fadeInScale {
      from {
        opacity: 0;
        transform: scale(0.95);
      }
      to {
        opacity: 1;
        transform: scale(1);
      }
    }

    @keyframes float {
      0%, 100% {
        transform: translateY(0px);
      }
      50% {
        transform: translateY(-10px);
      }
    }

    @keyframes pulse {
      0%, 100% {
        box-shadow: 0 0 0 0 rgba(2, 160, 160, 0.7);
      }
      50% {
        box-shadow: 0 0 0 10px rgba(2, 160, 160, 0);
      }
    }

    .container {
      width: 100%;
      max-width: 420px;
      padding: 40px 24px;
      text-align: center;
      background: rgba(255, 255, 255, 0.12);
      border-radius: 24px;
      backdrop-filter: blur(15px);
      border: 1px solid rgba(255, 255, 255, 0.2);
      animation: fadeInScale 0.6s ease-out;
      box-shadow: 0 20px 60px rgba(0, 0, 0, 0.15);
      margin: 20px;
    }

    .logo-container {
      margin-bottom: 20px;
      animation: float 3s ease-in-out infinite;
    }

    .logo {
      width: 70px;
      height: 70px;
      margin: 0 auto;
      font-size: 40px;
      display: flex;
      align-items: center;
      justify-content: center;
      background: rgba(255, 255, 255, 0.2);
      border-radius: 50%;
      animation: pulse 2s infinite;
    }

    h1 {
      margin: 15px 0 10px 0;
      font-size: 28px;
      color: #ffffff;
      font-weight: 700;
      letter-spacing: 0.5px;
    }

    .subtitle {
      font-size: 14px;
      color: rgba(255, 255, 255, 0.85);
      margin-bottom: 30px;
      font-weight: 400;
      line-height: 1.6;
    }

    .links-container {
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .link {
      text-decoration: none;
      color: #ffffff;
      background: rgba(255, 255, 255, 0.15);
      padding: 16px 20px;
      border-radius: 14px;
      font-size: 15px;
      font-weight: 500;
      border: 1px solid rgba(255, 255, 255, 0.2);
      transition: all 0.35s cubic-bezier(0.34, 1.56, 0.64, 1);
      display: flex;
      align-items: center;
      gap: 14px;
      cursor: pointer;
    }

    .link:hover {
      background: rgba(255, 255, 255, 0.25);
      transform: translateY(-6px);
      box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
      border: 1px solid rgba(255, 255, 255, 0.35);
    }

    .link:active {
      transform: translateY(-2px);
    }

    .icon-box {
      width: 40px;
      height: 40px;
      background: rgba(255, 255, 255, 0.25);
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 20px;
      flex-shrink: 0;
      transition: all 0.3s ease;
    }

    .link:hover .icon-box {
      background: rgba(255, 255, 255, 0.4);
      transform: scale(1.1);
    }

    .text {
      flex: 1;
      text-align: right;
    }

    .footer {
      margin-top: 30px;
      padding-top: 20px;
      border-top: 1px solid rgba(255, 255, 255, 0.15);
      font-size: 12px;
      color: rgba(255, 255, 255, 0.7);
    }

    @media (max-width: 480px) {
      .container {
        max-width: 100%;
        margin: 16px;
        padding: 30px 20px;
      }

      h1 {
        font-size: 24px;
      }

      .link {
        padding: 14px 18px;
      }
    }
  </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
  <script src="https://cdn.tailwindcss.com" type="text/javascript"></script>
 </head>
 <body>
  <div class="container">
   <div class="logo-container">
    <div class="logo">
     🌙
    </div>
   </div>
   <h1 id="org-name">جمعية البركة الخيرية</h1>
   <p class="subtitle" id="subtitle">نسعد بخدمتكم</p>
   <div class="links-container"><a href="https://www.albarkah.org/profile-request/" target="_blank" rel="noopener noreferrer" class="link">
     <div class="icon-box">
      📝
     </div>
     <div class="text" id="link1">
      طلب تسجيل مستفيد جديد
     </div></a> <a href="https://example.com/documents" target="_blank" rel="noopener noreferrer" class="link">
     <div class="icon-box">
      📄
     </div>
     <div class="text" id="link2">
      طريقة استخراج الوثائق
     </div></a>
   </div>
  </div>
  <script>
    const defaultConfig = {
      organization_name: "جمعية البركة الخيرية",
      subtitle_text: "نسعد بخدمتكم",
      link1_text: "طلب تسجيل مستفيد جديد",
      link2_text: "طريقة استخراج الوثائق",
      background_color: "#016b6b",
      surface_color: "#ffffff",
      text_color: "#ffffff",
      primary_action: "#02a0a0",
      secondary_action: "#c5eded",
      font_family: "Tajawal",
      font_size: 16
    };

    async function onConfigChange(config) {
      const orgName = config.organization_name || defaultConfig.organization_name;
      const subtitle = config.subtitle_text || defaultConfig.subtitle_text;
      const link1 = config.link1_text || defaultConfig.link1_text;
      const link2 = config.link2_text || defaultConfig.link2_text;
      
      const bgColor = config.background_color || defaultConfig.background_color;
      const surfaceColor = config.surface_color || defaultConfig.surface_color;
      const textColor = config.text_color || defaultConfig.text_color;
      const primaryAction = config.primary_action || defaultConfig.primary_action;
      const secondaryAction = config.secondary_action || defaultConfig.secondary_action;
      
      const fontFamily = config.font_family || defaultConfig.font_family;
      const fontSize = config.font_size || defaultConfig.font_size;
      
      document.getElementById('org-name').textContent = orgName;
      document.getElementById('subtitle').textContent = subtitle;
      document.getElementById('link1').textContent = link1;
      document.getElementById('link2').textContent = link2;
      
      document.body.style.background = `linear-gradient(135deg, ${bgColor} 0%, ${primaryAction} 50%, ${secondaryAction} 100%)`;
      
      document.querySelectorAll('h1, .subtitle, .link, .footer').forEach(el => {
        el.style.color = textColor;
      });
      
      document.body.style.fontFamily = `${fontFamily}, 'Segoe UI', system-ui, sans-serif`;
      document.querySelector('h1').style.fontSize = `${fontSize * 1.75}px`;
      document.querySelector('.subtitle').style.fontSize = `${fontSize * 0.875}px`;
      document.querySelectorAll('.link').forEach(link => {
        link.style.fontSize = `${fontSize * 0.9375}px`;
      });
      document.querySelector('.footer').style.fontSize = `${fontSize * 0.75}px`;
    }

    function mapToCapabilities(config) {
      return {
        recolorables: [
          {
            get: () => config.background_color || defaultConfig.background_color,
            set: (value) => {
              if (window.elementSdk) {
                window.elementSdk.setConfig({ background_color: value });
              }
            }
          },
          {
            get: () => config.surface_color || defaultConfig.surface_color,
            set: (value) => {
              if (window.elementSdk) {
                window.elementSdk.setConfig({ surface_color: value });
              }
            }
          },
          {
            get: () => config.text_color || defaultConfig.text_color,
            set: (value) => {
              if (window.elementSdk) {
                window.elementSdk.setConfig({ text_color: value });
              }
            }
          },
          {
            get: () => config.primary_action || defaultConfig.primary_action,
            set: (value) => {
              if (window.elementSdk) {
                window.elementSdk.setConfig({ primary_action: value });
              }
            }
          },
          {
            get: () => config.secondary_action || defaultConfig.secondary_action,
            set: (value) => {
              if (window.elementSdk) {
                window.elementSdk.setConfig({ secondary_action: value });
              }
            }
          }
        ],
        borderables: [],
        fontEditable: {
          get: () => config.font_family || defaultConfig.font_family,
          set: (value) => {
            if (window.elementSdk) {
              window.elementSdk.setConfig({ font_family: value });
            }
          }
        },
        fontSizeable: {
          get: () => config.font_size || defaultConfig.font_size,
          set: (value) => {
            if (window.elementSdk) {
              window.elementSdk.setConfig({ font_size: value });
            }
          }
        }
      };
    }

    function mapToEditPanelValues(config) {
      return new Map([
        ["organization_name", config.organization_name || defaultConfig.organization_name],
        ["subtitle_text", config.subtitle_text || defaultConfig.subtitle_text],
        ["link1_text", config.link1_text || defaultConfig.link1_text],
        ["link2_text", config.link2_text || defaultConfig.link2_text]
      ]);
    }

    if (window.elementSdk) {
      window.elementSdk.init({
        defaultConfig,
        onConfigChange,
        mapToCapabilities,
        mapToEditPanelValues
      });
    }
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9c802f8623396846',t:'MTc3MDEwMzQzNS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
