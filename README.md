# 실시간 채팅 애플리케이션

Spring Boot, WebSocket, Vue.js를 사용하여 구축한 실시간 채팅 애플리케이션입니다.

## 주요 기능

- WebSocket을 이용한 실시간 메시징
- JWT를 이용한 사용자 인증
- 개인 및 그룹 채팅방
- 온라인 상태 표시
- 메시지 읽음 확인 기능

## 기술 스택

### 백엔드
- Java 17
- Spring Boot 3.x
- Spring WebSocket
- Spring Security
- Spring Data JPA
- H2 Database (개발용) / MySQL (운영용)
- JSON Web Tokens (JWT)

### 프론트엔드
- Vue.js 3
- Vuex (상태 관리)
- Axios (HTTP 요청)
- SockJS & STOMP (WebSocket 통신)

## 설치 및 실행 방법

### 사전 요구사항
- JDK 17 이상
- Maven 3.6 이상
- Node.js 16 이상 (프론트엔드용)

### 백엔드 설정
1. 저장소 복제
2. 프로젝트 디렉토리로 이동
3. `mvn spring-boot:run` 실행
4. 서버는 로컬 http://localhost:8080에서 기동

### 프론트엔드 설정


## API 문서

