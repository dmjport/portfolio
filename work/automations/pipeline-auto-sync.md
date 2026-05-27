# Pipeline Auto-Sync

## Objective
Keep the CRM pipeline current without anyone updating it by hand, and without automation ever overwriting a human's judgment.

## What I shipped
- A puller that runs twice daily, taking positive replies from the cold-email platform and adding them to the pipeline automatically.
- A managed-by auto/manual flag: once a human moves a lead by hand, that lead is marked manual and the automation never touches its stage again.
- Enrichment (last reply, phone) applied to every lead regardless of who owns it.

## Outcome
- Zero-touch pipeline hygiene: new positive replies become pipeline within hours, with no data entry.
- No conflict between automation and manual stage edits, the exact problem that makes most auto-sync setups untrustworthy.

## Stack
Python, the cold-email platform API, a JSON and SQLite store, launchd (twice daily).
