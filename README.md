<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=3000&color=E6EDF3&center=true&vCenter=true&width=600&height=60&lines=Sanan+Malik">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=3000&color=1a1a2e&center=true&vCenter=true&width=600&height=60&lines=Sanan+Malik" alt="Sanan Malik"/>
</picture>

<p><code>Backend Systems · AI-Integrated Platforms · MNS University of Agriculture, Multan · CS '28</code></p>

<p>
<a href="https://linkedin.com/in/sanan-malik-9a4412325"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
&nbsp;
<a href="mailto:iamsanan50@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

</div>

---

I build backend systems that connect structured data pipelines to AI inference layers. My current work sits at the intersection of REST API design, multi-agent orchestration, and production deployment — areas I'm developing toward graduate research in intelligent systems.

---

## Research Interests

Systems that reason over incomplete or adversarial data. Specifically: how multi-agent architectures can coordinate under uncertainty, how knowledge can be extracted reliably from unstructured web sources, and how backend infrastructure can be designed to support reproducible AI pipelines.

---

## Selected Projects

### SentinelIQ — Web Intelligence Platform
Real-time competitor and market monitoring system. Scrapes live web sources via Bright Data, runs OpenAI inference over extracted signals, and surfaces structured business intelligence through a layered REST API.

**What makes it non-trivial:** The pipeline has to be robust to inconsistent HTML structure, rate limits, and hallucination drift in summaries. I handle this through source normalization, prompt constraints, and confidence-gated output filtering.

`ASP.NET Core` · `EF Core` · `SQL Server` · `OpenAI API` · `Bright Data` · `Next.js` · `TypeScript`

---

### SIFT Guardian — Multi-Agent Incident Response *(UC Berkeley AI Hackathon)*
Autonomous security forensics system built around four specialized agents: Investigator, Skeptic, Verifier, and Reporter. The system runs a self-correction loop — if any agent flags missing telemetry, it requests and pulls the gap before generating a final advisory.

**What makes it non-trivial:** Self-correction in agentic systems requires explicit disagreement protocols between agents. I implemented an inter-agent confidence scoring mechanism so the Skeptic can halt and redirect the Investigator mid-analysis.

`C#` · `ASP.NET Core` · `.NET 10` · `JavaScript`

---

### Cognivex AI — Academic Workflow Agent *(Production Deployment)*
Agent-based platform that parses uploaded academic documents, extracts tasks and deadlines, and generates structured study plans. Deployed on Vultr VPS behind Nginx.

**What makes it non-trivial:** Multi-format input parsing (PDF, image, plain text) with consistent structured output requires careful prompt design and schema enforcement. Failure modes are silent — the agent must detect when it hasn't extracted enough to plan.

`ASP.NET Core` · `C#` · `SQL Server` · `Gemini API` · `React` · `Nginx`

---

## Technical Foundation

| Layer | Tools |
|---|---|
| Backend | C#, ASP.NET Core Web API, ADO.NET, EF Core |
| Data | SQL Server, stored procedures, repository pattern |
| AI Integration | OpenAI API, Gemini API, prompt engineering, agent orchestration |
| Infrastructure | Vultr VPS, Nginx, Git |
| Frontend | React, Next.js, TypeScript, Tailwind CSS |

---

## Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sananmalik&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&hide_title=true&custom_title=&hide_rank=false" height="140"/>
&nbsp;&nbsp;
<img src="https://streak-stats.demolab.com?user=sananmalik&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" height="140"/>

</div>

---

## Current Work

- Building toward a publishable Final Year Project in intelligent systems (2025–2028)
- Developing ML foundations: linear algebra, probability, Andrew Ng specializations, PyTorch
- Targeting funded MS CS programs, Fall 2028 — research alignment is the primary focus

---

<div align="center">
<sub>Open to research collaboration and internship opportunities. Email is the fastest way to reach me.</sub>
</div>
