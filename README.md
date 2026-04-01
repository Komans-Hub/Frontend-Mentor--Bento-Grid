# Bento Grid

A lightweight responsive landing section built with HTML and CSS. This project demonstrates a modern, card-based grid layout (Bento-style) with distinct feature panels, mobile-first design, and smooth desktop reflow at larger breakpoints.

## Project structure

- `Index.html` - main markup for the 8-section Bento grid
- `Style.css` - styling for responsive grid layout and component cards
- `random.txt` - (unused / placeholder file)

## Technologies

- HTML5
- CSS3
- CSS Grid
- CSS variables
- Responsive media queries

## Features

- Mobile-first single-column layout
- Two-column layout from `768px`
- Four-column grid with named template areas from `1100px`
- Eight semantic sections (hero, multi-account, schedule, optimization, growth, stats, creator, AI writer)
- Gradient backgrounds per card with consistent rounded corners and shadows
- Accessible `aria-label` usage for semantic sections

## Local setup

1. Open `Index.html` in a browser.
2. Optional: use Live Server (VS Code) to view on local dev server.

## Customization

- Tailor color palette inside CSS variables in `:root`
- Adapt container orders and spans in `@media (min-width: 1100px)` template grid
- Add/remove sections by editing markup inside `main.container`

## Notes

- Image assets are referenced as `illustration-*.webp`; ensure files exist in the project folder or replace them with your own.
- `.container-5` has custom large-device styling in the `@media (min-width: 1100px)` rule to emphasize growth panel layout.

## Licence

MIT