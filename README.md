# Rizwanul Haque

Full-stack engineer and engineering leader. 13+ years building production systems end to end — the app, the services behind it, and the pipeline that ships both.

Most teams lose time at the seam between the app and the server. I've worked both sides for over a decade, so I can design the API and the screen together instead of negotiating across a handover.

## What I work with

**Mobile** — Kotlin, Jetpack Compose, Kotlin Multiplatform, Swift. Native Android and iOS apps used by millions, including lead roles on banking and consumer products.

**Backend** — Java/Spring Boot, C#/.NET, Node.js, Python/Django. REST APIs, authentication, payments and integrations, relational data modelling, performance work.

**Frontend** — React, TypeScript, Ember. Responsive UI, state management, accessibility.

**Platform** — AWS, Kubernetes, Docker, CI/CD. I own the deploy path, not just the code that goes through it.

## Leading teams

I led the MMR squad at Barclays US — a cross-functional team of Android, iOS, backend, frontend and QA engineers — and have spent years in engineering management alongside hands-on delivery. The work I care most about is removing single points of knowledge: a team where only one person can touch a system is a team with a bus factor of one.

## Selected work

Reference implementations, each built around one hard problem rather than a
feature list. All run, all have CI, and each README explains the decisions and
the bugs that only appeared once it was running.

| Repository | The hard part |
| --- | --- |
| [stockroom](https://github.com/rizwan-dev/stockroom) | Spring Boot 3.5 + Next.js 16 — concurrent orders for the last unit resolve to exactly one sale, proved by a 20-thread test against real PostgreSQL |
| [pulse](https://github.com/rizwan-dev/pulse) | Ktor WebSockets + Next.js — a dropped client resumes from a sequence cursor; one slow consumer cannot stall the broadcast |
| [pulse-mobile](https://github.com/rizwan-dev/pulse-mobile) | Kotlin Multiplatform + Compose Multiplatform — Android and iOS sharing the client protocol and the UI, tests running on both the JVM and native iOS |

## Teaching

I write and maintain [RizTech Academy](https://riztechacademy.com), a set of free, practical engineering courses. Each one ships with a reference implementation you can read, run and break:

| Repository | What it demonstrates |
| --- | --- |
| [dakiya](https://github.com/RizTech-Academy/dakiya) | Spring Boot 3.4 REST API — JPA, Spring Security, concurrency-safe state with optimistic locking, full test pyramid |
| [cinema-booking](https://github.com/RizTech-Academy/cinema-booking) | PostgreSQL + Redis — double-booking made impossible under a real concurrent race, TTL holds, atomic Lua rate limiter |
| [nidaan](https://github.com/RizTech-Academy/nidaan) | Django 5.1 + DRF — patient-scoped API, constraints enforced in the database, test suite |
| [agentpay](https://github.com/RizTech-Academy/agentpay) | Fastify API + React dashboard — Vitest API tests, Playwright end-to-end tests |
| [weather-client](https://github.com/RizTech-Academy/weather-client) | TypeScript — untrusted JSON validated at the boundary, every failure modelled as a typed Result |

More courses, including Kotlin, Java, Python, JavaScript and full-stack web, at [RizTech-Academy](https://github.com/RizTech-Academy).

## Elsewhere

- Courses and writing — [riztechacademy.com](https://riztechacademy.com)
- LinkedIn — [rizwanulhaque1](https://www.linkedin.com/in/rizwanulhaque1/)
