# HEROES RELAXATION HUB

## 🌿 Project Overview
Heroes Relaxation Hub is a static web application deployed using Azure Static Web Apps with a CI/CD pipeline powered by GitHub Actions.

---

## 🚀 Technologies Used
- HTML
- CSS
- JavaScript
- GitHub Actions
- Azure Static Web Apps

---

## 🔁 CI/CD Pipeline Design (Staging → Production)

This project implements a two-stage CI/CD pipeline using GitHub Actions and Azure Static Web Apps.

### 🟡 Staging Environment
- Automatically triggered on push to `main`
- Used for deployment validation
- No manual approval required

### 🟢 Production Environment
- Runs after successful staging deployment
- Requires manual approval using GitHub Environments
- Protected deployment workflow

---

## ☁️ Deployment Platform
Azure Static Web Apps

---

## ⚙️ CI/CD Tools
- GitHub Actions
- GitHub Environments
- Azure Deployment Tokens

---

## 📌 Workflow Summary
1. Developer pushes code to GitHub
2. GitHub Actions pipeline starts
3. Staging deployment runs automatically
4. Production deployment waits for approval
5. Reviewer approves deployment
6. Application deploys to production