# KPI Definitions

## Purpose
This document defines the key performance indicators used in the Web Analytics Lab project. These KPIs help measure traffic quality, content engagement, and meaningful visitor actions on my live portfolio site.

## Traffic KPIs

### Users
The number of distinct users who visited the site during the reporting window.

**Why it matters:**  
Shows overall audience reach.

### Sessions
The total number of visits to the site during the reporting window.

**Why it matters:**  
Shows how often the site is being visited.

### Engaged Sessions
Sessions that lasted longer than 10 seconds, included a key event, or had at least 2 page or screen views.

**Why it matters:**  
Helps separate higher-quality visits from very brief visits.

### Engagement Rate
The percentage of sessions that counted as engaged sessions.

**Why it matters:**  
Shows the share of visits that resulted in meaningful interaction.

## Acquisition KPIs

### Source / Medium
The channel combination that brought a visitor to the site, such as:
- direct / none
- google / organic
- linkedin.com / referral

**Why it matters:**  
Shows where traffic is coming from and which channels are working.

### Organic Search Traffic
Traffic arriving through unpaid search engine results.

**Why it matters:**  
Helps measure SEO visibility over time.

### Referral Traffic
Traffic arriving from another website, such as LinkedIn or GitHub.

**Why it matters:**  
Shows whether outside platforms are sending visitors to the portfolio.

## Content Engagement KPIs

### Page Views
The total number of times pages were viewed.

**Why it matters:**  
Shows which parts of the site are getting attention.

### Views by Page
The number of views for each individual page or section.

**Why it matters:**  
Helps identify the most visited content.

### Average Engagement Time
The average amount of time users actively spend on a page or site.

**Why it matters:**  
Gives a sense of whether visitors are actually consuming content.

### Scrolls
The number of scroll events collected by GA4.

**Why it matters:**  
Acts as a light engagement signal, especially on longer pages.

## CTA Performance KPIs

### Resume Downloads
Tracked through the custom event `resume_download`.

**Why it matters:**  
Signals strong hiring or recruiter interest.

### Email Clicks
Tracked through the custom event `email_click`.

**Why it matters:**  
Signals direct contact intent.

### GitHub Clicks
Tracked through the custom event `github_click`.

**Why it matters:**  
Signals deeper interest in technical work and implementation details.

### Project Clicks
Tracked through the custom event `project_click`.

**Why it matters:**  
Signals interest in portfolio content and case studies.

## Key Events
The following custom events are treated as the most important conversion-style actions in this project:

- `resume_download`
- `email_click`
- `github_click`
- `project_click`

**Why they matter:**  
These events represent the clearest signals that a visitor is moving beyond passive browsing into meaningful engagement.

## Interpretation Notes
Not every KPI has equal value.

For this project, the strongest success signals are:
1. Resume downloads
2. Email clicks
3. GitHub clicks
4. Project clicks

Traffic volume matters, but action-oriented engagement matters more than raw visits alone.

## Current KPI Priorities

### Primary KPIs
- Users
- Sessions
- Engagement Rate
- Resume Downloads
- Email Clicks
- GitHub Clicks
- Project Clicks

### Secondary KPIs
- Scrolls
- Views by Page
- Source / Medium
- Average Engagement Time

## Future KPI Expansion
As the portfolio grows, future KPI tracking may include:
- project page views
- homepage-to-project click rate
- organic search impressions
- organic search clicks
- click-through rate from Search Console
- landing page performance by channels