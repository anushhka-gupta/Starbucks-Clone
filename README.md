# Starbucks Coffee Company — Website Clone

A front-end clone of the Starbucks India website homepage, built with plain HTML and CSS. This project focuses on replicating the layout, visual hierarchy, and responsive behavior of the original site using semantic markup and a clean, component-based stylesheet.

## Preview

The page recreates the following sections from the Starbucks homepage:

- **Sticky Header** — logo, primary navigation, search box, and account icon
- **Green Promo Panel** — a slim announcement bar with a call-to-action
- **Favourites Banner** — hero-style promo card with a background image and carousel controls
- **Handcrafted Curations** — a row of circular category shortcuts (Bestseller, Drinks, Food, etc.)
- **Barista Recommends** — product cards with pricing and an "Add Item" action
- **Coffee Culture Spotlight** — a full-width feature banner with a hover overlay
- **Nutritional Disclaimer** — fine-print info section
- **Footer** — sitemap links, social media icons, app store badges, and legal links

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — Flexbox, CSS Grid, custom properties-free styling, and media queries for responsiveness
- **Font Awesome** — icon set (loaded via CDN)
- **Google Fonts** — Noto Sans typeface

No build tools, frameworks, or JavaScript are used — this is a pure HTML/CSS static page.

## Project Structure

```
.
├── index.html              # Main page markup
├── starbucks_clone.css     # All styling for the page
└── assets/                 # Images, icons, and logos used across the page
    ├── logo.png
    ├── search.svg
    ├── account_thin.svg
    ├── ASSET_aad6872b43.png
    ├── Bestseller.jpg
    ├── Drinks.jpg
    ├── Food.jpg
    ├── Merchandise.jpg
    ├── CoffeeAtHome.jpg
    ├── placeholder.svg
    ├── veg.svg
    ├── 100501.webp
    ├── greyleafright.svg
    ├── ICW_Live_Event_Day5_41f11ca3d2.jpg
    ├── instagram.svg
    ├── facebook.svg
    ├── twitter.svg
    ├── appstoreiOS.png
    └── appstoreAndroid.png
```

## Getting Started

No installation or build step is required.

1. Clone or download this repository.
2. Make sure the `assets/` folder sits alongside `index.html` and `starbucks_clone.css`.
3. Open `index.html` directly in any modern browser.

That's it — the page is fully static.

## Responsive Design

The layout adapts across four breakpoints to keep content readable on smaller screens:

| Breakpoint | Behavior |
|---|---|
| `≤ 1360px` | Hero banner text scales down, button positioning adjusts |
| `≤ 1024px` | Further text and button scaling for tablets |
| `≤ 768px` | Layout shifts to a stacked/centered flow; footer columns become a single column |
| `≤ 455px` | Fine-tuned spacing and font sizes for small mobile devices |

## Notes

- This project is built purely for **learning and portfolio purposes** (practicing HTML/CSS layout, Flexbox/Grid, and responsive design patterns).
- All Starbucks branding, imagery, and copy belong to Starbucks Corporation. This is an unofficial, non-commercial clone and is not affiliated with or endorsed by Starbucks.
- CSS selectors are kept intentionally shallow (scoped to the nearest unique class/ID) rather than deeply nested, to keep the stylesheet easier to read and maintain.

## Possible Next Steps

- Add JavaScript to make the carousel arrows, search box, and "Add Item" buttons functional
- Extract repeated card/button patterns into reusable CSS classes
- Add proper `alt` text coverage and ARIA labels for full accessibility
- Convert to a component-based framework (React/Vue) for larger-scale iteration
