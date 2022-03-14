
### 강의 유튜브 주소
https://www.youtube.com/watch?v=akbdsrOpQ60&list=PLRx0vPvlEmdAezo0wkmUdT6WBCch0_1ie&index=1

### 학습 정리

#### Swagger란?
API 명세를 도와주는 도구

서버 개발자가 API를 만들어서 클라이언트에게 전달해주는 방법은 다양하다.

흔히 엑셀파일 등으로 작성해서 알려줄 수 있다.

다만 이런식으로 작업하면 문서 관리가 어렵다.

엑셀파일 같은 경우에는 깃을 가지고 관리하기 편하지 않다.

이렇게 개발자들의 소통을 위해서 다양한 Tool들이 존재한다.

#### Swagger가 필요한 대상 ?
Swagger API의 경우 1개월~2개월 이상 협업하는 경우에 매우 좋은 도구라고 할 수 있다.

개발자가 3명이상 되어도 API명세를 위한 도구는 필요하다.

개발자에게 깃과 같이 기본이 되는 도구이다.

단발성 프로젝트인 경우에는 굳이 사용하지 않을 수도 있다.

#### Swagger의 장점
Swagger API가 좋은 점은 문서 자체에 API를 테스트 할 수 있는 환경이 잘 갖추어져 있다.

즉 웹문서 형태로 누구든지 암호만 알고 있으면 Swagger API명세를 확인 할 수 있고, 실제로 서버로 그 API 테스트 패킷을 보내서 API가 잘 동작하는지 확인 또한 할 수 있다.

특정한 프로그램에 존재하는 API기능을 명세하고 API기능을 바로 테스트 해볼 수 있는 도구이다.

백엔드 포로그램과 프론트엔드 프로그램 사이에서 정확히 어떠한 방식으로 데이터를 주고 받을 지에 대한 명세를 도와준다.

#### Swagger Hub
Swagger Hub은 스웨거 기능을 제공해주고 있는 공식 사이트다. https://swagger.io/tools/swaggerhub/

스웨거 허브를 이용해서 API명세를 이용할 수도 있고, 자체적인 서버에서 스웨거 모듈을 탑재해서 API를 명세 할수 있다.

스웨거 같은 경우는 yml 형식을 사용해서 문서를 작성할 수 있도록 도와준다.

#### Open API

REST API를 위한 표준 API 명세 규격을 의미한다.

https://github.com/OAI/OpenAPI-Specification

요청, 응답, API접근 경로를 포함해서 전체 API 명세를 어떻게 하면 되는 지 그 방법을 규정하고 있다.

Open API는 yml 형식 json 형식을 지원한다.

스웨거는 기본적으로 REST API를 채택한다.

서비스를 마이크로하게 개발하는 구조에 잘 어울린다.

#### 스웨거를 이용하는 방법
스웨거를 이용하는 방법은 크게 2가지 방식으로 많이 이용한다.

1. 특정한 서버 프로그래밍 언어를 이용해서 스웨거를 종속적인 형태로 이용하는 방식
    1. 흔히 스프링으로 어노테이션을 붙여서 API를 명세한다.
    2. swagger-ui : https://github.com/swagger-api/swagger-ui
    3. 설치형 swagger-ui
2. 특정한 서버 프로그래밍 언어를 전혀 거치지 않고 스웨거 API를 별도의 웹문서로 완전히 빼내서 독립적으로 이용하는 방식
    1. yml문서를 작성해서 API를 명세한다.
    2. swagger hub : [https://support.smartbear.com/swaggerhub/docs/tutorials/index.html](https://support.smartbear.com/swaggerhub/docs/tutorials/index.html)