
    
    style DB fill:#f9f,stroke:#333,stroke-width:2px
    style Nginx fill:#bbf,stroke:#333,stroke-width:2px# 🛡️ Secure Zero-Trust WordPress

A high-performance WordPress setup using **Docker Compose**, featuring a custom Nginx reverse proxy and strict network isolation (3-Tier Architecture). ✨

### 🛠 Tech Stack
* 🌐 **Nginx Proxy:** Efficiently handles traffic on port 80, isolating the backend.
* 🐘 **MariaDB:** Completely hidden in a private network with `service_healthy` checks.
* 🔒 **Secure Env:** Sensitive credentials managed strictly via `.env`.
* 🐳 **Docker Optimized:** Seamless orchestration with Zero-Trust security principles.

### 🚦 Quick Start
Copy `.env.example` to `.env` 📝, run `docker compose up -d` 🐳, and start building at `http://localhost` 💻.
