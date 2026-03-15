# RiskHarbor — Cyber Risk Assessment

> AI-powered small business cybersecurity risk assessment tool by Orcannus Technologies.

**Live demo:** https://orcannus.github.io/riskharbor

---

## What It Does

RiskHarbor is a free, browser-based cybersecurity risk assessment for small businesses. It:

- Collects business info (name, industry, size, contact, email)
- Walks the user through **24 questions** across **8 risk categories**
- Uses the **Claude AI API** to generate a personalized threat report
- Outputs a **branded PDF report** for download

### Risk Categories
1. Network & Infrastructure
2. Access Control
3. Data Backup & Recovery
4. Employee Awareness
5. Software & Patching
6. Incident Response
7. Physical Security
8. Compliance & Policy

---

## Deployment (GitHub Pages)

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your app is live at `https://yourusername.github.io/riskharbor`

No build step. No dependencies. Single HTML file.

---

## Tech Stack

- Vanilla HTML / CSS / JavaScript (zero framework)
- [Claude API](https://docs.anthropic.com) — AI threat analysis
- [jsPDF](https://github.com/parallax/jsPDF) — PDF generation
- Google Fonts (Inter + Space Grotesk)

---

## Customization

All content is in `index.html`. Key areas to edit:

| What | Where |
|------|-------|
| Brand name / logo | `<nav>` section + `downloadPDF()` function |
| Questions | `SECTIONS` array in `<script>` |
| AI prompt tone | `getAI()` function |
| PDF styling | `downloadPDF()` function |
| Colors | `:root` CSS variables |
| Footer links | `<footer>` section |

---

## Revenue Ideas

- **Email capture** — already built in; connect to Mailchimp / ConvertKit via Zapier
- **PDF gating** — require email before download (already structured for this)
- **Upsell CTA** — add a "Book a Free Consultation" button after results
- **White-label** — resell to IT consultants at $99–299/mo

---

## License

© 2025 Orcannus Technologies. All rights reserved.
