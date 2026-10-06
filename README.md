## Hi, I'm Erin

Software developer in Birmingham.
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

### What I do

- **For clients:** complete software solutions, from full applications to the AI workflows that run inside them.
- **In-house:** the internal tools and AI systems the team uses every day.

Most of that work is private, so each project below links to an overview repo that explains what it does and how it's built.

### What I've shipped

**[Talus](https://github.com/erinnod/talus-app)** · *React Native, Expo, Supabase, Mapbox* · live on the App Store\
An offline-first bouldering log for climbers who log at the crag with no signal, with a statistical coach that tells you what to work on next and a community map of over 10,000 spots.

**[Figma → spec agent](https://github.com/erinnod/figma-spec-agent)** · *Claude Code, Figma MCP*\
Paste a Figma handoff and it reads every screen, then writes two reports: plain English for the client, technical for the developer. Every open question is backed by evidence from the design.

**Shopify product automation** · *n8n, LLMs, Shopify Admin API* · live in production\
Product photos land in Google Drive, get cropped and re-backgrounded, an LLM writes titles and descriptions from the images, and a 25-node n8n workflow publishes them to Shopify for a client.

**[ASP.NET → Hono migration](https://github.com/erinnod/aspnet-to-hono)** · *Hono, Cloudflare Workers, Postgres, Drizzle*\
A strangler-fig toolkit for moving a legacy ASP.NET + SQL Server backend onto Cloudflare Workers one endpoint at a time, with responses matched byte for byte. On a production CRM it moved 200+ endpoints and 130+ tables while the app stayed fully usable.

**[Life-OS](https://github.com/erinnod/life-os-agent)** · *Python, Raspberry Pi 5, Telegram* · running daily since May 2026\
A personal AI operating system on a Raspberry Pi. It reads a 132-note Obsidian vault, runs 18 scheduled jobs and hands work to five specialist agents, then sends one message at 06:00: exactly two tasks, each tied to a quarterly goal.

### How I build

- **Track delivery, not just execution.** Life-OS once had jobs firing with nothing arriving. Now delivery is tracked, so a green check can't hide a broken system.
- **Plan for models disappearing.** The daily model rotator won't save a new list unless at least three fallbacks survive.
- **Only spend tokens on judgement.** Jobs that don't need an LLM run as plain scripts, so half the schedule costs nothing.
- **Make the stats earn their claims.** Talus's coach only says something when the sample size can back it up.
