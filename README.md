# Open-source orchestration for zero-human companies 실전 가이드

**원본 저장소 `paperclip` 를 학습/실무 관점에서 재구성한 guide repo**

---

## 이 가이드는 무엇인가?

이 저장소는 [paperclip](https://github.com/paperclipai/paperclip.git) 원본을 직접 분석해,
설치/핵심 개념/운영 흐름/실무 활용 포인트를 한국어 guide 형태로 정리하는 문서 저장소입니다.

원본 요약: <p align="center"> <img src="doc/assets/header.png" alt="Paperclip — runs your business" width="720" /> </p>

## 시작 순서

1. `README.md` — 전체 지도 파악
2. `01-learning-paths.md` — 학습 경로 선택
3. `02-glossary.md` — 핵심 용어 정리
4. `sections/` 또는 `categories/` — 세부 주제 학습
5. `UPSTREAM-SNAPSHOT.md` — 현재 원본 기준점 확인

## 원본 저장소

- Source: `https://github.com/paperclipai/paperclip.git`
- Current synced commit: `5b479652f2dd`
- Local guide repo: `paperclip-guide`

<!-- GUIDE_SYNC:START -->
## 자동 동기화 상태

- origin repo: `paperclip`
- latest source commit: `8adae848e4f9`
- sync mode: `update`
- 영향 분류: CLI/명령어, 문서 구조, 소스코드

### 이번 반영 포인트

origin 변경 파일을 기준으로 guide 문서의 관련 섹션을 다시 읽고 반영했습니다. 핵심 영향 영역: CLI/명령어, 문서 구조, 소스코드.

### 최근 upstream 커밋

- `8adae848 Merge pull request #2675 from paperclipai/pap-feedback-trace-export-fixes`
- `00898e81 Restore feedback trace export fixes`
- `ed95fc1d Merge pull request #2674 from paperclipai/fix/feedback-test-uuid-redaction`
- `e13c3f7c fix: use deterministic UUID in feedback-service test to avoid phone redaction`
- `f8452a45 Merge pull request #2657 from paperclipai/fix/inbox-last-activity-ordering`
- `68b2fe20 Address Greptile telemetry review comments`

### 변경 파일 샘플

- `CONTRIBUTING.md`
- `docs/feedback-voting.md`
- `packages/shared/src/telemetry/client.ts`
- `packages/shared/src/telemetry/events.ts`
- `packages/shared/src/telemetry/index.ts`
- `packages/shared/src/telemetry/types.ts`
- `packages/shared/src/types/issue.ts`
- `releases/v2026.403.0.md`
- `scripts/screenshot.cjs`
- `server/src/__tests__/agent-skills-routes.test.ts`
- `server/src/__tests__/company-skills-routes.test.ts`
- `server/src/__tests__/feedback-service.test.ts`
- `server/src/__tests__/feedback-share-client.test.ts`
- `server/src/__tests__/issue-feedback-routes.test.ts`
- `server/src/__tests__/project-goal-telemetry-routes.test.ts`
- `server/src/__tests__/routine-run-telemetry.test.ts`
- `server/src/__tests__/routines-routes.test.ts`
- `server/src/__tests__/telemetry-client-flush.test.ts`
- `server/src/__tests__/workspace-runtime.test.ts`
- `server/src/app.ts`

> 이 블록은 guide sync가 자동 갱신합니다.
<!-- GUIDE_SYNC:END -->
