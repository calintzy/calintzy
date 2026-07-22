[EN](https://github.com/calintzy/calintzy/blob/main/README.md) · [한국어](https://github.com/calintzy/calintzy/blob/main/README.ko.md)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,100:0ea5e9&height=200&section=header&text=promptnroll&fontSize=40&fontAlignY=36&fontColor=ffffff&desc=AI%20Native%20Fullstack%20%E2%80%A2%20ex-Quant%20Lead%20%E2%80%A2%2014%20years&descSize=16&descAlignY=56" width="100%" alt="promptnroll" />

<br/>

## 소개

프로덕션 시스템을 만든 지 14년, 그중 5년은 퀀트 트레이딩 팀을 이끌었습니다. 정확성과 지연시간에 적당히 넘어갈 여지가 없는 일이었죠. 지금은 AI Native 풀스택으로 일하며 질문 하나에 집중합니다. **AI 에이전트가 하는 일을 우리는 믿을 수 있는가?**

요즘 만드는 것들은 대부분 에이전트의 행동을 측정하는 도구고, 전부 끝까지 출시합니다. Python, TypeScript, Rust를 오가면서요. 제 도구는 경쟁 방식과도 직접 비교해 재고, 불리한 결과도 README에 그대로 적습니다.

<br/>

## 🔭 요즘 하는 일

- **ratchetlock** — LLM 프롬프트용 회귀 테스트. 통과한 출력을 저장해 두고 CI에서는 LLM 호출 없이 재채점합니다. 고쳐 둔 프롬프트 문제가 나흘 연속 되살아난 사고가 출발점입니다
- **mycelium** — 마크다운 볼트용 하이브리드 RAG. 공개 벤치마크 KorQuAD에서 Hit@5 98.0%를 쟀고, 최근에는 에이전틱 검색이나 플러그인 기본 임베딩과도 비교해 봤습니다
- **adoptscore** — 설치 목록이 아니라 대화 로그를 읽어 실제로 쓰는 도구를 가려냅니다. 처음 나온 "78%를 안 쓴다"는 숫자를 스스로 검증해 38.6%로 바로잡았습니다
- **daily briefing** — 매일 아침 AI 뉴스를 사람 손 없이 인스타그램 카드로 발행합니다([@todays.ai.brief](https://www.instagram.com/todays.ai.brief)). 스케줄은 Airflow로 관리합니다

<br/>

## 🧰 기술 스택

<img src="https://skillicons.dev/icons?i=python,typescript,rust,fastapi,nextjs,react,docker,postgres&theme=dark" alt="tech stack" />

<br/>

## ⭐ 주요 프로젝트

### 🛡️ AI 에이전트 안전·평가

| 프로젝트 | 무엇을 하나 | 스택 |
|---|---|---|
| **[mycelium](https://github.com/calintzy/mycelium)** | 마크다운 볼트 위에서 도는 로컬 하이브리드 RAG + GraphRAG. 한국어 형태소를 아는 키워드 검색을 의미 검색과 묶어 KorQuAD에서 Hit@5 98.0%를 냈고, 재현 스크립트도 공개했습니다. 답변에는 출처를 달고, 근거가 부족하면 지어내는 대신 모른다고 답합니다. | `Python` |
| **[stateful-guardrails](https://github.com/calintzy/stateful-guardrails)** | 한 번에 터지지 않고 여러 턴에 걸쳐 쌓이는 위기를, 메시지를 하나씩 보는 대신 대화 전체의 위험을 누적해 잡아냅니다. 최근 5턴만 보는 방식보다 위기 적중률이 38.0%p 높고, 비용은 전체를 매번 읽는 방식의 45분의 1입니다. 약점도 README에 그대로 적었습니다. | `Python` |
| **[ratchetlock](https://github.com/calintzy/ratchetlock)** | LLM 프롬프트의 회귀를 막는 CLI. promptfoo 위에 얹어(런타임 의존성은 그것 하나) 통과한 출력을 스냅샷으로 동결하고, CI에서는 LLM 호출 없이 재채점해 한번 잡은 실패가 조용히 되살아나지 못하게 합니다. 실운영 카드뉴스 프롬프트에서 0/5 → 4/5로 검증했고, 남은 1건은 도구가 실제 결함을 잡은 사례라 그대로 공개했습니다. | `TypeScript` |
| **[agentscore](https://github.com/calintzy/agentscore)** | AI 에이전트 개발환경을 진단하는 CLI. Claude Code의 MCP·플러그인 구성이 건강한지 점수로 보여줍니다. | `Python` |
| **[adoptscore](https://github.com/calintzy/adoptscore)** | 설치 목록이 아니라 대화 로그를 읽어 실제로 쓰는 AI 도구를 측정합니다. 스스로 낸 78% 헤드라인을 검증해 38.6%로 바로잡고 그 과정까지 공개했습니다. | `Python` |
| **[vali](https://github.com/calintzy/vali)** | AI가 만든 코드에서 환각, 슬롭, 과잉설계를 잡아내는 린터. | `TypeScript` |

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
