# A boilerplate project for nextjs

## 주요 패키지

### Base

- [nextjs](https://nextjs.org/) — React 기반 웹 프레임워크

### UI

- [tailwindcss](https://tailwindcss.com/) — CSS 프레임웨크로 미리 정의된 유틸리티 클래스를 활용
- [storybook](https://storybook.js.org/) — UI 개발/테스트/문서 등 전반적으로 활용

### Better for Development Experience

- 코드 포매터 및 린터
  - [prettier](https://prettier.io/) — 일관된 코드 스타일 유지
  - [eslint](https://eslint.org/) — javascript 코드 검사
  - [typescript-eslint](https://typescript-eslint.io/) — typescript 코드에서 eslint 실행
- git 훅
  - [husky](https://typicode.github.io/husky) — 커밋(or 푸시)할 때 커밋 메세지 검사, 테스트 등을 실행
  - [lint-staged](https://github.com/okonet/lint-staged) — 스테이지된 파일을 검사 (husky 와 같이 사용)
- 개발 환경 호환
  - [cross-env](https://github.com/kentcdodds/cross-env) — 환경에 상관없이 동일한 환경 변수 설정
  - [rimraf](https://github.com/isaacs/rimraf) — The UNIX command rm -rf for node

### ETC

- [@next/bundle-analyzer](https://www.npmjs.com/package/@next/bundle-analyzer) — 번들 파일 분석 for 웹 성능 최적화

---

## 예제 사용

> 먼저 프로젝트를 복사

```bash
git clone <this repository>
npm install
```

### 커맨드 사용

- `npm run dev` — 개발 [http://localhost:3000/](http://localhost:3000/)
- `npm run build` — 빌드
- `npm run start` — 로컬에서 빌드 확인 [http://localhost:3000/](http://localhost:3000/)
- `npm run clean` — `node_modules` 와 `.next` 폴더 삭제
- `npm run analyze` — 번들 분석 실행
