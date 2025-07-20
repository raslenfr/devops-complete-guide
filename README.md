# 🚀 DevOps Project Guide

📘 I’ve gathered and shared all my knowledge about DevOps in this complete guide (PDF). It covers essential concepts, tools, workflows, and best practices—perfect for anyone starting out or looking to deepen their DevOps skills.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

--------> Welcome to my DevOps setup repository! This project includes hands-on configuration and use of essential DevOps tools such as Git, GitBucket, Jenkins, Chef, Docker, Maven, Apache Tomcat, and Ansible.

## 📚 Table of Contents

- [🔧 Git & GitBucket](#-git--gitbucket)
- [👨‍🍳 Chef (Configuration Management)](#-chef-configuration-management)
- [🐳 Docker (Containerization)](#-docker-containerization)
- [📦 Maven (Build Tool)](#-maven-build-tool)
- [🧪 Jenkins (CI/CD)](#-jenkins-cicd)
- [🌐 Tomcat (Web Server)](#-tomcat-web-server)
- [🤖 Ansible (Automation)](#-ansible-automation)
- [🔁 Pipeline Automation](#-pipeline-automation)
- [🗃️ Backups & Restore](#️-backups--restore)

---

## 🔧 Git & GitBucket

Version control and collaboration setup:

- 🧱 Initialize project: `git init`
- 📥 Stage files: `git add .`
- ✅ Commit changes: `git commit -m "message"`
- 🌿 Branching: `git branch`, `git checkout`, `git merge`
- 🐙 GitBucket hosted locally via `.war` or Docker
- 📌 Tag versions & manage stash
- 🔗 Connect to remote: `git remote add origin <url>`

---

## 👨‍🍳 Chef (Configuration Management)

Automated infrastructure configuration using Ruby DSL:

- 🍽️ Write Cookbooks & Recipes
- 🔁 Manage Nodes, Roles & Environments
- 📦 Example cookbooks: Apache, User & Group management
- 📤 Upload via `knife cookbook upload`
- 🧩 Connect with Workstation, Node, and Server

---

## 🐳 Docker (Containerization)

Lightweight container-based virtualization:

- 🔧 Install Docker Engine
- 📦 Create & run containers: `docker run -ti ubuntu /bin/bash`
- 📂 Manage containers: `docker ps`, `docker stop`, `docker rm`
- 🛠️ Build custom images via `Dockerfile`
- 🚢 GitBucket & Jenkins deployment in containers
- 🌍 Port forwarding: `docker run -p 80:8080`

---

## 📦 Maven (Build Tool)

Dependency management and build automation:

- 🔨 Install Maven & configure environment
- 🧪 Build lifecycle: `mvn validate`, `compile`, `test`, `package`
- 📁 Project structure via `pom.xml`
- 🔗 Git integration for source management
- ⚙️ Use with Jenkins for full CI pipeline

---

## 🧪 Jenkins (CI/CD)

Continuous Integration & Deployment:

- ⚙️ Install via `.war` file or Docker
- 🛠️ Create Freestyle or Maven projects
- 📥 Connect Git repository for SCM
- 🧱 Build, test, and package automatically
- 🔌 Install plugins: Git, Maven, Deploy to container
- 🧰 Manage jobs, triggers, and workspaces

---

## 🌐 Tomcat (Web Server)

Host and manage Java web applications:

- 🏗️ Install Apache Tomcat 8
- 📁 Deploy `.war` files (e.g., GitBucket, Jenkins)
- 🔐 Set user roles in `tomcat-users.xml`
- 🔄 Enable system service for auto-restart

---

## 🤖 Ansible (Automation)

Agentless automation using SSH:

- 🧠 Write playbooks in YAML
- 📋 Inventory: `/etc/ansible/hosts`
- 🛠️ Commands: `ansible all -m ping`, `ansible-playbook file.yml`
- 🔐 SSH key-based access
- ⚙️ Install packages, configure services, manage users

---

## 🔁 Pipeline Automation

🧩 Combine tools into a seamless CI/CD workflow:

1. ✅ Maven Compile
2. 🧪 Maven Test
3. 📦 Maven Package
4. 🚀 Deploy `.war` to Tomcat via Jenkins
5. 🔁 Trigger via GitBucket webhook and token

---

## 🗃️ Backups & Restore

### 📤 GitBucket
- Backup `.gitbucket` hidden directory for repository state

### 💾 Jenkins
- Use **Backup Plugin** via Dashboard
- 🔙 Restore using saved Hudson configuration

---

## ⚙️ Tools Used

- 🐙 Git & GitBucket
- 👨‍🍳 Chef
- 🐳 Docker
- 📦 Maven
- 🧪 Jenkins
- 🌐 Tomcat
- 🤖 Ansible

---

## 📋 Prerequisites

- 🐧 Ubuntu/Debian OS
- ☕ Java 8
- 📡 Internet connection
- 🔐 SSH keys configured for remote access

---

## 📜 License

This DevOps repository is built for educational and demonstration purposes. Feel free to fork and adapt!

---

> ⭐ *Don’t forget to star this repository if you found it helpful!*

