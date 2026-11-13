![header](https://capsule-render.vercel.app/api?type=Waving&color=gradient&customColorList=6&height=180&section=header&text=Ethan%20Jung&fontSize=50&fontAlignY=35&desc=Full-Stack%20%C2%B7%20Infra%20%C2%B7%20AI&descAlignY=55)

<div align="center">

### 코드부터 인프라, 사내 AI까지 직접 만들고 운영하는 개발자

경력 5년 · 금융·제조·공공·유통·커머스

[![Blog](https://img.shields.io/badge/Blog-blog.korphil.com-20c997?style=for-the-badge&logo=notion&logoColor=white)](https://blog.korphil.com)

</div>

---

## 👨‍💻 What I Do

- **풀스택·인프라**: Java·Spring Boot 백엔드부터 React·Vue 프론트엔드, Kubernetes(k3s) 인프라까지 설계와 운영을 직접 수행
- **사내 AI 플랫폼 1인 구축**: 오픈소스 LLM 서빙(vLLM), 벡터 검색(RAG), 에이전트 도구 호출, 정확도 자동 측정
- **대용량 데이터 마이그레이션**: 현대자동차 CRM DB 4억 건, Siebel → Salesforce 파일 10TB 단독 수행 (Best Practice 선정)
- **스마트팩토리**: MOM 운영·고도화, KPI 대시보드 구축, 2026년 사내 신규 시스템 5종 단독 구축

---

## 🚀 Featured Project

### KorPhil - Korea-Philippines Multicultural Community Platform

<div align="center">

[![Live](https://img.shields.io/badge/🌐_Live-korphil.com-blue?style=for-the-badge)](https://korphil.com)
[![PWA](https://img.shields.io/badge/📱_PWA-Install_as_App-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)](https://korphil.com)

</div>

한국-필리핀 다문화 가정을 위한 **프로덕션 레벨 풀스택 커뮤니티 플랫폼**

#### 🏗️ Architecture

```
Backend:  Java 17 · Spring Boot 3.2 · JPA · WebSocket
Frontend: React 18 · TypeScript · Capacitor 8
Database: MariaDB 11.2 · Redis · Kafka
Infra:    Docker · Nginx · Blue-Green Deployment
AI:       Groq Llama 3.3 · Google Gemini
```

#### ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🤖 **AI 뉴스 다이제스트** | 자동 뉴스 수집, 요약, 3개국어 번역 |
| 💬 **실시간 채팅** | WebSocket STOMP 기반 1:1/그룹 채팅 |
| 📱 **모바일 앱** | Capacitor 하이브리드 앱 + FCM 푸시 |
| 🌏 **다국어 지원** | 한국어, English, Tagalog |
| 💼 **구인구직** | 채용 공고 등록 및 지원 관리 |
| 📅 **이벤트 관리** | 커뮤니티 이벤트 및 RSVP |

#### 📊 Project Scale

- **32** REST Controllers · **30** Services · **32** JPA Entities
- **17** React Pages · **38+** Components
- **9** Admin Dashboard Pages

> 개인 서버(Ubuntu 24.04 + K3s, 컨테이너 40여 개)에서 Private GitLab CI/CD 와 Prometheus·Grafana 모니터링으로 직접 운영합니다. 소스 코드는 비공개입니다.

---

## 🌱 Open Source

| Project | Activity |
|:--|:--|
| [Spring Framework](https://github.com/spring-projects/spring-framework) | 레퍼런스 문서 오류 제보, 반영 ([#32335](https://github.com/spring-projects/spring-framework/issues/32335)) |
| [Orca](https://github.com/stablyai/orca) | 버그 제보, 수정 ([#34690](https://github.com/stablyai/orca/issues/34690)) |
| [Orca](https://github.com/stablyai/orca) | Pull Request 제출 ([#40020](https://github.com/stablyai/orca/pull/40020)) |

---

## 🛠️ Tech Stack

<div align="center">

**Backend**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-B22222?style=flat-square)
![.NET](https://img.shields.io/badge/C%23_.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socket.io&logoColor=white)

**Frontend & Mobile**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin_Android-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Database**

![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square)
![MSSQL](https://img.shields.io/badge/MSSQL-CC2927?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Infra & DevOps**

![Kubernetes](https://img.shields.io/badge/Kubernetes_%28k3s%29-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Rancher](https://img.shields.io/badge/Rancher-0075A8?style=flat-square&logo=rancher&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Harbor](https://img.shields.io/badge/Harbor-60B932?style=flat-square&logo=harbor&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**AI**

![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=flat-square)
![RAG](https://img.shields.io/badge/RAG_%28Vector_Search%29-6E40C9?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)

**Tools**

![IntelliJ](https://img.shields.io/badge/IntelliJ-000000?style=flat-square&logo=intellijidea&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white)

</div>

---

<div align="center">

💼 업무 코드는 회사 GitLab(비공개)에서 관리하고 있어 이곳 기여 그래프에는 나타나지 않습니다.

📫 **Contact**: <ethan@korphil.com>

</div>

![footer](https://capsule-render.vercel.app/api?type=Waving&color=gradient&customColorList=6&height=100&section=footer)
