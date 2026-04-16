# OPSCEN v6.27 — Iran Theatre Intelligence Briefing

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

## Current Briefing: Day 48

- The U.S. blockade of Iranian ports is still active on April 16, 2026, and AP reports Pakistani mediators are still trying to get a second round of U.S.-Iran talks back to Islamabad, but no meeting has been formally locked in.
- AP also reports U.S. Central Command said no ships got past the blockade in the first 48 hours and 10 merchant vessels turned around, which keeps the coercive pressure real even though the Strait of Hormuz is not fully shut.
- The most important Australia-specific change is the Geelong refinery fire: Fire Rescue Victoria said the blaze was extinguished and that diesel and petrol production were continuing at reduced rates for safety reasons.
- Australia remains on fuel watch rather than fuel panic. Bowen's April 13 briefing still points to 38 days of petrol, 31 days of diesel, 28 days of jet fuel and 57 ships inbound, but the domestic refining picture is now weaker than yesterday.
- Check Petrol's live outage tracker shows 690 stations affected nationally across 964 fuel-type outages, with overall availability at 96% across 7,498 tracked stations.
- The working outlook is still a fragile maritime standoff with live mediation, not a verified return to the heaviest U.S. strike phase and not yet a durable settlement.
- The next hard triggers are whether a new Islamabad round is actually scheduled, whether the ceasefire is formally extended before April 22, 2026, and how quickly Geelong petrol output is restored.

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
