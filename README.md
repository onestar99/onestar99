# Hanbyeol

> **Backend Engineer (Java & Spring Boot)**  
> "견고한 아키텍처와 효율적인 데이터 처리를 통해 안정적인 백엔드 시스템을 구축합니다."

<br>

## 🛠 Tech Stack

| Category | Stack | Proficiency |
| :--- | :--- | :--- |
| **Core Language** | ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) | **Advanced**<br>JVM 아키텍처, 메모리 모델, GC 튜닝 등 언어의 깊이 있는 이해를 바탕으로 개발합니다. |
| **Framework** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) | **Advanced**<br>대규모 트래픽 처리를 고려한 설계, 트랜잭션 관리, Spring Security 적용 등에 능숙합니다. |
| **Database** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | **Intermediate**<br>쿼리 최적화 및 인덱싱 전략 수립 경험이 있습니다. |
| | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) | **Intermediate**<br>복잡한 관계형 데이터 모델링 및 트랜잭션 처리에 활용합니다. |
| | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) | **Basic**<br>NoSQL의 특성을 이해하고 비정형 데이터 처리에 활용합니다. |
| **Sub Language** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | **Intermediate**<br>데이터 분석, 자동화 스크립트 작성 및 오픈소스 분석 보조 도구로 활용합니다. |
| **Infrastructure** | ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white) | **Intermediate**<br>리눅스 환경에서의 개발 및 시스템 운영, 쉘 스크립팅에 익숙합니다. |
| | ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) | **Intermediate**<br>리버스 프록시, 로드 밸런싱 구성 및 SSL 인증서 적용이 가능합니다. |
| | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) | **Basic**<br>컨테이너 생태계를 이해하고 Dockerfile을 작성하여 환경을 구성할 수 있습니다. |
| | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) | **Basic**<br>Pod, Service, Deployment 등 기본 오브젝트의 개념을 이해하고 있습니다. |
| **Monitoring** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) | **Basic**<br>서버 메트릭 수집 및 시각화 대시보드(Loki 포함)를 구성해 본 경험이 있습니다. |
| **DevOps** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) | **Intermediate**<br>Git Flow 등 브랜치 전략을 준수하며 협업합니다. |
| | ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white) | CI/CD 파이프라인 구축 및 배포 자동화 경험이 있습니다. |

<br>

## 🚀 Research & Projects

### **Autonomous Multi-Cloud CI/CD with LLM**
> **"자연어 기반 인프라 구성 자동화 및 지능형 배포 시스템"**

**Background & Challenge**
- **리소스 최적화**: 비용 효율성을 위해 다중 클라우드 환경(Multi-Cloud)을 구축하였으나, 이기종 환경 관리의 복잡성이 증대됨.
- **네트워크 보안**: VPC가 부재한 독립 환경 간의 보안 통신을 위해 정교한 IP 화이트리스팅 및 Config 동기화가 필수적임.

**Solution Architecture**
- **Centralized Monitoring**: Prometheus와 Grafana를 활용하여 분산된 클라우드 리소스의 메트릭을 중앙 집중형으로 모니터링.
- **Automated Configuration**: Jenkins 파이프라인을 구축하여, Config Server 변경 시 각 독립 서버의 방화벽 및 설정이 유기적으로 동기화되도록 구현.
- **LLM Integration**: 
  - 자연어 명령을 통해 인프라 설정 코드를 생성 및 적용.
  - **Code Verification**: LLM 생성 코드의 신뢰성 확보를 위해 Cross-Check(모델 간 검증) 및 GAN(적대적 생성) 방식의 검증 프로세스 연구.
  - **MCP (Model Context Protocol)**: 클라이언트-서버 구조의 유연한 확장을 위해 MCP 프로토콜 도입 및 적용 중.

<br>

## 🌱 Fields of Interest

- **Backend Architecture**: 대용량 트래픽 처리를 위한 분산 시스템 설계 및 MSA(Microservices Architecture).
- **Performance Tuning**: JVM 튜닝, 쿼리 최적화 등을 통한 시스템 성능 개선.
- **Cloud Native**: Kubernetes 등 클라우드 네이티브 환경에서의 안정적인 서비스 운영.

<br>

## 📊 Activity

<div align="center">

<!-- Snake Animation -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/onestar99/onestar99/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/onestar99/onestar99/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/onestar99/onestar99/output/github-contribution-grid-snake.svg">
</picture>

<br><br>

| Solved.ac |
| :---: |
| <img src="https://mazassumnida.wtf/api/v2/generate_badge?boj=jhb9904" height="150" alt="Solved.ac Profile"/> |

</div>
