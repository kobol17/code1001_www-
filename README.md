# Code1001 — Engineering & Applied R&D

Bilingual landing site for **Code1001 d.o.o.** (Rijeka, Croatia), an engineering and applied-research studio working with **international clients in digital health**.

Two pillars:

- **Product engineering** — privacy-first digital-health platforms that clinical and wellness providers deploy to real users.
- **Applied R&D** — research into how digital interventions can deliver measurably better patient outcomes.

The site is intentionally lean: hero + a single "What we do" section + footer.

## Site structure

| File | Purpose |
|---|---|
| `index.html` | English landing page (default) |
| `hr.html` | Croatian landing page |
| `privacy.html` / `privacy-hr.html` | GDPR Privacy Policy (EN/HR) |
| `legal-notice.html` / `legal-notice-hr.html` | Legal Notice / Impressum with full company registration data (EN/HR). Retains the managing director as legally required for a Croatian Impressum. |
| `404.html` | Custom 404 page |
| `assets/` | Logo (webp). *(Legacy certification-badge and consultant-photo images remain in the folder but are no longer referenced by any page.)* |
| `sitemap.xml`, `robots.txt`, `CNAME`, `site.webmanifest` | SEO and deployment configuration |

## Deployment (GitHub Pages)

Static site deployed via GitHub Pages from the repository root.

1. Commit and push to the deployment branch.
2. In **Settings → Pages**, choose "Deploy from a branch," select the branch and the `/ (root)` folder, and save.
3. Custom domain configured via `CNAME` (`code1001.eu`).
