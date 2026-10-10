# Smoked Delights BBQ

Website for **Smoked Delights BBQ LLC**, a family owned BBQ catering business in Norco, CA (est. 2020).

- Phone: (951) 588-7901
- Email: smokeddelightsbbq@gmail.com
- Instagram: [@smokeddelightsllc](https://www.instagram.com/smokeddelightsllc/)

## What's here

A single-page static site. There's no build step.

| Path | What it is |
|---|---|
| `index.html` | The whole site (HTML, CSS and JavaScript in one file) |
| `images/` | Web-sized photos and the logo |
| `img/` | Favicons and the Apple touch icon |
| `favicon.ico` | Browser tab icon |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

## Sections

Home, About, Services, Menu (Barbecue, Mexican, Lunch & Grill, Apps/Sides/Desserts), Gallery, Booking, Reviews, Contact.

The booking form doesn't need a backend. It opens a text message to (951) 588-7901 with the customer's event details filled in.

## Editing

- **Text and menu items:** edit `index.html` directly. Each section starts with a comment like `<!-- MENU -->`.
- **Photos:** replace a file in `images/` and keep the same name, or add a new one and update its `src` in `index.html`. Keep photos around 1600px wide or less so the site loads fast on phones.
- **Preview locally:** open `index.html` in a browser.

## Hosting

Hosted on GitHub Pages from the `main` branch (Settings → Pages).

To use a custom domain, add a `CNAME` file containing the domain (for example `smokeddelightsbbq.com`) and point the domain's DNS to GitHub Pages.

Live at https://smokeddelightscatering.com

## Credits

The layout is adapted from [AR-Catering-service](https://github.com/fearswag1106/AR-Catering-service) by fearswag1106, used with permission. Photos and menus are provided by Smoked Delights. Reviews are quoted from Yelp.

Built by Howe Digital.
