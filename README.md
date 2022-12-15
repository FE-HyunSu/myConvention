## 🤺 My convention

- 개인 저장소에서 진행한 convention 입니다.

#### 🥋 변수 선언
- 예약어를 변수명으로 사용 X (const / class / export / import / extends.. 등등)
- 변수명은 카멜케이스로 지정.
- const는 let 보다 위에 선언하기. (var 사용x)
- 변수 선언시 any Type 지양.

#### 📝 UI 컴포넌트 폴더구조
```java
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
├── store
├── api
...
```

#### 🪡 Git convention.
- main 브랜치에서 직접 작업 commit 금지.
- feature에서 main 브랜치까지 직접적으로 merge하지 말것. 반드시 release 브랜치를 통해 merge.
- main 브랜치까지 push 후 merge된 feature는 삭제할 것.
- main push 단위 기준은 없음. ETC(EveryDay Ten Commit) 챌린지 진행중으로 개인 저장소에서는 push 전략없이 필요 시 즉시 진행.
```java
// 개인 저장소에서 Branch Tree convention.
├── feature
│   └── {YYYYMMDD_TaskName}
├── release
└── main
```

#### 🤹‍♂️ Prettier set

```js
// .prettierrc
{
  "editor.formatOnSave": true,
  "prettier.semi": false,
  "prettier.trailingComma": "all",
  "prettier.singleQuote": true,
  "prettier.tslintIntegration": true,
  "prettier.tabWidth": 2,
  "prettier.printWidth": 120
}
```

#### 🔪 Recoil Naming convention.

- Atom : keywordAtom
- Value : recoilKeyword
- State : isKeywordAtom, setKeywordAtom
