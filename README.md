# 👋 Hey, I’m Harman

Developer from **Dhar, Madhya Pradesh**.

Most of my time right now goes into **TechSeekho**, an edtech platform I work on as an intern at **Koshalyam Learning Solutions**. That's where I've been finding out what it actually takes to build software for real users instead of another demo app.

I started out doing the usual "new framework every week" thing, and I still enjoy that part. But the interesting half turned out to be the other one — **Go services, Postgres schemas, authorization that has to be correct, and a monorepo that has to stay buildable on a Monday morning.** Shipping is mostly unglamorous work done carefully, which was not the lesson I expected.

This profile is the log: experiments, abandoned ideas, and the occasional thing that made it all the way to production.

---

## 🌐 Connect with me

[![Behance](https://img.shields.io/badge/Behance-1769ff?logo=behance&logoColor=white)](https://behance.net/harmansoni22)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NSAyMC40NWgtMy41NXYtNS41N2MwLTEuMzMtLjAyLTMuMDQtMS44NS0zLjA0LTEuODUgMC0yLjEzIDEuNDUtMi4xMyAyLjk0djUuNjdIOS4zNlY5aDMuNDF2MS41NmguMDVjLjQ3LS45IDEuNjMtMS44NSAzLjM3LTEuODUgMy42IDAgNC4yNiAyLjM3IDQuMjYgNS40NXY2LjI5ek01LjM0IDcuNDNhMi4wNiAyLjA2IDAgMSAxIDAtNC4xMiAyLjA2IDIuMDYgMCAwIDEgMCA0LjEyem0xLjc4IDEzLjAySDMuNTZWOWgzLjU2djExLjQ1eiIvPjwvc3ZnPg==&logoColor=white)](https://linkedin.com/in/harmansoni)
[![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?logo=stack-overflow&logoColor=white)](https://stackoverflow.com/users/30782064/harman-soni)
[![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:harman.codes.dev@gmail.com)
<!-- [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/harman.frr)
-->

---

## 🏗️ TechSeekho — what I actually work on

A learning platform built around **a separate ecosystem for each kind of user** — learners, educators, administrators, school representatives and guests. Every role signs in through its own gateway and never shares a session with another role, which sounds like a small detail until you try to retrofit it.

**How it's put together**

- **Go** backends — 45 modules, each with strict `transport → service → repository` layering, so SQL and authorization never leak up into HTTP handlers
- **Next.js 16** frontends on the App Router, server components by default
- **PostgreSQL** through `pgx`, with ownership and scope checks enforced in the service layer rather than trusted from the client
- A **pnpm monorepo** holding 42 TypeScript workspaces alongside the Go modules, sharing one design system and one auth/session layer
- Privacy treated as a constraint rather than a feature: learner profiles are private by default, with no peer access

> **Note:** the code isn't public — it's a company codebase, so there's nothing to browse here. This section exists so the profile reflects what I actually spend my days on.

---

## 🚀 Other things I'm doing

- Building small, focused web apps to keep the fundamentals sharp (React, Next.js, APIs, auth, state).
- Getting properly comfortable with **Go** on the backend after years of only reaching for Node.
- Poking at **Rust** in a side project, mostly to find out what the fuss is about.
- Exploring deployment for real: **AWS EC2**, **Vercel**, **Netlify**, **Cloudflare**.
- Slowly moving towards **AI/ML** and stronger **math foundations**, so future projects aren't just CRUD apps.

---

## 🧠 Current Focus

- Writing **cleaner, more consistent code** instead of jumping stacks every week.
- **Finishing things**: idea → prototype → deployed → documented.
- Getting better at **debugging**, **testing**, and **reading docs** instead of only tutorials.
- Learning to **balance ambition with discipline** — fewer half-finished projects, more things that actually ship.

---

## 🛠 Tech I use (and break)

**Core languages**

![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%233178C6.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/css-%231572B6.svg?style=for-the-badge&logo=css&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![React Router](https://img.shields.io/badge/React%20Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vue.js](https://img.shields.io/badge/vue.js-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![TezJS](https://img.shields.io/badge/TezJS-000000?style=for-the-badge&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)

---

### **Backend & Databases**

![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-00E599?style=for-the-badge&logo=neon&logoColor=black)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=prisma&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

---

### **AI Tools**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude Design](https://img.shields.io/badge/Claude%20Design-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![Google AI Studio](https://img.shields.io/badge/Google%20AI%20Studio-4285F4?style=for-the-badge&logo=google&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![Windsurf](https://img.shields.io/badge/Windsurf-2563EB?style=for-the-badge&logo=windsurf&logoColor=white)
![ChatGPT](https://img.shields.io/badge/ChatGPT-74AA9C?style=for-the-badge)
![Codex](https://img.shields.io/badge/Codex-412991?style=for-the-badge)
![AntiGravity](https://img.shields.io/badge/AntiGravity-6D28D9?style=for-the-badge)
![Blackbox AI](https://img.shields.io/badge/Blackbox%20AI-000000?style=for-the-badge)
![v0](https://img.shields.io/badge/v0-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Bolt.new](https://img.shields.io/badge/Bolt.new-000000?style=for-the-badge&logo=stackblitz&logoColor=white)
![Replit AI](https://img.shields.io/badge/Replit%20AI-F26207?style=for-the-badge&logo=replit&logoColor=white)

---

### **Cloud & Deployment**

![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=00C7B7)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logoColor=black)
![Amazon EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge)

---

### **Dev Workflow & Tooling**

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![TurboRepo](https://img.shields.io/badge/Turborepo-EF4444?style=for-the-badge&logo=turborepo&logoColor=white)
![Biome](https://img.shields.io/badge/Biome-60A5FA?style=for-the-badge&logo=biome&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)
![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/prettier-%23F7B93E.svg?style=for-the-badge&logo=prettier&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)

---

**Design & visuals**

![Adobe Lightroom](https://img.shields.io/badge/Adobe%20Lightroom-31A8FF.svg?style=for-the-badge)
![Adobe Express](https://img.shields.io/badge/Adobe%20Express-FF0000?style=for-the-badge)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge)
![Spline](https://img.shields.io/badge/Spline-0A0E1A?style=for-the-badge)

---

## 📊 GitHub Stats

<!-- NOTE: these three cards read the PUBLIC contributions calendar. Because every
     TechSeekho repo is private, they currently report Current Streak 0 and a flat
     activity graph. Fix: GitHub Settings -> Public profile -> Contributions ->
     tick "Include private contributions on my profile". -->

<p align="center">
  <a href="https://github.com/vn7n24fzkq/github-profile-summary-cards">
    <img
      src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=harmansoni22&theme=radical"
      alt="Harman's GitHub profile summary"
      width="100%"
    />
  </a>
</p>

<!-- Language cards intentionally omitted: public-repo stats show 0% Go, because every Go
     service is in a private repo. A self-hosted github-readme-stats instance with
     count_private=true would report them accurately. -->

<p align="center">
  <a href="https://github.com/DenverCoder1/github-readme-streak-stats">
    <img
      src="https://streak-stats.demolab.com?user=harmansoni22&theme=radical&hide_border=true"
      alt="GitHub streak"
      height="200px"
    />
  </a>
</p>

<p align="center">
  <a href="https://github.com/Ashutosh00710/github-readme-activity-graph">
    <img
      src="https://github-readme-activity-graph.vercel.app/graph?username=harmansoni22&theme=radical&hide_border=true&area=true"
      alt="Contribution activity graph"
      width="100%"
    />
  </a>
</p>

---

## 📌 A few things I care about

- **Clarity over chaos**: simple UIs, clear structure, readable code.
- **Learning in public**: small commits, honest mistakes, visible progress.
- **Getting the boring parts right**: auth, data modelling, and error states are where products actually succeed or fail.
- **Long-term game**: using these projects as a foundation for future work in AI, backend systems, and more serious engineering.

---

## ✍️ Random Dev Quote

![Random Dev Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---

## 💰 Support my work

If you’ve found something here helpful, motivating, or just cool:

[![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/harmansoni)
