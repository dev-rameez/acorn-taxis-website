# Elementor page recipes (simple layouts)

Use the same spacing: 64px desktop / 40px mobile section padding. Max width 1140px.

Fonts: **DM Sans** (headings) + **Source Sans 3** (body). Colours from `design/elementor-globals.md`.

## Standard inner page
1. Page hero: H1 + 1 short paragraph on navy band (optional subtle gold accent shape)
2. Content sections (H2 + text + optional image)
3. CTA band (navy background): Book Online + Call

## Home
Follow section order in `content/pages/home.md` — one Elementor Container per section.

Hero budget: brand name (Acorn Taxis) + H1 + one short supporting line + Book / Call only. Move trust stats to Why Acorn.

## Motion Effects (optional, match preview)

| Moment | Elementor setting |
|--------|-------------------|
| Hero widgets | Entrance: Fade In Up, duration ~600ms, slight stagger |
| Section titles / service rows | Entrance: Fade In Up on scroll |
| Primary buttons | Rely on `acorn-globals.css` hover lift |

Disable all entrance animations when **prefers-reduced-motion** is on (or rely on the CSS reset in `acorn-globals.css`).

## Do / Don’t
| Do | Don’t |
|----|--------|
| 1–2 columns | 4+ competing columns on mobile |
| One primary button per section | Three gold buttons side by side |
| Real UK photography | Neon gradients / glassmorphism / Unsplash filler |
| Linked service list or light tiles | Heavy bordered card grids everywhere |
| CF7 or Elementor Form with labels | Fake fare widgets |
| Cab9 link in new tab | Homemade booking calendar |
| Confident Book Online handoff panel | Dashed “placeholder” boxes for conversion |
