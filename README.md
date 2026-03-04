
<img src="https://github.com/user-attachments/assets/b369071c-3d64-4f57-b8a6-773e9c576610" style="pointer-events: none;" /> 

# 🧑‍💻 About Me
> [📄 포트폴리오(PDF)보기 ](https://github.com/jjsh0208/portfolio/blob/master/%EC%A0%84%EC%8A%B9%ED%98%84%20%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4.pdf)

> **병목을 분석하고 시스템 성능을 개선하는 백엔드 개발자**

대용량 데이터 처리 과정에서 발생하는 병목을 분석하고 시스템 성능을 개선하는 과정에 흥미를 느낍니다.  
티켓팅 서비스 프로젝트에서 Redis Pipeline과 DB IN절을 적용해 10만 건 기준 배치 작업 시간을 **3.8초에서 0.2초로 단축**하며 I/O 병목을 해결한 경험이 있습니다.

Kafka, RabbitMQ 기반의 이벤트 중심 아키텍처와 Redis를 활용한 캐싱 전략을 적용하며 확장성과 안정성을 고려한 백엔드 시스템을 구현해 왔습니다.

단순 기능 구현을 넘어 문제의 원인을 분석하고 구조적으로 해결하는 개발자로 나아가고 있습니다.
<br>

### 🚀 Core Competencies

- **성능 최적화**
  - Redis Pipeline 도입 및 I/O 구조 개선으로 Batch 처리 병목 해결
  - 티켓팅 프로젝트 Batch 작업 성능 **19배 향상** 달성 (3.8s → 0.2s, 95% 단축)

- **분산 아키텍처**
  - Kafka/RabbitMQ 기반 **Event-Driven Architecture 구현 경험**
  - Saga 패턴 적용으로 분산 환경에서 데이터 정합성 보장 및 서비스 간 결합도 완화

- **동시성 제어 및 보안**
  - 비관적 락(Pessimistic Lock)을 활용한 동시성 제어
  - Spring Security & JWT 기반 이중 토큰 인증(Access/Refresh) 시스템 구축

- **DevOps 및 자동화**
  - GitHub Actions Matrix Strategy 기반 멀티 모듈 병렬 빌드 환경 구축
  - Docker Compose & SSH Action을 활용한 CI/CD 배포 파이프라인 자동화

<br><br>

<h1>💡 Projects</h1>

| 프로젝트 명                                       | 설명                                               | 기술 스택                                                                                                                                                                                      | 역할                                                                                                                                                       | 기간                |관련 <br> 링크                      |
| :------------------------------------------- | :----------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------- | :------------------------- |
| 🚀 **공연 및 콘서트 티켓팅 플랫폼**                | 대규모 공연 예매 트래픽을 처리하기 위한 실시간 티켓 예매 백엔드 시스템         | `Java` `Spring Boot` `MySQL` `Redis` `Kafka` `FeignClient` `QueryDSL` `TossPayments API` `Docker` `EC2` `GitHub Actions`                                                                   | - 공연·예매·결제 도메인 API 설계 및 개발<br>- Kafka 기반 비동기 메시징 처리<br>- Redis 캐싱 및 동시성 제어 적용<br>- FeignClient 기반 서비스 간 통신 구현<br>- GitHub Actions + Docker를 이용한 CI/CD 구축 | 2025.04 ~ 2024.05 | [GitHub](https://github.com/jjsh0208/TakenSeat)  |
| 💻 **물류 관리 및 배송 플랫폼**                  | 주문·상품·업체 간 연동되는 물류 관리 및 배송 자동화 시스템               | `Java` `Spring Boot` `PostgreSQL` `Redis` `RabbitMQ` `FeignClient` `QueryDSL` `Gemini API` `Slack API` `Docker`                                                                            | - 주문·상품·업체 간 사가(Saga) 패턴 기반 프로세스 설계<br>- 도메인 REST API 및 메시지 기반 MSA 구조 설계<br>- RabbitMQ 기반 이벤트 처리 구조 설계 및 운영<br>- 이벤트 시퀀스 정리 및 팀 리딩 (팀장)                  | 2025.03   | [GitHub](https://github.com/jjsh0208/b2b-service-platform)               |
| 📦 **배달 주문 백엔드 애플리케이션**                      | 배달 주문 및 회원 인증 기능을 포함한 백엔드 애플리케이션                 | `Java` `Spring Boot`  `Spring Security ` `QueryDSL`  `Swagger (Springdoc OpenAPI)` `PostgreSQL` `H2` `Tomcat 9.0` `JWT` `Docker` `Docker Compose` `nginx` `GitHub Actions` | - USER 도메인 설계 및 인증/인가 로직 구현<br>- JWT 발급 및 재발급 기능 개발<br>- Spring Security 기반 토큰 인증 구조 설계                                                                  | 2025.02  | [GitHub](https://github.com/jjsh0208/delivery)               |
| 🌱 **농촌 체험 기획 및 홍보 영상 제작 지원 플랫폼** | 농가의 체험 등록을 돕고 AI 기반 리브랜딩·추천·홍보 영상 제작을 제공하는 웹 서비스 | `Java` `Spring Boot`  `Elasticsearch` `FastAPI` `OpenAI API` `MySQL` `React` `Docker`                                                             | - 농장 및 체험 도메인 API 설계 및 개발<br>- OpenAI API 연동으로 체험 리브랜딩 및 맞춤형 추천 기능 구현<br>- Elasticsearch 기반 고급 검색 기능 개발                                                  | 2025.08 ~ 2025.10   | [GitHub](https://github.com/Onnongwa/Onnongwa) |

<br><br>

<h1> 🎯 Trouble Shooting </h1>

| 주제 (Topic) | 관련 링크 (Link) |
| :--- | :--- |
| 🚀 **[리뷰 평점]** 성능 최적화 (Query Indexing & Redis Pipeline) | [Blog](https://ddong-kka.tistory.com/61) |
| 🚀 **[MySql]** MySql에서 UUID,Double 타입 처리  | [Blog](https://ddong-kka.tistory.com/38) |
| 🚀 **[Redis 직렬화]** Redis 캐싱 - Jackson LocalDateTime 직렬화 문제 해결 | [Blog](https://ddong-kka.tistory.com/34?category=1164019)  |
| 🚀 **[도메인 설계]** 결제 도메인 트러블슈팅 (책임 분리) | [Blog](https://ddong-kka.tistory.com/36) |
| 💻 **[동시성 제어]** 재고 감소 동시성 제어 (RabbitMQ & 비관적 락) | [Blog](https://ddong-kka.tistory.com/28?category=1164019) |
| 💻 **[Saga Pattern]**  무한 재시도 방지 (Redis 활용) | [Blog](https://ddong-kka.tistory.com/27)|
| 📦 **[Spring MVC]** 데이터 바인딩 순서 (트러블슈팅)| [Blog](https://ddong-kka.tistory.com/6) |
| 🌱 **[Elasticsearch]** '_class' 필드 역직렬화 문제 해결 | [Blog](https://ddong-kka.tistory.com/59) |

<br><br>

<h1>📊 GitHub Statistics</h1>

<div align="center">
  <a href="https://github.com/anuraghazra/github-readme-stats">
    <img height="200" src="https://github-readme-stats.vercel.app/api?username=jjsh0208&theme=vue-dark&icons=true&show_icons=true&title_color=a8edea" />
  </a>
  <a href="https://github.com/anuraghazra/github-readme-stats">
    <img height="200" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jjsh0208&theme=vue-dark&layout=donut" />
  </a>
</div>

<div align="center">
  <a href="https://www.gitanimals.org/en_US?utm_medium=image&utm_source=jjsh0208&utm_content=farm">
    <img src="https://render.gitanimals.org/farms/jjsh0208" width="440" height="280"/>
  </a>
  
  <a href="https://solved.ac/jjssh0208">
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=jjssh0208" alt="Solved.ac Profile"/>
  </a>

</div>

</div>

<h1>🎧 Now Playing</h1>

<div align="center">
  <a href="https://github.com/kittinan/spotify-github-profile">
    <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=317lqwuznnpiobn2fk7lw72ksklq&cover_image=true&theme=novatorem&show_offline=false&background_color=121212&interchange=false&profanity=false&bar_color=e23232&bar_color_cover=true" />
  </a>
</div>
