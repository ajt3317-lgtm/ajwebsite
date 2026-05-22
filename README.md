# AJ Website (Hub)

The landing page for all of AJ's web projects. Each card links out to the project's own deployed site.

**Live site:** _(add the Cloudflare Pages URL here once deployed)_

## What's in here

- `index.html` — the hub page. Each card is a `<a href="...">` pointing at the project's deployed URL.

## Linked projects

| Project | Repo | Current URL (Netlify) |
|---|---|---|
| Gravity Simulator | ajgravitysimulator | https://ajgravitysimulator.netlify.app/ |
| Periodic Table | ajperiodictable | https://ajperiodictable.netlify.app/ |
| Knockoff Clash Royale | ajknockoffclashroyale | https://ajknockoffclashroyale.netlify.app/ |
| Nuclear Effects Simulator | ajnukesimulator | https://ajnukesimulator.netlify.app/ |

> **TODO when migrating to Cloudflare Pages:** Once each project repo is deployed to Cloudflare Pages, update the four `<a href>` URLs in `index.html` to point at the new `*.pages.dev` (or custom-domain) URLs. The current Netlify URLs are left in for now so the hub keeps working during the migration.

## Running locally

Open `index.html` directly — all the links point at remote sites, so nothing is served from this repo.

## Deploying to Cloudflare Pages

1. Push this repo to GitHub.
2. Cloudflare dashboard → **Workers & Pages → Create → Pages → Connect to Git**.
3. Pick this repo.
4. Build settings: **Framework preset:** None · **Build command:** _(empty)_ · **Build output directory:** `/`.
5. Deploy.
