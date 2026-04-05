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
- latest source commit: `6c8569156c60`
- sync mode: `update`
- 영향 분류: 설치/설정, 문서 구조, 스킬/플러그인, 소스코드

### 이번 반영 포인트

origin 변경 파일을 기준으로 guide 문서의 관련 섹션을 다시 읽고 반영했습니다. 핵심 영향 영역: 설치/설정, 문서 구조, 스킬/플러그인, 소스코드.

### 최근 upstream 커밋

- `6c856915 Merge pull request #2792 from paperclipai/pr/master-pre-rebind-recovery`
- `c1920801 fix: harden worktree dependency hydration`
- `8ae4c0e7 Clean up opencode rebase and stabilize runtime test`
- `22af797c Provision local node_modules in issue worktrees`
- `27accb1b Clarify issue-scoped comment wake prompts`
- `b9b2bf3b Trim resumed comment wake prompts`

### 변경 파일 샘플

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

> 이 블록은 guide sync가 자동 갱신합니다.
<!-- GUIDE_SYNC:END -->
