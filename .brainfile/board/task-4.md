---
id: task-4
title: Migrate pmprofessionalservices.com DNS to Cloudflare
column: backlog
position: 0
description: "Client owns pmprofessionalservices.com via Porkbun (order 7448686) with domain registration and email hosting. Migrate DNS management to Cloudflare for the Grayskull Technology account — point nameservers from Porkbun to Cloudflare. Set up: A/CNAME records for the Workers site, MX records for email, SPF/DKIM/DMARC for email auth. This enables using pmprofessionalservices.com as the primary domain instead of a workers.dev subdomain."
priority: high
tags:
  - dns
  - cloudflare
  - domain
  - infrastructure
subtasks:
  - id: task-4-1
    title: Add pmprofessionalservices.com zone to Cloudflare
    completed: true
  - id: task-4-2
    title: Update Porkbun nameservers to Cloudflare
    completed: false
  - id: task-4-3
    title: Configure A/CNAME records for Workers site
    completed: false
  - id: task-4-4
    title: Set up MX records for email
    completed: false
  - id: task-4-5
    title: Configure SPF, DKIM, DMARC for email deliverability
    completed: false
  - id: task-4-6
    title: Add custom domain route to Workers
    completed: false
createdAt: "2026-02-20T21:35:22.802Z"
updatedAt: "2026-03-08T00:39:57.852Z"
---

## Description
Client owns pmprofessionalservices.com via Porkbun (order 7448686) with domain registration and email hosting. Migrate DNS management to Cloudflare for the Grayskull Technology account — point nameservers from Porkbun to Cloudflare. Set up: A/CNAME records for the Workers site, MX records for email, SPF/DKIM/DMARC for email auth. This enables using pmprofessionalservices.com as the primary domain instead of a workers.dev subdomain.
