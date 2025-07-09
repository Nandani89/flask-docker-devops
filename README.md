# 🚀 Flask + Docker DevOps Project

This is a simple Python Flask web app that displays a message inside the browser. The app is containerized using Docker and deployed with a CI/CD pipeline using GitHub Actions.

---

## 🛠️ Tech Stack

- Python 3.9
- Flask
- Docker
- Git & GitHub
- GitHub Actions (CI/CD)
- WSL (Ubuntu)

---

## 📦 Features

- ✅ Flask web app that runs on port `5000`
- ✅ Dockerized with custom `Dockerfile`
- ✅ CI/CD with GitHub Actions to build on every push
- ✅ Fully configured inside WSL with no need for Docker Desktop

---

## 🚨 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/Nandani89/flask-docker-devops.git
cd flask-docker-devops

# Build Docker image
docker build -t flask-docker-app .

# Run container
docker run -p 5000:5000 flask-docker-app

