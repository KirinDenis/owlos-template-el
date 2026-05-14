# owlos-template-el

A dark, glassmorphism-style **electrician / electrical services website template** —
single page, mobile-friendly, 100% self-contained, GDPR compliant out of the box.

> **Template demo** — replace all placeholder content (business name, phone, address,
> portfolio photos) before deploying as a real website.

---

## Features

- **Single page** — Hero, Services, About, Portfolio, Testimonials, Contact
- **Dark glassmorphism design** — electric blue accent (#0090ee), animated circuit-board background
- **Self-hosted fonts** — Inter (woff2, 400–800); zero requests to Google Fonts or any CDN
- **No analytics, no tracking** — zero external HTTP requests at page load
- **Real portfolio photos** — actual work photos included in `/images/` (replace with your own)
- **Demo disclaimer banner** — fixed-position notice with localStorage dismissal;
  remove the banner block before going live
- **MIT License** — use freely, replace `[Your Company Name]` in `LICENSE`

---

## File structure

```
index.html        — main website (edit this)
electro.html      — standalone circuit-board animation demo (background preview only)
images/           — portfolio photos; replace with your own
fonts/            — self-hosted Inter woff2 files
```

---

## Quick Start

1. Download or clone this repository
2. Open `index.html` in your browser — no build step required
3. Replace placeholder content:
   - Business name (search for `Elektro MH` / `Marek Horváth`)
   - Phone and email (search for `+421 911 000 000`)
   - Address (search for `Hlohovec`)
   - Portfolio photos in `images/` — replace with your actual project photos
   - Replace `© 2026 Your Company Name` in the footer
   - Remove the `<!-- Demo disclaimer -->` block (or dismiss it once — uses `localStorage`)
4. Deploy: upload all files to any static web host

---

## Browser Support

Chrome 90+, Firefox 88+, Safari 14+, Edge 90+.
Canvas background animation requires a GPU — degrades gracefully on older hardware.

---

## GDPR Notice

This template is designed for use in the EU/EEA and follows GDPR best practices:

- **Fonts** — fully self-hosted (woff2 in `/fonts/`); no Google Fonts CDN requests
- **No analytics** — no Google Analytics, Matomo, Hotjar, or similar scripts included
- **No tracking pixels** — no Facebook Pixel or third-party pixels
- **No contact form backend** — the contact form does not submit data anywhere
  in demo mode; connect your own backend, email service, or form provider

---

## Disclaimer

This is a **template** — a starting point for a real website. The business name, phone
numbers, address, and placeholder text are fictional. owlos.sk provides this template
as-is, with no warranty. The licensee is responsible for all content, legal compliance,
and data protection obligations of the deployed website.

---

## License

MIT License — see [LICENSE](LICENSE).
Replace `[Your Company Name]` in `LICENSE` with your actual company or personal name.

---

## Third-Party Credits

| Asset | License | Source |
|---|---|---|
| Inter | SIL Open Font License 1.1 | Rasmus Andersson |

---

Designed with ♥ by [owlos.sk](https://owlos.sk)
