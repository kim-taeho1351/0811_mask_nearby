# HTTPS
**H**yper **T**ext **T**ransfer **P**rotocol

<br>

>Hyper Text<br>
참조를 통해 한 문서에서 관련된 다른문서들로 넘나들며 원하는 정보를 얻을 수 있게 해주는 텍스트<br>
예시: 유튜브 추천 영상

>Transfer Protocol<br>
인터넷을 통해서 정보를 주고받을 때 지켜야하는 규칙

<br>

### HTTPS의 구성
   * Request 요청 & Response 응답

<br>

### HTTPS의 요청 메소드
   * **GET**  URL에 표시된 리소스를 가져오기 (읽기)
      * URL: 리소스에 찾아가는 주소
   * **POST**  body에 정보를 담아 서버에 입력 (쓰기)
   * **PUT**  URL에 표시된 리소스와 바꿔 치기 (수정)
   * **PATCH**  PUT과 다르게 일부만 수정 (수정)
   * **DELETE**  URL에 표시된 특정 리소스를 삭제 (삭제)  

<br>

# JSON
**J**ava **S**cript **O**bject **N**otation

<br>

* 데이터 표현 방식
* Key : Value 형식
* 데이터 교환
   * JSON 형식을 자주 사용
   * 이전에는 XML이라는 형식을 사용했었다.

<br>

### JSON의 특징
* 기존 XML보다 가볍다.
* 많은 프로그래밍 언어가 지원힌다.
* 전송 시: 직렬화 과정을 거친다.
   * 직렬화: object형식(원 객체) -> string형식(연속적인 데이터 형식)
* 수신 시: 역직렬화 과정을 거친다. 
   * 역직렬화: string형식 -> object형식

<br>

# API
**A**pplication **P**rogramming **I**nterface<br>
어플리케이션의 프로그래밍 인터페이스를 제공<br>
마치 TV의 리모컨

<br>

### API의 종류
* **SOAP**
* **REST**
* **GraphQL**

<br>

**REST**
   * **R** **E**presentational **S**tate **T**ransfer
   * 하나의 아키텍처이다.
      * 소프트웨어 아키텍쳐: 소프트웨어를 설계하는 지침과 원칙 (완전히 지켜지지 않기도 함)
   * REST의 구성요소
      * 자원
         * URL에 매칭된 리소스들
         * 예시: GET **/likelion/member/8th/list**
      * 행위
         * HTTP 요청 메소드
         * 예시: **GET**/likelion/member/8th/list
      * 표현
         * JSON형식
         * 예시: { "members" : ["김멋사", ... , "허멋사"] }

<br><br>

>[01. 강의에 들어가며](./OT.md)<br>
[03. REST API, Postman 실습](./REST_API&Postman.md)