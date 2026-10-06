## Hi, I'm Erin

I'm a software developer in Birmingham. I build software for clients, from full apps to the AI workflows that run inside them, and I build internal tools and AI systems for the team I work in. These days most of what I do is AI: agents, automations and everything around them that keeps them running.

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

### Things I've built

Most of my work is private, so the links go to write-ups rather than code.

**[Talus](https://github.com/erinnod/talus-app)**: a bouldering log app, live on the App Store. It works offline at the crag, syncs later, and has a coach that looks at your sessions and tells you what to work on. *React Native, Expo, Supabase*

**[Figma → spec agent](https://github.com/erinnod/figma-spec-agent)**: give it a Figma link and it goes through every screen and writes up the questions that need answering before anyone starts building. One set for the client in plain English, one for the developer, and each question points at the part of the design that raised it. *Claude Code, Figma MCP*

**Shopify product automation**: live for a client. Product photos go into Google Drive, get cropped and have the background swapped, an LLM writes the titles and descriptions from the photos, and a 25-node n8n workflow puts them on Shopify. *n8n, LLMs, Shopify Admin API*

**[ASP.NET → Hono migration](https://github.com/erinnod/aspnet-to-hono)**: moving an old ASP.NET + SQL Server backend onto Cloudflare Workers one endpoint at a time, so the app never goes down. On a production CRM it moved 200+ endpoints and 130+ tables while people were still using it. *Hono, Cloudflare Workers, Postgres, Drizzle*

**[Life-OS](https://github.com/erinnod/life-os-agent)**: my own AI assistant running on a Raspberry Pi. It reads my Obsidian vault, runs 18 scheduled jobs across five agents and sends me one Telegram message at 6am with two things to do that day, each tied to a goal. It's been running every day since May. *Python, Raspberry Pi 5, Telegram*

### Things I've learnt the hard way

- A job running isn't the same as a message arriving. Life-OS had a silent outage where everything looked fine and nothing got sent, so now it checks delivery.
- Models get pulled. Life-OS won't save its daily model list unless at least three fallbacks still work.
- Don't use an LLM where a script will do. About half of Life-OS's jobs are plain scripts and cost nothing to run.
- Stats need enough data behind them. The Talus coach stays quiet until it has enough sessions to back up what it's saying.
