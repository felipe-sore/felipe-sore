# Felipe Sore

GTM Engineer. I build customer acquisition systems in code and run them in production.

I build with AI coding agents (Claude Code) in Node.js and SQL, and I own the design, the rules and what goes to production. 
Most of my work lives in private repositories because it runs on real client data; this profile shows the activity and a few clean extracts.

## What I build

- **AUXO**, an outbound and growth-engineering platform: Node.js, Postgres, pipeline board, lead data model, AI reply classification for WhatsApp and email, analytics dashboards. Deployed on my own VPS.
- **An AI outbound engine on WhatsApp** for an AI recruitment platform: 1,000+ prospects reached, 64% reply rate, 70 meetings booked, 52 held. OpenAI, N8N, Chatwoot, Pipedrive and the Meta WhatsApp Cloud API, with quality gates and human-handoff rules.
- **Lead and reply pipelines**: intake, enrichment, follow-up selection and reply classification, integrated with CRMs through APIs and webhooks.

## Open source

Claude Code skills and tools extracted from my own sales and outbound work, rewritten without client data, with tests running on every push.

- [whatsapp-booking-agent](https://github.com/felipe-sore/whatsapp-booking-agent): a WhatsApp agent that qualifies leads and books meetings on a real calendar. Claude proposes, the code decides: slots, privacy, required fields and handoff are enforced in tested code, with evals that include a rogue model the code has to hold.
- [pipedrive-lead-qa](https://github.com/felipe-sore/pipedrive-lead-qa): checks Pipedrive leads before the first outreach (identity, company, name, casing, duplicates, phone and WhatsApp), one report, one approval, dry run by default. Never completes an activity, so it never sends a message by accident.
- [lead-list-cleanup](https://github.com/felipe-sore/lead-list-cleanup): turns a messy prospect export into a usable list: dedupe, one contact per company, E.164 phones, seniority segments, offline email checks and an integrity check after LinkedIn enrichment.
- [digital-footprint](https://github.com/felipe-sore/digital-footprint): audits a company's public digital presence (website, SEO, social, paid media, reputation) and writes a report for the client. The agent researches, the code decides what the report may claim: a blocked source is "not identified", never zero, and an estimate has to show its basis.

## Stack

Node.js, JavaScript, PostgreSQL, REST APIs and webhooks, Docker, Linux, Git, OpenAI, N8N, Pipedrive, HubSpot, Clay, WhatsApp Business Cloud API.

## Contact

[linkedin.com/in/felipesore](https://linkedin.com/in/felipesore) | felipesore@gmail.com
