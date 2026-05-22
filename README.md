# AJ Website (Hub)

The landing page for all of AJ's web projects. Each card links out to the project's own deployed site.

**Live site:** _(add the Cloudflare Pages URL here once deployed)_

## What's in here

- `index.html` — the hub page. Each card is a `<a href="...">` pointing at the project's deployed URL.

## Linked projects

| Project | Repo | URL (Cloudflare Pages) |
|---|---|---|
| Gravity Simulator | ajgravitysimulator | https://ajgravitysimulator.pages.dev/ |
| Periodic Table | ajperiodictable | https://ajperiodictable.pages.dev/ |
| Knockoff Clash Royale | ajknockoffclashroyale | https://ajknockoffclashroyale.pages.dev/ |
| Nuclear Effects Simulator | ajnukesimulator | https://ajnukesimulator.pages.dev/ |

> **Note:** These URLs assume each Cloudflare Pages project is named the same as its repo (`ajgravitysimulator`, etc.). If you pick different Cloudflare project names — or set up a custom domain — update the four `<a href>` URLs in `index.html` accordingly. Until each project is deployed, its card will 404.

## Running locally

Open `index.html` directly — all the links point at remote sites, so nothing is served from this repo.

## Deploying to Cloudflare Pages

1. Push this repo to GitHub.
2. Cloudflare dashboard → **Workers & Pages → Create → Pages → Connect to Git**.
3. Pick this repo.
4. Build settings: **Framework preset:** None · **Build command:** _(empty)_ · **Build output directory:** `/`.
5. Deploy.
