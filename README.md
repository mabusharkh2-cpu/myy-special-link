# myy-special-link
أمن و فعال 
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحة الرابط الخاص بي</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f2f5;
            margin: 0;
        }
        .card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            text-align: center;
            max-width: 400px;
        }
        .my-link {
            display: inline-block;
            padding: 12px 25px;
            background-color: #25d366; /* لون أخضر مثل واتساب */
            color: white;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
            transition: transform 0.2s;
        }
        .my-link:hover {
            transform: scale(1.05);
            background-color: #128c7e;
        }
    </style>
</head>
<body>

    <div class="card">
        <h2>أهلاً بك في صفحتي</h2>
        <p>اضغط على الزر أدناه للانتقال إلى الرابط المخصص:</p>
        
        <a href="https://www.google.com" id="targetLink" class="my-link">اضغط هنا للدخول</a>
    </div>

</body>
</html>
