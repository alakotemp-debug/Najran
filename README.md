
## 🌐 زيارة الموقع
<div align="center" style="margin-top: 20px;">
  <!-- زر النسخة العربية -->
  <a href="https://alakotemp-debug.github.io/Najran/pages/index.html" 
     style="text-decoration: none; 
            padding: 12px 30px; 
            background: linear-gradient(135deg, #e0a3ff, #ff69b4); 
            color: #000; 
            border-radius: 25px; 
            font-weight: bold; 
            font-size: 1rem; 
            margin: 0 10px; 
            display: inline-block;">
    العربية (الصفحة الرئيسية)
  </a>

  
  <!-- زر النسخة الإنجليزية -->
  <a href="https://alakotemp-debug.github.io/Najran/pages/index-en.html" 
     style="text-decoration: none; 
            padding: 12px 30px; 
            background: linear-gradient(135deg, #7fffd4, #32cd32); 
            color: #000; 
            border-radius: 25px; 
            font-weight: bold; 
            font-size: 1rem; 
            margin: 0 10px; 
            display: inline-block;">
    English
  </a>
</div>

## 📌 مشاهدة كود المشروع
<div align="center" style="margin-top: 20px;">
  <a href="https://github.com/alakotemp-debug/Najran/blob/main/pages/index.html" 
     style="text-decoration: none; 
            padding: 12px 30px; 
            background: #ffb347; 
            color: #000; 
            border-radius: 25px; 
            font-weight: bold; 
            font-size: 1rem; 
            display: inline-block;">
    عرض كود الصفحة الرئيسية
  </a>
</div>
##

# 🕌 نجران – بوابة التاريخ والتراث  
بوابة رقمية تفاعلية تستعرض تاريخ وتراث منطقة نجران بأسلوب حديث ومرئي، وتهدف إلى تقديم تجربة استخدام جذابة عبر تصميم متناسق، فيديو افتتاحي، وتنقل سهل بين أقسام الموقع.

<img width="1910" height="913" alt="01" src="https://github.com/user-attachments/assets/d847dac2-e013-4cd6-bec4-188a6af598cd" />


---

## 📌 محتوى المشروع
يحتوي المشروع على:

- **صفحة رئيسية**: واجهة تفاعلية تضم مقدمة عن نجران.
- **صفحات فرعية** داخل مجلد `pages/` مثل:
  - الجغرافيا  
  - التاريخ  
  - الاقتصاد  
  - المعالم
    - فيديو يحكي قصة التراث
      <img width="1901" height="889" alt="05" src="https://github.com/user-attachments/assets/9449ab3e-bdc8-43a9-94c9-be5aa528fe18" />

- **وسائط متعددة** داخل `images/`
  <img width="1914" height="942" alt="02" src="https://github.com/user-attachments/assets/29f0251f-d5ac-4ee0-b2eb-99368e15a195" />
- **ملفات تصميم وبرمجة**:
  - `templatemo-neural-style.css`
  - `templatemo-neural-scripts.js`

---

## 🧭 طريقة عمل الموقع
عند فتح المشروع يقوم الملف الرئيسي **index.html** بتنفيذ إعادة توجيه تلقائية إلى الصفحة الأساسية داخل مجلد **pages**:

```html
<meta http-equiv="refresh" content="0; url=pages/index.html">
<script>
    window.location.href = "pages/index.html";
</script>
🖼️ الوسائط المستخدمة
المجلد images/ يحتوي على:

css
Copy code
najran-intro.mp4
video-poster.jpg
najran-history.jpg
najran-geography.jpg
najran-economy.jpg
وتُستخدم لإثراء تجربة المستخدم في الصفحات.

🎨 تصميم الواجهة
يعتمد تصميم المشروع على:

خط Cairo للغة العربية.

تأثيرات Glassmorphism وشفافية.

خلفية داكنة مع ألوان بنفسجية وزهرية.

عناصر متحركة (مثل Spinner) لزيادة التفاعل البصري.

📂 هيكلة المجلدات
pgsql
Copy code
root/
│── index.html
│── index-en.html
│── templatemo-neural-style.css
│── templatemo-neural-scripts.js
│── README.md
│
├── images/
│     ├── najran-intro.mp4
│     ├── video-poster.jpg
│     ├── najran-history.jpg
│     ├── najran-geography.jpg
│     └── najran-economy.jpg
│
└── pages/
      └── index.html
🚀 طريقة التشغيل
1️⃣ افتح الملف:

diff
Copy code
index.html
2️⃣ سيتم توجيهك تلقائيًا إلى الصفحة الرئيسية:

bash
Copy code
pages/index.html
الموقع يعمل مباشرة دون أي تثبيت أو إعداد إضافي، ويدعم الاستضافة على GitHub Pages.

🎯 الهدف من المشروع
تم إنشاء هذا المشروع كجزء من تقييم عملي لعرض مهارات:

تصميم الويب Front-End




استخدام HTML / CSS 

القليل من اكواد JavaScript لاعطاء الاحترافية



تنظيم المشروع بشكل احترافي

تقديم محتوى مرئي وحديث

بناء واجهة عربية متناسقة سهلة الاستخدام

يدعم ايضا عرض الصفحه باللغه الانجليزيه...
