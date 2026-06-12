<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=480&lines=LeeKyeongMin+%2F+%EC%9D%B4%EA%B2%BD%EB%AF%BC;Backend-focused+Developer;Java+%C2%B7+Spring+Boot+%C2%B7+REST+API" alt="Typing SVG" />

</div>

---

### ✨ About Me

- 🖥 현재 **백엔드 중심의 풀스택 개발자**를 목표로 공부 중입니다.
- 💻 코딩하는 과정을 즐기며, 새로운 기능을 하나씩 완성하는 데서 큰 재미를 느낍니다.
- 🐞 에러와 버그를 만나도 스트레스보다는 **원인 분석하고 해결하는 과정**을 좋아합니다.
- 📚 프로젝트를 진행하면서 부족한 CS 기초를 **정리하고 채워가는 중**입니다.
- ☁ 사이드 프로젝트를 통해 **Docker, GCP, CI/CD 기반 배포 환경**을 직접 구성하며 백엔드부터 배포까지 전체 흐름을 이해하려고 노력합니다.
- 🔀 팀 프로젝트에서 branch / PR / merge 기반 협업을 경험했고, 다수의 merge conflict를 해결하며 안정적으로 코드를 통합하는 연습을 했습니다.

---

### ⚙️ Tech Stack

#### 🖥 Backend
![Java](https://img.shields.io/badge/-Java-555555?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-555555?logo=springboot&logoColor=6DB33F)
![Spring Security](https://img.shields.io/badge/-Spring%20Security-555555?logo=springsecurity&logoColor=6DB33F)
![Spring Data JPA](https://img.shields.io/badge/-Spring%20Data%20JPA-555555?logo=spring&logoColor=6DB33F)
![REST API](https://img.shields.io/badge/-REST%20API-555555?logoColor=white)
![OAuth2](https://img.shields.io/badge/-OAuth2-555555?logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-555555?logo=jsonwebtokens&logoColor=white)

#### 🌐 Frontend
![React](https://img.shields.io/badge/-React-555555?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/-TypeScript-555555?logo=typescript&logoColor=3178C6)
![JavaScript](https://img.shields.io/badge/-JavaScript-555555?logo=javascript&logoColor=F7DF1E)
![HTML5](https://img.shields.io/badge/-HTML5-555555?logo=html5&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/-CSS3-555555?logo=css3&logoColor=1572B6)
![TanStack Query](https://img.shields.io/badge/-TanStack%20Query-555555?logo=reactquery&logoColor=FF4154)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-555555?logo=tailwindcss&logoColor=06B6D4)

#### 🗄 Database
![MySQL](https://img.shields.io/badge/-MySQL-555555?logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/-MariaDB-555555?logo=mariadb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-555555?logo=postgresql&logoColor=white)

#### 🛠 Infra / Tools
![Docker](https://img.shields.io/badge/-Docker-555555?logo=docker&logoColor=2496ED)
![GCP](https://img.shields.io/badge/-GCP-555555?logo=googlecloud&logoColor=4285F4)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-555555?logo=githubactions&logoColor=2088FF)
![Git](https://img.shields.io/badge/-Git-555555?logo=git&logoColor=F05032)
![Linux](https://img.shields.io/badge/-Linux-555555?logo=linux&logoColor=white)
![Python](https://img.shields.io/badge/-Python-555555?logo=python&logoColor=3776AB)
![IntelliJ IDEA](https://img.shields.io/badge/-IntelliJ%20IDEA-555555?logo=intellijidea&logoColor=white)
![VSCode](https://img.shields.io/badge/-VS%20Code-555555?logo=visualstudiocode&logoColor=007ACC)

---

### 🛠 Projects

<details>
  <summary>🧾 ShareStay — 공동 거주 · 방 공유 웹 서비스</summary>
  <br/>

  > 사용자가 방을 등록하고 지도 기반으로 주변 매물을 탐색할 수 있는 공동 거주 웹 서비스

  - **기간**: 2025.10.29 ~ 2025.12.10 (6주, 5인)
  - **역할**: Full-stack (React + Spring Boot) 개발, 팀장
  - **주요 기능**
    - 카카오맵 연동 매물 등록 및 지도 기반 탐색
    - JWT + Google OAuth2 인증 구조 구현
    - DB 1차 필터링 + 서비스 레이어 2차 필터링 구조 설계
    - 즐겨찾기 이중 방어 구조 (existsByUserIdAndRoomId + DB 제약)
    - 지도 idle 이벤트 기반 API 호출 최적화, 마커 클러스터링 적용
    - Git 브랜치 전략 수립 · PR 코드리뷰 프로세스 정착
  - **기술 스택**
    - FE: `React`, `TypeScript`, `JavaScript`
    - BE: `Java`, `Spring Boot`, `Spring Security`, `Spring Data JPA`
    - DB: `MariaDB`
    - API: `Kakao Map API`, `Google OAuth2`
  - 링크: [깃허브 링크](https://github.com/rudals5215/sharestay-)
</details>

<details>
  <summary>🧾 YouthBridge — 청년 정책 추천 플랫폼 (진행 중)</summary>
  <br/>

  > 외부 공공 API 데이터를 수집·가공하여 청년 정책을 추천하는 플랫폼

  - **기간**: 2026.01 ~ (진행 중, 1인)
  - **주요 기능**
    - 공공 API 데이터 수집 · 가공 후 DB 저장
    - 필터링 · 정렬 · 페이징 포함 조회 API 구현
  - **기술 스택**
    - BE: `Java`, `Spring Boot`, `Spring Data JPA`
    - DB: `MariaDB`
    - API: `공공데이터포털 API`
</details>

---

*기계과 졸업 후 방송국 보도팀 · 제조업 현장을 거치며 데이터 체계와 협업의 중요성을 체감, 개발자로 전향.*
