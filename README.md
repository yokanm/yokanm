# Ayokanmi Ogunyebi

Full-Stack Software Engineer · React · Node.js · TypeScript · Security-First

I build full-stack systems with a focus on secure authentication, authorization, testing, and production-oriented infrastructure. My work spans React/Next.js frontends, Node.js/Express APIs, PostgreSQL, and deployment pipelines — with security baked in from the start, not bolted on at the end.

---

## Featured Project: PostBoard

**Full-Stack Multi-Tenant Recruitment Platform** — 101 API endpoints, 82 frontend routes, 5 RBAC portals

PostBoard is a multi-tenant job board and applicant tracking system connecting Candidates, Recruiters, Companies, and a platform Super-Admin through five role portals. One React client talks to a versioned Express REST API built on PostgreSQL, Redis, and BullMQ background workers.

| Component | Repository | Stack |
|---|---|---|
| Frontend | [yokanm/postboard](https://github.com/yokanm/postboard) | React 19, TypeScript, Vite, TanStack Query, Zustand, Tailwind CSS |
| Backend API | [yokanm/jobboard](https://github.com/yokanm/jobboard) | Express 5, Prisma, PostgreSQL, Redis, BullMQ, Docker |

**What it demonstrates:**
- Dual-entity JWT signing with Argon2id hashing and refresh-token family rotation
- RBAC across five actors with IDOR and authorization test suites
- 34 Jest suites (~7,230 LOC), Playwright E2E, k6 load testing
- Containerized via Docker Compose (API + worker + Postgres + Redis)
- GitHub Actions CI spinning up real Postgres and Redis for integration tests

---

## Engineering Focus

- Multi-tenant architecture with role-based access control
- Secure authentication: JWT rotation, Argon2id, httpOnly cookies, RBAC middleware
- Production-grade APIs: validation, rate limiting, input sanitization, Helmet headers
- Testing strategy: unit, integration, E2E, load testing, security/IDOR test suites
- CI/CD pipelines with containerized test environments
- Observability: structured logging (Winston), error tracking (Sentry), request tracing, health endpoints

---

## Core Stack

| Layer | Technologies |
|---|---|
| Frontend | React 19, Next.js 15, TypeScript, Vite, Tailwind CSS v4, TanStack Query, Zustand |
| Backend | Node.js, Express 5, Prisma ORM, REST API design, Zod validation |
| Database | PostgreSQL, Redis, Supabase |
| Infrastructure | Docker + Compose, GitHub Actions, Vercel, Netlify, Sentry |
| Testing | Jest, Supertest, Vitest, Playwright, MSW, k6, autocannon |
| Security | Argon2id, JWT rotation, RBAC, httpOnly cookies, Helmet, DOMPurify, rate-limit-redis |

---

## Other Projects

**[Cyber Gadget](https://github.com/yokanm/Cyber-gadget)** — Production e-commerce store with Next.js 15 App Router, 200+ products, URL-persisted filters, Supabase (PostgreSQL), and a 3-step checkout. [Live demo](https://cyber-gadget-v2.vercel.app/)

**[TaskFlow](https://github.com/yokanm/taskflow)** — Cross-platform (iOS, Android, web) task manager with React Native + Expo, Express/Prisma backend, httpOnly refresh cookies, in-memory access tokens, and optimistic UI updates.

**[Portfolio](https://github.com/yokanm/portfolio)** — This site. Built with React 19, TypeScript, Tailwind CSS v4, and Vite. Deployed on Netlify.

---

## Certifications

- **Google Cybersecurity Professional Certificate** — Coursera, 2026
- **The Frontend Developer Career Path** — Scrimba, 2023

---

## Portfolio

[kanmiportfolio.netlify.app](https://kanmiportfolio.netlify.app/)

---

## Contact

- **Email:** ogunyebiayokanmi@gmail.com
- **LinkedIn:** [linkedin.com/in/ayokanmi-ogunyebi](https://linkedin.com/in/ayokanmi-ogunyebi)
- **X/Twitter:** [@kayspice3](https://twitter.com/kayspice3)

---

Open to full-stack and security engineering roles. Remote-first.
