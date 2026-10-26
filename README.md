# Jasper Meyer — Living Impact Portfolio

A responsive personal website built around a living, evidence-based work journal. Static HTML, CSS, JS and structured JSON; no build dependency, backend, paid service, or API keys.

## Features
- Homepage and personal brand pillars
- Latest weekly-review dashboard with metrics and highlights
- Selected initiative cards
- Weekly timeline and impact methodology
- Collaboration section
- GitHub Pages deployment workflow

## Local preview
Run `python3 -m http.server 8080` from the repository root. Open `http://localhost:8080`.

## Publication
In GitHub Settings → Pages choose **GitHub Actions** as deployment source. Once deployed, the expected URL is https://itsjasperr.github.io/jasper-living-portfolio/ (verify the Actions result).

## Update the website each week
Edit `data/site.json` and create a PR:
- `week`: replace only with verified public-safe metrics and highlights.
- `journal`: prepend a short dated retrospective and retain older entries.
- `projects`: update links and project descriptions.
- `contactEmail`: add the email you're comfortable publishing; otherwise the copy button explains why it isn't available.

Review for confidentiality, actual attribution, payment details and sensitive organizational data before merging. The website does not connect automatically to Jira, GitHub, financial records or private systems.

## Next
Automate draft PR creation from vetted weekly review records, with a manual editorial approval step. Add longer case studies and custom-domain support after the first public launch.

## Status
MVP with illustrative reporting from October 2026. Portfolio-wide development metrics are not claims of personal code authorship. A successful GitHub commit does not automatically mean GitHub Pages was activated.
