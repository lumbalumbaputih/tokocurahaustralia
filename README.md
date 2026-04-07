# Toko Curah Australia

A responsive single-page landing site for **Toko Curah Australia (Shop with Alia)**, designed to promote trusted Australian products and direct customers to marketplace channels.

## Overview

This project is a lightweight static website built as one HTML file (`index.html`) with:

- Inline CSS (mobile-first responsive layout)
- Small vanilla JavaScript interactions
- No framework and no build step

## Features

- Hero section with brand messaging and CTA buttons (Tokopedia, Shopee)
- Responsive design for mobile, tablet, and desktop breakpoints
- Reviews/satisfaction section with:
  - 5-star visual highlight
  - review count stat card
  - swipeable review cards on mobile
- Simple scroll reveal animations using `IntersectionObserver`
- Footer with contact email and copyright

## Project Structure

```text
.
├── index.html   # Full page markup, styling, and behavior
└── README.md
```

## Run Locally

Because this is a static site, you can run it directly:

1. Clone/download the repository
2. Open `index.html` in your browser

Optional (recommended): use a local static server for testing:

```bash
python3 -m http.server 8000
```

Then open: `http://localhost:8000`

## Customization

Main areas to update in `index.html`:

- **Brand text/title**: `<title>`, hero heading, hero paragraph
- **Marketplace links**: replace `href="#"` in Tokopedia/Shopee buttons
- **Review content**: update review cards and total review count
- **Contact info**: footer email address
- **Theme colors**: CSS variables in `:root`

## Deployment

This site can be deployed to any static hosting platform (for example GitHub Pages, Netlify, Vercel static output, or shared hosting) by publishing `index.html`.

## Notes

- Fonts are loaded from Google Fonts (`Fredoka`, `Nunito`).
- Emoji and SVG visuals are used for simple decorative branding elements.
