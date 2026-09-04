# ERP Weekly Brief

Automated weekly roundup of what's happening in the ERP software industry: vendor news, AI-in-ERP developments, market trends, and anything specifically relevant to a mid-market/distribution ERP vendor.

This is a personal research feed for tracking industry context, not an official publication of any company. It runs on its own schedule via a scheduled Claude Code agent and requires no manual intervention.

## How it works

- A cloud agent runs every Monday morning and researches ERP industry news, social media chatter (X/LinkedIn), and market trends from the past week.
- It writes a self-contained HTML file for each run: `erp_brief_<YYYY-MM-DD>.html`.
- It checks `erp_brief_log.json` before writing so the same story isn't repeated week to week, unless it has genuinely moved forward with new developments.
- After each run, `erp_brief_log.json` is updated with that week's included items and trimmed of anything older than 20 days.

## Files

- `erp_brief_<date>.html` — one brief per week, open directly in a browser.
- `erp_brief_log.json` — internal dedup log, not meant to be read directly.

## Note

The repository is public only so the automated agent can access it; it contains no confidential or company internal information, just links to public news articles and summaries of publicly available content.
