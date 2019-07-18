# TIL

Today I Learned

#### TIL 목표

- 이전부터 TIL 을 하고자 했지만 미루고 미루다보니 생각만 했었습니다.
- 하지만 최근에 js 기반으로 부스트캠프 를 진행하고 있는데 js 입문 상태에서 참석하니 모르는 내용도 많은 뿐더러 부스트캠프 내용 퀄리티가 너무 좋아 js 외적으로도 많이 배워 해당 내용들을 기억하고자 TIL 을 시작합니다.!!

#### 20190715

- multipleGCD 를 처음에는 주어진 배열에 모든 수의 최대공약수를 구해서 O(N^2) 이 걸렸다.  
  하지만 좀 더 고민해보니 제일 작은 수 두 수를 골라 해당 값의 GCD를 구하고 이후에 나누어 떨어지는 수들만 GCD를 구하면 연산속도가 빨라지는 것을 알게되었다.
- git의 동작 방식과 git PL 등
  - git add 를 한 경우 index 파일과 생성된 objects 파일.
  - git commit 의 경우 objects 파일들과 해당 object 파일의 구성요소(tree, parent 등)
- js annotation

```js
/**
 *	@param {number}
 *	@returns {void}
 */
```

#### 20190716

- 로그를 쉽게 찍는 방법

```js
fucntion log(d) {
	console.log(d);
}
log("Hello log Test");
```

- rest parameter
  - rest parameter 사용 방식
  - 처음 사용했던 거라 모든 데이터를 처리할 수 있는줄 알았는데 분리해서 처리 가능

```js
function test(value, ...rest)
```

#### 20190717

##### TIL

- js 입문한지 얼마되지 않아 문제풀기 위한 개념을 빨리 익혀야한다는 생각과 빨리 문제를 풀어야한다는 생각 때문에 개념 공부와 문제에 집중하지 못했음.  
  개념을 확실하게 잡을려고 노력하고 문제 풀이 시간에 대한 압박감을 벗어나도록 약간의 노력하기!

- **배열과 객체 개념**
- **배열 관련 함수 - 추가 학습 필요**
  - foreach()
  - reduce()
  - map()
  - filter()
- **계층적 구조에 접근 방법 - 문제 해결에 필수적인 개념**

  - array 안에 객체가 있는 경우
  - js 문법과 개념 미숙으로 큰 로직은 생각했지만 접근 방법을 고려하지 못함!
  - array 함수의 foreach(), reduce() 함수를 사용 하면 접근 할 수 있음

- **prototype 에 대한 개념**
  - Array.prototype.NAME 은 배열에 새로운 속성을 정의할 수 있음

##### 부족한 부분 및 보완해야할 부분

- callback 함수에 대한 개념
- prototype 개념
- 함수안에 매개변수로 함수를 줄때 접근 방법 및 동작 원리 - 해당 내용 미숙으로 문제 풀이 실패
- Array 내장 함수 동작 원리

> 너무 급하게 생각하지 말고 차근차근 배우며 자신의 것으로 만들자!!
