# Sillage — a school of scent

A single-page, dependency-free static site. No build step.

## Deploy to Vercel

**Option A — drag and drop**
1. Unzip this folder.
2. Go to https://vercel.com/new, choose **Deploy** → drag the `sillage-site` folder in.
3. Framework preset: **Other**. Build command: *(leave empty)*. Output directory: `.`

**Option B — Vercel CLI**
```bash
npm i -g vercel
cd sillage-site
vercel          # preview
vercel --prod   # production
```

**Option C — GitHub**
Push this folder to a repo, then import it at https://vercel.com/new. Same settings as Option A.

## Files
- `index.html` — the whole app (HTML, CSS and JS inline). Fonts load from Google Fonts.
- `vercel.json` — clean URLs and a couple of security headers.

## Notes
- Progress, the journal, the lab formula and each visitor's sorted house are saved in that visitor's browser (localStorage). Nothing is sent to a server.
- Navigation uses `#` routes (e.g. `/#organ`, `/#lesson-3`), so no rewrites are needed.
- Support link: https://ko-fi.com/yirschen (home page and footer).
