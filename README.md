# 4학년 1학기 심화캡스톤 산학협력 팀프로젝트 

- 팀원 : 임유진*, 이진석, 전정민, 이상욱, 박현서, 응웬당퉁  총 6명
- 역할 : 팀장, backend
- 자문 : 아이티존 송정규
- 소개
    1. 유저는 관리자 승인을 통해 특정 카테고리에 대한 전문성 등급을 부여받을 수 있다.
    2. 전문가 유저는 해당 카테고리 게시판에 정보전달 등을 통해 유저 피드백(별점, 리뷰)을 받을 수 있다.
    3. 전문가 유저의 유저 피드백 데이터가 내부 기준에 충족할 시 등급을 올릴 수 있다.
    4. 일반 유저는 전문가 유저에게 후원할 수 있다. (PortOne API)
       
- 결과 : 한국정보기술학회 종합학술대회 논문 발표, SW등록

# Backend API Server

Spring Boot 기반 RESTful API 서버  
JWT 인증, 게시글(Post), 인증 요청(Verify) 기능 구현

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
- P6Spy (SQL Logging)  
- Thumbnailator (이미지 썸네일 생성)  
- JJWT 0.11.5  

---

## 주요 기능

### 회원 (Member)
- 이메일 기반 회원 조회  
- 사용자 등급(grade / primitiveGrade) 관리  
- 포인트 및 인증 상태(Verify) 관리  

---

### 인증 (JWT)

- JWT 기반 인증 시스템  
- 사용자 정보 포함 토큰 발급  

---


### 게시글 (Post)

- 게시글 등록 / 수정 / 삭제  
- 게시글 단건 조회  
- 게시글 리스트 조회 (페이징)  
- 이미지 업로드 및 관리  

---

### 인증 요청 (Verify)

- 인증 요청 등록 (이미지 포함)  
- 인증 요청 리스트 조회 (페이징)  
- 인증 승인 / 결과 처리  
- 관리자 승인 구조  

---

### 파일 업로드

- Multipart 파일 업로드 지원  
- 파일명 기반 저장 구조  
- 썸네일 생성 (Thumbnailator)  
