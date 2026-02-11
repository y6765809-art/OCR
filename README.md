# 📚 מערכת OCR מתקדמת לספרי קודש

> מערכת מקצועית לעיבוד אוטומטי של טקסט עברי מסרוק - מותאמת למכון תוצאות

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Hebrew](https://img.shields.io/badge/Language-Hebrew-blue.svg)](https://he.wikipedia.org/wiki/עברית)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)](https://github.com)

---

## ✨ תכונות עיקריות

### 🎯 עריכה מתקדמת
- ✅ **ניווט בולט** - כפתורים גדולים למעבר בין עמודים
- ✅ **חיפוש והחלפה חכם** - עם תבניות מובנות ואזהרות
- ✅ **סנכרון סמן** - הטקסט מודגש בתמונת המקור
- ✅ **3 פריסות עבודה** - התאם את המסך לצרכיך
- ✅ **מסך מלא** - עבודה מרוכזת ללא הסחות

### 💾 שמירה אמינה
- ✅ **3 שכבות שמירה** - LocalStorage + IndexedDB + Server
- ✅ **גיבויים אוטומטיים** - כל 30 שניות
- ✅ **גרסאות היסטוריה** - 10 גרסאות אחרונות
- ✅ **אין אובדן מידע** - גם בסגירה פתאומית

### 🎨 עיצוב תורני
- ✅ **צבעים מיוחדים** - חום, זהב, ברונזה (ללא כחול!)
- ✅ **גופן דוד** - קריא ומסורתי
- ✅ **ממשק עברי מלא** - RTL ומותאם לשפה

### 🔍 סימונים חכמים
- `◆` - תו לא ברור
- `◇` - תו ספק
- `⟪חסר⟫` - שורה חסרה
- `▓` - בלוק לא מזוהה

---

## 🚀 התחלה מהירה

### 1. פתיחה מקומית
```bash
# פשוט פתח את הקבצים בדפדפן
index-updated.html    # מסך ראשי
editor-COMPLETE.html  # מסך עריכה
```

### 2. שרת מקומי
```bash
# Python
python -m http.server 8000

# Node.js
npx http-server

# ואז גלוש ל:
http://localhost:8000
```

### 3. GitHub Pages
אם העלית ל-GitHub:
```
https://YOUR-USERNAME.github.io/REPO-NAME/
```

---

## 📁 מבנה הפרויקט

```
hebrew-ocr-app/
│
├── 🌟 קבצים ראשיים
│   ├── index-updated.html       # מסך ראשי - רשימת ספרים
│   ├── editor-COMPLETE.html     # מסך עריכה מלא
│   └── colors-torah.css         # ערכת צבעים תורנית
│
├── 📖 מדריכים
│   ├── README.md                # מדריך זה
│   ├── README-FINAL.md          # מדריך מפורט
│   ├── GITHUB-UPLOAD.md         # איך להעלות ל-GitHub
│   ├── COLOR-GUIDE.md           # מדריך צבעים
│   └── COMPLETE-CHECKLIST.md    # רשימת תכונות
│
└── 📄 גרסאות קודמות
    ├── editor-v3.html
    └── editor-v4.html
```

---

## ⌨️ קיצורי מקלדת

| קיצור | פעולה |
|-------|--------|
| `Ctrl+S` | שמירה ידנית |
| `Ctrl+F` | חיפוש והחלפה |
| `F11` | מסך מלא |
| `ESC` | סגירת חלונות |
| `Alt+←` | עמוד הבא |
| `Alt+→` | עמוד קודם |

---

## 🎯 תכונות מרכזיות

### ניווט עמודים
- כפתורים ענקיים למעבר בין עמודים
- מספר עמוד בולט (3.5rem)
- קפיצה מהירה לעמוד
- רשימת כל העמודים
- חזרה למקום שהפסקת

### חיפוש והחלפה
- חיפוש למטה/למעלה
- אזהרה על מחיקת עבודה
- תבניות מוכנות:
  - `אלוקים` → `אלוהים`
  - `מצוה` → `מצווה`
  - `ה'` → `הקב"ה`
- הוספת תבניות משלך
- החלפה בכל הספר

### פריסות
1. **תמונה + טקסט** - פריסה פשוטה
2. **2 שכבות** - תמונה למעלה, טקסט+תמונה למטה
3. **3 חלונות** - מקסימום גמישות

---

## 🛠️ טכנולוגיות

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **אחסון:** LocalStorage + IndexedDB
- **גופנים:** Google Fonts (Heebo, Frank Ruhl Libre, David)
- **צבעים:** ערכת צבעים תורנית מותאמת אישית

---

## 📊 דרישות מערכת

### דפדפן מומלץ:
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

### רזולוציה מינימלית:
- 1366x768 ומעלה

### אחסון:
- ~5MB לכל ספר (בממוצע)

---

## 🔮 תוכניות עתידיות

### בפיתוח:
- [ ] OCR אמיתי עם PaddleOCR
- [ ] זיהוי גופנים אוטומטי (רש"י/מרובע)
- [ ] מסגור אוטומטי חכם
- [ ] Backend Python/Node.js

### מתוכנן:
- [ ] ניהול משתמשים
- [ ] סנכרון בין מכשירים
- [ ] אפליקציית Desktop (Electron)
- [ ] ייצוא Word/PDF

---

## 🤝 תרומה לפרויקט

אנחנו שמחים לקבל תרומות! 

### איך לתרום:
1. Fork את הפרויקט
2. צור branch חדש (`git checkout -b feature/AmazingFeature`)
3. Commit את השינויים (`git commit -m 'Add some AmazingFeature'`)
4. Push ל-branch (`git push origin feature/AmazingFeature`)
5. פתח Pull Request

---

## 📝 רישיון

פרויקט זה מופץ תחת רישיון MIT - ראה את קובץ [LICENSE](LICENSE) לפרטים.

---

## 💬 יצירת קשר

**מכון תוצאות**
- 📧 Email: contact@machon-results.org
- 🌐 Website: [machon-results.org](https://machon-results.org)

---

## 🙏 תודות

- **OpenAI** - על הטכנולוגיה
- **Google Fonts** - על הגופנים העבריים
- **קהילת המפתחים** - על ההשראה והתמיכה

---

## 📖 מדריכים נוספים

- [📤 איך להעלות ל-GitHub](GITHUB-UPLOAD.md)
- [🎨 מדריך צבעים](COLOR-GUIDE.md)
- [✅ רשימת תכונות](COMPLETE-CHECKLIST.md)
- [📋 מדריך מפורט](README-FINAL.md)

---

<div align="center">
  
### עשוי באהבה ❤️ למען שימור המורשת התורנית

**⭐ אם הפרויקט עזר לך, תן כוכב!**

</div>
