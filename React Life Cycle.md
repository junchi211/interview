# React life cycle 관련 정리
 
> 기본 순서 
1.  constructor →  render → componentDidMount → (fetch완료) → (setState) → render → componentDidUpdate → componentWillUpdate  

> 각 메소드들은 언제 사용하는가?
1. **constructor**: ```constructor ``` 는 컴포넌트의 생성자 매서드 입니다. 컴퍼넌트가 만들어지면 가장 먼저 실행되는 매서드 입니다. 
2. **render**: 컴퍼넌트를 렌더링하는 매서드 입니다. 
3. **componentDidMount**: 컴퍼넌트의 첫번째 렌더링이 마치고 나면 호출되는 매서드입니다. 
4. **componentDidUpdate**: 리렌더링을 끝내고, 화면에 우리가 원하는 변화가 모두 반영되고 난뒤 호출 되는 매서드 입니다. 
5. **componentWillUnmount**: 컴퍼넌트가 화면에서 사라지기 직전에 호출 됩니다. 여기서는 주로 DOM에 직접 등록했었던 이벤트를 제거하고, 만약 setTimeout을 걸어 놓은 것이 있다면 clearTimeout을 통하여 제거 해줍니다. 

> 라이프사이클 중 써본 메소드가 뭐가 있는지?
1. constructor 
2. render
3. componentDidMount
4. componentWillUnmount

> react의 setState를 왜 사용하는지
1. ```setState```는  컴퍼넌트의 state 객체에 대한 업데이트를 실행합니다. 이후 컴퍼넌트는 리렌더링 됩니다. 
