# instagram-engagement-bot
Scraper + Engagement Bot using n8n

## Overview

This project is an automated pipeline built using n8n to scrape Instagram posts based on hashtags, filter relevant content, generate personalized DM messages, and simulate engagement actions like follow and follow-up.

## Workflow

1. Input hashtags via form
2. Scrape Instagram posts using Apify
3. Filter posts based on keywords and engagement
4. Generate personalized DM messages
5. Simulate follow and follow-up actions
6. Store results in Google Sheets for reporting

## Tools Used

* n8n (workflow automation)
* Apify (Instagram scraping)
* JavaScript (data processing & logic)
* Google Sheets (data storage)

## Why this approach?

Instagram APIs have restrictions on automation (follow/DM), so engagement actions are simulated. The workflow is designed to easily integrate with real tools like Instagrapi if needed.

## Setup Steps

1. Import workflow.json into n8n
2. Add Apify API token
3. Connect Google Sheets credentials
4. Run workflow using form input

## Output

The system generates:

* Filtered leads
* Personalized DM messages
* Engagement tracking data

## Future Improvements

* Real DM and follow using Instagrapi
* Better AI-based lead scoring
* Scheduling and automation triggers
* Dashboard for analytics

