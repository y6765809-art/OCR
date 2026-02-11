# 📤 מדריך העלאה ל-GitHub

## 🎯 שלב 1: צור Repository חדש ב-GitHub

1. **היכנס ל-GitHub.com**
   - לך ל: https://github.com/new

2. **מלא פרטים:**
   - **Repository name:** `ocr-torah` או `hebrew-ocr-system`
   - **Description:** מערכת OCR מתקדמת לספרי קודש
   - **Public/Private:** בחר לפי רצונך
   - **אל תסמן:** Add README, .gitignore, או license (יש לנו כבר!)

3. **לחץ:** Create repository

---

## 🎯 שלב 2: הכן את הקבצים

### א. הורד ואחלץ את הקובץ שנתתי לך
```bash
# חלץ את OCR-FINAL-COMPLETE.zip
# תקבל תיקייה: hebrew-ocr-app/
```

### ב. נקה קבצים מיותרים (אופציונלי)
```bash
cd hebrew-ocr-app

# מחק גרסאות ישנות אם רוצה רק את הסופי
rm -f editor-v3.html editor-v4.html

# השאר רק:
# - index-updated.html
# - editor-COMPLETE.html
# - colors-torah.css
# - קבצי MD (מדריכים)
```

---

## 🎯 שלב 3: העלאה ל-GitHub

### דרך 1: דרך הדפדפן (קל!)

1. **לך ל-Repository שיצרת**
   - https://github.com/YOUR-USERNAME/ocr-torah

2. **לחץ על:** "uploading an existing file"

3. **גרור את כל הקבצים:**
   ```
   index-updated.html
   editor-COMPLETE.html
   colors-torah.css
   README-FINAL.md
   COLOR-GUIDE.md
   ... וכל השאר
   ```

4. **כתוב הודעה:** 
   ```
   Initial commit - מערכת OCR מלאה
   ```

5. **לחץ:** Commit changes

**זהו! זה עובד! ✅**

---

### דרך 2: דרך Terminal (מתקדם)

#### א. התקן Git (אם אין לך)
```bash
# Windows
winget install Git.Git

# Mac
brew install git

# Linux
sudo apt install git
```

#### ב. הגדר את Git (פעם ראשונה)
```bash
git config --global user.name "השם שלך"
git config --global user.email "your.email@example.com"
```

#### ג. העלה את הקבצים
```bash
# 1. פתח Terminal בתיקיית hebrew-ocr-app
cd /path/to/hebrew-ocr-app

# 2. אתחל Git
git init

# 3. הוסף את כל הקבצים
git add .

# 4. צור commit ראשון
git commit -m "Initial commit - מערכת OCR מלאה"

# 5. חבר ל-GitHub (שנה את YOUR-USERNAME!)
git remote add origin https://github.com/YOUR-USERNAME/ocr-torah.git

# 6. העלה!
git push -u origin main
```

**אם יש שגיאה "main vs master":**
```bash
git branch -M main
git push -u origin main
```

---

## 🎯 שלב 4: הגדר GitHub Pages (אתר חי!)

אם רוצה שהפרויקט יהיה זמין באינטרנט:

1. **לך להגדרות:**
   - Repository → Settings → Pages

2. **Source:** 
   - Branch: `main`
   - Folder: `/ (root)`

3. **שמור**

4. **תוך 1-2 דקות תקבל URL:**
   ```
   https://YOUR-USERNAME.github.io/ocr-torah/
   ```

5. **פתח:**
   ```
   https://YOUR-USERNAME.github.io/ocr-torah/index-updated.html
   ```

**עכשיו יש לך אתר חי! 🎉**

---

## 📁 מבנה הקבצים ב-GitHub

```
ocr-torah/
├── index-updated.html          ← מסך ראשי
├── editor-COMPLETE.html        ← העורך המלא
├── colors-torah.css            ← צבעים
├── README-FINAL.md             ← תיעוד
├── COLOR-GUIDE.md
├── COMPLETE-CHECKLIST.md
├── FEATURES-CHECKLIST.md
├── TODO-NEXT.md
└── ... שאר הקבצים
```

---

## 🔧 עדכונים עתידיים

כשאתה משנה משהו:

```bash
# 1. עשה שינויים בקבצים

# 2. הוסף לגיט
git add .

# 3. צור commit
git commit -m "תיאור השינוי"

# 4. העלה
git push
```

---

## ⚠️ בעיות נפוצות

### בעיה: "Repository not found"
**פתרון:** בדוק שה-URL נכון
```bash
git remote -v  # בדוק מה ה-URL
git remote set-url origin https://github.com/USERNAME/REPO.git
```

### בעיה: "Permission denied"
**פתרון:** צריך להתחבר ל-GitHub
```bash
# אופציה 1: HTTPS (יבקש סיסמה)
git remote set-url origin https://github.com/USERNAME/REPO.git

# אופציה 2: SSH (מתקדם)
# צור SSH key ב-GitHub settings
```

### בעיה: קבצים גדולים מדי
**פתרון:** GitHub מגביל ל-100MB לקובץ
```bash
# אל תעלה תמונות/PDFs גדולים
# השתמש ב-.gitignore
```

---

## 📝 קובץ .gitignore מומלץ

צור קובץ בשם `.gitignore`:

```
# IDEs
.vscode/
.idea/

# OS
.DS_Store
Thumbs.db

# Large files
*.pdf
*.zip
*.psd

# Temp
temp/
backup/
```

---

## 🎯 סיכום מהיר

### העלאה ראשונה:
1. צור Repository ב-GitHub
2. גרור קבצים לדפדפן
3. Commit!

### עדכונים:
```bash
git add .
git commit -m "עדכון"
git push
```

### אתר חי:
Settings → Pages → Branch: main → Save

**זהו! פשוט! 🚀**
