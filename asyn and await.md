# async / await

> async
  - async와 await는 자바스크립트의 비동기 처리 패턴 중 가장 최근에 나온 문법입니다. 
  - promise 를 좀 더 간결하고 동기적으로 보여주게 만들어주는 것이 async await이다. 
  - promise + 추가된 api 가 asynce/await => syntatic sugar
  - 오래 걸리는일들은 비동기적이 처리가 필요한데 그러기위해서 promise 혹은 async await을 쓴다. 
  - ansync function xxx 이렇게 하면 promiseㄹ 변환됨


> 추가설명
  - 자바스크립트에느 비동기 처리를 다룰 수 있는 방법이 여러가지 있다. 주로 callback, promise, async/await 이다. 
  - promise는 자바스크립트에서 비동기처리에 사용되는 객체이다. (내용은 실행되었지만 결과를 아직 반환하지 않으 객체)
  - promise에는 3가지 상태가 있다. pending / fullfilled / rejected. 
  - resolve(true)일때는 then으로 값을 반환받고 / reject(false) 이면 catch로 반환 받는다.
  - 콜백지옥등에 빠지지 않기 위해서 (꼬리에 꼬리를 무는) promise , callback함수 단점을 해소하기 위해 async/await나옴
  - await을 통해 promise반한값을 받아 올 수있다.
  - await는 async안에서만 동작한다. tr-catch통해서 에러르 핸들링해준다.
  - async/await는 비동기 코드가 동기코드처럼 읽힉 해준다. 코드 가독성 업!
