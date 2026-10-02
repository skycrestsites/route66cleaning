# Route 66 Cleaning Co.

Marketing website for **Route 66 Cleaning Co.**, professional cleaning services in **Kingman, AZ & surrounding areas**.

🌐 [route66cleaningco.com](https://route66cleaningco.com)

## Overview

A fast, fully static, mobile-first website built with HTML + [Tailwind CSS](https://tailwindcss.com) (CDN). A clean light theme carries the logo's desert-sunset accents: gold, ember and flame gradients on white and warm linen.

## Pages

Each page lives in its own folder as an `index.html`, so it is served at a clean, extensionless URL on any static host.

| Page | URL | File |
| --- | --- | --- |
| Home | `/` | `index.html` |
| Residential Cleaning | `/residential-cleaning/` | `residential-cleaning/index.html` |
| Deep Cleaning | `/deep-cleaning/` | `deep-cleaning/index.html` |
| Recurring Cleaning | `/recurring-cleaning/` | `recurring-cleaning/index.html` |
| Move-In / Move-Out | `/move-in-out-cleaning/` | `move-in-out-cleaning/index.html` |
| Commercial Cleaning | `/commercial-cleaning/` | `commercial-cleaning/index.html` |
| Vacation Rental / Airbnb | `/airbnb-cleaning/` | `airbnb-cleaning/index.html` |

## Features

- 📱 Fully responsive / mobile optimized with a clean nav bar + mobile menu
- 🎨 Brand colors matched to the logo: gold `#FDB42D`, ember `#F7861F`, flame `#E8431F` over white `#ffffff` / linen `#faf6f1`, with ink `#1a1410` text
- 🔎 SEO: unique titles, meta descriptions, keywords, canonical URLs, Open Graph + Twitter cards, JSON-LD `CleaningService` schema
- 🔗 Clean, extensionless URLs (`/deep-cleaning/`) with no `.html` anywhere in the site
- 🧭 `sitemap.xml` + `robots.txt`
- 🖼️ Favicon set (32px, 256px), Apple touch icon, 512px PWA icon + `site.webmanifest`
- ⚡ Scroll-reveal animations and hover states

## Things to update before launch

- Replace the placeholder phone number `(928) 555-0166` with the real business line.
- Confirm the contact email `info@route66cleaningco.com`.
- Wire the contact / quote forms to a real backend or form service (currently front-end only).
- Swap the stock Unsplash imagery for real job photos when available.

## Local preview

Serve the folder rather than opening the files directly, so the directory-based URLs resolve:

```bash
npx serve .
```
