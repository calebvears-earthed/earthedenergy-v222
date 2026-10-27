# Earthed Energy · v222

New site build for earthedenergy.au — staging deployment.

**Status:** in progress · adding forms + finer touches before domain swap.

## Stack
- Static HTML/CSS/JS
- Vercel hosting
- Domain: `earthedenergy.au` (currently on old `earthedenergy-website` repo — to be swapped once v222 is polished)

## Workflow
1. Edit locally
2. `git add . && git commit -m "..." && git push`
3. Vercel auto-deploys from `main`

## Files
- `index.html` — home page (Claude Design "Earthed Energy Home v5")
- `<slug>.html` — 40 content pages, served at clean URLs (`/residential`, `/knowledge`, `/get-a-quote`, …)
- `support.js` — Claude Design page runtime (renders the `<x-dc>` templates client-side)
- `image-slot.js` + `.image-slots.state.json` — image slot component and saved crop/framing
- `knowledge-index.js` — guide list used by `/knowledge`
- `img/site/` — compressed images used by the v5-era pages
- `vercel.json` — clean URLs + redirects for old slugs (`/equipment`, `/credentials`)
