# Web Analytics Lab

## Overview
Web Analytics Lab is a marketing analytics portfolio project built on my live personal website, [quinnreams.com](https://www.quinnreams.com/). The goal of this project is to measure how visitors interact with my portfolio, track meaningful career-intent actions, and establish a clean baseline for future optimization.

## Business Problem
After relaunching my portfolio site, I needed a measurement framework that could answer basic but important questions:

- Where is traffic coming from?
- What content are visitors engaging with?
- Are users taking meaningful actions like downloading my resume, clicking email, viewing GitHub, or exploring projects?
- What should I improve as more portfolio content goes live?

## Project Objectives
- Implement Google Analytics 4 on a live portfolio site
- Track important CTA interactions with custom GA4 events
- Establish a clean post-launch baseline
- Create a repeatable measurement framework for future portfolio growth
- Turn a personal website into a real web analytics testing environment

## Site Context
This project uses my personal portfolio site as the live analytics sandbox.

- **Website:** [quinnreams.com](https://www.quinnreams.com/)
- **Platform:** Astro
- **Hosting:** GitHub Pages
- **Analytics Tool:** Google Analytics 4
- **Search Tool:** Google Search Console

## Events Tracked

### Automatically Collected Events
- `page_view`
- `scroll`
- `file_download`
- `click`
- `user_engagement`

### Custom Events
- `resume_download`
- `email_click`
- `github_click`
- `project_click`

## Why These Events Matter
- **resume_download** indicates hiring or recruiter interest
- **email_click** indicates direct contact intent
- **github_click** indicates deeper evaluation of technical work
- **project_click** indicates interest in portfolio content and case studies

## Implementation Summary
To build this tracking setup, I:

- Installed GA4 on the live site
- Converted important buttons into real anchor links for better measurement
- Added unique IDs to key CTAs across the header, hero, projects section, and footer
- Implemented custom event tracking through a shared layout script in `BaseLayout.astro`
- Validated events using GA4 Realtime reporting

## Repository Structure
```text
.
├── docs/
│   ├── ga4-screens-notes.md
│   ├── kpi-definitions.md
│   ├── search-console-screens-notes.md
│   ├── tracking-plan.md
│   └── utm-conventions.md
├── reports/
├── LICENSE
└── README.md
```

## Documentation

This repo includes planning and measurement documentation to support the implementation.

- `docs/tracking-plan.md` — tracking strategy and event structure
- `docs/kpi-definitions.md` — KPI definitions for the project
- `docs/ga4-screens-notes.md` — setup notes and GA4 observations
- `docs/search-console-screens-notes.md` — Search Console notes and SEO observations
- `docs/utm-conventions.md` — naming rules for campaign tracking

## Current Status

GA4 is installed and actively collecting data from the live site. Custom events are firing correctly in live reporting, and the project is now moving into the baseline analysis and documentation phase.

## Next Steps

- Mark custom events as Key Events once they finish processing in GA4
- Build a Week 1 baseline report
- Add screenshots and notes from live GA4 reports
- Expand project pages and measure deeper project engagement
- Add Search Console insights as more search data becomes available

## Portfolio Value

This project demonstrates practical experience with:

- GA4 implementation
- event tracking strategy
- CTA measurement
- live-site analytics validation
- marketing analytics thinking
- translating user behavior into actionable insights

## Author

**Quinn Reams**  
Marketing and Data Analytics Portfolio  
[quinnreams.com](https://www.quinnreams.com)