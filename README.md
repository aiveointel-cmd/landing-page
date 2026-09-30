# HoyoPay Telegram Landing Page

Cloudflare Pages-ready static landing page for:
https://t.me/hoyopay412

## Deploy on Cloudflare Pages

1. Create a GitHub repository.
2. Upload `index.html` (and `hoyopay-promo.png` if you want to keep the supplied visual).
3. In Cloudflare: Workers & Pages → Create application → Pages → Import an existing Git repository.
4. Production branch: `main`
5. Framework preset: None
6. Build command: `exit 0`
7. Build output directory: `.`
8. Deploy.

Cloudflare will provide a `*.pages.dev` URL.

## Meta Pixel

The page contains a commented Meta Pixel placeholder. Replace `YOUR_PIXEL_ID` with your real Pixel ID and uncomment the block before publishing.

The Telegram buttons also send a `Lead` event when the Pixel is active.

## Telegram destination

All CTAs currently point to:
https://t.me/hoyopay412
