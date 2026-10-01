# BPLEX Leads — Kinetic Signal

BPLEX Leads is finalized on the **Kinetic Signal** landing-page design. The live site is the Kinetic Signal page at the repository root; the other concepts remain archived under `designs/` for reference.

**Company:** BPLEX Leads — lead sourcing, enrichment, and sales services.
**Contact:** [ammagsinoalvin@bplexleads.com](mailto:ammagsinoalvin@bplexleads.com)  
**Custom domain:** `bplexleads.com` is not configured on GitHub Pages yet.

## Structure

```
/
  index.html                          # Live Kinetic Signal site
  designs/
    01-midnight-pipeline/index.html   # Archived concept
    02-editorial-trust/index.html     # Archived concept
    03-kinetic-signal/index.html      # Archived source / reference
  README.md
```

The live root page has no design-picker bar. The archived design pages are retained as-is for reference.

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080/`.

## GitHub Pages

- **Source:** `main` branch, site root `/`
- **URL:** https://venthewise.github.io/bplexleads/

## Custom domain (later)

When ready for **bplexleads.com**, add it in **Repo Settings → Pages → Custom domain**, then configure the GitHub Pages DNS records at the DNS provider and enable HTTPS after propagation. Do not add a `CNAME` file until DNS is planned.

## Tech notes

- Static HTML + inline CSS; Google Fonts via `<link>`.
- No build step, no frameworks.
- Responsive and self-contained for GitHub Pages.

© BPLEX Leads
