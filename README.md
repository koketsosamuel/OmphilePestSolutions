# Omphile Pest Solutions

Astro static website for Omphile Pest Solutions.

## Production

- Domain: `https://pestsolutions.omphilebotshelo.co.za`
- Analytics: Umami via `https://umami.brightsync.co.za/script.js`
- Contact submissions: Brightsync Hub `https://hub.brightsync.co.za/api/contact-submissions`
- Deploy target: Cloudflare Workers static assets via Wrangler

## Commands

```sh
npm install
npm run dev
npm run build
npm run preview
```

`npm run build` runs `astro check` before generating the static site in `dist/`.
