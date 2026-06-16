# 👨‍💻 안녕하세요! 문제의 본질을 파고드는 개발자 최성보입니다.

단순한 기능 구현을 넘어, **'데이터 확장성'**과 **'시스템 안정성'**을 고려한 견고한 아키텍처 설계에 관심이 많습니다. 프레임워크의 코어 동작 원리를 깊이 학습하고, 이를 바탕으로 발생 가능한 서버 부하와 예외 상황을 선제적으로 제어하는 것을 즐깁니다.

## 🛠 Tech Stack

### Backend
* [cite_start]**Java**: 코딩 테스트 및 Spring 서버 개발에 주력으로 사용합니다. [cite: 248]
* [cite_start]**Spring Framework**: DI와 AOP의 핵심 원리를 이해하며, 유지보수가 용이한 RESTful API 서버를 구축합니다. [cite: 249]
* [cite_start]**JPA / MyBatis**: 영속성 컨텍스트의 동작 원리를 이해하여 객체 지향적인 도메인 모델을 설계하고 [cite: 255][cite_start], 필요에 따라 MyBatis를 활용해 DAO를 구축합니다. [cite: 277]
* [cite_start]**C++**: 메모리 관리와 포인터 개념, 객체지향 프로그래밍에 대한 높은 이해도를 보유하고 있습니다. [cite: 250, 251]

### Database
* [cite_start]**MySQL / PostgreSQL**: 관계형 데이터베이스의 핵심 원리를 바탕으로 ERD 모델링 및 제3정규화(3NF)를 수행할 수 있습니다. [cite: 251, 252]
* [cite_start]**Redis**: TTL 기능을 활용한 안전한 인증 체계를 구축한 경험이 있습니다. [cite: 278]

### DevOps & Infra
* [cite_start]**Docker / Docker Compose**: 컨테이너 기술을 활용해 개발 환경을 격리하고, 다중 컨테이너(서버, DB, 캐시) 환경을 유기적으로 구성할 수 있습니다. [cite: 253, 254]

---

## 🚀 Projects

### 💳 카드까득 (Card GGaduek)
[cite_start]**사용자 맞춤형 카드 추천 및 위치 기반 주변 가맹점 조회 서비스** [cite: 272]
* [cite_start]**기간/인원:** 2025.05 ~ 2025.08 (5인 팀 프로젝트) [cite: 271]
* [cite_start]**역할:** 풀스택 개발자 (인증/인가, 외부 API 연동, 글로벌 예외 처리 구축) [cite: 275]
* [cite_start]**기술 스택:** Spring Framework, MyBatis, Vue, MySQL, Redis [cite: 273]
* **주요 성과 및 구현 사항:**
  * [cite_start]**보안 및 인증 아키텍처 구축:** Spring Security와 Custom FilterChain을 활용해 JWT 기반의 Stateless 인증 로직을 구현했습니다. [cite: 280] [cite_start]또한 Redis TTL을 활용해 안전한 이메일 인증을 도입하고 [cite: 278][cite_start], OAuth 2.0 (Naver) 기반 소셜 로그인 및 데이터베이스 동기화를 처리했습니다. [cite: 279]
  * [cite_start]**글로벌 공통 예외 처리:** `@ControllerAdvice`와 `@ExceptionHandler`를 도입해 횡단 관심사인 예외 처리 로직을 전역으로 분리하여 비즈니스 로직의 응집도를 높였습니다. [cite: 283]
  * [cite_start]**외부 데이터 융합:** 구글 Places API를 연동해 수집한 실시간 가맹점 정보를 내부 DB의 카드 혜택 정보와 유기적으로 매핑하여 사용자에게 시각화해 제공했습니다. [cite: 281, 282, 284]
* [cite_start]**Link:** [GitHub Repository](https://github.com/cseongbo/cardGGaduekMainServiceBackend) [cite: 285]

<br>

### ✈️ TripPlannerZ
[cite_start]**다중 목적지 최단 경로 계산을 지원하는 여행 일정 조율 종합 서비스** [cite: 260]
* [cite_start]**기간/인원:** 2023.03 ~ 2023.11 (3인 팀 프로젝트) [cite: 258]
* [cite_start]**역할:** 백엔드 개발자 (경로 추천 알고리즘, DB 설계, REST API 개발) [cite: 262]
* [cite_start]**기술 스택:** Spring Framework, JPA, React, PostgreSQL, Redis [cite: 261]
* **주요 성과 및 구현 사항:**
  * [cite_start]**알고리즘 최적화를 통한 성능 개선:** 다중 목적지 선택 시 기존 완전 탐색 알고리즘에서 발생하던 연산량 폭발 문제를 인지하고, **'유전 알고리즘(Genetic Algorithm)'**을 새롭게 도입하여 탐색 효율성과 서버 성능을 획기적으로 개선했습니다. [cite: 265]
  * [cite_start]**데이터베이스 정규화:** 회원(Member)과 여행 동행 그룹(Party) 간의 복잡한 다대다(N:M) 관계를 중간 연결 테이블(MemberParty)로 설계해 DB 부하를 예방하고 무결성을 확보했습니다. [cite: 266]
  * [cite_start]**JPA ORM 도입:** 영속성 컨텍스트 기반의 데이터 관리 아키텍처를 구축했습니다. [cite: 264]
* [cite_start]**Link:** [GitHub Repository](https://github.com/cseongbo/Tripplannerz) [cite: 268]

---

## 📚 Education & Certification
* [cite_start]**SSAFY (삼성 청년 SW 아카데미):** 알고리즘 훈련, 백엔드/프론트엔드 아키텍처 심화 학습 (2026.01 ~ 이수 중) [cite: 237]
* [cite_start]**KB IT's Your Life:** 풀스택 개발 및 금융 IT 도메인 실무 프로젝트 수행 (2025.03 ~ 2025.08) [cite: 236]
* [cite_start]**정보처리기사** (2023.11 취득) [cite: 242]
