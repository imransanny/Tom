# TOMATO Clothing — Responsive Ecommerce Frontend

A multi-page fashion storefront based on the provided visual reference. The homepage uses cropped visual assets from the supplied screenshot to preserve the original styling; substitute original high-resolution product photography before launch.

## Run
Open `index.html` in a browser for the homepage. For working deep-page URLs (`/shop`, `/product/1`, `/about`), run a simple local server with SPA fallback. Using Node.js:

```bash
npx vite --host
```

Vite is configured below with the included `package.json`, and serves deep links with fallback to `index.html`.

## Features
- Responsive landing page matching the reference layout
- Product catalogue, category filters, sorting and search
- Product detail pages with size choices
- Add/remove/quantity in shopping cart, persistent with localStorage
- Wishlist persistent with localStorage
- Newsletter and contact form UI
- Shipping, returns, FAQ, privacy and terms placeholder pages

## Before production
This is **frontend only**, not a live commerce store. Wire up inventory, payment gateway, customer authentication, real order submission, transactional email, shipping and tax, consent/storage and a real newsletter provider. Replace sample products, contact number, prices, placeholder policies and low-resolution cropped images.
