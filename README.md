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
- latest source commit: `36049beeeacc`
- sync mode: `update`
- 영향 분류: README/소개, 설치/설정, CLI/명령어, 문서 구조, 소스코드

### 이번 반영 포인트

origin 변경 파일을 기준으로 guide 문서의 관련 섹션을 다시 읽고 반영했습니다. 핵심 영향 영역: README/소개, 설치/설정, CLI/명령어, 문서 구조, 소스코드.

### 최근 upstream 커밋

- `36049bee Merge pull request #2552 from paperclipai/PAPA-42-add-model-used-to-pr-template-and-checklist`
- `c041fee6 feat: add Model Used section to PR template and checklist`
- `82290451 Merge pull request #2541 from paperclipai/pap-1078-qol-fixes`
- `fb3b57ab merge master into pap-1078-qol-fixes`
- `ca8d35fd Merge pull request #2540 from paperclipai/pap-1078-inbox-operator-polish`
- `81a7f79d Merge pull request #2539 from paperclipai/pap-1078-workspaces-routines`

### 변경 파일 샘플

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

> 이 블록은 guide sync가 자동 갱신합니다.
<!-- GUIDE_SYNC:END -->
