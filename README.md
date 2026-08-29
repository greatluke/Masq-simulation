# Masquerade — Top Lineups

Static page: the 100 strongest **epic (purple) only, level‑6** lineups for the
King's Choice *Masquerade / Dance Battle* event, ranked by round‑robin on the
client's real battle engine.

`index.html` is fully self‑contained (mask icons inlined as data URIs, only
Google Fonts loaded externally). Just open it, or serve the folder statically.

## Publish to GitHub Pages

```bash
git init
git add .
git commit -m "Masquerade top-100 purple lineups"
git branch -M main
git remote add origin git@github.com:<you>/<repo>.git   # create the empty repo first
git push -u origin main
```

Then on github.com: **Settings → Pages → Build and deployment → Source: Deploy
from a branch → `main` / `/ (root)` → Save**. Live at
`https://<you>.github.io/<repo>/` within a minute.

`.nojekyll` is present so Pages serves the files as‑is.
