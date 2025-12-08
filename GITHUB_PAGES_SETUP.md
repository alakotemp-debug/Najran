# إعداد GitHub Pages للمشروع

## 📋 خطوات الإعداد

### 1. رفع المشروع على GitHub
- تأكد من رفع جميع الملفات والمجلدات:
  - ✅ `index.html` (في الجذر)
  - ✅ `pages/` (المجلد كاملاً)
  - ✅ `images/` (المجلد كاملاً)

### 2. تفعيل GitHub Pages
1. اذهب إلى إعدادات المستودع (Settings)
2. اضغط على "Pages" من القائمة الجانبية
3. في "Source"، اختر "Deploy from a branch"
4. اختر Branch: `main` (أو `master`)
5. اختر Folder: `/ (root)`
6. اضغط "Save"

### 3. رابط الموقع
بعد بضع دقائق، سيكون الموقع متاحاً على:
```
https://YOUR_USERNAME.github.io/Najran_web/
```

أو إذا كان المستودع اسمه مختلف:
```
https://YOUR_USERNAME.github.io/REPO_NAME/
```

## 🔧 حل مشاكل المسارات

إذا كانت الصور لا تظهر:

### الحل 1: التأكد من هيكل المجلدات
```
Najran_web/
├── index.html
├── pages/
│   ├── index.html
│   ├── index-en.html
│   └── ...
└── images/
    ├── najran-history.jpg
    ├── najran-geography.jpg
    ├── najran-economy.jpg
    ├── najran-intro.mp4
    └── video-poster.jpg
```

### الحل 2: التحقق من المسارات
- المسارات في `pages/index.html` يجب أن تكون: `../images/`
- المسارات في CSS يجب أن تكون: `../images/`

### الحل 3: استخدام JavaScript
تم إضافة script تلقائي في الصفحات لتحديث المسارات ديناميكياً.

## ✅ التحقق من العمل
1. افتح الموقع على GitHub Pages
2. افتح Developer Tools (F12)
3. اذهب إلى Console
4. تحقق من عدم وجود أخطاء 404 للصور

## 🐛 حل المشاكل الشائعة

### المشكلة: الصور لا تظهر
**الحل:**
- تأكد من رفع مجلد `images/` كاملاً
- تحقق من أن أسماء الملفات صحيحة (case-sensitive)
- تأكد من أن الملفات موجودة في GitHub

### المشكلة: CSS لا يعمل
**الحل:**
- تأكد من رفع ملف `templatemo-neural-style.css`
- تحقق من المسار في HTML: `templatemo-neural-style.css`

### المشكلة: الفيديو لا يعمل
**الحل:**
- تأكد من رفع ملف الفيديو `najran-intro.mp4`
- GitHub Pages قد لا يدعم ملفات كبيرة جداً (> 100MB)
- استخدم ملفات فيديو أصغر أو استخدم رابط خارجي

---

# GitHub Pages Setup

## 📋 Setup Steps

### 1. Upload Project to GitHub
- Make sure to upload all files and folders:
  - ✅ `index.html` (in root)
  - ✅ `pages/` (entire folder)
  - ✅ `images/` (entire folder)

### 2. Enable GitHub Pages
1. Go to repository Settings
2. Click "Pages" from sidebar
3. Under "Source", select "Deploy from a branch"
4. Select Branch: `main` (or `master`)
5. Select Folder: `/ (root)`
6. Click "Save"

### 3. Website URL
After a few minutes, the site will be available at:
```
https://YOUR_USERNAME.github.io/Najran_web/
```

Or if repository name is different:
```
https://YOUR_USERNAME.github.io/REPO_NAME/
```

## 🔧 Fixing Path Issues

If images are not showing:

### Solution 1: Check Folder Structure
```
Najran_web/
├── index.html
├── pages/
│   ├── index.html
│   ├── index-en.html
│   └── ...
└── images/
    ├── najran-history.jpg
    ├── najran-geography.jpg
    ├── najran-economy.jpg
    ├── najran-intro.mp4
    └── video-poster.jpg
```

### Solution 2: Verify Paths
- Paths in `pages/index.html` should be: `../images/`
- Paths in CSS should be: `../images/`

### Solution 3: Use JavaScript
Automatic script has been added to pages to update paths dynamically.

## ✅ Verify It Works
1. Open the site on GitHub Pages
2. Open Developer Tools (F12)
3. Go to Console
4. Check for no 404 errors for images

## 🐛 Common Issues

### Issue: Images not showing
**Solution:**
- Make sure `images/` folder is fully uploaded
- Check file names are correct (case-sensitive)
- Verify files exist on GitHub

### Issue: CSS not working
**Solution:**
- Make sure `templatemo-neural-style.css` is uploaded
- Check path in HTML: `templatemo-neural-style.css`

### Issue: Video not working
**Solution:**
- Make sure video file `najran-intro.mp4` is uploaded
- GitHub Pages may not support very large files (> 100MB)
- Use smaller video files or external link

