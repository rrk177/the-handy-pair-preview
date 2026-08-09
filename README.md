# The Handy Pair — landing page directions

Two live design directions for a family-run cleaning company in San Francisco (Igor & Tatyana).

Open `index.html` and use the switcher in the top bar. Each version is also a standalone page:

- **Final** → `final/index.html` — deep forest-green + milky-beige bands, Newsreader serif display,
  soap-bubble decor, scroll-driven services ticker, auto-sliding reviews carousel.
- **V2** → `v2/index.html` — bright off-white ground with one forest-green accent, Onest display type,
  rounded photo frames, bracketed section eyebrows, pill service tags with a green promo price card,
  scroll-driven "Where we clean" rail and a Process stepper that ticks green as you scroll.

The switcher remembers your last choice and accepts `?v=final` / `?v=v2` for sharing a direct link.

## Before launch — client data still needed

Everything below is marked with a `PLACEHOLDER` comment in the source:

- **Phone** — (236) 514-2372 is a British Columbia area code; an SF business needs a local 415/628 number.
- **Photos** — V2 has real photography; the Final version's image slots are still flat CSS stand-ins.
- **Licence number**, real Google Business profile URL, social profile URLs, business email.
- **Prices and figures** — the starting prices, "typical ≈ $X" anchors and stat numbers are samples.

## Forms

Both versions post to FormSubmit (no backend needed on GitHub Pages), with a native `action` fallback
so a lead still arrives if JavaScript fails. **The first real submission triggers a one-time activation
email to the destination address — the link in it must be clicked before leads are delivered.**
