# Aaron C. Zimmerman

**CFO who builds.** I design and run the AI-built systems a licensed cannabis cultivator in Denver operates on: production analytics, state compliance, reconciliation and cash. I specify them, validate them against real history, and own whether they're right. Claude, n8n and GitHub Actions do the typing.

Most of my repositories are private because they run on company data. The contribution graph is real.

## Production systems

**Yieldbook** · production analytics platform
Next.js / TypeScript, Supabase, Clerk RBAC, Vercel. 18 pages, 10 API routes, 300+ commits, live since February 2026. Replaced hand-assembled spreadsheets, and fixed a structural denominator error that produced the facility's first benchmark-comparable grams-per-square-foot figures.

**METRC harvest workflow** · state compliance automation
44-node n8n workflow running weekdays at 05:45 on a hardened VPS, moving ~140 plants a day into Colorado's track-and-trace system. Replayed against 147 days and 18,205 plants before go-live: 96.5% agreement, with the rule correct in every disagreement.

**QuickBooks ↔ HubSpot** · CRM-to-ledger automation
Pipeline reconciliation between HubSpot deals and QuickBooks invoices, a HubSpot-to-QuickBooks customer builder on a Vercel cron, and purchase-order-to-deal entry.

**Cash forecasting** · treasury
A live QuickBooks-integrated forecast with customer-level scenarios, plus an unattended weekly pipeline that turns a ledger export into a projected cash calendar.

**Close automation** · accounting
Claude-built bank reconciliation that matches the statement to QuickBooks and produces the close packet.

## Public showcase repos

Cleaned-up versions of production work, with synthetic data so anyone can run them:

- [metrc-harvest-batching](https://github.com/azimm291955/metrc-harvest-batching) · the harvest batching engine and the replay check that validated it
- [po-to-crm-deal](https://github.com/azimm291955/po-to-crm-deal) · purchase-order PDFs to CRM deals, every number tied out first
- [hubspot-qbo-customer-sync](https://github.com/azimm291955/hubspot-qbo-customer-sync) · HubSpot requests to QuickBooks customers on a Vercel cron

## Side builds

**Titans of the Line** · a railroad-building game · [titansoftheline.com](https://titansoftheline.com)

## Stack

TypeScript · Next.js · Python · n8n · GitHub Actions · Supabase / PostgreSQL · Vercel · QuickBooks Online API · HubSpot API · METRC · Claude / Anthropic SDK

## How I work

Computation automated, commitment owned. Nothing goes to production until it has been replayed against real history.

[LinkedIn](https://www.linkedin.com/in/aaron-zimmerman-35ab6762)
