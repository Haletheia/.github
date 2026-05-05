<div align="center">

![HALETHEIA Ecosystem](./assets/haletheia-github-hero-banner.png)

[![License: AGPL](https://img.shields.io/badge/License-AGPL%20v3-00ff88.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![EU AI Act Aligned](https://img.shields.io/badge/EU_AI_Act-Aligned_by_Design-00ff88.svg)]()
[![Zero-Trust Architecture](https://img.shields.io/badge/Zero--Trust-Hardware_Isolated-00D9FF.svg)]()
[![100% Traceable](https://img.shields.io/badge/100%25-Traceable-00ff88.svg)]()

**[🇪🇸 Versión en Español](./README.es.md)**

</div>

---

## 🎯 The Structural Crisis HALETHEIA Solves

Enterprise AI is facing a **structural trust crisis**:

- 🔴 **Undetected hallucinations** → Wrong business decisions
- 🔴 **Lack of traceability** → Impossible to audit for EU AI Act
- 🔴 **Monolithic black boxes** → You can't debug or optimize
- 🔴 **Ephemeral context** → Agents lose memory between sessions

**The real problem:** AI frameworks were born for prototypes, not for regulated production. Companies try to patch *compliance* at the last minute, and they fail.

### 💡 The HALETHEIA Solution

We invert the paradigm: **Governance and ethics are not an external filter, they are the base architecture.**

We build the structural ecosystem that:
- ✅ **Optimizes people**, not processes
- ✅ **Audits agents**, doesn't blindly trust them
- ✅ **Preserves human agency**, doesn't automate everything

---

## 🧬 The HALETHEIA Ecosystem

Our stack is divided into **Open Source (Legos)** and **Enterprise (Castle)**:

### 🟢 Open Source: Primitives for Responsible AI

We release our fundamental protocols and frameworks so the community can build ethical and traceable agents.

<table>
<tr>
<td width="33%" align="center">

### 📚 HCP Protocol
**Git-Native Context Management**

If code deserves Git, context deserves structure.

HCP is the **first git-native protocol** for governing context between humans and LLMs through structured directories (`.procontext/`).

**Real impact:**
- ✅ Validated in production (8+ months)
- ✅ Built by one engineer
- ✅ Proven in real projects
- ✅ Convergence with SPDD (Martin Fowler)

[![Explore HCP](https://img.shields.io/badge/🔗_Explore-HCP_Protocol-00D9FF?style=for-the-badge)](https://github.com/haletheia/hcp)

</td>
<td width="33%" align="center">

### 🧠 LiiADA Framework
**Modular Agent Orchestration**

100% modular orchestration framework.

Unlike monolithic black boxes, LiiADA connects **memory (CIPP)**, **multi-domain RAGs**, and **LLM providers** with traceability from the first token.

**Hexagonal architecture:**
- ✅ 13 independent modules
- ✅ Plug & Play capabilities
- ✅ Observability built-in
- ✅ Multi-LLM (Ollama, OpenAI, Anthropic, Gemini)

[![Explore LiiADA](https://img.shields.io/badge/🔗_Explore-LiiADA_Core-8800ff?style=for-the-badge)](https://github.com/haletheia/liiada-core)

</td>
<td width="33%" align="center">

### 📜 MEIA Manifesto
**Ethical Foundation**

The philosophical heart that guides our code.

The **"Ethics of the Excluded"** materialized in software development principles: Privacy by Design, Epistemic Humility, and Algorithmic Transparency.

**52+ interactive documents:**
- ✅ 11 main chapters
- ✅ 40+ analyzed ethical cases
- ✅ Living dynamic system (Astro)
- ✅ Real-time metrics

[![Read MEIA](https://img.shields.io/badge/🔗_Read-MEIA_Manifesto-00ff88?style=for-the-badge)](https://github.com/haletheia/meia)

</td>
</tr>
</table>

---

## 🏛️ The 5 Ethical Pillars of MEIA

<div align="center">

![MEIA Ethical Principles](./assets/meia-ethical-principles.png)

</div>

### 🔒 1. Privacy by Design
**Not compliance, it's architecture.**

- Data minimization from initial design
- Encryption by default, not as a patch
- GDPR and CCPA aligned from the first line of code

### 🤔 2. Epistemic Humility
**AI admits when it doesn't know.**

- No "creative" hallucinations in production
- Confidence metrics in every response
- The agent says "I don't have enough information" when necessary

### 🔍 3. Algorithmic Transparency
**Explainable decisions, auditable code.**

- Open Source by default (Legos)
- Structured and versioned logs (Git-Native)
- Traceability of every generated token

### 🧭 4. Human Agency
**Humans in the loop, not on autopilot.**

- Trust Loop: User approves every piece of evidence
- Granular control over agent autonomy
- You can always stop, review, or modify

### 👑 5. Cognitive Sovereignty
**Users own their AI context.**

- Context versioned in Git (no lock-in)
- Exportable, auditable, transferable
- You don't depend on a provider for your knowledge

> *"Optimize people, not processes. Uncover truth, maintain control."*  
> — MEIA foundational principle

---

## 📊 Real Validation

<div align="center">

![HALETHEIA Real Validation](./assets/haletheia-real-validation.png)

</div>

### 🌍 External Validation

**Industry convergence:**
- ✅ **Martin Fowler (ThoughtWorks)**: SPDD (Structured Prompt-Driven Development) validates the HCP approach
- ✅ **Anthropic**: Claude.md patterns converge with HCP
- ✅ **GitHub**: Copilot Workspace adopts structured context

**Honest about the journey:**
- 🏗️ Built solo by one engineer over 8+ months
- ✅ Validated in real production projects (own projects)
- ✅ Open Source protocols with clear philosophical foundation
- ✅ No fake star counts, no inflated metrics
- 🎯 Focus: Quality and coherence over vanity metrics

---

## 🔵 Enterprise: Compliance and Regulated Production

The HALETHEIA Open Source ecosystem embodies transparency. However, for deployments in **highly regulated** environments (finance, healthcare, government), organizations require:

- 🔐 **Immutable cryptographic audits**
- 🏗️ **Hardware isolation (KVM)**
- 🎛️ **Granular access control (RBAC)**
- 📋 **Automatic EU AI Act reports**

For these cases, we offer our **Enterprise (Castle)** layer:

### 🏢 NIDALI Enterprise Harness

<table>
<tr>
<td width="50%">

#### 🎨 NIDALI UI
**Corporate dashboard and human Trust Loop.**

- Unified control panel for all your agents
- Human validation of every piece of evidence (Trust Loop)
- Management of curated knowledge vaults
- Real-time confidence metrics

</td>
<td width="50%">

#### 🛡️ Sentinel Gateway
**Reactive firewall and hallucination prevention.**

- 100% non-blocking API Gateway (Java 21 reactive)
- Circuit Breakers for LLMs (Resilience4j)
- Intelligent routing (LiiADA ↔ Hidden Brain)
- Asymmetric timeouts per provider

</td>
</tr>
<tr>
<td width="50%">

#### 🧠 Hidden Brain (RAG 4.0)
**Generative and auditable Knowledge Base.**

- Agentic RAG with Pydantic AI
- Knowledge Integrity (Karpathy Linter)
- Token Optimization (aronly: -60-90%)
- Audit & Traceability (cutufato logs)
- Knowledge Graph (Neo4j) + Vector Search (pgvector)

</td>
<td width="50%">

#### 🏝️ Marisma Sandbox
**Hardware isolation for code execution.**

- Ephemeral Unikernels (KVM, not Docker)
- Megabyte VMs (not gigabytes)
- Radical security: hardware isolation
- ROI: 40-60% cloud savings vs containers

</td>
</tr>
</table>

### 📋 EU AI Act Compliance

HALETHEIA Enterprise automatically generates **audit evidence** according to Article 12 of the EU AI Act:

- ✅ **Structured logs** of every agent decision
- ✅ **Complete traceability** from input to output
- ✅ **Confidence metrics** for every response
- ✅ **Exportable reports** for audits

🏢 **[Discover our Enterprise solutions](https://haletheia.github.io)**

---

## 🛠️ Tools and OSS Gems

Besides our core, HALETHEIA publishes security and optimization tools under MIT/AGPL license:

| Tool | Purpose | Impact |
|------|---------|--------|
| **[aronly](https://github.com/drhiidden/aronly)** | Token optimization (Rust) | ↓ 60-90% token usage |
| **[babuino](https://github.com/drhiidden/babuino)** | Hardware isolation (KVM) | Secure AI code execution |
| **[xokito](https://github.com/drhiidden/xokito)** | Privacy framework | PII obfuscation and redaction |
| **[cutufato](https://github.com/drhiidden/cutufato)** | Auditable logs | Cryptographic traceability |

---

## 🚀 Get Started Now

### 👨‍💻 For Developers

**Quickstart with HCP:**
```bash
# 1. Install HCP Toolkit
git clone https://github.com/haletheia/hcp.git
cd hcp && npm install -g

# 2. Initialize a project
hcp init --template=minimal

# 3. Use structured context
hcp verify  # Validate your .procontext/
```

**Quickstart with LiiADA:**
```bash
# 1. Install LiiADA Core
pip install liiada-core

# 2. Configure your first agent
from liiada import Agent, LLM

agent = Agent(
    llm=LLM.ollama(model="llama3"),
    memory="episodic",
    traceable=True
)

# 3. Generate with traceability
response = agent.generate("How to optimize this code?")
print(response.audit_log)  # View complete traceability
```

**Resources:**
- 📚 [Complete Documentation](https://haletheia.github.io/docs)
- 💬 [Discord Community](https://discord.gg/haletheia)
- 📺 [YouTube Tutorials](https://youtube.com/@haletheia)

### 🏢 For CISOs and CTOs

Need to comply with the EU AI Act? Looking for enterprise AI without black boxes?

- 📅 **[Schedule a demo](https://haletheia.github.io/demo)**
- 📋 **[Join the Enterprise Waitlist](https://haletheia.github.io/waitlist)**
- 📧 **[Direct contact](mailto:enterprise@haletheia.ai)**

---

## 🌐 Additional Resources

### 📖 Technical Documentation
- [HCP Whitepaper](https://github.com/haletheia/hcp/blob/main/WHITEPAPER.md)
- [LiiADA Architecture Docs](https://github.com/haletheia/liiada-core/tree/main/docs)
- [MEIA Platform (52+ documents)](https://github.com/haletheia/meia)

### 🎓 Learning
- [Technical Blog (drhidden.github.io)](https://drhidden.github.io)
- [Case Studies](https://haletheia.github.io/case-studies)
- [Webinars and Workshops](https://haletheia.github.io/events)

### 🤝 Community
- [Contributing to HALETHEIA](https://github.com/haletheia/.github/blob/main/CONTRIBUTING.md)
- [Code of Conduct](https://github.com/haletheia/.github/blob/main/CODE_OF_CONDUCT.md)
- [Roadmap 2026-2027](https://haletheia.github.io/roadmap)

---

## 📜 Licenses and Philosophy

- **Open Source (Legos):** AGPL-3.0 / MIT depending on project
- **Enterprise (Castle):** Commercial license with support

**Philosophy:**
> *"Technology should serve people, not replace them. AI agents should amplify human intelligence, not obscure it. Ethics is not a compliance checkbox, it is the base architecture."*

---

<div align="center">

### 🌟 Join the Movement

**We're building the future of responsible AI. Join us.**

[![GitHub](https://img.shields.io/badge/GitHub-HALETHEIA-181717?style=social&logo=github)](https://github.com/haletheia)
[![Follow @haletheia](https://img.shields.io/twitter/follow/haletheia?style=social)](https://twitter.com/haletheia)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-HALETHEIA-0077B5?style=flat&logo=linkedin)](https://linkedin.com/company/haletheia)

---

**HALETHEIA AI Lab**  
*Uncover truth. Maintain control.*

🌐 [haletheia.github.io](https://haletheia.github.io) | 📧 [hello@haletheia.ai](mailto:hello@haletheia.ai)

</div>
