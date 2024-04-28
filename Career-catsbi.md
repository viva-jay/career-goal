# career-goal

# 요구사항
- [x] KYS(Known Your Self)를 작성한다.
    - [x] Key Strength 를 작성한다.
    - [x] Read.me 를 작성한다.
    - [x] Goal을 작성한다.
- [x] 되고싶은 개발자(Goal)가 되기 위한 gap 분석을 한다..
    - [x] Goal 작성 : 위에서 완성된 Goal중 원하는 하나를 선택한다.
    - [x] 필요역량 작성 : 되고싶은 개발자(Goal)가 되기 위해 필요 역량을 작성한다.
    - [x] 나의 상태 작성 : 지금 나는 어떤 역량을 가지고 있는지 작성한다.
    - [x] Gap 분석 : 되고싶은 개발자(Goal)가 되기 위해 가지고 있는 역량과 앞으로 습득해야할 역량을 작성한다.
    - [x] To-Do List : 되고싶은 개발자(Goal)가 되기 위해 어떤 것들이 필요할지 작성한다.


# 예시
## 이름
이한솔
## KYS 작성
### Key Strength
- 개발자로서 본인을 대표할 수 있는 keyword를 3~5개 정도 작성하여 본다. 
- answer: 
    - Java, Kotlin Backend
    - Spring/JPA
    - Spring Batch
    - ATS
    - Share
### Read.me 작성
- Key Strength로 표현된 keyword를 가지고 본인을 소개하는 3~5줄 정도의 Read.me를 작성해 본다.
- answer
    - Java, Kotlin기반의 Spring Boot 환경에서 JPA를 활용하여 회사별 전체 지원자에 대한 채용 관리 솔루션을 개발하였고, Spring Batch를 이용해 대용량 지원자 정보 엑셀 및 PDF 생성및 다운로드 기능을 개발했습니다.
      현재는, 지원서 개편과 서비스 권한 그룹 기능을 개발하고 있습니다.
    - 개발을 좀 더 효과적으로 할 수 있도록 트러블슈팅 및 개발 팁들을 문서화하여 노션 및 컨플루언스를 통해 공유하고 있습니다.

### Goal 설정
- 작성된 read.me로 현재의 자신을 객관적으로 살펴 보고 현실적으로 본인이 되고자하는 개발자로서의 목표를 2~3개 잡아본다.
- answer
  - 동시 2만명 이상의 대규모 공채 지원자 정보를 안정적으로 관리할 수 있는 ATS 시스템을 개발하고 운영한다.
  - 매 년 두 배이상 늘어나는 누적 데이터와 트래픽에도 latency 100ms 이하의 응답성을 제공하고, 데이터의 일관성과 무결성을 보장하는 시스템을 구축할 수 있게 리드하는 개발자
  - (주제가 뚜렷하지 않아 고민되지만 적어봅니다.) 장르를 가리지 않고 개발 주제가 정해지면 빠르게 학습하고 적용해 성공적으로 방향을 제시해줄 수 있는 개발리더
## Gap 분석
### Goal
- 동시 2만명 이상의 대규모 공채 지원자 정보를 안정적으로 관리할 수 있는 ATS 시스템을 개발하고 운영한다.
### 필요역량
- Java 개발역량
- Kotlin 개발 역량
- Spring Boot 역량
- Spring Batch 역량
- Docker 역량
- 데이터 제어및 관리 역량
  - JPA 역량
  - MyBatis 역량
  - NoSQL / Redis 를 이용한 캐싱 및 데이터 관리 능력 
  - 데이터베이스 설계 및 쿼리 튜닝 능력
- 대용량 Transaction을 무결성을 지키면서 처리 할 수 있는 역량
    - bulk transaction 처리
    - partitioning 처리 능력
    - 동시성 제어 관리 역량
    - DB Transaction 역량 : isolation, MySQL
    - Heap Memory 관리
- 시스템 안정성이 높은 아키택쳐 구성
    - SPOF 방지를 위한 아키택쳐 : MSA, 핵사고날, EDA
    - Traffic 처리 : Circuit break, A/B Test, Traffic control
    - 데이터 모니터링 능력 : Kibana, Prometheus, Grafana, Pinpoint
