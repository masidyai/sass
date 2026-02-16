                                      # masidy  
           **Modern Multi‑Tenant SaaS Boilerplate for Production‑Grade Applications**

<p align="center">
  <img src="https://raw.githubusercontent.com/masidyai/sass/main/public/logo.png" width="120" alt="masidy logo" />
</p>

<p align="center">
  masidy is a fully‑featured SaaS starter kit designed for developers who want to build scalable, secure, and beautifully‑designed SaaS products without wasting months on boilerplate.
</p>

<p align="center">
  <a><img src="https://img.shields.io/badge/build-passing-brightgreen" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue" /></a>
  <a><img src="https://img.shields.io/badge/PRs-welcome-brightgreen" /></a>
</p>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/masidyai/sass/main/public/screenshot.png" width="750" alt="masidy dashboard screenshot" />
</p>

---

## 📌 What is masidy?

masidy is a **production‑ready SaaS boilerplate** built with modern technologies like **Next.js 14**, **TypeScript**, **Prisma**, and **Tailwind CSS**.  
It includes everything you need to launch a SaaS product:

- Multi‑tenant architecture  
- Authentication & authorization  
- Workspace & project management  
- Analytics dashboard  
- Clean, responsive UI  
- Scalable backend structure  

Instead of spending months building the same foundation every SaaS needs, masidy gives you a **battle‑tested starting point** so you can focus on your actual product.

---

## 🚀 Features

### 🧱 Core Stack
- **Next.js 14** — App Router, server components, layouts  
- **TypeScript** — End‑to‑end type safety  
- **Prisma ORM** — Modern, type‑safe database layer  
- **PostgreSQL** — Reliable relational database  

### 🔐 Authentication & Security
- Email/password login  
- OAuth providers (Google, GitHub, etc.)  
- Secure session handling  
- Role‑based access control (RBAC)  

### 🏢 Multi‑Tenancy
- Workspace‑based tenant isolation  
- Middleware‑driven tenant resolution  
- Subdomain or path‑based tenancy  
- Secure data separation  

### 📊 Analytics & Insights
- Usage metrics  
- Workspace‑level analytics  
- Activity logs  
- Growth indicators  

### 🗂️ Workspace & Project Management
- Create & manage workspaces  
- Invite members  
- Assign roles  
- Organize projects  

### 🎨 UI & UX
- Tailwind CSS  
- Fully responsive  
- Dashboard‑ready components  
- Dark mode support  

### 🧩 Developer Experience
- ESLint + Prettier  
- Clean folder structure  
- Environment variable validation  
- Modular architecture  

---

## 📁 Folder Structure

```
masidy/
│
├── app/                # Next.js App Router
│   ├── (auth)/         # Authentication pages
│   ├── dashboard/      # Tenant dashboard
│   └── api/            # API routes
│
├── components/         # Reusable UI components
├── lib/                # Utilities, configs, helpers
├── prisma/             # Prisma schema & migrations
├── public/             # Static assets
└── types/              # Global TypeScript types
```

---

## ⚙️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/masidyai/sass.git
cd sass
```

### 2. Install dependencies
```bash
npm install
```

### 3. Configure environment variables
Create a `.env` file:

```
DATABASE_URL="postgresql://..."
NEXTAUTH_SECRET="your-secret"
NEXTAUTH_URL="http://localhost:3000"
```

### 4. Run migrations
```bash
npx prisma migrate dev
```

### 5. Start the development server
```bash
npm run dev
```

---

## 🧪 Testing

masidy includes a testing‑ready setup:

- Unit tests  
- Integration tests  
- Mocked Prisma client  

---

## 🚀 Deployment

masidy is optimized for:

- **Vercel** (recommended)  
- Docker  
- Railway / Render  
- AWS / GCP / Azure  

### Deploy to Vercel
```bash
vercel deploy
```

---

## 🤝 Contributing

Contributions are welcome.  
Open an issue or submit a pull request.

---

## 📄 License

MIT License — see `LICENSE`.

---

## ⭐ Support

If masidy helps you, consider starring the repo.
