# Lokesh Yadav — Portfolio

A single-page, animated portfolio site for **Lokesh Yadav**, a graphic designer specializing in healthcare & wellness visual communication — with a data science background that shapes how he approaches clarity and visual storytelling.

🔗 **Live site:** _add your GitHub Pages link here once deployed_
👤 **GitHub:** [github.com/LokeshYadav631](https://github.com/LokeshYadav631)

---

## About

This portfolio positions Lokesh at the intersection of **design and data** — a designer who can turn complex, technical information (clinical charts, data dashboards, model results) into visuals a non-technical audience can actually understand. It's built as a single self-contained HTML file, so it's easy to host, share, or download.

## Features

- **Animated hero** — a hand-drawn heartbeat/ECG line (tying into the healthcare focus) that draws itself in on load, plus a gradient scroll-progress bar
- **Colorful, brand-accurate design system** — accent colors are drawn from real issuer branding (Canva's gradient, Microsoft blue, Deloitte green, BCG X teal, Tata blue, etc.) rather than arbitrary decoration
- **Verifiable certifications** — every certificate (Canva Design School, Microsoft/NSQF, Skill India, Forage job simulations, MNIT Jaipur, Thiranex) is embedded as an actual image. Click any certification card to open the real document full-size in a lightbox
- **Scroll-triggered timeline** — a chronological timeline of data & AI certifications that animates into view as you scroll
- **Sections:** Hero · About · Skills · Certifications · Experience · Selected Work · Education · Contact
- **Fully responsive** — works on mobile, tablet, and desktop
- **Respects `prefers-reduced-motion`** for accessibility
- **Zero build step, zero dependencies** — one HTML file, fonts loaded from Google Fonts, everything else is vanilla CSS/JS

## Tech Stack

- HTML5, CSS3 (custom properties, grid, keyframe animations)
- Vanilla JavaScript (IntersectionObserver for scroll reveals, no frameworks)
- Google Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces) (display serif) + [Work Sans](https://fonts.google.com/specimen/Work+Sans) (body)

## File Structure

```
.
├── index.html      # the entire site — markup, styles, and scripts in one file
└── README.md       # this file
```

> Note: certificate images are embedded directly in `index.html` as base64 data URIs, so there are no separate image assets to manage or link.

## Running Locally

No build tools or dependencies required — just open the file in a browser:

```bash
git clone https://github.com/LokeshYadav631/<your-repo-name>.git
cd <your-repo-name>
open index.html   # or double-click the file
```

## Deploying to GitHub Pages

1. Rename the portfolio file to `index.html` (if it isn't already) and push it to a repository.
2. In the repo, go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder, then save.
4. Your site will be live at `https://LokeshYadav631.github.io/<your-repo-name>/` within a few minutes.

## Content Overview

| Section | What's there |
|---|---|
| **About** | Profile summary, quick facts, core strengths |
| **Skills** | Design software, web & visual tech, design fundamentals |
| **Certifications** | 4 design certifications (Canva Design School ×3, Forage Branding & Design) + 10 data/AI certifications (Microsoft, Skill India/NASSCOM, Forage ×7) shown as a timeline |
| **Experience** | Research Internship — MNIT Jaipur (2025); Virtual Internship — Thiranex (2026), each with the original certificate embedded |
| **Selected Work** | College Website Design, Breast Cancer Classification Visual Reporting, Voice Assistant Application, Data Cleaning & Visualization |
| **Education** | Bachelor of Data Science, Tribhuvan College — Nalanda University Centre |

## Contact

- **Email:** lokeshyadav826943@gmail.com
- **Phone:** +91 98870 87343
- **Location:** Neemrana, Rajasthan
- **GitHub:** [github.com/LokeshYadav631](https://github.com/LokeshYadav631)

---

*Open to freelance projects, internships, and entry-level design roles — especially in healthcare and hospital settings.*
