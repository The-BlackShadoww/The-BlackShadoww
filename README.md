# Ashikur Rahman

**Full-stack TypeScript developer.** I build the React screens people click and the Node.js services behind them, then write the tests that keep both working in production.

Junior Full Stack JavaScript Developer at [FlowAppz](https://flowappz.com), building Webflow apps · Dhaka, Bangladesh (UTC+6)<br>
**Open to full-time full-stack, backend or frontend roles.**

[Portfolio](https://ashikurrahman.vercel.app) · [Resume](https://drive.google.com/file/d/1q0ArDo7pLpW2iXga6G-phQkT-8YSKoaP/view?usp=sharing) · [LinkedIn](https://www.linkedin.com/in/ashikur-rahman-5b55a4276/) · [Email](mailto:ashikurrahmanbusiness111@gmail.com)

## What I build at FlowAppz

Four Webflow apps in TypeScript monorepos: Express and Next.js APIs on PostgreSQL, Redis and BullMQ job queues, and React extensions that run inside the Webflow Designer. 300+ commits since May 2026.

- **Scheduled CMS Publisher**: BullMQ jobs that survive a deploy, refresh-token rotation with reuse detection, per-site rate limits in Redis, and schedules that stay correct when a site changes time zone.
- **Multistep Form** (top committer): rebuilt session auth, scoped every query to the caller's site, signed CDN releases with integrity hashes, and moved webhooks to the server.
- **Advanced Search**: webhook-driven re-indexing on MeiliSearch that collapses a burst of edits into one job, ranking across collections, and licence checks.
- **Memberflow**: Stripe webhooks and in-place plan upgrades, auth templates, and a closed open redirect.

The code is private. [My site](https://ashikurrahman.vercel.app/#quests) has more detail.

## Projects you can read

| Project | What it shows | Stack |
| --- | --- | --- |
| [Personal Finance](https://github.com/The-BlackShadoww/personal-finance) · [live](https://bank-ar.vercel.app) | Multi-tenant money app: JWT with refresh cookies, Google OAuth, TOTP 2FA, CSP, money stored as integer minor units, unit-tested calculations. Built with Claude Code as my pair programmer. | NestJS, PostgreSQL, Drizzle, Next.js 15, TanStack Query |
| [Event Calendar](https://github.com/The-BlackShadoww/event-calendar-app) · [live](https://event-calendar-app-sand.vercel.app) | Delayed BullMQ jobs open and close each event on time, with retries and backoff. Postgres and Redis in one Docker Compose file. | NestJS, PostgreSQL, Drizzle, Redis, BullMQ, React |
| [Clarix](https://github.com/The-BlackShadoww/clarix) · [live](https://clarix-six.vercel.app) | Infinite-canvas relation builder with SVG links that follow your drag | Next.js, TypeScript, Framer Motion |
| [Plinth](https://github.com/The-BlackShadoww/landing) · [live](https://landing-beta-bice-47.vercel.app) | Concept landing page with isometric illustrations drawn in code and GSAP motion. Built with Claude Code in four days. | Next.js 16, Tailwind CSS v4, GSAP |

## Stack

**Languages:** TypeScript, JavaScript<br>
**Frontend:** React, Next.js, Tailwind CSS, TanStack Query, React Hook Form, Zod<br>
**Backend:** Node.js, Express, NestJS, BullMQ, OAuth + JWT, Stripe, webhooks<br>
**Data:** PostgreSQL, Drizzle, Prisma, Redis, MeiliSearch, MongoDB<br>
**Testing:** Vitest, Playwright, Supertest<br>
**Shipping:** Docker, Railway, Vercel, AWS S3

## Writing

- [Mastering Next.js caching: all four mechanisms](https://ashikurrahman.vercel.app/blog/mastering-nextjs-caching)

## Off the clock

I studied psychology at the University of Dhaka, which helps more than you'd expect when building for real users. Basketball when I'm away from the keyboard.
