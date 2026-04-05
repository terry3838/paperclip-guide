# paperclip 개요

## 원본 저장소 역할

- repo: `paperclip`
- source: `https://github.com/paperclipai/paperclip.git`
- latest synced commit: `6c8569156c60`
- summary: Quickstart &middot; Docs &middot; GitHub &middot;

## 이번 싸이클 판단

- sync mode: `update`
- impact labels: 설치/설정, 문서 구조, 스킬/플러그인, 소스코드
- 판단: origin 변경 파일을 기준으로 guide 문서의 관련 섹션을 다시 읽고 반영했습니다. 핵심 영향 영역: 설치/설정, 문서 구조, 스킬/플러그인, 소스코드.

## 최근 upstream 커밋

- `6c856915 Merge pull request #2792 from paperclipai/pr/master-pre-rebind-recovery`
- `c1920801 fix: harden worktree dependency hydration`
- `8ae4c0e7 Clean up opencode rebase and stabilize runtime test`
- `22af797c Provision local node_modules in issue worktrees`
- `27accb1b Clarify issue-scoped comment wake prompts`
- `b9b2bf3b Trim resumed comment wake prompts`

## 확인한 원본 구조

- `.agents/`
- `.claude/`
- `.dockerignore`
- `.env`
- `.env.example`
- `.mailmap`
- `.npmrc`
- `.omx/`
- `adapter-plugin.md`
- `AGENTS.md`
- `cli/`
- `CONTRIBUTING.md`
- `doc/`
- `docker/`
- `Dockerfile`
- `docs/`
- `evals/`
- `LICENSE`
- `node_modules/`
- `package.json`

## guide 업데이트 포인트

- README 관리 블록 갱신
- `UPSTREAM-SNAPSHOT.md` 갱신
- `SYNC-LOG.md` 갱신
- 개요 문서 재작성

## 변경 파일 샘플

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
