html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>НАШЕТАКСИ - междугородние перевозки</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        
        body {
            background-color: #000;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }
        
        .phone-container {
            width: 360px;
            height: 700px;
            background-color: #000;
            border-radius: 40px;
            padding: 20px;
            position: relative;
            box-shadow: 0 0 20px rgba(255, 204, 0, 0.5);
            border: 4px solid #ffcc00;
            overflow: hidden;
        }
        
        .phone-screen {
            background: linear-gradient(to bottom, #ffcc00, #000);
            height: 100%;
            border-radius: 30px;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            overflow-y: auto;
        }
        
        .header {
            text-align: center;
            margin-bottom: 30px;
            width: 100%;
        }
        
        .logo {
            font-size: 28px;
            font-weight: bold;
            color: #000;
            background-color: #ffcc00;
            padding: 10px 20px;
            border-radius: 50px;
            margin-bottom: 10px;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
        }
        
        .slogan {
            font-size: 16px;
            color: #ffcc00;
            margin-top: 5px;
        }
        
        .order-btn {
            display: block;
            width: 80%;
            padding: 15px;
            background-color: #ffcc00;
            color: #000;
            text-align: center;
            font-size: 20px;
            font-weight: bold;
            text-decoration: none;
            border-radius: 50px;
            margin: 20px 0;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            transition: all 0.3s;
        }
        
        .order-btn:hover {
            background-color: #fff;
            transform: scale(1.05);
        }
        
        .pricing {
            background-color: rgba(0,0,0,0.7);
            border-radius: 15px;
            padding: 15px;
            width: 100%;
            margin: 15px 0;
        }
        
        .pricing-title {
            color: #ffcc00;
            text-align: center;
            margin-bottom: 15px;
            font-size: 18px;
        }
        
        .price-item {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
            border-bottom: 1px solid #ffcc00;
        }
        
        .price-item:last-child {
            border-bottom: none;
        }
        
        .price-name {
            color: #fff;
        }
        
        .price-value {
            color: #ffcc00;
            font-weight: bold;
        }
        
        .support {
            margin-top: 20px;
            text-align: center;
            color: #fff;
        }
        
        .support-title {
            color: #ffcc00;
            margin-bottom: 5px;
        }
        
        .support-phone {
            font-size: 20px;
            font-weight: bold;
            color: #ffcc00;
            text-decoration: none;
            display: block;
            margin: 10px 0;
        }
        
        .telegram-info {
            margin-top: 15px;
            font-size: 14px;
            color: #ccc;
            text-align: center;
        }
        
        .notification {
            position: absolute;
            top: 20px;
            width: 90%;
            background-color: rgba(255, 204, 0, 0.9);
            color: #000;
            padding: 8px;
            border-radius: 10px;text-align: center;
            font-size: 14px;
            display: none;
        }
        
        .phone-top {
            position: absolute;
            top: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 20px;
            background-color: #000;
            border-bottom-left-radius: 10px;
            border-bottom-right-radius: 10px;
            z-index: 10;
        }
        
        .phone-bottom {
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 20px;
            background-color: #000;
            border-top-left-radius: 10px;
            border-top-right-radius: 10px;
            z-index: 10;
        }
    </style>
</head>
<body>
    <div class="phone-container">
        <div class="phone-top"></div>
        <div class="phone-screen">
            <div class="header">
                <div class="logo">НАШЕТАКСИ</div>
                <div class="slogan">Межгород и поездки по территориям</div>
            </div>
            
            <a href="https://t.me/Nikita24_01" class="order-btn">ЗАКАЗАТЬ ТАКСИ</a>
            
            <div class="pricing">
                <div class="pricing-title">НАШИ ТАРИФЫ</div>
                <div class="price-item">
                    <span class="price-name">Новые территории</span>
                    <span class="price-value">от 70 руб/км</span>
                </div>
                <div class="price-item">
                    <span class="price-name">Старые территории</span>
                    <span class="price-value">20 руб/км</span>
                </div>
            </div>
            
            <div class="support">
                <div class="support-title">Поддержка клиентов:</div>
                <a href="tel:89952256830" class="support-phone">8 (995) 225-68-30</a>
                <div class="telegram-info">Для заказа такси нажмите кнопку "ЗАКАЗАТЬ ТАКСИ"</div>
            </div>
        </div>
        <div class="phone-bottom"></div>
    </div>

    <script>
        // Простая функция для показа уведомления при нажатии на кнопку
        document.querySelector('.order-btn').addEventListener('click', function(e) {
            e.preventDefault();
            window.open('https://t.me/Nikita24_01', '_blank');
        });
    </script>
</body>
</html>

Telegram (https://t.me/Nikita24_01)
Nikita# -Taksi-
