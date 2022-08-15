# gyeolstagram-front

## TODO

- [x] Router
- [x] Authentication
- [x] Architecture
- [ ] Styles ( like dark mode )

## Setup

npm i styled-components react-hook-form react-router-dom @apollo/client graphql react-helmet-async

npm i --save @fortawesome/fontawesome-svg-core
npm install --save @fortawesome/free-solid-svg-icons
npm install --save @fortawesome/react-fontawesome

npm install --save @fortawesome/free-brands-svg-icons
npm install --save @fortawesome/free-regular-svg-icons

### Router

hash router -> browser router -

#### Hash router

/banana/delicious를 받을 때,
router matching : `/` , `/banana/`, `/delicious/`
각각의 routes를 다 받아옴

- `<switch>` 를 추가하면 됨. => `<Routes>` 로 변경되었음.
- 하나의 route만 render 하고 싶을 때 사용함.
- `exact` 도 삭제됨

#### Reactive Variables

    - Apollo client 에 포함
    - login status, dark mode, volume...etc.
    -

#### styled component

`import styled from "styled-components";`
얘네들은 Component 다. `props` 받는 것도 가능함.

- Dark mode : Themeprovider

- App 에 Theme 넣어주기

- npm i styled-reset

- background-color에 GobalStyle 에서 접근이 가능함

#### Login Page

- Container 만들기
- Link Component : in react router dom.
  link component return a href
- login 하지 않았을 때만 접근하도록 `app.js` 수정
