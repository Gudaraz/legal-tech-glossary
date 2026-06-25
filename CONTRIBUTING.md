# Contributing to Legal Tech Glossary

First off, thank you for considering contributing! This glossary grows through the collective knowledge of lawyers, engineers, legal ops professionals, and legal tech enthusiasts.

**You don't need to know Git to contribute.** Seriously.

## 🚪 Choose Your Path

| Your Profile | Best Way to Contribute | Time Required |
|--------------|------------------------|---------------|
| 🎓 Lawyer / Legal Professional | [Path A: No Git Required](#-path-a-no-git-required) | 10 minutes |
| 💻 Engineer / Developer | [Path B: Git Workflow](#-path-b-git-workflow) | 15-30 minutes |
| 🏢 Legal Ops / Vendor | [Path A or C](#-path-c-suggest-a-term-without-writing-it) | 5 minutes |

---

## 🟢 Path A: No Git Required

Perfect for lawyers, legal professionals, and anyone who prefers not to touch the command line.

### Option 1: Send me an email

Just email me at **rafael.montaner@gmail.com** with:
- The term you want to add or correct
- Your explanation (in your own words, plain language is perfect)
- A real-world example if you have one

I'll format it and add it to the glossary, crediting you.

### Option 2: Connect on LinkedIn

Send me a message on [LinkedIn](https://www.linkedin.com/in/rafaelmontaner) with your contribution. Same process as email.

### Option 3: Open a simple issue

1. Go to [Issues](https://github.com/gudaraz/legal-tech-glossary/issues)
2. Click "New Issue"
3. Use the "Term Request" template
4. Fill in what you know — don't worry about formatting

That's it. I'll take care of the rest.

**This is the path most lawyers take.** And that's totally fine. The goal is to get your knowledge into the glossary, not to make you learn Git.

---

## 🔵 Path B: Git Workflow

For engineers, developers, and anyone comfortable with GitHub.

### Adding a New Term

1. **Fork the repository** (click "Fork" at the top right)
2. **Clone your fork** locally:
   ```bash
   git clone git@github.com:YOUR-USERNAME/legal-tech-glossary.git
   cd legal-tech-glossary
   ```
3. **Create a branch** for your contribution:
   ```bash
   git checkout -b add/term-name
   ```
4. **Copy the template** from `templates/term-template.md`
5. **Fill it out** following the style guide below
6. **Add it** to the appropriate file in `categories/`
7. **Update the table of contents** in that category file
8. **Commit and push**:
   ```bash
   git add .
   git commit -m "Add term: [TERM NAME]"
   git push origin add/term-name
   ```
9. **Open a Pull Request** against `main`

### Improving an Existing Term

Same process, but edit the existing file instead of creating a new one. Use a commit message like:
```bash
git commit -m "Improve definition: [TERM NAME]"
```

### Branch Naming Convention

- `add/term-name` — Adding a new term
- `fix/term-name` — Correcting an existing term
- `improve/term-name` — Enhancing a definition
- `docs/...` — Documentation changes
- `feature/...` — New features (search, translations, etc.)

---

## 🟡 Path C: Suggest a Term Without Writing It

Don't have time to write a full definition? Just suggest it:

1. Go to [Issues](https://github.com/gudaraz/legal-tech-glossary/issues)
2. Click "New Issue" → "Term Request"
3. Tell us:
   - What's the term?
   - Why is it important in legal tech?
   - Any context or use case you're curious about?

Someone else (or me) will write the full definition. You'll be credited as the requester.

---

## 📝 Style Guide

### Tone

- **Conversational but professional** — Like explaining to a smart colleague over coffee
- **Jargon-free in the "Plain English" section** — Assume no prior knowledge
- **Specific in the "For Lawyers" and "For Engineers" sections** — Use domain-appropriate language
- **Concrete in examples** — Real scenarios, real outcomes (anonymized if needed)

### Structure (for full term definitions)

Every term should have:
- ✅ Plain English explanation (2-3 sentences max)
- ✅ "For Lawyers" section (why they should care, what questions to ask)
- ✅ "For Engineers" section (technical considerations, implementation notes)
- ✅ Real-world use case (specific, not generic)
- ✅ Related terms (with links)

Optional but encouraged:
- Common misconceptions
- Further reading links
- Diagrams or visual aids

### Formatting

- Use **Markdown** for all content
- Use **headers** (`##`, `###`) for structure
- Use **bold** for emphasis, *italic* for terms
- Use **tables** for comparisons
- Keep paragraphs **short** (3-4 sentences max)

### Examples

❌ **Bad:** "RAG is a technique used in AI."

✅ **Good:** "RAG lets an AI look up relevant documents before answering, instead of relying only on what it 'remembers' from training."

❌ **Bad:** "Lawyers should understand RAG."

✅ **Good:** "When your engineering team says 'we need to build a RAG pipeline,' you should ask: What documents are we retrieving from? How do we ensure the retrieved context is relevant? What's our fallback if retrieval fails?"

---

## 🔍 Review Process

1. **Submit your contribution** (email, issue, or PR)
2. **Human review** — I'll review within 3-5 days
3. **Feedback** — I may suggest changes (collaborative, not critical!)
4. **Merge** — Once approved, it goes live
5. **Credit** — You'll be listed as a contributor

---

## 💡 Tips for Great Contributions

- **Start small** — Improve one term before tackling a new one
- **Use real examples** — Generic examples are forgettable
- **Link to related terms** — Help readers build mental models
- **Cite your sources** — If you're making a technical claim, link to a reference
- **Ask for help** — If you're unsure, just reach out

---

## 🤝 Code of Conduct

We're committed to a welcoming and inclusive experience for everyone. By participating, you agree to:

- Use welcoming and inclusive language
- Be respectful of differing viewpoints and experiences
- Gracefully accept constructive criticism
- Focus on what is best for the community
- Show empathy towards other community members

---

## ❓ Questions?

Not sure how to contribute? Just reach out:

- 📧 **Email:** rafael.montaner@gmail.com
- 💼 **LinkedIn:** [rafaelmontaner](https://www.linkedin.com/in/rafaelmontaner)
- 🐙 **GitHub:** [@gudaraz](https://github.com/gudaraz)

---

**Thank you for helping make legal tech more accessible!** 🙏

*P.S. If you're a lawyer reading this and thinking "I don't know Git" — that's exactly why Path A exists. Your knowledge is valuable regardless of your technical skills.*
