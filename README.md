<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Abhinav%20C&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20Developer%20%C2%B7%20TypeScript%20%C2%B7%20NestJS%20%C2%B7%20PostgreSQL&descAlignY=58&descSize=16" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3200&pause=1200&color=A78BFA&center=true&vCenter=true&width=560&lines=I+build+full-stack+systems+end+to+end.;Multi-tenant+SaaS+%C2%B7+Real-time+%C2%B7+Geolocation;NestJS+%2B+Prisma+%2B+PostgreSQL+%2B+React+Native" alt="Typing SVG" />
</a>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d0d1a)](www.linkedin.com/in/abhinav-c-877ab3253)


[![Email](https://img.shields.io/badge/Email-Reach%20Out-6D28D9?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d0d1a)](mailto:abhinavc038@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-5B21B6?style=for-the-badge&logo=github&logoColor=white&labelColor=0d0d1a)](https://github.com/Abhinav-C-7)

</div>

<br/>

---

## About

I'm a full-stack developer (B.Tech CSE, 2025) who has shipped **three production-style full-stack systems end to end as the sole developer** — backend architecture, database schema, real-time infrastructure, and the frontends on top. My work tends toward systems with non-trivial structure: multi-tenant data isolation, real-time messaging, and geolocation-based matching.

What I care about is *why* a system is built the way it is. Auth security boundaries, transactional integrity, and role-based access control show up as deliberate decisions across all three projects — not bolted on afterward. I also co-authored an **IEEE NetACT 2025** paper on the architecture behind one of them.

**Currently:** building TrainLabs, a B2B2C remote personal-training SaaS, solo — from the NestJS backend to the React Native app.

**Open to:** full-stack / backend-leaning roles at product companies and Series A–C startups where I can own architecture, not just close tickets.

<br/>

---

## Tech Stack

**Languages**  `TypeScript` · `Python` · `SQL`

**Backend**  `NestJS` · `Node.js` · `Express` · `REST APIs` · `JWT & OTP Auth` · `Passport` · `RBAC`

**Database**  `PostgreSQL` · `Prisma ORM` · `Schema Design` · `Migrations` · `Transactions` · `Indexing`

**Frontend**  `React` · `React Native (Expo)` · `Tailwind` · `NativeWind` · `Material UI`

**Real-Time & State**  `Socket.IO` · `TanStack Query` · `Zustand` · `Svix Webhooks`

**Tooling**  `Git` · `Linux / VPS` · `Postman` · `Vite` · `Clerk` · `Leaflet` · `Nodemailer`

<br/>

---

## Featured Projects

### 🏋️ TrainLabs — Remote Personal Training Platform
**NestJS · React Native (Expo) · Prisma · PostgreSQL (Neon) · Socket.IO**  ·  *Solo, in active development*

A two-sided B2B2C fitness coaching platform connecting trainers and clients.

- Architected a NestJS + Prisma backend on Neon PostgreSQL; a **single Expo codebase serves role-scoped trainer and client experiences** via file-based routing.
- Designed phone-OTP auth with a two-step signup flow and a **JWT purpose-claim guard** separating mid-signup temp tokens from access tokens to block privilege escalation; trainer/client scoping enforced with custom RBAC decorators and guards.
- Modeled nested workout plans (Plan → Day → Exercise) with **atomic transactional writes** and a full-tree replacement endpoint.
- Built a real-time chat system on Socket.IO with reply threading, read receipts, typing indicators, and presence — scoped to active trainer–client links, with auto-posted plan-update cards on plan changes.
- Wired TanStack Query + Zustand behind an Axios interceptor (JWT injection, 401 auto-logout); **Socket.IO events sync directly into the query cache**, eliminating manual refetches.

<br/>

### 🎓 CourseCore — Multi-Tenant Tuition Management SaaS
**React · Node.js · Express · Prisma · PostgreSQL · Clerk**  ·  [Repository »](https://github.com/Abhinav-C-7)

A multi-tenant SaaS for tuition centers: batch management, student records, attendance, and fee billing.

- Enforced **row-level tenant isolation** — every entity carries a `tenantId` FK; centralized Express middleware resolves the tenant from the Clerk-authenticated user and injects it into every query.
- Built a **Svix-verified Clerk webhook** that auto-provisions Tenant, User, and Admin role on `user.created`, removing all manual onboarding.
- Normalized the fee chain (`FeeRequest → StudentFee → Payment`) with compound unique constraints to prevent duplicate assignments; idempotent batch attendance via delete-then-create Prisma transactions.
- React 19, Material UI v7, Tailwind v4, React Router v7; deployed to a self-managed Linux VPS.

<br/>

### 🔧 Done-It — On-Demand Home Services Marketplace
**React · Node.js · Express · PostgreSQL · Socket.IO**  ·  [Repository »](https://github.com/Abhinav-C-7)  ·  *IEEE Published*

A 3-role marketplace (customer / serviceman / admin) across 8 household service categories.

- Implemented **geolocation job dispatch using the Haversine formula** in both SQL and JavaScript to rank nearby servicemen by proximity; live location stored in PostgreSQL's native `point` type.
- Real-time, role-scoped notifications via Socket.IO rooms — job requests pushed to the nearest serviceman the moment a booking is placed.
- Multi-step serviceman onboarding (ID-proof upload → admin review → activation) and a React + Leaflet map UI for browser-geolocation address selection.

<br/>

---

## Publication

**On-Demand Service Web Application Architecture** — IEEE NetACT 2025, published in IEEE Xplore.
DOI: [10.1109/NetACT65906.2025.11188147](https://doi.org/10.1109/NetACT65906.2025.11188147)

<br/>

---

## Education

**B.Tech, Computer Science & Engineering** — Vimal Jyothi Engineering College, Kannur, Kerala  ·  2025

<br/>

---

<div align="center">

*Architecture is a decision, not a default.*

</div>
