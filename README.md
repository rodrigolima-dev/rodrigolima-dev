<p align="center">
  <img src="assets/profile-banner.svg" alt="Rodrigo Lima — Full Stack Engineer + AI" width="100%" />
</p>

# Hi, I'm Rodrigo Lima 👋

**Full Stack Engineer + AI** based in Rio de Janeiro, Brazil. I build web and mobile products, APIs, and AI-assisted workflows that connect software to real operations.

At **OpportunusAI**, I work across product interfaces, integrations, automation, and data boundaries. My engineering priorities are clear user flows, explicit access control, reproducible setup, and evidence that a change actually works. I'm interested in remote Full Stack and AI engineering roles.

[Connect on LinkedIn](https://www.linkedin.com/in/rodrigo-lima-95a548242/) · [Explore my repositories](https://github.com/rodrigolima-dev?tab=repositories)

## Applied engineering

### [OpportunusAI Dashboard](https://github.com/rodrigolima-dev/opportunus-dashboard)

A runnable Next.js and TypeScript dashboard with fictional data, tenant-aware routes, and read-only APIs. I kept tenant membership and role permissions on the server, signed the demo session, and tested both allowed and denied access. The repository includes [architecture notes](https://github.com/rodrigolima-dev/opportunus-dashboard/blob/main/docs/ARCHITECTURE.md), [local setup](https://github.com/rodrigolima-dev/opportunus-dashboard#executar-localmente), and [passing CI](https://github.com/rodrigolima-dev/opportunus-dashboard/actions/workflows/ci.yml).

The key design decision is that switching a tenant in the interface never grants access to that tenant's data. The API checks membership on tenant-scoped requests; automated tests exercise forbidden access, expired sessions, and safe failure paths.



My applied AI work includes n8n and LangChain orchestration for operational workflows. I share code and demonstrations after checking data boundaries and reproducibility.

## Selected learning projects

| Project | What you can inspect | Status |
| --- | --- | --- |
| [Book Wishlist](https://github.com/rodrigolima-dev/Book-Wishlist) | React Native book list with local Realm persistence. | Mobile learning project with local storage. |
| [Space App](https://github.com/rodrigolima-dev/space-app) | React interface built while studying component composition and styled components. | Frontend learning project. |

My earlier HTML, CSS, Java, and React projects remain public as an honest record of how my work has evolved. Mobile and API projects receive focused security, documentation, and reproducibility reviews before I feature them here.

## Infrastructure and access

I work with Docker Swarm service operations, monitoring, controlled updates, and rollback planning. I use least-privilege access patterns, including Cloudflare Zero Trust, and verify runtime behavior after changes. For multi-customer systems, I treat isolation as an API and data-layer requirement rather than a visual setting.



## What I work with

- **Interfaces:** TypeScript, JavaScript, React, React Native, HTML, CSS
- **Backend and data:** Java, Spring Boot, REST APIs, PostgreSQL, MySQL, Firebase, Supabase
- **Systems:** Git, Docker Swarm, Cloudflare Zero Trust, monitoring, n8n, LangChain, integrations

I prefer a small, working slice with clear boundaries over a large demo that cannot be reproduced. For projects involving multiple customers, access control belongs in the data and API layers, not only in the interface.

<details>
<summary>Resumo em português</summary>

Sou Rodrigo Lima, desenvolvedor **Full Stack + IA** no Rio de Janeiro. Construo aplicações web e mobile, APIs e fluxos com IA ligados a operações reais. Na OpportunusAI, trabalho com interfaces, integrações, automação, Docker Swarm e separação segura de dados. Procuro oportunidades remotas em engenharia Full Stack e IA.

Os projetos acima mostram etapas diferentes da minha evolução. Documentação, testes e demonstrações são publicados conforme cada projeto passa por revisão técnica e de segurança.

</details>

## A little motion

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rodrigolima-dev/rodrigolima-dev/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rodrigolima-dev/rodrigolima-dev/output/github-contribution-grid-snake.svg" />
  <img alt="Animated snake following the GitHub contribution grid" src="https://raw.githubusercontent.com/rodrigolima-dev/rodrigolima-dev/output/github-contribution-grid-snake.svg" />
</picture>
