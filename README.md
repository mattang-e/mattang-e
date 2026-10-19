<!--
**hkiyeon/hkiyeon** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
Infrastructure / DevOps Engineer

10년 가까이 Linux 기반 인프라를 구축·운영하며 서버, 네트워크, 스토리지, 가상화 및 AWS 환경을 경험해왔습니다.

현재는 기존 인프라 운영 경험을 기반으로 Kubernetes, Container, CI/CD 및 GitOps 영역으로 기술 역량을 확장하고 있습니다.

Tech Stack

Infrastructure

* Linux (Rocky Linux)
* AWS
* XCP-ng / Xen Orchestra
* FortiGate
* NFS

Automation & Container

* Terraform
* Ansible
* Python / Bash
* Docker

Kubernetes & DevOps

* Kubernetes
* Helm
* Jenkins
* Harbor
* Argo CD
* Prometheus / Grafana

DevOps Projects

Terraform과 Xen Orchestra Provider를 활용하여 XCP-ng 가상화 환경의 VM 프로비저닝을 자동화한 프로젝트입니다.

* Xen Orchestra Provider 기반 XCP-ng 연동
* 기존 Template / Network / NFS Storage 연동
* CPU / Memory / Disk 리소스 코드 기반 관리
* for_each를 활용한 다중 VM 프로비저닝
* Terraform State 기반 리소스 관리 및 Drift 감지
* xcp-ng-terraform
  
[xcp-ng-terraform](https://github.com/mattang-e/xcp-ng-terraform)

1. Kubernetes Platform Lab

On-Premise 환경에서 Kubernetes Cluster를 직접 구축한 프로젝트입니다.

* Control Plane / Worker Node 기반 Kubernetes Cluster 구축
* Container Runtime 및 Kubernetes 주요 구성요소 설치
* CNI 기반 Pod Network 구성
* Kubernetes Cluster 운영 및 Troubleshooting 실습

[kubernetes-platform-lab](https://github.com/mattang-e/kubernetes-platform-lab)

⸻

2. Kubernetes CI/CD Lab

Jenkins와 Harbor를 활용하여 애플리케이션의 Container Image Build 및 배포 Pipeline을 구성한 프로젝트입니다.

Pipeline

GitHub → Jenkins → Docker Build → Harbor → Kubernetes

* Jenkins CI Pipeline 구성
* Docker Image Build 및 Tag 관리
* Harbor Private Registry 구축 및 Image Push
* Kubernetes 배포 과정 연동

[kubernetes-cicd-lab](https://github.com/mattang-e/kubernetes-cicd-lab)

⸻

3. Server Inventory Kubernetes

FastAPI 기반 Server Inventory 서비스를 Kubernetes 환경에 배포하고 Helm과 Argo CD를 적용한 프로젝트입니다.

Deployment

Git Repository → Argo CD → Helm → Kubernetes

* FastAPI Application Kubernetes 배포
* PostgreSQL Database 구성
* Helm Chart 기반 Kubernetes Resource 관리
* Argo CD 기반 GitOps 배포 환경 구성

[server-inventory-k8s](https://github.com/mattang-e/server-inventory-k8s)

⸻

4. Server Inventory API

서버 정보를 관리하기 위해 제작한 FastAPI/PostgreSQL 기반 REST API 프로젝트입니다.

* FastAPI 기반 Server Inventory CRUD API 구현
* PostgreSQL Database 연동
* Docker Image 구성
* Docker Compose 기반 Application/Database 실행 환경 구성

[server-inventory-api](https://github.com/mattang-e/server-inventory-api)

Architecture / Project Flow

전체 프로젝트는 다음 과정으로 확장하며 구성했습니다.

FastAPI + PostgreSQL
→ Docker
→ Kubernetes
→ Helm
→ Jenkins + Harbor
→ Argo CD / GitOps

Certification

* CKA (Certified Kubernetes Administrator)