- 안정적인 서비스 제공을 위한 테스트 역량
  - 단위 테스트, 인수 테스트, 통합 테스트, 성능 테스트 역량
  - 테스트 자동화 역량
  
### 나의 상태
- Java 개발역량 
- Kotlin 개발 역량
- Spring Boot 역량
- Spring Batch 역량
- Kafka와 같은 MessageQueue 역량
- Docker 역량 
- 데이터 제어및 관리 역량
  - JPA 역량
  - MyBatis 역량
  - NoSQL / Redis 를 이용한 캐싱 및 데이터 관리 능력
  - 데이터베이스 설계 및 쿼리 튜닝 능력
- 대용량 Transaction을 무결성을 지키면서 처리 할 수 있는 역량
  - bulk transaction 처리
  - partitioning 처리 능력
  - 동시성 제어 관리 역량
  - Heap Memory 관리
- 시스템 안정성이 높은 아키택쳐 구성
  - SPOF 방지를 위한 아키택쳐(MSA, 핵사고날, EDA)  
  - 데이터 모니터링 능력 : Kibana, Pinpoint, Datadog
- 안정적인 서비스 제공을 위한 테스트 역량
  - 단위 테스트, 인수 테스트, 통합 테스트, 성능 테스트 역량

### Gap 분석
- Java 개발역량 : OOP를 이해하고 요구사항을 개발할 능력은 있으나 JDK 버전업에 따른 새로운 기능들을 활용하지 못함.
- Kotlin 개발 역량: 코틀린을 이용한 개발 경험은 있으나, 코틀린의 특징을 활용한 개발은 부족함.
- Spring Boot 역량: Spring Boot의 라이프 사이클을 이해하고 있으며, 순수 자바만 가지고 스프링 프레임워크를 제한적으로 구현할 수 있으나, 스프링 부트의 다양한 기능을 활용하지 못하며 스프링 진영의 다양한 프로젝트들을 활용하지 못함.
- Spring Batch 역량: Spring Batch를 이용한 대용량 데이터 처리를 경험해보았으나, chunk transaction 처리에 대한 이해가 부족함.
- Kafka와 같은 MessageQueue 역량: kafka나 rabbitMQ를 활용해 기능을 개발한 경험은 있고 강의를 통해 학습한적은 있으나 실무에서 트러블슈팅을 해본 적은 없음
- Docker 역량 : 간단한 컨테이너 환경을 구축해본 경험은 있으나, 복잡한 환경에서의 운영 경험이 부족함.
- 데이터 제어및 관리 역량
  - JPA 역량 : JPA + NativeQuery부터 queryDSL, JPQL까지 다양한 방법으로 JPA를 활용한 경험이 있으며 트러블슈팅 경험도 있지만, 성능 최적화 및 쿼리 튜닝 경험이 부족함.
  - MyBatis 역량 : MyBatis-Generator와 xml을 통해 엔티티를 만들고, 필요한 쿼리를 작성한 경험은 있으나 정확한 동작 원리를 이해하고 튜닝해본 경험은 없음.
  - NoSQL / Redis 를 이용한 캐싱 및 데이터 관리 능력 : Redis를 이용한 캐싱을 구현한 경험은 있으나, 실제 Redis 운영환경 스펙에 대한 자세한 정보는 모르며 기본적인 strings타입을 제외하고 써본적이 없음
  - 데이터베이스 설계 및 쿼리 튜닝 능력 : 데이터베이스 설계를 통해 테이블을 만들어본 경험과 튜닝 경험은 있지만 복잡한 쿼리 튜닝 경험이 부족함.
- 대용량 Transaction을 무결성을 지키면서 처리 할 수 있는 역량
  - bulk transaction 처리 : JPA 환경에서 bulk query를 위해 JDBCTemplate을 템플릿화 하여 개발한 경험은 있으나 bulk 의 파티셔닝 사이즈 설정에 필요한 수치를 계산하지 못함
  - partitioning 처리 능력 : 파티셔닝 사이즈를 수치화하지 못하며 적당히 눈대중으로만 하는 수준
  - 동시성 제어 관리 역량 : Transaction의 isolation level을 설명할 수 있고, 전파 레벨(propagation)을 설명할 수 있지만 제대로 사용해본 경험이 없음.
  - Heap Memory 관리 : GC의 종류와 동작원리에 대해 추상적으로 이해하고 있으나 실제로 경험해보거나 부하 테스트를 통해 수치화한적이 없음
