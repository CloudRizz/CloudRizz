<div align="center">

# 👋 Rizwan Hussain

### Cloud & DevOps Engineer

AWS SAA Certified | Terraform Certified | AWS | Terraform | Kubernetes | Docker | CI/CD

Building secure, automated and scalable cloud infrastructure.

</div>

---

<h2 align="center">🧰 Tech Stack</h2>

<div align="center">

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ECS / Fargate](https://img.shields.io/badge/ECS_%2F_Fargate-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![AWS CDK](https://img.shields.io/badge/AWS_CDK-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![ECR](https://img.shields.io/badge/ECR-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazoncloudwatch&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)

</div>

---

<h2 align="center">🚀 Featured Projects</h2>

### 🔗 [Shrnk — AWS ECS URL Shortener & Analytics Platform](https://github.com/CloudRizz/url-shortener-ecs-v2)

**AWS ECS Fargate • Terraform • Python/FastAPI • Go • React • Docker • PostgreSQL • Redis • SQS • CloudFront • GitHub Actions**

Engineered and deployed a multi-service URL shortener on AWS, combining a FastAPI API, an asynchronous Go analytics worker and a Go dashboard with a React frontend hosted on S3 and CloudFront.

Provisioned modular Terraform infrastructure with private ECS Fargate workloads, PostgreSQL, Redis caching, SQS event processing, an Application Load Balancer protected by AWS WAF, and secure GitHub Actions delivery using OIDC.

**Key engineering outcomes:**
- Built and validated the end-to-end URL shortening, redirection and asynchronous analytics pipeline.
- Implemented private VPC networking without NAT gateways, using AWS VPC endpoints.
- Automated container builds, security checks and commit-tagged ECS deployments with health-based rollback.
- Integrated Trivy, Checkov and Gitleaks into CI/CD security validation.
- Tested Redis failure fallback, PostgreSQL recovery and SQS dead-letter queue redrive.
- Diagnosed deployment and Terraform teardown failures, documenting root causes and remediation.
- Decommissioned AWS infrastructure after testing to eliminate ongoing cloud costs while preserving deployment evidence and architecture documentation.

### 🗄️ [PostgreSQL High Availability / SRE Platform](https://github.com/CloudRizz/postgresql-ha-sre-platform)

**AWS • Terraform • Ansible • PostgreSQL • Patroni • etcd • NLB • Systems Manager**

Engineered a private PostgreSQL high-availability platform on AWS using Terraform and Ansible, implementing streaming replication, Patroni-managed leader election and a three-member etcd consensus cluster.

Executed controlled failure scenarios, including complete primary EC2 instance failure, validating automatic replica promotion, quorum retention, NLB connectivity and recovery of the former primary.

**Key engineering outcomes:**
- Automated PostgreSQL failover without manual promotion.
- Validated database connectivity through a stable internal NLB endpoint.
- Diagnosed and resolved network security-group connectivity failures.
- Documented availability limitations, recovery procedures and architectural trade-offs.
- Verified infrastructure teardown after completing the lab.

### 🔄 [EC2 to ECS Production-Style Migration](https://github.com/CloudRizz/ec2-to-ecs-migration)

**AWS ECS Fargate • Terraform • Docker • GitHub Actions • ECR • ALB • Route 53 • CloudWatch**

Migrated a legacy Python Flask API from a single EC2 instance to a containerised ECS Fargate platform using private subnets, multi-AZ infrastructure and an Application Load Balancer.

Implemented automated container delivery using GitHub Actions and AWS OIDC, with security scanning, Terraform plan reviews and controlled production deployment approvals.

**Key engineering outcomes:**
- Containerised and deployed the legacy Flask application to ECS Fargate.
- Implemented secure CI/CD using short-lived AWS credentials.
- Integrated Trivy, Checkov and Gitleaks security scanning.
- Performed a controlled Route 53 DNS cutover from EC2 to ECS.
- Tested rollback to the original EC2 environment.
- Implemented CloudWatch monitoring and controlled infrastructure teardown.

### ☁️ [IT Tools — AWS ECS Fargate Platform](https://github.com/CloudRizz/it-tools-ecs-platform)

**AWS ECS Fargate • Terraform • Docker • GitHub Actions • ECR • ALB • CloudWatch**

Built a production-style AWS container platform running ECS Fargate workloads in private subnets, with HTTPS ingress through an Application Load Balancer and infrastructure provisioned using reusable Terraform modules.

Automated application deployments using GitHub Actions and AWS OIDC, enabling repeatable image builds, immutable container tagging and deployment to ECS without long-lived AWS credentials.

**Key engineering outcomes:**
- Provisioned secure AWS networking and container infrastructure with Terraform.
- Deployed private ECS Fargate workloads behind an HTTPS-enabled ALB.
- Automated container build and deployment workflows.
- Implemented IAM controls, CloudWatch logging and operational health checks.
- Documented networking, security and cost trade-offs.

### 📊 [AWS Cost Intelligence Bot](https://github.com/CloudRizz/aws-cost-intelligence-bot)

**TypeScript • AWS CDK • Lambda • EventBridge • Cost Explorer • CloudWatch • GitHub Actions**

Developed an event-driven AWS cost monitoring solution using TypeScript, AWS CDK and Lambda to retrieve billing information and automatically deliver daily spending reports through Telegram.

Implemented secure credential management, automated infrastructure testing, scheduled execution, operational monitoring and security scanning.

**Key engineering outcomes:**
- Automated daily AWS cost reporting using EventBridge Scheduler.
- Integrated AWS Cost Explorer with Lambda and Telegram notifications.
- Secured credentials using AWS Systems Manager Parameter Store.
- Implemented CloudWatch alarms, encrypted SNS notifications and failure handling.
- Validated application and infrastructure behaviour using automated tests.
- Integrated Checkov and Gitleaks into CI/CD validation.

---


<h2 align="center">📜 Certifications</h2>

<div align="center">

![AWS re/Start Graduate](https://github.com/user-attachments/assets/de3b6763-4063-4c7f-84db-117cb52b7e63)
![AWS Cloud Practitioner](https://github.com/user-attachments/assets/321aa4da-d61e-4fa5-b4d9-611a1b5ba844)
<img width="160" height="160" alt="AWS Solutions Architect Associate" src="https://github.com/user-attachments/assets/d0d918f4-83bf-48e4-a37e-c23b5306249b" />
<img width="160" height="160" alt="Terraform Associate" src="https://github.com/user-attachments/assets/4d154171-391a-4450-b534-f27b715ab176" />

</div>

---

<h2 align="center">🤝 Connect</h2>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/riz-hussain/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CloudRizz)
[![Medium](https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@CloudRizz)

</div>