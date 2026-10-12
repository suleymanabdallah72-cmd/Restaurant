# Savanna Table — Restaurant Website (Concept)

A simple, responsive, single-page restaurant website built with plain HTML, CSS and JavaScript. No frameworks or build step.

**Savanna Table is a fictional restaurant** made as a web design portfolio piece. The address, phone, email and prices are placeholders.

## Features
- Sticky navigation and a warm, dark hero section
- Tabbed menu (Starters, Mains, Desserts, Drinks)
- Opening hours and location cards
- Reservation form with date validation (demo only, nothing is sent)
- Fully responsive for phones, tablets and desktops
- Form output is HTML-escaped to avoid injecting user input into the page

## Run locally
Open `index.html` in any browser. No install needed.

## Deploy on GitHub Pages
1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Source**, choose the `main` branch and the root (or `/restaurant`) folder, then save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/` (add `/restaurant/` if it sits in a subfolder).

## Make the reservation form real
The form currently only shows a confirmation message. To receive bookings, connect it to a form service (such as Formspree or Netlify Forms) or your own backend, and validate the data on the server.

## Customise
- Change colours in the `:root` block at the top of `index.html`.
- Edit menu items inside the `<div class="menu">` sections.
- Replace the placeholder contact details in the "Find Us" card.

## Author
Designed and built by Suleiman Saidi Abdallah.
