# Muhammad Asyraf — Media Kit 2026

Static single-page site. No build step.

## Structure
- `index.html` — all markup, CSS and JS
- `assets/` — optimised photos
- `vercel.json` — caching and security headers

## Commit to GitHub
```bash
git init
git add .
git commit -m "Initial media kit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo>.git
git push -u origin main
```

## Deploy on Vercel
1. Go to vercel.com/new and import the GitHub repo.
2. Framework preset: **Other**. Leave build command and output directory empty.
3. Click Deploy. Every push to `main` redeploys automatically.

## Inquiry form
The form validates in the browser and opens the visitor's email app with the inquiry pre-filled to masyrafph@gmail.com. To receive submissions without an email app, swap the submit handler for a Formspree endpoint or a Vercel serverless function.
