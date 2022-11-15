
# Todo-app

* JSX 문법을 사용한 리액트 앱 개발 
* 함수 컴포넌트 기반의 개발
* React Hooks 사용
* PostCSS를 활용한 스타일링
* Netlify를 이용한 사이트 배포 (https://unique-boba-607005.netlify.app)

___

### 구현기능
1. 다크모드 
2. 투두아이템 필터링 기능
3. 투두아이템 체크박스 기능
4. 투두아이템 추가
5. 투두아이템 삭제
6. 투두리스트 저장 
<br />

<img src='https://github.com/dmswnlee/todo-app/blob/main/src/img/01.png?raw=true' alt='todo-app' />
<img src='https://github.com/dmswnlee/todo-app/blob/main/src/img/02.png?raw=true' alt='todo-app' />
<br />

### 다크모드
* 순수 CSS를 사용하여 다크모드 기능 동작
* context API를 사용하여 전역 데이터 관리 및 데이터 사용 
* tailwindcss darkmode를 활용하여 localStorage에 다크모드 여부 저장
<br />

### 필터링
* 외부데이터를 사용해서 필터링 기능 동작
<br />

### 아이템 체크박스 / 아이템 추가 / 아이템 삭제 
* input checkbox 요소 사용 
* checkbox를 checked 헸을 때 상태변경 됐을 때 함수 호출
* react hook을 사용하여 데이터값 저장 및 업데이트 
* filter() 메서드를 사용해서 상태변경 됐을 때 함수 호출 
<br />

### 아이템 저장 
* localStorage API를 이용한 아이템 저장
* react hook을 사용하여 처음 마운트 됐을 때만 동작할 수 있도록 구현 
<br />

___

### 어려웠던 부분 / 오류
* 초반 컴포넌트 구분의 어려움 
* 저장 된 투두아이템을 가져오기 위해 초기값에 함수를 호출했을 떄 useEffect를 사용했음에도 계속 호출되는 문제가 생김
* checkbox와 lable을 연결하는데 고정적인 id로 인해 오류가 생김 
<br />

### 문제해결
* useState초기값에 함수를 콜백함수로 감싸줌 
* 고정적인 id 값이 아닌 id 상태값을 가져와서 사용















