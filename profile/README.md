<img width="1213" height="769" alt="image" src="https://github.com/user-attachments/assets/81492a62-213d-416b-84ff-6d77fecbd4c7" />
실시간 화상 회의와 AI 기반 학습 관리 기능을 제공하는 협업 스터디 플랫폼입니다.

## 레포지토리
### [Frontend](https://github.com/5-re-5/smore-front)
### [Backend](https://github.com/5-re-5/smore-back)
### [AI](https://github.com/5-re-5/smore-ai)

## 🚀 주요 기능

### 📹 실시간 화상 회의

- LiveKit 기반 고품질 비디오/오디오 스트리밍
- 다중 참가자 지원
- 실시간 참가자 관리

### 🤖 AI 기반 자리 비움 감지

- MediaPipe를 활용한 얼굴 인식 기술
- 자동 출석 체크 및 집중도 모니터링
- 학습 효율성 향상

### ⏱️ 학습 도구

- **스톱워치**: 학습 시간 측정 및 관리
- **화이트 노이즈**: 집중력 향상을 위한 배경음 제공
- **마이크 시각화**: 실시간 음성 레벨 표시

### 🎯 스터디 관리

- 개인별 학습 시간 추적
- 그룹 스터디 세션 관리
- 학습 통계 및 분석

### **스터디룸 관리**  
  - 스터디룸 생성, 조회, 수정, 삭제
  - 참여자 초대 및 관리
### **참여자(유저) 관리**  
  - 회원가입 및 로그인  
  - 프로필 관리
### **집중도(포커스) 기록 기능**  
  - 사용자의 집중 시간 기록 및 조회  
  - 일/주/월별 집중도 통계 제공
### **포인트 시스템**  
  - 학습 활동에 따른 포인트 적립 및 차감 기능  
  - 활동 보상 및 리워드 시스템 연동 가능
### **출석 관리 기능**  
  - 스터디룸별 출석 기록 기능 (예: 출석 체크, 지각 등)  
  - 출석 현황 통계 및 리포트 기능 제공

## 🛠️ 기술 스택

- **Frontend**: React 19, TypeScript, Vite
- **Real-time**: LiveKit (WebRTC)
- **AI/ML**: MediaPipe (Face Detection)
- **State**: Zustand, TanStack Query
- **Styling**: Tailwind CSS, shadcn/ui
- **Testing**: Vitest, Testing Library


---
## 📦 Dependencies

| 항목 | 버전/설명 |
|------|-----------|
| **Java** | 17 이상 |
| **Spring Boot** | 3.x (Gradle 기반) |
| **Spring Web** | REST API 개발 |
| **Spring Security** | 인증/인가 처리 |
| **Spring Data JPA** | ORM, 데이터베이스 액세스 |
| **OAuth2 Client** | 소셜 로그인(Kakao 등) |
| **MySQL Driver** | MySQL 연결용 JDBC 드라이버 |
| **Lombok** | 보일러플레이트 코드 감소 |
| **Validation (Jakarta Validation)** | 요청 파라미터 유효성 검사 |
| **Jackson** | JSON 직렬화/역직렬화 |
| **Springdoc OpenAPI** | API 문서화(Swagger UI) |
| **JUnit 5** | 단위/통합 테스트 |
| **Mockito** | 테스트용 Mock 객체 생성 |
| **Redis Client (spring-data-redis)** | 캐싱, 토큰 저장 |
| **Dockerfile** | 컨테이너 빌드/배포 지원 |
