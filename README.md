# Rish.exe — 8 Years, Still My Player 2
Static site, no build step, no dependencies.
## Edit
Everything personal is in `content.js` (chapters, notes, photo paths, quiz, easter egg, letter). Search for `[EDIT]`. Put photos in an `images/` folder and set `photo:"images/x.jpg"`.
## Run locally
`python3 -m http.server` in this folder, open http://localhost:8000
## Deploy to GitHub Pages
1. Push these files to a repo's `main` branch root.
2. Settings → Pages → Deploy from branch → `main` / root.
Routes use `#/map`, `#/chapter/2018`, `#/fruit-game`, `#/quiz`, `#/co-op`, `#/scrapbook`, `#/final`, so refresh works with no base-path config.
Progress is in localStorage (`rish-save`); "Reset save" is on the home screen.
