[EN](https://github.com/calintzy/calintzy/blob/main/README.md) · [한국어](https://github.com/calintzy/calintzy/blob/main/README.ko.md)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:0ea5e9&height=200&section=header&text=promptnroll&fontSize=40&fontAlignY=36&fontColor=ffffff&desc=AI%20Native%20Fullstack%20%E2%80%A2%20ex-Quant%20Lead%20%E2%80%A2%2014%20years&descSize=16&descAlignY=56" width="100%" alt="promptnroll" />

<br/>

## About

14 years building production systems — 5 of them leading a quant trading team, where correctness and latency left no room for hand-waving. I work AI Native and full-stack now, focused on a question that keeps getting more urgent: **can we trust what AI agents actually do?**

Most of my recent work makes agent behavior measurable, and I ship all of it, across Python, TypeScript, and Rust. I also benchmark my own tools against their alternatives. When the result is unflattering, it goes in the README anyway.

<br/>

## 🔭 Currently

- **ratchetlock** — regression testing for LLM prompts. Freeze outputs that pass, replay them in CI with zero LLM calls — built after a prompt fix quietly un-fixed itself four days in a row
- **mycelium** — hybrid RAG for markdown vaults, 98.0% Hit@5 on KorQuAD. Recently benchmarked it against agentic search and stock plugin embeddings
- **adoptscore** — reads conversation logs to find out which AI tools you actually use. Its own first headline (78% unused) failed an audit; the honest number is 38.6%
- **daily briefing** — turns each morning's AI news into Instagram cards and ships top-5 news Reels twice a day, no human in the loop ([@todays.ai.brief](https://www.instagram.com/todays.ai.brief), [@muleori.news](https://www.instagram.com/muleori.news)), scheduled with Airflow

<br/>

## 🧰 Tech

<img src="https://skillicons.dev/icons?i=python,typescript,rust,fastapi,nextjs,react,docker,postgres&theme=dark" alt="tech stack" />

<br/>

## ⭐ Featured Projects

### 🛡️ AI Agent Safety & Evaluation

| Project | What it does | Stack |
|---|---|---|
| **[mycelium](https://github.com/calintzy/mycelium)** | Local hybrid RAG + GraphRAG over any markdown vault. Korean-aware BM25 fused with dense retrieval reaches 98.0% Hit@5 on KorQuAD, with a public reproduction script. Answers cite their sources, and when retrieval confidence is low it says so instead of guessing. | `Python` |
| **[stateful-guardrails](https://github.com/calintzy/stateful-guardrails)** | Catches slow-burn, multi-turn crises by accumulating risk across the conversation instead of judging each message alone. Beats a 5-turn window by 38.0%p in crisis recall at 1/45 the cost of re-reading everything. Known weak spots are in the README. | `Python` |
| **[ratchetlock](https://github.com/calintzy/ratchetlock)** | Regression testing for LLM prompts, layered on promptfoo (its only runtime dependency). Freezes passing outputs as snapshots and replays them in CI with zero LLM calls, so a failure caught once can never quietly come back. Proven on a production card-news prompt: 0/5 → 4/5, with the remaining failure kept visible as a real catch. | `TypeScript` |
| **[agentscore](https://github.com/calintzy/agentscore)** | Lighthouse for AI agent dev environments — a CLI that scores the health of Claude Code MCP / plugin setups. | `Python` |
| **[adoptscore](https://github.com/calintzy/adoptscore)** | Reads conversation logs to measure which AI coding tools you actually use, not which ones you installed. Audited its own 78% headline down to 38.6% and published the process. | `Python` |
| **[vali](https://github.com/calintzy/vali)** | Linter that flags hallucinations, slop, and over-engineering in AI-generated code. | `TypeScript` |

<br/>

### ⛓️ Blockchain Intelligence (MCP)

| Project | What it does | Stack |
|---|---|---|
| **[evmscope](https://github.com/calintzy/evmscope)** | EVM intelligence toolkit for AI agents — 23 MCP tools across 7 chains, zero config. | `TypeScript` |
| **[chain-eye](https://github.com/calintzy/chain-eye)** | Real-time EVM transaction monitoring TUI. | `Rust` |

<br/>

### 🦀 Developer Tools

| Project | What it does | Stack |
|---|---|---|
| **[drift](https://github.com/calintzy/drift)** | Dependency health monitor — scores your project's dependency survival probability. | `Rust` |
| **[git-vibe](https://github.com/calintzy/git-vibe)** | Vibe-check your codebase — git history analysis with emoji-based reports. | `Rust` |
| **[dotfig](https://github.com/calintzy/dotfig)** | One config to rule them all — generate ESLint, Prettier, TypeScript & EditorConfig from a single `dotfig.yml`. | `TypeScript` |

<br/>

## 📫 Contact

[GitHub](https://github.com/calintzy) · [email](mailto:byjrasid@gmail.com)
