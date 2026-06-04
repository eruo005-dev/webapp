# WebApp — Web Design & App Development Studio

The official marketing website for **webapp.com.ng**, a Nigerian studio building fast, modern websites and mobile apps.

## Overview

A single-page, fully responsive site built as one self-contained `index.html` (no build step) using:

- **Tailwind CSS** (CDN) + **Plus Jakarta Sans**
- Dark, modern aesthetic with glassmorphism, an animated gradient-mesh background and film grain
- Custom AI-crafted SVG illustration and brand logo
- Scroll-reveal animations, hover micro-interactions, and `prefers-reduced-motion` support

### Sections
Hero · Client marquee · Services · Process · Work · Testimonials · About · Pricing · FAQ · Contact

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire website |
| `logo.svg` / `logo.png` | Full logo, light/white wordmark (for dark backgrounds) |
| `logo-dark.svg` / `logo-dark.png` | Full logo, dark wordmark (for light backgrounds) |
| `logo-icon-1024.png` | Icon-only mark (social avatar, print) |
| `favicon.svg` | Browser tab icon |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` | PWA / mobile home-screen icons |
| `site.webmanifest` | PWA manifest |

## Run locally

It's a static site — open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8137
# then visit http://localhost:8137
```

## Deploy

Upload all files to your host's web root, or deploy to any static host (Netlify, Vercel, Cloudflare Pages, GitHub Pages).

## To-do before going fully live

- Replace placeholder testimonials, client names and stats with **real** ones
- Confirm pricing matches your actual rates
- Wire the contact form to an email service (e.g. Formspree / Web3Forms) so submissions reach `contact@webapp.com.ng`

---

Contact: **contact@webapp.com.ng** · WhatsApp **+234 903 771 5505**
