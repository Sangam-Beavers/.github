<div align="center">

# 🦫 Sangam Beavers

### Building **GlobalBridge** — a financial bridge for migrant workers

외국인 근로자를 위한 **금융 플랫폼**을 만드는 팀입니다.<br/>
송금 · 지갑 · 커뮤니티, 그리고 AI 계약서 분석까지 — 언어와 제도의 장벽을 넘어 누구나 안전하게 금융을 누리도록.

<br/>

![Frontend](https://img.shields.io/badge/Frontend-1E293B?style=for-the-badge)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

![Backend](https://img.shields.io/badge/Backend-1E293B?style=for-the-badge)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

![AI](https://img.shields.io/badge/AI%20%2F%20LLM-1E293B?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Amazon Bedrock](https://img.shields.io/badge/Bedrock-FF9900?style=for-the-badge&logo=amazon&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

![Infra](https://img.shields.io/badge/Infra%20%2F%20DevOps-1E293B?style=for-the-badge)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![vSphere](https://img.shields.io/badge/vSphere-607078?style=for-the-badge&logo=vmware&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)

![Network](https://img.shields.io/badge/Network-1E293B?style=for-the-badge)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=for-the-badge&logo=tailscale&logoColor=white)

</div>

---

## 💡 What we build

**GlobalBridge**는 한국에 거주하는 외국인 근로자가 겪는 금융 불편을 해소하기 위한 종합 핀테크 서비스입니다.

- 💸 **간편 송금 · 디지털 지갑** — 충전부터 현금화까지, 외부 은행 연동 결제 흐름을 안전하게
- 🤖 **AI 계약서 분석 챗봇** — Bedrock 기반으로 근로계약서를 읽고 핵심 조항·위험 요소를 모국어로 설명
- 🌐 **다국어 커뮤니티** — 게시글·댓글 실시간 번역으로 한국어/영어/베트남어/태국어/필리핀어 등 언어 장벽 없는 소통
- 🛡️ **규제 수준의 신뢰성** — 변경 불가 금융 감사 로그, KYC, 거래 추적과 운영 SLO 관리

---

## 📦 Repositories

#### 🖥️ Frontend
| Repo | 설명 | Stack |
|------|------|-------|
| [`frontend`](https://github.com/Sangam-Beavers/frontend) | 외국인 근로자용 모바일 앱 (고객 대면) | React · TypeScript · Vite · i18next |
| [`gb-admin-frontend`](https://github.com/Sangam-Beavers/gb-admin-frontend) | 운영팀용 어드민 콘솔 (금융·사용자·시스템 관리) | React · TypeScript · Recharts |

#### ⚙️ Backend
| Repo | 설명 | Stack |
|------|------|-------|
| [`gb-backend`](https://github.com/Sangam-Beavers/gb-backend) | 핀테크 마이크로서비스 모노레포 (member·wallet·community·document·admin) | Java · Spring Boot · Gradle · MySQL/Aurora |
| [`gb-mock-banks`](https://github.com/Sangam-Beavers/gb-mock-banks) | 외부 은행 모의 서버 (Beaver Bank / Quokka Bank) | Node.js · Express · SQLite · mTLS |

#### 🤖 AI
| Repo | 설명 | Stack |
|------|------|-------|
| [`gb-chatbot-lambda`](https://github.com/Sangam-Beavers/gb-chatbot-lambda) | AI 계약서 분석 챗봇 + 커뮤니티 번역 Lambda | Python · Bedrock · Claude · MCP |
| [`gb-document-lambda`](https://github.com/Sangam-Beavers/gb-document-lambda) | AI 문서 분석 Lambda | Python · Bedrock |
| [`gb-mcp-servers`](https://github.com/Sangam-Beavers/gb-mcp-servers) | 챗봇용 MCP 서버 (환율·커뮤니티 어댑터) | Python · FastAPI · Redis · MySQL |

#### ☁️ Infra & DevOps
| Repo | 설명 | Stack |
|------|------|-------|
| [`cloud-infra-iac`](https://github.com/Sangam-Beavers/cloud-infra-iac) | AWS 인프라 IaC (VPC·EKS·Aurora·KMS) | Terraform · AWS |
| [`gb-infra`](https://github.com/Sangam-Beavers/gb-infra) | 마이크로서비스 Helm 차트 & 배포 매니페스트 | Helm · Kubernetes · ArgoCD |
| [`devops-infra-configs`](https://github.com/Sangam-Beavers/devops-infra-configs) | 온프레미스 K8s 클러스터 구축 가이드 (vSphere) | Kubernetes · Cilium · pfSense |
| [`devops-vpn-configs`](https://github.com/Sangam-Beavers/devops-vpn-configs) | 온프레미스 ↔ AWS Site-to-Site VPN | WireGuard · FRR/BGP |

---

## 🧰 Tech Stack

| 영역 | 기술 |
|------|------|
| **Frontend** | React · TypeScript · Vite · React Query · i18next |
| **Backend** | Java · Spring Boot · Gradle · MySQL / Aurora |
| **AI / LLM** | Amazon Bedrock · Claude (Sonnet · Haiku) · MCP (Model Context Protocol) |
| **Cloud** | AWS (EKS · Aurora · KMS · Secrets Manager) · Terraform |
| **On-prem** | vSphere · Kubernetes · Cilium · pfSense |
| **Networking** | WireGuard · BGP(FRR) · Route53 Resolver |
| **DevOps** | Helm · ArgoCD · Harbor · Prometheus · Grafana |
| **Auth** | Authentik (OIDC) |

---

<div align="center">

**Sangam Beavers** 🦫 — _bridging people and finance, in every language._

</div>
