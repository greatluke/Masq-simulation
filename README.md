# Masquerade — Top Lineups

Static site: the strongest ordered 5-mask lineups for the King's Choice
*Masquerade / Dance Battle* event, ranked by round-robin on the client's real
battle engine (every finalist vs every other, both slot orders, many seeds,
draws = ½).

| page | pool |
|---|---|
| `purple.html` | epic (purple) only, level 6 |
| `purple-blue.html` | epic (purple) L4 + rare (blue) L6 |
| `gold.html` | legendary (gold) only, level 6 |

Each page embeds every ranked finalist and filters client-side to teams that
contain a chosen set of masks (up to 5); it renders at most 100 rows. Mask icons
are inlined, while the polished site emblem lives at
`assets/masquerade-medal.png` (mirrored under `docs/assets`). Only Google Fonts
is external.

The same files are mirrored under `docs/` so GitHub Pages works from either
**`/ (root)`** or **`/docs`**. `.nojekyll` is present in both.

## Rebuild

```bash
python3 ../webtool/build_site.py   # reads reverse/data/topteams_*.json
```
