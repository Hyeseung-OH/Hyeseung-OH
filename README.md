<div align="center">

# 👋 안녕하세요, 오혜승입니다

### Backend Engineer who asks "Why?"

기술 선택과 아키텍처 설계에서 항상 "**왜?**"를 질문하고,  
트레이드오프를 고려한 의사결정 과정을 문서화하는 백엔드 개발자입니다.

단순한 기능 구현을 넘어 **유지보수성과 확장성**을 고려한 설계를 지향하며,  
병목을 중심으로 시스템을 분석·개선하고  
그 과정과 판단 근거를 문서로 남기는 데에 강점이 있습니다.

> "작동하는 코드"보다 "왜 이 방식을 선택했는지 설명할 수 있는 코드"를 목표로 개발합니다.

<br />

[![Velog Badge](https://img.shields.io/badge/Tech%20Blog-20C997?style=for-the-badge&logo=Velog&logoColor=white)](https://velog.io/@behyeppy/posts)
[![Gmail Badge](https://img.shields.io/badge/Contact-EA4335?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:hyesiness@gmail.com)

</div>

<br />

## 🛠 Tech Stack

### Language
<p>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
</p>

### Framework & Library
<p>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white" />
  <img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
</p>

### Database & Cache
<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
</p>

### Infrastructure & DevOps
<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white" />
</p>

### Tools & Collaboration
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" />
  <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" />
  <img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" />
</p>

<br />

## 🚀 Projects

### 📮 Dear.___ – 시간·공간 기반 타임캡슐 서비스
> **2025.12 - 2026.01 (5주)** | 백엔드 팀장 / 사용자 인증·인가, 동시성 제어, 보안 아키텍처
<details>
<summary>📋 상세 정보</summary>

**핵심 성과**
- 트랜잭션 최적화 + 비동기 병렬 처리로 응답 시간 96.1% 단축 (30,989ms → 1,208ms)
- Redisson 분산 락 도입으로 선착순 캡슐 응답 56.3% 개선, 에러율 52% → 0%
- GPS 스푸핑·시간 조작 방어 시스템 (4계층 방어 + 6단계 이동 속도 검증)

**담당 기능**
- JWT 기반 Access Token(쿠키) + Refresh Token(Redis) 인증 구조 설계
- AES-256, SHA-256 전화번호 암호화 및 Bcrypt 비밀번호 해싱
- Redis 분산 락을 활용한 선착순 캡슐 동시성 제어
- GPS 기반 이상 접근 탐지 및 Redis 점진적 제재 시스템 (50점 쿨다운 → 100점 계정 정지/IP 차단)
- 회원, 인증, 캡슐, 북마크 도메인 계층 분리 및 ERD 설계 주도

**기술 스택**
- Backend: Java 21, Spring Boot, JPA, Redis(Redisson), Resilience4j
- External API: OpenAI, 솔라피(SMS), Google OAuth
- Test: JMeter, K6, JUnit5
- Infra: AWS EC2, S3, RDS, Nginx, Docker

</details>

[![GitHub](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/prgrms-web-devcourse-final-project/WEB7_9_FullChamZal_BE)
[![Velog](https://img.shields.io/badge/Blog-20C997?style=flat-square&logo=Velog&logoColor=white)](https://velog.io/@behyeppy/series/%EB%8D%B0%EB%B8%8C%EC%BD%94%EC%8A%A4-4%EC%B0%A8-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8)
[![Live](https://img.shields.io/badge/Live-4285F4?style=flat-square&logo=google-chrome&logoColor=white)](https://web.dear4u.cloud/)

<br />

### 📊 PortfolioIQ – GitHub 저장소 품질 분석 서비스
> **2025.10 - 2025.11 (3주 + 1주)** | 백엔드 팀장 / Analysis, Repository 도메인 전담
<details>
<summary>📋 상세 정보</summary>

**핵심 성과**
- GitHub REST API 7개 엔드포인트 연동 + OpenAI API 통합 분석 파이프라인 구축
- SSE 실시간 진행 상황 전달 + Redis 분산 락으로 중복 분석 차단
- Java → Kotlin 마이그레이션 주도, Null Safety 활용으로 코드 라인 약 20% 감소

**담당 기능**
- GitHub REST API → 데이터 가공 → OpenAI 분석 → 결과 저장 전체 흐름 설계
- SSE(Server-Sent Events) 기반 실시간 진행 상황 스트리밍
- 인메모리 락(ConcurrentHashMap) → 분산 락으로 동일 Repository 중복 분석 방지
- Spring Retry로 GitHub API 일시적 장애 대응
- 6가지 평가 카테고리 설계 (유지보수성, 문서화, 보안, 테스트, CI/CD, 커뮤니티)

**기술 스택**
- Backend: Java 21 → Kotlin, Spring Boot, Redis
- External API: GitHub REST API, OpenAI API
- Test: K6
- Infra: Docker, Railway, Vercel

</details>

[![GitHub (Java)](https://img.shields.io/badge/Repository_(Java)-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/prgrms-be-devcourse/NBE7-9-2-Team08)
[![GitHub (Kotlin)](https://img.shields.io/badge/Repository_(Kotlin)-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/prgrms-be-devcourse/NBE7-9-3-Team08)
[![Velog](https://img.shields.io/badge/Blog-20C997?style=flat-square&logo=Velog&logoColor=white)](https://velog.io/@behyeppy/series/%EB%8D%B0%EB%B8%8C%EC%BD%94%EC%8A%A4-2%EC%B0%A8-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8)
[![Velog](https://img.shields.io/badge/Blog-20C997?style=flat-square&logo=Velog&logoColor=white)](https://velog.io/@behyeppy/series/%EB%8D%B0%EB%B8%8C%EC%BD%94%EC%8A%A4-3%EC%B0%A8-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8)
[![Live](https://img.shields.io/badge/Live-4285F4?style=flat-square&logo=google-chrome&logoColor=white)](https://nbe-7-9-3-team08.vercel.app/)

<br />

### ☕ Grids & Circles – 원두 패키지 주문 사이트
> **2025.09 (1주)** | 백엔드 팀장 / Payment 도메인 담당

<details>
<summary>📋 상세 정보</summary>
  
**핵심 성과**
- 디자인 패턴(전략, 팩토리, 상태) 적용 + Spring Retry 재시도 메커니즘
- 낙관적 락 + 유니크 제약 2중 방어로 중복 결제 차단
  
**담당 기능**
- Payment 도메인 전체 설계 및 구현
- Spring Retry 기반 재시도 메커니즘 구현

**기술 스택**
- Backend: Java 21, Spring Boot 3.5.6, JPA, MySQL, Spring Retry
- Test: JUnit5, ExecutorService (동시성 테스트)

</details>

[![GitHub](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Hyeseung-OH/NBE7-9-1-Team04-refactoring)
[![Velog](https://img.shields.io/badge/Blog-20C997?style=flat-square&logo=Velog&logoColor=white)](https://velog.io/@behyeppy/series/%EB%8D%B0%EB%B8%8C%EC%BD%94%EC%8A%A4)

<br />
