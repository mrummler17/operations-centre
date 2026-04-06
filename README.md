# OPSCEN v6.19 — Iran Theatre Intelligence Briefing

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
- **Live system clock (Sydney + UTC)**
- **DEFCON gauge with visual assessment**
- **Multi-theatre threat matrix** — 9 active zones tracked
- **Scenario analysis with probability-weighted forecasts**
- **Australian-specific sections** — ASX 200, RBA rate impacts, fuel crisis monitoring
- **UPDATED badges showing what changed since last briefing**

## Current Briefing: Day 39

- The briefing has rolled into deadline day, with Trump's 8pm ET Tuesday, April 7 Hormuz threat landing at 10am AEST on Wednesday, April 8 in Sydney.
- No verified breakthrough has emerged yet on shipping access, mediation, or a broader pause in strikes.
- The rescued US crew member is no longer the lead thread; the operational question is what happens when the deadline expires.
- Tehran is still rejecting the ultimatum publicly while mediated contact appears to remain open through intermediaries.
- Hormuz remains physically open but commercially distorted, with risk, insurance and confidence still doing most of the damage.
- Oil markets remain headline-sensitive because traders still see a live shipping-risk problem rather than restored normality.
- Lebanon remains one of the sharpest spillover fronts, with AP still describing more than 1,400 killed and over 1 million displaced.
- Australia's fuel position is still stressed, with reserve drawdowns and standards changes buying time rather than removing vulnerability.
- The working outlook is still coercion plus mediation, not a clean ceasefire.
- The next hard trigger is the post-deadline outcome: quiet standoff, infrastructure strikes, or a narrow mediated delay.

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
