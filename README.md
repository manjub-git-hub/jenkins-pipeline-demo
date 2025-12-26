# Jenkins Pipeline Demo

## Project Overview
This project demonstrates a **basic Jenkins Pipeline** using a **declarative Jenkinsfile**.  
The pipeline is connected to a GitHub repository and automates a simple CI/CD workflow.

## Features
- **Pipeline as Code:** Defined in `Jenkinsfile` in the GitHub repo  
- **Stages Implemented:**  
  - **Build:** Simulates a build process  
  - **Test:** Simulates a test process  
- **Integration:** Jenkins pulls code directly from GitHub  
- **Automated Execution:** Pipeline runs automatically when triggered in Jenkins

## Architecture
- **EC2 Instance:** Hosts Jenkins server  
- **Security Group:** Allows SSH (port 22) and Jenkins web access (port 8080)  
- **Jenkinsfile:** Located in the root of the repository  
- **Pipeline:** Declarative, multi-stage pipeline (Build, Test)

## How to Use
1. Clone the repository:
```bash
git clone https://github.com/manjub-git-hub/jenkins-pipeline-demo.git
