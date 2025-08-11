# Jenkins Zero to Hero 🎓🚀

Welcome to the official repository for the **Jenkins Zero to Hero** tutorial series! This repository contains all the examples, configuration files, and code used throughout the playlist to help you learn Jenkins from beginner to advanced level.

---

## 📂 Repository Structure

```bash
.
├── 01-installation/           # Jenkins installation & setup
├── 02-basic-pipeline/         # Basic pipeline with Jenkinsfile
├── 03-docker-integration/     # Using Jenkins with Docker
├── 04-advanced-pipeline/      # Parallel stages, shared libs, etc.
├── 05-deployment/             # CI/CD pipeline with deployment steps
├── 06-jenkins-on-kubernetes/  # Running Jenkins in Kubernetes
├── shared-libraries/          # Reusable Jenkins pipeline code
├── scripts/                   # Bash, Groovy scripts used in pipelines
├── jenkins.yaml               # Jenkins Configuration as Code (JCasC)
└── README.md

✅ What You'll Learn
✅ How to install Jenkins (locally, Docker, or cloud)

✅ Creating freestyle jobs and pipeline jobs

✅ Writing and using Jenkinsfile (Declarative and Scripted)

✅ Using Docker with Jenkins

✅ Integrating Jenkins with GitHub, Maven, Gradle, and more

✅ CI/CD best practices

✅ Jenkins on Kubernetes

✅ Jenkins Configuration as Code (JCasC)

✅ Creating and using Shared Libraries

✅ Pipeline triggers, webhooks, and credentials

🧰 Requirements
Git

Docker (for container-based setup)

Java 8 or later

Optional: Kubernetes (for advanced sections)

🚀 Getting Started
Clone the repo
bash
Copy
Edit
git clone https://github.com/your-username/jenkins-zero-to-hero.git
cd jenkins-zero-to-hero
Run Jenkins using Docker (Basic Setup)
bash
Copy
Edit
docker run -d -p 8080:8080 -p 50000:50000 \
  -v jenkins_home:/var/jenkins_home \
  jenkins/jenkins:lts
Access Jenkins at http://localhost:8080

📘 Docs & Resources
Official Jenkins Documentation

Pipeline Syntax Guide

Jenkins GitHub Plugin

Jenkins Shared Libraries

🙌 Contributing
Contributions, pull requests, and suggestions are welcome!

If you find an issue or want to enhance a specific part of the tutorial examples, feel free to open a PR or submit an issue.

📄 License
This repository is licensed under the MIT License.

⭐️ Support the Project
If you found the playlist and this repo helpful:

⭐️ Star this repo

Happy Jenkins-ing! 🛠️💙

yaml
Copy
Edit

---

