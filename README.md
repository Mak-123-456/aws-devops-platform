# AWS Automated CI/CD Deployment Platform

A robust cloud infrastructure and containerized microservices deployment platform built on **Amazon Web Services (AWS)** using **Docker**, **Flask**, **Terraform**, and **GitHub Actions**.

## 🚀 Features & Architecture
- **Containerization:** Flask applications packaged with Docker for seamless portability.
- **Infrastructure as Code:** Automated resource provisioning via Terraform.
- **CI/CD Pipeline:** Automated build, push to Amazon ECR, and deploy to Amazon ECS Fargate.

## 📌 Application Endpoints
- `/` - Health check & deployment status.

## ⚙️ Local Execution
Run the app using Docker Compose:
\`\`\`bash
docker compose up --build
\`\`\`
