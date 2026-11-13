# شبیه‌ساز زندگی (Bale Bot)

ربات شبیه‌ساز زندگی برای پیام‌رسان بله.

## اجرا

```bash
pip install -r requirements.txt
export BALE_TOKEN="your_token"
export DATABASE_URL="postgresql://..."
# اختیاری:
# export RESERVE_TOKENS="token1,token2"
python app.py
```

## Deep linkها

- `/start game` — منوی بازی
- `/start shop_black` — بازار سیاه
- `/start rank` — لیدربورد
- `/start mainer` — ماینر
- `/start factory` — کارخانه
- `/start buying_coins` — خرید سکه
- `/start account` — حساب
- `/start coins_game` — کازینو
- `/start houses` — املاک
- `/start shop` — فروشگاه
- `/start items` — آیتم‌ها
- `/start bank` — بانک
- `/start channel` یا `/channel` — کانال و گروه
- `/start ref` — دعوت
- `/start inventory` — اینونتوری
- `/start anonymous_message` — پیام ناشناس
- `/start setting` — تنظیمات

## نکته

فایل `app.py` را از همین چت دانلود کنید و در ریشهٔ ریپو آپلود کنید (Upload file در گیت‌هاب).
