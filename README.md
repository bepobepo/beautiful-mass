# Beautiful Mass

Company site for [BeautifulMass.ai](https://beautifulmass.ai) — helping NGOs and companies that don’t usually use technology become more agentic and AI-first.

The live page is static HTML and CSS at the repo root. Open `index.html` in a browser, or visit the GitHub Pages URL once it is enabled.

## Custom domain

This repo is set up for GitHub Pages with the custom domain `beautifulmass.ai` (see `CNAME`).

After Pages is on, point DNS at GitHub from the BeautifulMass.ai registrar:

- **Apex (`beautifulmass.ai`)** — A records to GitHub Pages IPs, or an ALIAS/ANAME if the registrar supports it
- **`www`** — CNAME to `bepobepo.github.io` (or the Pages URL GitHub shows)

GitHub lists the current A-record IPs under the repo’s Pages settings. HTTPS usually finishes after DNS has propagated.
