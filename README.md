# João Victor Equer

Software engineer at [Wibi](https://wibi.dev), Rio de Janeiro. Mobile, backend and tooling for AI-assisted development.

I build and ship products end to end: architecture, API, mobile app, deploy, monitoring. Most of my work is on Dreambook, a sleep and dream journal app made with neuroscientists, available on the [App Store](https://apps.apple.com/br/app/dreambook-di%C3%A1rio-de-sonhos/id6478346247) and [Google Play](https://play.google.com/store/apps/details?id=br.com.wibi.dreambook). It started charging for subscriptions in late 2025, which changed what "good enough" means for a codebase.

*PT-BR: engenheiro de software na Wibi. Apps mobile, APIs e ferramentas de IA para desenvolvimento.*

## Work

**Dreambook** (React Native, Node, Prisma). Mobile features (audio players, dynamic forms, navigation) and backend. Selected for Dealist University (ArcelorMittal) and Sebrae Start Deeptech. The AI gamification features were part of the INOVA+ Saúde program (EMBRAPII/SEBRAE).

**Internal and client platforms** (Express, Prisma, PostgreSQL, Vite). An admin panel and a task-management platform for a client, owned end to end: data model, role-based permissions, documented REST API, deploy.

**[Oficina](https://github.com/JoaoEquer/Oficina)** (open source). A portable set of skills, rules and slash commands that makes AI coding agents (Claude Code, Gemini CLI, Cursor, Codex) behave the same way across projects. A pattern only goes in after it shows up in two real projects. Its supply-chain audit command found known vulnerabilities in real production dependencies, which is the reason I trust it.

**Weekly reporting agent** (private, in development). LangGraph.js, a custom MCP client, human approval before any write.

## What I use, and for what

| Tool | Where it earns its place |
|---|---|
| TypeScript, strict, no `any` | Everywhere. The compiler is the cheapest reviewer. |
| React Native | Dreambook: audio, forms, navigation. |
| Node, Express, Prisma, PostgreSQL | APIs in controller, usecase, repository layers, wired by hand. |
| Docker, GitHub Actions | Reproducible builds and CI. |
| Sentry | Exception tracking across the company's apps. |
| Jest | Business rules, not getters. |
| Claude Code, MCP | Daily, under the rules in Oficina. |

Also used: React, Vite, Tailwind, NestJS, MySQL, Firebase, Google Cloud, Swagger.

## How I work

- Boring technology first. New tools have to beat the one already in the repo.
- Prefer reversible decisions. Small PRs, one theme per branch, Conventional Commits.
- Verify before asserting. Read the real contract (schema, response, lockfile) instead of assuming it.
- Dependencies are attack surface. Audit them, scan for secrets, model permissions explicitly.
- Name the real limit of a system (scale, data integrity, security, cost) before calling it ready.

## Background

Systems Analysis and Development, Descomplica (2022 to 2024), with an academic excellence award in Mobile Development and AI Algorithms. MBA in Information Security, Descomplica (on hold). Before software: army, smartphone repair, administrative work.

[LinkedIn](https://www.linkedin.com/in/joão-victor-equer-5033b8209)
