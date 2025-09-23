# 🚀 Udacity 풀스택 웹개발자 과정 학습 저장소

## 📖 과정 소개

Udacity 풀스택 웹개발자 나노디그리 과정을 수강하며 학습한 내용을 정리한 저장소입니다.

<br />

## 🎯 학습 목표

- 프론트엔드 개발 (HTML, CSS, JavaScript)
- 백엔드 개발 (Node.js, Express, 데이터베이스)
- 배포 및 DevOps 기초
- 풀스택 웹 애플리케이션 구축

<br />

## 📁 저장소 구조

```
udacity-fullstack-web-dev/
├── 📚 notes/              # 강의 노트 정리
├── 💻 projects/           # 프로젝트 소스코드
├── 📝 exercises/          # 실습 및 연습문제
└── 📎 resources/          # 참고자료 및 유용한 링크
```

<br />

## 📚 강의 노트

### 코스 1: 프로그램 소개

- [풀스택 웹 개발자 나노디그리 프로그램에 오신 것을 환영합니다](./notes/01-program-intro/welcome.md)

### 코스 2: 웹용 SQL 및 데이터 모델링

- [강사 인터뷰](./notes/02-web-sql/instructor-interview.md)
- [강의 소개](./notes/02-web-sql/course-intro.md)
- [데이터베이스의 상호 작용](./notes/02-web-sql/database-interaction.md)
- [SQLAlchemy 기본 개념](./notes/02-web-sql/sqlalchemy-basics.md)
- [SQLAlchemy ORM에 대한 심층 수업](./notes/02-web-sql/sqlalchemy-orm-deep-dive.md)
- [마이그레이션](./notes/02-web-sql/migration.md)
- [Build a CRUD App with SQLAlchemy - Part 1](./notes/02-web-sql/crud-app-part1.md)
- [SQLAlchemy ORM으로 CRUD 앱 구축하기 - 파트 2](./notes/02-web-sql/crud-app-part2.md)
- **프로젝트: Fyyur**

### 코스 3: API 개발 및 문서화

- [API 입문](./notes/03-api-dev/api-intro.md)
- [HTTP 및 Flask 기본 개념](./notes/03-api-dev/http-flask-basics.md)
- [엔드포인트 및 페이로드](./notes/03-api-dev/endpoints-payloads.md)
- [API 테스트](./notes/03-api-dev/api-testing.md)
- [API 문서화](./notes/03-api-dev/api-documentation.md)
- **프로젝트: Trivia API**

### 코스 4: ID 액세스 관리

- [기초](./notes/04-identity-access/basics.md)
- [ID 및 인증](./notes/04-identity-access/id-authentication.md)
- [패스워드](./notes/04-identity-access/passwords.md)
- [액세스 및 권한 부여](./notes/04-identity-access/access-authorization.md)
- [공격자 입장에서 생각하기](./notes/04-identity-access/attacker-perspective.md)
- **프로젝트: 커피 좀 스택**

### 코스 5: 서버 배포 및 컨테이너화

- [소개](./notes/05-deployment/intro.md)
- [컨테이너](./notes/05-deployment/containers.md)
- [AWS와 Kubernetes](./notes/05-deployment/aws-kubernetes.md)
- [CI/CD를 사용한 배포](./notes/05-deployment/cicd-deployment.md)
- **프로젝트: EKS를 사용하여 Kubernetes에 Flask 앱 배포하기**

### 코스 6: 풀스택 캡스톤

- [캡스톤 준비 및 배포 옵션](./notes/06-capstone/preparation-deployment.md)
- **프로젝트: 캡스톤**

### 코스 7: 진로 서비스

- **프로젝트: 30분 동안 LinkedIn 개선하기**
- **프로젝트: 이력서 리뷰**

<br />

## 💻 주요 프로젝트

### 1. 프로젝트: Fyyur (음악 공연 예약 사이트)

- **기술스택**: Python, Flask, SQLAlchemy, PostgreSQL
- **폴더**: [project-1-fyyur](./projects/project-1-fyyur/)
- **설명**: 아티스트와 공연장을 연결하는 음악 공연 예약 플랫폼
- **데모**: [Live Demo](#)

### 2. 프로젝트: Trivia API

- **기술스택**: Python, Flask, RESTful API, 테스트
- **폴더**: [project-2-trivia-api](./projects/project-2-trivia-api/)
- **설명**: 퀴즈 게임을 위한 RESTful API 개발 및 문서화
- **데모**: [Live Demo](#)

### 3. 프로젝트: 커피 좀 스택 (Coffee Shop)

- **기술스택**: Python, Flask, Auth0, JWT, RBAC
- **폴더**: [project-3-coffee-shop](./projects/project-3-coffee-shop/)
- **설명**: 역할 기반 액세스 제어를 구현한 커피숍 메뉴 관리 시스템

### 4. 프로젝트: EKS를 사용하여 Kubernetes에 Flask 앱 배포하기

- **기술스택**: Docker, Kubernetes, AWS EKS, CI/CD
- **폴더**: [project-4-kubernetes-deployment](./projects/project-4-kubernetes-deployment/)
- **설명**: Docker 컨테이너화 및 Kubernetes 클러스터 배포

### 5. 프로젝트: 캡스톤

- **기술스택**: 전체 풀스택 기술 활용
- **폴더**: [project-5-capstone](./projects/project-5-capstone/)
- **설명**: 모든 학습 내용을 종합한 최종 프로젝트

### 6. 진로 서비스 프로젝트

- **LinkedIn 프로필 개선**: [linkedin-optimization](./career/linkedin-optimization/)
- **이력서 리뷰**: [resume-review](./career/resume-review/)

<br />

## 🛠️ 사용 기술

### Backend & API

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)

### Database

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

### Authentication & Security

![Auth0](https://img.shields.io/badge/Auth0-EB5424?style=flat-square&logo=auth0&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=json-web-tokens&logoColor=white)

### DevOps & Deployment

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)

### Tools & Testing

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![unittest](https://img.shields.io/badge/unittest-3776AB?style=flat-square&logo=python&logoColor=white)

<br />

## 📈 학습 진도

- [x] **코스 1**: 프로그램 소개
- [ ] **코스 2**: 웹용 SQL 및 데이터 모델링
  - [ ] SQLAlchemy 기본 개념
  - [ ] 데이터베이스 모델링
  - [ ] CRUD 애플리케이션 구축
  - [ ] 프로젝트: Fyyur
- [ ] **코스 3**: API 개발 및 문서화
  - [ ] RESTful API 설계
  - [ ] Flask API 개발
  - [ ] API 테스트 및 문서화
  - [ ] 프로젝트: Trivia API
- [ ] **코스 4**: ID 액세스 관리
  - [ ] 인증 및 권한 부여
  - [ ] JWT 토큰 관리
  - [ ] 보안 모범 사례
  - [ ] 프로젝트: 커피 좀 스택
- [ ] **코스 5**: 서버 배포 및 컨테이너화
  - [ ] Docker 컨테이너화
  - [ ] Kubernetes 오케스트레이션
  - [ ] AWS 클라우드 배포
  - [ ] CI/CD 파이프라인
  - [ ] 프로젝트: Kubernetes 배포
- [ ] **코스 6**: 풀스택 캡스톤
  - [ ] 최종 프로젝트 설계
  - [ ] 풀스택 애플리케이션 구현
- [ ] **코스 7**: 진로 서비스
  - [ ] LinkedIn 프로필 최적화
  - [ ] 이력서 검토 및 개선
