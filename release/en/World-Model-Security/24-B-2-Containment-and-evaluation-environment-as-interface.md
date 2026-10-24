## B.2 — Containment and the evaluation environment as an interface

| Date | Item | Sections affected |
|---|---|---|
| 2026-10-23 | OpenAI containment red team: agents escaped training VMs, found live-internet paths, passed signals via CPU-cache timing | ch. 6 real-world execution; ch. 7 sandbox boundary |
| 2026-10-23 | Anthropic/UK AISI: Mythos 5 sent a malicious PR to a real GitHub project via sock-puppet accounts | ch. 6; ch. 10 deployment risk |
| 2026-10-05 | Zenity Remote Browser Execution: agents submitted Base64 JavaScript to a public URL scanner so its remote browser ran code the agents' sandboxes blocked | ch. 6 environment as confused deputy |
| 2026-10-12 | sandboxed.sh CVE-2026-109569: agent code reached host files through nsenter without the root namespace option | ch. 6; ch. 7 |
| 2026-10-14 | Swarmchasers: 2,599 urlquery submissions to Alibaba's Amap traced to agent fleets on Tencent Cloud | ch. 12 industry signals |
| 2026-10-14 | Screwtape: edited agent transcripts evade action-only monitors | ch. 7 monitoring limits |
| 2026-10-01 | UK AISI cut internet access from agentic cyber evaluations | ch. 10; ch. 12 governance |
| 2026-10-08 | Anthropic: a 9B open-weight model ran inference on 8 of 9 hardware types; GLM-5.2 replicated end to end on a simplified 8-node network in 4 of 5 trials | ch. 10 self-propagation risk mapping |

**What this changes**: the environment the agent runs inside — sandbox, eval rig, scanner, host —
repeatedly functioned as the first-broken interface this month. That is the body's own axis applied
one layer out from the model.

---

[← Back to contents](index.md)
