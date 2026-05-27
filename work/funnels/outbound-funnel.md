# Quantitative Outbound Funnel

**Context:** A single operating system for outbound, built so email, phone, and LinkedIn all report into one funnel and can be compared like a portfolio of bets.

## Objective
Stop running channels as separate, unmeasurable efforts. Make every touch roll up to the same funnel math, so dead campaigns get cut and working ones get more.

## What I shipped
- One universal funnel across all channels: Touch, Reach, Response, Completion, Activation, Meeting Booked, Meeting Held, Opportunity, Closed.
- Disposition buckets on every completion (Yes / No / Not Me / Not Now) feeding list targeting.
- Kill and promote thresholds (auto-pause under 0.5% response rate; promote above 3%).
- A friction model baked in (reach loss, bad data, bounces, contact fatigue) so forecasts stay honest.

## Outcome
- Deployed across 9 signal-based verticals at once.
- Each campaign scored on expected value per touch and per contact, so spend followed the math.
- Underpinned the $840K cold-email pipeline and the $1.43M cold-calling pipeline.

## Stack
Python and SQLite (funnel math and dashboards), email and phone channels, Clay (signal and enrichment), Google Sheets and Looker Studio (reporting).
