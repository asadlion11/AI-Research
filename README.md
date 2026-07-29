# AI Research

Notes and materials for a self-study path from software development to AI research.

**Goal:** become an AI Researcher — able to read, implement, and publish research.

**The path:** ML Engineer → Research Engineer → AI Researcher

## Roadmap overview

Full details: [`Roadmap/AI_Research_Roadmap.pdf`](Roadmap/AI_Research_Roadmap.pdf)

| Phase | Focus | Duration |
| --- | --- | --- |
| 1 · Engineer Foundations | Math → Python data stack → Machine Learning → Deep Learning → Projects. Ends job-ready as an ML Engineer. | ≈ 9–12 months |
| 2 · Research Depth | Rigorous math → Transformers & LLMs → reading and reproducing research papers. | ≈ 6–9 months |
| 3 · Research Practice | Original experiments → writing & publishing → research community contributions. | Ongoing |

### The four golden rules

1. **Strict order, no parallel learning.** Start a step, finish it completely, then start the next.
2. **One concept = one resource.** Never two courses for the same topic.
3. A video counts as done only when the **mentor test** on it is passed. Testing is the course.
4. **Optional:** publish what you build to GitHub + portfolio — recommended when job hunting.

### Phase 1 · Engineer Foundations

Five stages, nine steps, in order.

| Stage | What you learn | Where |
| --- | --- | --- |
| 1 · Math | Linear Algebra, Calculus, Multivariable basics, Probability & Statistics | 3Blue1Brown + StatQuest |
| 2 · Data Analysis | Python data stack: NumPy, Pandas, Matplotlib, EDA | freeCodeCamp |
| 3 · Machine Learning | Supervised, unsupervised & reinforcement learning | Coursera — Andrew Ng |
| 4 · Deep Learning | Neural networks, CNNs, sequence models + GPT from scratch | Coursera + Karpathy |
| 5 · Projects | Three portfolio builds: House Price Prediction → Movie Recommender → Mini-GPT | GitHub |

Framework rule: courses may use TensorFlow — that's fine. The personal framework is **PyTorch**, the language of research.

### Phase 2 · Research Depth

1. Linear Algebra rigor pass — MIT 18.06SC (Strang); the problem sets are the point
2. Math of ML papers — *Mathematics for Machine Learning* (free book)
3. NLP & Transformers — Stanford CS224n
4. Hands-on LLMs — Hugging Face LLM Course
5. **Reproduce 3–5 papers** — read → reimplement in PyTorch → match a reported number → write up what didn't match

First five papers, in order: Attention Is All You Need → GPT-2 → BERT → Adam → LoRA.

### Phase 3 · Research Practice

The research loop: reproduce → ablate → question → small original experiment → write it up → share → repeat.

Focus area: low-resource NLP (Somali) and health-domain data — an active frontier with communities such as Masakhane and EleutherAI that publish cited work without a PhD gate.

## Repository contents

```
Roadmap/     the roadmap itself (PDF)
Lessons/     notes taken while working through each resource
```

### Lessons

- **Linear Algebra — 3Blue1Brown, *Essence of Linear Algebra*** — chapter notes for Ch01–Ch09 and Ch13–Ch16, plus a combined notebook. Chapters 10–12 (cross products, Cramer's rule) are skipped per the roadmap.

## Milestone checklist

- [ ] Essence of Linear Algebra finished — all mentor tests passed *(P1)*
- [ ] freeCodeCamp Data Analysis certification earned *(P1)*
- [ ] ML + Deep Learning Specializations completed *(P1)*
- [ ] Zero to Hero done — mini-GPT trained *(P1)*
- [ ] 3 projects completed *(P1)*
- [ ] 18.06SC problem sets completed *(P2)*
- [ ] First paper reproduction published *(P2)*
- [ ] First original experiment written up and shared *(P3)*
- [ ] First community contribution — Masakhane or open source *(P3)*
