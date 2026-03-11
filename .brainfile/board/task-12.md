---
id: task-12
title: Write service card descriptions for all 13 services
column: todo
position: 9
description: Service cards currently show icon + title only — no descriptions. This hurts SEO (thin content) and user experience (visitors can't tell what's offered without clicking). Write 2-3 sentence descriptions for each of the 13 service cards highlighting what PM Professional Services offers for that category.
priority: high
tags:
  - content
  - seo
subtasks:
  - id: task-12-1
    title: Inventory all 13 service card titles
    completed: false
  - id: task-12-2
    title: Write descriptions for each service card
    completed: false
  - id: task-12-3
    title: Add descriptions to HTML service cards
    completed: false
  - id: task-12-4
    title: Verify responsive layout with longer card content
    completed: false
createdAt: "2026-02-20T22:08:58.780Z"
contract:
  status: ready
  deliverables:
    - type: file
      path: src/index.html
      description: Updated service cards with 2-3 sentence descriptions for all 13 services
  validation:
    commands:
      - grep -c 'service-card' src/index.html
  constraints:
    - Each description must be 2-3 sentences, not generic filler
    - Include relevant keywords for local SEO (Chesapeake, VA contractor terms)
    - Descriptions should highlight what PM Professional Services specifically offers
    - Consistent tone and length across all 13 cards
    - No placeholder or lorem ipsum text
updatedAt: "2026-03-10T13:42:55.169Z"
---

## Description
Service cards currently show icon + title only — no descriptions. This hurts SEO (thin content) and user experience (visitors can't tell what's offered without clicking). Write 2-3 sentence descriptions for each of the 13 service cards highlighting what PM Professional Services offers for that category.
