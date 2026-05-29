# Cherry Augusta | Single-Page Portfolio

Single-page personal portfolio website for Cherry Augusta, a London-based Software Engineer.

## Live site

**[cherryaugusta.github.io/portfolio-single-page](https://cherryaugusta.github.io/portfolio-single-page)**

## GitHub and LinkedIn

- GitHub profile: [github.com/cherryaugusta](https://github.com/cherryaugusta)
- LinkedIn: [linkedin.com/in/cherry-augusta-3957a916](https://www.linkedin.com/in/cherry-augusta-3957a916)

## Portfolio focus

Python, Django, DRF, TypeScript, React, Angular, PostgreSQL, Redis, Celery, Django Channels, Docker, backend APIs, full-stack applications, workflow-heavy systems, and reviewable AI-assisted products.

## Page sections

| Section | Anchor |
|---------|--------|
| Hero | #hero |
| About | #about |
| Skills | #skills |
| Projects | #projects |
| Resume | #resume |
| Contact | #contact |

## Project groups shown

- **Flagship:** Consumer Duty Evidence Engine, Meridian Ledger, Agentic Compliance Auditor, AI Model Governance Workbench
- **Featured:** Sentra Nexus, LawPulse, GreenOps, TradeFlow
- **Angular and contract-aware:** EcoRoute LEZ Optimiser, PolicyPulse, FinCrime GraphOps, LondonPlan RAG
- **Supporting:** Python Contacts Manager, Advanced Python Calculator, GloBox A/B Testing Analysis

## Repository structure

```text
portfolio-single-page/
├── index.html
├── styles.css
├── script.js
├── README.md
├── LICENSE
├── .github/
│   └── workflows/
│       └── deploy.yml
└── assets/
    └── og-preview.png
```
## Local preview
Run from the repository root:
```
python -m http.server 8080
```
Open in browser:
```
http://localhost:8080
```
This is a long-running process. Press CTRL + C when you are finished previewing the site.

## GitHub Pages deployment
1.	Push to the main branch
2.	Go to the repository on GitHub
3.	Click Settings → Pages
4.	Under Build and deployment, select GitHub Actions
5.	The workflow at .github/workflows/deploy.yml handles the rest
Expected live URL:
```
https://cherryaugusta.github.io/portfolio-single-page/
```

## Implementation notes
•	Built with semantic HTML5, external CSS, and external JavaScript
•	Sticky navbar with smooth-scroll and active-section highlighting via IntersectionObserver
•	Fully responsive: desktop, tablet, and mobile
•	Accessibility: skip link, ARIA labels, keyboard navigation, focus-visible styles, reduced-motion support
•	Zero build step — pure static files, GitHub Pages compatible

## License
MIT License. See LICENSE for full details.

---
