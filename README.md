# Modern Restaurant Landing Page Template

A single-page, responsive restaurant template built with **HTML + CSS + vanilla JavaScript**.

## Files

- `index.html` - page structure and content sections
- `styles.css` - visual design, layout, responsive breakpoints, and animations
- `script.js` - mobile navigation toggle, reveal-on-scroll effects, and form interaction

## Sections Included

- Hero section with name placeholder and full-width background image
- About section
- Menu highlights section
- Gallery section
- Reservation/contact section
- Footer with social links

## How to Use

1. Open `index.html` in your browser.
2. Edit text directly in `index.html` for your brand, menu, and contact details.
3. Replace image URLs in `index.html` (`hero-image` background in `styles.css`, gallery `<img>` URLs in `index.html`) with your own photography.
4. Adjust colors, fonts, spacing, and section styling in `styles.css` using the `:root` variables.
5. Update social links in the footer (`index.html`).

## Customization Guide

### 1) Restaurant name and hero text

Edit in `index.html` inside the `.hero-content` block:

- Main title in `<h1>`
- Supporting paragraph in `.hero-copy`

### 2) Hero background image

Edit in `styles.css` under `.hero-image`:

- Replace the `url(...)` value with your own image URL or local path.

### 3) Menu highlight cards

Edit the cards in `index.html` under `#menu`:

- Dish name in `<h3>`
- Description in `<p>`
- Price in `.price`

### 4) Gallery photos

Replace each `<img src="...">` inside `#gallery` in `index.html`.

Tip: keep landscape-oriented images for best layout consistency.

### 5) Reservation/contact details

Edit the `#reserve` section in `index.html`:

- Phone, email, address
- Form fields if needed

### 6) Social links

Edit footer links in `index.html` under `.social-links`.

## Notes

- The form is currently front-end only and shows a confirmation message via JS.
- For real reservations, connect the form to a backend/email service.
- Layout is fully responsive for desktop, tablet, and mobile.
