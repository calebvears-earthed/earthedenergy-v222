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
- `index.html` — main landing page
- `image-slot.js` — image loading logic
- `support.js` — support/chat integration
- `img/` — hero + gallery images
- `vercel.json` — Vercel config
