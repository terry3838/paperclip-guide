# Sync Log — paperclip

## latest cycle

- previous source sha: `056a5ee32a1aac43474030c78b5815cda2c8a79a`
- current source sha: `36049beeeacc54a79993aac05b8ae1dcf8ea580c`
- mode: `update`
- impact labels: README/소개, 설치/설정, CLI/명령어, 문서 구조, 소스코드

## decision

origin 변경 파일을 기준으로 guide 문서의 관련 섹션을 다시 읽고 반영했습니다. 핵심 영향 영역: README/소개, 설치/설정, CLI/명령어, 문서 구조, 소스코드.

## upstream commits reviewed

- `36049bee Merge pull request #2552 from paperclipai/PAPA-42-add-model-used-to-pr-template-and-checklist`
- `c041fee6 feat: add Model Used section to PR template and checklist`
- `82290451 Merge pull request #2541 from paperclipai/pap-1078-qol-fixes`
- `fb3b57ab merge master into pap-1078-qol-fixes`
- `ca8d35fd Merge pull request #2540 from paperclipai/pap-1078-inbox-operator-polish`
- `81a7f79d Merge pull request #2539 from paperclipai/pap-1078-workspaces-routines`
- `ad1ef6a8 fix(ui): address final Greptile follow-up`
- `833842b3 fix(inbox): address Greptile review findings`

## evidence

- source remote: `https://github.com/paperclipai/paperclip.git`
- docs/interesting dirs: docs/, doc/, skills/, packages/, tests/
- changed file sample:
- `.github/CODEOWNERS`
- `.github/PULL_REQUEST_TEMPLATE.md`
- `.gitignore`
- `README.md`
- `cli/src/__tests__/allowed-hostname.test.ts`
- `cli/src/__tests__/company-delete.test.ts`
- `cli/src/__tests__/company-import-url.test.ts`
- `cli/src/__tests__/company.test.ts`
- `cli/src/__tests__/doctor.test.ts`
- `cli/src/__tests__/feedback.test.ts`
- `cli/src/__tests__/onboard.test.ts`
- `cli/src/__tests__/routines.test.ts`
- `cli/src/__tests__/telemetry.test.ts`
- `cli/src/__tests__/worktree.test.ts`
- `cli/src/commands/client/company.ts`
- `cli/src/commands/client/feedback.ts`
- `cli/src/commands/client/issue.ts`
- `cli/src/commands/configure.ts`
- `cli/src/commands/onboard.ts`
- `cli/src/commands/routines.ts`
