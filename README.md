# URBAN HARDWARE

Mobile-friendly bilingual (Hindi/English) shopping storefront for the Urban Hardware shop in Ludhiana, Punjab.

## Run locally
Open `index.html` in a browser. No build step is required.

## Publish with GitHub Pages
1. Create a **new public repository** named `urban-hardware`.
2. Upload all files and folders from this project (keep `index.html` at repository root).
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main`, folder `/ (root)`, then Save.
6. Wait for the Pages URL shown on that screen.

## Current functionality
- Responsive product storefront, search and category filters.
- Hindi/English interface toggle.
- Cart, customer checkout and COD order handoff to WhatsApp.
- Browser-local product management and order list in demo admin.
- Admin demo PIN is `2468`.

## Important production limitations
This is a front-end starter/demo. `localStorage` data is stored only in the current browser and is not shared between customers or devices. The admin PIN is visible in client-side JavaScript and is **not secure**. Do not use this demo admin for confidential or production administration.

Online payments are deliberately disabled. A real payment gateway requires a backend/serverless function and verified payment webhooks. Real shared orders, secure admin login, stock sync and order history also require a database/backend (for example, Supabase/Firebase plus server-side access rules). GitHub Pages alone cannot securely provide these services.

## Before publishing
- Change `ADMIN_PIN` in `app.js` only for a temporary private demo; this does not make it secure.
- Replace starter products/prices and add your own product photos.
- Confirm WhatsApp number and delivery policy.
- Add a backend before accepting real online payments or relying on shared order records.