- 시스템 안정성이 높은 아키택쳐 구성
  - SPOF 방지를 위한 아키택쳐(MSA, 핵사고날, EDA) : MSA, 헥사고날, EDA와 SAGA패턴등을 강의를 통해 실습해본적은 있으나 실무에서는 파편적인 MSA 사용 경험만 있음.
  - Traffic 처리 : Circuit break, A/B Test, Traffic control: 이론으로만 추상적으로 알고 있으며 경험해본적은 없음.
  - 데이터 모니터링 능력 : Kibana, Prometheus, Grafana, Pinpoint, Datadog: Kibana와 Datadog의 log를 이용해 에러 로그를 확인해본적이 있고, Datadog의 APM을 확인해 리소스 부하나 성능을 확인해본적은 있으나, Prometheus나 Grafana를 이용해 모니터링을 해본적은 없음.
- 안정적인 서비스 제공을 위한 테스트 역량
  - 단위 테스트, 인수 테스트, 통합 테스트, 성능 테스트 역량 : 단위 테스트와 인수 테스트는 리뷰어로 활동하며 실무경험도 있고 리뷰어로 활동하고 있으나 라인커버리지부터 펑션커버리지, 브랜치 커버리지등의 명확한 수치 측정등을 해본적은 없고 IDE의 run with coverage만 사용해본적은 있음.
  - 테스트 자동화 역량 : 별도로 경험해본적은 없으며 QA팀에서 postman을 통한 테스트 자동화를 한다는 얘기만 들어봄

### To-Do List
- Kotlin 학습 심화: 코틀린과 자바의 차이점과 코루틴의 특징 및 장단점 분석 및 학습 후 프로젝트에 적용해본다.
- Spring Boot 역량:
  - Spring Boot Configuration의 속성들을 학습 후 어떤 상황에서 사용될 수 있는지에 대해 학습해본다. 
  - Spring 진영에서 사용해보지 않은 프로젝트들을 사용해보고, 스프링 부트의 다양한 기능들을 활용해본다.
- Spring Batch 역량: Spring Batch의 chunk transaction 처리에 대한 이해를 높이고, 실제로 사용해보며 튜닝해본다.
- Kafka와 같은 MessageQueue 역량: Kafka에서 발생할 수 있는 문제점을 조사해보고 해결방법등을 학습해본다.
- Docker 역량
  - Docker 의 장단점과 사용법을 학습하고 기술 블로그 등을 통해 관련된 트러블 슈팅 경험을 학습한다.
  - 복잡한 환경에서 발생할 수 있는 트러블슈팅 기술 블로그 글들을 찾아 학습한다. 
- 데이터 제어및 관리 역량
  - NoSQL / Redis 를 이용한 캐싱 및 데이터 관리 능력 : Redis 환경을 구축해본다. 
  - 데이터베이스 설계 및 쿼리 튜닝 능력 : MySQL 성능최적화 책과, 인프런 강의를 들은 뒤 정리해서 쿼리에 반영해본다.
- 대용량 Transaction을 무결성을 지키면서 처리 할 수 있는 역량
  - partitioning 처리 능력 강화: 파티셔닝 사이즈를 수치화하는 방법에 대해 학습해본다.
- 시스템 안정성이 높은 아키택쳐 구성
  - Traffic 처리 
    - 동시에 트래픽이 몰리는 경우에 대한 처리 방법들을 조사한 뒤 (ex: 코루틴, 스케일아웃, 캐싱, 코드최적화등...) 각 방식에 대해 학습해본다.
  - 데이터 모니터링 능력
    - 서버의 각 리소스(cpu, memory, disk) 가 사용되는 주된 기능이나 작업들을 확인해보고, 현재 운영중인 서비스의 리소스 사용량을 별도의 툴을 사용하지 않고 확인및 로깅, 분석을 해본다..



