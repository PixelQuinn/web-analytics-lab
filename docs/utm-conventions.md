# UTM Conventions

## Purpose
This document defines the UTM tagging rules for the Web Analytics Lab project. The goal is to keep campaign links consistent so traffic sources can be analyzed clearly in GA4.

## Why UTM Parameters Matter
UTM parameters help label incoming traffic from controlled links. They make it easier to answer questions like:

- Did traffic come from LinkedIn, GitHub, email, or another source?
- Which post, profile link, or campaign drove the visit?
- Which traffic sources are producing the most meaningful engagement?

## Core UTM Parameters

### utm_source
Identifies where the traffic came from.

Examples:
- `linkedin`
- `github`
- `email`
- `portfolio`
- `discord`

### utm_medium
Identifies the channel type.

Examples:
- `social`
- `referral`
- `email`
- `community`
- `profile`

### utm_campaign
Identifies the broader campaign or initiative.

Examples:
- `web_analytics_lab_launch`
- `portfolio_feature_update`
- `project_showcase`
- `resume_sharing`

### utm_content
Used to distinguish versions of a link or placement.

Examples:
- `hero_link`
- `footer_link`
- `featured_project_card`
- `linkedin_post_1`

### utm_term
Optional. Usually used for paid search keywords, so it will not be a priority for this project right now.

## Naming Rules
To keep data clean, all UTM values should follow these rules:

- use lowercase only
- use underscores instead of spaces
- keep names short but descriptive
- avoid special characters
- use consistent wording across campaigns

## Recommended Standard Values

### Sources
- `linkedin`
- `github`
- `email`
- `discord`
- `reddit`

### Mediums
- `social`
- `referral`
- `email`
- `community`
- `profile`

### Campaigns
- `web_analytics_lab_launch`
- `portfolio_launch`
- `featured_project_launch`
- `project_update`
- `resume_outreach`

## Example Tagged URLs

### LinkedIn profile link

```text
https://www.quinnreams.com/?utm_source=linkedin&utm_medium=profile&utm_campaign=portfolio_launch
```
### LinkedIn post promoting a project

```text
https://www.quinnreams.com/?utm_source=linkedin&utm_medium=social&utm_campaign=web_analytics_lab_launch&utm_content=post_1
```
### GitHub profile link

```text
https://www.quinnreams.com/?utm_source=github&utm_medium=profile&utm_campaign=portfolio_launch
```
### Email signature link

```text
https://www.quinnreams.com/?utm_source=email&utm_medium=email&utm_campaign=resume_outreach&utm_content=signature
```

## How This Will Be Used

UTM-tagged URLs will help measure:
- which external platforms send traffic
- which campaign links drive the most visits
- which tagged visits lead to deeper engagement or CTA actions
- whether project promotion creates measurable traffic spikes

## Current Status

UTM conventions are documented now so future campaign links stay consistent. Full use of UTMs will become more important as the portfolio is shared more actively on LinkedIn, GitHub, email, and other external platforms.

## Future Improvements
- create a reusable UTM builder sheet
- document real campaign links used in outreach
- compare UTM-tagged traffic against untagged direct/referral traffic
- evaluate which campaigns drive the most key events