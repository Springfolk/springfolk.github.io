# Site

| Path | What |
|---|---|
| `index.html` | header lockup, one-line lede, project cards, footer |
| `404.html` | minimal not-found page (root-absolute paths) |
| `assets/site.css` | all styles; light/dark via `prefers-color-scheme` |
| `assets/brand/` | unedited copies of `full-logo{,-dark}.svg`, `glyph{,-dark}.svg` (favicon) from `Springfolk/branding` |
| `assets/fonts/` | Nunito Sans variable woff2 (latin, cyrillic, cyrillic-ext for Sakha letters) + `OFL.txt` |
| `assets/alaas.svg` | Алаас icon, copied from `alaas/docs/img/icon.svg` (replace with the redrawn one when it lands) |
| `assets/voxlook.png` | VoxLook icon, 192 px downscale of `voxlook/docs/icon.png` |

## Brand mapping

- Light: `paper` bg, `soil` text. Dark: `soil` bg, `paper` text. Muted greys are soil/paper mixes (≥ 6.5:1).
- Green appears only in the logo and favicon. Buttons are `soil`/`paper` inverted, never green.

## Adding a project

Public, non-commercial repos only (`gh repo view <repo> --json visibility`). Copy one `<li class="card">`, use a small icon (≤ 50 kB) with `alt=""` (the name is beside it), link "Play"/"Install" and "Source", and add its licence to the footer. AI-assisted projects get `<span class="tag" lang="en" title="Assisted by <model>">AI-assisted</span>` in the `h2`; the footer line about the tag is generic, so leave it.
