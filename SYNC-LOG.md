# Sync Log — paperclip

## latest cycle

- previous source sha: `36049beeeacc54a79993aac05b8ae1dcf8ea580c`
- current source sha: `8adae848e4f9be916fe72dcdfc3bc3ac818e3f9c`
- mode: `update`
- impact labels: CLI/명령어, 문서 구조, 소스코드

## decision

origin 변경 파일을 기준으로 guide 문서의 관련 섹션을 다시 읽고 반영했습니다. 핵심 영향 영역: CLI/명령어, 문서 구조, 소스코드.

## upstream commits reviewed

- `8adae848 Merge pull request #2675 from paperclipai/pap-feedback-trace-export-fixes`
- `00898e81 Restore feedback trace export fixes`
- `ed95fc1d Merge pull request #2674 from paperclipai/fix/feedback-test-uuid-redaction`
- `e13c3f7c fix: use deterministic UUID in feedback-service test to avoid phone redaction`
- `f8452a45 Merge pull request #2657 from paperclipai/fix/inbox-last-activity-ordering`
- `68b2fe20 Address Greptile telemetry review comments`
- `aa256fee feat: add authenticated screenshot utility (#2622)`
- `728fbdd1 Fix markdown paste handling in document editor (#2572)`

## evidence

- source remote: `https://github.com/paperclipai/paperclip.git`
- docs/interesting dirs: docs/, doc/, skills/, packages/, tests/
- changed file sample:
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
