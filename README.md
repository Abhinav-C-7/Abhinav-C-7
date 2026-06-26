<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Abhinav%20C&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Full-Stack%20Developer%20%7C%20TypeScript%20%C2%B7%20React%20%C2%B7%20NestJS%20%C2%B7%20PostgreSQL&descAlignY=55&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Architecting+multi-tenant+SaaS+systems;Building+real-time+messaging+at+scale;NestJS+%2B+Prisma+%2B+PostgreSQL;Solo-founder+%40+TrainLabs" alt="Typing SVG" />
</a>

<br/>

![B.Tech CSE](https://img.shields.io/badge/B.Tech-Computer%20Science-6D28D9?style=flat-square&labelColor=1a1a2e)
![Graduate](https://img.shields.io/badge/Graduate-2025-7C3AED?style=flat-square&labelColor=1a1a2e)
![Location](https://img.shields.io/badge/Location-Kannur,%20Kerala,%20India-8B5CF6?style=flat-square&labelColor=1a1a2e&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-A78BFA?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d0d1a)](https://github.com/Abhinav-C-7)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d0d1a)](https://linkedin.com/in/abhinav-c)
[![Email](https://img.shields.io/badge/Email-Reach%20Out-6D28D9?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d0d1a)](mailto:abhinavc038@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-5B21B6?style=for-the-badge&logo=github&logoColor=white&labelColor=0d0d1a)](https://github.com/Abhinav-C-7)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Abhinav-C-7&color=8B5CF6&style=flat-square&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/Abhinav-C-7?style=flat-square&color=8B5CF6&labelColor=1a1a2e)
![Stars](https://img.shields.io/github/stars/Abhinav-C-7?style=flat-square&color=8B5CF6&labelColor=1a1a2e)

</div>

<br/>

---

## 👤 About Me

```
const abhinav = {
    role: "Full-Stack Developer",
    education: "B.Tech, Computer Science & Engineering (2025)",
    focus: ["Multi-tenant SaaS architecture", "Real-time systems", "Geolocation marketplaces"],
    currentlyBuilding: "TrainLabs — B2B2C remote personal training SaaS",
    philosophy: "Ship working systems, then make them correct, then make them fast.",
};
```

I'm a sole-developer engineer who has shipped three full-stack production-style systems end to end — backend architecture, database schema, real-time infrastructure, and mobile/web frontends — without a team. My work centers on **systems that need to scale across multiple tenants or actors**: tuition centers with isolated tenant data, fitness coaches and clients connected in real time, and household-service marketplaces matching customers to nearby providers by geolocation.

I care more about *why a system is designed the way it is* than about following a tutorial pattern — RBAC enforcement, transactional integrity, and auth security boundaries show up as deliberate decisions across all three of my projects, not afterthoughts.

**🔭 Open to:** Full-stack / backend-leaning roles at product companies and early-stage startups (Series A–C) where I can own architecture decisions, not just implement tickets.

<br/>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![TypeScript](https://skillicons.dev/icons?i=ts) ![JavaScript](https://skillicons.dev/icons?i=js) ![Python](https://skillicons.dev/icons?i=python) ![PostgreSQL](https://skillicons.dev/icons?i=postgres)

**Frontend**

![React](https://skillicons.dev/icons?i=react) ![React Native](https://skillicons.dev/icons?i=react) ![Tailwind](https://skillicons.dev/icons?i=tailwind) ![Materialize](https://skillicons.dev/icons?i=materialui) ![Vite](https://skillicons.dev/icons?i=vite)

**Backend & Databases**

![Node.js](https://skillicons.dev/icons?i=nodejs) ![Express](https://skillicons.dev/icons?i=express) ![NestJS](https://skillicons.dev/icons?i=nestjs) ![PostgreSQL](https://skillicons.dev/icons?i=postgres) ![Prisma](https://skillicons.dev/icons?i=prisma)

**Cloud, DevOps & Tooling**

![Git](https://skillicons.dev/icons?i=git) ![GitHub](https://skillicons.dev/icons?i=github) ![Linux](https://skillicons.dev/icons?i=linux) ![Postman](https://skillicons.dev/icons?i=postman) ![VSCode](https://skillicons.dev/icons?i=vscode)

</div>

**Also working with:** REST APIs · JWT & OTP Auth · Passport.js · RBAC · Socket.IO · TanStack Query · Zustand · Svix Webhooks · Clerk · Leaflet · Nodemailer · Expo · NativeWind · React Router

<br/>

---

## 🚀 Featured Projects

<details open>
<summary><b>🏋️ Remote Personal Training Platform — TrainLabs</b></summary>
<br/>

A two-sided B2B2C fitness coaching platform connecting trainers and clients, built solo from architecture to deployment.

| | |
|---|---|
| **Stack** | NestJS · React Native (Expo) · Prisma · PostgreSQL (Neon) · Socket.IO |
| **Scale** | Single Expo codebase serving role-scoped trainer & client experiences via file-based routing |
| **Performance** | Socket.IO events sync directly into TanStack Query cache — zero manual refetches |
| **Security** | JWT purpose-claim guard isolating mid-signup temp tokens from access tokens; custom RBAC decorators/guards |
| **Impact** | Real-time chat with threading, read receipts, typing indicators & presence, scoped to active trainer–client links |
| **Repository** | *Private — in active development* |

**What it does:** Architected a NestJS + Prisma backend for a two-sided fitness coaching app. Designed phone-OTP auth with a two-step signup flow, blocking privilege escalation via a purpose-claim JWT guard. Modeled nested workout plans (Plan → Day → Exercise) with atomic transactional writes and full-tree replacement endpoints; weekday scheduling via a PostgreSQL `Int[]` of ISO weekdays. Built real-time chat on Socket.IO with auto-posted plan-update cards on plan changes. Wired TanStack Query and Zustand behind an Axios interceptor handling JWT injection and 401 auto-logout.

</details>

<details>
<summary><b>🎓 CourseCore — Multi-Tenant Tuition Management SaaS</b></summary>
<br/>

A multi-tenant SaaS for tuition centers covering batch management, student records, attendance, and fee billing.

| | |
|---|---|
| **Stack** | React 19 · Node.js · Express · Prisma · PostgreSQL · Clerk |
| **Scale** | Admin / Tutor / Viewer roles via a `UserTenantRole` join table |
| **Performance** | Idempotent batch attendance via delete-then-create Prisma transactions |
| **Security** | Row-level tenant isolation — every entity carries a `tenantId` FK, resolved centrally via Express middleware |
| **Impact** | Svix-verified Clerk webhook auto-provisions Tenant/User/Admin on `user.created`, eliminating manual onboarding |
| **Repository** | [github.com/Abhinav-C-7](https://github.com/Abhinav-C-7) |

**What it does:** Enforced row-level tenant isolation across every query via centralized middleware. Normalized the fee chain (`FeeRequest → StudentFee → Payment`) with compound unique constraints to prevent duplicate assignments. Frontend built in React 19, Material UI v7, Tailwind v4, React Router v7; deployed to a self-managed Linux VPS.

</details>

<details>
<summary><b>🔧 Done-It — On-Demand Home Services Marketplace</b></summary>
<br/>

A 3-role marketplace connecting customers to nearby service providers across 8 household service categories.

| | |
|---|---|
| **Stack** | React · Node.js · Express · PostgreSQL · Socket.IO |
| **Scale** | 3 roles (customer / serviceman / admin) across 8 service categories |
| **Performance** | Haversine formula in SQL & JavaScript for proximity-ranked job dispatch |
| **Security** | Role-typed JWT auth, bcrypt password hashing, Nodemailer email verification |
| **Impact** | Real-time job push to nearest serviceman the moment a booking is placed |
| **Repository** | [github.com/Abhinav-C-7](https://github.com/Abhinav-C-7) |

**What it does:** Implemented geolocation job dispatch ranking nearby servicemen by proximity, with live location stored in PostgreSQL's native `point` type. Built role-scoped real-time notifications via Socket.IO rooms. Designed multi-step serviceman onboarding (ID-proof upload → admin review → activation) and a React + Leaflet map UI for address selection via browser geolocation. Co-authored as IEEE NetACT 2025 publication.

</details>

<br/>

---

## 📜 Publication

<div align="center">

| Title | Venue | DOI |
|---|---|---|
| *On-Demand Service Web Application Architecture* | IEEE NetACT 2025, IEEE Xplore | [10.1109/NetACT65906.2025.11188147](https://doi.org/10.1109/NetACT65906.2025.11188147) |

</div>

<br/>

---

## 🎓 Education

<div align="center">

| Institution | Degree | CGPA | Year |
|---|---|---|---|
| Vimal Jyothi Engineering College, Kannur, Kerala | B.Tech, Computer Science & Engineering | 6.87 / 10.0 (First Class) | June 2025 |

</div>

<br/>

---

## 💻 Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=0d0d1a)](#)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-Profile-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white&labelColor=0d0d1a)](#)
[![HackerRank](https://img.shields.io/badge/HackerRank-Profile-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white&labelColor=0d0d1a)](#)
[![CodeChef](https://img.shields.io/badge/CodeChef-Profile-5B4638?style=for-the-badge&logo=codechef&logoColor=white&labelColor=0d0d1a)](#)

*Links pending — drop in your actual handles to activate.*

</div>

<br/>

---

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Abhinav-C-7&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d0d1a&title_color=A78BFA&icon_color=8B5CF6&text_color=c9c9e0" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Abhinav-C-7&theme=tokyonight&hide_border=true&background=0d0d1a&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abhinav-C-7&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d0d1a&title_color=A78BFA&text_color=c9c9e0" width="49%"/>

</div>

<br/>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Abhinav-C-7&theme=algolia&no-frame=true&no-bg=true&margin-w=4&column=7" width="100%"/>

</div>

<br/>

---

## 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Abhinav-C-7&theme=tokyo-night&hide_border=true&bg_color=0d0d1a&color=A78BFA&line=8B5CF6&point=ffffff" width="100%"/>

</div>

<br/>

---

## 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/Abhinav-C-7/Abhinav-C-7/output/github-contribution-grid-snake-dark.svg" width="100%"/>

</div>

> Generated via the [`platane/snk`](https://github.com/Platane/snk) GitHub Action — add the workflow to your profile repo to activate.

<br/>

---

## 🎯 Current Focus

```yaml
learning:
  - Distributed systems fundamentals
  - System design (post month 9 of personal roadmap)
  - AWS Cloud Practitioner fundamentals

building:
  - TrainLabs — diet & meal plan builder, trainer program preset library
  - Directional tab-bar slide navigation (Expo Router + Reanimated)

exploring:
  - B2B SaaS opportunities in the Kerala/Kannur market
  - VPS-based real-time infra patterns (Socket.IO at scale)

open_to:
  - Full-stack / backend roles at Series A–C product companies
  - Conversations with engineers solving multi-tenant or real-time problems
```

<br/>

---

## 📫 Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/-abhinavc038@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white&labelColor=1a1a2e)](mailto:abhinavc038@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-abhinav--c-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=1a1a2e)](https://linkedin.com/in/abhinav-c)
[![GitHub](https://img.shields.io/badge/-Abhinav--C--7-181717?style=flat-square&logo=github&logoColor=white&labelColor=1a1a2e)](https://github.com/Abhinav-C-7)

</div>

<br/>

---

<div align="center">

*"Architecture is a decision, not a default."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

</div>
