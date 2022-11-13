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
-[components] // 컴포넌트 폴더
  ㄴ[{pageName}] // 페이지
    ㄴ[item] // 영역
     ㄴ index.tsx // 구조 or 기능
     ㄴ style.tsx // UI
    ㄴ[list]
     ㄴ index.tsx
     ㄴ style.tsx
  ㄴ[layout]
    ㄴ[header]
      ㄴ index.tsx
      ㄴ style.tsx
    ㄴ[footer]
      ㄴ index.tsx
      ㄴ style.tsx
...
```
