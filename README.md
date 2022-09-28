# react-app-template

React UI 작업용 Template

## 개요

- 주 사용자 : 웹 퍼블리셔  
- UI 작업에 필요한 기본 폴더 구조 세팅  
- dom control 위한 jquery 세팅

## 디렉토리  
```
/
node_modules/     // node 모듈
public/           // public
package.json
package-lock.json
tsconfig.json     // tsx 설정
└ src             // 작업 폴더
  └ assets        // 리소스
    └ css
    └ images
  └ componets     // 컴포넌트
    └ ...
  └ pages         // 페이지
    └ ...
App.tsx
index.tsx
```

## 설치
```
node, git 설치 후
> npm install
> npm start
```

## 메모

- `create-react-app`의 typescript 템플릿 사용
- 별도 라이브러리
  - `sass`: sass(scss) 
  - `jQuery`: don control 및 jquery 기반 라이브러리 사용 시