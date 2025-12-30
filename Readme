# Jenkins CI/CD Pipeline with GitHub, SonarQube, and Docker on AWS EC2

This project demonstrates how to set up a complete **CI/CD pipeline** using **Jenkins**, **GitHub**, **SonarQube**, and **Docker** on an **AWS EC2 instance**. The pipeline automates code integration, quality analysis, build, and deployment processes.

---

## 🚀 Project Overview

In this project, we:

* Launch an AWS EC2 instance
* Install and configure Jenkins
* Integrate Jenkins with a GitHub repository
* Set up SonarQube for static code analysis
* Build Docker images using Jenkins
* Deploy the application using Docker

By the end, you will have a fully functional CI/CD pipeline that ensures **code quality**, **automation**, and **faster deployments**.

---

## 🛠️ Tools & Technologies Used

* **AWS EC2** – Virtual server to host Jenkins, SonarQube, and Docker
* **Jenkins** – Automation server for CI/CD
* **GitHub** – Source code management
* **SonarQube** – Code quality and security analysis
* **Docker** – Application containerization
* **Linux (Ubuntu)** – Operating system

---

## 🧩 Architecture Flow

1. Developer pushes code to GitHub
2. GitHub webhook triggers Jenkins pipeline
3. Jenkins:

   * Pulls code from GitHub
   * Runs SonarQube code analysis
   * Builds Docker image
   * Deploys application using Docker

---

## 📦 Prerequisites

Before starting, make sure you have:

* AWS account
* GitHub account
* Basic knowledge of:

  * Linux commands
  * Git & GitHub
  * Docker
  * Jenkins

---

## ⚙️ Step-by-Step Setup

### 1️⃣ Launch AWS EC2 Instance

* Launch an **Ubuntu EC2 instance**
* Open required ports in the security group:

  * `22` – SSH
  * `8080` – Jenkins
  * `9000` – SonarQube
  * `80` – Application (optional)

---

### 2️⃣ Install Jenkins

* Install Java (OpenJDK)
* Add Jenkins repository
* Install and start Jenkins
* Access Jenkins via:

```
http://<EC2-Public-IP>:8080
```

---

### 3️⃣ Configure GitHub Integration

* Create a GitHub repository
* Generate GitHub webhook
* Configure Jenkins job or pipeline to pull code from GitHub

---

### 4️⃣ Install & Configure SonarQube

* Install SonarQube on EC2
* Access SonarQube via:

```
http://<EC2-Public-IP>:9000
```

* Generate SonarQube token
* Configure SonarQube server in Jenkins

---

### 5️⃣ Install Docker

* Install Docker on EC2
* Add Jenkins user to Docker group
* Verify Docker installation

---

### 6️⃣ Create Jenkins Pipeline

The pipeline includes stages such as:

* Checkout code from GitHub
* SonarQube code analysis
* Build Docker image
* Run Docker container

---

## 📄 Sample Jenkins Pipeline Stages

* **Checkout** – Pull code from GitHub
* **Code Quality Check** – SonarQube scan
* **Build** – Docker image creation
* **Deploy** – Run container

---

## ✅ Benefits of This CI/CD Pipeline

* Automated builds and deployments
* Improved code quality
* Faster development lifecycle
* Reduced manual errors
* Scalable and production-ready setup

---

## 📌 Conclusion

This project helps you understand how real-world CI/CD pipelines are built using industry-standard tools. It is ideal for **DevOps beginners**, **cloud learners**, and anyone preparing for **DevOps interviews**.

---

## 📬 Contact

If you have questions or want to improve this project, feel free to contribute or reach out.

Happy Learning 🚀
