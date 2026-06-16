<div align="center">

# Elton Chiwala

**Backend developer building civic and financial infrastructure**

[![GitHub](https://img.shields.io/badge/GitHub-Slade--creator-181717?style=flat&logo=github&logoColor=white)](https://github.com/Slade-creator)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Elton%20Chiwala-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/elton-chiwala-9924b1261/)
[![Email](https://img.shields.io/badge/Email-eltonchiwala%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:eltonchiwala@gmail.com)

</div>

---

I'm a final-year ICT student at Mulungushi University. My background is backend development: authentication, database design, API architecture. I've used that on four projects covering national digital identity, fintech, student housing, and humanitarian field operations. Lately I've been shifting toward AI engineering and the infrastructure and system design work underneath it.

## Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Backend Frameworks**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)

**AI / ML**

![OpenRouter](https://img.shields.io/badge/OpenRouter-AI%20Integration-6E56CF?style=flat&logo=openai&logoColor=white)
![Anthropic Claude](https://img.shields.io/badge/Claude%20API-D97757?style=flat&logo=anthropic&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-RAG%2FEmbeddings-4169E1?style=flat&logo=postgresql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=flat&logo=react&logoColor=black)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

**Infrastructure & Auth**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892CA0?style=flat&logo=podman&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)

---

## Projects

### ZDID — Zambia Digital ID System
*ZAMREN Hackathon project, built with a team of four*

A national digital identity platform issuing cryptographically signed Digital IDs over a hybrid Django + FastAPI backend.

**What I built:**
- Citizen enrollment and Registration Officer approval flow end to end
- Django ORM data layer with FastAPI as a thin async API surface
- ECDSA P-256 signing pipeline for Digital IDs and time-limited QR payloads
- Birth registration module with auto-generated serial numbers
- Role-gated audit logging across CITIZEN / RO / REGISTRAR / SUPERVISOR roles
- Digital ID wallet UI with a 3D flip card and dynamic verification status

**Stack:** Django · FastAPI · PostgreSQL/MySQL · Next.js · React Native (Capacitor) · Web Crypto API · ECDSA

[→ View Repository](https://github.com/nosiemaker/digital-id-prototype.git)

---

### BH Finder — Student Housing Marketplace

A full-stack marketplace connecting students with verified boarding house listings, with role-scoped flows for students, landlords, and admins.

**What I built:**
- JWT authentication with httpOnly cookies and automatic token refresh
- Landlord verification pipeline with document upload and admin approval
- Listing search/filter with Caffeine caching and Bucket4j rate limiting
- Booking lifecycle: request, approve or reject, renew, cancel
- Full React frontend, deployed on AWS

**Stack:** Java (Spring Boot) · PostgreSQL (Supabase) · Spring Security · React · TypeScript · AWS

[→ View Repository](https://github.com/Slade-creator/bhfinder.git)

---

### ICTAZ MU Chapter Financial Tracker
*Built for my role as Treasurer, ICTAZ Mu Chapter*

An offline-first Android financial tracker with an AI-powered reporting backend, in active use for chapter finance.

**What I built:**
- Offline-first Room (SQLite) data layer with incremental Google Drive backup
- FastAPI backend generating AI financial insights via OpenRouter
- Multi-criteria filtering, approvals workflow, branded PDF report export
- App-lock security with PIN and biometric authentication

**Stack:** Java (Android) · Room · FastAPI · Python · OpenRouter AI · ReportLab

[→ View Repository](https://github.com/Slade-creator/financial_tracker.git)

---

### Field Finance Tracker — World Vision Zambia
*Portfolio project*

A role-based mobile app for tracking field-level expenses and budget utilisation across a humanitarian program.

**What I built:**
- Layered backend: Controller → Service → Repository, with JWT + RBAC middleware
- Sequential approval routing (Finance-only vs. Finance-then-DME) by expense type
- Offline-safe submissions using client-generated IDs for server-side deduplication
- React Native (Expo) frontend with a custom humanitarian-themed design system

**Stack:** FastAPI · SQLModel · SQLite · React Native (Expo) · TypeScript · JWT

[→ View Repository](https://github.com/Slade-creator/world_vision_prototype.git)

## Currently Learning

- AI engineering: RAG pipelines, embeddings, agentic workflows. LexaZM is where most of this is coming from right now.
- Infrastructure and system design: scalability, reliability, deployment architecture, the stuff underneath the APIs.
- Cryptographic identity systems: signing, verification, key management, picked up while building ZDID's ID-signing and QR flow.

## Where I'm Headed

I want to do AI engineering that's actually built on solid infrastructure rather than an API call wrapped in a UI. National ID, legal tech, fintech, housing, humanitarian finance: different domains, but each one needed data and auth handled correctly or the whole thing falls apart. Right now I'm looking for an industrial attachment where I can do that kind of work at production scale.

---

## GitHub Stats

![Elton's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Slade-creator&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Slade-creator&layout=compact&hide_border=true&theme=default)

---

## Contact

- **GitHub:** [@Slade-creator](https://github.com/Slade-creator)
- **LinkedIn:** [linkedin.com/in/elton-chiwala](https://www.linkedin.com/in/elton-chiwala-9924b1261/)
- **Email:** eltonchiwala@gmail.com
