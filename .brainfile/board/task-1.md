---
id: task-1
title: Set up contact form email delivery
column: todo
position: 0
description: "The \"Request Your Free Estimate\" form currently posts to `#` (no backend). Need to wire it up to deliver submissions to Paul's email. Options: Cloudflare Workers email routing, Formspree, or a simple Workers handler that sends via Mailchannels/SendGrid. Should use the pmprofessionalservices.com domain for professional appearance. Email hosting is included in the Porkbun order (7448686)."
priority: high
tags:
  - email
  - forms
  - client-facing
subtasks:
  - id: task-1-1
    title: Decide email delivery method (CF Workers handler vs Formspree vs Porkbun email forwarding)
    completed: false
  - id: task-1-2
    title: Wire form action to submission endpoint
    completed: false
  - id: task-1-3
    title: Add success/error feedback UI after form submit
    completed: false
  - id: task-1-4
    title: "Test end-to-end: form submit → email arrives at pmpsrvcs@gmail.com"
    completed: false
createdAt: "2026-02-20T21:35:22.297Z"
contract:
  status: ready
  deliverables:
    - type: file
      path: src/contact-handler.js
      description: Cloudflare Worker handler for contact form submissions
    - type: file
      path: wrangler.toml
      description: Worker config with email routing bindings
  validation:
    commands:
      - npx wrangler deploy --dry-run
      - test -f src/contact-handler.js
  constraints:
    - Must send to Paul's email address
    - Use pmprofessionalservices.com domain as sender
    - Include spam protection (honeypot field or rate limiting)
    - Form validation server-side — never trust client input
updatedAt: "2026-03-10T13:42:55.123Z"
---

## Description
The "Request Your Free Estimate" form currently posts to `#` (no backend). Need to wire it up to deliver submissions to Paul's email. Options: Cloudflare Workers email routing, Formspree, or a simple Workers handler that sends via Mailchannels/SendGrid. Should use the pmprofessionalservices.com domain for professional appearance. Email hosting is included in the Porkbun order (7448686).
