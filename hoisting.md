# Hoisting

> Hoisting 이란?

  - 호이스팅은 어디에 선언했냐에 상관없이 제일 위로 끌어 올려주는 것을 말한다. 
  - 스코프 내부 어디서든 변수 선언은 최상윙 선언되 것 처럼 행동

> var
  - var를 안쓰느 이유는 var는 선언도 하기전에 사용할 수 있다. 
  - var 는 block scope이 없다. 블록안에다 변수를 선언해도 어디에서나 var를 콘솔 찍을 수 있다. 
  - 한번 선언되 변수를 다시 사용 할 수 있다. 
  - 선언하기전에 사용 할 수있다. 
  - 최상위로 끌어 올료준다. 선언으 호이스팅은 되자민 할당은 호이스팅 안됨
  - 함수 스코프

> let (es6)

  - muttable data type 
  - block scope

> const (es6)

  - immutable data type.  보안상 / 다양한 thread들이 값을 변경 못시키게.. / 실수를 줄 일 있다. 
  - block scope

> Tempoeral dead Zone: let 과 hoist는 TDZ영향을 받음 그래서 let 과 const가 호이스팅은 되지만 에러가 뜨는 이유임.
