# paperclip 개요

## 원본 저장소 역할

- repo: `paperclip`
- source: `https://github.com/paperclipai/paperclip.git`
- latest synced commit: `8adae848e4f9`
- summary: Quickstart &middot; Docs &middot; GitHub &middot;

## 이번 싸이클 판단

- sync mode: `update`
- impact labels: CLI/명령어, 문서 구조, 소스코드
- 판단: origin 변경 파일을 기준으로 guide 문서의 관련 섹션을 다시 읽고 반영했습니다. 핵심 영향 영역: CLI/명령어, 문서 구조, 소스코드.

## 최근 upstream 커밋

- `8adae848 Merge pull request #2675 from paperclipai/pap-feedback-trace-export-fixes`
- `00898e81 Restore feedback trace export fixes`
- `ed95fc1d Merge pull request #2674 from paperclipai/fix/feedback-test-uuid-redaction`
- `e13c3f7c fix: use deterministic UUID in feedback-service test to avoid phone redaction`
- `f8452a45 Merge pull request #2657 from paperclipai/fix/inbox-last-activity-ordering`
- `68b2fe20 Address Greptile telemetry review comments`

## 확인한 원본 구조

- `.agents/`
- `.claude/`
- `.dockerignore`
- `.env.example`
- `.mailmap`
- `.npmrc`
- `AGENTS.md`
- `cli/`
- `CONTRIBUTING.md`
- `doc/`
- `docker/`
- `Dockerfile`
- `docs/`
- `evals/`
- `LICENSE`
- `package.json`
- `packages/`
- `patches/`
- `pnpm-lock.yaml`
- `pnpm-workspace.yaml`

## guide 업데이트 포인트

- README 관리 블록 갱신
- `UPSTREAM-SNAPSHOT.md` 갱신
- `SYNC-LOG.md` 갱신
- 개요 문서 재작성

## 변경 파일 샘플

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
