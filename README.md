# Atom Research

기술 리서치 & 분석 아카이브. 정적 웹사이트로 GitHub Pages에서 배포.

## Structure

```
index.html              ← 포털 (리서치 목록)
ai-agent/               ← AI Agent 서비스 비교
  index.html            ← 상세 비교표
  summary.html          ← Executive Summary
  insights.html         ← TCO 분석 & 인사이트
docs/                   ← 스펙, 플랜, 참조 데이터
```

## Research Topics

### AI Agent 서비스 비교 (2026.03)

Perplexity Computer, Claude Cowork/Code, OpenAI Codex, OpenClaw — 구독 요금, 과금 모델, 아키텍처, TCO 분석.

- 개인용 / 기업용 플랜별 기능 매트릭스
- 실측 토큰/크레딧 소비 데이터
- TCO 시뮬레이터 (작업량/복잡도 조절)
- 에이전트 아키텍처 비교 (협업 / 데스크톱 자동화 / 코딩)
- 서비스 평가 및 숨겨진 비용 분석

## Tech

순수 HTML/CSS/JS. 빌드 도구 없음. Pretendard 폰트 CDN.

## Deploy

GitHub Pages — `main` 브랜치 루트에서 배포.

## Adding Research

1. 새 디렉토리 생성 (예: `new-topic/`)
2. `index.html` 등 페이지 작성
3. 포털 `index.html`의 `.research-grid`에 카드 추가
