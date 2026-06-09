# BabyEats Marketing Site

One-page landing site for the BabyEats iOS app.

## Stack
- Plain HTML/CSS — no build step, no framework
- Self-contained: all styles inline in `index.html`
- Hosted via GitHub Pages

## Local preview
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Structure
```
/
├── index.html              ← Single-page site (all CSS inline)
├── assets/
│   ├── icon.png            ← App icon (used in header + footer)
│   ├── favicon.png         ← Browser favicon
│   └── screenshots/        ← 6 in-app screenshots
└── README.md
```

## Sections
1. Hero — headline + screenshot + App Store CTA
2. Trust strip — WHO / AAP / ESPGHAN / EFSA / LEAP
3. Features grid — 6 cards
4. Showcase — 3 phone screenshots with captions
5. Science — clinical evidence list + screenshot
6. Pricing — Free Week 1 vs $9.99 Pro
7. Final CTA — dark-green banner with App Store button
8. Footer — Movement by Design Labs

## Deploy
Push to `main` and enable GitHub Pages in repo settings → Source: `main` / `(root)`.

Custom domain (optional): add a `CNAME` file with `babyeats.co` once DNS is configured.
