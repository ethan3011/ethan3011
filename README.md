![header](https://capsule-render.vercel.app/api?type=Waving&color=gradient&customColorList=6&height=180&section=header&text=Ethan%20Jung&fontSize=50&fontAlignY=35&desc=Full-Stack%20%C2%B7%20Infra%20%C2%B7%20AI&descAlignY=55)

<div align="center">

### I build and run everything from code to infrastructure to in-house AI

5 years of experience · Finance · Manufacturing · Public sector · Retail · Commerce

</div>

---

## 👨‍💻 What I Do

- **Full-stack & infrastructure**: Design and run everything from Java/Spring Boot backends and React/Vue frontends to Kubernetes (k3s) infrastructure
- **In-house AI platform, built solo**: Open-source LLM serving (vLLM), vector search (RAG), agent tool calling, automated accuracy evaluation
- **Large-scale data migration**: Hyundai Motor CRM database (400 million records); 10 TB of files from Siebel to Salesforce, single-handedly (selected as a client best practice)
- **Smart factory**: MOM operations and improvements, KPI dashboards, and five new in-house systems built solo in 2026

---

## 🚀 Featured Project

### KorPhil - Korea-Philippines Multicultural Community Platform

<div align="center">

[![Live](https://img.shields.io/badge/🌐_Live-korphil.com-blue?style=for-the-badge)](https://korphil.com)
[![PWA](https://img.shields.io/badge/📱_PWA-Install_as_App-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)](https://korphil.com)

</div>

A **production-grade full-stack community platform** for Korean-Filipino multicultural families

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
| 🤖 **AI News Digest** | Automatic news collection, summaries, and translation into 3 languages |
| 💬 **Real-time Chat** | 1:1 and group chat over WebSocket (STOMP) |
| 📱 **Mobile App** | Capacitor hybrid app with FCM push notifications |
| 🌏 **Multilingual** | Korean, English, Tagalog |
| 💼 **Jobs** | Job postings and application management |
| 📅 **Events** | Community events and RSVPs |

#### 📊 Project Scale

- **32** REST Controllers · **30** Services · **32** JPA Entities
- **17** React Pages · **38+** Components
- **9** Admin Dashboard Pages

> Self-hosted on my own server (Ubuntu 24.04 + K3s, 40+ containers) with private GitLab CI/CD and Prometheus/Grafana monitoring. The source code is private.

---

## 🌱 Open Source

| Project | Activity |
|:--|:--|
| [Harbor](https://github.com/goharbor/harbor) | Pull requests: fixed the Korean portal translation, where placeholders hid the real error ([#24482](https://github.com/goharbor/harbor/pull/24482), approved, in review) and failed replications were labeled "run" ([#24483](https://github.com/goharbor/harbor/pull/24483), in review) |
| [docx](https://github.com/dolanmiu/docx) | Pull request: clarified that the paragraph `wordWrap` option makes Word break Korean words, measured in Word ([#3936](https://github.com/dolanmiu/docx/pull/3936), in review) |
| [Harbor](https://github.com/goharbor/harbor) | Pull request: harbor-db refuses to start with an empty database when an upgrade skips a release ([#24466](https://github.com/goharbor/harbor/pull/24466), in review; reported in [#24465](https://github.com/goharbor/harbor/issues/24465)) |
| [Orca](https://github.com/stablyai/orca) | Reported a bug: a comma-separated terminal font family was quoted as one font name, so a Korean fallback font couldn't be added ([#47488](https://github.com/stablyai/orca/issues/47488), now fixed in [#47561](https://github.com/stablyai/orca/pull/47561)) |
| [MetalLB](https://github.com/metallb/metallb) | Pull request: L2 speakers keep retrying until the node's interfaces are known, so LoadBalancer IPs are announced after a reboot ([#3202](https://github.com/metallb/metallb/pull/3202), in review; reported in [#3201](https://github.com/metallb/metallb/issues/3201)) |
| [K3s](https://github.com/k3s-io/k3s) | Reported LoadBalancer downtime during upgrades caused by the iptables cleanup in install.sh; maintainers pointed to `INSTALL_K3S_SKIP_START` to avoid it ([#15040](https://github.com/k3s-io/k3s/issues/15040), closed) |
| [Traefik](https://github.com/traefik/traefik) | Pull request: documented the entryPoint read timeout in the ingress-nginx migration guide, based on a production migration ([#14352](https://github.com/traefik/traefik/pull/14352), in review) |
| [Orca](https://github.com/stablyai/orca) | Pull request: connect chat sessions to Claude Code Remote Control so they show up in the Claude mobile app ([#40020](https://github.com/stablyai/orca/pull/40020), in review) |
| [Orca](https://github.com/stablyai/orca) | Reported a bug, now fixed ([#34690](https://github.com/stablyai/orca/issues/34690)) |
| [Spring Framework](https://github.com/spring-projects/spring-framework) | Reported an error in the reference docs, now fixed ([#32335](https://github.com/spring-projects/spring-framework/issues/32335)) |

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

💼 My day-to-day work lives in a private company GitLab, so it doesn't show up in the contribution graph here.

📫 **Contact**: <ethan@korphil.com>

</div>

![footer](https://capsule-render.vercel.app/api?type=Waving&color=gradient&customColorList=6&height=100&section=footer)
