<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>هک شدن سیستم</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            background-color: black;
            color: lime;
            text-align: center;
            padding: 50px;
        }
        #console {
            white-space: pre-wrap;
            font-size: 18px;
            line-height: 1.6;
            margin-top: 20px;
        }
        .typing {
            display: inline-block;
            width: 0;
            overflow: hidden;
            border-right: 2px solid lime;
            animation: typing 4s steps(40) 1s forwards, blink 0.75s step-end infinite;
        }
        @keyframes typing {
            from {
                width: 0;
            }
            to {
                width: 100%;
            }
        }
        @keyframes blink {
            50% {
                border-color: transparent;
            }
        }
    </style>
</head>
<body>
    <h1>هک شدن سیستم</h1>
    <div id="console">
        <div class="typing">در حال اتصال به سیستم...</div>
        <div class="typing">اتصال برقرار شد...</div>
        <div class="typing">سیستم شما توسط تیم ناشناس هک شده!</div>
        <div class="typing">آی‌پی شما: 192.168.1.1</div>
        <div class="typing">لوکیشن: بابل، مازندران</div>
        <div class="typing">نام کاربری: امیر محمد</div>
        <div class="typing">هشدار! در صورت عدم پاسخگویی، اطلاعات شما در خطر است.</div>
    </div>
</body>
</html>
