<div align="center" dir="rtl">

# 🎯 Pinterest Pro Downloader

**یک نرم‌افزار دسکتاپ سریع، قدرتمند و مدرن برای دانلود انبوه محتوای بوردهای پینترست (Pinterest)**

<div dir="ltr">

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=for-the-badge&logo=windows)](https://www.microsoft.com/windows)
[![Python](https://img.shields.io/badge/Python-3.12-yellow?style=for-the-badge&logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-PolyForm%20Noncommercial-red?style=for-the-badge)](LICENSE)

</div>

**🇮🇷 فارسی | [🇬🇧 English](README.en.md)**

</div>

---

<div dir="rtl">

## ✨ ویژگی‌های کلیدی

- 📥 **دانلود کامل بوردها:** پشتیبانی از دانلود تمام محتوای یک بورد (حتی بوردهای با بیش از ۲۶۰ پین).
- 🔒 **پشتیبانی از بوردهای خصوصی (Private):** با استفاده از کوکی‌های مرورگر (Chrome, Edge, Firefox) بدون نیاز به وارد کردن رمز عبور.
- 🎬 **پشتیبانی از تمامی فرمت‌ها:** دانلود خودکار عکس‌ها (JPG, PNG)، گیف‌ها (GIF) و ویدیوها (MP4) با کیفیت اصلی.
- ⚙️ **نصب خودکار FFmpeg:** برنامه به طور هوشمند تشخیص می‌دهد که آیا FFmpeg نصب است یا خیر و در صورت نیاز، آن را به صورت خودکار نصب می‌کند.
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
1. به بخش [Releases](https://github.com/MortezaAbner/Pinterest-Pro-Downloader) بروید.
2. فایل `PinterestPro-Setup-v1.0.0.exe` را دانلود و اجرا کنید.
3. برنامه به صورت خودکار نصب می‌شود و آیکون آن در دسکتاپ ظاهر می‌شود.

### روش دوم: نسخه پرتابل (Portable)
1. فایل `PinterestPro-Portable-v1.0.0.zip` را دانلود کنید.
2. آن را از حالت فشرده خارج کنید.
3. فایل `PinterestApp.exe` را اجرا کنید (نیازی به نصب ندارد).

### روش سوم: اجرا از طریق سورس کد
اگر می‌خواهید برنامه را مستقیماً از سورس کد اجرا کنید، دستورات زیر را به ترتیب در ترمینال (CMD) کپی و اجرا کنید:

```bash
# ۱. کلون کردن مخزن و ورود به پوشه
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

# ۲. نصب پیش‌نیازها
pip install gallery-dl pyinstaller

# ۳. اجرای برنامه
python PinterestApp.py
