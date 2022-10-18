# GraphQL과 타입스크립트로 개발하는 웹 서비스

본 저장소는 GraphQL과 타입스크립트로 개발하는 웹 서비스: 설계부터 개발·배포까지 따라 하며 완성하는 웹 풀스택 개발 도서의 예제 프로젝트 코드가 담겨있는 저장소입니다.

[프로젝트 저장소 사용 방법](./how-to-use.md)에서 이 저장소를 어떻게 사용할 지에 대한 내용을 간략히 담았습니다. 질문 또는 오류 및 오타 제보등은 [이슈 게시판](https://github.com/hwasurr/graphql-book-fullstack-project/issues)을 활용해주세요.

## 책 소개

<img width="280px" src="./assets/graphql_book_signage.jpg" alt="GraphQL과 타입스크립트로 개발하는 웹 서비스 표지">

- 제목: GraphQL과 타입스크립트로 개발하는 웹 서비스
- 부제: 설계부터 개발·배포까지 따라 하며 완성하는 웹 풀스택 개발
- 출간일: 2022년 10월 14일
- 페이지 수: 360쪽

### 간략 책 소개

지브리 영화 명장면에 ‘좋아요’와 ‘감상평’을 남기는 웹 서비스를  
GraphQL과 타입스크립트로 개발해 보자!

GraphQL은 효과적인 API를 제공하기 위한 쿼리 언어이며 런타임 및 도구이다. 클라이언트/서버 구조의 중간자로서 양측에 공유되는 추상화된 데이터 명세 계층을 제시한다. 여러 글로벌 기업에서 GraphQL을 적극적으로 활용하고 있으며 국내 기업에서도 기존 또는 신규 프로젝트에 도입하는 사례가 많아지고 있다. 또한 GraphQL은 특정 언어나 플랫폼에 종속적이지 않아 지속해서 관련 프레임워크, 라이브러리, 서비스가 생산되고 있다.

이 책은 스튜디오 지브리 영화의 명장면 감상평 서비스를 함께 구현하면서 GraphQL을 자연스럽게 익힐 수 있도록 구성되어 있다. 백엔드 스키마 설계부터 프런트엔드 화면 구성과 서비스 배포에 이르기까지 순차적으로 따라 하며 하나의 웹 서비스를 개발해 볼 수 있다. 이 책에서 배운 내용을 바탕으로 본인이 원하는 주제의 웹 서비스를 개발해 보자.

## 온라인 서점 링크

1. [예스24](http://www.yes24.com/Product/Goods/114635182)
2. [교보문고](https://product.kyobobook.co.kr/detail/S000200019862)
3. [알라딘](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=302978770&start=slayer)
4. [영풍문고](https://www.ypbooks.co.kr/book.yp?bookcd=101198108)

## 출판사 리뷰

웹 서비스를 직접 만들며 배우는 GraphQL

이 책은 단순한 이론 설명이 아닌 지브리 영화를 주제로 한 웹 서비스를 만들어 보면서 GraphQL에 대해 설명하여 재밌게 배울 수 있고 실무에도 유익하다. 기초 지식부터 단계별로 상세하게 설명하기 때문에 GraphQL을 처음 접하더라도 쉽게 이해하며 따라 해볼 수 있다. 백엔드부터 프런트엔드까지 직접 개발 및 배포한 경험을 바탕으로 여러분이 원하는 웹 서비스를 개발해 볼 수 있길 바란다.

이 책은 다음과 같이 구성되어 있다. 1장에서는 웹 개발의 역사부터 시작하여 GraphQL 탄생과 명세, REST와 GraphQL의 차이점, GraphQL이 해결할 수 있는 문제에 대해 알아본다. 2장에서는 Node.js + 타입스크립트 환경에서의 GraphQL 개발 생태계에 대해 알아본다. 3장부터는 함께 서비스를 구성하기 시작한다. Docker를 통해 Redis, MySQL을 구성하고 Node.js 개발 환경을 구성한다. 4장에서는 영화 목록에 대한 데이터베이스 모델과 GraphQL 스키마를 설계하고 쿼리를 통해 데이터를 불러오는 과정을 알아본다. 5장에서는 회원가입과 로그인, 감상평과 좋아요 기능을 구현하며 뮤테이션을 통해데이터를 조작하는 과정을 알아본다. 6장에서는 알림 기능을 구현하며 GraphQL을 통한 파일 업로드 방식에 대해 알아본다. 7장에서는 구현한 서비스를 AWS의 Beanstalk, S3를 통해 배포하는 과정을 진행한다.

## 저자 소개

[강화수](https://github.com/hwasurr)

끝없는 성장을 목표하는 개발자다. 언제나 배움에 목말라하며 새로운 지식을 탐구하는 것과 성장하는 것에 즐거움을 느낀다. 작은 스타트업의 공동 창업자로 커리어를 시작했다. 그리고 개발팀의 리더로 설계, 프로젝트 관리, 백엔드/프런트엔드 개발, 인프라 구성 및 배포, 자동화에 이르기까지 서비스를 구성하기 위한 다양한 업무를 수행했다. 주로 Node.js, 타입스크립트, NestJS, React, GraphQL, Deno 등에 관심이 있다.

- [블로그](https://hwasurr.io)
- [이메일](mailto:iamsupermazinga@gmail.com)
