<div align="center">

# Mouad Chaouni

### DevOps & Cloud · Java Backend · Full Stack Development

**Building software. Automating delivery. Deploying and observing applications in the cloud.**

Final-year Engineering Student @ INPT · Class of 2027  
📍 Rabat, Morocco · Open to a six-month PFE from January 2027

[LinkedIn](https://www.linkedin.com/in/mouad-chaouni/) · [GitHub](https://github.com/Mouad852) · [Email](mailto:mdchaouni@gmail.com)

</div>

---

## About Me

I'm a final-year engineering student at **INPT**, primarily focused on **DevOps and Cloud Engineering**, with hands-on experience in **Java backend and full-stack development**.

I build secure REST APIs, backend services and web interfaces using **Java/Spring Boot, NestJS, React and Angular**. I also automate application delivery through testing, CI/CD, containerization, cloud deployment and observability.

My work includes a multi-tenant authorization service and React administration console developed during my **SYNERTIC internship**, software projects such as **MedCore and HealOps**, and cloud delivery projects on **Azure and AWS**.

I'm looking for a **six-month final-year internship starting January 2027**. I'm **AWS Certified Solutions Architect – Associate**.

---

## ☁️ Cloud & Software Delivery

### OrderFlow — Azure Application Delivery

An order-management API with a reproducible Azure delivery pipeline, from application tests to verified deployment and recovery.

- Provisioned separate staging and production environments with **Terraform**: Azure Container Apps, ACR, private PostgreSQL, Key Vault and managed identities.
- Automated testing, security scans, signed container image publication and staging checks with **Jenkins**; implemented approval-gated canary promotion and rollback.
- Secured business endpoints with **Microsoft Entra ID** and validated monitoring alerts, PostgreSQL point-in-time restore and Jenkins VM recovery.

**Stack:** Azure · Terraform · Jenkins · Ansible · FastAPI · PostgreSQL · Cosign

[Explore OrderFlow →](https://github.com/Mouad852/OrderFlow)

### CloudForge — AWS Infrastructure & Delivery

A Terraform-managed AWS platform for a Go API, with security controls, automated delivery and operational validation.

- Built private application and data tiers with **VPC, EC2, ALB/WAF, RDS, Redis and S3**, using modular Terraform.
- Automated infrastructure checks and application delivery with **GitHub Actions and AWS OIDC**, including scheduled drift detection.
- Implemented **CloudWatch** monitoring and documented load testing, recovery exercises and RDS point-in-time restore validation.

**Stack:** AWS · Terraform · GitHub Actions · OIDC · Checkov · CloudWatch · Go · k6

The environments are intentionally ephemeral; the project documents its single-instance and Single-AZ trade-offs.

[Explore CloudForge →](https://github.com/Mouad852/cloudforge)

### Pitstop — Kubernetes & Secure CI/CD

Platform and delivery engineering around an existing garage-management microservices application.

- Containerized **five existing application components** and automated delivery through **GitLab CI/CD and Argo CD**, with commit-SHA image tags and GitOps reconciliation.
- Added **Gitleaks, SonarQube, Trivy and OWASP ZAP** checks, alongside Sealed Secrets, Istio workload policies and Prometheus/Grafana/Loki observability.
- Developed the platform on **Minikube**, then validated the GitOps deployment on a **temporary AWS EKS cluster provisioned with Terraform**.

**Stack:** Docker · Kubernetes · GitLab CI/CD · Argo CD · Istio · Terraform · AWS EKS

[Explore Pitstop →](https://github.com/Mouad852/pitstop) · [GitLab GitOps repository](https://gitlab.com/pitstop-mouad-chaouni/pitstop-kubernetes)

### terraform-aws-cache — Reusable Infrastructure Module

A reusable Terraform module extracted from CloudForge's AWS cache layer.

- Configured a **single-node ElastiCache Redis** layer with encryption at rest and in transit.
- Managed the AUTH token through **AWS Secrets Manager** and restricted network access through security groups.
- Added input validation, runnable examples and automated **Terraform module tests**.

[Explore terraform-aws-cache →](https://github.com/Mouad852/terraform-aws-cache)

---

## 💻 Backend & Full Stack Applications

### MedCore — Clinic Management

A full-stack clinic-management application covering patients, appointments, billing, prescriptions and laboratory workflows.

- Built **six Spring Boot domain services**, a **React** interface and PostgreSQL persistence, with Spring Cloud Gateway and Eureka.
- Implemented **Keycloak/OIDC** authentication, JWT validation at the gateway and service boundaries, and role- and ownership-based authorization.
- Used **Flyway** migrations, **OpenFeign/Resilience4j** and health-gated Docker Compose startup for repeatable integration.

**Stack:** Java · Spring Boot · React · PostgreSQL · Keycloak · Docker Compose

[Explore MedCore →](https://github.com/Mouad852/MedCore) · [Demo with fictional data](https://myheart.mdchaouni.workers.dev) · [Walkthrough](https://youtu.be/AJEzYZvm-dY)

### HealOps — AI Integration & Operational APIs

A local operations-assistant prototype connecting an AI application to infrastructure services.

- Built an **Angular** interface and a **Spring Boot/Spring AI** service using **Gemini**.
- Developed **five Python/FastAPI adapters** for Docker operations, Prometheus metrics, optional Kubernetes diagnostics, OpenStack-oriented logs and metrics, and tracing.
- Packaged the application with **Docker Compose**, with supported operations initiated through user requests.

**Stack:** Java · Spring Boot · Spring AI · Angular · Python · FastAPI · Gemini · Docker Compose

[Explore HealOps →](https://github.com/Mouad852/HealOps)

### Dari — Flatshare Marketplace

A personal full-stack platform for finding shared accommodation in Morocco.

- Built **Spring Boot APIs and Next.js interfaces** for listing search, publication, favorites, messaging and moderation.
- Implemented location-based search with **PostgreSQL/PostGIS**, Firebase identity verification and API-side access controls.
- Used **Flyway** migrations and **Testcontainers** integration tests to verify backend behavior.

**Stack:** Java · Spring Boot · Next.js · TypeScript · PostgreSQL · PostGIS · Firebase

[Explore Dari →](https://github.com/Mouad852/Dari)

---

## 🛠️ Technical Skills

| Area | Technologies & practices |
| --- | --- |
| **Backend & APIs** | Java, Spring Boot, Spring Security, Spring Cloud, NestJS, Python/FastAPI, REST APIs, microservices |
| **Frontend** | React, Angular, Next.js, TypeScript, JavaScript |
| **Databases** | PostgreSQL, MySQL, MongoDB, Redis, PostGIS, Prisma, Flyway |
| **Cloud & Infrastructure** | Azure, AWS, Oracle Cloud, Terraform, Ansible, Linux, Bash |
| **CI/CD & Containers** | Jenkins, GitLab CI/CD, GitHub Actions, Docker, Docker Compose, Kubernetes, Argo CD, Istio |
| **Security & Observability** | Keycloak, OAuth2/OIDC, JWT, Cerbos, RBAC/ABAC, Gitleaks, Trivy, Checkov, SonarQube, OWASP ZAP, Prometheus, Grafana, Loki, CloudWatch |
| **Software Quality & Testing** | Clean Code principles, readable and modular code, unit and integration testing, JUnit, Vitest, pytest, Testcontainers, Git |

**Working strengths:** problem solving, analytical thinking, autonomy, teamwork, adaptability and technical curiosity.

---

## 💼 Experience

### DevOps & Full Stack Engineering Intern · SYNERTIC

**Casablanca, Morocco · Jun – Aug 2026**

- Developed a **multi-tenant authorization service** with Java 21, Spring Boot and PostgreSQL, integrating Keycloak authentication, Cerbos RBAC/ABAC policies and tenant isolation.
- Built a **React/TypeScript administration console** and a visual BPMN editor integrated with **Flowable** for approval-workflow modeling.
- Automated builds, security scans and deployments with **GitLab CI/CD, Kaniko and Trivy**.
- Deployed the service on **Oracle Cloud with Ansible** and centralized metrics and logs with **Prometheus, Grafana and Loki**.

### Full Stack Developer Intern · French Startup

**Remote, France · Jul – Aug 2025**

Developed a campaign-management module using **NestJS, Prisma and MongoDB**, including REST APIs, campaign-status tracking and **JWT-based access control**.

---

## 🎓 Education

### Institut National des Postes et Télécommunications — INPT

**Engineering Degree — Ubiquitous and Distributed Systems**  
Focus: DevOps and Cloud Engineering  
2024 – 2027 · Rabat, Morocco

### CPGE Ibn Timiya

**MPSI / MP — Mathematics and Physics**  
2022 – 2024 · Marrakesh, Morocco

---

## 🏅 Certifications

- [**AWS Certified Solutions Architect – Associate**](https://www.credly.com/badges/50f72001-1e5d-487b-b75f-e2828ef57292/public_url) · October 2026
- [**AWS Certified Cloud Practitioner**](https://www.credly.com/badges/75e7cbe5-6450-44ba-b61e-e2ad8ec3925a)
- [**Oracle Cloud Infrastructure Foundations Associate**](https://catalog-education.oracle.com/pls/certview/sharebadge?id=18405CC30BE250C13C15C4FC2452776928715E42D1CDFC6B37C4B761F37C04A4) · October 2025

---

## 🔭 Current Focus

- Secure cloud delivery with **Azure/AWS, Terraform, CI/CD and Kubernetes**.
- Backend API design, application security and distributed systems with **Java/Spring Boot**.
- Maintainable software, automated testing and practical AI integration.

## 🎯 Looking for a PFE

I'm looking for a **six-month final-year engineering internship starting January 2027**.

My preferred areas, in order:

1. **DevOps & Cloud Engineering**, with DevSecOps as a supporting strength.
2. **Backend Java / Spring Boot Development**.
3. **Full Stack Development**.

I'm interested in contributing to application development, software delivery and cloud deployment, depending on the role.

---

<div align="center">

## 🤝 Let's Connect

[LinkedIn](https://www.linkedin.com/in/mouad-chaouni/) · [GitHub](https://github.com/Mouad852) · [Email](mailto:mdchaouni@gmail.com)

</div>
