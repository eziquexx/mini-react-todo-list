# 📝✅ 할 일 목록 관리 애플리케이션
> 리액트를 사용하여 To-do List를 만들고 GitHub Pages로 배포하는 개인 미니 프로젝트.<br>
> 데이터는 로컬 스토리지 사용.
```
- 개발 기간: 24.08.05 ~ 24.08.21
- 목적: React를 이해하고 개인이 가볍게 사용할 목적으로 React를 사용하여 To-do List를 제작하였습니다.
```
---

## 🧩 구현 기능
<table>
  <thead>
    <tr>
      <th>기능</th>
      <th>설명</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>할 일 추가</td>
      <td>내용을 입력 후 + 버튼을 클릭하면 할 일이 목록에 추가된다.</td>
    </tr>
    <tr>
      <td>할 일 삭제</td>
      <td>추가된 할 일 우측에 있는 - 버튼을 클릭하면 삭제된다.</td>
    </tr>
    <tr>
      <td>할 일 수정</td>
      <td>추가된 할 일을 클릭하면 내용 수정이 가능하다.</td>
    </tr>
    <tr>
      <td>할 일 완료</td>
      <td>추가된 할 일 좌측의 체크박스를 클릭하면 완료가 되고 할 일 완료 영역으로 이동된다.</td>
    </tr>
    <tr>
      <td>할 일 취소</td>
      <td>할 일 완료 영역으로 이동된 할 일의 좌측에 체크박스를 클릭하면 다시 할 일 영역으로 이동된다.</td>
    </tr>
    <tr>
      <td>스타일</td>
      <td>스타일 컴포넌트를 사용하여 스타일 주기</td>
    </tr>
    <tr>
      <td>반응형</td>
      <td>브라우저 너비 마다 조절 (데스크탑, 태블릿+모바일 두 가지로 설정)</td>
    </tr>
    <tr>
      <td>데이터</td>
      <td>로컬 스토리지를 통해 목록 관리</td>
    </tr>
  </tbody>
</table>

---

## 🛠 사용 기술 스택
- HTML5
- CSS3
- React, React Styled Component
- Tools: VS Code, Git & GitHub, GitHub Pages

---

## 🎬 배포 & 데모
🚀 [배포 사이트 바로가기](https://eziquexx.github.io/mini-react-todo-list/) - GitHub Pages로 배포

---

## 📘 프로젝트 상세 기록
👉 [상세 보러가기](https://dev-jelee.notion.site/To-do-List-React-2c4d0316bc68817daea9fa9da5f7958c) - 노션에 올린 글

---

## 📁 디렉토리 구조

```
📂 src/
├── App.js                 // 할 일 메인 컴포넌트
├── App.css                // 공통 스타일(CSS)
├── components/
│   ├── TodoCompInput.js   // 할 일 완료 영역 컴포넌트
│   └── TodoListInput.js   // 할 일 기본 영역 컴포넌트
```

---

## 🖼️ UX/UI
<div>
  <span>▼▼ PC 화면 ▼▼</span><br/>
  <img src="https://github.com/eziquexx/mini-react-todo-list/blob/develop/src/img/todolist_img01.png" alt="PC화면" style="width:48%;">
</div><br>
<div>
  <span>▼▼ 태블릿, 모바일 화면 ▼▼</span><br/>
  <img src="https://github.com/eziquexx/mini-react-todo-list/blob/develop/src/img/todolist_img02.png" alt="태블릿,모바일일화면" style="width:48%;">
</div>

---

## :eyes: 개발 참고 자료
- To do List 입력 후 추가, 삭제하는 기능 (학원 수업 때 배운 내용 참고)
- 웹브라우저 새로고침 또는 종료 후 실행했을 경우 localStorage의 데이터를 가져와서 화면에 출력하기 위해 참고한 자료
  - [StackOverflow](https://stackoverflow.com/questions/77006383/react-localstorage-value-resets-after-every-refresh)
  - [MDN-Array.prototype.includes()](https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)
  - [MDN-String.prototype.includes()](https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/String/includes)
  - [MDN-String.prototype.slice()](https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/String/slice)
  - [MDN-String.prototype.toString()](https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/String/toString)
- input checkbox 기능
  - [React input](https://react.dev/reference/react-dom/components/input#controlling-an-input-with-a-state-variable)
- useCallback
  - [React useCallback](https://ko.react.dev/reference/react/useCallback)
- onBlur 기능
  - [React FocusEvent-onBlur](https://ko.react.dev/reference/react-dom/components/common#focusevent-handler)
  - [MDN-blur event](https://developer.mozilla.org/en-US/docs/Web/API/Element/blur_event)
- enter키 방지
  - [React KeyboardEvent-onKeyDown](https://ko.react.dev/reference/react-dom/components/common#keyboardevent-handler)
- 배열 정렬
  - [MDN-Array.prototype.sort()](https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)
- textarea 줄바꿈
  - [CodeSandbox](https://codesandbox.io/p/sandbox/textarea-auto-resize-react-hngvd?file=%2Fsrc%2Findex.js%3A19%2C1)
- styled-components
  - [styled-components](https://styled-components.com/)

---

## 💻 실행 방법 (VS Code 기준 설명)
```
# 1. 저장소 클론
git clone https://github.com/eziquexx/mini-react-todo-list.git

# 2. 프로젝트 디렉토리로 이동
cd mini-random-flag-quiz

# 3. node modules 설치
npm install

# 4. 실행
npm start
```

---

## ⬇️ 애플리케이션 설치
```
# 1. 배포 사이트로 이동
https://eziquexx.github.io/mini-react-todo-list/

# 2. 주소창 우측에 설치 모양 아이콘 클릭
주소창 우측에 보면 🖥️↓ 모니터에 화살표 아래방향으로 있는 아이콘이 있다.
마우스를 올리면 create react App sample 설치 라는 툴팁이 뜬다.
이 아이콘을 클릭하여 설치하면 바탕화면에 애플리케이션이 설치된다.
```

---
