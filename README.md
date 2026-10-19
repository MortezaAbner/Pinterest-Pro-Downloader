<div align="center">

# 🎯 Pinterest Pro Downloader

**یک نرم‌افزار دسکتاپ سریع، قدرتمند و مدرن برای دانلود انبوه محتوای بوردهای پینترست (Pinterest)**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=for-the-badge&logo=windows)](https://www.microsoft.com/windows)
[![Python](https://img.shields.io/badge/Python-3.12-yellow?style=for-the-badge&logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-PolyForm%20Noncommercial-red?style=for-the-badge)](LICENSE)

</div>

---

## ✨ ویژگی‌های کلیدی

- 📥 **دانلود کامل بوردها:** پشتیبانی از دانلود تمام محتوای یک بورد (حتی بوردهای با بیش از ۲۶۰ پین).
- 🔒 **پشتیبانی از بوردهای خصوصی (Private):** با استفاده از کوکی‌های مرورگر (Chrome, Edge, Firefox) بدون نیاز به وارد کردن رمز عبور.
- 🎬 **پشتیبانی از تمامی فرمت‌ها:** دانلود خودکار عکس‌ها (JPG, PNG)، گیف‌ها (GIF) و ویدیوها (MP4) با کیفیت اصلی.
- ⚙️ **نصب خودکار FFmpeg:** برنامه به طور هوشمند تشخیص می‌دهد که آیا FFmpeg نصب است یا خیر و در صورت نیاز، آن را به صورت خودکار نصب می‌کند (برای دانلود ویدیوهای طولانی).
- 🖥️ **رابط کاربری گرافیکی (GUI):** کار با برنامه بدون نیاز به نوشتن حتی یک خط کد در ترمینال.
- 🚀 **نسخه پرتابل و نصبی:** امکان استفاده بدون نصب یا نصب آسان با ایجاد آیکون در دسکتاپ.

---

## ⚙️ پیش‌نیازها

- **سیستم‌عامل:** ویندوز ۱۰ یا ویندوز ۱۱
- **اینترنت:** اتصال پایدار به اینترنت (به دلیل مسدود بودن پینترست در برخی مناطق، استفاده از VPN الزامی است).
- **مرورگر:** (اختیاری) برای دانلود بوردهای خصوصی، باید در یکی از مرورگرهای Chrome، Edge یا Firefox لاگین باشید.

---

## 🚀 نحوه نصب و اجرا

### روش اول: نسخه نصبی (Setup)
۱. به بخش [Releases](https://github.com/YOUR_USERNAME/YOUR_REPO/releases) بروید.
۲. فایل `PinterestPro-Setup-v1.0.0.exe` را دانلود و اجرا کنید.
۳. برنامه به صورت خودکار نصب می‌شود و آیکون آن در دسکتاپ ظاهر می‌شود.

### روش دوم: نسخه پرتابل (Portable)
۱. فایل `PinterestPro-Portable-v1.0.0.zip` را دانلود کنید.
۲. آن را از حالت فشرده خارج کنید.
۳. فایل `PinterestApp.exe` را اجرا کنید (نیازی به نصب ندارد).

### روش سوم: اجرا از طریق سورس کد
اگر می‌خواهید برنامه را مستقیماً از سورس کد اجرا کنید:

۱. مخزن را کلون کنید:
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
۲. کتابخانه‌های مورد نیاز را نصب کنید:
pip install gallery-dl pyinstaller
۳. برنامه را اجرا کنید:
python PinterestApp.py
