# Header & Footer — Elementor Theme Builder

## Header (desktop)

**Structure (one horizontal container):**

| Left | Centre | Right |
|------|--------|--------|
| Site logo (link home) | Nav menu | Phone + Book Online |

**Settings**
- Background: Navy `#0B1F3A`
- Text / links: white
- Active link: Gold underline `#C4A35A`
- Sticky: yes (desktop)
- Padding: 12–16px vertical
- Logo height: ~40–48px

**Nav items (keep short)**
1. Home  
2. Services (dropdown — optional)  
3. Airport Transfers  
4. App  
5. Contact  
6. Become a Driver  

Or flatter: Home · Services · Airports · Vehicles · Contact · Drivers  

Always separate **Book Online** as a styled button (not a menu item of equal weight).

**Phone**
- Text: `01827 63333`
- Link: `tel:+44182763333`
- Visible on tablet+; on small phones rely on sticky bar

**Book Online button**
- Label: `Book Online`
- URL: `https://booker.cab9.app?company=ACO&code=0951`
- Target: `_blank` + `noopener noreferrer`
- Style class: `acorn-btn-primary`

## Header (mobile)

- Logo left
- Hamburger right
- Open drawer: same links + Book Online + Call Now at top of drawer
- Large tap targets (min 44px)

## Footer

**Background:** Navy Deep `#071627`  
**Text:** off-white / muted  

**Columns (4 → stack on mobile):**

1. **Acorn Taxis**  
   - Short line: Reliable taxis and private hire in Tamworth. Open 24/7.  
   - Address  
   - Phone + Email  

2. **Services**  
   - Airport Transfers  
   - Vehicles  
   - Account Facilities  
   - Journey Updates  
   - Pay Cash or Card  
   - Download Our App  

3. **Company**  
   - Areas Covered  
   - Become a Driver  
   - Blog  
   - Carbon Footprint  
   - Contact Us  

4. **Legal & social**  
   - Privacy Notice  
   - Data Protection Policy  
   - Facebook · Instagram · LinkedIn  
   - App Store badges  

**Bottom bar**
`© Acorn Taxis Ltd` + year  

## Sticky mobile CTA (HTML widget in Footer — sitewide)

```html
<div class="acorn-sticky-cta" role="navigation" aria-label="Quick booking actions">
  <div class="acorn-sticky-cta__inner">
    <a class="acorn-sticky-cta__call" href="tel:+44182763333">Call Now</a>
    <a class="acorn-sticky-cta__book" href="https://booker.cab9.app?company=ACO&code=0951" target="_blank" rel="noopener noreferrer">Book Online</a>
  </div>
</div>
```

Add CSS class / ensure `acorn-globals.css` is loaded.
