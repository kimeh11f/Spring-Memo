### HTTP Request
- Request Line : 
  - HTTP메서드 방식 및 요청 URL과 프로토콜 정보  
  ```
  [HTTP METHOD(POST)] [URL(/--/--)] [PROTOCOL/VERSIONH (HTTP/1.1)]  
  ```  
- Request Header : 
  - 웹브라우저정보, 언어, 인코딩 방식, 요청 서버 정보 등과 같은 추가 정보  
  ```
  [USER-AGENT : MOZILLA/4.0] [CONTENT-TYPE : APPLICATION/X-WWW-FORM-RLENCODED] [ACCEPT-LANGUAGE : KO] ...  
  ```  
- Request Body  
  - 요청에 필요한 내용. 일반적으로 HTML 폼 태그 안에 입력된 값들인 파라미터 정보를 의미  


### HTTP Response  
- Status Line : 
  - 응답상태코드 및 프로토콜 정보를 갖는다.  주요상태코드 (200:OK, 404:NOT FOUND, 500:Internal Server Error]
  ```
  [PROTOCOL/VERSION (HTTP/1.1)] [상태코드(200)] [설명(OK)]  
  ```
- Response Header : 
  - 응답처리 날짜, 인코딩 방식, 요청 서버 정보 등과 같은 추가정보를 갖는다.  
  ```
  [CONTENT-TYPE : TEXT/HTML] [DATE : MON, 27, FEB 2006] [SERVER: APACHE-COYOTE/1.1] ...  
  ```
- Response Body : 
  - 응답에 필요한 내용을 갖는다. 일반적으로 HTML 문서이다.  
  ```html
  <HTML><HEAD><TITLE></TITLE></HEAD><BODY></BODY></HTML>
  ```
 