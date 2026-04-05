# Sync Log — paperclip

## latest cycle

- previous source sha: `8adae848e4f9be916fe72dcdfc3bc3ac818e3f9c`
- current source sha: `6c8569156c60ab28ce531e25adbe15e8d69ae770`
- mode: `update`
- impact labels: 설치/설정, 문서 구조, 스킬/플러그인, 소스코드

## decision

origin 변경 파일을 기준으로 guide 문서의 관련 섹션을 다시 읽고 반영했습니다. 핵심 영향 영역: 설치/설정, 문서 구조, 스킬/플러그인, 소스코드.

## upstream commits reviewed

- `6c856915 Merge pull request #2792 from paperclipai/pr/master-pre-rebind-recovery`
- `c1920801 fix: harden worktree dependency hydration`
- `8ae4c0e7 Clean up opencode rebase and stabilize runtime test`
- `22af797c Provision local node_modules in issue worktrees`
- `27accb1b Clarify issue-scoped comment wake prompts`
- `b9b2bf3b Trim resumed comment wake prompts`
- `4dea3027 Speed up issues-page search`
- `b825a121 Prioritize comment wake prompts`

## evidence

- source remote: `https://github.com/paperclipai/paperclip.git`
- docs/interesting dirs: docs/, doc/, skills/, packages/, tests/
- changed file sample:
- `AGENTS.md`
- `adapter-plugin.md`
- `docs/adapters/adapter-ui-parser.md`
- `docs/adapters/claude-local.md`
- `docs/adapters/creating-an-adapter.md`
- `docs/adapters/external-adapters.md`
- `docs/adapters/overview.md`
- `docs/agents-runtime.md`
- `docs/docs.json`
- `packages/adapter-utils/src/index.ts`
- `packages/adapter-utils/src/log-redaction.ts`
- `packages/adapter-utils/src/server-utils.ts`
- `packages/adapter-utils/src/session-compaction.ts`
- `packages/adapter-utils/src/types.ts`
- `packages/adapters/claude-local/src/index.ts`
- `packages/adapters/claude-local/src/server/execute.ts`
- `packages/adapters/claude-local/src/server/test.ts`
- `packages/adapters/codex-local/src/server/execute.ts`
- `packages/adapters/cursor-local/src/server/execute.ts`
- `packages/adapters/gemini-local/src/server/execute.ts`
