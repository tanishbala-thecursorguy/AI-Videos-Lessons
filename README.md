# ClipCash Academy

Sales site for the ClipCash course: learn to build faceless AI Shorts channels that earn from YouTube monetization, brand collabs and link-in-bio offers.

## Files
- `index.html` — the whole site (no build step)
- `site.json` — prices, early-bird counter and checkout links. Edit this to update the page.
- `clips/` — looping preview clips from our channels

## Update the counter / checkout
Edit `site.json`:
```json
{ "earlyBirdTotal": 200, "earlyBirdClaimed": 0, "earlyPrice": 9, "fullPrice": 19,
  "checkoutEarly": "https://your-9-dollar-checkout-link",
  "checkoutFull":  "https://your-19-dollar-checkout-link" }
```
Set `earlyBirdClaimed` to the real number of sales. When it reaches 200 the page switches to the full price automatically.

## Deploy
Any static host works: Netlify, Vercel or GitHub Pages (Settings → Pages → deploy from `main`).
