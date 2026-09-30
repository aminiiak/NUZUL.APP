# محاسبه چک - PWA برای iPhone

این پروژه نسخه PWA برنامه محاسبه چک است و بدون نیاز به App Store از طریق GitHub Pages روی آیفون قابل نصب است.

## انتشار روی GitHub Pages
1. در GitHub یک Repository جدید بسازید (مثلاً `check-calculator`).
2. همه فایل‌های این پوشه را در ریشه Repository آپلود کنید.
3. به `Settings > Pages` بروید.
4. در بخش `Build and deployment` گزینه `Deploy from a branch` را انتخاب کنید.
5. Branch را `main` و Folder را `/ (root)` انتخاب و Save کنید.
6. بعد از فعال شدن Pages، لینک سایت را در Safari آیفون باز کنید.
7. دکمه Share را بزنید و `Add to Home Screen` را انتخاب کنید.

## فایل‌ها
- `index.html`: برنامه اصلی
- `manifest.webmanifest`: تنظیمات PWA
- `sw.js`: کش آفلاین
- `icon-180.png`، `icon-192.png` و `icon-512.png`: آیکن‌های آیفون/PWA
