# Acorn Taxis website (WordPress + Elementor)

Elementor build pack for **Acorn Taxis**, Tamworth — navy/gold, mobile-first, booking via Cab9 (no custom booker).

## Live booking URL

`https://booker.cab9.app?company=ACO&code=0951`

## WordPress setup (staging or live)

1. Install a light theme: **Hello Elementor** (recommended) or Astra.
2. Install plugins: **Elementor** (+ Pro if you have Theme Builder), **Contact Form 7** or Elementor Forms, **Yoast SEO** (or Rank Math).
3. Apply globals from [`design/elementor-globals.md`](design/elementor-globals.md).
4. Paste custom CSS from [`elementor/css/acorn-globals.css`](elementor/css/acorn-globals.css) into Elementor → Site Settings → Custom CSS (or Appearance → Customize → Additional CSS).
5. Build **Header** and **Footer** Theme Builder templates using [`elementor/header-footer/`](elementor/header-footer/).
6. Create pages from the sitemap; paste copy from [`content/pages/`](content/pages/).
7. Set menus, forms, map embed, reviews slot, and 301 redirects from [`docs/redirects.md`](docs/redirects.md).
8. Check unresolved items in [`CONTENT_FLAGS.md`](CONTENT_FLAGS.md).

## Design references (inspiration only)

- Tone: [Belper Executive Travel](https://www.belperexecutivetravel.co.uk/)
- Structure / CTAs: [Metro Cars](https://metro-cars.info/)

## Project structure

```
design/           Brand tokens & Elementor Site Settings
elementor/        CSS + header/footer build notes
content/pages/    Ready-to-paste British English page copy
content/blog/     Starter blog posts
docs/             Build checklist, redirects, SEO, forms
```

## Business facts (do not invent beyond these)

| Item | Value |
|------|--------|
| Company | Acorn Taxis |
| Address | 20 Lichfield St, Tamworth, B79 7QD |
| Phone | 01827 63333 |
| Email | acorntaxisltd@gmail.com |
| Hours | Open 24/7 |
| Established | 50 years |
| Fleet | Over 100 vehicles |
