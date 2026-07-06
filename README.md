# Football Analytics Platform v1

Clean V1 deployable football charting platform.

## Features
- Supabase online database
- Project dashboard
- PFF CSV/XLSX import
- Mobile charting for iPhone/iPad
- Formation builder
- FZ Advantage
- FZ Attacked
- Auto-calculated Advantage Attacked
- Team filters using PFF codes
- Next blank / flag / skip
- CSV export merged with original PFF data

## Database
Run `supabase/schema.sql` in Supabase SQL Editor.

## Local setup
```bash
npm install
cp .env.example .env
npm run dev
```

Add your Supabase URL and anon key to `.env`.

## Deployment
Deploy this folder to Vercel. Add the same two environment variables:

- `VITE_SUPABASE_URL`
- `VITE_SUPABASE_ANON_KEY`
