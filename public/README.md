# Code1001 Compliance Solutions

This repository hosts the single-page website for Code1001, focused on specialized consulting services for **ISO 27001 Certification** and **NIS 2 Directive Implementation**.

The site heavily leverages the credibility associated with the PECB ISO 27001 Lead Auditor and NIS 2 Implementer certifications.

## Deployment Instructions (GitHub Pages)

This site is designed to be easily deployed using GitHub Pages.

1.  **Clone the Repository:**
    ```bash
    git clone [repository-url]
    cd code1001-compliance-site
    ```

2.  **Add Assets:**
    *   Place the actual image files for the PECB badges (`badge-iso27001.png` and `badge-nis2.png`) into the `assets/` folder. (Placeholder files are currently referenced).

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

*   **index.html:** Contains all HTML, structure, and embedded CSS.
*   **Hero Section:** Highlights the dual service focus and displays the PECB credibility badges immediately.
*   **Service Pillars:** Clear, dedicated sections explaining the deliverables for ISO 27001 and NIS 2.
*   **Expertise:** Emphasizes the "Lead Auditor" perspective, translating compliance into practical business value.