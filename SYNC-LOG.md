# Sync Log — paperclip

## latest cycle

- previous source sha: `5b479652f2dda2bff3905ecfb7f1f272e75de733`
- current source sha: `056a5ee32a1aac43474030c78b5815cda2c8a79a`
- mode: `update`
- impact labels: 문서 구조, 소스코드

## decision

origin 변경 파일을 기준으로 guide 문서의 관련 섹션을 다시 읽고 반영했습니다. 핵심 영향 영역: 문서 구조, 소스코드.

## upstream commits reviewed

- `056a5ee3 fix(ui): render agent capabilities field in org chart cards (#2349)`
- `dedd972e Fix inbox ordering: self-touched issues no longer sink to bottom (#2144)`
- `6c2c63e0 Merge pull request #2328 from bittoby/fix/project-slug-collision`
- `461779a9 Merge pull request #2430 from bittoby/fix/add-gemini-local-to-adapter-types`
- `6aa3ead2 fix: add gemini_local to AGENT_ADAPTER_TYPES validation enum`
- `e0f64c04 Merge pull request #2407 from radiusred/chore/docker-improvements`
- `420cd4fd chore(docker): improve base image and organize docker files`
- `99296f95 fix: append short UUID suffix to project slugs when non-ASCII characters are stripped to prevent slug collisions`

## evidence

- source remote: `https://github.com/paperclipai/paperclip.git`
- docs/interesting dirs: docs/, doc/, skills/, packages/, tests/
- changed file sample:
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
