# ניהול חומרי גלם

אתר סטטי (index.html) עם Supabase כשכבת נתונים.

- **Supabase project:** `Inventory` (`wayigvagjucphixkcsim`)
- **טבלאות:** `materials`, `transactions`, `campaigns`, `campaign_daily_entries`, `campaign_material_consumption`

## שמירה על הפרויקט ער
`.github/workflows/keep-supabase-awake.yml` שולח בקשת קריאה פעמיים ביום כדי שהפרויקט
בתוכנית החינם לא יעבור למצב לא-אקטיבי אחרי ~7 ימים ללא פעילות.
אפשר גם להריץ ידנית: Actions → Keep Supabase awake → Run workflow.

> ⚠️ הפרויקט ב-Supabase כרגע במצב INACTIVE. תוכנית החינם מאפשרת 2 פרויקטים
> פעילים בלבד, וכרגע הם `sicily-trip-2026` ו-`Instructions-41-42`.
> צריך לפנות מקום (pause/delete) או לשדרג לפני ה-restore — עד אז ה-workflow ייכשל.
