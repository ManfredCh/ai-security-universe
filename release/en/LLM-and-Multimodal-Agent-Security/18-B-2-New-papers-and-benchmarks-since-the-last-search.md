## B.2 — New papers and benchmarks since the last search

| Paper / benchmark | Topic | Body issue it speaks to |
|---|---|---|
| Overcoming the Retrieval Barrier (USENIX Security '26) | trigger-fragment decomposition makes indirect injection reliably retrieved; near-100% retrieval on 11 benchmarks, SSH-key exfiltration >80% in a multi-agent workflow | ch. 4 attack surface; ch. 6 earliest-interruption controls |
| Ignored, Not Refused (arXiv 2610.23254) | 33,000 trajectories: most failed injections are ignored (76–80%), not refused; system-prompt change alone swings ASR 0.2%→43% | ch. 8 data, metrics and the valid-denominator problem |
| PIAtlas + PICorpus (arXiv 2610.24999) | six-mechanism construction taxonomy over the largest license-clean injection corpus; shows benchmark blind spots | ch. 5 taxonomy design and coverage audit |
| The Window Is in the Reasoning (arXiv 2610.24048) | branching rollouts: whether an agent follows an injection is partly decided *after* it is read; thinking shifts the share | ch. 6 runtime monitors; ch. 8 single-run evaluation limits |
| MPIDetector (arXiv 2610.30202) | few-shot ICL detection of multimodal prompt injection | ch. 6 defence families |
| Compaction Laundering (Pixee) | forged user-approval turn survives context compaction in five coding agents (87–100%) | ch. 5 memory/state; ch. 6 defences |
| Memory injection & CarryoverBench | planted orders persist in long-term memory across vendors and re-fire over five later rounds | ch. 5 memory persistence |
| INFUSE | injections hidden in files a coding agent reads; mean ASR 19.6% across 19 models | ch. 7 evaluation evidence |
| LatentRiskBench | action-level guardrails miss state-dependent violations (0.09 vs 0.96 detection) | ch. 7 metrics; ch. 6 monitor layer |
| HarnessSecurity-Bench | auto-approve raises ASR 29.2%→95.6% across six harnesses | ch. 8 deployment mapping |
| AutoRedClaw | auto-generated attacks beat hand-built benchmarks (>50% ASR on most of seven harnesses) | ch. 7 benchmark design |
| Approve What, Exactly | four frameworks execute tool-call arguments changed after user approval | ch. 4 authorisation boundary |
| BRANCH (Mindgard) | tree search rewrote prompts until six guardrail systems passed; 100% ASR | ch. 6 guardrail composition |
| Provably hidden capabilities (NeurIPS '26) | encrypted backdoor in weights resists fine-tuning and trigger search | ch. 6 supply-chain defence limits |
| SLDR | LoRA recovery adapter restores refusals after malicious fine-tuning | ch. 6 defence families |
| PersistBD | backdoors survive benign fine-tuning; RL stage can strengthen them | ch. 6 supply chain |
| Screwtape (Redwood) | edited agent transcripts evade action-only monitors (35 attacks in 252 runs) | ch. 6 monitor layer |
| Jev-as-a-judge counterfeit policy (Datadog) | handing a classifier its own answer key cut detection recall 82.9%→3.88% | ch. 6, ch. 8 evaluation fragility |
| MCP-FSD | 1 in 6 unclassified MCP servers reach the host filesystem; 150 vulnerable instances confirmed | ch. 6 tool boundary |
| MITRE ATT&CK v20 | T1698/T1699 prompt-injection IDs, T1700 AI-enabled exfiltration | ch. 9 incident taxonomy mapping |

---

[← Back to contents](index.md)
