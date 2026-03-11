# rally-around.us Website

Static site for Rally app. Built to deploy on Vercel (recommended) or any static host.

## Files
- `index.html` — Landing page
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service
- `vercel.json` — Vercel config (clean URLs: /privacy, /terms)

## Deploy to Vercel (5 minutes)

1. Push this folder to a GitHub repo (e.g., `kyudo/rally-website`)
2. Go to [vercel.com](https://vercel.com) → New Project → Import repo
3. No build settings needed — it's a static site
4. Add custom domain: `rally-around.us`
5. Vercel will issue a free SSL cert automatically

## Deploy to GitHub Pages (alternative)

1. Push to a GitHub repo
2. Settings → Pages → Deploy from branch → main → / (root)
3. Add custom domain `rally-around.us` in the Pages settings
4. Add a CNAME record at your DNS registrar pointing to `<username>.github.io`

## After Deploy — Update in App

The app currently links to:
- `https://rally-around.us/privacy`
- `https://rally-around.us/terms`

These will work automatically once the domain is live.
