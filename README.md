# NRC Workspace — Interactive UI Demo v2

A static interactive front-end prototype with fictional sample records.

## Run locally
Open `index.html` in a modern browser. No build tools are required.

## Working demo functions
- Dashboard totals update from records in this browser
- Create SO, edit SO, view SO detail
- SO Number auto-suggestion and duplicate check
- Pending/Paid validation (Paid requires invoice number and payment date)
- Search, payment filter and sorting
- Archive and restore SO records
- Add customer names
- Export SO records to CSV
- Activity log for key demo actions
- Browser localStorage persistence (data stays in this browser)

## Important limitations
This is not a production system. There is no login, no shared database, no server-side permissions, no secure audit log, and no cloud backup. Data is stored only in the current browser. Do not enter real customer or company data.

## Deploy to Vercel
1. Create a GitHub repository and upload `index.html` (and this README).
2. In Vercel, choose **Add New → Project**, import that GitHub repository.
3. For this static HTML demo, no framework preset or build command is needed. Set the output directory to `.` if requested.
4. Deploy. Vercel will provide a public URL.
5. Any future GitHub push to the connected branch can trigger a new deployment.

Production version will later move to Next.js + Supabase Auth/PostgreSQL/RLS.
