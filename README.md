# AI Agent 서비스 비교

Perplexity Computer, Claude Cowork/Code, OpenAI Codex, OpenClaw — 4개 AI Agent 서비스의 구독 요금, 과금 모델, 아키텍처를 비교하는 정적 웹사이트.

## Pages

| 페이지 | 설명 | URL |
|--------|------|-----|
| **상세 비교표** | 개인용/기업용 탭, 플랜별 기능 매트릭스, 에이전트 카테고리 맵 | `index.html` |
| **Executive Summary** | C레벨 의사결정용 한 페이지 요약 | `summary.html` |
| **TCO 분석 & 인사이트** | 사용량별 연간 비용 시뮬레이터, 서비스 평가, 숨겨진 비용 분석 | `insights.html` |

## Features

- 개인용 / 기업용 탭 전환
- 카테고리별 기능 필터링
- 실측 데이터 기반 토큰/크레딧 소비량 비교
- TCO 시뮬레이터 (작업량/복잡도 조절)
- 에이전트 아키텍처 비교 (협업 / 데스크톱 자동화 / 코딩)
- 다크/라이트 모드 자동 전환 + 수동 토글
- 모바일 반응형 블록 레이아웃

## Tech

순수 HTML/CSS/JS. 빌드 도구 없음. Pretendard 폰트 CDN.

## Data Sources

- Anthropic 공식 문서 (Claude 토큰 제한)
- Perplexity Help Center (크레딧 시스템)
- OpenAI Help Center (메시지 제한, Enterprise 크레딧)
- 실사용자 리포트 (Substack, dev.to, Reddit)
- 실제 Enterprise 구독 크레딧 데이터

가격 정보는 2026년 3월 27일 기준.

## Deploy

GitHub Pages — `main` 브랜치 루트에서 배포.
