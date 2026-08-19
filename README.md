<a href="https://yuriqueiroz.com.br">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="dark_mode.svg?v=35f93c9" />
    <source media="(prefers-color-scheme: light)" srcset="light_mode.svg?v=35f93c9" />
    <img alt="Yuri Queiroz — Software Engineer profile card with ASCII portrait, stack, selected work, and GitHub statistics" src="light_mode.svg?v=35f93c9" width="100%" />
  </picture>
</a>

# Yuri Queiroz

**Software Engineer — .NET · TypeScript · React/Next.js.**

TypeScript · React/Next.js · Node.js · C#/.NET · Python · SQL — based in Brazil, working in PT-BR and EN.

I build software end to end: data model, backend, UI, integrations, tests, deploy. Before writing code full time I spent 8+ years running high-pressure retail operations — conversion, staffing, inventory, daily targets — so I'm at my best turning a messy real-world workflow into a working system, and measuring the result instead of assuming it.

**Currently:** Full-Stack Software Engineer at [PageForce](https://pageforce.com.br) · back-end work under NDA (.NET 8 / EF Core / MySQL) · operating [Entrevista Mapeada](https://entrevistamapeada.com.br) in production · evolving [Escala que Converte](https://escalaqueconverte.com.br)

## Recent client work

Client repos are private and names are withheld by agreement. I'm happy to walk through architecture and sanitized code in a call.

- **Back-end module for a platform in a regulated market** (Brazil, under NDA) — .NET 8, EF Core, MySQL. Spec-driven implementation with risk-tiered review and property-based tests (xUnit + FsCheck). The same conventions, in the open: [retail-orders-api](https://github.com/Lob0Garou/retail-orders-api).
- **Logistics & inventory analytics dashboard** (national retail chain) — turns ERP and spreadsheet exports into replenishment and transfer decisions by crossing stock coverage and logistics flow with each category's share of revenue. React, Recharts, CSV/spreadsheet parsing. Built and evolved across multiple store operations.
- **Sales performance calendar** (retail leadership) — generates a month view that distributes the sales target across days using the store's historical sales curve and commercial dates, then tracks target vs. actual per day. Rebuilt generic in public: [code](https://github.com/Lob0Garou/sales-performance-calendar) · [live demo](https://lob0garou.github.io/sales-performance-calendar/).
- **Marketplace MVP for a gaming startup** — Next.js, TypeScript, mock-first architecture designed to swap in the real backend without UI rewrites. Typed end to end, green build.
- **Desktop automation assistant** — Python, Tesseract OCR, keyboard/mouse control with failsafe hotkeys and per-machine calibration config.
- **Data pipeline for a sports-analytics spreadsheet product** — Google Apps Script importing CSV exports from Drive into structured analysis tabs, safe to re-run.

## Products I built and operate

- **[Entrevista Mapeada](https://entrevistamapeada.com.br)** — B2C interview-prep product, live in production. Next.js + Turso (libSQL) + Cloudflare R2 + Resend. Payment webhook triggers an automated document-generation pipeline (LLM with output validation) feeding a customer delivery portal.
- **Escala que Converte** — retail scheduling intelligence: parses store sales and staffing spreadsheets, scores coverage in 15-minute slots, and optimizes schedules against each seller's conversion curve. React + Node. Used across 40+ stores, with a historical observed gain of +0.86 percentage point in conversion in the analyzed context. ([case](https://yuriqueiroz.com.br/projetos/escala-que-converte))
- **[PageForce](https://pageforce.com.br)** — websites and growth systems for local businesses. Vite/React/Tailwind/GSAP landing pages, Next.js client portal, n8n automations, and an internal pipeline built on the Claude Agent SDK — with tool whitelists, structured logs and human review on everything that reaches a client.

## Public code

- **[retail-orders-api](https://github.com/Lob0Garou/retail-orders-api)** — production-grade .NET 8 reference API: retail orders and stock with exact-cent installment math, no-oversell optimistic concurrency, a strict order state machine, property-based tests (xUnit + FsCheck) and Testcontainers integration tests against real MySQL. This is how I build client back-ends.
- **[sales-performance-calendar](https://github.com/Lob0Garou/sales-performance-calendar)** — splits a monthly sales target across days via weekday weights and commercial-date boosts. Largest-remainder allocation: daily targets sum to the monthly target exactly, enforced by a 300-case randomized test. Vanilla JS, zero dependencies, `node --test`. ([live demo](https://lob0garou.github.io/sales-performance-calendar/))
- **[pageforce-seo-cro-checklist](https://github.com/Lob0Garou/pageforce-seo-cro-checklist)** — interactive SEO/CRO audit checklist with live scoring. Single-file vanilla HTML/CSS/JS, zero dependencies, no build step, deployed via GitHub Pages. ([live demo](https://lob0garou.github.io/pageforce-seo-cro-checklist/))

Most of my work is client delivery, so it stays in private repositories on purpose. This profile shows enough to evaluate how I build; the rest I show on request.

## Stack

- **Languages:** TypeScript/JavaScript, C#, Python, SQL
- **Frontend:** React, Next.js, Vite, Tailwind, GSAP, Recharts
- **Backend:** Node.js, .NET 8 / EF Core, REST APIs, webhooks
- **Data:** PostgreSQL, MySQL, Turso/libSQL, Supabase, spreadsheet/CSV/PDF parsing
- **Testing:** xUnit, FsCheck (property-based), Playwright
- **Infra:** Vercel, Cloudflare R2, GitHub Pages, CI on GitHub
- **AI tooling:** LLM APIs and agent pipelines (Claude Agent SDK) treated as engineering components — logged, sandboxed, human-reviewed — never as a black box owning business rules

## Open for work

Freelance and contract. Best fit:

- Web apps and MVPs (Next.js/React or .NET)
- Automation of real business processes — data pipelines, integrations, bots
- Dashboards and internal tools over messy operational data
- Conversion-focused websites and landing pages

Contact: [yuriqueiroz.com.br](https://yuriqueiroz.com.br)
