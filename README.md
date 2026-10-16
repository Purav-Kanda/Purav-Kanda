# 👋 Hi, I'm Purav

![Typing SVG](https://readme-typing-svg.herokuapp.com?color=58A6FF&center=true&vCenter=true&lines=Computer+Science+%26+Economics+Student;Full-Stack+%2F+AI+Systems+Developer;Building+Real%2C+Shipped+Projects)

💻 3rd-year Computer Science & Economics (Honours Co-op) student at McMaster University
🤖 Interested in AI agent systems, backend infrastructure, and full-stack development
🛠 Open-source contributor on [Drasil](https://github.com/JacquesCarette/Drasil), a McMaster research project
🚀 I build things that actually ship — not just prototypes

---

## 🔥 Featured Projects

### 🔒 ACEL — Agent Contract Enforcement Layer
Open-source Python library (PyPI: `acel-core`, MIT) that blocks AI agent tool calls violating declared rules (ordering, spend caps, required steps) before they execute. Rules run as deterministic state machines, with signed tamper-evident audit logs and an MCP proxy. 357 automated tests and 100% precision/recall on a hand-labeled 67-trace benchmark.
📁 [`Acel`](https://github.com/Purav-Kanda/Acel)

### 📐 MathScan — Handwritten Math to LaTeX
Full-stack OCR pipeline (Next.js frontend on Vercel, FastAPI backend on Modal) that converts handwritten notes into editable LaTeX in real time, streaming results via Server-Sent Events. Dual-OCR pipeline (Pix2Text plus a PaddleOCR second opinion on every page, higher confidence wins) with an LLM correction pass, benchmarked at **71.4% mean character accuracy** on real photographed handwritten notes. Full CI test suite on every push.
📁 [`MathScan`](https://github.com/Purav-Kanda/MathScan) · **Live:** math-scan-lake.vercel.app

### 🛡️ AgentSentinel — AI Agent Observability
Real-time observability API detecting AI agent hallucinations, tool-call loops, and reasoning drift via a per-span composite anomaly scorer combining linguistic, latency, and retry-pattern signals. Three-tier automated remediation (WARN / PAUSE-with-human-gate / ABORT), backed by 31 unit tests. Submitted to the Splunk Agentic Ops Hackathon ($20K prize pool, 1,300+ participants).
📁 `AgentSentinel` · 🎥 [Demo](https://youtu.be/zLXxlxDPzIg)

### 🩺 DysphagiaSense — AI Swallow Risk Detection
Full-stack AI pipeline built with a 4-person team — React/TypeScript frontend, FastAPI backend, and a rule-based acoustic risk scorer using MFCC, spectral centroid, and zero-crossing rate features. I owned the risk classification engine and acoustic feature research. **Placed 3rd of 20+ teams** (Health & Aging track) at MacHacks 2026.
📁 `DysphagiaSense`

### 🧩 Drasil — Open-Source Research Contributions
Merged 18 pull requests into a multi-package Haskell codebase spanning printer backends, code generators (C#, Python, Java), and requirements-engineering domain logic — used across 10+ downstream case studies. McMaster research project supervised by Dr. Jacques Carette and Dr. Spencer Smith.
📁 [`Drasil`](https://github.com/JacquesCarette/Drasil)

---

## 🛠 Tech Stack

**Languages**
Python • TypeScript • JavaScript • Java • C • SQL • Go • Haskell • HTML/CSS

**Frameworks & Libraries**
FastAPI • React • Next.js • Node.js • REST APIs • NumPy • Pandas • Librosa

**Cloud & DevOps**
AWS • Docker • Modal (serverless) • CI/CD (GitHub Actions) • PostgreSQL • MySQL • Git • Linux

**Concepts**
OOP • Distributed Systems • Unit Testing • Agile • API Design

---

## 🧩 What I Focus On

- Shipping full-stack systems end-to-end — idea to deployment, not just demos
- Debugging real production issues (deployment failures, root-cause fixes) rather than working around them
- AI/agent infrastructure: observability, evaluation, and reliability
- Writing tested, maintainable code with real CI pipelines

---

## 📫 Contact

- 📧 puravkanda@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/purav-kanda-971357296/)
- 🌐 [Portfolio](https://puravkanda13.42web.io/)
