# Awesome-One-Person-Unicorn-Stack

# Top One-Person Unicorn Stack Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Solo Founder Infrastructure, AI-Assisted Shipping & Zero-Headcount Operations*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** that together form the **One-Person Unicorn Stack** — the combination of AI coding agents, backend-as-a-service, payments, auth, email, analytics, and project management that lets a single founder build, launch, and scale a software business without hiring. These tools have collapsed the cost and time required to ship production software from team-years to solo-weeks.

**Examples** include Cursor, Lovable, v0 by Vercel, Replit Agent, Bolt.new, Supabase, Stripe, GitHub Copilot, Linear, and Resend (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting each layer of the solo stack — ideal for founders who want zero per-seat costs, full data ownership, and no vendor lock-in on the infrastructure that runs their business.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Cursor](https://cursor.com/)**  
  Leading AI code editor with agent mode, codebase-aware chat, and multi-file edits. Bundled into The X Subscription alongside Grok and X Premium, with Cursor Start at ₹649/month (~$7) in India and Pro tier at $30/month including X Premium+ .

- **[Lovable](https://lovable.dev/)**  
  Prompt-to-app builder with **Lovable Cloud** built-in backend: managed PostgreSQL, authentication, file storage, and region selection. Three modes — Build, Plan, Chat — with Cloud permission model (Always allow / Ask each time / Never allow) .

- **[v0 by Vercel](https://v0.app/)**  
  Turns text prompts into production-ready React components trained on React, Tailwind, and shadcn/ui best practices. Next.js 16 runtime with Turbopack, React 19.2 features, and MCP server support .

- **[Replit Agent](https://replit.com/)**  
  Turns ideas into apps, designs, slides, and data visualizations from plain language. **Agent 4** adds Design Canvas, Plan mode with approval gating, parallel task execution, and teammate collaboration. Connects to BigQuery, Linear, Slack, and Notion directly from chat .

- **[Bolt.new](https://bolt.new/)**  
  Prompt-to-production platform on Microsoft Azure and Microsoft 365. Digital Virgo case study: time to launch reduced from 12 months to 3-4 months, team size from 4-5 people to one primary architect, one codebase for web/iOS/Android across 50 countries .

- **[Supabase](https://supabase.com/)**  
  Open-source Firebase alternative with managed PostgreSQL, real-time subscriptions, authentication, storage, edge functions, and auto-generated APIs. Free tier and $25/month Pro plan. The default backend for solo AI-built apps .

- **[Stripe](https://stripe.com/)**  
  Payments infrastructure with Checkout, Billing, subscriptions, tax, and Invoicing. Handles global payment methods, fraud detection (Radar), and revenue recovery. Standard 2.9% + $0.30 per transaction .

- **[GitHub Copilot](https://github.com/features/copilot)**  
  AI pair programmer with code completion, chat, and agent mode across VS Code, JetBrains, Visual Studio, and GitHub.com. Moving to usage-based AI Credits billing in June 2026 .

- **[Linear](https://linear.app/)**  
  Fast, keyboard-driven issue tracking and project management built for high-velocity product teams. Free tier for small teams, with Linear for Startups offering discounts and credits .

- **[Resend](https://resend.com/)**  
  Developer-first transactional email API with React Email templates, deliverability tooling, and a generous free tier (3,000 emails/month). Built by the team behind React Email .

## Open-Source GitHub Projects

- **[Dittofeed](https://github.com/dittofeed/dittofeed)**  
  **Open-source customer engagement platform** positioned as an alternative to Iterable and Customer.io. Features drag-and-drop journey builder, segmentation interface, web-based template editor, git-based workflows, testing SDK, OpenTelemetry integration, and self-hostable platform. MIT licensed. The marketing automation layer for a solo founder running lifecycle email without per-contact pricing.

- **[Autumn](https://github.com/useautumn/autumn)**  
  **Open-source pricing and billing layer between Stripe and your application.** Supports subscriptions, credit systems, usage-based models, custom plans, and hybrid pricing. Three core functions (`/attach`, `/check`, `/track`) embed billing logic with minimal code. The open alternative to Stripe Billing's usage-based tier .

- **[Lago](https://github.com/getlago/lago)**  
  **Open-source usage-based billing and subscription management** positioned as an alternative to Stripe Billing and Chargebee. Send usage events via API; Lago meters them, applies plans and taxes, and issues PDF invoices. Supports subscriptions, credits, hybrid pricing, and payment provider integrations (Stripe, Adyen, GoCardless). AGPL-3.0 licensed .

- **[BillaBear](https://github.com/billabear/billabear)**  
  **Open-source subscription management and billing** with Stripe integration, tax management (EU VAT, VAT Sense), workflows for async tasks, and multi-currency support. Includes LTV and churn reports, dunning, vouchers, credit notes, and customer-facing frontend via Stripe.js. Symfony/PHP with Docker deployment .

- **[Documenso](https://github.com/documenso/documenso)**  
  **Open-source DocuSign alternative** for e-signatures. AGPL-3.0 licensed with self-hosting. Essential for solo founders needing contract signing without per-envelope pricing.

- **[Plane](https://github.com/makeplane/plane)**  
  **Open-source project management and issue tracking** positioned as a Jira and Linear alternative. MIT licensed core with self-hosted Community Edition. Good for founders wanting their own data.

- **[Ghost](https://github.com/TryGhost/Ghost)**  
  **Open-source publishing platform with native memberships, subscriptions, and newsletters.** Built-in Stripe integration for paid tiers. Self-hosted edition free under MIT license. The content and audience layer for solo newsletter businesses.

- **[Listmonk](https://github.com/knadh/listmonk)**  
  **Open-source newsletter and mailing list manager.** Self-hosted with PostgreSQL. Handles large subscriber lists with no per-contact pricing. AGPL-3.0 licensed.

- **[Umami](https://github.com/umami-software/umami)**  
  **Simple, self-hosted open-source analytics** alternative to Google Analytics. Privacy-focused with no cookie banners required. MIT licensed.

- **[Plausible](https://github.com/plausible/analytics)**  
  **Lightweight, privacy-focused open-source web analytics.** AGPL-3.0 licensed with self-hosting. Used by solo founders who want analytics without the Google dependency.

- **[Cal.com](https://github.com/calcom/cal.com)**  
  **Open-source scheduling infrastructure** alternative to Calendly. AGPL-3.0 licensed with self-hosting. Handles booking, payments, and routing without per-seat fees.

### Additional Strong Open-Source Options

- **[Coolify](https://github.com/coollabsio/coolify)** — Self-hostable PaaS alternative to Vercel, Heroku, and Netlify. Deploy static sites, databases, and full-stack apps on your own server for the cost of a VPS. Apache 2.0 licensed.
- **[Dokku](https://github.com/dokku/dokku)** — Minimal Heroku alternative with `git push dokku` workflow. MIT licensed.
- **[Dokploy](https://github.com/Dokploy/dokploy)** — Open-source alternative to Vercel and Netlify with modern web UI and Docker Compose support.
- **[Kamal](https://github.com/basecamp/kamal)** — CLI deployment tool over SSH with no dashboard or control plane. 37signals reported cutting cloud bills from $3.2M to $1.3M annually using this approach.
- **[Keycloak](https://github.com/keycloak/keycloak)** — Open-source identity and access management with SSO, OIDC, SAML, and social login. Apache 2.0 licensed.
- **[Authelia](https://github.com/authelia/authelia)** — Open-source authentication and authorization server with 2FA/MFA.
- **[Authentik](https://github.com/goauthentik/authentik)** — Open-source identity provider with MFA and SSO.
- **[Novu](https://github.com/novuhq/novu)** — Open-source notification infrastructure with unified API for email, SMS, push, in-app, and chat.
- **[OpenHands](https://github.com/OpenHands/OpenHands)** — Autonomous AI coding agent platform. 68K+ GitHub stars, 77.6% on SWE-Bench.
- **[Cline](https://github.com/cline/cline)** — Open-source autonomous coding agent for VS Code. 62K+ stars.
- **[Aider](https://github.com/Aider-AI/aider)** — Terminal-based AI pair programming with git integration. 49K+ stars.
- **[OpenCode](https://github.com/anomalyco/opencode)** — Terminal-native AI coding agent. 172K+ stars — the most-starred open-source coding agent.
- **[vLLM](https://github.com/vllm-project/vllm)** or **[Ollama](https://github.com/ollama/ollama)** — Self-hosted LLM inference for founders running models locally.
- **Metabase / Apache Superset** — Open-source BI for internal dashboards.
- **PostHog** — Open-source product analytics with session replay and feature flags.

**Frameworks for building custom systems**: Combine **Coolify** or **Dokku** for deployment, **Supabase** or **Keycloak** for auth and database, **Autumn** or **Lago** for usage-based billing, **Listmonk** or **Ghost** for audience and email, **Plausible** or **Umami** for analytics, **Cal.com** for scheduling, **Documenso** for e-signatures, and **OpenCode/Cline/Aider** for AI-assisted development to build a complete self-hosted solo founder stack with zero per-seat costs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- The one-person unicorn stack involves operating business-critical infrastructure. Self-hosted open-source solutions require proper security hardening, backups, and monitoring — **you become the on-call engineer for everything you replace with open source.** Cloud SaaS alternatives shift that burden to the vendor at the cost of subscription fees.
- Payment processing, tax compliance, and e-signature tools have regulatory requirements (PCI-DSS, PSD2, eIDAS) that must be satisfied regardless of which layer is self-hosted.

---

**Made for solo founders, indie hackers, bootstrapped operators, and developers building businesses without headcount.**  
Let's make the one-person unicorn stack more open, affordable, and founder-friendly.
