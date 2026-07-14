# Research de Capitalé — Website

A single-page, self-contained website for **Research de Capitalé**, an independent investment and corporate finance research house.

Live everything — markup, styles, and behavior — lives in one file: `index.html`. No build step, no dependencies to install.

## Features

- Black-and-gold theme built around the firm's emblem logo (embedded inline, no external image files)
- Typeface: EB Garamond, loaded from Google Fonts
- Sections: hero, about, coverage, research (sample listing), footer with social links
- Custom gold cursor with a rotating ring and trailing glow (desktop only)
- Ambient drifting particle background (respects `prefers-reduced-motion`)
- Fully responsive layout for desktop, tablet, and mobile
- No build tools, frameworks, or package manager required

## Getting started

Clone the repo and open the file directly in a browser:

```bash
git clone https://github.com/<your-username>/research-de-capitale.git
cd research-de-capitale
open index.html   # or double-click the file
```

Because it's a static file, you can also serve it locally with any simple server, e.g.:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying

The site is a single static HTML file, so it works with any static host:

- **Netlify / Vercel** — drag and drop the folder, or connect the repo for automatic deploys
- **GitHub Pages** — enable Pages on this repo, pointing to the root of the default branch
- Any web server — just upload `index.html`

## Before going live — things to update

A few placeholders are left intentionally for you to fill in with real details:

| Location | What to change |
|---|---|
| Research section | Swap the 3 sample report cards for real titles, tags, dates, and abstracts |
| Footer | Replace the `#` links on the LinkedIn, X, and Instagram icons with your real profile URLs |
| Contact | Update the email address (`research@researchdecapitale.com`) if needed |
| Contact form | The form currently only shows a front-end success message — connect it to an email service, form backend, or CRM to actually receive submissions |
| Address | Add your real office address wherever a placeholder is shown |

## Notes

- Requires an internet connection to load Google Fonts (EB Garamond); for a fully offline version, self-host the font files instead.
- All visible on-page text is styled lowercase by design.

## License

Add your preferred license here (e.g. MIT, or "All rights reserved" for a private/commercial site).
