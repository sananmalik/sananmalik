<div align="center">

```
███████╗ █████╗ ███╗   ██╗ █████╗ ███╗   ██╗    ███╗   ███╗ █████╗ ██╗     ██╗██╗  ██╗
██╔════╝██╔══██╗████╗  ██║██╔══██╗████╗  ██║    ████╗ ████║██╔══██╗██║     ██║██║ ██╔╝
███████╗███████║██╔██╗ ██║███████║██╔██╗ ██║    ██╔████╔██║███████║██║     ██║█████╔╝ 
╚════██║██╔══██║██║╚██╗██║██╔══██║██║╚██╗██║    ██║╚██╔╝██║██╔══██║██║     ██║██╔═██╗ 
███████║██║  ██║██║ ╚████║██║  ██║██║ ╚████║    ██║ ╚═╝ ██║██║  ██║███████╗██║██║  ██╗
╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝╚═╝  ╚═══╝    ╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝╚═╝╚═╝  ╚═╝
```

</div>

<div align="center">

**Backend Developer · CS Student at MNS University of Agriculture, Multan**

I build clean, reliable APIs and care about writing code that still makes sense six months later.
My stack is centered on .NET — C#, ASP.NET Core Web API, SQL Server, and ADO.NET.
Currently grinding LeetCode, deepening system design fundamentals, and aiming for a successful career in the US.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sanan-malik-9a4412325)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@gmail.com)

</div>

---

## 🛠 Tech Stack

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![ADO.NET](https://img.shields.io/badge/ADO.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity_Framework-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## 🚀 Featured Projects

<br>

### 🌐 SentinelIQ — Real-Time Web Intelligence Platform

> *AI-powered enterprise intelligence that monitors the live web for competitor activity, market movements, and risk signals — turning raw web data into structured, actionable business intelligence.*

Built for a hackathon. Phase 1 backend is live; Bright Data integration and AI summarization pipeline are next.

**What it does:**
- Tracks pricing changes, product launches, hiring trends, and customer sentiment in real time
- Uses OpenAI to generate business summaries, market insights, and risk assessments automatically
- Detects funding announcements, hiring spikes, layoffs, and competitor expansion as they happen
- Layered REST API: Controller → Service → Repository, clean DTOs, custom exceptions

**Stack:** `ASP.NET Core Web API` `SQL Server` `Entity Framework Core` `OpenAI API` `Bright Data (SERP, Scraper, MCP)` `Next.js` `TypeScript` `Tailwind CSS`

```
Architecture
─────────────────────────────────────────────
Frontend Dashboard (Next.js)
        ↓
ASP.NET Core Web API
        ↓
Bright Data Intelligence Layer
        ↓
OpenAI Engine
        ↓
SQL Server
```

<br>

---

### 🧠 Cognivex AI — Autonomous Academic Workflow Platform

> *Agent-based academic productivity platform that analyzes uploaded assignments, extracts tasks, prioritizes workloads, and generates structured study plans through autonomous AI workflows.*

Unlike a chatbot — this is about intelligent task orchestration across multi-step academic assistance pipelines.

**What it does:**
- Accepts PDF, image, or plain text assignments and extracts requirements, deadlines, and subtasks
- Autonomous Planning Agent divides work into subtasks, estimates effort, and generates study roadmaps
- Deployed on a Vultr VPS behind Nginx — production experience from day one
- Full workflow pipeline: Upload → Analysis → Task Extraction → Prioritization → Dashboard Response

**Stack:** `ASP.NET Core Web API` `C#` `SQL Server` `Google Gemini API` `React` `Tailwind CSS` `Vultr VPS` `Nginx`

```
Workflow Pipeline
─────────────────────────────────────────────
Assignment Upload
        ↓
Document Analysis Agent
        ↓
Task Extraction Engine
        ↓
Planning & Prioritization Agent
        ↓
Study Workflow Generation → SQL Server → Dashboard
```

<br>

---

### 🏦 Banking System API — ASP.NET Core

> *A backend banking system built with C# and ASP.NET Core Web API that simulates real-world banking operations. Built to practice layered architecture and OOP principles in a realistic context.*

This wasn't just about making it work — it was about structuring it the way a real production system should be structured.

**What it does:**
- Open accounts, deposit, withdraw, transfer funds between accounts
- Full transaction history with proper audit trail
- Invalid operations handled gracefully with custom exception classes — no generic 500s
- Raw SQL via ADO.NET — no ORM abstraction hiding what's actually happening

**Stack:** `C#` `ASP.NET Core Web API` `ADO.NET` `SQL Server` `Postman`

```
Layered Architecture
─────────────────────────────────────────────
Controllers  →  HTTP request handling
Services     →  Business logic
Repositories →  Database queries (raw ADO.NET)
DTOs         →  Request/response shapes
Exceptions   →  Custom error handling
```

| Method | Endpoint | Description |
|--------|----------|-------------|
| `POST` | `/api/accounts/create` | Create a new account |
| `POST` | `/api/accounts/deposit` | Deposit money |
| `POST` | `/api/accounts/withdraw` | Withdraw money |
| `POST` | `/api/accounts/transfer` | Transfer between accounts |

<br>

---

## 📌 Current Focus (2025–2026)

- [ ] Deep dive into ASP.NET Core — middleware, authentication, DI, EF Core
- [ ] LeetCode grind — targeting consistent problem solving
- [ ] Research experience — treating FYP as publishable work
- [ ] Building toward a fully funded MS in Computer Science in the US (Fall 2028)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=sananmalik&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&icon_color=58A6FF)
&nbsp;&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sananmalik&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9)

</div>

---

<div align="center">

*"I build things I'd want to maintain."*

</div>
