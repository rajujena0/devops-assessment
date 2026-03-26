# 🚀 DevOps Assignment – End-to-End Pipeline

## 📌 Overview
This project demonstrates the implementation of a complete DevOps pipeline for a sample Node.js application. It replaces manual deployment with an automated, scalable, and production-ready workflow.

---

## ⚙️ Tech Stack
- CI/CD: GitHub Actions
- Containerization: Docker
- Orchestration: Docker Compose
- Infrastructure as Code: Terraform
- Monitoring: Prometheus

---

## 🏗️ Architecture
Git Push → CI/CD Pipeline → Docker Build → Terraform Provisioning → Deployment → Monitoring

---

## 🔁 CI/CD Pipeline
Implemented using GitHub Actions:
- Install dependencies
- Run tests
- Build Docker image
- Deploy using Terraform

---

## 🐳 Docker Setup
- Containerized Node.js application
- Multi-service setup using docker-compose

Run locally:
```bash
docker compose up --build
