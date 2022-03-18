### ionic 뷰 타입으로 설치 방법(node_modules 파일- vue 타입도 선택할 수 있게 프레임워크에 추가된 모듈이다.)
---
1. `npm i -g` : npm 글로벌로 설치
2. 모듈 복사해서 넣기(vue 프레임워크 추가된 모듈)
3. `ionic start` 해서 파일 만들기
4. 만든 파일로 들어가기(cd 만든파일 이름)
5. `npm install -g @vue/cli` 설치
6. `npm i vue-router` 설치
7. `.ts`확장자를 `.js`로 바꿔주기
#### `.ts`확장자를 `.js`로 바꾸는 방법
💜참고페이지💜 https://ionicframework.com/docs/vue/quickstart
1) TypeScript 종속성 제거
    + `npm uninstall --save typescript @types/jest @typescript-eslint/eslint-plugin @typescript-eslint/parser @vue/cli-plugin-typescript @vue/eslint-config-typescript`
2) 모든 `.ts` 확장자 파일을 `.js`로 바꾸기
3) 모든 파일에 `script태그` 안에 `lang="ts"` 없애기
4) `tsconfig.json` 파일 지우기
5) `shims-vue.d.ts` 파일 지우기
6) `router > index.js` 파일에 `: Array<RouteRecordRaw>`와 `import { RouteRecordRaw } from 'vue-router';` 지우기
7) 밖에 `.eslintrc.js` 파일 안에서 `'@vue/typescript/recommended'` 와 `'@typescript-eslint/no-explicit-any': 'off'` 삭제하기
