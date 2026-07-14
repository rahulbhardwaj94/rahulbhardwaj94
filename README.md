<div align="center">

# Hi, I'm Rahul Bhardwaj 👋

### Backend & AI engineer (fintech) — I build systems that move money and tools developers actually download.

<p>
<a href="https://www.linkedin.com/in/rahul-bhardwaj-sde"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:rhlbhrdwj3@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/rahulbhardwaj94"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

</div>

---

5 years shipping **Node.js / NestJS microservices** in regulated fintech. My work has powered a direct credit-bureau integration that **saves ₹30L+ annually**, helped enable **₹70Cr+ in projected co-lending disbursements**, migrated **20+ microservices to EKS (~40% infra cost reduction)**, and taken a critical billing job from **6 minutes to 11.2 seconds**.

Now building at the intersection of **backend systems and applied AI** — agent orchestration, local-first voice AI, and developer tooling in the open. My Claude Code analyzer **`inspecto`** has crossed **3,000+ downloads** on npm.

---

## 🛠 Stack

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

> Daily drivers: NestJS · TypeScript · PostgreSQL (+ pgvector) · MongoDB · Redis · RabbitMQ · AWS (SQS · S3 · EKS · Lambda) · Kubernetes · Docker · Claude API / MCP

---

## 🔧 Open-source & AI projects

*Ranked by real-world impact — downloads, users, and problems solved.*

<table>
<tr>
<td width="50%" valign="top">

### 1. 📦 [inspecto](https://github.com/rahulbhardwaj94/inspecto)
Claude Code **session quality analyzer** — 12 behavioral & cost metrics pulled straight from your session logs.

![npm](https://img.shields.io/npm/v/inspecto?style=flat-square&logo=npm&color=CB3837)
![downloads](https://img.shields.io/npm/dt/inspecto?style=flat-square&logo=npm&label=downloads&color=CB3837)

`3,000+ npm downloads`

</td>
<td width="50%" valign="top">

### 2. 🛡 [veto](https://github.com/rahulbhardwaj94/veto)
**Cost governor for Claude Code** — a plugin that enforces spend policies before your agent burns your budget. Policy rules, session budgets, hard stops.

`220+ tests passing`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 3. 🕸 [agentrie](https://github.com/rahulbhardwaj94/agentrie)
NestJS **multi-agent orchestration & observability** platform — distributed agent coordination with W3C trace propagation and a full eval/scoring layer: dataset runner, trace-derived scorers, LLM-as-judge, and compare mode with regression detection.

`88+ tests passing · CLI exits non-zero on regressions`

</td>
<td width="50%" valign="top">

### 4. 🎙 Vani (वाणी) [वाणी](https://github.com/rahulbhardwaj94/vani)
**Fully local, offline voice dictation for macOS** (Apple Silicon) — WhisperKit + CoreML, zero network, zero data leaving your machine. Vani launched publicly; Uvaach is its open-source evolution, positioned as a **Wispr Flow alternative**.

`On-device ML · Privacy-first · Launched`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 5. 📝 [gradelee](https://github.com/rahulbhardwaj94/gradelee)
**AI homework grader** — snap a photo of handwritten work → OCR → RAG retrieves syllabus context → adaptive feedback + grade. Serverless on AWS (API Gateway · Lambda · CDK), end-to-end in **~8s**.

Model sits behind one **swappable provider seam** (env-var driven) — hosted fast model in the sync path, and flips to **fully offline Gemma 12B** for zero-network validation. Eval harness scores grounding, accuracy, and p50/p95 latency across models.

`Built AI-augmented with Claude Code in 4 days`

</td>
<td width="50%" valign="top">

### 6. 🔍 [traceglass](https://github.com/rahulbhardwaj94/traceglass)
**Tamper-evident audit logging for AI agents** — SHA-256 hash-chained logs so you can prove what your agent did (and didn't do). Built for the coming wave of AI compliance requirements.

`Hash-chain integrity verification`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 7. 🧠 [memory-os](https://github.com/rahulbhardwaj94/memory-os)
Local-first **AI memory vault** — NestJS + PostgreSQL + pgvector, exposed over the **Model Context Protocol**. Long-term memory for any MCP-capable agent.

`Active`

</td>
<td width="50%" valign="top">

### 8. ⏰ [timebomb](https://github.com/rahulbhardwaj94/timebomb)
Static analysis for code that fails **later** — `setTimeout` int32 overflows, unbounded `Promise.all`, sequential awaits in loops.

`🔥 Found real bugs in inspecto itself`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 9. 📊 trendrie
**YouTube intelligence platform** for tracking AI/dev-tools content trends — what's rising, what's saturated, where the gaps are.

`In development`

</td>
<td width="50%" valign="top">

### 10. 🎤 Local mock interview coach
Fully offline **interview practice app** — Electron + Python sidecar, mlx-whisper for transcription, MediaPipe for delivery analysis. Practice out loud, get feedback, nothing leaves your laptop.

`On-device AI · Electron + Python`

</td>
</tr>
</table>

---

## 💼 Production work (fintech / NBFC & manufacturing)

**Direct credit bureau integration (CIBIL)** — replaced a third-party aggregator with a direct integration: orchestration layer, PDF report generation, async processing at scale. **₹30L+/year saved.**

**Co-lending module (CLM2)** — built the disbursement workflow that enabled co-lending operations: **₹14Cr+ actually disbursed**, supporting a projected **₹70Cr+** pipeline.

**EKS migration** — moved **20+ microservices** to Kubernetes on EKS, cutting infra costs by **~40%**.

**Billing job optimization** — took a critical billing process from **6 minutes → 11.2 seconds (~32x faster)** by eliminating sequential awaits and redundant DB round-trips.

**Multi-vendor data fetch service** — a single API layer over multiple data vendors with rate limiting, background jobs, and webhook callbacks.

**Enterprise workflow portals** — two greenfield systems for a large auto-components manufacturer: a **CRM complaint portal** (~74 endpoints, DB-configured approval workflows, per-request RBAC) and a **warranty claims portal** built as a pure table-driven state machine with idempotency keys, gapless claim numbering, and 3-system JWT federation.

---

## ✍️ Elsewhere

I write real backend debugging stories on **[LinkedIn](https://www.linkedin.com/in/rahul-bhardwaj-sde)** — production war stories with the actual fixes.

---

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=rahulbhardwaj94&show_icons=true&hide_border=true&theme=tokyonight)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=rahulbhardwaj94&layout=compact&hide_border=true&theme=tokyonight)

📫 **[rhlbhrdwj3@gmail.com](mailto:rhlbhrdwj3@gmail.com)**

</div>
