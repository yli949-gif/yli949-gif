# Hi, I'm Ella (Yiyao Li)

**I build and evaluate AI systems for real-world decision making.**

Everything I ship comes with its own evaluation: a set of cases written before the first run, numbers I can defend, and the failures listed next to the wins.

Data Science at UC Berkeley · Research Assistant, WISE Team (LLM evaluation and label-efficient learning)

## Featured

| Project | What it proves | Numbers |
|---|---|---|
| **[Verdict](https://github.com/yli949-gif/verdict)** | AI-assisted decision support for PayPal dispute handling. Policy rules decide, the model explains, PayPal's own allowed-actions links gate every call, and the seller approves before anything is sent. | 95-case benchmark · 100% agreement with an independent policy table vs. 66% for Claude zero-shot · 0% unsafe actions · 11/11 gate-bypass probes rejected by PayPal · 400 randomized contract tests |
| **[Holdfast](https://github.com/yli949-gif/holdfast)** | Stateful guardrails for AI coding agents: plain-English rules ("only push after the tests pass") enforced on every tool call, with state kept outside the model so it can't be forgotten. | missed violations 8/129 vs. 39/129 (regex hook) and 54/129 (native permissions) on a blind test set · 0/93 adversarial bypasses · 1,170 tests |
| **[WiderWorld](https://github.com/yli949-gif/widerworld)** · [live](https://widerworld-tau.vercel.app) | A deployed AI decision-support product where a rule engine is the source of truth, the model may only propose structured changes, and the parent approves each one. Evidence provenance on every suggestion. | 10-case eval with pre-stated expectations · 29/29 proposals passed hard constraints · 0 fabricated sources · 45 tests · whole V1 cost $0.43 in API spend |
| **[tadpole](https://github.com/yli949-gif/tadpole)** | A human-in-the-loop workflow for coding agents, tested against the failure modes it claims to prevent, with a pre-registered rubric. | plan-before-edit 0/3 → 3/3 · criteria 20/30 → 30/30 · regression 27/28 · the one failure motivated v0.2 |

Also: [ai-workflow-observability](https://github.com/yli949-gif/ai-workflow-observability), operational analytics of AI agents inside a support workflow (routing, escalation, cost; 10 figures, executive summary, Tableau-ready exports) · [saythis](https://github.com/yli949-gif/saythis), a grounded meeting-answer pipeline (small-model triage → retrieval → cited answer, LOW confidence when the answer isn't in the sources; 10/10 fixtures).

## How I work

Rules and deterministic checks before model judgment; model judgment before human review; human review always. Write the eval before the feature. Keep the failures in the README.

Background: data science, AI evaluation, and AI product work; bilingual (English / 中文). Open to Data & AI analytics, Applied AI, AI product, and evaluation roles.
