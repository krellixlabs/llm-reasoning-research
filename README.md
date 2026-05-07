# LLM Reasoning Research

> A curated, annotated research collection on reasoning gaps in large language models.

This repository tracks active research on the cognitive limitations of large language models — the places where current LLMs struggle, why those gaps matter, and what's being done about them.

It is maintained by the team at **[Krellix](https://krellixlabs.com)** as a public resource for developers, researchers, and product teams building with LLMs.

---

## Why this exists

Large language models have advanced rapidly, but several core reasoning capabilities remain unsolved or actively contested. These gaps matter — for builders deciding what to ship, for researchers deciding what to work on, and for users trying to understand what LLMs can and cannot reliably do.

Most of the literature is scattered across arXiv, conference proceedings, and lab blog posts. This repo is an attempt to organize the most important work in one place, with honest annotations about what each paper contributes and what it leaves open.

**This is curation, not original research.** We are practitioners building an AI product. We read this work to understand the landscape we're operating in. This collection is a byproduct of that work, shared publicly because we think it's useful.

---

## What's covered

### Currently in the collection

- **[Temporal Reasoning](./temporal-reasoning/)** — How LLMs handle time, sequence, duration, and temporal context. Why models that can write a sonnet often fail at "what happened before what."

- **[Causal Reasoning](./causal-reasoning/)** — The gap between correlation and causation in LLM outputs. Why current models struggle with cause-and-effect reasoning, and what the research community is doing about it.

### Coming soon

We're expanding this collection over time. Topics on the roadmap:

- Mathematical and logical reasoning
- Planning and multi-step problem solving
- Theory of mind and social reasoning
- World models and physical reasoning
- Counterfactual reasoning
- Long-horizon coherence

If you'd like to suggest a topic or contribute papers to existing sections, see [CONTRIBUTING.md](./CONTRIBUTING.md).

---

## How this collection is organized

Each topic folder contains:

- **`README.md`** — An accessible introduction to the reasoning gap, why it matters, and where the research currently stands
- **`foundational-papers.md`** — The core papers that defined the problem
- **`recent-research.md`** — Recent work (last ~24 months)
- **`benchmarks-and-datasets.md`** — How researchers measure progress on the problem
- **`practical-implications.md`** — What this means for people building with LLMs

Every paper entry follows a consistent format:

```
### [Paper Title]
**Authors** · **Year** · **Venue**
Links · TL;DR · Why it matters · Key insight · Limitations
```

The goal is for each entry to be useful in 60 seconds, with enough signal to decide whether to read the full paper.

---

## How to use this repo

- **If you're a developer building with LLMs** — Start with the `practical-implications.md` file in any topic. It translates research into things you can act on.
- **If you're a researcher** — The `foundational-papers.md` and `recent-research.md` files give you a structured reading path. The benchmarks file points to where evaluation is happening.
- **If you're a product team** — Read the topic READMEs first. They explain the gaps in language that doesn't require an ML background.

---

## Contributing

This repo improves with community input. We welcome:

- Suggestions for papers we've missed
- Corrections to existing annotations
- New topic proposals (see roadmap above)
- Better organization of existing content

See [CONTRIBUTING.md](./CONTRIBUTING.md) for how to suggest changes or open issues.

---

## A note on AI-generated content

Annotations in this repository are written by humans after reading the papers. We do not auto-generate summaries from titles or abstracts. Where we make judgment calls about a paper's contribution or limitations, those are real assessments — and we welcome pushback when we get them wrong.

---

## About Krellix

[Krellix](https://krellixlabs.com) is an AI copilot platform built as a multi-agent system, where AI agents collaborate, share context, and solve problems together. We care about the limits of LLM reasoning because those limits shape what's possible to build.

If you're interested in multi-agent AI workflows for macOS and Windows, [join our beta](https://krellixlabs.com).

---

## License

All content in this repository is released under [Creative Commons Zero (CC0)](./LICENSE) — public domain. Use it freely for research, citation, redistribution, or any other purpose, with no attribution required (though attribution is always appreciated).
