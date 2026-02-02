# Elearn Frontend 🚀

This repository contains the **frontend application** for the Elearn project, containerized with Docker for easy deployment and local testing.

---

## 📦 Prerequisites
- [Docker](https://docs.docker.com/get-docker/) installed on your system
- Basic knowledge of Docker commands

---

## ▶️ Run Locally with Docker

To start the frontend application inside a Docker container:

```bash
docker build -t elearn-frontend .
docker run -d -p 8080:80 --name elearn-frontend-container elearn-frontend
