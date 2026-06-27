# 🚀 AWS DevOps CI/CD Pipeline for Static Website Deployment

## 📌 Project Summary

This project demonstrates an end-to-end CI/CD pipeline for deploying a static website using AWS, Jenkins, Docker, GitHub, and GitHub Webhooks.

Whenever a developer pushes code to GitHub, GitHub Webhooks automatically trigger Jenkins. Jenkins fetches the latest source code, builds the project, and deploys the website to both the Jenkins Master and Jenkins Agent (Node).

The project also demonstrates distributed builds using Jenkins Multi-Configuration Jobs.


## 🎯 Project Objectives

- Automate website deployment using Jenkins.
- Integrate GitHub with Jenkins using Webhooks.
- Deploy the same website on multiple servers.
- Learn CI/CD pipeline implementation.
- Understand Jenkins Master-Agent architecture.
- Perform distributed builds using Multi-Configuration Jobs.


## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| AWS EC2 | Hosting Jenkins Master, Agent and Developer Server |
| Jenkins | CI/CD Automation |
| Git | Version Control |
| GitHub | Source Code Repository |
| GitHub Webhooks | Automatic Build Trigger |
| Docker | Containerized Deployment |
| HTML | Static Website |
| CSS | Website Styling |
| JavaScript | Website Functionality |
| Linux (Ubuntu) | Server Operating System |


## 🏗️ Project Architecture

Developer

⬇

GitHub Repository

⬇ (GitHub Webhook)

Jenkins Master

⬇

Jenkins Agent (JNLP)

⬇

Docker Container

⬇

Website Deployment on Jenkins Master

AND

Website Deployment on Jenkins Agent


## 🔄 CI/CD Workflow

1. Developer pushes code to GitHub.
2. GitHub Webhook automatically triggers Jenkins.
3. Jenkins pulls the latest source code.
4. Jenkins builds the project.
5. Docker image is created.
6. Docker container starts.
7. Website is deployed on Jenkins Master.
8. Website is deployed on Jenkins Agent.
9. Multi-Configuration Job executes builds on both servers.


## ✨ Key Features

✅ Jenkins Freestyle Job

✅ Jenkins Multi-Configuration Job

✅ GitHub Webhook Integration

✅ Docker Deployment

✅ AWS EC2 Infrastructure

✅ Jenkins Master-Agent Architecture

✅ Automatic Website Deployment

✅ Distributed Build Execution


## 📂 Repository Structure
.
├── css/
├── fonts/
├── images/
├── js/
├── screenshots
├── Dockerfile
├── index.html
├── project-detail.html
└── README.md


## 📷 Project Screenshots

### AWS EC2 Instances />
creenshot here)


### GitHub Repository

(Add GitHub Repository screenshot here)


### GitHub Webhook Configuration

(Add Webhook screenshot here)


### Jenkins Freestyle Job (Master)

(Add Screenshot)


### Jenkins Freestyle Job (Agent)

(Add Screenshot)


### Multi-Configuration Job

(Add Screenshot)


### Website Successfully Running on Jenkins Master before code chnages and after code changes

(Add Screenshot)


### Website Successfully Running on Jenkins Agent before code chnages and after code changes

(Add Screenshot)


## 📈 Skills Demonstrated

- AWS EC2 Management
- Jenkins Installation & Configuration
- Jenkins Master-Agent Setup (JNLP)
- Git & GitHub
- GitHub Webhooks
- Docker Basics
- CI/CD Pipeline
- Linux Commands
- Static Website Deployment
- Multi-Configuration Jobs


## 💡 Challenges Faced

- Configuring Jenkins Agent using JNLP.
- Connecting GitHub Webhooks with Jenkins.
- Deploying website simultaneously on multiple servers.
- Creating Multi-Configuration Jobs.


## 👨‍💻 Author

**Amarjeet Kumar**

AWS DevOps Fresher

GitHub: https://github.com/Amarjeet-467

---

⭐ Thank you for visiting this repository.
