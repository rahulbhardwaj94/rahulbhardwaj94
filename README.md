<div align="center">

# Hi, I'm Rahul Bhardwaj 👋

### Backend engineer (fintech) — I build systems that move money and tools developers actually download.

<p>
<a href="https://www.linkedin.com/in/rahul-bhardwaj-sde"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:rhlbhrdwj3@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/rahulbhardwaj94"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

</div>

---

5 years shipping **Node.js / NestJS microservices** in regulated fintech. My work has powered a direct credit-bureau integration that **saves ₹30L+ annually**, helped enable **₹70Cr+ in projected co-lending disbursements**, and taken a critical billing job from **6 minutes to 11.2 seconds**.

I also build developer tooling in the open — my Claude Code analyzer **`inspecto`** has crossed **3,000+ downloads** on npm.

---

## 🛠 Stack

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

> Daily drivers: NestJS · TypeScript · PostgreSQL · MongoDB · Redis · RabbitMQ · AWS (SQS · S3 · EKS · Lambda) · Kubernetes · Docker

---

## 🔧 Open-source projects

<table>
<tr>
<td width="50%" valign="top">

### 📦 [inspecto](https://github.com/rahulbhardwaj94/inspecto)
Claude Code **session quality analyzer** — 12 behavioral & cost metrics pulled straight from your session logs.

![npm](https://img.shields.io/npm/v/inspecto?style=flat-square&logo=npm&color=CB3837)
![downloads](https://img.shields.io/npm/dt/inspecto?style=flat-square&logo=npm&label=downloads&color=CB3837)

</td>
<td width="50%" valign="top">

### ⏰ [timebomb](https://github.com/rahulbhardwaj94/timebomb)
Static analysis for code that fails **later** — `setTimeout` int32 overflows, unbounded `Promise.all`, sequential awaits in loops.

`🔥 Found real bugs in inspecto itself`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 [memory-os](https://github.com/rahulbhardwaj94/memory-os)
Local-first **AI memory vault** — NestJS + PostgreSQL + pgvector, exposed over the Model Context Protocol.

`Active`

</td>
<td width="50%" valign="top">

### 🕸 [agentrie](https://github.com/rahulbhardwaj94/agentrie)
NestJS **multi-agent orchestration & observability** platform — distributed agent coordination with a full eval/scoring layer: dataset runner, trace-derived scorers, LLM-as-judge, and compare mode with regression detection.

`88 tests passing · CLI exits non-zero on regressions`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📝 [gradelee](https://github.com/rahulbhardwaj94/gradelee)
**AI homework grader** — snap a photo of handwritten work → OCR → RAG retrieves syllabus context → adaptive feedback + grade. Serverless on AWS (API Gateway · Lambda · CDK), end-to-end in **~8s**.

The model lives behind one **swappable provider seam** (env-var driven): ships on a hosted fast model in the sync path, with quota-aware backoff in the eval harness — and flips to **fully offline Gemma 4 12B** with zero network for validation. Eval harness scores grounding, accuracy, and p50/p95 latency across models.

`Built AI-augmented with Claude Code in 4 days`

</td>
<td width="50%" valign="top">

&nbsp;

</td>
</tr>
</table>

---

## 💼 Production work (fintech / NBFC)

**Direct credit bureau integration (CIBIL)** — replaced a third-party aggregator with a direct integration: orchestration layer, PDF report generation, async processing at scale. **₹30L+/year saved.**

**Co-lending module (CLM2)** — built the disbursement workflow that enabled co-lending operations, supporting a projected **₹70Cr+** pipeline.

**Multi-vendor data fetch service** — a single API layer over multiple data vendors with rate limiting, background jobs, and webhook callbacks.

**Billing job optimization** — took a critical billing process from **6 minutes → 11.2 seconds (~32x faster)** by eliminating sequential awaits and redundant DB round-trips.

---

## ✍️ Elsewhere

I write real backend debugging stories on **[LinkedIn](https://www.linkedin.com/in/rahul-bhardwaj-sde)** — production war stories with the actual fixes.

---

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=rahulbhardwaj94&show_icons=true&hide_border=true&theme=tokyonight)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=rahulbhardwaj94&layout=compact&hide_border=true&theme=tokyonight)

📫 **[rhlbhrdwj3@gmail.com](mailto:rhlbhrdwj3@gmail.com)**

</div>
