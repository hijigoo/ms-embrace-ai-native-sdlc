# Embrace AI Native SDLC

GitHub Copilot으로 우리 팀의 개발 베스트 프랙티스를 하네스로 만드는 워크숍 자료입니다.
이론 세션 2개(각 60분)와 Hands-on Lab 180분으로 구성되며, 원리 → 방법론 → 실습 순서로 진행합니다.

## 프로그램 개요

| 항목 | 내용 |
|------|------|
| 대상 | 개발자 · 개발 리드 · 플랫폼 담당 (10~30명) |
| 소요 시간 | 5시간 (이론 세션 120분 = 60분 × 2 · 실습 180분) |
| 사용 도구 | GitHub Copilot (VS Code · CLI) |
| 장소 | 마이크로소프트 또는 고객사 |

**목적** — 요구사항 분석부터 설계·구현·테스트·배포까지 개발 전 과정에 코딩 에이전트를 적용하고, 팀의 개발 베스트 프랙티스를 하네스로 구성하는 방법을 실습합니다.

**고객 준비 사항**
- 실습용 개인 컴퓨터 환경 (VS Code, GitHub Copilot CLI)
- 실습 도구 계정·라이선스 및 인터넷 가능한 네트워크 환경

## 타임테이블

| # | 제목 | 타입 | 시간 | 핵심 주제 | 결과 |
|---|------|------|------|-----------|------|
| 01 | AI 개발 에이전트 아키텍처 딥다이브 | 세션 | 60분 | 코딩 에이전트의 작동 방식, 확장 방법과 비용 구조 | 에이전트 작동 원리 이해 및 심화 |
| 02 | AI Native SDLC의 설계와 진행 | 세션 | 60분 | 명세 · 근거 · 검증 중심의 3가지 방법론 비교, 팀 적용 시 고려 사항 | 우리 팀 베스트 프랙티스 선정 기준 수립 |
| 03 | Hands-on Lab | 실습 | 180분 | 빈 저장소에서 앱과 팀 개발 표준(하네스) 구축, 명세 → 구현 → 테스트 → 배포 | 동작하는 앱과 팀 하네스 |

> 시간 배분은 예시이며, 고객 일정과 참석자 수준에 맞춰 조정할 수 있습니다.

## 슬라이드 · 실습 자료

| 세션 | 위치 | 내용 |
|------|------|------|
| 01 | [`slides-html/ai-native-harness-slides.html`](slides-html/ai-native-harness-slides.html) | 모델·도구·하네스, 에이전트 루프와 Context, 확장(Tool · MCP · Skill · Hook · Subagent), 토큰 최적화, HydraFusion |
| 02 | [`slides-html/harness-sdlc-slides-native.html`](slides-html/harness-sdlc-slides-native.html) | Spec Kit(SDD), Superpowers, HVE Core |
| 03 | [daeungo1/msft-ghcp-dev-workshop](https://github.com/daeungo1/msft-ghcp-dev-workshop) | Hands-on Lab 실습 자료 |

> `slides-pptx/`는 `.gitignore`에 포함되어 있습니다.
