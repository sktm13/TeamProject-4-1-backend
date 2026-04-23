# Etime Backend API Server

4학년 1학기 심화캡스톤 산학협력 팀프로젝트

팀원  
임유진*, 이진석, 전정민, 이상욱, 박현서, 응웬당퉁 (총 6명)

자문  
아이티존 송정규

---

## 프로젝트 소개

전문가 인증 기반 커뮤니티 서비스

- 관리자 승인을 통한 전문가 인증 시스템
- 사용자 피드백(별점, 리뷰)을 통한 등급 상승 구조
- PortOne 결제 API 기반 후원 기능

---

## 성과

- 한국정보기술학회 종합학술대회 논문 발표
- SW 등록 완료

---

## 역할

- 팀장
- Spring Security + JWT 인증 구조 설계 및 구현
- 회원, 게시글, 인증 요청 API 설계 및 개발
- 파일 업로드 및 이미지 관리 로직 구현

---

## Tech Stack

### Backend
- Java 17
- Spring Boot 3.2.5
- Spring Security + JWT
- Spring Data JPA
- MySQL

### Libraries
- Querydsl
- Thumbnailator

---

## 주요 기능

### 회원 (Member)
- 이메일 기반 회원 조회
- 사용자 등급(grade / primitiveGrade) 관리
- 포인트 및 인증 상태 관리
- Spring Security + JWT(Access/Refresh Token) 기반 인증

---

### 게시글 (Post)
- 게시글 CRUD
- 페이징 처리
- 이미지 업로드 및 썸네일 생성

---

### 인증 요청 (Verify)
- 전문가 인증 요청 CRUD
- 관리자 승인 및 결과 처리

---
<img width="1193" height="634" alt="시연1" src="https://github.com/user-attachments/assets/60adbb64-ec3a-4c72-b966-5a7297f21d22" />
<img width="1195" height="631" alt="시연2" src="https://github.com/user-attachments/assets/ebe67e7c-1674-470f-b374-ae6af5a68a2e" />
<img width="1127" height="626" alt="시연3" src="https://github.com/user-attachments/assets/7419ce81-2b07-4205-859c-e59f6c4faf00" />

