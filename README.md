# 🚀 Two-Tier Flask + MySQL Application (Dockerized)

A containerized **two-tier web application** built using **Flask (Python)** as the backend and **MySQL** as the database. The project uses **Docker Compose** to manage multi-container deployment, networking, and persistent storage.

This project is built for hands-on **DevOps learning** covering Docker, container networking, volumes, and service orchestration.

---

# 📌 Features

- Flask backend API
- MySQL database integration
- Dockerized multi-container setup
- Docker Compose orchestration
- Service-to-service communication using Docker networking
- Persistent database storage using Docker volumes
- Health checks for MySQL service
- Environment-based configuration
- Easy one-command deployment

---

# 🧠 Architecture
            ┌──────────────────────┐
            │  Flask Application   │
            │  (Python Backend)    │
            └─────────┬────────────┘
                      │
           Docker Network Communication
                      │
            ┌─────────▼────────────┐
            │   MySQL Database     │
            │   (Persistent Data)  │
            └──────────────────────┘


---

# 🛠️ Tech Stack

- Python 3.9+
- Flask
- MySQL 8
- Docker
- Docker Compose
- Linux (Ubuntu / WSL / EC2)

---

# 📁 Project Structure
two-tier-flask-app/
│
├── app.py # Flask application
├── requirements.txt # Python dependencies
├── Dockerfile # Flask image build file
├── docker-compose.yml # Multi-container setup
└── README.md # Project documentation


---

# ⚙️ Prerequisites

Make sure you have installed:

- Docker
- Docker Compose

Check versions:

```bash
docker --version
docker compose version

🚀How to Run the Project

. Clone Repository
git clone https://github.com/chirayu-webkorps/Two-Tier-Flask-MySQL-Application
cd two-tier-flask-app
2. Build and Start Containers
docker compose up --build

This will:
Build Flask image
Pull MySQL image
Create network
Start both services
3. Access Application

Open browser:

http://localhost:5000
