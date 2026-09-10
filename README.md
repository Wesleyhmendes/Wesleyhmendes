<h1 align="center">Wesley Mendes</h1>

<p align="center">
  <b>Tech Lead @ Liquid AI</b><br>
  I build agentic AI systems that run in production, not prototypes.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/wesley-mendes/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://wesleymendes.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:wesleymendes123321@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## What I build

**🤖 Agentic WhatsApp assistant — in production**
A tool-calling converse-loop on Amazon Bedrock with eleven action tools and a RAG
sub-agent over a knowledge base I built and publish through its own pipeline.
Context is engineered in blocks — a cached prefix carrying instructions, tool
catalogue and knowledge, plus a per-turn volatile directive — so prompt caching
pays off and cost per conversation drops.

Reliability is structural, not prompted: deterministic gates resolve before the
model runs, guardrails enforce consent and PII masking in code where the prompt
cannot reach them, and every figure is rendered in code. The model never writes a
number.

**🧠 Agentic operations CRM — front end and API**
Hexagonal architecture, published OpenAPI contract, versioned migrations with an
audit trail, per-feature authorization, and a domain model with arbitration-free
identity merging. Agents work the pipeline alongside human analysts: SLA-bound
task queue, case timeline, human-in-the-loop on every state change.

**⚙️ Multi-agent development harness — how my team ships**
A planner reads the board, breaks the work down and lays the queue out as a
dependency graph, dispatching everything unblocked in parallel. Implementer agents
run per service against versioned ADRs. Reviewer agents send corrections back. A
contract reviewer checks that service boundaries match the plan. A publisher opens
the PR and updates the docs. Context routing is a graph over the documentation —
each document declares the files it covers, so an agent traverses to the exact
file list instead of scanning the codebase.

Humans stay at both ends: defining the task, validating the delivery.

**💳 AI legal SaaS — own product, built solo**
From nothing to a billable product: multi-tenant with cross-tenant isolation
covered by tests, Stripe subscription billing with usage limits and dunning, AI
cost governance (monthly quotas, top-up credit, per-operation ceilings), and
data-protection compliance shipped before the first customer.

---

## Stack

**AI** ![Bedrock](https://img.shields.io/badge/Amazon%20Bedrock-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-2D8CFF?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-6E56CF?style=flat-square) ![Tool calling](https://img.shields.io/badge/Tool%20calling-0F9D58?style=flat-square) ![Multi-agent](https://img.shields.io/badge/Multi--agent-8B5CF6?style=flat-square) ![Context engineering](https://img.shields.io/badge/Context%20engineering-EC4899?style=flat-square) ![Guardrails](https://img.shields.io/badge/Guardrails-DC2626?style=flat-square)

**Languages** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

**Server** ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

**Client** ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Cloud** ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white) ![Serverless](https://img.shields.io/badge/Serverless-FD5750?style=flat-square&logo=serverless&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Wesleyhmendes&show_icons=true&theme=tokyonight&hide_border=true&card_width=450" alt="">
</p>
