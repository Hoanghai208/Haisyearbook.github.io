<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Thiệp mời Kỷ Yếu</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Nunito:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
    * {
        box-sizing: border-box;
    }

    body {
        margin: 0;
        min-height: 100vh;
        padding: 20px; /* SAFE MARGIN FOR MOBILE */
        display: flex;
        justify-content: center;
        align-items: center;
        background: linear-gradient(135deg, #fcefee, #e8f4ff, #fdf6e3);
        font-family: 'Nunito', sans-serif;
    }

    .card {
        width: 100%;
        max-width: 420px; /* OPTIMAL FOR MOBILE */
        background: rgba(255, 255, 255, 0.85);
        backdrop-filter: blur(6px);
        padding: 36px 28px;
        text-align: center;
        border-radius: 24px;
        box-shadow: 0 30px 40px rgba(0,0,0,0.12);
        border: 2px solid #f3d7e3;
    }

    .invite {
        font-size: 14px;
        color: #7a7a7a;
        margin-bottom: 16px;
    }

    .title {
        font-family: 'Pacifico', cursive;
        font-size: 40px;
        color: #e89ab3;
        margin: 6px 0;
    }

    .name {
        font-size: 16px;
        color: #555;
        margin-bottom: 20px;
    }

    .divider {
        width: 72px;
        height: 4px;
        background: linear-gradient(to right, #f6b1c3, #a6dcef);
        margin: 0 auto 20px;
        border-radius: 10px;
    }

    .info {
        background: #f7fbff;
        padding: 14px;
        border-radius: 16px;
        font-size: 14px;
        line-height: 1.7;
        color: #444;
    }

    .dear {
        margin-top: 22px;
        font-family: 'Pacifico', cursive;
        font-size: 18px;
        color: #9bb7d4;
    }

    .footer {
        margin-top: 12px;
        font-size: 13px;
        color: #999;
    }

    /* DESKTOP / LARGE SCREEN */
    @media (min-width: 768px) {
        body {
            padding: 40px;
        }

        .card {
            max-width: 480px;
            padding: 44px 36px;
        }

        .title {
            font-size: 48px;
        }

        .name {
            font-size: 18px;
        }

        .invite {
            font-size: 15px;
        }
    }
</style>

</head>
<body>

    <div class="card">
        <div class="invite">
            Thân mời bạn đến tham dự
        </div>

        <div class="title">KỶ YẾU</div>
        <div class="name">của Hoàng Hải</div>

        <div class="divider"></div>

        <div class="info">
            📍 Địa điểm: Trường THPT Phúc Lợi <br>
            🕒 Ngày: 18/01/2026 <br>
	    ⌚Thời gian: 10:00 - 11:30
        </div>

        <div class="dear">
            Thân gửi
        </div>

     
    </div>

</body>
</html>
