Field Zone Charting v9 Supabase Full Save

What changed from v8:
- Uploading a CSV now saves every row to Supabase.
- Reopening the website can load a cloud project without uploading the CSV again.
- The app lists cloud projects on the home screen.
- Charted plays still export back to CSV.

Setup:
1. Upload index.html to the root of your GitHub repo, replacing the old file.
2. Vercel should redeploy automatically.
3. If cloud save/list/open fails, open Supabase SQL Editor and run supabase/V9_SQL_RUN_THIS.sql.

Important:
This v9 uses demo/public RLS policies so it is easy to test. Do not put sensitive/private team data in this public demo until we add login/user security.
