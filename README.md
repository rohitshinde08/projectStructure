## 🧩 Tech Stack Overview

### 🌐 Frontend
- **Node.js:** 20.x (LTS)
- **React:** 18.x
- **npm:** Bundled with Node.js 20.x
- **Build Tool:** Vite

---

### ⚙️ Backend
- **Python:** 3.11.x
- **FastAPI:** ≥ 0.110.0
- **Uvicorn:** ≥ 0.27.0

---

### 🗄️ Databases
- **PostgreSQL:** 15.x  
  *(Primary relational database)*
- **MongoDB:** Cloud-hosted  
  *(MongoDB Atlas – latest stable, used for flexible / document-based data)*

---

### 🐳 Containerization & OS
- **Docker Engine:** 24.x+
- **Frontend Base Image:** `node:20-alpine`
- **Backend Base Image:** `python:3.11-slim`
- **Base OS:** Debian (stable)

---


## ▶️ Getting Started

### Prerequisites
- Docker & Docker Compose
- Node.js 20.x (for local frontend development)
- Python 3.11.x (for local backend development)

---

### Run with Docker (Recommended)

```bash

docker compose up --build
```

---

## 📂Folder Structure

   
   
    Project Directory/
    ├── docker-compose.yaml
    ├── docker-compose.local.yaml
    ├── README.md
    │
    ├── backend/
    │   ├── Dockerfile
    │   ├── requirements.txt
    │   └── app/
    │       ├── main.py
    │       ├── database.py
    │       ├── models/
    │       ├── routes/
    │       ├── schemas/
    │       ├── services/
    │       ├── utils/
    │       └── main.py
    │
    ├── frontend/
    │   ├── Dockerfile
    │   ├── package.json
    │   ├── vite.config.js
    │   ├── index.html
    │   └── src/
    │       ├── assets/
    │       ├── components/
    │       ├── pages/
    │       │   ├── admin/
    │       │   ├── student/
    │       │   └── superAdmin/
    │       ├── layouts/
    │       ├── utils/
    │       ├── App.jsx
    │       └── main.jsx





