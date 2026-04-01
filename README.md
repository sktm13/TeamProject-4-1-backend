# Etime Backend API Server

4학년 1학기 심화캡스톤 산학협력 팀프로젝트

팀원  
임유진*, 이진석, 전정민, 이상욱, 박현서, 응웬당퉁 (총 6명)

자문  
아이티존 송정규

---

## 프로젝트 소개

전문가 인증 기반 커뮤니티 서비스

- 관리자 승인 기반 전문가 인증 시스템
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
- 게시글(Post) / 인증 요청(Verify) API 설계 및 개발
- 파일 업로드 및 이미지 관리 로직 구현

---

## Backend 개요

Spring Boot 기반 RESTful API 서버

- JWT 인증 시스템 구현
- Filter 기반 인증 처리 구조
- 게시글 및 인증 요청 도메인 설계

---

## Tech Stack

### Backend
- Java 17
- Spring Boot 3.2.5
- Spring Data JPA
- Spring Security

### Database
- MySQL

### Build Tool
- Gradle

### Libraries
- Querydsl
- Lombok
- Gson
- P6Spy
- Thumbnailator
- JJWT 0.11.5

---

## 주요 기능

### 회원 (Member)
- 이메일 기반 회원 조회
- 사용자 등급(grade / primitiveGrade) 관리
- 포인트 및 인증 상태 관리

---

### 인증 (JWT)
- JWT 기반 인증 시스템
- 사용자 정보 포함 토큰 발급
- Filter 기반 인증 처리

---

### 게시글 (Post)
- 게시글 등록 / 수정 / 삭제
- 게시글 조회 (단건, 리스트)
- 페이징 처리
- 이미지 업로드 및 관리

---

### 인증 요청 (Verify)
- 인증 요청 등록 (이미지 포함)
- 인증 요청 리스트 조회
- 관리자 승인 및 결과 처리

---

### 파일 업로드
- Multipart 파일 업로드
- 파일명 기반 저장 구조
- 썸네일 생성
- 수정 시 기존 파일 정리
