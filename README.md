# AI Control Safety Package  

> **A design framework for deciding where AI must NOT be used.**

🚧 **Currently under development (design framework stage).**  
This package is **not a deployable product** and **not a certification scheme**.  
It is a **design- and governance-level framework** for making *defensible decisions*
about AI / LLM usage in control systems.

---

## 🔗 Links

| Language | GitHub Pages 🌐 | GitHub 💻 |
|----------|----------------|-----------|
| 🇺🇸 English | [![GitHub Pages EN](https://img.shields.io/badge/GitHub%20Pages-English-brightgreen?logo=github)](https://samizo-aitl.github.io/ai-control-safety-package/) | [![GitHub Repo EN](https://img.shields.io/badge/GitHub-English-blue?logo=github)](https://github.com/Samizo-AITL/ai-control-safety-package/tree/main) |

---

## What problem this package addresses

AI and LLMs are increasingly pushed into control systems.  
In many projects, the real question is not “How can we use AI?” but:

> **Where must AI be limited, isolated, or stopped?**

This package exists to answer that question **clearly, structurally, and defensibly**.

---

## Core philosophy

- AI is **not trusted by default**
- Safety comes from **architecture, not intelligence**
- Real-time control must remain **deterministic**
- Failure handling must be **designed, not improvised**

We focus on **risk judgment, safety boundaries, and recovery**  
—not performance optimization.

---

## Package Structure (How they work together)

The three packages form a **single safety story**:

1. **Risk Review** → Should AI be allowed at all?  
2. **Safety Envelope** → If allowed, where must AI be strictly constrained?  
3. **Recovery Control** → When things go wrong, how do we return safely?

---

## Packages

### 1. AI Control Risk Review
Architectural **Go / Conditional Go / No-Go** judgment  
for AI / LLM-based control concepts.

- AI placement outside real-time loops
- Explicit stop conditions and fallback paths
- Clear responsibility and failure ownership

🔗 **Open:**  
[AI Control Risk Review](https://samizo-aitl.github.io/ai-control-safety-package/packages/risk-review.html)

---

### 2. Safety Envelope Design
Explicit definition and enforcement of  
**operational boundaries AI must never violate**.

- Allowed operational envelopes
- Pre-violation detection
- FSM-based supervisory enforcement

🔗 **Open:**  
[Safety Envelope Design](https://samizo-aitl.github.io/ai-control-safety-package/packages/safety-envelope.html)

---

### 3. Recovery Control Design
Deterministic recovery design after  
disturbances, degradation, or abnormal behavior.

- Recovery triggers and modes
- Safe fallback structures
- Controlled re-entry with accountability

🔗 **Open:**  
[Recovery Control Design](https://samizo-aitl.github.io/ai-control-safety-package/packages/recovery-control.html)

---

## Engagement & Fees (Guideline)

This package is provided as a **limited-scope design review and consulting service**  
focused on **architecture, responsibility, and safety logic**.

### Service Menu

- **AI Control Risk Review**  
  from **JPY 50,000 – 100,000**  

- **Safety Envelope Design**  
  from **JPY 100,000 – 300,000**  

- **Recovery Control Design**  
  from **JPY 150,000 – 400,000**  

Fees depend on system complexity and documentation quality.

---

## Where to start

If you are unsure where to begin,  
**[AI Control Risk Review](https://samizo-aitl.github.io/ai-control-safety-package/packages/risk-review.html)** is recommended as the first step.

---

## Contact

📧 [shinichi.samizo2@gmail.com](mailto:shinichi.samizo2@gmail.com)  
🌐 [samizo-aitl.github.io](https://samizo-aitl.github.io/)

---

## License

Provided for **design reference and discussion only**.  
Commercial use or product implementation requires prior written agreement.  
This is **not** an open-source software license.

---

## Discussions

For questions and architectural discussion:  
💬 **[GitHub Discussions](https://github.com/Samizo-AITL/ai-control-safety-package/discussions)**
