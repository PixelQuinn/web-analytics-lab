# GA4 Screens & Notes

## Purpose
This document captures the GA4 setup status, validation steps, and early observations for the Web Analytics Lab project. It acts as a running implementation log and evidence record for the portfolio case study.

## Property Setup Notes
- A fresh GA4 property was created for the relaunched portfolio site.
- The website tracked in this project is [quinnreams.com](https://www.quinnreams.com/).
- GA4 was installed directly in the shared site layout.
- The Google tag was added to the `<head>` of the site so page activity could be collected globally.

## Tracking Setup Notes
The project uses a combination of:
- automatically collected GA4 events
- custom events sent through site code

### Automatically Collected Events Observed
- `page_view`
- `scroll`
- `click`
- `file_download`
- `user_engagement`

### Custom Events Implemented
- `resume_download`
- `email_click`
- `github_click`
- `project_click`

## Site Instrumentation Notes
To support cleaner event tracking:
- important buttons were converted to real anchor links
- key links were given unique IDs
- custom GA4 events were triggered from a shared layout script instead of adding separate tracking logic inside every component

Examples of tracked link IDs:
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

## Validation Notes

### Realtime Validation
During testing, custom events appeared in GA4 Realtime reporting, confirming that the implementation was working on the live site.

Events successfully observed in live reporting included:
- `resume_download`
- `email_click`
- `github_click`
- `project_click`

### Event Processing Note
Custom events appeared in live reporting before fully appearing in the standard Events admin views. This is an expected part of the GA4 processing workflow and was noted during implementation.

## Screens to Capture
The following screenshots should be added to this project over time:

### Setup Screens
- GA4 property / data stream setup
- Google tag installation confirmation
- Enhanced Measurement enabled

### Validation Screens
- Realtime report showing active users
- Realtime event list showing custom events
- DebugView or live event validation if used

### Reporting Screens
- Traffic acquisition report
- Pages and screens report
- Events report
- Key events status once processed

## Early Observations
- GA4 installation was successful on the live portfolio site
- Automatic tracking was working before custom event setup was finalized
- Custom code-based events provided clearer portfolio-specific event names than relying only on generic `click` and `file_download`
- Realtime reporting was the most useful early validation screen during setup

## Implementation Challenges
- GA4's no-code event creation flow was more limited than expected for this use case
- The admin event views did not update as quickly as Realtime reporting
- Internal testing created noise during early validation
- Some project links are still placeholders until full project pages are built

## Why This Matters for the Project
These screens and notes document that the analytics setup is not theoretical. The implementation is live, validated, and tied directly to measurable portfolio actions.

## Next Updates to Add
- screenshots of custom events in GA4 reports
- screenshots of key events once fully processed
- screenshots from week 1 baseline reporting
- screenshots from Search Console once enough SEO data accumulates