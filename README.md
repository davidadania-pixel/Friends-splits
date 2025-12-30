# PWA לאנדרואיד (הוספה למסך הבית)

זו אפליקציית Web מוכנה מסוג PWA. כדי שתוכל להוסיף למסך הבית והיא תיפתח כאפליקציה,
צריך לפרוס אותה לכתובת https (URL קבוע).

## אופציה A: GitHub Pages (חינמי ופשוט)
1) צור ריפו חדש ב-GitHub (למשל: `my-pwa-app`)
2) העלה את כל הקבצים של הפרויקט לתיקיית השורש של הריפו
3) ב-GitHub: Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / root
4) אחרי דקה-שתיים תקבל URL לדוגמה:
   `https://<username>.github.io/my-pwa-app/`

## אופציה B: Vercel (חינמי, גם פשוט)
1) היכנס ל-Vercel עם GitHub
2) Import Project → בחר את הריפו
3) Deploy (אין צורך בבילד)

## התקנה באנדרואיד
1) פתח את ה-URL ב-Chrome
2) תפריט ⋮ → "הוסף למסך הבית" / "Install app"
3) האייקון יופיע על מסך הבית ותיפתח במצב standalone.

## התאמה אישית
- לשנות שם: `manifest.webmanifest`
- לשנות אייקון: `icons/`
