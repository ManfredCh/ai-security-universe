## B.3 — New vulnerabilities and supply-chain items

The window's dominant fact: the compromise surface moved from models to the **agent toolchain**.

| Date | Item |
|---|---|
| 2026-10-21 | **LiteLLM 1.107.0** — PyPI wheels and containers ran a startup-hook credential stealer for ~100 minutes; intrusion dated ~2026-10-10 |
| 2026-10-08 | `tensorlake` 0.5.144 npm — Shai-Hulud worm in a preinstall hook on an agent-sandbox SDK |
| 2026-10-08/09 | GhostAction wave — fake security-audit workflows in 346 repos scraped AI-provider keys from git history |
| 2026-10-12/19 | Apex Accelerator fake AI-coding-assistant packages rerouted model traffic and registered an attacker MCP server; NEBULA shipped seven fake "AI SDK" droppers |
| 2026-09-30 → 10-20 | MCP TypeScript SDK: CVE-2026-104850 (OAuth material to hostile servers), CVE-2026-111770 (cross-client responses), four 1.32.0 advisories |
| 2026-10 | Agent harnesses: Claude Code CVE-2026-86063 / 103435; Claude Agent SDK CVE-2026-96620; GitLab CVE-2026-90970 / 96893; VS Code CVE-2026-102232 / 102851; Copilot CVE-2026-103572; Continue CVE-2026-109560; Roo Code CVE-2026-110202 (unfixed, archived); DeepSeek Harness CVE-2026-95183 |
| 2026-10 | Serving and runtime: Ollama CVE-2026-103663 / 102697; LMCache CVE-2026-105192; SGLang CVE-2026-111391 / 111392; Xoscar CVE-2026-49950; Langflow CVE-2026-105740 exploited in the wild (1,674 attempts) |
| 2026-10 | Frameworks and platforms: LangGraph CVE-2026-115883; LangChain-MongoDB CVE-2026-106119; Strands CVE-2026-115419; Google Agent Mesh CVE-2026-103091; FastMCP (two); IntentKit CVE-2026-76066; Azure SRE Agent CVE-2026-69435; Windows AI CVE-2026-69923; AgenticSeek CVE-2026-115727; Aider CVE-2026-115726; Archon CVE-2026-111322; LangChat CVE-2026-111704; Omnigent six advisories |
| 2026-10 | Sandboxes and spend: sandboxed.sh CVE-2026-109569 (nsenter host access); x402 SDK flaws letting a hostile API drain an agent wallet |
| 2026-10-22/23 | Agent skills as a vector: 88 indexed skills install PHP vulnerable to PHP2Shell; Manifold found 121 components calling high-risk domains |
| 2026-10 | Offensive operations (threat-intel): Storm-0940/ARTEX vs 2,250+ M365 tenants; Cairn 1,200+ sites; Skynet honeypot; CARLIY0S 400+ targets; BUGSTER (DeepSeek V4 Hermes agent); CyberXero 51 Claude Code agents; LLMjacking via GCP billing; PoeLLM botnet 3,400+ servers; DIVD breach via chained Zammad zero-days |

**What this changes**: ch. 6's supply-chain family is no longer a projection. A month produced more
toolchain CVEs than the body's entire pre-cutoff sample; ch. 9's deployment mapping gains named,
costed offensive operations as a routine category.

---

[← Back to contents](index.md)
