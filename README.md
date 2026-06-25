# Petclinic Microservices Platform on AWS

## End-to-End DevOps Implementation

## Overview

This project demonstrates a complete cloud-native microservices platform deployed on AWS using modern DevOps practices.

The original Spring Petclinic microservices application was extended and deployed using a fully automated CI/CD pipeline, infrastructure provisioning, containerization, and monitoring stack.

The goal of this project is to simulate a production-grade microservices deployment pipeline using industry-standard DevOps tools.

---

## Architecture Overview

This project is based on a distributed Spring Boot microservices architecture consisting of:

* API Gateway
* Config Server
* Discovery Server (Eureka)
* Customers Service
* Vets Service
* Visits Service
* Admin Server

---

## Technologies Used

* AWS (EC2, VPC, IAM)
* Terraform
* Docker
* Kubernetes
* Jenkins
* Ansible
* Prometheus
* Grafana
* Spring Boot
* Git & GitHub

---

## Repository Structure

```text
.
├── infrastructure/        # Terraform configurations
├── ansible/               # Deployment automation
├── docker/                # Docker configurations
├── jenkins/               # CI/CD pipeline definitions
├── k8s/                   # Kubernetes manifests
├── docs/                  # Architecture diagrams & screenshots
├── spring-petclinic-*     # Microservices modules
└── README.md
```

---

## CI/CD Pipeline

```text
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
Push to Amazon ECR
      │
      ▼
Ansible / Kubernetes Deployment
      │
      ▼
Running Microservices on AWS
      │
      ▼
Monitoring with Prometheus & Grafana
```

---

## Project Preview

### Architecture

![Architecture](docs/microservices-architecture-diagram.jpg)

### Application

![Application](docs/application-screenshot.png)

### Monitoring

![Grafana Dashboard](docs/grafana-custom-metrics-dashboard.png)

---

## Key Features

* End-to-end CI/CD automation
* Microservices architecture deployment
* Infrastructure as Code (Terraform)
* Configuration management with Ansible
* Container orchestration with Docker & Kubernetes
* Monitoring and observability using Prometheus & Grafana
* Cloud deployment on AWS

---

## Monitoring & Observability

* Prometheus metrics collection
* Grafana dashboards
* Application health monitoring
* Infrastructure observability

---

## My Responsibilities

* Designed and provisioned AWS infrastructure using Terraform
* Built CI/CD pipelines with Jenkins
* Containerized microservices using Docker
* Deployed workloads to Kubernetes
* Automated deployments using Ansible
* Integrated Prometheus and Grafana for monitoring
* Managed the complete deployment lifecycle

---

## Learning Outcomes

Through this project, I gained practical experience with:

* Designing production-grade microservices architectures
* Infrastructure provisioning with Terraform
* Building end-to-end CI/CD pipelines
* Kubernetes-based application deployment
* Containerization with Docker
* Monitoring distributed systems using Prometheus and Grafana
* End-to-end DevOps workflow implementation

---

## Notes

This project is part of my Cloud & DevOps portfolio and demonstrates practical experience with cloud infrastructure, automation, and microservices deployment.

It is intended for learning and portfolio purposes and would require additional enhancements for production environments, including:

* Security hardening
* Auto Scaling
* Centralized logging (ELK/OpenSearch)
* Secret management (AWS Secrets Manager or HashiCorp Vault)
* Advanced monitoring and alerting
