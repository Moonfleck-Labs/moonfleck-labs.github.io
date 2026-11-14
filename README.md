# Moonfleck Labs website

Static site served by GitHub Pages at https://moonfleck-labs.github.io

- `index.html` — studio page
- `privacy.html` — privacy policy (linked from Google Play)
- `app-ads.txt` — authorised ad sellers, checked by AdMob; must stay at the site root
- `.nojekyll` — serve files as they are, without Jekyll
- `<app-slug>/index.html` — one page per app, once it has store assets

## Brand assets

The logos are copies from the Moonfleck Labs brand set (`moonfleck-labs-brand`). Don't edit them here: change the brand set, then copy them again.

| Here | Brand set file |
|---|---|
| `assets/logo.svg` | `logo/svg/moonfleck-logo-stacked-on-dark.svg` |
| `assets/mark.svg` | `logo/svg/moonfleck-mark-color-on-dark.svg` |
| `assets/icon-512.png` | `play-store/app-icon-512x512.png` |

The colours in `assets/style.css` (`:root`) are the brand palette: Night `#111111`, White `#FFFFFF`, Gold `#E8B84A`, Grey `#8A8A8A`.

Everything here is public. Never commit secrets.
