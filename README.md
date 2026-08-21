# Harshit Dhaduk

**AI/ML Engineer · Full-Stack Developer**

I build AI-powered products end to end: RAG pipelines, LLM integrations, and ML models, wrapped in backends and interfaces people actually use. Currently focused on retrieval systems and low-latency inference services on GCP and AWS.

Open to AI/ML and full-stack engineering roles.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-harshit--dhaduk-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/harshit-dhaduk)
[![X](https://img.shields.io/badge/X-@HarshitDhaduk-000000?logo=x&logoColor=white)](https://twitter.com/HarshitDhaduk)
[![Email](https://img.shields.io/badge/Email-dhadukharshit@gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:dhadukharshit@gmail.com)

---

## Featured Work

### [DevPulse](https://github.com/HarshitDhaduk/DevPulse) — Engineering health intelligence
A zero-ETL analytics platform that joins live GitHub, Linear, Slack, and Sentry data through Coral's federated SQL engine — no warehouse, no pipeline, no copies of anyone's data.

- Natural-language questions compiled to Coral SQL by Gemini, so managers query engineering health in plain English
- Automated morning standup digests: what's blocked, what shipped, what's broken, synthesized from live APIs
- Cross-source JOINs across SaaS tools that normally can't talk to each other

`Python` `FastAPI` `Next.js` `Coral (Federated SQL / MCP)` `Google Gemini` `Cloud Run`

### [Walk Through Time](https://github.com/HarshitDhaduk/walk-through-time) — 3D memorial walkway, 1526–present
A scroll-driven WebGL walk through Indian history, paired with a sourced ledger of the contemporary era. Built for Independence Day.

- 45 stations along an S-curved camera path, with 42 public-domain photographs hung behind glass and 51 clickable monuments the camera orbits
- Texture streaming keeps ~5 images resident instead of 42 — ~12 MB of VRAM rather than ~130 MB
- Ships as a fully static, offline-capable build (~52 kB app gzipped); reduced-motion and screen-reader paths built in, with a plain-HTML fallback when WebGL isn't available
- The Republic's Ledger: 91 verified source links, allegations kept separate from documented findings

`React` `Vite` `Three.js` `WebGL` `Canvas`

### [Amazon Rufus Twin](https://github.com/HarshitDhaduk/Amazon-Rufus-Twin) — AI-powered AEO diagnostics
A reverse-engineered pipeline that simulates how Amazon Rufus surfaces product recommendations, then reports back what's driving them.

- 6-stage AI pipeline returning a full diagnostic report in under 30 seconds
- Async RAG on Voyage AI + ChromaDB, keeping the server fully concurrent through high-latency LLM calls
- SSE streaming with intent-matched query planning — 95%+ agreement with manual audits
- Cloud Run deploys via Cloud Build CI/CD, with instance warming to cut cold starts

`Python` `FastAPI` `Next.js` `Voyage AI` `ChromaDB` `Docker` `GCP Cloud Run`

### [Chunav Mitra](https://github.com/HarshitDhaduk/Chunav-Mitra) — Civic tech for Indian elections
A gamified platform that teaches first-time voters how the electoral process actually works. **Scored 95+ at Google PromptWars.**

- 9-step persona-based journey with XP and badge progression
- EVM/VVPAT simulator built on state-machine logic and the Web Audio API
- Polling booth locator with live turn-by-turn routing

`Next.js` `TypeScript` `Gemini 2.5 Pro` `Google Maps Platform` `Docker`

---

## Tech

| | |
|---|---|
| **AI/ML** | Python, scikit-learn, RAG systems, LLM integration, Gemini, Voyage AI, ChromaDB, MCP |
| **Backend** | FastAPI, Node.js, Express, Flask, REST design, WebSockets, JWT/OAuth |
| **Frontend** | React, Next.js, TypeScript, Tailwind CSS, Three.js, Vite |
| **Data** | PostgreSQL, MySQL, MongoDB, Redis, Coral federated SQL, query optimisation |
| **Cloud & DevOps** | GCP (Cloud Run, Cloud Build), AWS (EC2, S3, Beanstalk), Docker, Nginx, GitHub Actions |
| **Tooling** | Git, Postman, Bull queues, PM2, Socket.IO |

---

## GitHub

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=HarshitDhaduk&theme=github_dark" />
    <img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=HarshitDhaduk&theme=github" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=HarshitDhaduk&theme=github_dark" />
    <img height="200" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=HarshitDhaduk&theme=github" alt="Top languages" />
  </picture>
</p>

![Profile views](https://komarev.com/ghpvc/?username=HarshitDhaduk&color=blue&style=flat)
