# Call-Scoring Pipeline

## Objective
Turn raw call recordings into structured coaching and scoring data automatically, instead of anyone re-listening to calls.

## What I shipped
- A pipeline that transcribes every recording (Whisper), scores it against a rubric (Claude), and compiles a daily digest.
- Disposition and outcome tagging that feeds back into list targeting.

## Outcome
- 1,400+ dials processed into transcripts, scores, and notes.
- A daily digest that surfaces what's working on the phones with no manual review.

## Stack
Whisper (transcription), Claude (scoring), Python and SQLite, scheduled daily.
