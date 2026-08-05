# Sanctum Obscure — Pillar Sequence Tracker

A small, single-page web app to track the pillar-lighting sequence during the
**Obscure** boss fight in [Medivia Online](https://medivia.online). Tap the
pillars in the order they light up (repeats allowed) to log and follow the
8-click sequence in real time.

Built as a lightweight fan/community tool — no build step, no dependencies,
just one HTML file.

## Features

- 🔮 8 interactive pillars laid out around the arena, matching the in-game room
- 🔢 Logs the click order, allows the same pillar to repeat
- ↩️ Undo last click / reset the whole sequence
- 🌗 Progress ring + counter showing `n / 8`
- 🌐 Language switch: **Spanish / English**, no page reload
- 📱 Responsive layout — works on phone, tablet, and desktop
- 🔗 Footer with copyright, a link to this repo, and a Discord contact link for bug reports/ideas
- ⚡ Pure HTML/CSS/JS, no frameworks, no build tools, no external JS libraries

## Demo

Open `index.html` directly in any modern browser, or serve it locally:

```bash
# any static server works, for example:
npx serve .
# or
python3 -m http.server 8000
```

Then visit `http://localhost:8000` (or the port your server prints).

## Deploying to GitHub Pages

1. Create a new GitHub repository and push this project to it:

   ```bash
   git init
   git add .
   git commit -m "Initial commit: Obscure pillar sequence tracker"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```

2. On GitHub, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then **Save**.
5. After a minute or two, your app will be live at:

   ```
   https://<your-username>.github.io/<your-repo>/
   ```

No build step is required — GitHub Pages serves `index.html` as-is.

## Project structure

```
.
├── index.html   # the entire app (markup, styles, and logic)
└── README.md    # this file
```

## Notes

- This is an unofficial, fan-made tool and is not affiliated with or endorsed
  by Medivia Online.
- All visuals (pillar icons, layout) are original assets created for this
  tool, styled to match the game's aesthetic — no game assets are reproduced.

## License

MIT — see [LICENSE](LICENSE) if included, or feel free to reuse/modify freely.
