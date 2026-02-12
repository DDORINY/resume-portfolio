# Resume-Portfolio

Backend Developer Portfolio — Python · Flask · MySQL  
구조 중심 설계와 Service Layer 아키텍처를 기반으로 한 프로젝트 포트폴리오입니다.

단순 기능 구현이 아니라  
**도메인 모델링 → 계층 분리 → DB 설계 → 재사용 구조화**를 중심으로 개발합니다.

---

# Core Focus

- Python OOP 기반 도메인 모델 설계
- Flask 웹 애플리케이션 구조화
- Service / Repository 계층 분리
- MySQL 데이터 모델링 및 관계 설계
- Role 기반 권한 처리
- CRUD → 모듈화 → 아키텍처 확장
- CLI → Web 확장 가능한 구조 설계

---

# Main Projects

## LMS Management System (Team Project)

Python + Flask + MySQL 기반 학습관리 시스템

**Architecture**

- Controller / Service / Repository 분리
- Service Layer 중심 비즈니스 로직
- DB 연결 모듈 분리
- Role 기반 접근 제어
- 모듈화 CRUD 구조

**Features**

- 회원 관리
- 로그인 / 세션 인증
- 성적 관리
- 게시판
- 상품 관리
- 관리자 기능

🔗 https://github.com/lms-mini-project/lms-team-project

---

## TODO Flask App (Mini Project)

사용자별 Todo 관리 서비스

**Technical Points**

- Service Layer 적용
- DAO 패턴 기반 DB 접근
- Soft Delete 처리
- 사용자별 데이터 분리
- 단건 조회 API 설계

🔗 https://github.com/DDORINY/MiniProject-ToDoList

Preview

| Login | Dashboard |
|------|-----------|
| ![](https://raw.githubusercontent.com/DDORINY/MiniProject-ToDoList/main/docs/images/login.png) | ![](https://raw.githubusercontent.com/DDORINY/MiniProject-ToDoList/main/docs/images/dashboard.png) |

---

## LMS Flask Mini Project (Personal)

Service Layer 구조를 유지하면서  
LMS 기능을 Flask 웹 애플리케이션으로 재구성한 개인 확장 프로젝트입니다.

CLI 기반 구조 → Web 구조로 전환하며  
Blueprint 라우트 분리 + Repository 계층 + 템플릿 UI 연결을 실습했습니다.


**Key Points**

- Flask Blueprint 라우트 분리
- Service / Repository 계층 구조
- 회원 기능 웹화
- 게시판 + 파일 업로드
- Session 기반 인증
- DB 모듈 분리
- 구조 재사용 중심 설계

🔗 Repository  
https://github.com/DDORINY/MyMiniProjects_lms_flask

---

# Frontend UI Portfolio

Bootstrap 기반 UI Template + Design System 구조 실습 저장소

- UI Samples + UI Kit 문서화
- Component / Pattern 분리
- v1 / v2 Variant 구조
- Design Token 기반 스타일 구조

🔗 https://github.com/DDORINY/Frontend-ui-portfolio

Preview

![](https://raw.githubusercontent.com/DDORINY/Frontend-ui-portfolio/main/assets/img/previews/auth-login-v1.png)

---

# Architecture Approach

프로젝트는 다음 계층 구조를 기준으로 설계합니다.
```
Controller
↓
Service (Business Logic)
↓
Repository / DAO
↓
Database
```

원칙:

- 비즈니스 로직은 Service Layer에 집중
- DB 접근은 Repository/DAO 분리
- Domain 모델 중심 설계
- 기능 단위 모듈화
- 테스트 및 확장 고려 구조

---

# Tech Stack

## Language
- Python
- SQL
- JavaScript (Basic)

## Backend
- Flask
- Blueprint 구조
- REST 스타일 API 설계
- Session 인증 처리
- Service Layer 패턴

## Database

- MySQL
- ERD 설계
- JOIN / 집계 쿼리
- CRUD 최적화
- 트랜잭션 처리 기초

## Frontend

- HTML5
- CSS3
- Bootstrap 5

---

# Study Repositories

Python Study  
https://github.com/DDORINY/study-PythonStudy26

Database Study  
https://github.com/DDORINY/study-DataBase26

Frontend Study  
https://github.com/DDORINY/study-Front-End-Study26

---

# Design & Engineering Principles

- 구조 중심 설계
- Service Layer 우선
- DB 모델 → 코드 구조 연결
- 재사용 가능한 모듈 지향
- 실행 가능한 프로젝트만 포트폴리오 포함
- 버전 확장 가능한 설계

---

# Roadmap

- [x] Flask LMS 구조 설계
- [x] Service Layer 프로젝트
- [x] UI Design System 레포 구축
- [ ] 인증 API 서버
- [ ] 게시판 시스템 고도화
- [ ] API 명세 문서화
- [ ] ERD 공개 문서화

---

# Run Guide (Flask Projects)

- git clone <repo_url>
- cd project
- python -m venv venv
- venv\Scripts\activate
- pip install -r requirements.txt
- flask run

DB 연결 정보는 config 또는 .env에 설정

---

# Contact

GitHub  
https://github.com/DDORINY

---

Python · Flask · MySQL Backend Developer Portfolio


