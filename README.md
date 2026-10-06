## Hi, I'm Erin

Software developer at [Shoothill](https://www.shoothill.com) in Birmingham.
I build AI workflows that are still running after the demo ends.

[Portfolio](https://portfolio-two-xi-95.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/erin-nodland/)

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![Postgres](https://img.shields.io/badge/Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

---

### What I've shipped

**Figma → spec agent** · *Claude Code, Figma MCP*
Paste a Figma handoff and it reads every screen, then writes two reports in under two minutes: plain English for the client, technical for the developer. Every open question is backed by evidence from the design.

**Shopify product automation** · *n8n, LLMs, Shopify Admin API* · live in production
Product photos land in Google Drive, get cropped and re-backgrounded, an LLM writes titles and descriptions from the images, and a 25-node n8n workflow publishes them to Shopify for a client.

**ASP.NET → Hono migration** · *Hono, Cloudflare Workers, Postgres, Drizzle*
A strangler-fig toolkit for moving a legacy ASP.NET + SQL Server backend onto Cloudflare Workers one endpoint at a time, with responses matched byte for byte so the client can't tell which backend answered. On a production CRM it moved 200+ endpoints and 130+ tables while the app stayed fully usable. Paired with a migration agent that crawls the legacy app, reads the solution and has Claude Code write the rebuild plan.

**Life-OS** · *Python, Raspberry Pi 5, Telegram* · running daily since May 2026
A personal AI operating system on a Raspberry Pi. It reads a 132-note Obsidian vault, runs 18 scheduled jobs and hands work to five specialist agents, then sends one message at 06:00: exactly two tasks, each tied to a quarterly goal.

### Currently building

**Talus** · *Expo, React Native, Supabase, Mapbox*
An offline-first bouldering tracker for climbers who log at the crag with cold hands and no signal, with a coach that builds session plans from your own log.

**RAG support assistant** · *Python, Chroma, Claude*
Answers questions grounded in a specific document set, with every answer traceable back to its source chunks.

### How I build

- **Track delivery, not just execution.** Life-OS once had jobs firing with nothing arriving. Now delivery is tracked, so a green check can't hide a broken system.
- **Plan for models disappearing.** The daily model rotator won't save a new list unless at least three fallbacks survive.
- **Only spend tokens on judgement.** Jobs that don't need an LLM run as plain scripts, so half the schedule costs nothing.

<sub>Most of this is client or personal work in private repos. Happy to walk through any of it.</sub>
