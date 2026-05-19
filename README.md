<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ابر‌اکوسیستم کلان IMAX - پلتفرم مستقل تحلیل ساختاری</title>
    <style>
        :root {
            --bg-color: #0c0f12;
            --container-bg: #13171c;
            --accent-green: #00ff66;
            --accent-blue: #00e5ff;
            --text-main: #f4f6f8;
            --text-muted: #94a3b8;
            --border-color: #222c35;
        }

        * { box-sizing: border-box; margin: 0; padding: 0; }

        body {
            font-family: 'Tahoma', 'Arial', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.8;
            padding: 40px 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background-color: var(--container-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 40px;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.5);
        }

        header {
            text-align: center;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 30px;
            margin-bottom: 40px;
        }

        h1 { font-size: 24px; color: var(--text-main); margin-bottom: 15px; }
        h1 span { color: var(--accent-blue); }
        .subtitle { font-size: 14px; color: var(--text-muted); max-width: 700px; margin: 0 auto; text-align: justify; }
        h2 { font-size: 18px; color: var(--accent-blue); margin: 35px 0 20px 0; padding-bottom: 5px; border-bottom: 1px solid var(--border-color); }
        .card { background-color: rgba(255, 255, 255, 0.02); border: 1px solid var(--border-color); border-radius: 8px; padding: 20px; margin-bottom: 20px; }
        .card h3 { font-size: 15px; color: var(--accent-green); margin-bottom: 10px; }
        .card p { font-size: 13.5px; color: var(--text-muted); text-align: justify; }

        .security-notice {
            background-color: rgba(239, 68, 68, 0.05);
            border: 1px solid rgba(239, 68, 68, 0.2);
            border-radius: 8px;
            padding: 20px;
            margin: 40px 0;
        }
        .security-notice h4 { color: #ef4444; font-size: 14px; margin-bottom: 8px; }

        .contact-section { background-color: rgba(0, 229, 255, 0.02); border: 1px solid rgba(0, 229, 255, 0.1); border-radius: 8px; padding: 25px; margin-top: 40px; }
        .contact-section h3 { font-size: 16px; color: var(--text-main); margin-bottom: 15px; }
        .contact-info { list-style: none; }
        .contact-info li { font-size: 14px; margin-bottom: 12px; color: var(--text-muted); }
        .contact-info strong { color: var(--text-main); display: inline-block; width: 220px; }
        .contact-info span.value { color: var(--accent-blue); font-family: 'Courier New', monospace; direction: ltr; display: inline-block; }

        footer { text-align: center; margin-top: 50px; font-size: 11px; color: #475569; }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>ابر‌اکوسیستم کلان <span>IMAX</span></h1>
            <p class="subtitle">پلتفرم مستقل تحلیل ساختاری، اورهال زیرساخت‌های صنعتی و پدافند غیرعامل شبکه. مهندسی خودکفا (Air-Gapped) جهت عارضه‌‌یابی صنایع سنگین، کالبدشکافی خطاهای صنعتی و پیش‌بینی ریسک بدون نیاز به اتصال به اینترنت بیرونی.</p>
        </header>

        <h2>لایه‌های عملیاتی هسته (Core Modules)</h2>
        
        <div class="card">
            <h3>۱. بازوی تحلیلی و تحول زیرساخت (GroundMaster)</h3>
            <p>پلتفرم اختصاصی مانیتورینگ رفتار اتوماسیون‌های صنعتی کلان (مانند تجهیزات زیمنس و سیستم‌های اسکادا). این لایه توانایی تفکیک اتمیک خطاها را در سه لایه (سیستمی، انسانی و ترکیبی) داراست تا از توقف‌های ناخواسته خطوط تولید (Shutdown) و خسارت‌های میلیاردی پیش‌بینی و جلوگیری کند.</p>
        </div>

        <div class="card">
            <h3>۲. دژ نفوذناپذیر ارتباطات (Zeus Layer 7)</h3>
            <p>مدیریت و صیانت از ترافیک پورت‌های شبکه از طریق باینری مقتدر imaxctl. ایجاد تونل‌های سخت‌افزاری کاملاً رمزنگاری‌شده (TUNNEL_L2_AES-256)، بارگذاری لایو باندهای اولویت و قرنطینه آنی پورت‌ها در لایه ۷ جهت خنثی‌سازی حملات اختلالی زیرساخت.</p>
        </div>

        <div class="card">
            <h3>۳. پایداری و استقلال ساختاری (Sovereign Ecosystem)</h3>
            <p>سیستمی بی‌پایان و خودکفا با پردازش اتمیک لیتنسی ۲۶ میکروثانیه‌ای (گره FRA-01). این پلتفرم دارای ساختار گردش نقدینگی دوگانه (پشتوانه رسمی نهادی به همراه درگاه‌های لایو غیرمتمرکز) است که تداوم عملیاتی سیستم را تحت هرگونه شرایط بحرانی تضمین می‌کند.</p>
        </div>

        <div class="security-notice">
            <h4>⚠️ پروتکل واگذاری لایسنس و دسترسی</h4>
            <p>با توجه به معماری بسته و سطح امنیتی زیرساخت IMAX، ارائه‌ی هرگونه دمو، بررسی تلمتری لایو یا انتقال لایسنس کارفرمایی، منوط به احراز هویت مراجع، تایید پورت‌های مبدا و امضای بالاترین سطح توافق‌نامه رسمی عدم افشای حقوقی (Strict NDA) از سوی دفتر مدیریت سیستم است.</p>
        </div>

        <div class="contact-section">
            <h3>درخواست جلسه‌ی فنی و بررسی ساختاری</h3>
            <p style="font-size: 13px; color: var(--text-muted); margin-bottom: 20px;">کارفرمایان محترم، مدیران پدافند غیرعامل و هلدینگ‌های صنعتی زیرساختی می‌توانند جهت هماهنگی جلسات استراتژیک، ارسال پروپوزال و تبادل اسناد NDA، مستقیماً با مراجع رسمی اکوسیستم در ارتباط باشند.</p>
            
            <ul class="contact-info">
                <li><strong>خط ارتباط مستقیم معمار ارشد (مکس):</strong> <span class="value">09121022208</span></li>
                <li><strong>تلفن تماس خط خدمات سیستم:</strong> <span class="value">09913799573</span></li>
                <li><strong>پست الکترونیک معمار ارشد:</strong> <span class="value">Max.monabbati@gmail.com</span></li>
                <li><strong>دفتر مدیریت و نظارت بیرونی:</strong> <span class="value" style="direction: rtl; font-family: inherit;">آیلار اردبیلی</span></li>
            </ul>
        </div>

        <footer>
            IMAX SOVEREIGN INFRASTRUCTURE • ALL RIGHTS RESERVED 2026
        </footer>
    </div>

</body>
</html>
