<h1 align="center">👋 Hey, I'm Prathik Reddy</h1>

<h3 align="center">AI Engineer · Agentic Systems · Voice AI · AI-First Full Stack</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/prathik-reddy7/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:p.prathikreddy7@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/pprathik07">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://topmate.io/prathik7">
    <img src="https://img.shields.io/badge/Book%20a%20Session-6636F1?style=for-the-badge&logoColor=white" alt="Topmate"/>
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=6366F1&center=true&vCenter=true&random=false&width=600&lines=Building+Agentic+AI+Systems;Voice+AI+in+Hindi%2C+Kannada+%26+Telugu;Evals+%2B+Guardrails+for+LLM+Agents;AI-First+Full+Stack+Development" alt="Typing SVG" />
</p>

---

### About

AI engineer building agentic systems, multilingual voice agents, and AI-first full-stack products. I own projects end to end, from architecture to deployment, and I care about the unglamorous parts: evals, guardrails, and measuring what actually happens.

- **Agentic AI**: multi-agent pipelines, state-machine-controlled agents, eval harnesses, human-in-the-loop workflows
- **Voice AI**: real-time voice agents on LiveKit in English, Hindi, Kannada and Telugu, with a latency breakdown per stage
- **AI-First Full Stack**: Next.js, Fastify, Supabase/PostgreSQL, BullMQ, multi-model LLM orchestration
- **Automation**: n8n workflows with custom JS nodes
- Freelancing with businesses across India and UAE

---

### 🔨 Featured Projects

> **Self-Improving Clinic Scheduling Agent** · evals + gated improvement loop
>
> Multi-turn scheduling agent (book / reschedule / cancel). Safety is enforced in code through a state machine, tool allowlists per state, and write guards, not only in the prompt. A **3-layer eval harness** scores final database state first, then the tool-call trace, then an LLM judge. When a scenario fails, a reflector proposes a policy patch, the full eval re-runs, and a regression gate accepts or rolls back.
>
> In the real run, the gate **rejected its own patch** and rolled back. The trace showed the real cause was a code bug, which I then fixed. 305 offline tests, 15 scenarios (9 train / 6 held-out), and known limitations documented in the README.
>
> `Python` `Evals` `LLM-as-judge` `State machines` `pytest` `uv`
>
> [![View Code](https://img.shields.io/badge/View_Code-6366F1?style=flat-square&logo=github&logoColor=white)](https://github.com/pprathik07/self-improving-clinic-agent)
> [![Demo](https://img.shields.io/badge/Watch_Demo-Loom-625DF5?style=flat-square&logo=loom&logoColor=white)](https://www.loom.com/share/8bbb9701a85e4be7b87c83f46f1474b3)
---

> **Multilingual Voice Agent for Solar Lead Qualification** (EN / HI / KN / TE)
>
> Inbound and outbound voice agent where **the AI talks but rules decide**. A config-driven state machine controls which tools exist at each step, prices come only from a structured lookup (never from the model's memory), and low speech-recognition confidence triggers "please repeat" instead of a guess. Opt-out is honoured immediately, and the agent discloses that it is an AI when asked.
>
> Hardened against real failures: three live call transcripts exposed 8 critical bugs (language mixing, a subsidy-timeline hallucination, a closing loop, and others). Each was fixed and added as a regression scenario. 18 state-machine eval cases plus scripted call simulations.
>
> **Measured typical response time: ~1–1.2 s**, tracked per stage (turn detection, LLM first token, TTS) with p50/p90/p99 from call logs.
>
> `Python` `LiveKit` `Sarvam` `Cartesia` `Gemini` `FastAPI` `Celery` `PostgreSQL` `Redis`
---

> **Product Brain: AI-Native Product Management Tool**
>
> Ingests customer calls, support tickets, NPS data and analytics. An AI pipeline clusters signals, detects churn correlations, scores by impact, and generates weekly PRD drafts and Linear tickets. Multi-model orchestration (Claude Sonnet + Gemini Flash), async BullMQ workers, Next.js + Fastify + PostgreSQL monorepo.
>
> `TypeScript` `Next.js 14` `Fastify` `PostgreSQL` `Prisma` `BullMQ` `Redis` `Vercel` `Railway`
>
> `Private repo — [Demo](https://www.loom.com/share/c3066174b9db40679cdf4cc36300e6d4)`

---

> **AI Sales Intelligence: Multi-Agent Pipeline**
>
> Four specialised agents (company research, contact discovery, news monitor, competition analysis) with their own tools and reasoning loops. Context passes downstream, with a human review step before final output. Celery workers, Redis queue, real-time WebSocket execution tracking.
>
> `Python` `LangGraph` `CrewAI` `FastAPI` `Celery` `Redis` `WebSockets`
>
> [![View Code](https://img.shields.io/badge/View_Code-6366F1?style=flat-square&logo=github&logoColor=white)](https://github.com/pprathik07/sales_intelligence_agent)

---

> **Vajra Renew: Solar Company Website**
>
> Production Next.js 14 site for a solar company in Andhra Pradesh. Live at vajrarenew.com
>
> `Next.js 14` `TypeScript` `TailwindCSS` `Vercel`
>
> [![Live](https://img.shields.io/badge/Live-00C7B7?style=flat-square&logo=vercel&logoColor=white)](https://vajrarenew.com)

---

### Skills

**Agentic AI & LLMs**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-000000?style=for-the-badge&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-000000?style=for-the-badge&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

**Voice AI & Real-Time Audio**

![LiveKit](https://img.shields.io/badge/LiveKit-000000?style=for-the-badge&logo=webrtc&logoColor=white)
![Sarvam](https://img.shields.io/badge/Sarvam_AI-000000?style=for-the-badge&logoColor=white)
![Cartesia](https://img.shields.io/badge/Cartesia-000000?style=for-the-badge&logoColor=white)
![ElevenLabs](https://img.shields.io/badge/ElevenLabs-000000?style=for-the-badge&logoColor=white)

**Full Stack & Data**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

**Deployment**

![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

### 🤝 Work With Me

Open to select remote freelance projects in **voice AI, agentic systems, and AI-first full stack**. Private repos are shared on request.

<p align="center">
  <a href="https://www.linkedin.com/in/prathik-reddy7/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:p.prathikreddy7@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>
