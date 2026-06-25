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
║  v1.2.0                                                              ║
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
║    "structure": "3 learning levels + code solutions",                ║
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

**[🚀 Start Here](#-start-here)** · **[📚 Browse Content](#-learning-paths)** · **[🤝 Contribute](./CONTRIBUTING.md)** · **[💡 Request a Topic](https://github.com/gudaraz/legal-tech-glossary/issues/new)** · **[⭐ Star](https://github.com/gudaraz/legal-tech-glossary)**

</div>

---

## 🚀 START HERE

```bash
$ ./start-here.sh
```

<div align="center">

### 👉 New to Legal Tech? Start with [01-foundations/](./01-foundations/)

**This is not a traditional glossary.** It's a structured learning path that takes you from "what is legal tech?" to "how do I build intelligent legal systems?"

</div>

### 🎯 Your Starting Point Depends on Who You Are

| If you are... | Start here | Why |
|---------------|-----------|-----|
| 🎓 **Lawyer / Legal Professional** | [01-foundations/glossary.md](./01-foundations/glossary.md) | Understand the landscape, vendors, and evolution of legal tech |
| 💻 **Engineer / Developer** | [01-foundations/roles.md](./01-foundations/roles.md) | Understand the roles, then jump to [03-technologies/](./03-technologies/) |
| 📊 **Legal Ops Professional** | [02-process-design/](./02-process-design/) | Skip foundations, go straight to workflow design |
| 🤔 **Just Curious** | [01-foundations/glossary.md](./01-foundations/glossary.md) | The narrative journey through legal tech evolution |

**The recommended path for everyone:**

```
01-foundations/ → 02-process-design/ → 03-technologies/
   (What?)           (How?)              (With what?)
```

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

## 🗺️ Current Structure

```bash
$ tree -L 2
```

```mermaid
flowchart TD
    ROOT["📚 legal-tech-glossary/<br/><i>The bridge between law and tech</i>"]
    
    subgraph Foundations["🟢 01-foundations/ — START HERE"]
        direction TB
        F1["📖 glossary.md<br/><i>The narrative journey</i>"]
        F2["👥 roles.md<br/><i>Real vs inflated titles</i>"]
        F3["📄 what-is-legal-tech.md<br/><i>Clear definition</i>"]
    end
    
    subgraph Process["🟡 02-process-design/ — COMING SOON"]
        direction TB
        P1["📥 intake.md"]
        P2["🔀 triage.md"]
        P3["🧠 decision-engine.md"]
        P4["⚖️ build-vs-buy.md"]
        P5["⚙️ workflow-optimization.md"]
    end
    
    subgraph Tech["🔵 03-technologies/ — IN PROGRESS"]
        direction TB
        T1["🤖 ai-and-llms.md"]
        T2["🧠 rag-and-knowledge.md"]
        T3["📄 clm-and-contracts.md"]
        T4["⚙️ automation-and-workflow.md"]
        T5["🛡️ compliance-and-governance.md"]
        T6["📊 legal-operations.md"]
    end
    
    subgraph Support["📦 Support Files"]
        direction TB
        S1["📋 CONTRIBUTING.md"]
        S2["📜 LICENSE"]
        S3["🎨 templates/"]
    end
    
    ROOT --> Foundations
    ROOT --> Process
    ROOT --> Tech
    ROOT --> Support

    style ROOT fill:#0a0e1a,stroke:#3b82f6,color:#fff,stroke-width:3px
    style Foundations fill:#22c55e,stroke:#16a34a,color:#fff
    style Process fill:#eab308,stroke:#ca8a04,color:#fff
    style Tech fill:#3b82f6,stroke:#1e3a8a,color:#fff
    style Support fill:#6b7280,stroke:#4b5563,color:#fff
    style F1 fill:#16a34a,stroke:#15803d,color:#fff
    style F2 fill:#16a34a,stroke:#15803d,color:#fff
    style F3 fill:#16a34a,stroke:#15803d,color:#fff
```

**Legend:**
- 🟢 **Green** = Available now (start here)
- 🟡 **Yellow** = Coming soon
- 🔵 **Blue** = In progress
- ⚪ **Gray** = Support files

---

## 🔮 What This Repo Will Become

```bash
$ cat roadmap.md
```

This is not just a glossary. It's evolving into a **complete resource hub** for legal tech professionals.

```mermaid
flowchart TD
    NOW["🎯 CURRENT STATE<br/><b>Conceptual Foundation</b><br/>• Narrative documents<br/>• Term definitions<br/>• Role clarifications"]
    
    NEXT["🚀 NEXT PHASE<br/><b>Process Design</b><br/>• Intake-to-archive frameworks<br/>• BPMN templates<br/>• Decision engine patterns"]
    
    CODE["💻 CODE PHASE<br/><b>Working Solutions</b><br/>• Python/Django POCs<br/>• RAG implementations<br/>• Document automation scripts"]
    
    TOOLS["🛠️ TOOLS PHASE<br/><b>Reusable Assets</b><br/>• Legal tech starter kits<br/>• GDPR compliance checkers<br/>• Workflow generators"]
    
    COMMUNITY["🌍 COMMUNITY PHASE<br/><b>Collaborative Platform</b><br/>• Case studies from contributors<br/>• Multilingual support<br/>• Vendor-neutral reviews"]
    
    NOW --> NEXT --> CODE --> TOOLS --> COMMUNITY

    style NOW fill:#22c55e,stroke:#16a34a,color:#fff,stroke-width:3px
    style NEXT fill:#eab308,stroke:#ca8a04,color:#fff
    style CODE fill:#3b82f6,stroke:#1e3a8a,color:#fff
    style TOOLS fill:#8b5cf6,stroke:#7c3aed,color:#fff
    style COMMUNITY fill:#ec4899,stroke:#db2777,color:#fff
```

### What's Coming Next

| Phase | What You'll Find | Timeline |
|-------|------------------|----------|
| 🟢 **Now** | Conceptual foundations, role definitions, narrative glossary | ✅ Live |
| 🟡 **Next** | Process design guides, intake frameworks, BPMN templates | 2-4 weeks |
| 🔵 **Code** | Python/Django POCs, RAG implementations, automation scripts | 1-2 months |
| 🟣 **Tools** | Reusable starter kits, compliance checkers, workflow generators | 3-4 months |
| 🩷 **Community** | Case studies, multilingual support, vendor-neutral reviews | Ongoing |

---

## 📚 Learning Paths

```bash
$ ./learning-paths --help
```

### 🟢 Level 1: Foundations (START HERE)

**Goal:** Understand what legal tech really is, who the real players are, and the basic vocabulary.

| 📖 Topic | 📝 What You'll Learn | ⏱️ Time | Status |
|----------|----------------------|---------|--------|
| [**The Legal Tech Landscape**](./01-foundations/glossary.md) | The narrative journey: vendors → legal ops → automation → AI → regulation | 25 min | ✅ Available |
| [**Roles in Legal Tech**](./01-foundations/roles.md) | Legal Engineer vs Legal AI Engineer vs inflated titles | 15 min | 🚧 Coming soon |
| [**What is Legal Tech?**](./01-foundations/what-is-legal-tech.md) | Clear definition, scope, and misconceptions | 10 min | 🚧 Coming soon |

**Who should start here?**
- Lawyers exploring legal tech for the first time
- Engineers joining a legal tech team
- Anyone confused by the buzzwords

---

### 🟡 Level 2: Process Design

**Goal:** Learn how to design, optimize, and automate legal workflows from intake to archive.

| 📖 Topic | 📝 What You'll Learn | ⏱️ Time | Status |
|----------|----------------------|---------|--------|
| [**Intake & Matter Creation**](./02-process-design/intake.md) | How to capture legal requests effectively | 20 min | 🚧 Coming soon |
| [**Triage & Prioritization**](./02-process-design/triage.md) | Classifying and routing matters efficiently | 15 min | 🚧 Coming soon |
| [**Decision Engines**](./02-process-design/decision-engine.md) | Building IF/THEN logic for legal workflows | 25 min | 🚧 Coming soon |
| [**Build vs Buy**](./02-process-design/build-vs-buy.md) | When to build custom vs buy off-the-shelf | 20 min | 🚧 Coming soon |
| [**Workflow Optimization**](./02-process-design/workflow-optimization.md) | Identifying bottlenecks and improving efficiency | 30 min | 🚧 Coming soon |

**Who should focus here?**
- Legal Ops professionals designing workflows
- Legal Engineers building automation
- Law firm managers optimizing operations

---

### 🔵 Level 3: Technologies

**Goal:** Deep dive into the specific tools, frameworks, and technologies powering legal tech.

| 📖 Category | 🔧 Technologies Covered | 📊 Terms | Status |
|-------------|-------------------------|----------|--------|
| 🤖 [**AI & LLMs**](./03-technologies/ai-and-llms.md) | Large Language Models, prompt engineering, fine-tuning | 12 | 🚧 Coming soon |
| 🧠 [**RAG & Knowledge**](./03-technologies/rag-and-knowledge.md) | Retrieval-Augmented Generation, embeddings, vector DBs | 10 | 🚧 Coming soon |
| 📄 [**CLM & Contracts**](./03-technologies/clm-and-contracts.md) | Contract Lifecycle Management, e-signature, clauses | 9 | 🚧 Coming soon |
| ⚙️ [**Automation & Workflow**](./03-technologies/automation-and-workflow.md) | BPMN, RPA, low-code, process mining | 11 | 🚧 Coming soon |
| 🛡️ [**Compliance & Governance**](./03-technologies/compliance-and-governance.md) | GDPR, EU AI Act, data sovereignty, ethics | 8 | 🚧 Coming soon |
| 📊 [**Legal Operations**](./03-technologies/legal-operations.md) | LPM, matter management, spend analytics | 7 | 🚧 Coming soon |

**Total: 57+ terms planned** 📈

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

📖 **Full explanation:** [01-foundations/glossary.md - Chapter 5](./01-foundations/glossary.md)

---

### ⚙️ BPMN (Business Process Model and Notation)

> A standardized way to draw **flowcharts that show how a process works**, step by step.

| Perspective | Explanation |
|-------------|-------------|
| ⚖️ **For Lawyers** | How you map "what happens when a client signs" so legal, tech, and business all understand. |
| 🛠️ **For Engineers** | The blueprint for automation. No BPMN = no specs = building in the dark. |
| 💼 **Real Use** | Succession process: receive case → verify docs → identify heirs → draft deed → file. |

📖 **Full explanation:** [03-technologies/automation-and-workflow.md](./03-technologies/automation-and-workflow.md) *(coming soon)*

---

### 🛡️ EU AI Act Risk Classification

> The EU's way of sorting AI systems by **how dangerous they could be**, from "no risk" to "unacceptable."

| Perspective | Explanation |
|-------------|-------------|
| ⚖️ **For Lawyers** | Determines what compliance hoops your legal tech tool must jump through. |
| 🛠️ **For Engineers** | Regulatory constraint that shapes your entire architecture. |
| 💼 **Real Use** | Contract tool recommending legal actions = high-risk. Case law summarizer = limited risk. |

📖 **Full explanation:** [01-foundations/glossary.md - Chapter 5](./01-foundations/glossary.md)

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

## 🔄 This Is a Living Document

```bash
$ git log --oneline
```

The legal tech landscape evolves fast. New tools emerge, regulations change, and best practices shift. This resource evolves with it.

**What "living document" means:**
- ✅ Content is updated regularly as the field evolves
- ✅ Community contributions are welcomed and reviewed
- ✅ Mistakes are corrected quickly
- ✅ New topics are added based on demand
- ✅ Code examples are tested and maintained

**How to stay updated:**
- ⭐ **Star this repo** to get notifications
- 👀 **Watch** for all changes
- 💼 **Follow me on LinkedIn** for announcements

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
