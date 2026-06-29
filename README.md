<div align="center">

# Sanan Malik

**Backend Engineer · AI Systems · CS Undergrad @ MNS University, Multan · '28**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sanan-malik-9a4412325)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:iamsanan50@gmail.com)

</div>

---

I build backend systems that connect structured data pipelines to AI inference layers — REST APIs, multi-agent orchestration, production deployments on real infrastructure. I am currently extending this into ML: learning how trained components can replace the heuristics I currently hand-engineer into my systems.

---

## What I Work On

**Backend first.** C#, ASP.NET Core Web API, EF Core, SQL Server. Layered architecture, repository pattern, ADO.NET where it matters. This is where most of my production code lives.

**AI integration.** OpenAI and Gemini APIs wired into backend pipelines. Prompt design, schema enforcement, output validation. Not just calling an endpoint — handling what happens when the model returns something wrong.

**Multi-agent systems.** Coordinating specialized agents that check each other's work. Self-correction loops, confidence scoring, explicit disagreement protocols between agents.

**ML foundations (active).** Linear algebra, probability, Andrew Ng specializations, moving toward PyTorch. Goal is to understand what is happening inside the models I am already integrating.

---

## Projects

### SentinelIQ — Web Intelligence Platform

Monitors competitors and markets in real time. Scrapes live sources via Bright Data, runs OpenAI inference over extracted signals, returns structured intelligence through a REST API.

The non-obvious problem: hallucination drift compounds silently across pipeline stages. A single degraded summary poisons downstream outputs before anything flags it. I handle this with confidence-gated filtering — outputs below threshold get flagged and held, not surfaced.

`C#` `ASP.NET Core` `EF Core` `SQL Server` `OpenAI API` `Bright Data` `Next.js` `TypeScript`

---

### SIFT Guardian — Multi-Agent Security Forensics

Built for the UC Berkeley AI Hackathon. Four agents — Investigator, Skeptic, Verifier, Reporter — running a self-correction loop over security telemetry. If the Skeptic finds missing evidence, it halts the Investigator and pulls the gap before the report runs.

The non-obvious problem: retry logic is not the same as disagreement. I built inter-agent confidence scoring so agents can formally challenge each other mid-analysis rather than silently passing bad data forward.

`C#` `ASP.NET Core` `.NET 10` `JavaScript`

---

### Cognivex AI — Academic Workflow Agent *(Live on Vultr VPS)*

Parses uploaded academic documents — PDFs, images, plain text — extracts tasks and deadlines, generates structured study plans. Running behind Nginx on a VPS I manage directly.

The non-obvious problem: failure is silent. An agent that produces a plausible-looking plan over insufficient data is worse than one that admits it has nothing. I built extraction confidence checks that surface incomplete parses explicitly rather than letting the planning layer guess.

`C#` `ASP.NET Core` `SQL Server` `Gemini API` `React` `Nginx` `Vultr`

---

### STEMPilot AI — Adaptive Learning Platform *(DSH Hacks V1)*

Identifies student knowledge gaps through quizzes, tracks performance over time, and adjusts content delivery based on results.

`C#` `ASP.NET Core` `SQL Server` `React`

---

## Stack

```
Backend       C#  ·  ASP.NET Core Web API  ·  ADO.NET  ·  EF Core
Data          SQL Server  ·  Stored Procedures  ·  Repository Pattern
AI            OpenAI API  ·  Gemini API  ·  Prompt Engineering  ·  Agent Orchestration
Infra         Vultr VPS  ·  Nginx  ·  Git
Frontend      React  ·  Next.js  ·  TypeScript  ·  Tailwind CSS
ML (active)   Python  ·  NumPy  ·  Linear Algebra  ·  Andrew Ng Specializations
```

---

## Where This Is Going

My FYP (2025–2028) targets a publishable result in intelligent systems or multi-agent coordination. The open research question I keep running into: how do you build agentic systems that know what they do not know — and communicate that reliably instead of hallucinating confidence?

Targeting funded MS CS programs in the USA, Fall 2028. Research alignment is the primary filter.

---

<div align="center">
<sub>Open to research collaboration and backend/AI internship opportunities · <a href="mailto:iamsanan50@gmail.com">iamsanan50@gmail.com</a></sub>
</div>
