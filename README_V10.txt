Field Zone Charting App v10 Cloud Resume

WHAT CHANGED
- Opens cloud projects without needing the CSV again.
- Adds Resume Last Cloud Project.
- Keeps v7 charting workflow.
- Uploads full CSV rows to Supabase.
- Saves each charted play back to Supabase.

SETUP
1. Upload index.html to GitHub, replacing the current index.html.
2. Let Vercel redeploy.
3. In Supabase SQL Editor, run supabase/V10_SQL_RUN_THIS.sql.
   Warning: it resets charting_projects and charted_plays.
4. Open the Vercel link.
5. Upload CSV once.
6. After upload finishes, close and reopen.
7. Click Refresh cloud projects or Resume Last Cloud Project.

NOTE
This is still development mode. RLS policies are permissive so the app works without login.
Later, add authentication and private user/project access.
