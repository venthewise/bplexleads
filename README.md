# BPLEX Leads — Landing design options

Three mutually distinct, production-ready landing pages for **BPLEX Leads**, plus a design picker hub so you can compare and finalize one look for the live site.

**Company:** BPLEX Leads — lead processor (sourcing, enrichment, sales services).  
**Contact:** [ammagsinoalvin@bplexleads.com](mailto:ammagsinoalvin@bplexleads.com)  
**Domain (later):** bplexleads.com (not configured on Pages yet)

## Structure

```
/
  index.html                          # Design gallery / picker hub
  designs/
    01-midnight-pipeline/index.html   # Cinematic dark B2B
    02-editorial-trust/index.html     # Light editorial / consulting
    03-kinetic-signal/index.html      # Bold modern kinetic
  README.md
```

Each landing page includes a fixed bottom **Design picker** bar (Design 1 / 2 / 3 / Hub).

## Designs at a glance

| # | Name | Art direction |
|---|------|----------------|
| 01 | **Midnight Pipeline** | Deep navy/black, electric teal, data-grid, glass cards, Space Grotesk — luxury SaaS |
| 02 | **Editorial Trust** | Cream/charcoal, warm gold, Cormorant serif headlines — premium magazine consulting |
| 03 | **Kinetic Signal** | Near-black, vivid coral/magenta, oversized Syne type, asymmetric — high-energy B2B |

## Local preview

Open any HTML file in a browser, or from this folder:

```bash
# Python
python3 -m http.server 8080

# or npx
npx --yes serve .
```

Then visit `http://localhost:8080/` for the hub.

## GitHub Pages

- **Source:** `main` branch, site root `/`
- **URL:** https://venthewise.github.io/bplexleads/
- Hub: https://venthewise.github.io/bplexleads/
- Design 01: https://venthewise.github.io/bplexleads/designs/01-midnight-pipeline/
- Design 02: https://venthewise.github.io/bplexleads/designs/02-editorial-trust/
- Design 03: https://venthewise.github.io/bplexleads/designs/03-kinetic-signal/

## Finalize one design

1. Browse all three via the hub or the bottom picker.
2. Tell the team which design wins.
3. That design’s `index.html` can be promoted to the repo root (replacing the gallery) for the live site.

## Custom domain (later)

When ready for **bplexleads.com**:

1. In repo **Settings → Pages → Custom domain**, add `bplexleads.com` (and optionally `www`).
2. At your DNS provider, add the GitHub Pages records (A/AAAA or CNAME) per [GitHub Docs](https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site).
3. Enable HTTPS once DNS propagates.

Do not add a `CNAME` file until DNS is planned.

## Tech notes

- Static HTML + inline CSS; Google Fonts via `<link>`.
- No build step, no frameworks.
- Responsive and self-contained for GitHub Pages.

© BPLEX Leads
