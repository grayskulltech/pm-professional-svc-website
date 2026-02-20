---
schema: https://brainfile.md/v2/board.json
title: PM Professional Services LLC Website
agent:
  instructions:
    - Task files are individual .md files in board/
    - Completed tasks are in logs/
    - Preserve all IDs
    - Make minimal changes
    - Client project — Paul Mefford, owner of PM Professional Services LLC
    - Licensed contractor in Chesapeake, VA (SDVOSB)
    - Domain pmprofessionalservices.com owned via Porkbun (order 7448686)
    - Hosted on Cloudflare Workers (pm-professional-svc-website)
    - CI/CD via GitHub Actions → Cloudflare Workers auto-deploy on push to main
columns:
  - id: todo
    title: To Do
  - id: in-progress
    title: In Progress
  - id: done
    title: Done
---

# PM Professional Services LLC Website

Client website for PM Professional Services LLC — licensed home repair and improvement contractor serving Chesapeake, VA. Owner: Paul Mefford (SDVOSB — Service-Disabled Veteran-Owned Small Business).

**Stack:** Static HTML/CSS on Cloudflare Workers, GitHub Actions CI/CD, domain via Porkbun.

> Note: Completing a task moves it to `logs/` via `brainfile complete`.
