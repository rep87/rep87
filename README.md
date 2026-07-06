# 방시온 / Sion Bang

> **TL;DR (EN):** I use small AI-assisted prototypes to test what current AI tools can actually do.
> What worked: coding agents can compress implementation, evaluation loops, and experiment setup dramatically.
> What still needs human judgment: defining what "good" means, checking risks, and deciding when results are trustworthy. (as of 2026-07, using Codex/Claude/GPT)

AI가 바꿀 미래를 막연히 상상하기보다, 작은 프로토타입을 직접 만들어보면서 지금 가능한 것과 아직 어려운 것을 확인하고 있습니다.

이곳은 완성된 제품만 전시하는 공간이라기보다, AI를 활용해 아이디어를 실제 시스템으로 바꿔보는 개인 실험실이자 작업 노트에 가깝습니다.

## 확인하고 싶은 질문

- AI에게 맡길 수 있는 일과 아직 사람의 손과 감각이 필요한 일의 경계는 어디인가?
- "아직 부족한 것"과 "거의 못하는 것"은 어떻게 구분할 수 있는가?
- 좋은 결과를 원한다면, 무엇을 먼저 평가 기준으로 바꿔야 하는가?
- 작은 프로토타입은 미래의 변화 방향을 확인하는 데 도움이 되는가?
- AI가 만든 결과뿐 아니라 평가 기준과 판단 과정 자체도 함께 설계해야 하는가?

## Current Focus

- AI-assisted prototyping
- LLM / RAG applications
- Evaluation-driven workflows
- Data-driven experiments
- Simulation and browser-based prototypes

## Selected Experiments

- [Farm_Agents](https://github.com/rep87/farm-agents) — 딸기 스마트팜에서 LLM 제어 판단을 바로 믿지 않고, 안전성·정책 준수·설명 가능성 같은 평가 기준으로 비교한 로컬 AI supervisor 하네스. 다음 단계는 실제 장비 제어가 아니라, 닫힌 루프와 스마트팜 트윈을 통한 반복 검증입니다.
- Coin Trading Research Harness — 업비트 KRW 현물 전략 후보를 백테스트, 랜덤 베이스라인, dry-run, 리스크 게이트로 검증하는 비공개 연구 하네스. 투자 조언이나 자동매매 성공 사례가 아니라, 위험한 의사결정 전 검증 구조를 빠르게 만든 실험입니다.
- Competition Automation — Kaggle/DACON에서 데이터 다운로드, 환경 설정, GPU 실험, 제출 반복을 Codex로 자동화했습니다. (2026-07, Codex 기준) 평가 지표가 명확할 때 반복 실험은 빨라졌지만, 포화된 리더보드와 새로운 접근 탐색은 여전히 사람이 설계해야 했습니다.
- [AI Game Prototyping Experiments](https://github.com/rep87/ai-game-prototyping-experiments) — Canvas/Phaser 게임들을 여러 번 만들며 게임 루프, 화면, 기본 시스템은 빠르게 만들 수 있음을 확인했습니다. (2026-04~07, Codex/GPT 이미지 생성 기준) 조작감, 타격감, 에셋 일관성, "게임의 맛"은 레퍼런스와 평가 기준이 없으면 쉽게 무너졌습니다.
- Smart Farm & Life Tools — [strawberry-daily-report](https://github.com/rep87/strawberry-daily-report), [pre-work-selftest](https://github.com/rep87/pre-work-selftest) 같은 작은 HTML 도구를 빠르게 만들었습니다. 실제로 쓸 만한 도구가 되려면 이상적인 기능보다 귀찮은 순간의 입력 부담과 판단 기준을 먼저 설계해야 했습니다.

## Note

Some projects are public experiments, while others are private, unfinished, or kept only as learning records.  
The focus is not only on what was built, but on what each attempt revealed about AI, tools, systems, and possible futures.
