# JSONPlacehplder
Fake online REST API 제공 사이트
   * REST API를 테스트, 프로토 타이핑 가능
   * 사이트 주소: https://jsonplaceholder.typicode.com/
      * Resources, Routes
   * 실습할 내용: GET, POST, PUT, PATCH, DELETE
   * URL의 구성
      * 프로토콜: http, https, file 등
      * 호스트 주소(예시): www.naver.com, www.google.com
      * 파일경로 /home, /index.html
      * Query parameter(예시): ?id=1&postld=1
         * 검색, 필터링, 데이터 교환시 사용 

<br>

# Postman 실습
Postman
   * 리소스 URL필요
   * 개발한 API를 테스트, 테스트 결과를 공유하여 API 개발의 생산성을 높여주는 플랫폼
   * POST를 요청할 때 id가 다름
      * id는 유일해야 하므로 서버에서 임의로 부여해줌.
      * body에 넣어 요청해도 바뀌지 않음
   * 리소스에 없는 필드를 body에 넣어 요청하면 error가 생길 수있다

<br><br>

>[01. 강의에 들어가며](./OT.md)<br>
[02. HTTP, JSON, API](./HTTP_JSON_API.md)