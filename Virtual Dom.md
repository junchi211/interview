# Virtual DOM (Document Object Model)

> what is DOM
  - DOM은 HTML 고 자바스크립트르 이어주는 공간으로, 내가 작성한 HTML을 자바스크립트가 이해할 수 있도록 객체 (object)로 변환 하느 것이다. 
  - DOM의 작동원리는 
    1) 브라우저가 HTML을 전달 받으면 이를 변환 (parsing)하고 노드들로 이루어진 DOM 트리를 만든다. 
    2) css 파일 고 스타일 파싱하여 스타일을 입힌 render 트리를 만든다.  그후 페인팅 메서드르 호출하면 구현 하고 싶은 화면일 출력
      <img src ="https://user-images.githubusercontent.com/78121571/125720766-804deafe-93e0-4c57-a870-998cd6bbbf90.png">
  - 하지만 현대의 대부분의 웹사이트는 수십 혹으 수백개 되느 페이지로 구성. 마이너한 오타/ 오류를 잡기 위해 전체 사이트를 다시 처음부터 렌더링 하는 것은 비효율! 이를 위해 virtual dom 나옴
 
 > Hola! Virtual DOM
  - virtual DOM은 수정사항이 여러거지 있더라도, 가상 DOM은 한번만 랜더링을 일으킨다.
  - 아래의 그림처럼 빨간 부분에 수정사항이 생겼으면, 가상 DOM이 달라진 값을 탐지하여 변경하고 최종적인 결과 물으 실제 DOM 에 전달한다. 
    <img src ="https://user-images.githubusercontent.com/78121571/125721511-6e17caa4-f56c-4595-a393-d6af68fbd88a.png">
