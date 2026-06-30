[EN](https://github.com/calintzy/calintzy/blob/main/README.md) · [한국어](https://github.com/calintzy/calintzy/blob/main/README.ko.md)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:0ea5e9&height=200&section=header&text=promptnroll&fontSize=40&fontAlignY=36&fontColor=ffffff&desc=AI%20Native%20Fullstack%20%E2%80%A2%20ex-Quant%20Lead%20%E2%80%A2%2014%20years&descSize=16&descAlignY=56" width="100%" alt="promptnroll" />

<br/>

## 소개

프로덕션 시스템을 만든 지 14년, 그중 5년은 퀀트 트레이딩 팀을 이끌었습니다. 정확성과 지연시간에 적당히 넘어갈 여지가 없는 일이었죠. 지금은 AI Native 풀스택으로 일하며, 점점 더 절박해지는 질문 하나에 집중합니다 — **AI 에이전트가 하는 일을 우리는 믿을 수 있는가?**

요즘 만드는 것들은 대부분 에이전트의 행동을 **측정하고, 안전하게 지키고, 검증하는** 도구입니다. 그리고 전부 끝까지 출시합니다. Python, TypeScript, Rust를 오가면서요.

<br/>

## 🔭 요즘 하는 일

- **stateful-guardrails** — 여러 턴에 걸쳐 쌓이는 에이전트 위협을 터지기 전에 잡아내기
- **agentscore** — AI 에이전트 개발환경이 건강한지 점수로 진단하기
- **vali** — AI가 만든 코드에서 환각과 슬롭을 걸러내기

<br/>

## 🧰 기술 스택

<img src="https://skillicons.dev/icons?i=python,typescript,rust,fastapi,nextjs,react,docker,postgres&theme=dark" alt="tech stack" />

<br/>

## ⭐ 주요 프로젝트

### 🛡️ AI 에이전트 안전·평가

| 프로젝트 | 무엇을 하나 | 스택 |
|---|---|---|
| **[stateful-guardrails](https://github.com/calintzy/stateful-guardrails)** | 한 번에 터지지 않고 여러 턴에 걸쳐 쌓이는 위협을, 메시지를 하나씩 보는 대신 대화 전체의 위험을 누적해 잡아냅니다. McNemar 검정·부트스트랩 신뢰구간으로 검증했고, 안 된 결과도 그대로 적었습니다. | `Python` |
| **[mycelium](https://github.com/calintzy/mycelium)** | 마크다운 볼트 위에서 도는 로컬 우선 하이브리드 RAG + GraphRAG. Dense와 BM25(한국어 토크나이저)를 RRF로 묶고, 출처까지 달아 답합니다. Ollama로 전부 로컬에서 돌아갑니다. | `Python` |
| **[agentscore](https://github.com/calintzy/agentscore)** | AI 에이전트 개발환경을 진단하는 CLI. Claude Code의 MCP·플러그인 구성이 건강한지 점수로 보여줍니다. | `Python` |
| **[vali](https://github.com/calintzy/vali)** | AI가 만든 코드에서 환각·슬롭·과잉설계를 잡아내는 린터. | `TypeScript` |

<br/>

### ⛓️ 블록체인 분석 (MCP)

| 프로젝트 | 무엇을 하나 | 스택 |
|---|---|---|
| **[evmscope](https://github.com/calintzy/evmscope)** | AI 에이전트를 위한 EVM 분석 툴킷. 7개 체인에서 23개 MCP 도구를, 설정 없이 바로. | `TypeScript` |
| **[chain-eye](https://github.com/calintzy/chain-eye)** | 실시간 EVM 트랜잭션 모니터링 TUI. | `Rust` |

<br/>

### 🦀 개발자 도구

| 프로젝트 | 무엇을 하나 | 스택 |
|---|---|---|
| **[drift](https://github.com/calintzy/drift)** | 의존성 건강 모니터 — 프로젝트 의존성의 생존 확률을 점수로 매깁니다. | `Rust` |
| **[git-vibe](https://github.com/calintzy/git-vibe)** | 코드베이스 바이브 체크 — git 히스토리를 이모지 리포트로 분석합니다. | `Rust` |
| **[dotfig](https://github.com/calintzy/dotfig)** | 설정 파일을 하나로 — `dotfig.yml` 하나에서 ESLint·Prettier·TypeScript·EditorConfig를 생성합니다. | `TypeScript` |

<br/>

## 📫 연락

[GitHub](https://github.com/calintzy) · [이메일](mailto:byjrasid@gmail.com)
