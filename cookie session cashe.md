# cookie session cashe

> cookie 

  - cookie는 사이트에 방문할때 브라우저에 저장됨
  - 쿠키는 사용자의 편의를 위한다. (예 자동아이디 입력 로그인x 장바구니 )
  - 그러나 지워지거나 누군가 가져가더라도 큰 문제가 없을 그런 정보들이 브라우져에 저장된다. 

> session
  - 세션아이디가 쿠키에 저장됨
  - 쿠키 저장하기 곤란한거는 세션으로
  - 서버는 임시키를 하나를 브라우저려 보내줌
  - 요청에 키가 담긴 쿠키를 보내줌
  - 서버에서느 세선에 사용자 로그인 정보를 갖고 이게 나임을 증명할 세션아이디가 쿠키보관함에 저장
  - 다른 누군가에 노출되면 안되거나 서비스제공자 직접 관리해야 할 정보들은 세션으로 서버안에 저장
  - 세션을 남발하면 서버에 부하가 걸림

> cashe

  - 가져오는데 비용이 드느 데이터를 한번 가져온뒤에는 임시로 저장하는것 
  - 웹 케쉬느 이미지등을 가져 올때 데이터 사용량도 발생하 시간도 든다. 
  - 한번 방문하 사이트의 데이터를 사용자의 컴퓨터 혹으 중간서버에 저장
