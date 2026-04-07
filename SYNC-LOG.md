# Sync Log — paperclip

## latest cycle

- previous source sha: `6c8569156c60ab28ce531e25adbe15e8d69ae770`
- current source sha: `08fea10ce1af97b52c1da41ee82d8340468244a4`
- mode: `update`
- impact labels: 설치/설정, 문서 구조, 스킬/플러그인, 소스코드

## decision

origin 변경 파일을 기준으로 guide 문서의 관련 섹션을 다시 읽고 반영했습니다. 핵심 영향 영역: 설치/설정, 문서 구조, 스킬/플러그인, 소스코드.

## upstream commits reviewed

- `08fea10c Merge pull request #2772 from paperclipai/PAPA-46-why-did-this-issue-succeed-without-following-my-instructions`
- `b74d94ba Treat Pi quota exhaustion as a failed run (#2305)`
- `8f722c57 fix: allow to remove project description (#2338)`
- `b6e40fec feat: add AWS Bedrock auth support on "claude-local" (#2793)`
- `eefe9f39 Merge pull request #2797 from paperclipai/PAP-1019-make-a-plan-for-first-class-blockers-wake-on-subtasks-done`
- `5a252020 fix: drop stale child issue props after rebase`
- `4c01a45d fix: address greptile feedback for blocker dependencies`
- `467f3a74 Stabilize rebased route test expectations`

## evidence

- source remote: `https://github.com/paperclipai/paperclip.git`
- docs/interesting dirs: docs/, doc/, skills/, packages/, tests/
- changed file sample:
- `AGENTS.md`
- `CONTRIBUTING.md`
- `doc/SPEC-implementation.md`
- `docs/api/issues.md`
- `docs/guides/agent-developer/heartbeat-protocol.md`
- `docs/guides/agent-developer/task-workflow.md`
- `packages/adapters/claude-local/src/server/execute.ts`
- `packages/adapters/claude-local/src/server/quota.ts`
- `packages/adapters/claude-local/src/server/test.ts`
- `packages/adapters/openclaw-gateway/src/server/execute.ts`
- `packages/adapters/pi-local/src/server/execute.ts`
- `packages/adapters/pi-local/src/server/parse.test.ts`
- `packages/adapters/pi-local/src/server/parse.ts`
- `packages/db/src/index.ts`
- `packages/db/src/migrations/0049_flawless_abomination.sql`
- `packages/db/src/migrations/meta/0049_snapshot.json`
- `packages/db/src/migrations/meta/_journal.json`
- `packages/db/src/schema/index.ts`
- `packages/db/src/schema/issue_relations.ts`
- `packages/shared/src/constants.ts`
