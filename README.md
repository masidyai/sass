masidy
Modern, Scalable, Multi‑Tenant SaaS Boilerplate

<p align="center">
<img src="https://raw.githubusercontent.com/masidyai/sass/main/public/logo.png" width="120" alt="masidy logo" />
</p>

<p align="center">
<strong>A production‑ready SaaS starter kit built with Next.js, TypeScript, Tailwind CSS, and Prisma.</strong><br>
Designed for speed, scalability, and developer happiness.
</p>

<p align="center">
<a href="#"><img src="https://img.shields.io/badge/build-passing-brightgreen" /></a>
<a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue" /></a>
<a href="#"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen" /></a>
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/masidyai/sass/main/public/screenshot.png" width="750" alt="masidy dashboard screenshot" />
</p>

📌 Overview
masidy is a complete SaaS boilerplate engineered for developers who want to build and launch modern SaaS products without reinventing the wheel.
It includes multi‑tenancy, authentication, analytics, workspace management, and a clean UI — all following best practices and scalable architecture.

Whether you're building a startup MVP or a full enterprise platform, masidy gives you a rock‑solid foundation.

🚀 Key Features
🧱 Core Architecture
Next.js 14 — App Router, server components, layouts, streaming

TypeScript-first — End‑to‑end type safety

Prisma ORM — Type‑safe database layer with migrations

PostgreSQL — Reliable, scalable relational database

🔐 Authentication & Security
Secure email/password login

OAuth providers (Google, GitHub, etc.)

Session management & middleware protection

Role‑based access control (RBAC)

🏢 Multi‑Tenancy
Tenant-aware routing

Workspace isolation

Middleware-based tenant resolution

Support for subdomains or path-based tenants

📊 Analytics & Insights
Usage metrics dashboard

Workspace-level analytics

Activity logs & audit trails

🗂️ Workspace & Project Management
Create and manage workspaces

Invite members & manage roles

Project creation, organization, and collaboration

🎨 UI & UX
Tailwind CSS + custom components

Fully responsive layout

Dark mode support

Dashboard-ready UI kit

🧩 Developer Experience
ESLint + Prettier + Husky

Modular folder structure

API routes with clean separation

Environment variable validation

📁 Project Structure
Codice
masidy/
│
├── app/                # Next.js App Router
│   ├── (auth)/         # Authentication pages
│   ├── dashboard/      # Tenant dashboard
│   └── api/            # API routes
│
├── components/         # Reusable UI components
├── lib/                # Utilities, helpers, configs
├── prisma/             # Prisma schema & migrations
├── public/             # Static assets
└── types/              # Global TypeScript types
⚙️ Installation
1. Clone the repository
bash
git clone https://github.com/masidyai/sass.git
cd sass
2. Install dependencies
bash
npm install
3. Configure environment variables
Create .env:

Codice
DATABASE_URL="postgresql://..."
NEXTAUTH_SECRET="your-secret"
NEXTAUTH_URL="http://localhost:3000"
4. Run database migrations
bash
npx prisma migrate dev
5. Start the development server
bash
npm run dev
🧪 Testing
masidy includes a testing-ready setup:

Jest / Vitest (optional)

Integration tests for API routes

Mocked Prisma client utilities

🚀 Deployment
masidy is optimized for:

Vercel (recommended)

Docker

Railway / Render

AWS / GCP / Azure

Deploy to Vercel
bash
vercel deploy
🤝 Contributing
Contributions are welcome!
Please open an issue or submit a pull request.

📄 License
masidy is licensed under the MIT License.
See the LICENSE file for details.

⭐ Support the Project
If you find masidy useful, consider giving the repository a star — it helps a lot.
