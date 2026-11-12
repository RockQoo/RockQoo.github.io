# RockQoo.github.io STATUS

마지막 갱신: 2026-11-12

## 현재 상태

- 시작 버전: **v20** (`C:\Work\Projects\rockqoo.github.io`에서 커밋하지 않았던 최신 `index.html`을 복사). v19 대비 "AI 활용" 탭 추가, 문제 해결 사례 문장 수정
- 예전 기록(v8~v19 커밋)은 새 저장소에 가져오지 않았다. 백업: `Interview/_backup/git/RockQoo/RockQoo.github.io.git`
- 버전별 초안(v14~v20)과 변경 메모: `Interview/resume/versions/`

## 다음 할 일

- [ ] 이력서 갱신할 내용 정리 (사용자와 함께)
- [ ] 공개 전 검토: 개인정보, 회사 기밀 기준(CLAUDE.md 규칙)
- [x] 로컬 저장소 생성, v20으로 첫 커밋 (640879c)
- [x] 기존 GitHub 저장소 삭제 (2026-11-12). **지금 https://rockqoo.github.io 는 내려가 있다**
- [x] GitHub에 `RockQoo/RockQoo.github.io` 공개 저장소 새로 만들고 push, Pages 배포 확인 (2026-11-12, 커밋 1개)
  - 변경: GitHub 링크 2곳 제거(계정이 비어 있어서), 깨진 `doc.html` 링크 제거, 재직 기간 자동 계산(`.dur[data-from]`)
  - AI 활용 탭은 빼고 올렸다. 초안: `Interview/resume/versions/index_20.html`
  - `_config.yml` 동작 확인: `/CLAUDE.md`는 사이트에서 404

## 다음 할 일 (갱신)

- [ ] AI 활용 탭 공개 범위 검토 → 일반화해서 다시 추가 (현 직장 내부 구조: CodeGen 파이프라인, 사내 CI 도구, 데드락 분석)
- [ ] 문제 해결 사례의 서버 구조 설명 검토
- [ ] GitHub에 새 프로젝트가 생기면 GitHub 링크와 "개인 프로젝트" 섹션 다시 추가
- [ ] 연차 "12년차" 표기는 고정 글자다. 해가 바뀌면 확인
- [ ] GitHub Pages 켜기: Settings → Pages → Deploy from a branch → `main` / `/ (root)`
- [ ] https://rockqoo.github.io 접속 확인
