# 🌸 لندینگ پیج زعفران پلاس

یک لندینگ پیج کامل و حرفه‌ای با HTML، CSS و JavaScript خام برای نرم‌افزار مدیریت پخش گل زعفران.

## 📂 ساختار پروژه

```
docs/
├── index.html          # صفحه اصلی
├── style.css           # استایل‌های CSS
├── images/             # تصاویر نمودارها
│   ├── chart1.png
│   ├── chart2.png
│   ├── chart3.png
│   ├── chart4.png
│   └── chart5.png
└── README.md           # راهنمای استفاده
```

## 🚀 نحوه استفاده

### انتشار در GitHub Pages

1. این ریپو رو به GitHub خودت push کن
2. برو به **Settings** > **Pages**
3. در قسمت **Source**:
   - Branch: `main`
   - Folder: `/docs`
4. روی **Save** کلیک کن
5. چند دقیقه صبر کن تا سایت منتشر بشه

لینک سایت شما در این آدرس خواهد بود:
```
https://username.github.io/repository-name/
```

### مشاهده محلی

فایل `docs/index.html` رو مستقیماً در مرورگر باز کنید.

## ⚙️ تنظیمات

### اتصال فرم به API

در فایل `docs/index.html` خط ۲۱۶ رو پیدا کنید:

```javascript
// const response = await fetch('YOUR_SCRIPT_URL', {
//   method: 'POST',
//   body: JSON.stringify({ phone: phone }),
//   headers: { 'Content-Type': 'application/json' }
// });
```

کامنت رو باز کنید و `YOUR_SCRIPT_URL` رو با آدرس API خودتان جایگزین کنید.

## ✨ ویژگی‌ها

- ✅ کاملاً RTL و فارسی
- ✅ طراحی ریسپانسیو (موبایل، تبلت، دسکتاپ)
- ✅ فرم ثبت شماره موبایل با اعتبارسنجی
- ✅ انیمیشن‌های روان
- ✅ بدون وابستگی به کتابخانه خارجی
- ✅ آماده برای GitHub Pages
- ✅ نمودارهای اختصاصی بدون متن

## 🎨 سفارشی‌سازی

### تغییر رنگ‌ها

رنگ‌های اصلی در فایل `docs/style.css` تعریف شده‌اند:

```css
/* رنگ اصلی (نارنجی/طلایی) */
background: linear-gradient(135deg, #d97706, #ea580c);

/* رنگ متن */
color: #1f1510;

/* رنگ متن ثانویه */
color: #5e524c;
```

### تغییر متون

تمام متون فارسی در فایل `docs/index.html` قابل ویرایش هستند.

## 📱 پشتیبانی از مرورگرها

- Chrome/Edge (آخرین نسخه)
- Firefox (آخرین نسخه)
- Safari (آخرین نسخه)
- موبایل (iOS Safari, Chrome Mobile)

## 📄 مجوز

این پروژه برای استفاده شخصی و تجاری آزاد است.
