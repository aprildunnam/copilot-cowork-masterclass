---
name: weekly-status-report
description: Use when I say "run my weekly status" or ask for a project status update. Compiles a Project Atlas status from the status CSV and recent emails into our standard format.
---

# Weekly Status Report

## When to use
Trigger on "weekly status", "status update", or "run my Friday wrap-up".

## Steps
1. Read the latest `ProjectAtlas_StatusData.csv`.
2. Pull any Project Atlas emails from the last 7 days for new risks/blockers.
3. Produce a status using the format below. Keep it to one page.

## Output format
**Project Atlas — Weekly Status (week of <date>)**
- **Overall:** On Track / At Risk / Blocked
- **Done this week:** 3 bullets
- **Up next:** 3 bullets
- **Risks / blockers:** owner + mitigation
- **Decisions needed:** who + by when

## Rules
- Use only these status labels: On Track, At Risk, Blocked, Complete, Not Started.
- Follow the Northwind file-naming and tone standards.
- Never invent numbers — if data is missing, say "data not available."

---
### STARTER TEMPLATE (copy this to build your own skill)
---
name: your-skill-name
description: Use when <trigger phrases>. <What it does, in one sentence.>
---
# Your Skill Title
## When to use
## Steps
## Output format
## Rules
