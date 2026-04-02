# Aws-three-tier
project for seminar
# AWS Three-Tier Cloud-Native Application with DevOps Automation

## 📌 Overview
This project implements a **cloud-native three-tier architecture** on AWS with full DevOps automation.

### Architecture:
- **Presentation Tier**
  - Amazon S3 (Frontend hosting)
  - CloudFront (CDN)
  - API Gateway

- **Business Logic Tier**
  - AWS ECS (Docker containers)
  - AWS Lambda (serverless functions)
  - Application Load Balancer

- **Data Tier**
  - Amazon RDS (MySQL/Aurora)
  - DynamoDB

---

## ⚙️ Tech Stack
- AWS (ECS, Lambda, RDS, S3, CloudFront, API Gateway)
- Docker
- Terraform / CloudFormation (IaC)
- CI/CD (CodePipeline, CodeBuild, CodeDeploy)
- Monitoring (CloudWatch, X-Ray)

---

## 📂 Project Structure
aws-three-tier-app/
│── frontend/
│   ├── index.html
│   ├── style.css
│   └── app.js
│
│── backend/
│   ├── app.py
│   ├── Dockerfile
│   └── requirements.txt
│
│── lambda/
│   └── function.py
│
│── infra/
│   └── main.tf
│
│── README.md
