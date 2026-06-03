<img src="https://github.com/user-attachments/assets/b369071c-3d64-4f57-b8a6-773e9c576610" style="pointer-events: none;" /> 

# 🧾 Portfolio
> [📄 백엔드 엔지니어 포트폴리오(PDF) 보기](https://github.com/jjsh0208/portfolio/blob/master/%EC%A0%84%EC%8A%B9%ED%98%84%20%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4%202026-06-01.pdf)

<br>

<h1>💡 Projects</h1>

| 프로젝트 명 | 핵심 성과 및 담당 역할 | 주요 기술 스택 | 기간 / 링크 |
| :--- | :--- | :--- | :--- |
| 🚀 **Taken Seat**<br>(공연 예매 플랫폼) | **대규모 트래픽 기반의 티켓 예매 시스템 구축**<br>• Redis Pipeline & Bulk Query 도입으로 배치 처리 속도 19배 향상 (3.8s ➡️ 0.2s)<br>• Kafka 기반 비동기 메시징 처리 및 결제 도메인 API 설계 | `Spring Boot` `Redis` `Kafka` `MySQL` | 25.04 - 25.05<br>[🔗 GitHub](https://github.com/jjsh0208/TakenSeat) |
| 💻 **DeliverySquad 10**<br>(B2B 물류/배송 플랫폼) | **MSA 기반 데이터 정합성 보장 및 이벤트 주도 아키텍처 설계**<br>• 파티션 큐와 Redis 분산 락을 도입하여 핫 키 트래픽 격리 (결제 지연 33배 단축)<br>• Saga 패턴을 활용한 서비스 간 분산 트랜잭션 구축 및 멱등성 보장 (팀장) | `Spring Boot` `RabbitMQ` `Redis` `PostgreSQL` | 25.03 - 25.03<br>[🔗 GitHub](https://github.com/jjsh0208/b2b-service-platform) |
| 🌱 **Onnongwa**<br>(농촌 체험/리브랜딩 플랫폼) | **AI 연동 및 검색 엔진 기반 맞춤형 추천 서비스 구축**<br>• OpenAI API를 활용한 체험 리브랜딩 및 사용자 맞춤형 추천 기능 구현<br>• Elasticsearch를 도입하여 복잡한 조건의 농장/체험 도메인 고급 검색 성능 최적화 | `Spring Boot` `Elasticsearch` `OpenAI API` `MySQL` `Docker` | 25.08 - 25.10<br>[🔗 GitHub](https://github.com/Onnongwa/Onnongwa) |
| 📦 **주문의 민족**<br>(배달 주문 플랫폼) | **인증/인가 및 보안을 강화한 백엔드 애플리케이션**<br>• Spring Security와 JWT를 활용한 Access/Refresh 이중 토큰 인증 아키텍처 설계<br>• USER 도메인 안정성 확보 및 GitHub Actions 기반 CI/CD 파이프라인 구축 | `Spring Boot` `Spring Security` `JWT` `Docker` | 25.02 - 25.02<br>[🔗 GitHub](https://github.com/jjsh0208/delivery) |

<br><br>

<h1> 🔥 Core Engineering (Trouble Shooting) </h1>

| 엔지니어링 주제 (Topic) | 주요 내용 및 해결 방안 | 관련 링크 |
| :--- | :--- | :--- |
| ⚡ **[아키텍처 & 동시성]**<br>대규모 트래픽 격리 및 동시성 제어 | RabbitMQ 파티션 큐 분산 라우팅 및 Redis 분산 락(Redisson)을 통한 Hot Key 병목 해소 (일반 결제 지연 234ms ➡️ 7ms 단축) | [Wiki 보기]([https://github.com/DevSquad10/b2b-service-platform/wiki](https://ddong-kka.tistory.com/83)) |
| 🚀 **[데이터베이스]**<br>대용량 데이터 조회 성능 최적화 | 복합 인덱스(Query Indexing) 설계 및 Redis Pipeline을 활용한 쿼리 조회 및 집계 성능 극대화 | [Blog 보기](https://ddong-kka.tistory.com/61) |
| 🔄 **[MSA & 트랜잭션]**<br>Saga Pattern 무한 재시도 방지 | 분산 환경에서 발생하는 트랜잭션 실패 시, Redis 멱등성 키와 DLQ를 활용한 안전한 보상 트랜잭션(Rollback) 파이프라인 구축 | [Blog 보기](https://ddong-kka.tistory.com/27) |
| 🏛️ **[도메인 설계]**<br>결제 시스템 책임 분리 | 결제 프로세스의 비즈니스 복잡도를 낮추기 위한 외부 API 연동 계층과 핵심 도메인 로직의 객체지향적 책임 분리 | [Blog 보기](https://ddong-kka.tistory.com/36) |

<br><br>

<h1>📊 GitHub Statistics</h1>

<div align="center">
  <a href="https://www.gitanimals.org/en_US?utm_medium=image&utm_source=jjsh0208&utm_content=farm">
    <img src="https://render.gitanimals.org/farms/jjsh0208" width="440" height="280"/>
  </a>
  
  <a href="https://solved.ac/jjssh0208">
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=jjssh0208" alt="Solved.ac Profile"/>
  </a>
</div>

<h1>🎧 Now Playing</h1>

<div align="center">
  <a href="https://github.com/kittinan/spotify-github-profile">
    <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=317lqwuznnpiobn2fk7lw72ksklq&cover_image=true&theme=novatorem&show_offline=false&background_color=121212&interchange=false&profanity=false&bar_color=e23232&bar_color_cover=true" />
  </a>
</div>
