# The Handy Pair — landing page

Landing page for a family-run cleaning company in Northern Canada (Tanya & Igor).

The whole site is a single file: `index.html` at the repo root, served as-is by GitHub Pages.
Deep forest-green + milky-beige bands, soft gold accent, Newsreader serif display, soap-bubble decor,
a scroll-driven services ticker and an auto-sliding reviews carousel.

## Before launch — client data still needed

Everything below is marked with a `PLACEHOLDER` or `IMG DROP` comment in the source:

- **Photo of Tanya & Igor** — the hero bubble shows the logo until a real photo is dropped in.
- **Social profile URLs** — the social buttons stay hidden until real links exist.
- **Business email** — the form currently delivers to a developer inbox; no email is shown on the page.
- **Custom domain** — canonical and `og:url` point at the GitHub Pages address for now.

## Forms

The quote form posts to FormSubmit (no backend needed on GitHub Pages), with a native `action` fallback
so a lead still arrives if JavaScript fails. **The first real submission triggers a one-time activation
email to the destination address — the link in it must be clicked before leads are delivered.**
