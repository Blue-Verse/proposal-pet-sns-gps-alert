# AI 기반 반려동물 SNS 및 GPS 실종 알림 앱 기능 고도화 — 제안 분석 로그

> 생성일: 2026-03-13
> 공고 URL: https://www.wishket.com/project/153500/

## 1. 공고 파싱 결과

```yaml
job:
  title: "AI 기반 반려동물 SNS 및 GPS 실종 알림 앱 기능 고도화"
  category: "모바일 앱 (Android/iOS), AI, 데이터 분석"
  budget_range: "45,000,000원 (금액 조율 가능)"
  duration: "150일"
  tech_stack:
    - FlutterFlow
    - Firebase
    - AI Vision API
    - LLM API
    - 추가 백엔드 자유 제안
  description: "반려동물 전용 SNS이자 위치 기반 실종 알림 서비스의 핵심 기능을 추가 개발하여 서비스 완성도를 높이는 프로젝트"
  requirements:
    - "AI Vision 이미지 필터링 (사람 사진 블라인드 처리)"
    - "AI 호소문 자동 완성 (LLM API 연동)"
    - "GPS 기반 대량 푸시 알림 (반경 5km)"
    - "포인트 시스템 백엔드 (적립/차감/정산)"
    - "관리자 페이지 (회원관리, 실종알림, 가맹점, 통계)"
  client_questions: []
  deadline: "2026-03-22"
  job_post_url: "https://www.wishket.com/project/153500/"
  urls: []
  images: []
```

## 2. URL/이미지 분석

참고 URL/이미지 없음.

공고 본문에 포함된 참고 자료: `개발사_견적_요청 (1).docx` (15.86 KB) — 위시켓 플랫폼에서 다운로드 불가하여 분석 생략.

## 3. 실현 가능성 분석 (내부용)

- **프로젝트 유형**: 모바일 앱 (Flutter) + AI + 풀스택 → "조건부 가능" (+20% 버퍼)
- **기본 공수 (AI 미반영)**: 107 M/D
  - 기획/설계: 20 M/D
  - 앱 FE (FlutterFlow 커스텀): 18 M/D
  - 백엔드: 31 M/D
  - 관리자 페이지: 23 M/D
  - QA/배포: 15 M/D
- **AI 반영 공수 (45-55% 절감)**: 52 M/D
  - 기획/설계 (35% 절감): 15 M/D
  - 앱 FE (55% 절감): 8 M/D
  - 백엔드 (55% 절감): 14 M/D
  - 관리자 웹 (65% 절감): 8 M/D
  - QA/배포 (55% 절감): 7 M/D
- **버퍼 20% 적용**: 63 M/D
- **달력 일수**: 63 ÷ 1 × (7/5) = 89일
- **클라이언트 예상 기간**: 150일
- **판정**: 산정 기간(89일) < 클라이언트 기간(150일) → 클라이언트 기간 그대로 사용

## 4. 포트폴리오 매칭

| 순위 | 프로젝트 | 매칭 점수 | 근거 |
|------|---------|----------|------|
| 1 | Harmony Link | 95/100 | Flutter + AI(OpenAI) + FCM 푸시 + 관리자 대시보드 + 멀티플랫폼 — 기술 스택/기능 완전 대응 |
| 2 | Calendar Share | 85/100 | Flutter + Firebase + SNS 구조 + 7종 FCM 푸시 — SNS + 푸시 알림 직접 유사 |
| 3 | Fortune App | 80/100 | Flutter + Firebase + 포인트/리워드 시스템 — 포인트 시스템 + 크로스플랫폼 유사 |

## 5. 최종 제안 요약

- **지원 금액**: 4,050만원 (45,000,000 × 90%, VAT 별도)
- **지원 기간**: 150일
- **핵심 제안 포인트**:
  1. Firebase 생태계 활용 극대화 (Cloud Functions 기반 서버리스)
  2. AI 기능 서버 측 분리로 유연한 고도화 가능
  3. GeoHash + FCM Batch 기반 안정적 대량 푸시
  4. 정부지원사업 서류 첨부용 상세 견적/기술 구현 방안 포함

## 6. 최종 산출물

### 제안서 사이트 URL
https://proposal-pet-sns-gps-alert.pages.dev/

### 지원 금액
4,050만원

### 지원 기간
150일

### 클라이언트 질문 답변
없음

### 지원 내용

안녕하세요, AI 기반 반려동물 SNS 및 GPS 실종 알림 앱 기능 고도화 프로젝트에 지원합니다.

본 프로젝트에 대한 상세 제안서(견적서, 공수계산서, PRD, 일정, 포트폴리오)를 별도 페이지로 준비하였습니다. 아래 링크에서 확인해 주시면 감사하겠습니다.
▶ 제안서 상세 페이지: https://proposal-pet-sns-gps-alert.pages.dev/
▶ 위시켓 포트폴리오: https://www.wishket.com/partners/p/blueverse1/

---

<프로젝트 진행 제안>

■ 프로젝트 분석
- FlutterFlow + Firebase 기존 환경 위에 AI Vision 이미지 필터링, LLM 호소문 자동생성, GPS 기반 대량 푸시 알림, 포인트 시스템, 관리자 페이지를 추가 개발하는 프로젝트로 파악하였습니다.
- 기존 앱 코드베이스를 유지하면서 Cloud Functions(Node.js) 기반 서버리스 백엔드를 추가하여, 별도 서버 관리 부담 없이 AI/푸시/포인트 핵심 기능을 구현하는 방향을 제안드립니다.
- 예비창업패키지 서류 심사에 활용 가능한 상세 견적서와 기술적 구현 방안을 본 제안서에 포함하였습니다.

