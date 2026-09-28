# 🚀 Quick Start Guide

## برای iPhone/iPad (بدون کدنویسی)

### ۱. دانلود Shortcut (۲ دقیقه)
```
https://www.icloud.com/shortcuts/crypto-tweet-replier
```

**یا دستی:**
- Shortcuts اپ را باز کن
- دکمه "+" را بزن
- اکشن‌های زیر را اضافه کن:
  1. Ask for Text (متن توییت)
  2. Ask ChatGPT / Claude
  3. Copy to Clipboard
  4. Show notification

### ۲. استفاده کن
```
۱. توی X متن توییت را کپی کن
۲. Shortcuts اپ را باز کن
۳. "Crypto Tweet Replier" را تپ کن
۴. جواب را نقل کن و در X قرار بده
```

---

## برای کامپیوتر (Python Agent)

### ۱. نصب Python
```bash
python --version  # باید 3.8+ باشد
```

### ۲. Clone Repository
```bash
git clone https://github.com/Amirnik77/crypto-tweet-replier.git
cd crypto-tweet-replier
```

### ۳. نصب Dependencies
```bash
pip install -r requirements.txt
```

### ۴. تنظیم API Key
```bash
# .env فایل را ایجاد کن و OpenAI API Key رو اضافه کن
cp .env.example .env
# سپس فایل را ویرایش کن و API Key رو وارد کن
```

### ۵. ��جرا کن

**حالت Demo (نمونه):**
```bash
python agent.py
```

**حالت Interactive (تعاملی):**
```bash
python agent.py interactive
```

---

## مثال استفاده

### Input:
```
Bitcoin just hit $50,000! 🚀 This is huge for the crypto market!
```

### Output:
```
Great momentum! Bitcoin's growth shows strong market confidence. 
The ecosystem continues to mature. Exciting times ahead for adoption! 📈
```

---

## لینک‌های مهم

| لینک | توضیح |
|------|--------|
| 🔗 [Shortcut](https://www.icloud.com/shortcuts/crypto-tweet-replier) | دانلود برای iOS |
| 📚 [راهنمای کامل](SHORTCUT_SETUP.md) | نصب و تنظیم |
| 🐍 [Python Agent](agent.py) | Agent برای سرور |
| 📋 [README](README.md) | توضیحات کامل |

---

## 🎯 بعدی

- [ ] Auto-reply feature
- [ ] Dashboard
- [ ] Multi-language
- [ ] Telegram Bot
- [ ] Discord Bot

---

**سوالی داری؟** → Issue بساز یا پیام بده 💬
