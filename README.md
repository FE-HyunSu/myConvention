## 🤺 My convention

- 개인 저장소에서 진행한 convention 입니다.

#### 🥋 변수 선언
- 예약어를 변수명으로 사용 X (const / class / export / import / extends.. 등등)
- 변수명은 카멜케이스로 지정.
- const는 let 보다 위에 선언하기. (var 사용x)
- 변수 선언시 any Type 지양.

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

#### 🪡 Git convention.
- main 브랜치에서 직접 작업 commit 금지.
- feature에서 main 브랜치까지 직접적으로 merge하지 말것. 반드시 release 브랜치를 통해 merge.
- main 브랜치까지 push 후 merge된 feature는 삭제할 것.
- main push 단위 기준은 없음. ETC(EveryDay Ten Commit) 챌린지 진행중으로 개인 저장소에서는 push 전략없이 필요 시 즉시 진행.
```
// 개인 저장소에서 Branch Tree convention.
├── feature
│   └── {YYYYMMDD_TaskName}
├── release
└── Main
```

#### 🤹‍♂️ Prettier set

```
{
  "editor.fontSize": 15,
  "debug.console.fontSize": 15,
  "terminal.integrated.fontSize": 15,
  "terminal.integrated.automationShell.osx": "",
  "terminal.integrated.shell.osx": "/bin/zsh",
  "editor.minimap.enabled": false,
  "prettier.printWidth": 100,
  "prettier.tabWidth": 2,
  "prettier.singleQuote": true,
  "editor.tabSize": 2,
  "editor.insertSpaces": false,
  "liveServer.settings.donotShowInfoMsg": true,
  "prettier.jsxSingleQuote": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "workbench.iconTheme": "vscode-icons",
  "workbench.colorTheme": "Community Material Theme Darker High Contrast",
  "vsicons.dontShowNewVersionMessage": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "diffEditor.wordWrap": "off",
  "explorer.confirmDragAndDrop": false,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "editor.guides.indentation": false,
  "editor.formatOnSave": true
}
```

