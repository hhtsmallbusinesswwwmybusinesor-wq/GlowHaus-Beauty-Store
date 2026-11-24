# GlowHaus Beauty — combined catalogue

This rebuild includes all 153 NailNest product pictures and all 92 product listings/photos from the Aurora Hair & Beauty source catalogue, with the original image assets also preserved in `source-images/`.

## Open
Extract the ZIP and open `index.html` in a modern browser. The product images and catalogue are locally included. Google Fonts are optional; the page uses local font fallbacks if offline.

## Features
- 245 catalogue entries and associated product images
- Search and category filtering; name/price sorting
- Image zoom/viewer, responsive product cards
- Enquiry basket and WhatsApp enquiry flow
- No unconfirmed prices displayed as prices (these are marked Price on enquiry)

## Updating catalogue
Edit `products.js` (JSON array assigned to `window.STORE_PRODUCTS`). Product image paths are relative to the folder. Original image files are retained in `source-images/nailnest/` and `source-images/aurora/`.

This is an enquiry catalogue, not a payment processing/stock-management platform.
