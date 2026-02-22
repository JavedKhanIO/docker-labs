# 🐳 Docker Labs

This repository contains a collection of mini-projects and experiments created while learning Docker, containerization, and CI/CD workflows.

It represents my hands-on learning journey — from basic Dockerfiles to multi-container applications and automated pipelines.

---

## 📁 Projects Included among others: 

### 1️⃣ Log Aggregator
A containerized logging demo that:
- Collects application logs
- Processes structured output
- Demonstrates Docker build + run workflow
- Includes CI pipeline for build validation

---

### 2️⃣ Flcker networking demo
A simple Flask application containerized using:
- Custom Dockerfile
- Exposed ports
- Environment variables
- Image build & run automation

---

### 3️⃣ Multi-App Demo
A multi-container setup demonstrating:
- Docker Compose
- Service communication
- Network isolation
- Dependency orchestration

---

### 4️⃣ Nelog cleaner:
- Cleans logs older than 7 days
- prints deleted file name with timestamp

---

## ⚙️ CI/CD

Each mini-project includes isolated CI workflows configured to:

- Trigger only when relevant project files change
- Build Docker images
- Validate container startup
- Ensure modular pipeline execution

This approach simulates mono-repo pipeline control with path-based triggers.

---

## 🛠 Tech Stack

- Docker
- Docker Compose
- GitHub Actions (CI)
- Linux CLI
- Bash scripting

---

## 🎯 Purpose of This Repository

This repository is focused on:

- Strengthening container fundamentals
- Understanding image layering & optimization
- Practicing CI/CD isolation per project
- Experimenting safely before production use

---

## 🚀 How to Run a Project

Navigate to a specific project folder:

```bash
cd log-aggregator
docker build -t log-aggregator .
docker run -p 5000:5000 log-aggregator
```
Or use Docker Compose where available

```bash
docker compose up --build
```

📌 Note

These are learning-oriented projects and may evolve over time as I continue refining containerization practices and pipeline design.

👨‍💻 Author

Javed Khan
DevOps & Infrastructure Enthusiast
