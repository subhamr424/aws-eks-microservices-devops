# 🚀 AWS EKS Microservices DevOps Project

This project demonstrates deployment of a Dockerized microservice to Amazon EKS using Infrastructure as Code (Terraform) and automated CI/CD pipeline via GitHub Actions.

---

## 🏗 Architecture Overview

Developer → GitHub → GitHub Actions → Amazon ECR → Amazon EKS → LoadBalancer → End Users

---

## 🔹 Project Highlights

- Production-style Kubernetes deployment
- Infrastructure as Code using Terraform
- Dockerized microservice architecture
- Automated CI/CD pipeline
- EKS Managed Node Groups
- Secure VPC with Public & Private Subnets
- Scalable Deployment (Replicas = 2)

---

## ⚙️ Infrastructure Components

- VPC (Custom CIDR)
- Public & Private Subnets
- NAT Gateway
- EKS Cluster
- Managed Node Group
- ECR Repository
- LoadBalancer Service

---

## 🔄 CI/CD Workflow

1. Developer pushes code to GitHub
2. GitHub Actions builds Docker image
3. Docker image pushed to Amazon ECR
4. Kubernetes Deployment updated automatically
5. Service exposed via LoadBalancer

---

## 🐳 Application

- Flask-based Python microservice
- Containerized using Docker
- Deployed with Kubernetes Deployment & Service

---

## 📂 Project Structure

```
.
├── app/
│   ├── app.py
│   ├── requirements.txt
│   └── Dockerfile
│
├── terraform/
│   ├── main.tf
│   └── variables.tf
│
├── k8s/
│   ├── deployment.yaml
│   └── service.yaml
│
└── .github/workflows/
    └── deploy.yml
```

---

## 🛠 Tech Stack

- AWS (EKS, VPC, ECR)
- Terraform
- Docker
- Kubernetes
- GitHub Actions
- Linux

---

## 📈 Future Improvements

- Helm Charts
- Horizontal Pod Autoscaler (HPA)
- Monitoring (Prometheus & Grafana)
- Blue-Green Deployment Strategy

---

## 👨‍💻 Author

Subham Rathore  
DevOps Engineer
