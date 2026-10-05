<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=190&section=header&text=Abhinav%20C&fontSize=56&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Full-Stack%20%26%20React%20Native%20Developer&descAlignY=58&descSize=17" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&duration=3000&pause=1200&color=A78BFA&center=true&vCenter=true&width=600&lines=Building+TrainLabs+solo+%E2%80%94+live+at+trainlabs.app;React+Native+%C2%B7+React+%C2%B7+NestJS+%C2%B7+PostgreSQL;Schema+%E2%86%92+API+%E2%86%92+app+%E2%86%92+deploy.+End+to+end." alt="Typing SVG" />

<br/><br/>

[![TrainLabs](https://img.shields.io/badge/TrainLabs-Live%20%E2%86%97-7C3AED?style=for-the-badge&labelColor=0d0d1a)](https://trainlabs.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d0d1a)](https://www.linkedin.com/in/abhinav-c-877ab3253)
[![Email](https://img.shields.io/badge/Email-Say%20hi-5B21B6?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d0d1a)](mailto:abhinavc038@gmail.com)
[![IEEE](https://img.shields.io/badge/IEEE-Published-4C1D95?style=for-the-badge&logo=ieee&logoColor=white&labelColor=0d0d1a)](https://doi.org/10.1109/NetACT65906.2025.11188147)

</div>

## 👋 About

- 🔭 Building **[TrainLabs](https://trainlabs.app)** solo: a platform for online fitness coaches, with a React Native app, a React web app and a NestJS API. It's live.
- 🧱 I like owning a feature end to end: database schema, API, mobile and web UI, payments and deployment.
- 📄 Co-author of an **IEEE NetACT 2025** paper on on-demand service architecture.
- 🎯 Open to **full-stack / React Native** roles at product companies and startups. B.Tech CSE '25, Kerala, India.

## 🛠️ Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,py,react,nextjs,nodejs,nestjs,express,postgres,prisma,mongodb,tailwind,vite,jest,git,linux,nginx,vercel,cloudflare,postman&perline=10&theme=dark" alt="Tech stack" />
</p>

<p align="center"><sub>Also: React Native (Expo) · Socket.IO · TanStack Query · Zustand · Razorpay · Gemini API · Cloudflare R2 · Railway · Neon</sub></p>

## 🚀 Featured work

### 🏋️ [TrainLabs](https://trainlabs.app) · coaching platform for online fitness trainers

`React Native (Expo)` `React + Vite` `NestJS` `Prisma` `PostgreSQL` `Socket.IO` `Cloudflare R2` `Razorpay` `Gemini API`

A mobile app for trainers and clients, a web app for trainers, and one NestJS API on a **53-model PostgreSQL schema**, deployed on Railway, Vercel and Neon. **216 Jest tests · 91 merged PRs.**

<details>
<summary><b>What's inside →</b></summary>
<br/>

- **Auth:** phone OTP and Google Sign-In, JWT access/refresh tokens and role guards. On the web, the refresh token lives in an httpOnly cookie issued only to allow-listed origins.
- **Real-time chat:** Socket.IO with replies, read receipts, typing indicators and cursor pagination. Events write straight into the TanStack Query cache, so screens never refetch.
- **AI PDF import:** Gemini turns a workout-program PDF into JSON matching the API's schema, and a fuzzy matcher maps exercise names onto an 873-exercise library. Results land as drafts for the trainer to review.
- **Payments:** Razorpay Subscriptions with idempotent webhooks, plus a trainer ledger where balances and overdue status are computed at read time, never stored.
- **Media:** photos and videos in private Cloudflare R2 buckets, served through short-lived presigned URLs.

<sub>The code is private. Happy to walk through it on a call.</sub>
</details>

### 🎓 [CourseCore](https://github.com/Abhinav-C-7/coursecore) · multi-tenant tuition management SaaS

`React` `Express` `Prisma` `PostgreSQL` `Clerk`

Every record carries a `tenantId`, enforced by central middleware. A Svix-verified Clerk webhook sets up a new tenant on sign-up, and batch attendance is idempotent through a single Prisma transaction. It was self-hosted on a Linux VPS with Nginx, PM2 and SSL.

### 🔧 [Done-It](https://github.com/Abhinav-C-7/done-it) · on-demand home services marketplace · *IEEE published*

`React` `Express` `PostgreSQL` `Socket.IO` `Leaflet`

A three-role app (customer, serviceman, admin). Servicemen are matched to nearby jobs with the Haversine formula over PostgreSQL's `point` type, and live locations and job alerts go out through per-user Socket.IO rooms.

### 🤝 [Attendance Management System](https://github.com/AbhiOO4/Attendance-Management-System) · contributor

`React` `TypeScript` `Express` `MongoDB` `node-cron`

Two merged PRs to an attendance app built for a construction company: [night-shift auto-attendance](https://github.com/AbhiOO4/Attendance-Management-System/pull/7) with scheduled check-in/out, and [inline attendance editing](https://github.com/AbhiOO4/Attendance-Management-System/pull/6).

## 📄 Publication

**On-Demand Service Web Application Architecture** · IEEE NetACT 2025 · [DOI 10.1109/NetACT65906.2025.11188147](https://doi.org/10.1109/NetACT65906.2025.11188147)

<div align="center">
<br/>
<sub><i>Architecture is a decision, not a default.</i></sub>
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
</div>
