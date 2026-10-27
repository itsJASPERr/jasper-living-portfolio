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

## Integrated identity and living storytelling (October 27, 2026)

**Primary positioning:** Connecting worlds. Creating possibilities.

The public site joins three distinct layers:
1. **Identity (slow-moving):** Jasper's personal story, values and four connected fields—technology & AI, land & regeneration, culture & medicine music, and consciousness & personal integration.
2. **Living storytelling (frequently updated):** verified project outcomes, field work, music/craft practice and reflections on what was learned. Keep agency and people central; do not frame team output as personal authorship.
3. **Invitations (actionable):** audience-specific ways to discuss a digital product, a regenerative partnership, music/circles/craft, or reflective personal coaching.

### Editorial checklist for every public story

- What happened, and what can be verified? Distinguish a decision, prototype, launched feature and validated adoption.
- Why does it matter to people, place or purpose? Add a reflection in Jasper's actual voice.
- What did we learn or what remains uncertain? Publish uncertainty when material.
- What could the reader explore, contribute to or ask about? Avoid generic sales language.
- Is it safe to publish? Do not expose Jira internals, credentials, financial data, participants or sensitive ceremonial/integration experiences. Request explicit consent before using another person's identifiable story or image.
- Maintain parity between `data/site.json` and `data/es.json`, including all project and journal updates.
- Favor Jasper's own documentary images, music, artwork and project evidence as they become available. Until then, the site's images remain illustrative.

### Distinct collaboration audiences

- **Technology:** founders and small organizations seeking product strategy, AI workflows or modular systems.
- **Regeneration:** land stewards, regenerative venues, local communities and project partners.
- **Music and circles:** event hosts and participants interested in medicine music, ceremonial drums or sharing circles.
- **Personal reflection:** people seeking conversation or non-clinical coaching around consciousness and integration, including entheogenic experiences. Never advertise substance access, clinical services, guaranteed outcomes or an unverified qualification.

The public site uses client-side contact prompts; no lead data is stored or submitted to a server. Email and WhatsApp are opened only when the visitor explicitly chooses them. This is a static site with no backend.

### Identity versus evidence

Brand discovery is the authoritative source of personal positioning, while weekly reviews supply verified, public-safe evidence. Revisit the editorial framing as the personal discovery progresses, but do not fabricate biographical turning points, testimonials, therapeutic credentials or project results.
