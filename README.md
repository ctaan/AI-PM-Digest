# AI + PM Digest

Caroline's daily AI + PM digest — a curated feed of frontier AI moves, PM thought leadership, and applied workflows top PMs are actually running.

**Live site:** https://ctaan.github.io/AI-PM-Digest/

## What this is

A daily-refreshed single-page digest covering three categories:

1. **AI Model & Product Releases** — frontier lab announcements, new models, product launches
2. **PM Thought Leaders** — essays from senior PMs and strategists on how the role is evolving
3. **Applied AI Workflows for PMs** — concrete tools, agents, and workflows PMs can adopt

Up to 3 items per category (9 total), with 2–3 flagged as must-reads for the day.

## How it works

A scheduled Cowork task runs every morning at 7:30 AM and:

1. Pulls the latest items from a trusted-source allowlist (Anthropic, OpenAI, DeepMind, Stratechery, Lenny's Newsletter, Simon Willison, Every, Reforge, Mind the Product, and more)
2. Filters to the current year and last 90 days only
3. Curates the freshest items, writes a 2–4 sentence PM-application takeaway for each
4. Saves a dated archive artifact in Cowork (`daily-ai-pm-digest-YYYY-MM-DD`)
5. Pushes the latest HTML to `index.html` in this repo so GitHub Pages always serves today's edition

## Curation rules

- **2026 only** — items from prior years are excluded
- **Last 90 days** — anything older is dropped
- **Explicit dates required** — undated items don't make it in
- **Allowlist-only sources** — URLs must come from the trusted-source list
- **No repeats** — yesterday's items are filtered out where possible
- **PM-application framing** — every takeaway embeds a practical use, not interview prep

## Repo structure

- `index.html` — today's digest (overwritten daily)
- `README.md` — this file

## Archive

Past editions live as dated artifacts inside Cowork (e.g. `daily-ai-pm-digest-2026-06-01`). Only the live edition is published to GitHub Pages.
