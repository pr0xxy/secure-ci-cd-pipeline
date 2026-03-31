![CI](https://github.com/pr0xxy/secure-ci-cd-pipeline/actions/workflows/ci.yml/badge.svg)

# 🔐 Secure CI/CD Pipeline (DevSecOps)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![CI/CD](https://img.shields.io/badge/CI/CD-GitHub%20Actions-green)
![Security](https://img.shields.io/badge/Security-SAST-red)

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
[View Pipeline Diagram](diagram.md)

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

---

## 🔗 Related Projects

- [Enterprise Docker Library](https://github.com/pr0xxy/enterprise-docker-library)

This project uses hardened container practices demonstrated in the Enterprise Docker Library.
