<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e1a,50:1e3a8a,100:3b82f6&height=120&section=header" />

</div>

```bash
 ██       ███████  ██████   █████  ██         ████████ ███████  ██████ ██   ██
 ██       ██      ██       ██   ██ ██            ██    ██      ██      ██   ██
 ██       █████   ██ █████ ███████ ██            ██    █████   ██      ███████
 ██       ██      ██    ██ ██   ██ ██            ██    ██      ██      ██   ██
 ███████  ███████  ██████  ██   ██ ███████       ██    ███████  ██████ ██   ██

  ██████   ██       ██████   ██████   █████  ██████  ██    ██
 ██        ██      ██    ██ ██       ██   ██ ██   ██  ██  ██
 ██  ████  ██      ██    ██  ██████  ███████ ██████    ████
 ██    ██  ██      ██    ██       ██ ██   ██ ██   ██    ██
  ██████   ███████  ██████   ██████  ██   ██ ██   ██    ██

╔══════════════════════════════════════════════════════════════════════╗
║  v1.1.0                                                              ║
║  The bridge between legal expertise and technology                   ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║  $ whoami                                                            ║
║  > Rafael Montaner — Attorney + Software Developer                   ║
║                                                                      ║
║  $ cat status.json                                                   ║
║  {                                                                   ║
║    "status": "🟢 Active Development",                                ║
║    "license": "MIT",                                                 ║
║    "structure": "3 learning levels",                                 ║
║    "languages": ["EN", "ES (coming soon)"]                           ║
║  }                                                                   ║
║                                                                      ║
║  $ echo $MISSION                                                     ║
║  > Lawyers hear "RAG" and think it's a rag doll.                     ║
║  > Engineers hear "force majeure" and think it's a French error.     ║
║  > This glossary fixes that.                                         ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝
```

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-3b82f6?style=for-the-badge&logo=open-source-initiative&logoColor=white)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-22c55e?style=for-the-badge&logo=github)](./CONTRIBUTING.md)
[![Contributions](https://img.shields.io/badge/Contributions-Welcome-f97316?style=for-the-badge)](./CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/gudaraz/legal-tech-glossary?style=for-the-badge&logo=star&color=eab308)](https://github.com/gudaraz/legal-tech-glossary/stargazers)

**[📚 Browse Content](#-learning-paths)** · **[🤝 Contribute](./CONTRIBUTING.md)** · **[💡 Request a Topic](https://github.com/gudaraz/legal-tech-glossary/issues/new)** · **[⭐ Star](https://github.com/gudaraz/legal-tech-glossary)**

</div>

---

## 🎯 The Problem

```bash
$ cat problem.txt
```

The gap between legal professionals and engineers isn't just about language—it's about **mental models**.

| ❌ What Happens | 💰 The Cost |
|----------------|-------------|
| Lawyers can't evaluate if a vendor's "AI-powered" tool is useful | Wasted budget |
| Engineers build solutions that violate legal principles | Failed implementations |
| Projects fail because of bad communication, not bad code | Millions lost |
| Legal tech tools that nobody actually uses | Low adoption |

**This resource fixes that.**

---

## 🗺️ How This Is Organized

```bash
$ tree -L 1
```

Unlike typical glossaries that just list terms alphabetically, this is structured as a **learning curriculum** with 3 progressive levels:

```
📂 01-foundations/          ← Start here: What is this field? Who are the real players?
📂 02-process-design/       ← Then: How do you design legal workflows?
📂 03-technologies/         ← Finally: What tools and technologies exist?
```

**Why this structure?**

- **Lawyers new to tech** → Start with foundations, understand the landscape
- **Legal Ops professionals** → Jump to process design, optimize workflows
- **Engineers** → Go straight to technologies, but read foundations first
- **Everyone** → Navigate by your current need and knowledge level

---

## 📚 Learning Paths

```bash
$ ./learning-paths --help
```

### 🟢 Level 1: Foundations

**Goal:** Understand what legal tech really is, who the real players are, and the basic vocabulary.

| 📖 Topic | 📝 What You'll Learn | ⏱️ Time |
|----------|----------------------|---------|
| [**What is Legal Tech?**](./01-foundations/what-is-legal-tech.md) | Clear definition, scope, and misconceptions | 10 min |
| [**Roles in Legal Tech**](./01-foundations/roles.md) | Legal Engineer vs Legal AI Engineer vs inflated titles | 15 min |
| [**Basic Glossary**](./01-foundations/glossary.md) | Essential terms every professional should know | 20 min |

**Who should start here?**
- Lawyers exploring legal tech for the first time
- Engineers joining a legal tech team
- Anyone confused by the buzzwords

---

### 🟡 Level 2: Process Design

**Goal:** Learn how to design, optimize, and automate legal workflows from intake to archive.

| 📖 Topic | 📝 What You'll Learn | ⏱️ Time |
|----------|----------------------|---------|
| [**Intake & Matter Creation**](./02-process-design/intake.md) | How to capture legal requests effectively | 20 min |
| [**Triage & Prioritization**](./02-process-design/triage.md) | Classifying and routing matters efficiently | 15 min |
| [**Decision Engines**](./02-process-design/decision-engine.md) | Building IF/THEN logic for legal workflows | 25 min |
| [**Build vs Buy**](./02-process-design/build-vs-buy.md) | When to build custom vs buy off-the-shelf | 20 min |
| [**Workflow Optimization**](./02-process-design/workflow-optimization.md) | Identifying bottlenecks and improving efficiency | 30 min |

**Who should focus here?**
- Legal Ops professionals designing workflows
- Legal Engineers building automation
- Law firm managers optimizing operations

---

### 🔵 Level 3: Technologies

**Goal:** Deep dive into the specific tools, frameworks, and technologies powering legal tech.

| 📖 Category | 🔧 Technologies Covered | 📊 Terms |
|-------------|-------------------------|----------|
| 🤖 [**AI & LLMs**](./03-technologies/ai-and-llms.md) | Large Language Models, prompt engineering, fine-tuning | 12 |
| 🧠 [**RAG & Knowledge**](./03-technologies/rag-and-knowledge.md) | Retrieval-Augmented Generation, embeddings, vector DBs | 10 |
| 📄 [**CLM & Contracts**](./03-technologies/clm-and-contracts.md) | Contract Lifecycle Management, e-signature, clauses | 9 |
| ⚙️ [**Automation & Workflow**](./03-technologies/automation-and-workflow.md) | BPMN, RPA, low-code, process mining | 11 |
| 🛡️ [**Compliance & Governance**](./03-technologies/compliance-and-governance.md) | GDPR, EU AI Act, data sovereignty, ethics | 8 |
| 📊 [**Legal Operations**](./03-technologies/legal-operations.md) | LPM, matter management, spend analytics | 7 |

**Total: 57+ terms and growing** 📈

**Who should dive deep here?**
- Engineers implementing specific technologies
- Legal Tech vendors evaluating tools
- Anyone needing technical depth on a specific topic

---

## 🔥 Featured Topics

```bash
$ cat featured-topics.md
```

### 🧠 RAG (Retrieval-Augmented Generation)

> Instead of relying only on what an AI "remembers," RAG lets it **look up relevant documents first**, then generate answers based on what it finds.

| Perspective | Explanation |
|-------------|-------------|
| ⚖️ **For Lawyers** | Your AI reads your actual contract database before answering—instead of making things up. |
| 🛠️ **For Engineers** | Retrieve chunks from a vector DB → inject into LLM prompt → generate grounded response. |
| 💼 **Real Use** | Compliance team asks about data transfer policy → RAG retrieves GDPR docs → LLM answers with citations. |

📖 **Full explanation:** [03-technologies/rag-and-knowledge.md](./03-technologies/rag-and-knowledge.md)

---

### ⚙️ BPMN (Business Process Model and Notation)

> A standardized way to draw **flowcharts that show how a process works**, step by step.

| Perspective | Explanation |
|-------------|-------------|
| ⚖️ **For Lawyers** | How you map "what happens when a client signs" so legal, tech, and business all understand. |
| 🛠️ **For Engineers** | The blueprint for automation. No BPMN = no specs = building in the dark. |
| 💼 **Real Use** | Succession process: receive case → verify docs → identify heirs → draft deed → file. |

📖 **Full explanation:** [03-technologies/automation-and-workflow.md](./03-technologies/automation-and-workflow.md)

---

### 🛡️ EU AI Act Risk Classification

> The EU's way of sorting AI systems by **how dangerous they could be**, from "no risk" to "unacceptable."

| Perspective | Explanation |
|-------------|-------------|
| ⚖️ **For Lawyers** | Determines what compliance hoops your legal tech tool must jump through. |
| 🛠️ **For Engineers** | Regulatory constraint that shapes your entire architecture. |
| 💼 **Real Use** | Contract tool recommending legal actions = high-risk. Case law summarizer = limited risk. |

📖 **Full explanation:** [03-technologies/compliance-and-governance.md](./03-technologies/compliance-and-governance.md)

---

## 📰 Related Content

```bash
$ cat blog-posts.md
```

I write about legal tech, AI governance, and the intersection of law and engineering on LinkedIn. Here are key posts that complement this resource:

| 📅 Date | 📝 Title | 🏷️ Topic | 🔗 Link |
|---------|----------|----------|---------|
| Jun 2026 | Why Most Legal AI Projects Fail (And How to Fix Them) | AI Strategy | [Read →](https://www.linkedin.com/in/rafaelmontaner) |
| May 2026 | RAG in Legal Tech: Beyond the Hype | RAG | [Read →](https://www.linkedin.com/in/rafaelmontaner) |
| Apr 2026 | The EU AI Act: What Legal Tech Builders Need to Know | Compliance | [Read →](https://www.linkedin.com/in/rafaelmontaner) |
| Mar 2026 | BPMN for Lawyers: A Practical Guide | Process Design | [Read →](https://www.linkedin.com/in/rafaelmontaner) |
| Feb 2026 | Why I Built This Glossary | Meta | [Read →](https://www.linkedin.com/in/rafaelmontaner) |

**Want more?** Follow me on [LinkedIn](https://www.linkedin.com/in/rafaelmontaner) for weekly insights.

---

## 🤝 Contributing

```bash
$ git contribute --help
```

This is a living resource. The legal tech landscape evolves fast, and we need the community to keep this current.

**You don't need to know Git to contribute.** See [CONTRIBUTING.md](./CONTRIBUTING.md) for:
- 🟢 **Path A:** Email or LinkedIn (no Git required)
- 🔵 **Path B:** Fork, branch, PR (for developers)
- 🟡 **Path C:** Suggest a topic without writing it

**First-time contributors welcome!**

---

## 📬 Stay Connected

```bash
$ cat contact.json
```

```json
{
  "maintainer": "Rafael Montaner",
  "role": "Legal Engineer & Legal Tech Consultant",
  "linkedin": "linkedin.com/in/rafaelmontaner",
  "website": "www.rafaelmontaner.com",
  "email": "rafael.montaner@gmail.com"
}
```

---

## 📄 License

```bash
$ head -1 LICENSE
```

MIT License — Use it, share it, remix it. Just give credit.

---

<div align="center">

```bash
$ echo "Go build something amazing."
```

### ⭐ If this helps you, star the repo!

**Built with ❤️ by [Rafael Montaner](https://www.rafaelmontaner.com)**

```bash
$ exit
logout
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3b82f6,50:1e3a8a,100:0a0e1a&height=80&section=footer" />

</div>
