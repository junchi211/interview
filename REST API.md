# REST API

> API (Application Programming Interface)
  - 스프트웨어가 다르 소프트웨어로부터 지정된 형식으로 요청,명령을 받을 수 있느 수단을 API라고한다. 

> REST API
  - REST의 가장 중요한 특성은 각 요청이 어떤 동작이나 정보를 위하 것인지를 그 요청의 모습 자체로 추론이 가능하다!
  - RESTful하게 만드 API는 요청을 보내는 주소만으로도 대략 이게 뭐 하는 요청인 파악이 가능하다.
  - HTTP 규약에 따라 
    1. GET은 데이터를 read, 조회하는데 사용
    2. POST는 Creat, 새로운 정보를 추가하는데 사용 그리고 body에 새로운 정보를 실어서 보낸다.
    3. PUT or Patch를 사용하면 변경된 update될 새 정보들을 body에 보낸다. 
    4. PUT은 정보를 통째로 갈아 끼운다.
    5. PATCH는 일정한 정보만
    6. DELTE는 정보를 지울때
  - URI는 동사가 아닌 명사로 이뤄줘야 한다.
  - 개발자사이에서 널리 지켜주는 양식
