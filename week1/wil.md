백엔드 스터디 1주차
=============
# SQL
데이터 베이스 관리하는 표준 언어

# Lombok
이해한 것: 자주쓰이는 기능을 Annotation(@)을 통해 빠르게 생성
효과: 어떤 기능이 있는지 빠르게 읽히고 생성할 때도 한줄이면 되서 편함

SDK(Software Development Kit, SDK)
개발 키트

프로토콜과 HTTP
=============
클라이언트-서버
(요청자) - (응답자)

프로토콜: 네트워크 속 정보전달(요청 및 응답) 규칙
웹은 HTTP 프로토콜 사용

HTTP 프로토콜 규칙
HTTP Method: 데이터에게 수행할 동작
URL(Uniform Resource Location): 데이터 위치
ex) 클라이언트의 요청: GET https://www.gdschongik.com
서버의 응답: <html> gdschongik code<html>

메서드 종류
GET 가져오기(조회)
POST 게시하기(생성)
PUT  교체하기(수정) #put이랑 patch차이?
PATCH 수정하기(수정)
DELETE 삭제하기(삭제)

URL 구조
https://www.gdschongik.com/25-1/backend-study/subject/week1-1
프로토콜//      서버주소          /서버 내 데이터 위치
https://www.gdschongik.com/{username}/backend-study/subject/week1-1
{매개변수}(path parameter)
.com/post/search?page=1&keyboard=hello
= domain(서버주소)/path(데이터위치)/Query string

HTTP 데이터는 헤더와 바디로 나뉨
HTTP헤더: 통신에 대한 정보(언제, 누가, 어떤 작업을(HTTP method), 요청경로 등)
HTTP바디: 주고 받으려는 데이터(보통 json)


![img.png](img.png)