# My Wallet — Jade's Expenses

An installable phone app (PWA) for Jade Valerie's daily allowance and expenses.

- **Page** → hosted here on GitHub Pages
- **Data** → still in the Google Sheet, through the Apps Script `/exec` link (`API_URL` in `index.html`)

## Install on a phone
- **Android (Chrome):** open the site → tap **Install** on the card (or menu ⋮ → *Install app*)
- **iPhone (Safari):** open the site → **Share** ⬆︎ → **Add to Home Screen**

## Files
| File | What it does |
|---|---|
| `index.html` | The app |
| `manifest.webmanifest` | App name, colours, icons (makes it installable) |
| `sw.js` | Lets the app open without signal |
| `icon-*.png`, `apple-touch-icon.png`, `favicon.png` | App icons |

## After editing `index.html`
Change `mywallet-v1` in `sw.js` to `mywallet-v2` (and so on) so installed phones pick up the update.
