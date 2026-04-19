Project: Happy New Year 2026 — For Radha

Version: 1.0.0
Date: 2026-04-19

Overview
- Purpose: A small, single-page interactive greeting site built as a personalized "Happy New Year 2026" card.
- Audience: Internal/personal recipients and company stakeholders who want a lightweight, shareable greeting micro-site.
- Scope: Client-side static HTML, CSS and images (no server-side components). Delivered as a simple static bundle.

Business / Company Purpose
- Demonstrates creative, design-first microsites that can be produced quickly for campaigns, events, and internal appreciation initiatives.
- Low-cost, brandable artifact suitable for sharing with customers, partners, or employees as part of seasonal outreach.
- Reusable patterns: hero/landing screen, modal greeting, image gallery, localized content blocks (shayari), and lightweight client interactions.

Value Proposition
- Fast to deploy: single static page with assets that can be hosted on any static host (S3, Netlify, Vercel, GitHub Pages).
- Brandable: colors, copy, and imagery can be swapped for other campaigns with minimal effort.
- Lightweight: no backend dependencies, minimal maintenance.

Repository Contents (high level)
- index.html — Main single-page application containing styles, markup and client interactions.
- img1.jpg ... img6.jpg — Assets used in the gallery.
- README.ms — (this file) company-level summary and instructions.

Quick Start (Local)
1. Clone the repository.
2. Open `index.html` in any modern browser (double-click or via a local static server).

Recommended local static server (optional):
- Python 3.x

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

Hosting and Deployment
- Preferred: Deploy as static site (GitHub Pages, Netlify, Vercel, AWS S3 + CloudFront).
- For GitHub Pages: push repository to a GitHub repo and enable Pages from the main branch.

Branding & Company Guidelines
- Replace title, greeting copy, and images to align with company tone and campaign goals.
- Use the company color tokens and logo in the `index.html` top-level style section for brand consistency.
- Keep font choices accessible and readable; follow company accessibility checklist (contrast, font sizes, focus states).

Security & Privacy
- No user data is collected by default. If you add a feedback or persistence feature, follow company data-handling and retention policies.

Accessibility
- Ensure images include descriptive `alt` text when replacing assets.
- If the site is repurposed for broader audiences, add keyboard navigation and ARIA attributes for interactive elements.

Customization Checklist (for productization)
- Update title and meta tags for SEO and campaign tracking.
- Add UTM parameters to any outbound links used in the campaign.
- Replace placeholder images and ensure copyright/permission for any external media.
- Add analytics if needed (company-approved provider only).

Maintenance & Ownership
- Suggested owner: Marketing / Creative Web Team (or designated campaign owner).
- Minor updates: update `index.html` and image assets; re-deploy to static host.

Contact / Support
- Primary contact: Name / Team — please replace with internal contact details.
- For production or hosting support, contact the Platform/Infra team.

License
- Default: Internal company asset. If open-sourcing, add an appropriate license file (e.g., MIT) and update this section.

Next Steps / Options
- (Optional) Convert styles to a company CSS framework or tokens for consistency.
- (Optional) Extract images and copy into a small CMS or static-data JSON for easier updates.

