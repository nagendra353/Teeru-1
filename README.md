# Teeru — Salon Marketplace

React + Vite starter with salon discovery, service pricing, booking request flow, hairstyle reference selector and customer reviews.

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## GitHub / Cloudflare Pages
Push this folder to a GitHub repository. In Cloudflare Pages connect the repository and set build command `npm run build` and output directory `dist`.

## Important before public launch
- `src/data.js` contains sample salons, locations, prices, opening hours and hairstyle reference images. Replace with verified salon partner information.
- Bookings and reviews are stored only in browser localStorage. No salon receives the booking; there is no shared database, authentication, payment or notification system yet.
- Hairstyle preview is a reference selector with local photo upload, not an AI hair transformation. Connect a secure server-side image API to enable actual transformation. Never put private API keys in frontend code.
- The displayed time slots are sample UI options, not live availability. Add a backend and salon owner dashboard before accepting real reservations.
