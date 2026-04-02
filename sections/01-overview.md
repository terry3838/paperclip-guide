# paperclip 개요

## 원본 저장소 역할

- repo: `paperclip`
- source: `https://github.com/paperclipai/paperclip.git`
- latest synced commit: `056a5ee32a1a`
- summary: Quickstart &middot; Docs &middot; GitHub &middot;

## 이번 싸이클 판단

- sync mode: `update`
- impact labels: 문서 구조, 소스코드
- 판단: origin 변경 파일을 기준으로 guide 문서의 관련 섹션을 다시 읽고 반영했습니다. 핵심 영향 영역: 문서 구조, 소스코드.

## 최근 upstream 커밋

- `056a5ee3 fix(ui): render agent capabilities field in org chart cards (#2349)`
- `dedd972e Fix inbox ordering: self-touched issues no longer sink to bottom (#2144)`
- `6c2c63e0 Merge pull request #2328 from bittoby/fix/project-slug-collision`
- `461779a9 Merge pull request #2430 from bittoby/fix/add-gemini-local-to-adapter-types`
- `6aa3ead2 fix: add gemini_local to AGENT_ADAPTER_TYPES validation enum`
- `e0f64c04 Merge pull request #2407 from radiusred/chore/docker-improvements`

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

- `Dockerfile`
- `doc/DEVELOPING.md`
- `doc/DOCKER.md`
- `doc/UNTRUSTED-PR-REVIEW.md`
- `docker/Dockerfile.onboard-smoke`
- `docker/docker-compose.quickstart.yml`
- `docker/docker-compose.untrusted-review.yml`
- `docker/docker-compose.yml`
- `docker/quadlet/paperclip-db.container`
- `docker/quadlet/paperclip.container`
- `docker/quadlet/paperclip.pod`
- `docs/deploy/docker.md`
- `packages/shared/src/constants.ts`
- `packages/shared/src/index.ts`
- `packages/shared/src/project-url-key.ts`
- `scripts/docker-build-test.sh`
- `scripts/docker-entrypoint.sh`
- `scripts/docker-onboard-smoke.sh`
- `server/src/services/projects.ts`
- `ui/src/lib/inbox.test.ts`
