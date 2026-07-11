# spillerstech.us

The product storefront for **Spillers Technology**, Joseph "Joey" Spillers'
independent software studio for IT operations. It is the suit-jacket counterpart
to the personal campfire at [spilloid.github.io](https://spilloid.github.io):
same builder, sharper product path.

The site presents the organization commercially: products sold and supported
directly, services offered, and clear contact channels.

## Structure

The page reads top to bottom as a storefront:

1. **Hero** — operator-first value proposition plus a live build-bench summary.
2. **Proof rail** — concise, sourced career and product evidence.
3. **Products** — real screenshots for the commercial headliners:
   - **AnchorDesk Hosting** — managed helpdesk hosting for MSPs and IT teams.
   - **ComFlow** — SIP voice reception; the line that answers our own phone.
4. **Method and services** — how operational pain becomes a reliable system.
5. **Open source** — direct download, source, issue, and contribution paths.
6. **Founder** — the human and professional proof behind the studio.
7. **CTA** — hire the builder, pilot the product, or open the PR.

No prices on the page by design — every deployment is scoped, so the CTA is
always "inquire within."

## Files

- `docs/` — static files served by GitHub Pages at
  [spillerstech.us](https://spillerstech.us) (Pages source: `main:/docs`,
  custom domain via `docs/CNAME`).
- `docs/index.html` / `docs/style.css` — the whole site. Plain HTML/CSS, no
  frameworks or build step.
- `docs/assets/` — product screenshots copied from the source repositories.
- `docs/404.html`, `docs/robots.txt`, `docs/sitemap.xml` — recovery and search
  basics for a production storefront.

## Stack

- HTML / CSS (Rokkitt + Lato via Google Fonts — same family as the campfire site)
- Feather Icons

## Local use

Open `docs/index.html` directly in a browser.

## Notes

- Tone is professional, concrete, and founder-led — receipts over adjectives,
  with enough personality to make the work memorable.
- Product claims are intentionally linked to source, releases, or working
  deployments. ComFlow is described precisely as a voicemail regulator, not a
  conversational AI receptionist.
- Self-hosted OpenReplay obscures form inputs, email addresses, and numbers.
- The playful personal brand lives at spilloid.github.io and links back here;
  the two sites deliberately share typography and the warm amber accent.
