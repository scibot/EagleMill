# Eagle Mill — Site Planner

An interactive site-planning tool that overlays your house, pole barn, driveway, fence line, tree line, and percolation test area on live satellite imagery — all placed and scaled to real-world coordinates, and freely movable/rotatable/adjustable right in the browser.

**Live site:** _(fill in after enabling GitHub Pages — see below)_ `https://<your-username>.github.io/<repo-name>/`

## What's in here

- `index.html` — the entire tool. One self-contained file: no build step, no dependencies to install, nothing to run locally beyond a web browser.

## Running it locally

Just open `index.html` directly in Chrome, Safari, or Edge. It needs your browser's own internet connection to pull satellite tiles from Esri — that works the same whether you're opening the file locally or viewing it hosted on GitHub Pages.

## Hosting it on GitHub Pages

1. Create a new **public** repository on GitHub (Pages' free tier only serves public repos).
2. Upload `index.html` (drag-and-drop works fine on the repo's "Add file → Upload files" page) and commit it to the `main` branch.
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment," set **Source** to "Deploy from a branch," then set **Branch** to `main` and the folder to `/ (root)`, and save.
5. GitHub will publish it at `https://<your-username>.github.io/<repo-name>/` within a minute or two — refresh the Pages settings page to see the live link once it's ready.

## Heads-up on privacy

This page shows your actual home's location, floor plan, driveway, fence line, and septic/perc test layout. A public GitHub repo (and the Pages site built from it) is visible to anyone with the link, and can be found by anyone browsing your GitHub profile. If that changes, you can make the repo private at any time from **Settings → General → Danger Zone** — note that GitHub Pages on a private repo requires GitHub Pro/Team/Enterprise; on the free tier, going private will take the live site down until it's public again.

## Notes on the placements

Everything you move, rotate, resize, or trace in the tool (house, barn, fence, tree line, driveway, perc area) is saved in *your browser's* local storage for that specific page — it is not written back into this repository. If you want a durable backup of a layout, use the "Save to file" buttons in the tool and keep the resulting `.json` files somewhere safe (this repo included, if you'd like).
