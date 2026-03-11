---
id: task-2
title: Add SDVOSB designation to website
column: todo
position: 1
description: Paul Mefford is a Service-Disabled Veteran-Owned Small Business (SDVOSB) owner. Add SDVOSB badge/designation to the website — this is a competitive differentiator and matters for government contracting eligibility. Add to About section credentials grid and consider a hero banner mention or footer badge.
priority: high
tags:
  - content
  - branding
  - client-facing
subtasks:
  - id: task-2-1
    title: Add SDVOSB credential badge to About section credentials grid
    completed: false
  - id: task-2-2
    title: Add veteran-owned mention to hero or info banner
    completed: false
  - id: task-2-3
    title: Add SDVOSB badge/icon to footer
    completed: false
createdAt: "2026-02-20T21:35:22.520Z"
contract:
  status: ready
  deliverables:
    - type: file
      path: src/index.html
      description: Updated HTML with SDVOSB badge in About section credentials grid and footer
    - type: file
      path: assets/sdvosb-badge.svg
      description: SDVOSB designation badge/icon
  validation:
    commands:
      - grep -qi 'sdvosb' src/index.html
      - test -f assets/sdvosb-badge.svg
  constraints:
    - SDVOSB badge must be visually prominent but not garish
    - Include in About section credentials grid AND footer
    - Use official SDVOSB designation language
    - Responsive — badge must render properly on mobile
updatedAt: "2026-03-10T13:42:55.134Z"
---

## Description
Paul Mefford is a Service-Disabled Veteran-Owned Small Business (SDVOSB) owner. Add SDVOSB badge/designation to the website — this is a competitive differentiator and matters for government contracting eligibility. Add to About section credentials grid and consider a hero banner mention or footer badge.
