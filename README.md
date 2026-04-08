GitHub Actions CI/CD Project 🚀

 **Project Overview**

This project demonstrates a complete CI/CD pipeline using GitHub Actions to build, containerize, and deploy a Java-based application.

Whenever code is pushed to GitHub, the pipeline automatically builds the application, creates a Docker image, pushes it to DockerHub, and deploys it on an AWS EC2 instance.

**🏗️ Architecture**

GitHub → GitHub Actions → DockerHub → AWS EC2 → User Access

## ⚙️ Tools Used

| Tool           | Purpose            |
|----------------|-------------------|
| GitHub Actions | CI/CD Automation  |
| Docker         | Containerization  |
| DockerHub      | Image Repository  |
| AWS EC2        | Deployment Server |
| Maven          | Build Tool        |
| Java           | Application       |

 **CI/CD Pipeline Flow**
 
1.Code pushed to GitHub
2.GitHub Actions pipeline triggered
3.Maven builds JAR file
4.Docker image is created
5.Image pushed to DockerHub
6.EC2 instance accessed via SSH
7.Container deployed automatically
8.Application becomes live

## 📂 Project Structure

- `.github/workflows/cicd.yml` → Pipeline configuration  
- `Dockerfile` → Container build instructions  
- `pom.xml` → Maven configuration  
- `src/` → Java source code  
- `screenshots/` → Project proof  

## 🔐 GitHub Secrets Used

- `DOCKERHUB_USERNAME`  
- `DOCKERHUB_TOKEN`  
- `EC2_HOST`  
- `EC2_USER`  
- `EC2_SSH_KEY`

**screenshots/**

## 📸 Screenshots

The following screenshots are available in the `screenshots/` folder:

- `github-actions-success.png` → Pipeline execution success  
- `dockerhub-image.png` → Image pushed to DockerHub  
- `ec2-docker-ps.png` → Running container on EC2  
- `application-running.png` → Application accessible in browser  

  
