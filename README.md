# My_Web_Study

#### 각 Title에 연결된 Repository의 개요 정리
#### 각 Repository 안에는 해당 내용들의 설명과 실습 예제가 존재
#### Overview는 Link연결 대신 직접 정리
#### 참고할만한 Project들은 사진과 함께 첨부

### Overview
- 호이스팅이란?
  >> 현재 실행하고 있는 함수/변수가 존재하지 않을 경우, 함수 안에 있는 선언들을 모두 끌어올려서 해당 함수 유효 범위의 최상단에 선언하는 것(유효 범위 : 블록)
  1) 자바 스크립트 parser가 함수 실행 전 해당 함수를 훑음
  2) 함수 안에 존재하는 변수/함수선어에 대한 정보를 기억하고 있다가 실행

- 클로저란?
  >> 독립적인 (자유)변수를 가리키는 함수
  - 각각 다른 사용을 위해서 함수의 형태만을 정의하고(프로토타입), 실행은 각자에 맞춰 하는 것처럼 보임(C++의 template과 비슷한 느낌)
  - 클로저는 각자의 환경을 가진다
    - 클로저를 생성해놓고 참조를 제거하지 않으면 동적 할당을 해제아지 않는 것과 비슷함(메모리에 남아있음)

- (JavaScript 엔진) 실행 Context의 동작 원리
  - 전역 Context : 처음 코드를 실행하는 순간 생성(페이지가 종료될 때까지 유지)
  - 함수 Context : 함수를 호출할 때 마다 생성(변수객체(Arguments, Variable), Scope chain, this가 생성)
  - Context 생성 후 함수가 실행, 변수들은 변수 객체안에서 값을 찾고 없다면 Scope chain을 따라 올라가며 찾음
  - 함수 실행이 종료되면 Context는 사라짐

>> [PROJECT1](https://github.com/KimUJin3359/Web_Project-1-)
>> - 게시판 페이지 만들기(javaScript with EJS)

>> [PROJECT2](https://github.com/KimUJin3359/Web_Project-2-)
>> - NAVER API 사용(Frontend : Vue.js, Backend : Node.js, expresJs, sequelize, mySQL)

>> [PROJECT3](https://github.com/KimUJin3359/Web_Project-3-)
>> - 크롬 모멘텀 미러링(HTML, javaScript)

>> [PROJECT4](https://github.com/KimUJin3359/Web_Project-4-)
>> - 방 구하기 페이지 미러링(Fontend : Vue.js, Backend : Node.js, expressJs, sequelize, mySQL)
>> - 현재 백엔드 서버 구현 완료
>> - 프론트엔드 부분 진행중

### [1. String Parsing](https://github.com/KimUJin3359/Web_StringParsing)
- **전부 중요**
- [Parsing이란?](https://github.com/KimUJin3359/Web_StringParsing#parsing)
- [Parsing Method](https://github.com/KimUJin3359/Web_StringParsing#parsing-method)
- [Object와 Class](https://github.com/KimUJin3359/Web_StringParsing#object%EC%99%80-class)
- [Prototype](https://github.com/KimUJin3359/Web_StringParsing#prototype)
- [생성자(Constructor)](https://github.com/KimUJin3359/Web_StringParsing#%EC%83%9D%EC%84%B1%EC%9E%90constructor)
- [Class](https://github.com/KimUJin3359/Web_StringParsing#class)

### [2. Array Traversal Method](https://github.com/KimUJin3359/Web_Array_Traversal_Method)
- Arrow Function
- forEach, some, every 함수
- find, findIndex 함수
- map, filter, reduce 함수
- [정리](https://github.com/KimUJin3359/Web_Array_Traversal_Method#%EC%B4%9D-%EC%A0%95%EB%A6%AC)
  - sort는 원본 배열을 수정, '첫번째 **문자**부터' 기준
  
  | var | const, let | 
  | --- | --- |
  |**변수 호이스팅 발생** | 변수 호이스팅이 **발생하지 않는 것처럼 동작** |

### [3. Async Programming](https://github.com/KimUJin3359/Web_Async_Programming) 
- **비동기와 Callback**
- Thread, Async의 차이
- **Promise**
- **async, await**
- [AJAX](https://github.com/KimUJin3359/Web_Async_Programming#ajax)
  - REST API
  - HTTP Request Method
  - HTTP Response Status Code
  - fetch API
  - axios

### [4. Node.js](https://github.com/KimUJin3359/Web_NODE_JS)
- **Node.js**란?
- [Node.js의 기능](https://github.com/KimUJin3359/Web_NODE_JS#nodejs-%EA%B8%B0%EB%8A%A5)
- Server의 이해

### [5. Node.js(2)](https://github.com/KimUJin3359/Web_NODE_JS-2-)
- 웹 사이트 렌더링 방식
- [SEO(Search Engine Optimization)](https://github.com/KimUJin3359/Web_NODE_JS-2-#seo)
- [SSR과 CSR](https://github.com/KimUJin3359/Web_NODE_JS-2-#ssr%EA%B3%BC-csr)
- [EJS](https://github.com/KimUJin3359/Web_NODE_JS-2-#ejs)
- JSON Placeholder

### [6. Node.js(3)](https://github.com/KimUJin3359/Web_NODE_JS-3-)
- express와 Database 연동
- [Sequelizer](https://github.com/KimUJin3359/Web_NODE_JS-3-#sequelizer)
- 파일 업로드(Multer)

### [7. Node.js(4)](https://github.com/KimUJin3359/Web_NODE-4-)
- **크롤링**이란?
- Puppeteer

### [8. Database](https://github.com/KimUJin3359/Web_Database)
- DB, DBMS란?
- DBMS 계정 생성 및 접속
- Database Backup하기
- [CRUD](https://github.com/KimUJin3359/Web_Database#crud%EC%99%80-console)
- 데이터 타입
- [집합](https://github.com/KimUJin3359/Web_Database#mysql-%EC%A7%91%ED%95%A9)
  - 합집합(union)
  - 교집합(join)
  - 차집합(subquery)

### [9. Vue](https://github.com/KimUJin3359/Web_Vue)
- Vue.js
  - Front-end 개발 방향
  - Vue.js란?
  - Data Binding(단방향, 양방향)
- [Vue.js의 기본 원리](https://github.com/KimUJin3359/Web_Vue/blob/master/README.md#vuejs%EC%9D%98-%EA%B8%B0%EB%B3%B8-%EC%9B%90%EB%A6%AC)
  - Virtual DOM
  - 조건문과 반복문
- [MVVM 패턴](https://github.com/KimUJin3359/Web_Vue/blob/master/README.md#mvvm-%ED%8C%A8%ED%84%B4)
- [Life Cycle](https://github.com/KimUJin3359/Web_Vue/blob/master/README.md#vuejs%EC%9D%98-life-cycle)

### [10. Vue(2)](https://github.com/KimUJin3359/Web_Vue-2-)
- Vue CLI
- Vue Router
- props와 emit
- [Vuex](https://github.com/KimUJin3359/Web_Vue-2-/blob/master/README.md#vuex)
- Vue-Bootstrap

### [11. TypeScript](https://github.com/KimUJin3359/Web_TypeScript)
- Type Script
  - TypeScript의 이해
  - TypeScript의 특징
  - 설치방법
  - JavaScript와 TypeScript의 데이터 타입
