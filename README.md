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
║  v1.0.0                                                              ║
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
║    "terms": "57+ and growing",                                       ║
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
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-22c55e?style=for-the-badge&logo=github)](http://makeapullrequest.com)
[![Contributions](https://img.shields.io/badge/Contributions-Welcome-f97316?style=for-the-badge)](./CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/gudaraz/legal-tech-glossary?style=for-the-badge&logo=star&color=eab308)](https://github.com/gudaraz/legal-tech-glossary/stargazers)

**[📖 Browse Glossary](#-categories)** · **[🤝 Contribute](./CONTRIBUTING.md)** · **[💡 Request a Term](https://github.com/gudaraz/legal-tech-glossary/issues/new)** · **[⭐ Star](https://github.com/gudaraz/legal-tech-glossary)**

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

---

## ✨ What Makes This Different

```bash
$ diff other-glossaries.md this-glossary.md
```

| Other Glossaries | This Glossary |
|-----------------|---------------|
| 📚 Academic definitions | 🎯 Plain language first |
| 👤 One perspective | ⚖️🛠️ Legal AND engineering perspectives |
| 📖 Theory only | 💼 Real-world use cases |
| 🤷 Isolated terms | 🔗 Connected mental models |
| 📝 Static | 🌱 Living, community-driven |
| 🎓 One type of author | 🤝 Written by attorney + developer |

---

## 📂 Categories

```bash
$ ls -la categories/
```

| # | Category | Terms | Description |
|---|----------|:-----:|-------------|
| 01 | 🤖 [**AI & LLMs**](./categories/ai-and-llms.md) | 12 | Large Language Models, prompt engineering, hallucinations |
| 02 | 🧠 [**RAG & Knowledge**](./categories/rag-and-knowledge.md) | 10 | Retrieval-Augmented Generation, embeddings, vector DBs |
| 03 | 📄 [**CLM & Contracts**](./categories/clm-and-contracts.md) | 9 | Contract Lifecycle Management, e-signature, clauses |
| 04 | ⚙️ [**Automation & Workflow**](./categories/automation-and-workflow.md) | 11 | BPMN, RPA, low-code, process mining |
| 05 | 🛡️ [**Compliance & Governance**](./categories/compliance-and-governance.md) | 8 | GDPR, EU AI Act, data sovereignty |
| 06 | 📊 [**Legal Operations**](./categories/legal-operations.md) | 7 | LPM, matter management, spend analytics |

---

## 🔥 Featured Terms

```bash
$ cat featured-terms.md
```

### 🧠 RAG (Retrieval-Augmented Generation)

> Instead of relying only on what an AI "remembers," RAG lets it **look up relevant documents first**, then generate answers based on what it finds.

| Perspective | Explanation |
|-------------|-------------|
| ⚖️ **For Lawyers** | Your AI reads your actual contract database before answering—instead of making things up. |
| 🛠️ **For Engineers** | Retrieve chunks from a vector DB → inject into LLM prompt → generate grounded response. |
| 💼 **Real Use** | Compliance team asks about data transfer policy → RAG retrieves GDPR docs → LLM answers with citations. |

### ⚙️ BPMN (Business Process Model and Notation)

> A standardized way to draw **flowcharts that show how a process works**, step by step.

| Perspective | Explanation |
|-------------|-------------|
| ⚖️ **For Lawyers** | How you map "what happens when a client signs" so legal, tech, and business all understand. |
| 🛠️ **For Engineers** | The blueprint for automation. No BPMN = no specs = building in the dark. |
| 💼 **Real Use** | Succession process: receive case → verify docs → identify heirs → draft deed → file. |

### 🛡️ EU AI Act Risk Classification

> The EU's way of sorting AI systems by **how dangerous they could be**, from "no risk" to "unacceptable."

| Perspective | Explanation |
|-------------|-------------|
| ⚖️ **For Lawyers** | Determines what compliance hoops your legal tech tool must jump through. |
| 🛠️ **For Engineers** | Regulatory constraint that shapes your entire architecture. |
| 💼 **Real Use** | Contract tool recommending legal actions = high-risk. Case law summarizer = limited risk. |

---

## 🗺️ Learning Paths

```bash
$ ./learning-paths --help
```

### 🛤️ "I need to understand AI in legal tech"
```
LLM → Prompt Engineering → Hallucination → RAG → Embeddings → Vector DB
```
⏱️ ~2 hours · 🟢 Beginner

### 🛤️ "I need to build compliant legal AI"
```
GDPR → EU AI Act → Privacy-by-Design → Data Sovereignty → Conformity Assessment
```
⏱️ ~3 hours · 🟡 Intermediate

### 🛤️ "I need to automate legal workflows"
```
BPMN → Workflow Automation → RPA → Low-Code → Process Mining
```
⏱️ ~2 hours · 🟢 Beginner

### 🛤️ "I need to manage contracts better"
```
CLM → E-Signature → Clause Library → Contract Analytics → Obligation Management
```
⏱️ ~2 hours · 🟡 Intermediate

---

## 📖 How to Use

```bash
$ man legal-tech-glossary
```

- 🎓 **Lawyers** → Start with [AI & LLMs](./categories/ai-and-llms.md)
- 💻 **Engineers** → Start with [Legal Operations](./categories/legal-operations.md)
- 🏢 **Vendors** → Use for documentation and sales decks
- 🎯 **Legal Ops** → Use for vendor evaluations and RFPs

---

## 🤝 Contributing

```bash
$ git contribute --help
```

This is a living document. See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

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
