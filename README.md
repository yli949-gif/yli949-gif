# Hi, I'm Ella (Yiyao Li)

**I build and evaluate AI systems for real-world decision making.**

Everything I ship comes with its own evaluation: a set of cases written before the first run, numbers I can defend, and the failures listed next to the wins.

## Featured

| Project | What it proves | Numbers |
|---|---|---|
| **[WiderWorld](https://github.com/yli949-gif/widerworld)** · [live](https://widerworld-tau.vercel.app) | A deployed AI decision-support product where a rule engine is the source of truth, the model may only propose structured changes, and the parent approves each one. Evidence provenance on every suggestion. | 10-case eval with pre-stated expectations · 29/29 proposals passed hard constraints · 0 fabricated sources · 45 tests · whole V1 cost $0.43 in API spend |
| **[tadpole](https://github.com/yli949-gif/tadpole)** | A human-in-the-loop workflow for coding agents, tested against the failure modes it claims to prevent, with a pre-registered rubric. | plan-before-edit 0/3 → 3/3 · criteria 20/30 → 30/30 · regression 27/28 · the one failure motivated v0.2 |
| **[ai-workflow-observability](https://github.com/yli949-gif/ai-workflow-observability)** | Operational analytics of AI agents inside a support workflow: routing, escalation, cost, where the system (not the model) fails. | 10 figures, executive summary, Tableau-ready exports |

Also: [saythis](https://github.com/yli949-gif/saythis), a grounded meeting-answer pipeline (small-model triage → retrieval → cited answer, LOW confidence when the answer isn't in the sources; 10/10 fixtures).

## How I work

Rules and deterministic checks before model judgment; model judgment before human review; human review always. Write the eval before the feature. Keep the failures in the README.

Background: data science and AI product work; bilingual (English / 中文). Open to Applied AI, AI product, and evaluation roles.
