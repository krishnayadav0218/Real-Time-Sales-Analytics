# sales-dashboard (Static Site)

Pure HTML/CSS/JS dashboard with simulated live sales data. No backend,
no Python files, no build step — deploys as-is on Vercel or Netlify.

## Deploy on Vercel
1. Push this folder as its own GitHub repo (or import just this folder).
2. On vercel.com/new, import the repo.
3. Framework Preset: "Other". Build Command: empty. Output Directory: empty.
4. Deploy.

## Deploy on Netlify
1. Drag-and-drop this folder at https://app.netlify.com/drop
   OR
2. `netlify deploy --prod` from inside this folder.

## Important
This repo must contain ONLY static files (html/css/js/json/md).
Do not add any .py files here — Vercel will try to auto-detect a Python
backend and the static site will stop deploying correctly.
