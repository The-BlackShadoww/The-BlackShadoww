<a href="https://ashikurrahman.vercel.app">
  <img src="assets/header.svg" width="100%" alt="Ashikur Rahman, full-stack TypeScript developer. Building Webflow apps at FlowAppz. Dhaka, Bangladesh." />
</a>

<p align="center">
  <a href="https://ashikurrahman.vercel.app"><img src="assets/badges/portfolio.svg" alt="Portfolio" /></a>
  <a href="https://drive.google.com/file/d/1q0ArDo7pLpW2iXga6G-phQkT-8YSKoaP/view?usp=sharing"><img src="assets/badges/resume.svg" alt="Resume" /></a>
  <a href="https://www.linkedin.com/in/ashikur-rahman-5b55a4276/"><img src="assets/badges/linkedin.svg" alt="LinkedIn" /></a>
  <a href="mailto:ashikurrahmanbusiness111@gmail.com"><img src="assets/badges/email.svg" alt="Email" /></a>
</p>

<p align="center">
  I build the React screens people click and the Node.js services behind them,<br />
  then write the tests that keep both working in production.
</p>

<p align="center"><img src="assets/badges/open.svg" alt="Open to full-time roles" /></p>

<br />

## 🟥 What I build at FlowAppz

Junior Full Stack JavaScript Developer at [**FlowAppz**](https://flowappz.com) since Aug 2026 (intern from May). Four Webflow apps in TypeScript monorepos: Express and Next.js APIs on PostgreSQL, Redis and BullMQ job queues, and React extensions that run inside the Webflow Designer. **300+ commits.**

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⏱ Scheduled CMS Publisher</h3>
      <sub><code>Express</code> <code>Drizzle</code> <code>BullMQ</code> <code>Redis</code> <code>Playwright</code></sub>
      <ul>
        <li>BullMQ jobs that survive a deploy</li>
        <li>Refresh-token rotation with reuse detection</li>
        <li>Per-site rate limits in Redis</li>
        <li>Schedules that stay correct when a site changes time zone</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🧩 Multistep Form <sub>· top committer</sub></h3>
      <sub><code>Express</code> <code>Prisma</code> <code>PostgreSQL</code> <code>React Query</code></sub>
      <ul>
        <li>Rebuilt session auth on every route</li>
        <li>Every query scoped to the caller's site</li>
        <li>Signed CDN releases with integrity hashes</li>
        <li>Webhooks moved from the browser to the server</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🔎 Advanced Search</h3>
      <sub><code>Express</code> <code>MeiliSearch</code> <code>BullMQ</code> <code>Drizzle</code></sub>
      <ul>
        <li>Webhook-driven re-indexing</li>
        <li>A burst of edits collapses into one job</li>
        <li>Ranking across collections, licence checks</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>💳 Memberflow</h3>
      <sub><code>Next.js</code> <code>Prisma</code> <code>Stripe</code> <code>Resend</code></sub>
      <ul>
        <li>Stripe webhooks and in-place plan upgrades</li>
        <li>Auth templates and 81 Webflow components</li>
        <li>Closed an open redirect</li>
      </ul>
    </td>
  </tr>
</table>

<sub>The code is private. <a href="https://ashikurrahman.vercel.app/#quests">My site</a> has more detail.</sub>

<br />

## 🟥 Projects you can read

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/The-BlackShadoww/personal-finance"><img src="assets/projects/personal-finance.png" alt="Personal Finance dashboard" /></a>
      <h3><a href="https://github.com/The-BlackShadoww/personal-finance">Personal Finance</a></h3>
      Multi-tenant money app: JWT with refresh cookies, Google OAuth, TOTP 2FA, CSP, money stored as integer minor units, unit-tested calculations. Built with Claude Code as my pair programmer.
      <br /><br />
      <code>NestJS</code> <code>PostgreSQL</code> <code>Drizzle</code> <code>Next.js 15</code> <code>TanStack Query</code>
      <br /><br />
      <a href="https://bank-ar.vercel.app"><b>Live demo →</b></a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/The-BlackShadoww/event-calendar-app"><img src="assets/projects/event-calendar.svg" alt="Event Calendar job flow: PENDING to ACTIVE to COMPLETED" /></a>
      <h3><a href="https://github.com/The-BlackShadoww/event-calendar-app">Event Calendar</a></h3>
      Delayed BullMQ jobs open and close each event on time, with retries and backoff. Postgres and Redis in one Docker Compose file.
      <br /><br />
      <code>NestJS</code> <code>PostgreSQL</code> <code>Drizzle</code> <code>Redis</code> <code>BullMQ</code> <code>React</code>
      <br /><br />
      <a href="https://github.com/The-BlackShadoww/event-calendar-app"><b>Source →</b></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/The-BlackShadoww/clarix"><img src="assets/projects/clarix.png" alt="Clarix landing page with a relation graph" /></a>
      <h3><a href="https://github.com/The-BlackShadoww/clarix">Clarix</a></h3>
      Infinite-canvas relation builder for networks, family trees and org charts, with SVG links that follow your drag.
      <br /><br />
      <code>Next.js</code> <code>TypeScript</code> <code>Framer Motion</code>
      <br /><br />
      <a href="https://clarix-six.vercel.app"><b>Live demo →</b></a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/The-BlackShadoww/landing"><img src="assets/projects/plinth.png" alt="Plinth landing page hero" /></a>
      <h3><a href="https://github.com/The-BlackShadoww/landing">Plinth</a></h3>
      Concept landing page with isometric illustrations drawn in code and GSAP motion. Built with Claude Code in four days.
      <br /><br />
      <code>Next.js 16</code> <code>Tailwind CSS v4</code> <code>GSAP</code>
      <br /><br />
      <a href="https://landing-beta-bice-47.vercel.app"><b>Live demo →</b></a>
    </td>
  </tr>
</table>

<br />

## 🟥 Tech stack

<table>
  <tr>
    <td width="130"><b>Frontend</b></td>
    <td><img src="assets/stack/frontend.svg" alt="TypeScript, JavaScript, React, Next.js, Tailwind CSS, Vite, TanStack Query, Zod" /></td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td><img src="assets/stack/backend.svg" alt="Node.js, Express, NestJS, BullMQ, Socket.IO, OAuth and JWT, Stripe" /></td>
  </tr>
  <tr>
    <td><b>Data</b></td>
    <td><img src="assets/stack/data.svg" alt="PostgreSQL, Redis, Prisma, Drizzle, MongoDB, MeiliSearch" /></td>
  </tr>
  <tr>
    <td><b>Testing &amp; shipping</b></td>
    <td><img src="assets/stack/ship.svg" alt="Vitest, Jest, Playwright, Docker, Vercel, Railway, AWS, Git, Figma" /></td>
  </tr>
</table>

<br />

## 🟥 Off the clock

I studied psychology at the University of Dhaka, which helps more than you'd expect when building for real users. Basketball when I'm away from the keyboard.

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/The-BlackShadoww/The-BlackShadoww/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/The-BlackShadoww/The-BlackShadoww/output/snake-light.svg" />
  <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/The-BlackShadoww/The-BlackShadoww/output/snake-dark.svg" width="100%" />
</picture>
