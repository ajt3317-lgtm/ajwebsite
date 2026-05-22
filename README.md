# AJ Website (Hub)

The landing page for all of AJ's web projects. Each card links out to the project's own deployed site.

**Live site:** _(add the Cloudflare Pages URL here once deployed)_

## What's in here

- `index.html` — the hub page. Each card is a `<a href="...">` pointing at the project's deployed URL.

## Linked projects

| Project | Repo | URL (Cloudflare Workers) |
|---|---|---|
| Gravity Simulator | ajgravitysimulator | https://ajgravitysimulator.ajt3317.workers.dev/ |
| Periodic Table | ajperiodictable | https://ajperiodictable.ajt3317.workers.dev/ |
| Knockoff Clash Royale | ajknockoffclashroyale | https://ajknockoffclashroyale.ajt3317.workers.dev/ |
| Nuclear Effects Simulator | ajnukesimulator | https://ajnukesimulator.ajt3317.workers.dev/ |

> **Note:** Each project is deployed as a Cloudflare Worker (static-assets Worker), at `<project-name>.ajt3317.workers.dev`. If you rename a Worker or set up a custom domain, update the matching `<a href>` URL in `index.html`.

## Running locally

Open `index.html` directly — all the links point at remote sites, so nothing is served from this repo.

## Deploying to Cloudflare Pages

1. Push this repo to GitHub.
2. Cloudflare dashboard → **Workers & Pages → Create → Pages → Connect to Git**.
3. Pick this repo.
4. Build settings: **Framework preset:** None · **Build command:** _(empty)_ · **Build output directory:** `/`.
5. Deploy.
