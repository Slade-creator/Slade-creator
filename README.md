<div align="center">

# Elton Chiwala

**I build backend systems that have to be right: auth, data integrity, retrieval, in places where getting it wrong actually costs someone something. National ID. Legal research. Mine safety. Field finance.**

[GitHub](https://github.com/Slade-creator) · [LinkedIn](https://www.linkedin.com/in/elton-chiwala-9924b1261/) · [eltonchiwala@gmail.com](mailto:eltonchiwala@gmail.com)

</div>

---

I'm a backend developer working across national ID, legal tech, mining safety, and humanitarian finance. My background is auth systems, database design, API architecture, built for domains where getting it wrong has real consequences. I'm currently based in Zambia, finishing a degree at Mulungushi University alongside that work, and pulling what I know into AI engineering: retrieval, evaluation, systems that check whether a model is actually right instead of just sounding right.

## What these projects have in common

Four different domains. Same question every time: what actually breaks if auth or data integrity is wrong here?

### ZDID — Zambia Digital ID
*ZAMREN Hackathon, team of three*

National digital identity issuing cryptographically signed IDs. I built citizen enrollment and the Registration Officer approval flow start to finish, plus the ECDSA P-256 signing pipeline for IDs and time-limited QR payloads, and role-gated audit logging across CITIZEN, RO, REGISTRAR, and SUPERVISOR. This is also where I learned signing, verification, and key management, mostly by getting it wrong first.

**Stack:** Django · FastAPI · PostgreSQL/MySQL · Next.js · React Native (Capacitor) · ECDSA
[→ Repository](https://github.com/nosiemaker/digital-id-prototype.git)

### MineOps — safety & compliance for large-scale mining
*Built for the Minepreneur Innovation Challenge (MIC) Zambia 2026*

An internal compliance console. It's not styled to look like a SaaS product because it isn't one. I own the auth module: Axios calls carry an in-memory access token and a localStorage refresh token, refreshed proactively before it expires, with de-duplication so two requests firing at once don't both try to refresh and step on each other.

**Stack:** FastAPI · Django ORM · React/TypeScript · JWT/RBAC

### BH Finder — student housing marketplace
Role-scoped flows for students, landlords, and admins. JWT auth with httpOnly cookies and automatic refresh. A landlord verification pipeline with document upload and admin approval. A full booking lifecycle, request, approve or reject, renew, cancel, sitting behind Caffeine caching and Bucket4j rate limiting.

**Stack:** Java (Spring Boot) · PostgreSQL (Supabase) · Spring Security · React · TypeScript · AWS
[→ Repository](https://github.com/Slade-creator/bhfinder.git)

### Field Finance Tracker — modeled on World Vision Zambia
Expense tracking for humanitarian field operations, where the thing you're actually fighting is bad connectivity. Layered backend (Controller to Service to Repository) with approval routing that changes depending on expense type, and offline-safe submissions using client-generated IDs so the server can sort out duplicates once a connection comes back.

**Stack:** FastAPI · SQLModel · SQLite · React Native (Expo) · JWT
[→ Repository](https://github.com/Slade-creator/world_vision_prototype.git)

### ICTAZ MU Chapter Financial Tracker
*Built for my role as Treasurer, in active use for chapter finance*

Offline-first Android app with incremental Google Drive backup, plus a FastAPI backend that turns the ledger into AI-generated financial insights and branded PDF reports.

**Stack:** Java (Android) · Room · FastAPI · OpenRouter · ReportLab
[→ Repository](https://github.com/Slade-creator/financial_tracker.git)

---

## Where I'm headed

I want to do this kind of work at production scale: less wrapping an API call in a nice UI, more the retrieval, auth, and data-correctness work underneath it, on problems where a confidently wrong model is a real cost, not an inconvenience.

## Tech Stack

`Python` `TypeScript` `Java` — `FastAPI` `Django` `Spring Boot` — `React` `Next.js` `React Native` — `PostgreSQL` `pgvector` `Redis` `MySQL` `SQLite` — `Docker` `AWS` `JWT` `ECDSA`

---

![Elton's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Slade-creator&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Slade-creator&layout=compact&hide_border=true&theme=default)
