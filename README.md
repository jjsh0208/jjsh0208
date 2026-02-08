
<img src="https://github.com/user-attachments/assets/b369071c-3d64-4f57-b8a6-773e9c576610" style="pointer-events: none;" /> 

# 🧑‍💻 About Me
> [📄 포트폴리오(PDF)](https://github.com/jjsh0208/portfolio/blob/master/%EC%A0%84%EC%8A%B9%ED%98%84%20%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4.pdf)

> **기술적 분석을 바탕으로 병목을 해결하고, 최적의 구조를 설계하는 백엔드 개발자 전승현입니다.**

10만 건의 대용량 데이터를 처리하면서, Redis와 DB 간 반복적인 I/O가 병목임을 파악하고, Redis 파이프라인과 SQL IN절을 적용해 처리 속도를 3.8초에서 0.2초로 단축한 경험이 있습니다.

반복되는 비효율을 자동화하고, 안정적인 시스템 구조를 설계하는 데서 개발의 가치를 느낍니다.  단순 구현을 넘어서 ‘왜’와 ‘어떻게’를 끊임없이 고민하는 개발자로 성장하겠습니다.

문제 해결 과정에서 혼자만의 접근보다는 팀원들과 소통하며 다양한 시야를 얻는 것을 중요하게 생각합니다.  비록 채택되지 않은 의견이라 하더라도 문서화하여 지식을 나누고, 팀의 성장에 기여하는 개발자가 되고자 합니다.
<br>

### 🚀 Core Competencies

- **성능 최적화**
  - Redis Pipeline 도입 및 I/O 구조 개선으로 대규모 트래픽 처리에 최적화
  - 티켓팅 프로젝트 Batch 작업 성능 **19배 향상** 달성 ($3.8s \rightarrow 0.2s$, 95% 단축)

- **분산 아키텍처**
  - Kafka/RabbitMQ 기반의 **Event-Driven Architecture** 설계
  - Saga 패턴을 적용하여 분산 환경에서의 데이터 정합성 보장 및 결합도 해소

- **데이터 무관성 및 보안**
  - 비관적 락(Pessimistic Lock)을 활용한 동시성 제어 
  - Spring Security & JWT 기반의 이중 토큰 인증(Refresh/Access) 체계 구축

- **DevOps 및 자동화**
  - GitHub Actions Matrix Strategy를 활용한 멀티 모듈 병렬 빌드 환경 구축
  - Docker Compose & SSH Action 연동으로 원격 배포 파이프라인(CI/CD) 자동화

<br><br>

<h1>💡 Projects</h1>

| 프로젝트 명                                       | 설명                                               | 기술 스택                                                                                                                                                                                      | 역할                                                                                                                                                       | 기간                |관련 <br> 링크                      |
| :------------------------------------------- | :----------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------- | :------------------------- |
| 🚀 **공연 티켓 실시간 예매 시스템**                | 대규모 공연 예매 트래픽을 처리하기 위한 실시간 티켓 예매 백엔드 시스템         | `Java` `Spring Boot` `MySQL` `Redis` `Kafka` `FeignClient` `QueryDSL` `TossPayments API` `Docker` `EC2` `GitHub Actions`                                                                   | - 공연·예매·결제 도메인 API 설계 및 개발<br>- Kafka 기반 비동기 메시징 처리<br>- Redis 캐싱 및 동시성 제어 적용<br>- FeignClient 기반 서비스 간 통신 구현<br>- GitHub Actions + Docker를 이용한 CI/CD 구축 | 2025.04 ~ 2024.05 | [GitHub](https://github.com/jjsh0208/TakenSeat)  |
| 💻 **물류 관리 및 배송 시스템**                  | 주문·상품·업체 간 연동되는 물류 관리 및 배송 자동화 시스템               | `Java` `Spring Boot` `PostgreSQL` `Redis` `RabbitMQ` `FeignClient` `QueryDSL` `Gemini API` `Slack API` `Docker`                                                                            | - 주문·상품·업체 간 사가(Saga) 패턴 기반 프로세스 설계<br>- 도메인 REST API 및 메시지 기반 MSA 구조 설계<br>- RabbitMQ 기반 이벤트 처리 구조 설계 및 운영<br>- 이벤트 시퀀스 정리 및 팀 리딩 (팀장)                  | 2025.03   | [GitHub](https://github.com/jjsh0208/b2b-service-platform)               |
| 📦 **배달 주문 백엔드 애플리케이션**                      | 배달 주문 및 회원 인증 기능을 포함한 백엔드 애플리케이션                 | `Java` `Spring Boot`  `Spring Security ` `QueryDSL`  `Swagger (Springdoc OpenAPI)` `PostgreSQL` `H2` `Tomcat 9.0` `JWT` `Docker` `Docker Compose` `nginx` `GitHub Actions` | - USER 도메인 설계 및 인증/인가 로직 구현<br>- JWT 발급 및 재발급 기능 개발<br>- Spring Security 기반 토큰 인증 구조 설계                                                                  | 2025.02  | [GitHub](https://github.com/jjsh0208/delivery)               |
| 🌱 **농촌 체험 기획 및 홍보 영상 제작 지원 플랫폼** | 농가의 체험 등록을 돕고 AI 기반 리브랜딩·추천·홍보 영상 제작을 제공하는 웹 서비스 | `Java` `Spring Boot`  `Elasticsearch` `FastAPI` `OpenAI API` `MySQL` `React` `Docker`                                                             | - 농장 및 체험 도메인 API 설계 및 개발<br>- OpenAI API 연동으로 체험 리브랜딩 및 맞춤형 추천 기능 구현<br>- Elasticsearch 기반 고급 검색 기능 개발                                                  | 2025.08 ~ 2025.10   | [GitHub](https://github.com/Onnongwa/Onnongwa) |

<br><br>

<h1> 🎯 Trouble Shooting </h1>

| 주제 (Topic) | 관련 링크 (Link) |
| :--- | :--- |
| 🚀 **[리뷰 평점]** 성능 최적화 (Query Indexing & Redis Pipeline) |[QueryIndexing 및 RedisPipline 도입](https://github.com/toolatebro/TakenSeat/wiki/%5BPerformance-Testing%5D-%EC%8A%B9%ED%98%84-%E2%80%90-%EB%A6%AC%EB%B7%B0-%ED%8F%89%EC%A0%90-%EA%B0%B1%EC%8B%A0%EC%9D%84-%EC%9C%84%ED%95%9C-Redis-%ED%8C%8C%EC%9D%B4%ED%94%84%EB%9D%BC%EC%9D%B8-%EB%B0%8F-%EC%BF%BC%EB%A6%AC-%EC%9D%B8%EB%8D%B1%EC%8B%B1-%EC%84%B1%EB%8A%A5-%EA%B0%9C%EC%84%A0)<br> [기존 성능 측정](https://github.com/toolatebro/TakenSeat/wiki/%5BPerformance-Testing%5D-%EC%8A%B9%ED%98%84-%E2%80%90-%EB%A6%AC%EB%B7%B0-%EB%B3%80%EA%B2%BD-%EA%B0%90%EC%A7%80-%EA%B8%B0%EB%B0%98-%ED%8F%89%EC%A0%90-%EC%BA%90%EC%8B%B1-%EA%B0%B1%EC%8B%A0-%EA%B8%B0%EB%8A%A5%EC%9D%98-%EC%B2%98%EB%A6%AC-%EC%84%B1%EB%8A%A5-%EC%B8%A1%EC%A0%95)<br> [리뷰 변경 감지 기반 평점 갱신](https://github.com/toolatebro/TakenSeat/wiki/%5BPerformance-Testing%5D-%EC%8A%B9%ED%98%84-%E2%80%90-%EB%A6%AC%EB%B7%B0-%EB%B3%80%EA%B2%BD-%EA%B0%90%EC%A7%80-%EA%B8%B0%EB%B0%98-%ED%8F%89%EC%A0%90-%EC%BA%90%EC%8B%B1-%EA%B0%B1%EC%8B%A0-%EA%B8%B0%EB%8A%A5%EC%9D%98-%EC%B2%98%EB%A6%AC-%EC%84%B1%EB%8A%A5-%EC%B8%A1%EC%A0%95) <br> [잘못된 TPS 지표 탈피와 N+1 문제 해결 (19배 성능 향상)](https://ddong-kka.tistory.com/61) |
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
