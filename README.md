# 🧠 تشخیص ذات‌الریه از تصاویر قفسه سینه با CNN

پروژه‌ای ساده برای تشخیص بیماری ذات‌الریه (Pneumonia) از طریق عکس‌های X-ray قفسه سینه با استفاده از شبکه‌های عصبی کانولوشنی (CNN) در Keras و TensorFlow.

## 📁 ساختار داده‌ها
داده‌ها از [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) دریافت می‌شن و به سه پوشه تقسیم شدن:
- `train/`
- `val/`
- `test/`

## ✅ تکنولوژی‌ها
- Python
- TensorFlow / Keras
- Google Colab
- CNN (Convolutional Neural Networks)
- Matplotlib, Seaborn

## 🚀 آموزش مدل
مدل روی داده‌های `train` آموزش داده می‌شه و با داده‌های `val` ارزیابی می‌شه. دقت نهایی روی داده‌های تست نیز بررسی می‌شه.

## 📊 نتایج
- دقت روی تست: حدود 90٪
- ماتریس سردرگمی برای تحلیل بهتر عملکرد

## ⚠️ توجه
داده‌ها در گیت‌هاب قرار نگرفته‌اند چون حجم بالایی دارند. لطفاً از Kaggle دانلود کنید.
