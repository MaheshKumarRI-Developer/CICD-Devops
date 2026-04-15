# 🚀 CI/CD DevOps Pipeline with GitLab & Docker

This project demonstrates a real-world CI/CD pipeline using **GitLab CI/CD**, **Docker**, and **AWS EC2**, with the repository mirrored to GitHub for public visibility.

---

## 📌 Overview

The goal of this project is to automate the complete workflow from code commit to production deployment.

It showcases how modern DevOps practices can be used to:

* Automate build and deployment
* Ensure consistent environments using Docker
* Reduce manual intervention in release cycles

---

## 🏗️ Architecture


**Flow:**

Developer → Git Push → GitLab CI/CD → Build → Dockerize → Deploy → EC2 Server

---

## ⚙️ Tech Stack

* **Frontend:** React.js
* **CI/CD:** GitLab CI/CD
* **Containerization:** Docker
* **Cloud:** AWS EC2
* **Version Control:** GitLab (Primary), GitHub (Mirror)

---

## 🔄 CI/CD Pipeline Flow

1. Code is pushed to GitLab repository
2. GitLab CI/CD pipeline is triggered automatically
3. Pipeline stages:

   * Install dependencies
   * Build application
   * Create Docker image
   * Deploy application to server
4. Repository is mirrored to GitHub for public access

---

## 🔧 GitLab CI/CD Configuration

The pipeline is defined using `.gitlab-ci.yml` and follows a multi-stage process:

* **Build Stage:** Installs dependencies and builds the React app
* **Docker Stage:** Creates Docker image for the application
* **Deploy Stage:** Deploys the container to the server

---

## 🐳 Docker Usage

Docker is used to:

* Ensure consistency across development and production
* Avoid environment-related issues
* Simplify deployment using containerized applications

---

## ☁️ Deployment

* Application is deployed on **AWS EC2**
* Deployment is automated via CI/CD pipeline
* No manual steps required after code push

---

## 🎯 Key Learnings

* Implemented end-to-end CI/CD pipeline using GitLab
* Automated build and deployment workflows
* Used Docker for containerized deployment
* Integrated frontend development with DevOps practices

---

## 📌 Notes

* GitLab is used for CI/CD execution
* GitHub repository is used for showcasing the project (mirror setup)

---

## 🚀 Future Improvements

* Add automated testing stage in pipeline
* Integrate Docker Hub for image storage
* Implement Kubernetes for scaling
* Add monitoring using Grafana / Prometheus

---
