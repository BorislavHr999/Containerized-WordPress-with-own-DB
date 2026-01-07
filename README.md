# 🚀 Containerized WordPress with Nginx Proxy

A high-performance WordPress setup using **Docker Compose**, featuring a custom Nginx reverse proxy and advanced health checks. ✨

### 🛠 Tech Stack:
* **🌐 Nginx Proxy:** Efficiently handles traffic on port `80`.
* **🐘 MariaDB + Healthcheck:** WordPress waits for DB readiness (`service_healthy`).
* **🔒 Secure Env:** Sensitive credentials managed via `.env`.
* **🐳 Docker Optimized:** Seamless container orchestration and networking.

### 🚦 Quick Start:
1. Copy `.env.example` to `.env` and set your passwords. 📝
2. Run `docker compose up -d` 🐳
3. Open `http://localhost` and start building! 💻
