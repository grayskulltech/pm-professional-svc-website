---
schema: https://brainfile.md/v2/board.json
title: PM Professional Services LLC Website
agent:
  instructions:
    - Task files are individual .md files in board/
    - Completed tasks are in logs/
    - Preserve all IDs
    - Make minimal changes
columns:
  - id: todo
    title: To Do
  - id: in-progress
    title: In Progress
  - id: done
    title: Done
rules:
  always:
    - id: 1
      rule: Client project — follow PM Professional Services branding, not Cisco or Grayskull
  never:
    - id: 1
      rule: Include Cisco or Grayskull branding in client deliverables
  context:
    - id: 1
      rule: "Client project, PUBLIC classification. Default assignee: claude. Infra: cloudflare"
---

# PM Professional Services LLC Website

Client website for PM Professional Services LLC — licensed home repair and improvement contractor serving Chesapeake, VA. Owner: Paul Mefford (SDVOSB — Service-Disabled Veteran-Owned Small Business).

**Stack:** Static HTML/CSS on Cloudflare Workers, GitHub Actions CI/CD, domain via Porkbun.

> Note: Completing a task moves it to `logs/` via `brainfile complete`.
