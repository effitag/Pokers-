# Felt Lab – Texas Hold'em Cash Trainer

אפליקציית רשת לאימון בפוקר (6-Max, 100bb), בקובץ יחיד: `index.html`.

**הרצה:** פותחים את `index.html` בדפדפן. אין צורך בהתקנה (React ו-htm נטענים מ-CDN).

## מה יש בפנים
- **Pre-Flop Trainer** – פתיחה (RFI) ומצבים מול פתיחה (Call / 3-Bet / Fold) לפי מיקום, עם פידבק ומפת טווח.
- **Post-Flop Trainer** – יד מלאה מול יריב (Flop → Turn → River): C-Bet, Check-Call, Check-Raise ועוד. כל החלטה מדורגת לפי Equity מול טווח משוער של היריב ו-Pot Odds.
- **סיכויים בזמן אמת** – Equity (Monte Carlo), אאוטים, כלל 2/4, Pot Odds, EV של קריאה וטווח היריב המצטמצם.
- **Range Explorer** – מפת 13×13 לכל מיקום ומצב.
- **התקדמות** – דיוק כולל, דיוק לפי רחוב, סוגי טעויות נפוצים וטיפים (נשמר ב-localStorage).
- **מצב אינטואיציה** – מסתיר את המספרים עד אחרי ההחלטה.

קיצורי מקלדת: `F` Fold · `C` Check/Call · `R`/`B` Raise/Bet · `N` יד הבאה.

הטווחים וההמלצות הם בסיס לימודי מפושט – לא Solver.
