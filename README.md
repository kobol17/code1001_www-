# Code1001 Compliance Solutions

This repository hosts the bilingual landing site for **Code1001 d.o.o.** (Rijeka, Croatia), focused on specialized consulting services for **ISO/IEC 27001 Certification**, **ISO/IEC 42001 (AIMS) Implementation**, and **NIS 2 Directive Implementation**.

The site leverages the credibility associated with three PECB certifications held by the Principal Consultant:
- ISO/IEC 27001 Lead Auditor (cert. #6068296-2025-11, KAB/UKAS/IAS accredited)
- ISO/IEC 42001 Lead Implementer (cert. #6864754-2025-12)
- NIS 2 Directive Senior Lead Implementer (cert. #3826054-2025-10)

## Site structure

| File | Purpose |
|---|---|
| `index.html` | English landing page (default) |
| `hr.html` | Croatian landing page |
| `privacy.html` / `privacy-hr.html` | GDPR Privacy Policy (EN/HR) |
| `legal-notice.html` / `legal-notice-hr.html` | Legal Notice / Impressum with full company registration data (EN/HR) |
| `404.html` | Custom 404 page |
| `assets/` | Logos, PECB badges, consultant photo (webp) |
| `sitemap.xml`, `robots.txt`, `CNAME`, `site.webmanifest` | SEO and deployment configuration |

## Deployment Instructions (GitHub Pages)

This site is designed to be easily deployed using GitHub Pages.

1.  **Clone the Repository:**
    ```bash
    git clone [repository-url]
    cd code1001-compliance-site
    ```

2.  **Verify Assets:**
    *   PECB badges (`badge-iso27001.webp`, `badge-iso42001.webp`, `badge-nis2.webp`), consultant photo (`consultant-photo.webp`), and logo (`logo-code1001.webp`) are already in the `assets/` folder. Replace if branding changes.

3.  **Commit and Push:**
    ```bash
    git add .
    git commit -m "Initial commit of compliance website"
    git push origin main
    ```

4.  **Activate GitHub Pages:**
    *   Go to your repository settings on GitHub.
    *   Navigate to the "Pages" section.
    *   Under "Build and deployment," select "Deploy from a branch" and choose the `main` branch and the `/ (root)` folder.
    *   Save the settings. Your site will be live shortly at `[your-username].github.io/code1001-compliance-site/`.

## Structure Highlights

*   **index.html / hr.html:** Each contains all HTML, structure, and embedded CSS for its respective language.
*   **Hero Section:** Highlights the tri-certification focus and displays the PECB credibility badges immediately.
*   **Consultant Profile:** Frane Karaman — mag. ing. el. (UNIZG FER 1989), 25 years C-level in NZ tech sector (Auckland), three PECB certifications.
*   **Service Pillars:** Dedicated sections explaining deliverables for ISO 27001, ISO 42001 (AIMS), and NIS 2.
*   **Why Us:** Tri-certified authority, integrated risk management, legal accountability focus, operation-first implementation.
*   **Legal compliance:** Bilingual GDPR Privacy Policy and Legal Notice / Impressum with full registration data per Croatian companies and e-commerce law.