# ๐ป ์ธ์ฆ ์ธ๊ฐ ๋ฐ ํฌ๋ ๋ฆฌ์คํธ ๊ตฌํ


## ๐ก ํ๋ก์ ํธ ์ค์น ๋ฐ ์คํ ๋ฐฉ๋ฒ

```zsh
$ npm install
$ npm start
```


## ๐ ๋ฐฐํฌ 
---
- ๋ฐฐํฌ ์ฃผ์: https://innie0526.github.io/wanted-pre-onboarding-frontend/
- 

### 1. ๋ก๊ทธ์ธ / ํ์๊ฐ์

<img src="https://user-images.githubusercontent.com/112600139/207554652-8bb40c2a-9743-4e6c-a9a1-01799fe12c25.gif">


- `/` ๊ฒฝ๋ก์ ๋ก๊ทธ์ธ / ํ์๊ฐ์ ๊ธฐ๋ฅ์ ๊ฐ๋ฐ
  - ํ์ด์ง ์์ ์ด๋ฉ์ผ ์๋ ฅ์ฐฝ, ๋น๋ฐ๋ฒํธ ์๋ ฅ์ฐฝ, ์ ์ถ ๋ฒํผ์ด ํฌํจ๋ ํํ๋ก ๊ตฌ์ฑ

- ์ด๋ฉ์ผ๊ณผ ๋น๋ฐ๋ฒํธ์ ์ ํจ์ฑ ๊ฒ์ฌ๊ธฐ๋ฅ์ ๊ตฌํ
  - ์ด๋ฉ์ผ ์กฐ๊ฑด: `@` ํฌํจ
  - ๋น๋ฐ๋ฒํธ ์กฐ๊ฑด: 8์ ์ด์
  - ์๋ ฅ๋ ์ด๋ฉ์ผ๊ณผ ๋น๋ฐ๋ฒํธ๊ฐ ์ ์กฐ๊ฑด์ ๋ง์กฑํ  ๋๋ง ๋ฒํผ์ด ํ์ฑํ 

- ๋ก๊ทธ์ธ API๋ฅผ ํธ์ถํ๊ณ , ์ฌ๋ฐ๋ฅธ ์๋ต์ ๋ฐ์์ ๋ `/todo` ๊ฒฝ๋ก๋ก ์ด๋
  - ๋ก๊ทธ์ธ API๋ ๋ก๊ทธ์ธ์ด ์ฑ๊ณตํ์ ์ Response Body์ JWT๋ฅผ ํฌํจํด์ ์๋ต
  - ์๋ต๋ฐ์ JWT๋ ๋ก์ปฌ ์คํ ๋ฆฌ์ง์ ์ ์ฅ

- ๋ก๊ทธ์ธ ์ฌ๋ถ์ ๋ฐ๋ฅธ ๋ฆฌ๋ค์ด๋ ํธ ์ฒ๋ฆฌ๋ฅผ ๊ตฌํ
  - ๋ก์ปฌ ์คํ ๋ฆฌ์ง์ ํ ํฐ์ด ์๋ ์ํ๋ก `/` ํ์ด์ง์ ์ ์ํ๋ค๋ฉด `/todo` ๊ฒฝ๋ก๋ก ๋ฆฌ๋ค์ด๋ ํธ 
  - ๋ก์ปฌ ์คํ ๋ฆฌ์ง์ ํ ํฐ์ด ์๋ ์ํ๋ก `/todo`ํ์ด์ง์ ์ ์ํ๋ค๋ฉด `/` ๊ฒฝ๋ก๋ก ๋ฆฌ๋ค์ด๋ ํธ 

---

### 2. ํฌ๋ ๋ฆฌ์คํธ

- `/todo`๊ฒฝ๋ก์ ์ ์ํ๋ฉด ํฌ๋ ๋ฆฌ์คํธ์ ๋ชฉ๋ก
- ๋ฆฌ์คํธ ํ์ด์ง์๋ ํฌ๋ ๋ฆฌ์คํธ์ ๋ด์ฉ๊ณผ ์๋ฃ ์ฌ๋ถ๊ฐ ํ์
- ๋ฆฌ์คํธ ํ์ด์ง์๋ ์๋ ฅ์ฐฝ๊ณผ ์ถ๊ฐ ๋ฒํผ์ด ์๊ณ , ์ถ๊ฐ ๋ฒํผ์ ๋๋ฅด๋ฉด ์๋ ฅ์ฐฝ์ ๋ด์ฉ์ด ์๋ก์ด ํฌ๋ ๋ฆฌ์คํธ๋ก ์ถ๊ฐ

- ํฌ๋ ๋ฆฌ์คํธ์ ์์ , ์ญ์  ๊ธฐ๋ฅ์ ๊ตฌํ
  - ํฌ๋ ๋ฆฌ์คํธ์ ๊ฐ๋ณ ์์ดํ ์ฐ์ธก์ ์์ ๋ฒํผ์ด ์กด์ฌํ๊ณ  ํด๋น ๋ฒํผ์ ๋๋ฅด๋ฉด ์์ ๋ชจ๋๊ฐ ํ์ฑํ๋๊ณ  ํฌ๋ ๋ฆฌ์คํธ์ ๋ด์ฉ์ ์์ 
  - ์์ ๋ชจ๋์์๋ ๊ฐ๋ณ ์์ดํ์ ์ฐ์ธก์ ์ ์ถ๋ฒํผ๊ณผ ์ทจ์๋ฒํผ์ด ํ์๋๋ฉฐ ํด๋น ๋ฒํผ์ ํตํด์ ์์  ๋ด์ฉ์ ์ ์ถํ๊ฑฐ๋ ์์ ์ ์ทจ์
  - ํฌ๋ ๋ฆฌ์คํธ์ ๊ฐ๋ณ ์์ดํ ์ฐ์ธก์ ์ญ์ ๋ฒํผ์ด ์กด์ฌํ๊ณ  ํด๋น ๋ฒํผ์ ๋๋ฅด๋ฉด ํฌ๋ ๋ฆฌ์คํธ๊ฐ ์ญ์ 


### ๋๋ ํ ๋ฆฌ ๊ตฌ์กฐ๋

```
๐ฆ src
โฃ ๐api
โ โฃ ๐api.js
โฃ ๐ components
โ โฃ ๐ Auth
โ โ โฃ ๐ SignIn.js
โ โ โ ๐ SignUp.js
โ โ ๐ Todo
โ   โฃ ๐ CreateTodo.js
โ   โฃ ๐ TodoList.js
โ   โ ๐ UpdateTodo.js
โฃ ๐pages
โ โฃ ๐ Auth
โ โ โ ๐ Auth.js
โ โ ๐ Todo
โ   โ ๐ Todo.js
โฃ ๐ index.js
โ ๐ Router.js
```



