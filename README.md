# Hotel de Orashi

Landing page for Hotel de Orashi — a lounge, restaurant, and hotel. Static HTML/CSS site with a home page featuring the logo, a "Luxury Redefined" tagline, and a featured menu grid, plus a bottom navigation bar for Home, Food, Drinks, Rooms, and Contact.

## Structure

- `index.html` — main page markup
- `styles.css` — primary stylesheet (hero, featured menu grid, bottom nav)
- `ivotel.css` — extended design system styles (gold text effects, menu/cart/modal components) for future pages
- `images/` — logo and food/drink photos referenced by `index.html`
- `menu-data.md` — full food & drinks menu reference, used to build out remaining pages (Food, Drinks, Cocktails, etc.) one section at a time

## Development

This is a static site with no build step — open `index.html` directly in a browser, or serve the folder with any static file server.

## Deployment

Deployed on [Vercel](https://vercel.com), connected to this GitHub repository. Pushes to `main` trigger a redeploy.
