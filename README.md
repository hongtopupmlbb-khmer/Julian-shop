# Julian Topup — Vercel deploy

Static site (no build step). Admin panel: /admin

## Deploy
- Dashboard: push this folder to GitHub → vercel.com/new → Import → Framework: "Other" → Deploy
- CLI: `npm i -g vercel && vercel --prod`

## Before going live
Edit the config block at the top of the <script> in index.html:
- KHQR.account  → your real Bakong Account ID (otherwise a demo notice shows)
- P (prices), RATE, TELEGRAM, ACCOUNTS
