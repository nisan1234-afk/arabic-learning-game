עדכון אותיות v3 - שמירת התקדמות

להעלות רק את הקבצים שבתיקיית letters אל תיקיית letters הקיימת בגיטהב:
- index.html
- unit.html
- letters-data.js
- letters.css

מה חדש:
1. לחיצה על "סיימתי יחידה" שומרת completed=true ב-Firebase Firestore.
2. letters/index.html קורא התקדמות ומציג "הושלם ✓" ליד יחידה שסומנה.
3. השינוי מקומי לתיקיית letters בלבד.

אם השמירה לא עובדת, ייתכן שצריך להפעיל Cloud Firestore בפרויקט Firebase או לפתוח הרשאות כתיבה למשתמשים מחוברים.
