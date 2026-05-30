# Cherry Augusta | Single-Page Portfolio

Single-page personal portfolio website of Cherry Augusta, a London-based Software Engineer.

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

| Group | Projects | Screenshot coverage |
|-------|----------|---------------------|
| Flagship | Consumer Duty Evidence Engine | `case-detail-weak-support.png` |
| Flagship | Meridian Ledger | `grounded-answer-with-sources.png` |
| Flagship | Agentic Compliance Auditor | `finding-detail-side-by-side.png` |
| Flagship | AI Model Governance Workbench | `release-candidate-blocked.png` |
| Featured | Sentra Nexus | `command-center.png` |
| Featured | LawPulse | `frontend-selected-clause.png` |
| Featured | GreenOps | `frontend-dashboard.png` |
| Featured | TradeFlow | `frontend-dashboard.png` |
| Featured — MCP integration | Gmail MCP Server | 5 screenshots (see below) |
| Angular and contract-aware | EcoRoute LEZ Optimiser | — |
| Angular and contract-aware | PolicyPulse | — |

## Project Screenshots (Multi-Page Portfolio Evidence)

Screenshots are stored under `screenshots/<project-folder>/` relative to the repository root and embedded in the Projects section of `index.html` using semantic `<figure>` and `<img>` elements with descriptive alt text, `loading="lazy"`, and `decoding="async"`.

### consumer-duty-evidence-engine

| Filename | Description |
|----------|-------------|
| `case-detail-weak-support.png` | Case review screen showing evidence sufficiency states alongside structured assessment output for a regulated-style artefact |

### meridian-ledger

| Filename | Description |
|----------|-------------|
| `grounded-answer-with-sources.png` | Grounded answer view showing retrieved source documents displayed alongside the generated answer output |

### agentic-compliance-auditor

| Filename | Description |
|----------|-------------|
| `finding-detail-side-by-side.png` | Finding detail view showing side-by-side contradiction analysis with cited policy evidence and review controls |

### ai-model-governance-workbench

| Filename | Description |
|----------|-------------|
| `release-candidate-blocked.png` | Release candidate screen showing a blocked state with approval gate controls and visible audit history |

### sentra-nexus

| Filename | Description |
|----------|-------------|
| `command-center.png` | Command center view showing operational workflow metrics and constrained AI decision surfaces |

### lawpulse

| Filename | Description |
|----------|-------------|
| `frontend-selected-clause.png` | Contract review interface showing a selected clause with extracted detail and traceable inspection controls |

### greenops

| Filename | Description |
|----------|-------------|
| `frontend-dashboard.png` | Dashboard showing ESG reporting charts and carbon accounting KPI summaries |

### tradeflow

| Filename | Description |
|----------|-------------|
| `frontend-dashboard.png` | Dashboard showing arbitrage opportunities table and live market data for multi-source tracking |

### gmail-mcp-server

| Filename | Description |
|----------|-------------|
| `mcp-server-running.png` | Terminal showing the MCP server process running locally and ready to accept connections via stdio transport |
| `google-cloud-gmail-api-enabled.png` | Google Cloud Console confirming the Gmail API is enabled for the project |
| `google-oauth-client-config.png` | OAuth 2.0 client credentials configuration screen in Google Cloud Console |
| `claude-desktop-config.png` | Claude Desktop configuration file showing the MCP server entry |
| `smoke-test-success.png` | Terminal output confirming a successful smoke test against a live Gmail account |

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
├── assets/
│   └── og-preview.png
└── screenshots/
    ├── consumer-duty-evidence-engine/
    │   └── case-detail-weak-support.png
    ├── meridian-ledger/
    │   └── grounded-answer-with-sources.png
    ├── agentic-compliance-auditor/
    │   └── finding-detail-side-by-side.png
    ├── ai-model-governance-workbench/
    │   └── release-candidate-blocked.png
    ├── sentra-nexus/
    │   └── command-center.png
    ├── lawpulse/
    │   └── frontend-selected-clause.png
    ├── greenops/
    │   └── frontend-dashboard.png
    ├── tradeflow/
    │   └── frontend-dashboard.png
    └── gmail-mcp-server/
        ├── mcp-server-running.png
        ├── google-cloud-gmail-api-enabled.png
        ├── google-oauth-client-config.png
        ├── claude-desktop-config.png
        └── smoke-test-success.png
```

## GitHub Pages deployment

1. Push to the main branch
2. Go to the repository on GitHub
3. Click Settings → Pages
4. Under Build and deployment, select GitHub Actions
5. The workflow at `.github/workflows/deploy.yml` handles the rest

Live URL:
```
https://cherryaugusta.github.io/portfolio-single-page/
```

## Implementation notes

- Built with semantic HTML5, external CSS, and external JavaScript
- Sticky navbar with smooth-scroll and active-section highlighting via IntersectionObserver
- Fully responsive: desktop, tablet, and mobile
- Accessibility: skip link, ARIA labels, keyboard navigation, focus-visible styles, reduced-motion support
- Project screenshots embedded with `<figure>` and `<img>`, descriptive alt text, `loading="lazy"`, and `decoding="async"`
- Screenshot composite layout for Gmail MCP Server shows all five setup and verification steps as a main image above a four-tile strip
- Zero build step — pure static files, GitHub Pages compatible

## License

MIT License. See LICENSE for full details.