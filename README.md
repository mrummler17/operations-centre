# OPSCEN v6.25 — Iran Theatre Intelligence Briefing

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

## Current Briefing: Day 44

- The first direct US-Iran round in Islamabad ended early on Sunday, April 12 without an agreement after about 21 hours of talks.
- That leaves the Pakistan-brokered two-week ceasefire formally alive but still unclear in practical terms.
- The operational proof point remains Hormuz, where AP reported only 12 ships had been recorded transiting since the ceasefire while US mine-clearing moves began.
- Markets are no longer pricing only imminent strikes; they are pricing whether any safe maritime corridor actually restores commercial confidence.
- Both crew members from the downed US F-15 are now reported rescued, removing one earlier uncertainty from the air campaign.
- Lebanon remains the clearest spoiler front, with the death toll now above 2,000 and direct Israel-Lebanon talks due in Washington this week.
- Oil fell sharply into the weekend, but Reuters said Brent still settled around $95 and physical-market disruption remains severe.
- Australia remains on fuel watch: the Guardian tracker still shows widespread station outages, at least six shipments cancelled or deferred, and 50+ ships inbound.
- Canberra also secured a public supply assurance from Singapore on April 10, which helps the refined-fuel side but does not remove Hormuz risk.
- The working outlook is now fragile ceasefire without deal, not a clean diplomatic breakthrough.
- The next hard trigger is visible shipping normalization, not another headline about talks.

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
