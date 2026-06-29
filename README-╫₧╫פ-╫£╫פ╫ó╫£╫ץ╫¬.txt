גרסה מסודרת - Arabic Learning Game
====================================

מה חשוב לדעת:
1. index.html נשאר דף הכניסה עם Google/Firebase.
2. learn.html הוא מרחב הלמידה הראשי.
3. כל מה שקשור לאותיות נמצא בתיקיית letters/:
   - letters/index.html       שער יחידות האותיות
   - letters/unit.html        מנוע אחד חכם לכל יחידות האותיות
   - letters/letters-data.js  כל נתוני האותיות והיחידות
   - letters/letters.css      עיצוב מקומי של אזור האותיות

כלומר: שינוי באותיות נעשה רק בתוך letters/ ולא אמור להשפיע על מילים/משפטים בעתיד.

איך מעלים:
להעלות לשורש הריפוזיטורי את התוכן של התיקייה הזו, לא את התיקייה עצמה.
כך שבשורש GitHub יהיו:
- index.html
- learn.html
- stage1.html
- letters-unit1.html
- audio/
- letters/
- archive/
- README-מה-להעלות.txt

בדיקות אחרי העלאה:
1. https://nisan1234-afk.github.io/arabic-learning-game/learn.html
2. https://nisan1234-afk.github.io/arabic-learning-game/letters/
3. https://nisan1234-afk.github.io/arabic-learning-game/letters/unit.html?unit=1
4. https://nisan1234-afk.github.io/arabic-learning-game/letters/unit.html?unit=2

לא למחוק כרגע:
- audio/letters/  כי שם קבצי השמע שעובדים.
- stage1.html     כי הוא עבד ומשמש גיבוי/אב-טיפוס.
- archive/        מכיל קבצי בדיקה ישנים שלא מפריעים.
