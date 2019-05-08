# 리액트
1. 목표 : 리액트 문법을 익히고, 
      todolist app을 실습을 통해 컴포넌트 나누기 / props & state 관리 / 이벤트 처리를 직접 해보기
2. 참고 :  
[React 기초 입문 프로젝트 – 흔하디 흔한 할 일 목록 만들기](https://velopert.com/3480)  
[React.js cheatsheet](https://devhints.io/react)
         
3. 결과 : 
<img src="https://user-images.githubusercontent.com/18348345/57347394-18af9b80-718d-11e9-9470-894aad94c76e.png" width="80%">
    
***

ES6 에 도입된 키워드  
**const**는 '한 번 선언하고 바뀌지 않는 값'을 설정 할 때 사용. 반면에, 바뀌게 될 수 있는 값은 **let**을 사용  
기존 자바스크립트의 var와 비슷하지만 작동 방식에 있어서 scope가 다름
- var 은 scope 가 함수단위
- const 와 let 은 scope 가 블록 단위 입니다.

## props와 state
리액트 컴포넌트에서 다루는 데이터 **props & state**
- props는 부모 컴포넌트가 자식 컴포넌트에게 주는 값  
  자식 컴포넌트에서는 props를 받아오기만하고, 받아온 props를 직접 수정 할 수 는 없음!
- state 는 컴포넌트 내부에서 선언하며 내부에서 값을 변경 가능 => 동적인 데이터 

**defaultProps**는 기본값을 설정할 때 사용
static defaultProps = {
  title: '초기 타이틀'
}

## 함수형 컴포넌트
참고 : Functional Component(https://velopert.com/2994)  
React 에서 컴포넌트를 정의 할 때는 보통 EcmaScipt 6 에 도입된 class 문법을 사용  
but,  
state 나 라이프사이클 API 를 전혀 사용하지 않을 때     
그리고 해당 컴포넌트는 자체 기능은 따로 없고 props 가 들어가면 뷰가 나온다는 것을 명시하기 위해 사용

## LifeCycle API


