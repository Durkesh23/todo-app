# 🚀 Task Manager App with CI/CD (DevOps Project)

## 📌 Project Overview

This is a simple Task Manager web application built to demonstrate a complete DevOps workflow including Docker containerization and CI/CD automation.

---

## 🛠️ Technologies Used

* HTML, CSS, JavaScript
* Docker
* GitHub Actions
* Docker Hub

---

## ⚙️ Features

* Add and delete tasks
* Simple user interface
* Runs inside Docker container

---

## 🐳 Docker Implementation

* Created a Dockerfile using Nginx
* Built Docker image
* Ran container using port mapping

---

## 🔁 CI/CD Pipeline

Implemented using GitHub Actions:

* Trigger: Push to main branch
* Steps:

  * Checkout code
  * Login to Docker Hub
  * Build Docker image
  * Push image to Docker Hub

---

## 📦 Docker Image

Available on Docker Hub:
durkesh14/todo-app

---

## ▶️ Run Locally

```bash
docker build -t todo-app .
docker run -p 8080:80 todo-app
```

---

## 🎯 Conclusion

This project demonstrates real-world DevOps practices like containerization and CI/CD automation.

---
