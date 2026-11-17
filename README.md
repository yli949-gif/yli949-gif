# Hi, I'm Ella (Yiyao Li)

**I build AI systems that help people make decisions, and I test them.**

Every project has its own test set. I write the test cases before the first run. I report the results and the failures.

Data Science student at UC Berkeley. Research Assistant on the WISE Team, where I test how well large language models (LLMs) classify student reasoning.

## Featured

| Project | What it does | Results |
|---|---|---|
| **[Verdict](https://github.com/yli949-gif/verdict)** | Helps PayPal sellers decide how to answer a dispute. Fixed policy rules make the decision. The AI model explains it. The seller approves before anything is sent. | 95 test cases · matches the policy table in 100% of cases (Claude alone: 66%) · 0 unsafe actions · PayPal refused all 11 actions that skipped the safety check · 400 random contract tests |
| **[Holdfast](https://github.com/yli949-gif/holdfast)** | Makes AI coding agents follow rules, such as "only push after the tests pass." It checks every action. The rules are stored outside the model, so the agent cannot forget them. | Missed 8 of 129 rule breaks (regex hook: 39, built-in permissions: 54) · 0 of 93 attacks got through · 1,170 tests |
| **[WiderWorld](https://github.com/yli949-gif/widerworld)** · [live](https://widerworld-tau.vercel.app) | Helps parents plan their child's education. Rules decide what is allowed. The model only suggests changes. The parent approves each change. Every suggestion shows its source. | 10 test cases · 29 of 29 suggestions passed the hard rules · 0 made-up sources · 45 tests · the first version cost $0.43 in API fees |
| **[tadpole](https://github.com/yli949-gif/tadpole)** | Makes a coding agent plan, ask for approval, and then act. I tested it against the problems it should prevent, with a scoring rubric written in advance. | Plans before editing: 0 of 3 → 3 of 3 · rubric score 20/30 → 30/30 · 27 of 28 regression tests pass; the one failure led to v0.2 |

Also:
- **[ai-workflow-observability](https://github.com/yli949-gif/ai-workflow-observability)**: analyzes how AI agents perform in a customer support workflow (routing, escalation, and cost). 10 charts, a summary, and data ready for Tableau.
- **[saythis](https://github.com/yli949-gif/saythis)**: answers questions in meetings from your project notes and shows the sources. It says "low confidence" when the notes do not have the answer. 10 of 10 test cases pass.

## How I work

- Rules and fixed checks come first. The AI model comes second. A person makes the final decision.
- I write the tests before I build the feature.
- I keep the failures in the README.

I work in data science, AI testing, and AI products. I speak English and Chinese (中文). I am open to Data & AI analytics, applied AI, AI product, and AI evaluation roles.
