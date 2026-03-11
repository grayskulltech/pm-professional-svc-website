---
id: task-11
title: Add privacy policy and terms of service
column: todo
position: 8
description: Contact form collects PII (name, email, phone). Virginia VCDPA applies. Must add privacy policy and terms of service pages to reduce legal liability. Include data collection disclosure, cookie policy (if applicable), and contact information for data requests.
priority: high
tags:
  - legal
  - compliance
subtasks:
  - id: task-11-1
    title: Draft privacy policy covering PII collection from contact form
    completed: false
  - id: task-11-2
    title: Draft terms of service
    completed: false
  - id: task-11-3
    title: Add privacy policy page/section to website
    completed: false
  - id: task-11-4
    title: Add terms of service page/section to website
    completed: false
  - id: task-11-5
    title: Add footer links to both documents
    completed: false
createdAt: "2026-02-20T22:08:51.053Z"
contract:
  status: ready
  deliverables:
    - type: file
      path: src/privacy-policy.html
      description: Privacy policy page covering VCDPA requirements
    - type: file
      path: src/terms-of-service.html
      description: Terms of service page
    - type: file
      path: src/index.html
      description: Updated footer with links to privacy policy and terms of service
  validation:
    commands:
      - test -f src/privacy-policy.html
      - test -f src/terms-of-service.html
      - grep -qi 'privacy-policy' src/index.html
  constraints:
    - Must address Virginia VCDPA requirements for PII collection
    - Disclose all data collected via contact form (name, email, phone, message)
    - Include cookie policy section even if no cookies currently used
    - Provide contact method for data access/deletion requests
    - Use plain language — not impenetrable legalese
updatedAt: "2026-03-10T13:42:55.159Z"
---

## Description
Contact form collects PII (name, email, phone). Virginia VCDPA applies. Must add privacy policy and terms of service pages to reduce legal liability. Include data collection disclosure, cookie policy (if applicable), and contact information for data requests.
