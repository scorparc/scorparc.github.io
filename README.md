# Vardholt developer website

Public website: https://scorparc.github.io/

Static HTML and CSS hosted by GitHub Pages from `main` at the repository root. No dependencies, build, analytics, cookies, browser storage, or external fonts.

- `index.html`: German homepage.
- `en/index.html`: English homepage.
- `privacy.html`, `en/privacy.html`: website-specific privacy information.
- `assets/`: Vardholt logo, app icons and real BonSafe screenshots.
- App-specific privacy policies and the shared legal notice remain at https://scorparc.github.io/legal/.
- Preserve `app-ads.txt` and `googlea574d79dab1b8967.html` when updating this site.

The site lists the apps that are live on Google Play.

## Preview

Run `node scripts/preview.cjs` and open http://127.0.0.1:4173/. Stop with Ctrl+C. Publishing is a normal push to `main`; verify the GitHub Pages deployment and the live URL afterwards.

## Content updates

Update German and English pages together. Keep app links and privacy links aligned by package name. Website privacy information describes this static site and GitHub Pages hosting, not the apps. Review it when adding embeds, forms, analytics or other providers.
