# Elementor Site Settings — Acorn Taxis

Apply in **Elementor → Site Settings**.

Working modern palette (pending final brand pack — see `CONTENT_FLAGS.md`).

## Global colours

| Name | Hex | Use |
|------|-----|-----|
| Navy | `#0B1F3A` | Header, primary text accents, dark bands |
| Navy Deep | `#071627` | Footer, sticky bar background |
| Gold | `#D4A84B` | Primary buttons, accents, underlines |
| Gold Soft | `#E0BA63` | Hover states |
| Off White | `#F5F7FA` | Page backgrounds, alternating sections |
| Surface | `#FFFFFF` | Content boxes, light sections |
| Charcoal | `#1C1C1C` | Body text |
| Muted | `#5C6570` | Secondary text |
| Border | `#D8DEE6` | Dividers, light borders |

**Avoid:** bright yellow from the old site, neon accents, purple SaaS gradients, warm cream + serif brochure looks, glassmorphism.

## Global fonts

| Role | Suggested font | Fallback |
|------|----------------|----------|
| Primary (headings) | `DM Sans` | system-ui, sans-serif |
| Secondary (body) | `Source Sans 3` | system-ui, sans-serif (Georgia optional for legal only) |

Weights: headings 700; body 400–500. Headings use slight negative letter-spacing.

### Typography scale (desktop → mobile)

| Style | Desktop | Mobile |
|-------|---------|--------|
| H1 | 48–56px | 38–40px |
| H2 | 32–38px | 27px |
| H3 | 22px | 20px |
| Body | 18px | 16–17px |
| Small | 14–15px | 14px |

Line height body: ~1.6. Section max width: **1140px**.

## Buttons

### Primary — Book Online
- Background: Gold `#D4A84B`
- Text: Navy Deep `#071627`
- Hover: Gold Soft `#E0BA63`
- Padding: 14px 28px
- Border radius: 4px (not pill)
- Font: DM Sans 700
- Link: Cab9 booker, open in new tab
- Min height: 52px (touch-friendly)

### Secondary — Call Now
- Background: transparent or white
- Border: 2px solid Navy
- Text: Navy
- Hover: Navy fill, white text
- Link: `tel:+44182763333`

### Ghost on dark
- Border/text: white or gold
- Used on navy bands / sticky bar

## Spacing rhythm

- Section padding: 64px desktop / 40px mobile (vertical)
- Gap between title and body: 12–16px
- Gap before CTAs: 24px
- Hero: brand name + one headline + one short line + Book/Call only (no stat pills in first viewport)

## Motion (Elementor)

Optional Motion Effects / entrance animations to match the preview:

1. **Hero content** — Fade In Up on load (duration ~600ms, staggered if using multiple widgets)
2. **Section titles / service rows** — Fade In Up on scroll (threshold mid-viewport)
3. **Buttons** — slight translateY on hover via custom CSS in `acorn-globals.css` (already included)

Always respect **prefers-reduced-motion**: disable entrance animations in Elementor responsive settings or via the CSS reset in `acorn-globals.css`.

## Inspiration mapping (do not copy)

| From Belper | Apply as |
|-------------|----------|
| Dark restrained header | Navy header, calm type |
| Executive calm | Short copy, generous but controlled spacing |
| From Metro | Apply as |
| Clear Book / Call | Always-visible booking + phone |
| Service blocks | Simple 3–6 item grid / linked list |
| App focus | Dedicated app section / page |
