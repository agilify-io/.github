# `.github` — Agilify GitHub org profile

This repo (`agilify-io/.github`) renders the **public organization profile** at
[github.com/agilify-io](https://github.com/agilify-io) from [`profile/README.md`](profile/README.md).

## ⚠️ Mirror rule (mandatory)

`profile/README.md` is the **GitHub mirror of the marketing landing page** (`site/index.html`,
deployed at `agilify.io`). The two present the **same content** — hero tagline, the services trio,
the Monetu / InvestDesk / Apura / Clioteca product grid (badges + descriptions), and the contact block.

**Any change to the site MUST be mirrored here in the same slice, and vice-versa.** The README is
markdown — no inline SVG / CSS / JS — so mirror the **content and intent**, not the literal HTML:

- Theme-aware logo via `<picture>` + the SVGs in [`profile/assets/`](profile/assets/)
  (`agilify-logo-dark.svg` for dark mode, `agilify-logo-light.svg` for light).
- Brand colors via shields.io badges (Monetu gold `d97706`, InvestDesk green `059669`, Apura purple `7c3aed`, Clioteca azure `2563eb`).

Full rationale: "Marketing site ⇄ GitHub org profile" rule in the platform `CLAUDE.md`.
