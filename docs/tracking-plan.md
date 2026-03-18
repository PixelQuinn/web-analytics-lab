# Tracking Plan

## Project Purpose
This tracking plan defines how Web Analytics Lab measures visitor behavior on my live portfolio site, quinnreams.com. The goal is to understand traffic sources, content engagement, and whether visitors take meaningful career-intent actions.

## Measurement Goals
The analytics setup is designed to answer four core questions:

1. Where is traffic coming from?
2. What content are visitors engaging with?
3. Which calls to action are getting clicked?
4. Are visitors moving deeper into the portfolio over time?

## Site Context
- **Website:** [quinnreams.com](https://www.quinnreams.com/)
- **Platform:** Astro
- **Hosting:** GitHub Pages
- **Analytics Platform:** Google Analytics 4
- **SEO Platform:** Google Search Console

## Event Strategy

### Automatically Collected Events
These events are collected through GA4 Enhanced Measurement without additional custom code:

- `page_view`
- `scroll`
- `click`
- `file_download`
- `user_engagement`

### Custom Events
These events are sent through a shared script in `BaseLayout.astro` to capture high-value portfolio actions more clearly:

- `resume_download`
- `email_click`
- `github_click`
- `project_click`

## Why These Events Matter

### resume_download
This event signals strong hiring or recruiter interest. A resume download is one of the clearest indications that a visitor wants to evaluate me as a candidate.

### email_click
This event signals direct contact intent. It helps measure whether the site encourages visitors to reach out.

### github_click
This event signals deeper interest in my technical work and implementation details.

### project_click
This event signals interest in my portfolio content and case studies. As more project pages are published, this event will become more important for understanding deeper engagement.

## CTA Locations Tracked
The site currently tracks CTA interactions across multiple locations:

- Header navigation
- Hero section
- Featured projects section
- Supporting project cards
- Footer contact links

## Link ID Strategy
To support cleaner event tracking, unique IDs were added to key links across the site.

Examples include:

- `nav-resume`
- `hero-resume`
- `hero-email`
- `footer-email`
- `footer-github`
- `featured-web-analytics`
- `project-marketing-impact`
- `project-marketing-dashboard`
- `project-crm-analytics`
- `project-forecasting`

## Key Events
The most important events in this project are intended to become GA4 Key Events once they finish processing in Analytics:

- `resume_download`
- `email_click`
- `github_click`
- `project_click`

## Measurement Priorities

### Priority 1: Acquisition
Understand how visitors arrive at the site.

Key metrics:
- Users
- Sessions
- Engaged sessions
- Session source / medium

### Priority 2: Engagement
Understand whether users are interacting with portfolio content.

Key metrics:
- Page views
- Scrolls
- Average engagement time
- Views by page

### Priority 3: CTA Performance
Understand whether users are taking meaningful actions.

Key metrics:
- Resume downloads
- Email clicks
- GitHub clicks
- Project clicks

## Reporting Plan

### Week 1 Baseline
The first reporting window focuses on:
- initial traffic sources
- top pages
- event counts
- early CTA behavior
- first optimization insights

### Future Reporting
As more project pages and traffic accumulate, future reports will analyze:
- homepage-to-project click paths
- CTA performance by section
- deeper project engagement
- organic search visibility from Search Console
- performance trends over time

## Current Limitations
- Early traffic volume may be low
- Some project links are still placeholders until full pages are built
- Search Console data will take time to accumulate
- Internal testing may influence short-term event counts

## Planned Improvements
- Mark custom events as Key Events in GA4
- Add Search Console reporting
- Register custom dimensions for parameters like CTA location if needed
- Compare hero, header, and footer CTA performance
- Analyze behavior changes as new featured projects go live