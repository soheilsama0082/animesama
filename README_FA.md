# Fire Charge Boost — Fabric 1.16.5

این پروژه یک مود Fabric برای Minecraft 1.16.5 است.

## قابلیت‌ها
- با راست‌کلیک روی Fire Charge، بازیکن به سمت بالا پرتاب می‌شود.
- در Survival یک Fire Charge مصرف می‌شود؛ در Creative مصرف نمی‌شود.
- قدرت پرتاب در `FireChargeBoost.java` با مقدار `1.5D` تنظیم شده است.

## ساخت خودکار
تمام فایل‌ها را در شاخه `main` مخزن GitHub آپلود کن. از بخش **Actions** اجرای `Build Fabric Mod` را باز کن. پس از موفقیت، فایل JAR در بخش **Artifacts** همان اجرا قابل دریافت است.

## ساخت دستی
با JDK 8 و Gradle 7.3.3:
```bash
gradle --no-daemon clean build
```
خروجی: `build/libs/fire-charge-boost-1.0.0.jar`

## نصب
Fabric Loader مخصوص Minecraft 1.16.5 و Fabric API سازگار را نصب کن و JAR را در پوشه `mods` قرار بده.

> این پروژه مود Fabric است، نه پلاگین Paper/Spigot. هنوز کامپایل واقعی و تست داخل بازی انجام نشده است.
