# F5 Money Exchange

Thai Baht ↔ Myanmar Kyat exchange-rate website, based on 100,000 MMK.

- Live site (after GitHub Pages is enabled): https://mookie247.github.io/f5-money-exchange/
- Rates are shown per 100,000 MMK (e.g. 100,000 MMK = 650 THB format)
- Baht → Kyat / Kyat → Baht converter, quick table, Bangkok + Yangon live clocks
- Promo Code: `WMTH13F5` — entering it shows a special rate
- Theme: blue #0047AB, green #2ECC71, near-black #1C1C1E

## Update the rates

Edit `CONFIG` at the top of `index.html` and replace the SAMPLE rates with the real rates:

- `buyRate` / `sellRate` — THB per 100,000 MMK
- `promoRate` — THB per 100,000 MMK for Promo Code `WMTH13F5` (leave empty to disable the promo)
- `promoCode` — the single promo code
- `updatedAt` — the date/time the rates were updated

Note: the rates shipped here are SAMPLE rates, clearly labelled on the page. Replace them before sharing the link.

## Enable GitHub Pages

Repo → Settings → Pages → Deploy from a branch → Branch `main`, folder `/ (root)` → Save. The site will be live at the URL above in a few minutes.
