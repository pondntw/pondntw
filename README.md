<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:e8b896&height=180&section=header&text=LNN%20DEV&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Full%20Stack%20Developer%20%C2%B7%20TypeScript%20%C2%B7%20PostgreSQL&descAlignY=58&descSize=17" width="100%" alt="LNN DEV — Full Stack Developer" />
</p>

<p align="center">
  📍 Bangkok, Thailand &nbsp;·&nbsp; 💼 Open to Junior Full Stack roles
</p>

## 👋 About me

I build full stack web apps with **TypeScript, Next.js, NestJS and PostgreSQL** — from database schema and business rules to the UI, tests and deployment.

Before web development I spent several years writing **game server scripts for FiveM (GTA V roleplay)** in Lua. Those scripts run on live servers with real players, so I learned early to care about server-side validation, realtime updates, and keeping things configurable for non-developers.

- 🧱 I like putting business rules where they can't be bypassed — in the API or the database, not the browser
- 🧪 I write tests for the logic that matters (order rules, fees, access control)
- 🚀 Every project below has a live demo you can try

## 🚀 Featured projects

### 🛒 [Gaming Gear E-Commerce](https://github.com/pondntw/gaming-gear-ecommerce) &nbsp;·&nbsp; [Live demo](https://gaming-gear-ecommerce-web.vercel.app)
Online store with a customer storefront and an admin back office. Team project (CSC481).
- Next.js 15 frontend + **NestJS 11 REST API** + **Prisma** on Supabase PostgreSQL, in one monorepo
- Cart → checkout → payment-slip upload → admin review → shipping, with an order state machine that restocks automatically on cancel
- Admin dashboard for products, categories, stock, orders, users and reviews; unit tests with Jest
- **My role:** built the NestJS API (auth, products, cart, orders, reviews, admin), the Next.js storefront, checkout and admin pages, wrote the unit tests, and set up deployment on Vercel

`Next.js` `NestJS` `Prisma` `PostgreSQL` `Supabase Storage` `JWT` `Jest` `Vercel`

### 🅿️ [Parking Membership System](https://github.com/pondntw/parking-membership) &nbsp;·&nbsp; [Live demo](https://parking-zeta-lilac.vercel.app)
Staff app for managing parking members, vehicles, zones, packages, gate entry/exit, fees and payments.
- Business rules live in **PostgreSQL** (SQL functions, views, Row Level Security) — the browser can't change times or amounts
- Versioned migrations with the Supabase CLI
- Unit tests with `node:test` against a real database, plus end-to-end tests with **Playwright**
- **Demo mode runs the real migrations in the browser with PGlite**, so anyone can try it without an account or backend

`React` `Vite` `PostgreSQL` `Supabase Auth` `RLS` `PGlite` `Playwright`

### 💰 [MoneyFlow](https://github.com/pondntw/MoneyFlow)
Personal finance dashboard: bank accounts, income/expense tracking, and a stock portfolio with live prices and USD/THB rates.
- Next.js App Router with an API route that fetches live stock quotes
- Supabase Auth + Postgres per-user data, Thai/English i18n, dark/light mode, charts with Recharts

`Next.js` `React 19` `Tailwind CSS` `shadcn/ui` `Supabase` `Recharts`

### 🎮 [lnn_alljob](https://github.com/pondntw/lnn_alljob) — FiveM resource
Config-driven job system with a live leaderboard for GTA V roleplay servers.
- Lua server/client + HTML/CSS/JS in-game UI (NUI) + MySQL
- Leaderboard updates live while players are viewing it; hooks let server owners extend it without touching the core
- Includes tests and a benchmark for the leaderboard

`Lua` `ESX` `oxmysql` `JavaScript` `MySQL`

## 🧰 Tech stack

| | |
|---|---|
| **Frontend** | TypeScript, React, Next.js, Tailwind CSS, shadcn/ui |
| **Backend** | Node.js, NestJS, REST APIs, JWT auth |
| **Database** | PostgreSQL, Prisma, Supabase (Auth, RLS, Storage), MySQL |
| **Testing** | Jest, node:test, Playwright |
| **Tools** | Git, GitHub, Vercel, VS Code |
| **Also** | Lua (FiveM / ESX), Java |

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,nodejs,nestjs,prisma,postgres,supabase,mysql,lua,git,vercel&perline=7" alt="Tech stack icons" />
</p>

## 📫 Contact

- 💬 Discord: **`pondhu8`**
- ✉️ Email: **[contact.nontawat@gmail.com](mailto:contact.nontawat@gmail.com)**
