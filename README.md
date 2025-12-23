# Integrated Docker Project

## 📌 Project Overview
This project demonstrates an integrated Docker workflow using Dockerfile, Docker Compose, and Docker Volumes to deploy a custom Nginx-based static website.

## 🛠 Tools & Technologies
- Linux (Ubuntu)
- Docker
- Docker Compose (v2)
- Docker Volumes
- Nginx
- Git & GitHub

## 🚀 What This Project Does
- Builds a custom Docker image using a Dockerfile
- Uses Docker Compose to manage the container lifecycle
- Uses Docker volumes for persistent data and live updates
- Serves a static HTML website via Nginx

## 📂 Project Structure
.
├── Dockerfile
├── docker-compose.yml
├── html/
│ └── index.html
└── README.md


## ▶️ How to Run the Project

```bash
docker compose up -d --build

Open in browser:
http://localhost:8086

To stop:
docker compose down


🧠 Key Concepts Learned
Difference between image and container

Dockerfile best practices

Docker volumes vs bind mounts

Docker Compose orchestration

Production-style container workflow

📌 Author
Fathima

