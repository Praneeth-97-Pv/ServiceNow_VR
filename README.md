# Enterprise Vulnerability Management & Remediation Automation

A responsive ServiceNow VR project website with high-resolution diagrams.

## Files
- `index.html` — self-contained website with all five diagrams embedded. Uploading this file alone preserves every image.
- `assets/images/` — five individual high-resolution PNG diagrams for reuse (optional for website rendering).

## View locally
Open `index.html` in a web browser. No installation or build step is necessary.

## Publish to GitHub Pages
1. Create a repository in GitHub (prefer **private** until content has been reviewed and approved).
2. Upload **`index.html`** to the repository root. The images are embedded, so they display even if the `assets/` folder is not uploaded. You may also upload `assets/` to share the PNGs individually.
3. Commit the files.
4. In **Settings → Pages**, choose **Deploy from a branch**, select the `main` branch and `/(root)`, then Save (if Pages is available for your repository/account).
5. Open the URL GitHub provides for the published website.

GitHub's source-code preview does not render an HTML website. Use GitHub Pages or open `index.html` locally.

## Important before publishing
The supplied Word document contains references to UPS Security Operations and named scanner tools. Verify that the material is yours to publish and remove or anonymize any non-public employer, system, infrastructure, or security details. Do not publish credentials, internal hostnames, vulnerabilities, or private endpoints. GitHub Pages visibility can differ from repository visibility depending on plan/settings.

## Source fidelity
Text and diagrams are reproduced from the uploaded document. The original document includes references to Rapid7/Tenable in the overview while some figures use Qualys; this discrepancy has been preserved and should be checked before external publication.

## Screenshot troubleshooting
GitHub’s repository file view displays HTML source rather than rendering the page. Open the deployed GitHub Pages URL or open `index.html` in a browser. All diagrams are now embedded directly in the HTML.
