# OPSCEN v6.26 — Iran Theatre Intelligence Briefing

A real-time military operations centre dashboard tracking the 2026 Iran conflict, originally built in [Claude](https://claude.ai) and now run through a Codex-powered publishing workflow by [RETSA Group](https://retsagroup.com.au).

**[Live Dashboard →](https://mrummler17.github.io/operations-centre)**

## What is this?

Rather than flicking between 7 News, 9, ABC and YouTube trying to piece together what's happening with Iran — I run an "update briefing" workflow.

It searches the web, refreshes my custom ops centre with today's intel, updates the site, and gives me personalised action items for my business and household.

Two words. Fresh every morning. The news comes to me now.

## Features

- **CRT military aesthetic** — retro-futuristic operations centre design
- **Two-tab interface** — Briefing view + interactive Fuel Depletion Forecast
- **Key metrics dashboard** — quick-reference tiles at top of page
- **9 collapsible intelligence sections covering all theatres of the conflict**
- **Australian Fuel Forecast module** — interactive depletion projections for petrol, diesel, and jet fuel with scenario presets and adjustable parameters
- **Live radio monitor** — embedded NPR public audio feed inside the dashboard
- **Live system clock (Sydney + UTC)**
- **DEFCON gauge with visual assessment**
- **Multi-theatre threat matrix** — 9 active zones tracked
- **Scenario analysis with probability-weighted forecasts**
- **Australian-specific sections** — ASX 200, RBA rate impacts, fuel crisis monitoring
- **UPDATED badges showing what changed since last briefing**

## Current Briefing: Day 47

- The U.S. blockade on vessels calling at Iranian ports is now active, but Reuters reports U.S. and Iranian teams could return to Islamabad later this week.
- Hormuz remains navigable for some non-Iran-bound traffic, yet Reuters shipping data says crossings are still only a fraction of the 130-plus daily pre-war norm.
- Oil has eased back below $100 on renewed talk hopes, which matters because the market is still trading shipping risk more than rhetoric.
- Washington also hosted the first direct Israel-Lebanon talks in decades on April 14, a real diplomatic opening even as Hezbollah fighting continues.
- Australia remains on fuel watch rather than fuel panic: Chris Bowen says 57 ships are inbound and national stock days are broadly steady, but local outages persist.
- The working outlook is still a fragile maritime standoff, not a clean settlement and not yet a verified return to wider U.S. strike escalation.
- The next hard trigger is whether talks actually resume and whether Hormuz traffic normalises in commercial practice, not just on paper.

## How it works

1. I run "update briefing" against the structured briefing file
2. The workflow searches the web across multiple sources
3. It refreshes the dashboard and README from the latest data
4. I preview the output locally and publish in one command
5. I also get a ready-to-post X image prompt

No app. No subscription. Just a tighter workflow.

## Tech

Single self-contained HTML file. React 18 via CDN. Structured JSON briefing data. Local preview and one-command publish. Zero runtime dependencies.

## Author

**Marcus Rummler** — [@Marcus_Rummler](https://x.com/Marcus_Rummler)

Founder, [RETSA Group](https://retsagroup.com.au) — Instructional design & AI-powered tech solutions.

I can't code. I've never been able to code. But I've shipped a SaaS product and built a military ops centre. All with AI.

## License

MIT
