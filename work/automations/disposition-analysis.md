# Closed-Loop Disposition Analysis

## The problem
Outbound has no feedback loop. Paid ads automatically reweight toward the people who convert. Cold calling and cold email don't. Teams generate thousands of structured disposition events every month (who answered, who was the wrong contact, who said not now, who converted), then choose next month's targets from gut feel. The data exists. The step that turns it back into sharper targeting is the one that's missing.

## What I built
A system that reads the disposition outcomes from completed campaigns and feeds them back into who gets targeted next, so list quality compounds cycle over cycle instead of resetting every time.

## Status
Early-stage. A first version is shipped and in use; the deeper write-back layer is the next build.

## Stack
Python, disposition data from dialers and email, automated reporting.
