## π€Ί My convention

- κ°μΈ μ μ₯μμμ μ§νν convention μλλ€.

#### π₯ λ³μ μ μΈ
- μμ½μ΄λ₯Ό λ³μλͺμΌλ‘ μ¬μ© X (const / class / export / import / extends.. λ±λ±)
- λ³μλͺμ μΉ΄λ©μΌμ΄μ€λ‘ μ§μ .
- constλ let λ³΄λ€ μμ μ μΈνκΈ°. (var μ¬μ©x)
- λ³μ μ μΈμ any Type μ§μ.

#### π UI μ»΄ν¬λνΈ ν΄λκ΅¬μ‘°
```java
βββ components // μ»΄ν¬λνΈ ν΄λ
β   βββ {pagaName} // νμ΄μ§
β   β   βββ {areaName} // μμ­
β   β   β   βββ index.tsx // λ μ΄μμ or κΈ°λ₯
β   β   β   βββ style.tsx // UI
β   β   βββ {areaName}
β   β       βββ index.tsx 
β   β       βββ style.tsx 
β   βββ layout
β       βββ header
β       β   βββ index.tsx
β       β   βββ style.tsx
β       βββ footer
β           βββ index.tsx 
β           βββ style.tsx 
βββ store
βββ api
...
```

#### πͺ‘ Git convention.
- main λΈλμΉμμ μ§μ  μμ commit κΈμ§.
- featureμμ main λΈλμΉκΉμ§ μ§μ μ μΌλ‘ mergeνμ§ λ§κ². λ°λμ release λΈλμΉλ₯Ό ν΅ν΄ merge.
- main λΈλμΉκΉμ§ push ν mergeλ featureλ μ­μ ν  κ².
- main push λ¨μ κΈ°μ€μ μμ. ETC(EveryDay Ten Commit) μ±λ¦°μ§ μ§νμ€μΌλ‘ κ°μΈ μ μ₯μμμλ push μ λ΅μμ΄ νμ μ μ¦μ μ§ν.
```java
// κ°μΈ μ μ₯μμμ Branch Tree convention.
βββ feature
β   βββ {YYYYMMDD_TaskName}
βββ release
βββ main
```

#### π€ΉββοΈ Prettier set

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

#### πͺ Recoil Naming convention.

- Atom : keywordAtom
- Value : recoilKeyword
- State : isKeywordAtom, setKeywordAtom
