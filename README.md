# 🔐 Secure CI/CD Pipeline (DevSecOps)

## 📌 Overview

This project demonstrates an enterprise-grade DevSecOps pipeline built using GitHub Actions.

It integrates security scanning, automated builds, and CI/CD best practices.

---

## 🚀 Key Features

* CI/CD pipeline using GitHub Actions
* Static Application Security Testing (SAST) with Semgrep
* Secret detection simulation
* Docker image build automation
* Flask application for testing pipeline

---

## 🏗️ Architecture

Developer → Push Code → GitHub Actions → Security Scans → Docker Build

---

## 🔐 Security

This pipeline follows a **shift-left security approach**:

* SAST scanning during CI
* Early detection of vulnerabilities
* Automated validation before build

---

## 🧪 Application

Simple Flask app with an intentional typo:

Flask Trainng App

---

## 🐳 Docker

The application is containerized using a lightweight Python image.

---

## 📈 CI/CD Pipeline

| Stage    | Description          |
| -------- | -------------------- |
| Setup    | Install dependencies |
| Test     | Run application      |
| Security | Run SAST scan        |
| Build    | Build Docker image   |

---

## 🧠 Lessons Learned

* CI/CD pipelines should fail fast on missing dependencies
* Security should be integrated early in the pipeline
* Automation improves consistency and reliability

---

## 🔮 Future Improvements

* Add container vulnerability scanning
* Integrate OIDC authentication
* Deploy to cloud (Azure / AWS)

