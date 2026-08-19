<div align="center">

# Fernando Abishai

### Founder of [TriHerm](https://www.triherm.com/) · AI / software engineer · protocol & infrastructure builder

I build systems for the point where **AI agents, businesses, software, and economic workflows meet**.

My current work focuses on agentic commerce, interoperability, production AI systems, and the infrastructure required for software agents to coordinate real-world services reliably.

[TriHerm](https://www.triherm.com/) · [GitHub](https://github.com/FernandoAbishai) · [YouTube](https://www.youtube.com/@FernandoAbishai) · [Writing](https://blog.triherm.com/)

</div>

---

## What I am building toward

Software agents are becoming capable of discovering information, reasoning, using tools, and executing increasingly complex tasks. The harder problem is what happens when those agents must interact with the real economy.

I am interested in the infrastructure between **intent and execution**:

```text
observe / request
      ↓
discover capabilities
      ↓
evaluate + quote
      ↓
authorize + transact
      ↓
execute real-world work
      ↓
verify outcome
```

That means working on questions around:

- machine-readable business capabilities;
- agent-to-business discovery and coordination;
- protocol interoperability and translation boundaries;
- permissions, policy, identity, and human approval;
- quoting, ordering, payments, fulfillment, and verification;
- connecting agent-facing protocols to the operational systems businesses already use.

I do not think the answer is to replace every CRM, ERP, field-service platform, payment rail, or protocol with one universal system. A large part of the interesting engineering problem is making these systems cooperate without losing operational authority or business semantics.

---

## Founder — [TriHerm](https://www.triherm.com/)

TriHerm is the company through which I am exploring and building this direction.

It began with practical business automation and operational software. That work exposed a broader problem: as agents become economic actors, businesses need a reliable coordination layer between agent intent and real-world execution.

The long-term direction is an **economic coordination / commerce execution layer for machine economies** — infrastructure that can sit above existing business systems and settlement rails rather than requiring businesses to replace them.

Current areas of work include:

- agent-to-business commerce infrastructure;
- service discovery and machine-readable capabilities;
- normalized economic workflow representations;
- authority-aware adapters into existing operational systems;
- programmable settlement and agent payments;
- fulfillment, evidence, verification, and auditability;
- production business systems that provide the practical test bed for these ideas.

TriHerm is deliberately being developed from real operational constraints outward rather than from protocol theory alone.

---

## Selected engineering work

### [agent-service-interop](https://github.com/FernandoAbishai/agent-service-interop)

A public interoperability experiment exploring whether one real-world service workflow can be exposed through multiple agent-facing protocols **without replacing the business system that remains operationally authoritative**.

The project currently investigates:

- AIP and A2A interoperability;
- normalized representations of economic workflow state;
- separation between protocol identity, canonical identity, and operational identity;
- authority-aware command/write boundaries;
- privacy-minimized intake;
- protocol/schema validation and executable falsification tests;
- future adapters for settlement and verification.

The goal is not to invent another universal protocol. It is to test where translation, normalization, and coordination actually provide value — and where they fail.

### [ScriptCut](https://github.com/FernandoAbishai/ScriptCut)

An open-source, local-first desktop video production system built around transcript editing, AI-assisted workflows, and creator-owned processing.

ScriptCut combines Electron, React, FastAPI, FFmpeg, local transcription engines, optional AI providers, persistent project state, export pipelines, and packaged desktop runtimes.

It reflects another part of how I like to build: products where architecture, UX, local infrastructure, packaging, reliability, and AI behavior all have to work together rather than existing as isolated demos.

### TriHerm production systems

Alongside the public protocol work, I build the production systems behind TriHerm: guided acquisition flows, operational workflows, protected internal tooling, commerce infrastructure, data pipelines, human approval boundaries, and integrations with external business systems.

That practical layer matters because infrastructure ideas become much more useful when they are forced to survive real state transitions, payment behavior, failure modes, permissions, and operational edge cases.

---

## How I approach engineering

I tend to work across product, architecture, implementation, and research rather than treating them as separate disciplines.

A few principles recur in my work:

- **Preserve the source of truth.** Integration layers should not casually become the operational authority.
- **Make claims executable.** Important architectural assumptions should become tests, invariants, fixtures, or falsification conditions.
- **Prefer boundaries over magic abstractions.** Good interfaces make ownership, permissions, state, and failure explicit.
- **Build from real workflows.** Protocols and agent systems are more convincing when tested against actual business constraints.
- **Keep humans in the right places.** Autonomy should increase where confidence and authorization support it, not simply because an agent can act.
- **Separate infrastructure from rails.** Payment providers, models, protocols, and operational systems should be replaceable when the architecture allows it.

---

## Current technical focus

- **Agentic systems:** tool use, durable workflows, structured outputs, evaluations, permissions, approval gates, and observability.
- **Agentic commerce:** discovery, service capabilities, quotes, orders, settlement, fulfillment, verification, and exceptions.
- **Protocol interoperability:** AIP, A2A, MCP and adjacent standards, with emphasis on semantic and authority boundaries.
- **Production AI:** retrieval, model orchestration, reliability, evaluation, human review, and integration into existing systems.
- **Programmable payments:** stablecoins, Base, USDC, x402-style payment flows, Stripe, and rail-neutral transaction architecture.
- **Operational software:** APIs, internal platforms, workflow systems, business data, and integrations.
- **Local-first software:** desktop applications and AI systems that preserve user control where local execution makes sense.

---

## Technical range

```text
Languages       TypeScript · Python · JavaScript
Frontend        React · Next.js · Vite · Tailwind CSS · shadcn/ui
Backend         Node.js · FastAPI · REST APIs · serverless functions
Data            PostgreSQL · Supabase · structured pipelines · retrieval systems
AI              OpenAI · Codex · Claude · Gemini · Ollama · agents · RAG · evaluation
Protocols       A2A · AIP · MCP · schema-driven interoperability
Commerce        Stripe · stablecoin / programmable-payment research
Infrastructure  Docker · GitHub Actions · Vercel · self-hosted services
Desktop         Electron · FFmpeg · local-first application architecture
```

The specific stack matters less to me than being able to move from an ambiguous systems problem to a working architecture, implementation, test strategy, and product surface.

---

## Research, writing, and technical communication

I publish technical analysis and educational content about AI systems, software engineering, infrastructure, agentic commerce, emerging protocols, and the companies shaping these areas.

Explaining systems publicly is part of the engineering process for me: it forces clearer models, exposes weak assumptions, and creates a record of how ideas evolve.

[YouTube](https://www.youtube.com/@FernandoAbishai) · [Writing](https://blog.triherm.com/)

---

<div align="center">

**Building the infrastructure between machine intent and real-world execution.**

</div>
