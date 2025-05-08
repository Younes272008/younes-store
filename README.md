<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اتصل بنا</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>اتصل بنا</h1>
        <nav>
            <ul>
                <li><a href="index.html">الصفحة الرئيسية</a></li>
                <li><a href="about.html">عنّا</a></li>
                <li><a href="contact.html">اتصل بنا</a></li>
            </ul>
        </nav>
    </header>

    <section>
        <h2>نموذج الاتصال</h2>
        <form action="#" method="POST">
            <label for="name">الاسم الكامل</label>
            <input type="text" id="name" name="name" required>

            <label for="email">البريد الإلكتروني</label>
            <input type="email" id="email" name="email" required>

            <label for="message">الرسالة</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">إرسال</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2025 متجرك الإلكتروني</p>
    </footer>
</body>
</html>
