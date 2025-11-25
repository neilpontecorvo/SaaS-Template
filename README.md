# SaaS Template

Opinionated starter for a modern SaaS application using Next.js (App Router), TypeScript, Prisma, and PostgreSQL. Includes example integrations for OpenAI (Codex) and Anthropic (Claude).

Features
- Next.js (App Router) + TypeScript
- Prisma ORM + PostgreSQL
- NextAuth for authentication (email + OAuth)
- Example integrations: OpenAI, Anthropic
- GitHub Actions CI (lint, typecheck, test, build)
- Dockerfile for containerized development

Quickstart
1. Copy .env.example to .env and fill in values.
2. Install dependencies: npm install
3. Run Prisma migrations and seed (after setting DATABASE_URL): npx prisma migrate dev --name init && npm run db:seed
4. Run dev server: npm run dev

License: MIT