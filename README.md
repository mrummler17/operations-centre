# OPSCEN v6.28 — Iran Theatre Intelligence Briefing

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

## Current Briefing: Day 60

- The ceasefire has bought time but still has not produced a settlement, and the blockade of Iranian port traffic remains the main coercive tool in play.
- The key shift is that Tehran has now put a conditional Hormuz reopening offer on the table in exchange for lifting the blockade and ending the war.
- Hormuz remains technically open to non-Iranian traffic, but commercial confidence has not normalized and tankers are still steering clear.
- The missing US crew member from the downed F-15 is still reported rescued after the weekend firefight inside Iran.
- Tehran's public line is still hard, but the new offer shows it is now testing a more explicit trade: shipping relief in return for blockade relief.
- Hormuz remains technically open but commercially constrained, with shipowners and insurers still behaving as if coercion risk is live.
- Oil remains headline-sensitive as markets price the new offer against the continued blockade.
- Lebanon remains one of the most dangerous spillover fronts, and continued Israel-Hezbollah violence is the clearest spoiler risk to wider diplomacy.
- Australia's fuel picture is stressed but improving, with fewer outages reported and more than 50 ships inbound.
- The working outlook is now fragile ceasefire plus maritime bargaining, not a clean peace settlement.
- The next hard trigger is whether Washington answers the Hormuz offer with concessions, rejection, or fresh coercion.

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
