# Cold Email Outbound

**Context:** Built and ran the full cold-email motion for my own boutique GTM advisory practice, selling into old-economy and B2B verticals from a standing start.

## Objective
Book qualified sales conversations with no inbound and no list to begin with.

## What I shipped
- A repeatable pipeline: list-building, then email and phone verification, then enrichment, then sending, then an AI reply classifier I built, then CRM sync.
- 9 distinct campaigns across separate verticals, each with its own angle and buying signal (permit filings, hiring signals, regulatory triggers).
- Spintax plus a spam-guard layer to hold deliverability at volume.
- Twice-daily automated sync of reply and positive-reply data into the CRM.

## Outcome
- 40K+ contacts emailed across the 9 campaigns.
- $840K in identified pipeline (interested leads x vertical ACV).
- Best verticals reached roughly 2% reply rates with double-digit positive-reply rates, well above generic B2B benchmarks.
- Every reply auto-triaged and routed, so follow-up never depended on me watching an inbox.

## Stack
Apollo and Clay (list and enrichment), email and phone verification, a cold-email sending platform, a Claude-based reply classifier, Python and SQLite, Google Sheets, launchd scheduling.