■ 작업 일정

[Phase 1: 기획/설계/디자인] Day 1–35 (5주)
- 기존 FlutterFlow + Firebase 환경 분석, 요구사항 상세화
- DB 스키마 설계, API 명세서 작성
- 관리자 페이지 UI/UX 디자인 (Figma)
- 산출물: 요구사항 정의서, DB ERD, API 명세서, Figma 디자인

[Phase 2: 핵심 백엔드 & AI 기능] Day 36–80 (6.5주)
- AI Vision 이미지 필터링 서버 (Google Cloud Vision API)
- LLM 호소문 자동생성 서버 (OpenAI API)
- GPS 기반 대량 푸시 알림 서버 (GeoHash + FCM Batch)
- 포인트 시스템 백엔드 (적립/차감/정산)
- 산출물: API 서버 배포, AI 기능 동작 데모

[Phase 3: 앱 기능 연동] Day 81–105 (3.5주)
- FlutterFlow 커스텀 코드 개발
- AI Vision, 호소문, GPS 알림, 포인트 UI 연동
- 산출물: 앱 알파 빌드

[Phase 4: 관리자 페이지 개발] Day 106–135 (4주)
- Next.js 기반 웹 관리자 페이지 구축
- 회원 관리, 실종 알림 관리, 가맹점 정산, 통계 대시보드
- 산출물: 관리자 페이지 베타 배포

[Phase 5: QA/배포/문서화] Day 136–150 (2주)
- 통합 테스트 & 버그 수정
- 운영 환경 배포, 개발 문서 작성
- 산출물: 최종 빌드, 소스 코드, 문서 일체

■ 마일스톤 및 산출물
- M1 (Day 35): 설계 문서 승인
- M2 (Day 80): 백엔드 & AI 기능 데모
- M3 (Day 105): 앱 알파 빌드 테스트
- M4 (Day 135): 관리자 페이지 완료
- M5 (Day 150): 최종 인수 및 소스 코드 이관

■ 미팅 시 협의 필요 사항
- 기존 FlutterFlow 프로젝트 코드베이스 공유 및 접근 권한
- AI API 선택 (Google Cloud Vision vs 대안, OpenAI vs 대안)
- 포인트 시스템 상세 정책 (적립 기준, 만료 정책, 정산 주기)
- 가맹점 정산 프로세스 상세 (정산 주기, 수수료 등)
- 월 단위 유지보수 범위 및 조건
- 정부지원사업 선정 후 프로젝트 착수 일정 확정

---

<유사 프로젝트 진행 경험>

▶ Harmony Link — 시니어 주간보호 관리 플랫폼 (약 6개월)
- 프로젝트 유형: B2B SaaS / 헬스케어 / 멀티플랫폼
- 핵심 기능: AI 건강분석(OpenAI), FCM 실시간 푸시, 웹 관리자 대시보드, 멀티플랫폼
- 유사점: AI API 연동, FCM 푸시 알림, 관리자 대시보드, Flutter + Firebase 풀스택
- 기술 스택: Flutter, NestJS, Next.js, Firebase, OpenAI API, AWS CDK

▶ Calendar Share — 소셜 캘린더 공유 플랫폼 (MVP)
- 프로젝트 유형: B2C 앱 / 소셜 네트워킹
- 핵심 기능: 소셜 피드, 7종 FCM 푸시 알림, QR 소셜 디스커버리
- 유사점: SNS 플랫폼 구조, 다양한 이벤트별 FCM 푸시, Flutter + Firebase 서버리스
- 기술 스택: Flutter, Firebase, Supabase, FCM

▶ Fortune App — 사주 기반 운세 앱 (3개월)
- 프로젝트 유형: B2C 앱 / 엔터테인먼트
- 핵심 기능: 포인트 & 리워드 시스템, Firebase 풀 통합, 3개월 풀패키지 딜리버리
- 유사점: 포인트/리워드 시스템, Flutter + Firebase 동일 스택, 빠른 딜리버리 경험
- 기술 스택: Flutter, Firebase, BLoC, Node.js

---

<사용 기술과 툴>

▶ 개발 기술
- 앱: FlutterFlow (기존 환경 유지) + Flutter 커스텀 코드
- 백엔드: Firebase Cloud Functions (Node.js/TypeScript)
- 관리자 페이지: Next.js + React + TypeScript
- AI: Google Cloud Vision API, OpenAI API
- 푸시: Firebase Cloud Messaging (FCM)
- DB: Firestore (기존) + Cloud SQL (PostgreSQL, 포인트/정산)
- 공간 인덱싱: GeoHash

▶ 개발 도구 및 인프라
- 버전 관리: GitHub
- CI/CD: GitHub Actions
- 클라우드: Google Cloud Platform (Firebase 생태계)
- 디자인: Figma

▶ 커뮤니케이션
- 일일 진행 공유: Slack 또는 카카오톡
- 주간 미팅: Zoom / Google Meet
- 문서 공유: Notion 또는 Google Docs
- 이슈 트래킹: GitHub Issues

### 관련 포트폴리오 추천
1. **Harmony Link** — Flutter + AI(OpenAI) + FCM 푸시 + 관리자 대시보드
2. **Calendar Share** — Flutter + Firebase + SNS 플랫폼 + 7종 푸시 알림
3. **Fortune App** — Flutter + Firebase + 포인트/리워드 시스템
