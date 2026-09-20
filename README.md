# spillerstech.us

The product storefront for **Spillers Technology**, Joseph "Joey" Spillers'
independent software studio for IT operations.

The visual direction is **black-tie workshop**: satin-black surfaces, warm ivory,
champagne details, and an editorial rhythm around real product evidence. The site
stays connected to the amber personal brand at
[spilloid.github.io](https://spilloid.github.io), but it is product-first rather
than résumé-first.

## Page structure

1. **Hero** — the studio's purpose and a release-linked console of the five flagship downloads.
2. **Headliners** — AnchorDesk and ComFlow with real screenshots, plus Partner Center Bridge as a wide third feature; each states its license and maturity.
3. **More from the workshop** — NetViz (featured), SpoolSmith, RetroSpool, and OpsQuest, followed by an "Off the clock" strip for Corporate-Simulator and SpillerMug.
4. **Custom software** — the operational-workflow service offer, capability tags, and method.
5. **Founder** — a concise explanation of Joey's operator and engineering mix.
6. **Contact** — email, public source, and a disclosed ComFlow demo line.

Release links use GitHub's `/releases/latest` route instead of embedding version
numbers that immediately become stale. Every flagship is MIT-licensed; SpillerMug is
BSD-2-Clause. Public source is still described separately from open-source licensing
— check the repo's LICENSE before making a licensing claim about a new product.

## Product positioning

- **AnchorDesk** — MIT, self-hosted service desk with device and RMM context. Integration
  maturity is labeled per connector (Jira beta; ConnectWise, NinjaOne, Datto alpha).
- **ComFlow** — MIT (adopted in v4.0.0), self-hostable or multi-tenant voicemail workflow.
  A voicemail regulator, deliberately not an AI receptionist.
- **Partner Center Bridge** — MIT, pre-1.0. Core deploy/provisioning/Find User workflows are
  marked stable in the repo; workflows, mailbox repair, config snapshots, and MCP are beta;
  two-way LDAP sync is planned, not built.
- **NetViz** — 1.0. Windows (Authenticode-signed) and Linux downloads; no prebuilt macOS.
- **SpoolSmith** — 1.0. Windows CLI and desktop app, signed builds. The repo lives under
  the personal `spilloid` account, not the org.
- **RetroSpool** — pre-1.0; the capture/render pipeline, operator console, and public
  submission intake work. The queue poller and the S3/SFTP export fan-out are marked
  *planned* in the repo — say "planned, not built", not "in development".
- **OpsQuest** — public trial (Android APK on GitHub Releases).
- **Corporate-Simulator** — pre-1.0 replay MVP; live model seats are planned.
- **SpillerMug** — playable browser game.

## Files

- `docs/` — static files served by GitHub Pages from `main:/docs`.
- `docs/index.html` / `docs/style.css` — the complete storefront; no build step.
- `docs/assets/` — product screenshots (AnchorDesk, ComFlow, Partner Center Bridge, NetViz), the social card, and dependency-free
  interaction scripts.
- `docs/privacy.html` — plain-language disclosure for website replay and the
  ComFlow demo line.
- `docs/404.html`, `docs/robots.txt`, `docs/sitemap.xml`, and `docs/CNAME` —
  production recovery and search basics.

## Local use

```sh
python3 -m http.server 4173 --directory docs
```

Then open <http://127.0.0.1:4173>.

## Content guardrails

- Use **Spillers Technology** and **independent software studio**. Add “LLC” only
  after legal formation is effective, then update the legal identity everywhere
  together.
- Prefer direct release, source, or documentation links over unsupported metrics.
- Keep product maturity explicit and avoid guarantees broader than the underlying
  implementation.
- Screenshots use synthetic demo data; never publish tenant, customer, credential,
  or internal-topology data.
- The OpenReplay recorder (also used on spilloid.github.io) is loaded from OpenReplay's delivery network and sends
  data to the configured Spillers Technology ingest endpoint. Input values, email
  addresses, and numbers are configured to be obscured; the privacy page must stay
  linked whenever replay is enabled.
