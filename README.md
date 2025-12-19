<!DOCTYPE html>
<html lang="ur">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ملک کی پہلی ویب سائٹ</title>
    <style>
        /* CSS: ڈیزائننگ */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
        }
        .container {
            background: white;
            padding: 30px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            width: 80%;
            max-width: 400px;
        }
        h1 { color: #2c3e50; }
        p { color: #7f8c8d; font-size: 18px; }
        .btn {
            background-color: #3498db;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 25px;
            font-size: 16px;
            cursor: pointer;
            transition: 0.3s;
        }
        .btn:hover { background-color: #2980b9; }
        #status {
            margin-top: 20px;
            font-weight: bold;
            color: #27ae60;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>خوش آمدید، ملک صاحب!</h1>
        <p id="message">یہ آپ کی بنائی ہوئی پہلی پروفیشنل ویب سائٹ ہے جو موبائل پر چل رہی ہے۔</p>
        
        <button class="btn" onclick="badlo()">جادو دیکھیں</button>
        
        <div id="status"></div>
    </div>

    <script>
        /* JavaScript: فنکشنلٹی */
        function badlo() {
            // میسج تبدیل کرنا
            document.getElementById("message").innerHTML = "واہ! آپ نے جاوا اسکرپٹ کے ذریعے ویب سائٹ کا متن بدل دیا!";
            
            // بیک گراؤنڈ رنگ تبدیل کرنا
            document.body.style.backgroundColor = "#dff9fb";
            
            // اسٹیٹس دکھانا
            document.getElementById("status").innerHTML = "سیکھنے کا سفر جاری ہے... 🚀";
            
            // الرٹ میسج
            alert("Malik: Coding is Life! 😁");
        }
    </script>

</body>
</html>
