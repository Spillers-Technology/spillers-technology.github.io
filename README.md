# spillerstech.us

The business storefront for **Spillers Technology** — the suit-jacket
counterpart to the personal campfire site at
[spilloid.github.io](https://spilloid.github.io). Same brand, after hours:
dark premium, embers traded for polish.

The site presents the organization commercially: products sold and supported
directly, services offered, and clear contact channels.

## Structure

The page reads top to bottom as a storefront:

1. **Hero** — value prop plus the two contact actions up front:
   `help@spillerstech.us` and `(260) 442-2113`.
2. **Products** — the commercial headliners, each with an inquire CTA:
   - **AnchorDesk Hosting** — managed helpdesk hosting for MSPs and IT teams.
   - **ComFlow** — SIP voice reception; the line that answers our own phone.
3. **Services** — custom internal tooling and automation consulting.
4. **Open Source** — RetroSpool, Partner Center Bridge, NetViz.
5. **Support** — existing customers file tickets via help@spillerstech.us,
   which lands in our own AnchorDesk queue.

No prices on the page by design — every deployment is scoped, so the CTA is
always "inquire within."

## Files

- `docs/` — static files served by GitHub Pages at
  [spillerstech.us](https://spillerstech.us) (Pages source: `main:/docs`,
  custom domain via `docs/CNAME`).
- `docs/index.html` / `docs/style.css` — the whole site. Plain HTML/CSS,
  no frameworks, no build step.

## Stack

- HTML / CSS (Rokkitt + Lato via Google Fonts — same family as the campfire site)
- Feather Icons

## Local use

Open `docs/index.html` directly in a browser.

## Notes

- Tone is professional, concrete, evidence-driven — receipts over adjectives,
  minus the dad jokes. One wink allowed in the footer.
- The playful personal brand lives at spilloid.github.io and links back here;
  the two sites deliberately share typography and the warm amber accent.
