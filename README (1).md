# Upsher
{
    "short_name": "Upsher",
    "name": "Upsher - استأجر المنتجات",
    "icons": [
        {
            "src": "icon-192x192.png",
            "type": "image/png",
            "sizes": "192x192"
        },
        {
            "src": "icon-512x512.png",
            "type": "image/png",
            "sizes": "512x512"
        }
    ],
    "start_url": "/index.html",
    "display": "standalone",
    "background_color": "#ffffff",
    "theme_color": "#2e7d32"
}
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="theme-color" content="#2e7d32">
    <title>Upsher - لوحة التحكم</title>
    <link rel="manifest" href="/manifest.json">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Upsher</h1>
        <p>لوحة التحكم للإدارة</p>
    </header>

    <!-- الشريط الجانبي -->
    <div class="sidebar">
        <div>
            <a href="#dashboard">لوحة التحكم</a>
            <a href="#products">إدارة المنتجات</a>
            <a href="#orders">إدارة الطلبات</a>
            <a href="#vendors">المتاجر</a>
            <a href="#users">المستخدمين</a>
            <a href="#payments">طرق الدفع</a>
            <a href="#support">خدمة العملاء</a>
        </div>
        <div>
            <a href="#logout">تسجيل الخروج</a>
        </div>
    </div>

    <!-- المحتوى الرئيسي -->
    <div class="content">
        <!-- نظرة عامة -->
        <div class="dashboard-section" id="dashboard">
            <h2>نظرة عامة</h2>
            <p>مرحبًا، يمكنك إدارة التطبيق من هنا.</p>
            <div style="display: flex; gap: 1rem;">
                <div style="background-color: #e3f2fd; padding: 1rem; border-radius: 8px; flex: 1;">
                    <h3>عدد المنتجات</h3>
                    <p>120 منتج</p>
                </div>
                <div style="background-color: #e3f2fd; padding: 1rem; border-radius: 8px; flex: 1;">
                    <h3>عدد الطلبات</h3>
                    <p>45 طلب</p>
                </div>
                <div style="background-color: #e3f2fd; padding: 1rem; border-radius: 8px; flex: 1;">
                    <h3>عدد المتاجر</h3>
                    <p>15 متجر</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2023 Upsher. جميع الحقوق محفوظة.</p>
    </footer>

    <script src="app.js"></script>
</body>
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="theme-color" content="#2e7d32">
    <title>Upsher - لوحة التحكم</title>
    <link rel="manifest" href="/manifest.json">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Upsher</h1>
        <p>لوحة التحكم للإدارة</p>
    </header>

    <!-- الشريط الجانبي -->
    <div class="sidebar">
        <div>
            <a href="#dashboard">لوحة التحكم</a>
            <a href="#products">إدارة المنتجات</a>
            <a href="#orders">إدارة الطلبات</a>
            <a href="#vendors">المتاجر</a>
            <a href="#users">المستخدمين</a>
            <a href="#payments">طرق الدفع</a>
            <a href="#support">خدمة العملاء</a>
        </div>
        <div>
            <a href="#logout">تسجيل الخروج</a>
        </div>
    </div>

    <!-- المحتوى الرئيسي -->
    <div class="content">
        <!-- نظرة عامة -->
        <div class="dashboard-section" id="dashboard">
            <h2>نظرة عامة</h2>
            <p>مرحبًا، يمكنك إدارة التطبيق من هنا.</p>
            <div style="display: flex; gap: 1rem;">
                <div style="background-color: #e3f2fd; padding: 1rem; border-radius: 8px; flex: 1;">
                    <h3>عدد المنتجات</h3>
                    <p>120 منتج</p>
                </div>
                <div style="background-color: #e3f2fd; padding: 1rem; border-radius: 8px; flex: 1;">
                    <h3>عدد الطلبات</h3>
                    <p>45 طلب</p>
                </div>
                <div style="background-color: #e3f2fd; padding: 1rem; border-radius: 8px; flex: 1;">
                    <h3>عدد المتاجر</h3>
                    <p>15 متجر</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2023 Upsher. جميع الحقوق محفوظة.</p>
    </footer>

    <script src="app.js"></script>
</body>
</html>
</html>
