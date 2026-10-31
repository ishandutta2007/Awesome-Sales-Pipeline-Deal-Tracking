# Awesome-Sales-Pipeline-Deal-Tracking

# Top Sales Pipeline & Deal Tracking Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Kanban Pipelines, Deal Forecasting & Self-Hosted CRM Platforms*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Sales Pipeline & Deal Tracking**. These tools enable sales teams to visualize deals moving through stages, forecast revenue, and manage customer relationships—turning scattered spreadsheets into a predictable, measurable revenue engine.

**Examples** include HubSpot Sales Pipeline Management, Pipedrive, Salesforce, Copper, Close, Monday Sales CRM, Zoho CRM, ActiveCampaign, Freshsales, and Pipeline CRM (the category leaders).

**Open-source emphasis**: Sales Pipeline & Deal Tracking is a domain where open-source tooling has **matured significantly and now offers genuinely viable self-hosted alternatives to commercial CRMs**. **Twenty** is the most prominent modern option—a TypeScript/NestJS/React CRM explicitly positioned as the open-source alternative to Salesforce and HubSpot, with customizable objects, kanban/table views, workflow automation, and active community development . **BottleCRM** (formerly Django-CRM) provides a full-lifecycle CRM with leads, opportunities, and support tickets, backed by PostgreSQL Row-Level Security for multi-tenancy and an agent-ready REST API . **Krayin** offers a Laravel-based CRM for SMEs with 24,000+ GitHub stars, focused on lead and sales management . **Relaticle** is a HubSpot/Pipedrive alternative with a Filament interface, AI assistant, and MCP server for agent access . The critical caveat: **commercial platforms differentiate on ecosystem breadth and managed reliability**—HubSpot's marketing-sales-service integration and Salesforce's AppExchange remain unmatched, and self-hosting means owning upgrades, backups, and security patches.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[HubSpot Sales Pipeline Management](https://www.hubspot.com/)**  
  Deal pipelines within HubSpot's Sales Hub; drag-and-drop stages, deal forecasting, and deep integration with marketing, service, and CRM data.

- **[Pipedrive](https://www.pipedrive.com/)**  
  Sales-focused CRM built around a visual pipeline; known for simplicity and activity-based selling, with deal rotting alerts and revenue forecasting.

- **[Salesforce](https://www.salesforce.com/)**  
  The enterprise standard for CRM; customizable pipeline stages, forecasting, and the AppExchange ecosystem for extending functionality.

- **[Copper](https://www.copper.com/)**  
  CRM built for Google Workspace; pipeline management with automatic activity capture from Gmail and Calendar.

- **[Close](https://close.com/)**  
  Conversation-first CRM with built-in calling, email, and SMS; sequences, smart views, and reporting for small sales teams [citation:search].

- **[Monday Sales CRM](https://monday.com/)**  
  Sales pipeline within monday.com's work OS; customizable boards, automations, and dashboards for deal tracking.

- **[Zoho CRM](https://www.zoho.com/crm/)**  
  Comprehensive CRM within the Zoho ecosystem; pipeline management, forecasting, and automation with competitive pricing.

- **[ActiveCampaign](https://www.activecampaign.com/)**  
  Marketing automation platform with built-in sales CRM; pipeline management integrated with email sequences and lead scoring.

- **[Freshsales](https://www.freshworks.com/freshsales/)**  
  CRM from Freshworks with visual pipeline, AI-powered deal insights, and built-in phone/email.

- **[Pipeline CRM](https://www.pipelinecrm.com/)**  
  Sales CRM focused on pipeline visibility and forecasting; positioned for small to mid-sized teams.

## Open-Source GitHub Projects

### Modern CRM Platforms (Salesforce/HubSpot Alternatives)

- **[Twenty](https://github.com/twentyhq/twenty)**  
  The **most actively developed open-source CRM** available (TypeScript/NestJS/React, ~58k GitHub stars) . Explicitly built as a Salesforce/HubSpot alternative with a fresh UX inspired by Notion, Airtable, and Linear. Features: **customizable objects and fields**, kanban and table views with filters/sort/group-by, custom roles and permissions, **workflow automation with triggers and actions**, emails, calendar events, and file management . **Best for teams wanting a modern, actively developed CRM** with a clean interface and self-hosting—but it is younger than established platforms and the plugin ecosystem is still emerging.

- **[BottleCRM (formerly Django-CRM)](https://github.com/django-crm/django-crm)**  
  Open-source, self-hosted **multi-tenant CRM** built with Django REST Framework and SvelteKit (MIT) . Covers the full customer lifecycle: **leads, accounts, contacts, opportunities, support tickets, tasks, and invoices** . Features: **PostgreSQL Row-Level Security** for database-level tenant isolation, native Flutter mobile app (iOS + Android), **agent-ready REST API** with OpenAPI schema for AI agent access, and a full helpdesk with SLA timers and approvals . **Best for teams wanting a full-lifecycle CRM with multi-tenancy and mobile access**—Django stack makes it hackable for Python teams.

- **[Krayin](https://github.com/krayin/laravel-crm)**  
  Free and open-source **Laravel CRM** for SMEs and enterprises (~24k GitHub stars, MIT) . Focused on complete customer lifecycle management: **customer, lead, and sales management** . Built on Laravel with a modern UI. **Best for Laravel/PHP teams** wanting a CRM they can extend within their existing stack.

- **[Relaticle](https://github.com/relaticle/relaticle)**  
  Open-source **HubSpot/Pipedrive alternative** with a fast Filament interface . Features: people, companies, opportunities, tasks, and notes; custom fields; CSV import; team workspaces; **AI assistant** that works on your records; and an **MCP server** so Claude or ChatGPT can read and update the CRM . Deployable on Railway with PostgreSQL and Redis. **Best for small teams wanting a lightweight, AI-augmented CRM** with a one-click deploy path.

### Traditional CRM Platforms

- **[EspoCRM](https://github.com/espocrm/espocrm)**  
  Open-source CRM application (PHP, AGPL-3.0, ~3.5k GitHub stars) . Features a clean UI, customizable entity manager, workflow automation, and a REST API. **Mature and stable** with an extension ecosystem. **Best for teams wanting a proven PHP-based CRM** with active development.

- **[SuiteCRM](https://github.com/salesagility/SuiteCRM)**  
  Open-source CRM for the world (PHP, AGPL-3.0, ~4,000 stars) . Fork of SugarCRM with modules for accounts, contacts, leads, opportunities, cases, documents, and quotes . **Best for organizations wanting a feature-rich, traditional CRM** with a large existing user base—but the UI is dated compared to Twenty or Relaticle.

- **[Horilla CRM](https://github.com/horilla/horilla-crm)**  
  Free and open-source **HR and CRM software** (LGPL-2.1) . Features: role-based access control, REST API with Swagger/OpenAPI docs, webhook support, CSV/Excel import/export, and 20+ languages . **Best for teams wanting CRM integrated with HR** in a single platform.

### Additional Strong Open-Source Options

- **OpenCRM (clawnify)** — Open-source HubSpot alternative for SaaS (MIT); lightweight CRM for contacts, companies, and deals with a clean API design and custom fields . **Best for SaaS companies** wanting a minimal, focused CRM.
- **Odoo CRM (OCA modules)** — Community-maintained CRM modules for Odoo (AGPL-3.0) . **Best for organizations already on Odoo ERP** wanting CRM integrated with accounting, inventory, and manufacturing.

**Frameworks for building custom systems**: For a **modern, actively developed CRM with kanban pipelines**, Twenty is the strongest option . For **full lifecycle with multi-tenancy and mobile**, BottleCRM . For **Laravel teams**, Krayin . For **lightweight AI-augmented CRM**, Relaticle . For **traditional PHP CRM with extensions**, EspoCRM . No open-source project matches Salesforce's **AppExchange ecosystem** or HubSpot's **marketing-sales-service integration** out of the box—those are commercial advantages.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Sales pipeline platforms handling customer and deal data must comply with applicable privacy regulations (GDPR, CCPA) and data security policies; **self-hosted solutions place full responsibility for security patches, backups, and uptime on the operator**.
- **Open-source sales CRM is mature and production-proven**—Twenty, BottleCRM, and EspoCRM provide viable self-hosted alternatives to commercial platforms . However, **no open-source project matches Salesforce's AppExchange ecosystem or HubSpot's integrated marketing-sales-service suite**—organizations requiring that depth should evaluate commercial platforms or plan for assembly.
- Verify license terms for commercial use; Twenty is open-source (check repository) , BottleCRM uses MIT , EspoCRM uses AGPL-3.0 , and Krayin uses MIT .

---

**Made for sales leaders, revenue operations teams, and organizations choosing their CRM stack.**  
Let's make sales pipeline tracking more open, but with clear eyes about the ecosystem breadth that commercial platforms still hold.
