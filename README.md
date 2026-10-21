<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:3b82f6,100:8b5cf6&height=230&section=header&text=AmirHossein%20Shamsi&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=32&desc=AI%20Engineer%20%7C%20full-stack%20developer%20%7C%20Geospatial%20Systems&descAlignY=53&descSize=18" alt="AmirHossein Shamsi header" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=800&color=3B82F6&center=true&vCenter=true&width=650&lines=%E2%9C%A8+Building+intelligent+systems...;%F0%9F%A4%96+LLM+Agents+%26+MCP;%E2%9A%99%EF%B8%8F+Go+%26+Python+Backends;%F0%9F%97%BA%EF%B8%8F+Geospatial+%26+Routing;%F0%9F%8F%AD+Industrial+Telemetry" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/followers/Amir-Hossein-shamsi?label=FOLLOWERS&style=for-the-badge&color=8b5cf6&logo=github" alt="Followers" />
  <a href="mailto:shamsiamirhossein1@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://linkedin.com/in/amirhossein-s-b2b97b38b/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://amir-hossein-shamsi.github.io/portfolio/"><img src="https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
</p>

---

## 👨‍💻 About Me

```bash
$ whoami
amirhossein-shamsi

$ cat ~/profile.json
{
  "name":     "AmirHossein Shamsi",
  "role":     ["AI Engineer", "Backend Developer"],
  "focus":    ["LLM Agents", "MCP", "Geospatial Systems", "Industrial Telemetry"],
  "building": "AI-powered backends · routing engines · industrial monitoring",
  "tools":    ["Go", "Python", "FastAPI", ".NET", "PyTorch"],
  "motto":    "AI + Backend + Data + Infrastructure = One Reliable System"
}

$ sudo make impact
▸ training models............ done ✓
▸ deploying systems.......... done ✓
▸ solving real problems...... always ✓
```

I build **AI-powered applications, backend services, and intelligent geospatial and industrial systems**. I focus on practical engineering: architecture, implementation, and deployment of systems that work reliably in the real world.

---

## 🚀 Featured Projects

### 🏭 Industrial Machine Monitoring (Go)
A backend system written in Go for monitoring CNC and industrial machines. It ingests telemetry from edge devices, detects machine downtime, and triggers maintenance-related operational events.

### ⚙️ Job Scheduler
An administrator workspace for creating script jobs, scheduling their execution, and inspecting results.

```mermaid
flowchart LR
    UI["🖥️ Taskflow UI<br/>(Next.js)"] --> API["🔌 Go API"]
    API --> PG[("🐘 PostgreSQL")]
    SCH["⏱️ Scheduler"] --> PG
    SCH -->|LPUSH| RQ[("🧱 Redis queue")]
    RQ -->|BRPOP| W["👷 Worker"]
    W --> DK["🐳 Temporary Docker container"]
    DK -->|logs| PG
    UI -. SSE live logs .-> API
```

- **Execution:** each run starts a temporary Docker container with memory, CPU, PID, and timeout limits, a read-only filesystem, and no network by default
- **Runtimes:** Python, Node.js, Bash, Go, and SQL jobs against PostgreSQL, MySQL, SQL Server, or Oracle, with AES-256-GCM encrypted database passwords
- **Scheduling:** one-time runs, interval schedules, and cron expressions with IANA timezones
- **Monitoring:** persisted logs, cursor pagination, live SSE streaming with a polling fallback
- **Honest limits:** no retries, dead-letter queue, or stale-run recovery; designed for trusted administrators

**Stack:** `Go` `PostgreSQL 16` `Redis 7` `Docker` `Next.js` `TypeScript` `Tailwind CSS` `Playwright`

### 🧭 MarketLens AI
A Python backend for competitor and market research. Questions move through a LangGraph workflow: Groq models plan the search and synthesize the answer, Tavily retrieves live web results, and the system filters the evidence and stores each report. Answers include source URLs and a confidence score.

**Stack:** `Python` `FastAPI` `LangGraph` `Groq` `Tavily` `PostgreSQL` `Redis` `SQLAlchemy` `Docker Compose`

<!-- MORE PROJECTS: copy this block for each project
### 🔧 Project Name
One or two sentences on what it does and who it's for.

- **Key feature:** detail
- **Key feature:** detail

**Stack:** `Tech` `Tech`
-->

---

## 🧰 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,python,fastapi,dotnet,pytorch,docker,redis,postgres,elasticsearch,mongodb,linux,git,graphql,typescript,nextjs" />
</p>

| Area | Technologies |
|------|--------------|
| 🤖 **AI / LLM** | LangChain · LangGraph · MCP · RAG · OpenAI · Groq · PyTorch · scikit-learn |
| ⚙️ **Backend** | Go · Python · FastAPI · .NET · REST · GraphQL · WebSockets · SSE |
| 🗺️ **Geospatial** | OpenStreetMap · OSRM · OSMnx · GeoPandas · NetworkX · MapLibre |
| 🏭 **Industrial / Real-time** | Telemetry ingestion · event detection · edge devices |
| 🔎 **Data** | PostgreSQL · Redis · Elasticsearch · MongoDB · vector search |
| 🐳 **Infrastructure** | Docker · Compose · Linux · Git · CI/CD |

---

## 🧠 Areas of Interest

```mermaid
mindmap
  root((My Universe 🚀))
    Artificial Intelligence 🤖
      RAG
      LLM Agents
        LangChain
        LangGraph
        MCP
    Backend Engineering ⚙️
      Go
      FastAPI
      .NET
    Geospatial Systems 🗺️
      Routing
      TSP
      Traffic Modeling
    Industrial Systems 🏭
      Telemetry
      Downtime Detection
```

---

## 🚀 Currently Exploring

| Focus Area | Progress |
|------------|----------|
| 🤖 Advanced LLM Agents | `█████████░` |
| 🔗 MCP-based Applications | `████████░░` |
| 🕸️ LangGraph Multi-Agent Systems | `████████░░` |
| 🗺️ Intelligent Routing & Optimization | `███████░░░` |
| ⚡ Distributed Backend Systems | `███████░░░` |
| ☸️ Kubernetes & Cloud-Native | `███░░░░░░░` |

<sub>*bars measured in pure enthusiasm, not science 📏😄*</sub>

---

## 💬 Wisdom of the Day

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Random dev quote" />
</p>

---

## 📫 Connect With Me

<p align="center">
  <i>“Build intelligent systems.<br>
  Solve real problems.<br>
  Keep the engineering solid.”</i>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8b5cf6,50:3b82f6,100:06b6d4&height=140&section=footer&fontSize=24&fontColor=ffffff&animation=fadeIn" />
