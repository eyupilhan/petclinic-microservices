Petclinic Microservices Platform (AWS DevOps Implementation)
Overview

This project demonstrates a complete cloud-native microservices platform deployed on AWS using modern DevOps practices.

The original Spring Petclinic microservices application was extended and deployed using a fully automated CI/CD pipeline, infrastructure provisioning, containerization, and monitoring stack.

The goal of this project is to simulate a production-grade microservices deployment pipeline using industry-standard DevOps tools.

🧱 Architecture Overview

This system is built using a distributed microservices architecture:

API Gateway
Config Server
Discovery Server (Eureka)
Customers Service
Vets Service
Visits Service
Admin Server
🛠️ Technologies Used
AWS (EC2, VPC, IAM)
Docker
Kubernetes
Jenkins (CI/CD Pipeline)
Terraform (Infrastructure as Code)
Ansible (Configuration Management)
Prometheus (Monitoring)
Grafana (Visualization)
Spring Boot Microservices
Git & GitHub
📦 Repository Structure
.
├── infrastructure/        # Terraform configurations
├── ansible/               # Deployment automation
├── docker/                # Docker configurations
├── jenkins/               # CI/CD pipeline definitions
├── k8s/                   # Kubernetes manifests
├── docs/                  # Architecture diagrams & screenshots
├── spring-petclinic-*     # Microservices modules
└── README.md
🔄 CI/CD Pipeline
Developer Push
      │
      ▼
GitHub Repository
      │
      ▼
Jenkins Pipeline
      │
      ▼
Terraform Infrastructure Provisioning
      │
      ▼
Docker Image Build
      │
      ▼
Push to Registry (ECR)
      │
      ▼
Ansible / Kubernetes Deployment
      │
      ▼
Running Microservices on AWS
      │
      ▼
Monitoring with Prometheus & Grafana
📊 Monitoring & Observability
Prometheus collects application and infrastructure metrics
Grafana dashboards visualize system performance
Health checks for microservices
Distributed system observability
🎯 Key Features
End-to-end CI/CD automation
Microservices architecture deployment
Infrastructure as Code (Terraform)
Configuration management with Ansible
Container orchestration with Docker & Kubernetes
Monitoring & observability stack integration
Cloud deployment on AWS
🧠 My Responsibilities
Designed and implemented AWS infrastructure using Terraform
Built CI/CD pipelines using Jenkins
Containerized microservices using Docker
Deployed services using Kubernetes
Configured Ansible automation workflows
Integrated Prometheus & Grafana monitoring stack
Managed full deployment lifecycle
📈 Learning Outcomes

Through this project, I gained experience in:

Designing production-grade microservice architectures
Automating cloud infrastructure provisioning
Building CI/CD pipelines from scratch
Kubernetes-based deployment strategies
Observability and monitoring in distributed systems
End-to-end DevOps workflow implementation
📌 Notes

This project is part of a DevOps portfolio and demonstrates real-world practices in cloud infrastructure, automation, and microservices deployment.

It is not intended for production use without additional enhancements such as:

Security hardening
Auto-scaling policies
Centralized logging (ELK stack)
Advanced monitoring rules
