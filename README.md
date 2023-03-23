# A boilerplate project for nextjs

## How to Use

### 프로젝트 시작

```bash
git clone <this repository>
npm install
```

### 개발

```bash
// 로컬 서버 http://localhost:3000
npm run dev
```

### 빌드

```bash
npm run build

// 로컬 서버에서 실행 (http://localhost:3000)
npm run start
```

---

## Packages

### Base

- nextjs [공식문서](https://nextjs.org/)
  - React 기반 웹 프레임워크

### UI

- tailwindcss [공식문서](https://tailwindcss.com/)
  - CSS 프레임웨크로 미리 정의된 유틸리티 클래스를 활용
- storybook [공식문서](https://storybook.js.org/)
  - UI 개발/테스트/문서 등 전반적으로 활용

### Better for Development Experience

- 코드 포매터 및 린터
  - prettier [공식문서](https://prettier.io/)
    - 일관된 코드 스타일 유지
  - eslint [공식문서](https://eslint.org/)
    - javascript 코드 검사
  - typescript-eslint [공식문서](https://typescript-eslint.io/)
    - typescript 코드에서 eslint 실행
- git 훅
  - husky [공식문서](https://typicode.github.io/husky)
    - 커밋(or 푸시)할 때 커밋 메세지 검사, 테스트 등을 실행
  - lint-staged [공식문서](https://github.com/okonet/lint-staged)
    - 스테이지된 파일을 검사 (husky 와 같이 사용)

### ETC

- @next/bundle-analyzer [공식문서](https://www.npmjs.com/package/@next/bundle-analyzer)
  - 번들된 파일 분석 for 웹 성능 최적화
- cross-env [공식문서](https://github.com/kentcdodds/cross-env)
  - 환경에 상관없이 동일한 환경 변수 설정
- rimraf [공식문서](https://github.com/isaacs/rimraf)
  - The UNIX command rm -rf for node
