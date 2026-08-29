# anantyaveda.in

Static website for the domain **[anantyaveda.in](https://anantyaveda.in)**.

> ⚠️ Status: **Under construction.** A placeholder landing page is currently deployed; the full site is yet to be built.

## About

This repository hosts the static site served at `anantyaveda.in`. It is a plain HTML/CSS site (no build step required) published via GitHub Pages.

## Contents

| File | Purpose |
|------|---------|
| `index.html` | The landing page (currently an "under construction" placeholder). |
| `CNAME` | Tells GitHub Pages to serve the site at the custom domain `anantyaveda.in`. |
| `README.md` | This file. |

## Local development

The site is static — open `index.html` directly in a browser, or serve it locally:

```bash
# Python
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

The site is served by GitHub Pages from the `main` branch at the repository root.

> **Note:** GitHub Pages for organization-owned repositories requires the organization to be on a paid plan. If Pages is not active for this repo, the site can alternatively be published from a personal-account mirror or an external static host (Cloudflare Pages / Netlify).

## Custom domain

DNS for `anantyaveda.in` should point at GitHub Pages:

- **A records** (root `@`): `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- **CNAME** (`www`): `tumbudu.github.io`

Do not edit or delete the `CNAME` file — GitHub uses it to map the domain to this repository.

## License

All rights reserved. © anantyaveda.in
