# 📸 دليل تحميل الصور للمشروع

## الطريقة الأسهل: استخدام ملف HTML

1. **افتح ملف `download-images.html` في المتصفح**
2. سترى جميع الأماكن مع صور معاينة من Unsplash
3. **لتحميل الصورة:**
   - انقر بزر الماوس الأيمن على الصورة
   - اختر "حفظ الصورة باسم"
   - احفظها في المجلد المناسب (`images/historical/` أو `images/religious/` إلخ)

## الطريقة التلقائية: استخدام Python Script

### المتطلبات:
```bash
pip install requests
```

### التشغيل:
```bash
python download_images.py
```

سيقوم السكريبت بتحميل جميع الصور تلقائياً في المجلدات المناسبة.

## الطريقة اليدوية: البحث والتحميل

### مواقع مجانية للصور:
1. **Unsplash**: https://unsplash.com
2. **Pexels**: https://pexels.com  
3. **Pixabay**: https://pixabay.com

### كلمات البحث الموصى بها:
- "Alexandria Egypt"
- "Qaitbay Citadel"
- "Bibliotheca Alexandrina"
- "Montazah Palace Alexandria"
- "Alexandria tourism"

## هيكل المجلدات المطلوب:

```
images/
├── historical/
│   ├── qaitebay.jpg
│   ├── pompey-pillar.jpg
│   ├── roman-theater.jpg
│   ├── montazah-palace.jpg
│   ├── jewelry-museum.jpg
│   ├── kom-el-shokafa.jpg
│   └── bahari-alexandria.jpg
├── religious/
│   ├── abo-elabbas-mosque.jpg
│   └── st-mark-church.jpg
├── cultural/
│   ├── alexandria-library.jpg
│   ├── fine-arts-museum.jpg
│   ├── art-center.jpg
│   └── nabi-danial-street.jpg
├── food/
│   ├── mohamed-ahmed-restaurant.jpg
│   ├── shaban-fish.jpg
│   └── feteer-elaalat.jpg
└── entertainment/
    ├── antoniades-gardens.jpg
    ├── montazah-gardens.jpg
    ├── fouad-street.jpg
    └── ali-hindi-cafe.jpg
```

## مواصفات الصور الموصى بها:

- **الدقة**: 1920x1080 أو أعلى
- **التنسيق**: JPG أو WebP
- **الحجم**: أقل من 500KB (استخدم TinyPNG للضغط)
- **النسبة**: 16:9 أو 4:3

## ملاحظات مهمة:

1. تأكد من أن الصور مناسبة للاستخدام التجاري (تحقق من الرخصة)
2. Unsplash و Pexels و Pixabay تسمح بالاستخدام التجاري مجاناً
3. بعد التحميل، اختبر عرض الصور في الموقع
4. إذا كانت الصورة كبيرة، استخدم أداة ضغط مثل TinyPNG

