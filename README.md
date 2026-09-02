# NickOfTime — Producer Website

One-page static site for NickOfTime Productions — black & gold luxury theme.
Services: beats & instrumentals, mixing & mastering, feature verses, sound engineering.

## Preview

No build step. Open `index.html` in a browser, or serve the folder:

    npx serve .

## Placeholders to replace before launch

| What | Where |
| --- | --- |
| Hero artwork | Drop your image as `image.png` next to `index.html` — until then a built-in SVG placeholder shows automatically |
| YouTube video | `VIDEO_ID` constant in the `<script>` at the bottom of `index.html` |
| Booking email | `nickoftime@email.com` (marked with a TODO comment) |
| Social links | The four `@nickoftime` handles in the Connect section |
| Beat list | Track names, BPM tags, and prices in the "Latest drops" section |

## Deploy

Any static host works — GitHub Pages, Netlify, Vercel, Cloudflare Pages. Upload the folder as-is.
