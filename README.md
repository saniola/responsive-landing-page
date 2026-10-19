# Responsive Landing Page

A responsive multi-section landing page for a design/development studio, with a portfolio subpage, modal contact form, and mobile navigation menu.

## Features

- Hero, services, portfolio, team, and customers sections
- Portfolio subpage (`portfolio.html`) with project filtering markup
- Modal dialog with a contact form, toggled via `js/modal.js`
- Mobile navigation menu with open/close toggling via `js/mobile-menu.js`
- Responsive layout via CSS media queries (flexbox-based)

## Technology

- Semantic HTML
- CSS (flexbox, custom properties, responsive media queries)
- Vanilla JavaScript for modal and mobile menu interactions

## Project structure

```
index.html        Main landing page
portfolio.html     Portfolio subpage
css/
  normalize.css    CSS reset
  styles.css       Site styles
js/
  modal.js         Modal open/close logic
  mobile-menu.js    Mobile navigation toggle
images/            Site images and icon sprite
```

## Running

Open `index.html` directly in a browser, or serve the directory with any static file server, e.g.:

```
npx serve .
```
