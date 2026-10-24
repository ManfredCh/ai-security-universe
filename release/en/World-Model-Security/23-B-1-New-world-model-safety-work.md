## B.1 — New world-model security work (2026-09-26 → 2026-10-25)

The body's material closes at 2026-08-09; Appendix A registers the 2026-09-26 search. This appendix
registers material found by 2026-10-25; **the body text is unchanged.**

| Work | Topic | Body issue |
|---|---|---|
| Towards Safe World Models: Risks, Defenses, and Evaluation (arXiv 2610.13372, 2026-10-09) | six-stage lifecycle (observations → state → dynamics → evaluation → action → feedback) organising a 163-work safety corpus | ch. 5 threat model; ch. 7 defence and runtime assurance — a second, compatible map of the same boundary structure |
| LGWM (arXiv 2610.11942) | decoder-free world model verifies GUI-agent transitions by predicting the next screen's representation; 0.987 AUC, 17 ms/decision | ch. 7: a world model deployed as a runtime *verifier*, not only an attack surface |
| Odyssey-3 (2026-10-08) | real-time interactive foundation world model; Physics-IQ Verified state of the art | ch. 10 deployment mapping: the "persistent interactive world" assumption moves toward product reality |
| Targeting World Models to Compromise Robot Learning Pipelines (noted in this search) | malicious prompts/dynamics injected into safe-looking teleop data activate only inside a world model, poisoning downstream policies | ch. 6 supply chain: the world model as a laundering point for training-data attacks |

**What this changes**: the body's convergence judgement — defence moves from detecting wrong
predictions to designing so wrong predictions are hard to exploit — gains a lifecycle-wide survey, a
deployed verifier pattern and a supply-chain attack that uses the world model itself as the
activation boundary.

---

[← Back to contents](index.md)
