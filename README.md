<h1 align="center">Hi, I'm Noby Tebulo</h1>
<h3 align="center">Full-Stack Web Developer · React · PHP / Laravel · REST APIs</h3>

<p align="center">
  Software engineer in Harare, Zimbabwe — I build production web platforms end-to-end:
  database schema, REST APIs, auth, payments, polished React/Tailwind dashboards, and the
  deploy pipeline that puts it all online.
</p>

<p align="center">
  <a href="https://noby.aizim.co.zw"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-noby.aizim.co.zw-047857?style=flat-square"></a>
  <a href="https://www.linkedin.com/in/nobytechy/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-nobytechy-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:nobytechy@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-nobytechy@gmail.com-475569?style=flat-square"></a>
  <img alt="Location" src="https://img.shields.io/badge/Harare,%20Zimbabwe-CAT%20(UTC%2B2)-475569?style=flat-square">
  <img alt="Available" src="https://img.shields.io/badge/Open%20to%20remote%20work-Yes-10b981?style=flat-square">
</p>

---

## Currently

Building **[ManishaPay](https://pay.aizim.co.zw)** — a middleware that fixes the integration headaches developers
hit with the **PayNow Zimbabwe** payment gateway. Hash math, decimal/phone normalisation, signed retries,
drop-in checkout widget, simulated test mode that requires no PayNow account, all wrapped in a clean
React dashboard. Code at [github.com/nobytechy/manishapay](https://github.com/nobytechy/manishapay).

In parallel, maintaining the **AiZim** ERP — a 996-PHP-file production platform serving a Zimbabwean
hospitality group — with an embedded Claude assistant that lets non-technical users propose and
preview UI changes via natural language.

---

## Tech stack

**Frontend**
&nbsp;
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Framer%20Motion](https://img.shields.io/badge/Framer%20Motion-0055FF?style=flat&logo=framer&logoColor=white)

**Backend**
&nbsp;
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**Database & infra**
&nbsp;
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![cPanel](https://img.shields.io/badge/cPanel-FF6C2C?style=flat&logo=cpanel&logoColor=white)

**Tooling & integrations**
&nbsp;
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic%20API-D97706?style=flat&logo=anthropic&logoColor=white)
![PayNow](https://img.shields.io/badge/PayNow%20Zimbabwe-047857?style=flat)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat&logo=wordpress&logoColor=white)

---

## Featured work

| Project | Stack | What it does |
|---|---|---|
| **[ManishaPay](https://pay.aizim.co.zw)** · [code](https://github.com/nobytechy/manishapay) | React 18 · Node 20 · Express · Supabase · libsodium | PayNow Zimbabwe middleware. Server-side SHA-512 hash, encrypted credential vault, drop-in checkout JS, signed webhooks, simulated test mode that requires no PayNow account. PHP + Node SDKs published. |
| **[AiZim ERP](https://aizim.co.zw)** | PHP 7.4 · MySQL · jQuery · cPanel | Production ERP for a hospitality group — branches, regions, stock, expenses, payroll, change-request workflow with HTML preview. Embedded AI assistant via Anthropic tool-use. |
| **[Chikoro](https://chikoro.aizim.co.zw)** | React 18 · Vite · Supabase RLS · PWA | Multi-tenant school management. Each school on its own subdomain with full row-level security; offline-first for low-connectivity classrooms. |
| **[Speedify](https://upgrade.ealliance.net/taxi/)** | React + TypeScript · Vite · Supabase · Leaflet · PayNow | InDrive-style ride-hailing for Zimbabwe. Negotiated fares between rider and driver, real-time map, in-app PayNow payments. |
| **[PriceScout](https://upgrade.ealliance.net/Claude/PriceScout/)** | React · Vite · Supabase · service worker | Offline-first price comparison built for load-shedding reality. Optional AI summary via server-side proxy. |
| **[Portfolio](https://noby.aizim.co.zw)** | React 18 · Vite · Tailwind · Supabase | Self-managed portfolio — projects and posts editable through a login-gated admin panel, no redeploy required for content changes. |

---

## Things I'm comfortable owning end-to-end

- REST API design — idempotency keys, versioning, signed webhooks, HMAC-SHA256
- Multi-tenant SaaS with Postgres RLS, role-based admin/operator/end-user dashboards
- Payment integrations (PayNow Zimbabwe) — hash math, tokenisation, retry queues, dispute flow
- Auth — Supabase Auth, JWT, bcrypt, libsodium envelope encryption for secrets at rest
- Deploys to cPanel / shared hosting (Apache, LiteSpeed, Phusion Passenger), Docker on Railway/Fly
- Embedding LLM features (Anthropic tool-use) into existing apps without rewriting them
- Writing docs and runbooks that make the system handoff-able

---

## GitHub

<p align="left">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=nobytechy&show_icons=true&hide_border=true&bg_color=00000000&title_color=047857&icon_color=10b981&text_color=475569" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nobytechy&layout=compact&hide_border=true&bg_color=00000000&title_color=047857&text_color=475569" alt="Top languages" />
</p>

---

## Get in touch

Available for remote contracts and full-time roles. Most comfortable in the React + Node/PHP +
Postgres/MySQL space, especially anything fintech-adjacent or multi-tenant SaaS for emerging markets.

- **Email:** [centuriongrill@gmail.com](mailto:centuriongrill@gmail.com)
- **Portfolio:** [noby.aizim.co.zw](https://noby.aizim.co.zw)
- **LinkedIn:** [linkedin.com/in/nobytechy](https://www.linkedin.com/in/nobytechy/)
