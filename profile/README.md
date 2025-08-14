# AI 이력서 평가 및 적성 검사 시스템

**MatchingFit** 은 멋쟁이사자처럼 부트캠프 수강생의 이력서를 AI가 분석하여 역량 기반 정량 평가 및 인사담당자의 성향에 맞는 인재 추천 시스템 입니다.

<br/>

## 👥 팀원 소개

 | 배민서 | 권태윤 | 김명수 | 윤지수 |
 |:--------:|:--------:|:--------:|:--------:|
 | <img src="https://github.com/minseoBae.png" alt="배민서" width="150"> | <img src="https://github.com/Kwon-TaeYun.png" alt="권태윤" width="150"> | <img src="https://github.com/Kim-ms527.png" alt="김명수" width="150"> | <img src="https://github.com/yoonmallang22.png" alt="윤지수" width="150"> |
 | BE | BE | BE | FE |
 | 팀장 | 팀원 | 팀원 | 팀원 |
 | [GitHub](https://github.com/minseoBae) | [GitHub](https://github.com/Kwon-TaeYun) | [GitHub](https://github.com/Kim-ms527) | [GitHub](https://github.com/yoonmallang22) | 

<br/>

---

<br/>

## 📸 UI 스크린샷

- 이력서 분석

![이력서분석](https://github.com/user-attachments/assets/4a23b77c-eba5-4958-b3dc-7e44774466e0)

- HR 담당자 성향 테스트

![HR담당자성향테스트](https://github.com/user-attachments/assets/c4ba9189-23f6-4dc4-a399-57f06f8b2f9b)

- 로그인 & 회원가입

![로그인_로그아웃](https://github.com/user-attachments/assets/e1a1401e-333f-4865-ac14-b68b8757f237)

<br/>

---

<br/>

## 🛠️ 주요 기능

- **사용자**: 이력서 업로드 및 분석 기능, 이력서 분석 결과 및 PDF 다운 이력서 매칭 될 경우 메일 알림
- **인사담당자**: HR 성향테스트 및 유저 이력서 매칭 기능

<br/>

---

<br/>

## ⚙️ 인프라 환경

- **개발 환경**
<img width="815" height="586" alt="개발환경" src="https://github.com/user-attachments/assets/b412b30b-0c24-4a8d-8782-d1a2c7696f3f" />

- **배포 환경**
<img width="742" height="655" alt="배포환경" src="https://github.com/user-attachments/assets/380d497d-33de-43a4-a670-4c8b64e33bbd" />

<br/>

---

<br/>

## 🏗️ 기술 스택

| 분야 | 기술 |
|:---|:---|
| Backend | Spring Boot, JPA, OPENAI, ELASTICSEARCH, KIBANA, PYTHON|
| Frontend | React, TypeScript, Zustand |
| Database | PostgreSQL, S3 |
| DevOps | Docker, NGINX, REDIS |
| CI/CD | GitHub Actions |

---

 ## Language
[![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
 <br/>
 
 ## Frontend
[![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)](https://react.dev/)
 <br/>
 
 ## Backend
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat&logo=spring&logoColor=white)](https://spring.io/projects/spring-data-jpa)
[![OpenAI](https://img.shields.io/badge/OpenAI-4A4A55?style=flat&logo=openai&logoColor=white)](https://openai.com)
[![Elasticsearch](https://img.shields.io/badge/Elasticsearch-F7A71D?style=flat&logo=elasticsearch&logoColor=white)](https://www.elastic.co/elasticsearch)
[![Kibana](https://img.shields.io/badge/Kibana-005571?style=flat&logo=kibana&logoColor=white)](https://www.elastic.co/kibana)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)](https://www.postgresql.org)
 <br/>

 ## Infra
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/)
[![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)](https://www.nginx.com/)
[![Amazon S3](https://img.shields.io/badge/Amazon_S3-569A31?style=flat&logo=amazon-s3&logoColor=white)](https://aws.amazon.com/s3/)
 <br/>

 ## Cooperation
[![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/)
[![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)](https://www.notion.so/)
[![Slack](https://img.shields.io/badge/Slack-4A154B?logo=slack&logoColor=white)](https://slack.com/)

<br/>

---

<br/>

## 🚀 Getting Started

### Backend (Spring Boot)
```bash
# 1. 프로젝트 클론
git clone https://github.com/MatchingFit/MatchingFit_BACKEND.git
cd MatchingFit_BACKEND

# 2. 환경변수 설정
cp src/main/resources/application.yml.example src/main/resources/application.yml
# (application.yml을 자신의 DB/환경에 맞게 수정하세요)

# 3. 서버 실행
./gradlew bootRun
```
### Frontend (React)
```bash
cd MatchingFit_FRONTREND

# 의존성 설치
pnpm install

# 개발 서버 실행
pnpm run dev

```
---


## :open_file_folder: Project Structure

```markdown
backend
└── src
    └── main
        └── java
            └── com
                └── example
                    └── matcing_fit
                        ├── domain/          # 핵심 도메인 로직
                        │   ├── manager/     # 인사담당자 관련
                        │   ├── resume/      # 이력서 관련  
                        │   ├── score/       # 점수 관련
                        │   └── user/        # 사용자 관련
                        ├── global/          # 전역 설정 (Ai, Elasticsearch, 보안 등)
                        └── Application.java # 메인 클래스
```

<br/>

---

<br/>

## 🧱 Git 컨벤션

### 📍 브랜치 전략

- **main**: 운영 배포용 브랜치  
- **develop**: 다음 출시 버전을 개발하는 브랜치 (오류 없는 코드만 push)  
- **기능 브랜치 규칙**:
```ardunio
main
develop
chore/브랜치명{issue-number}
hotfix/브랜치명{issue-number}
feat/브랜치명{issue-number}
refactor/브랜치명{issue-number}
```

**예시:**  
`31-feat-마이페이지-api-추가`

---

### 📌 Git-Flow 전략

| 브랜치    | 설명                                |
|-----------|-------------------------------------|
| `main`    | 제품 출시용 안정화 브랜치           |
| `develop` | 통합 개발 브랜치 (기능 병합 후 테스트) |
| `feat/*`  | 기능 개발 브랜치 (develop에서 분기)  |

---

### 📍 커밋 메시지 컨벤션
```php-template
<타입> <변경 요약> <이슈번호(optional)>
```

**예시:**  
`feat : user생성 #10`

---

### ✅ 커밋 타입 목록

| 타입       | 설명                              |
|------------|-----------------------------------|
| `Feat`     | 새로운 기능 추가                  |
| `Fix`      | 버그 수정                         |
| `Refactor` | 코드 리팩토링         |
| `Chore`    | 패키지 매니저 수정, 그 외 기타 수정 ex) .gitignore            |
| `!HOTFIX`   | 급하게 치명적인 버그를 고쳐야 하는 경우             |

---

 


멋쟁이사자처럼 인턴쉽 프로그램 프로젝트입니다.
