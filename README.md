# 딜메이트 한 페이지 홈페이지 (claude 작업본)

문구 출처: 로컬 `output/딜메이트_사업계획서_v20261003.md`. 프로젝트 규칙은 로컬 프로젝트의 `AGENTS.md`를 따른다.

- 미확정 가격, 출시되지 않은 기능, 후기·실적은 넣지 않았다.
- 미리보기: 이 폴더에서 `node scripts/preview.mjs` → http://127.0.0.1:4173 (포트 변경: `node scripts/preview.mjs 4174`)
- `public/`이 배포할 정적 파일이다. 빌드 과정 없음.
- GitHub 업로드와 Vercel 배포는 공개 문구를 사용자가 확정한 뒤 진행한다.
- 배포 저장소: [make-dealmate/dealmate_claude](https://github.com/make-dealmate/dealmate_claude) (공개). 이 폴더(`claude/site/`)의 내용만 저장소 최상위에 올린다. 프로젝트 코드 정본(AGENTS.md)은 바꾸지 않는다.
