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

I build backend systems that connect structured data pipelines to AI inference layers. My work sits at the intersection of REST API design, multi-agent orchestration, and production deployment. I am now extending this foundation into ML — specifically, learning how to replace hand-engineered heuristics in my existing systems with trained components.

---

## Research Interests

How multi-agent architectures coordinate under uncertainty. How knowledge can be extracted reliably from unstructured web sources. How backend infrastructure can be designed to support reproducible, observable AI pipelines.

These questions came directly out of building the projects below — not from reading about them.

---

## Selected Projects

### SentinelIQ — Web Intelligence Platform

Real-time competitor and market monitoring system. Scrapes live web sources via Bright Data, runs OpenAI inference over extracted signals, and surfaces structured business intelligence through a layered REST API.

**The hard part:** Hallucination drift in LLM summaries compounds silently across pipeline stages. I handle this through confidence-gated output filtering — outputs below a defined threshold are flagged rather than surfaced, keeping downstream consumers from acting on degraded data.

`ASP.NET Core` · `EF Core` · `SQL Server` · `OpenAI API` · `Bright Data` · `Next.js` · `TypeScript`

---

### SIFT Guardian — Multi-Agent Incident Response *(UC Berkeley AI Hackathon)*

Autonomous security forensics system built around four specialized agents: Investigator, Skeptic, Verifier, and Reporter. The system runs a self-correction loop — if any agent flags missing telemetry, it requests and pulls the gap before generating a final advisory.

**The hard part:** Self-correction in agentic systems requires explicit disagreement protocols, not just retry logic. I implemented inter-agent confidence scoring so the Skeptic can halt and redirect the Investigator mid-analysis rather than letting low-confidence signals propagate to the final report.

`C#` · `ASP.NET Core` · `.NET 10` · `JavaScript`

---

### Cognivex AI — Academic Workflow Agent *(Production Deployment)*

Agent-based platform that parses uploaded academic documents, extracts tasks and deadlines, and generates structured study plans. Deployed on Vultr VPS behind Nginx.

**The hard part:** Failure modes are silent. The agent must detect when it has not extracted enough structure to produce a valid plan — and surface that explicitly — rather than generating a plausible-looking output over insufficient data. Schema enforcement and extraction confidence checks handle this.

`ASP.NET Core` · `C#` · `SQL Server` · `Gemini API` · `React` · `Nginx`

---

## Technical Stack

| Layer | Tools |
|---|---|
| Backend | C#, ASP.NET Core Web API, ADO.NET, EF Core |
| Data | SQL Server, stored procedures, repository pattern |
| AI Integration | OpenAI API, Gemini API, prompt engineering, agent orchestration |
| Infrastructure | Vultr VPS, Nginx, Git |
| Frontend | React, Next.js, TypeScript, Tailwind CSS |
| ML (in progress) | Python, NumPy, linear algebra, probability, Andrew Ng specializations |

---

## Direction

My existing systems handle agent coordination and inference integration at the application layer. The open question is how learned components — classifiers, embeddings, retrieval — can replace or improve the heuristics currently doing that work.

That is what I am building toward: an FYP (2025–2028) that produces a publishable result in intelligent systems, and funded MS CS admission in the USA for Fall 2028.

---

## Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sananmalik&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&hide_title=true&hide_rank=false" height="140"/>
&nbsp;&nbsp;
<img src="https://streak-stats.demolab.com?user=sananmalik&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" height="140"/>

</div>

---

<div align="center">
<sub>Open to research collaboration and internship opportunities in AI systems and backend infrastructure. Email is the fastest way to reach me.</sub>
</div>
