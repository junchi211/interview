# react vs vue.js

> 둘의 차이점은?

1) vue.js는 자료 검색시 중국어 관려 자료가 많았다.
2) pure 싱글 파일 컴퍼넌트 
  <html></html>
  <script></script>
  <style></style>
3) react js
Function(){
render(){
// JSX
}
}
// styled-component
}
4) vue.js
<template></template>
<script></script>
<style scoped></style>

이는 HTML에 익숙한 개발자들이 빠르게 적응 할 수 있다. 
styled component를 사용하지 않으면 스타일시트를 별도의 파일로

5) template /style에서 camel case 가 아니 kebab case 
   컴퍼넌트 이름도 대문자 아닌 kebab-case로 사용
   
> 비슷한점은?
  vue watch = use effect 
  vue slot = props childern
