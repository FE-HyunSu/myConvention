## 🤺 My convention

- 개인 코딩 컨벤션 정리. (update..)

#### 🥋 변수 선언
- 예약어를 변수명으로 사용 X (const / class / export / import / extends.. 등등)
- 변수명은 카멜케이스로 지정.
- const는 let 보다 위에 선언하기.

#### 🛹 들여쓰기
- space와 tab을 섞어서 사용하지 않고, space를 두번 쓰기.
- {tab} = return {space} * 2;

#### 📝 컴포넌트 폴더구조
```
├── components // 컴포넌트 폴더
│   ├── {pagaName} // 페이지
│   │   ├── {areaName} // 영역
│   │   │   ├── index.tsx // 레이아웃 or 기능
│   │   │   └── style.tsx // UI
│   │   └── {areaName}
│   │       ├── index.tsx 
│   │       └── style.tsx 
│   └── layout
│       ├── header
│       │   ├── index.tsx
│       │   └── style.tsx
│       └── footer
│           ├── index.tsx 
│           └── style.tsx 
...
```

#### 🪡 Git 
- main 브랜치에서 직접 작업 commit 금지.
- main push 후 merge feature는 삭제할 것.
