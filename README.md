# QI Data Lab — GitHub Pages

This repository holds the public landing page for the **QI Data Lab** working in the context of BAM's QI-Digital activities.

The site is deliberately buildless: `index.html` contains its markup, styling, and small navigation script. GitHub Pages serves it directly, with no Node or Jekyll build required.

## Publish

1. Create a **public** repository named `qi-data-lab.github.io` inside the `QI-Data-Lab` organization.
2. Push this repository's `main` branch to `https://github.com/QI-Data-Lab/qi-data-lab.github.io.git`.
3. In **Settings → Pages → Build and deployment**, select **Deploy from a branch**, `main`, `/(root)`, then save.
4. The organization site is served at <https://qi-data-lab.github.io/> after GitHub finishes publishing.

## Update

Edit `index.html`, then commit and push to `main`. The page has no external dependencies or secrets.

## Content scope

The page introduces public research directions and links to VC4QI, DRMD, Evidence Tracer, and official BAM/QI-Digital background. It is a research-group landing page, not a replacement for BAM's official institutional website.
