Versions

Frontend
Node.js: 20.x (LTS)
React: 18.x
npm: Bundled with Node.js 20.x

Backend
Python: 3.11.x
FastAPI: >= 0.110.0
Uvicorn: >= 0.27.0

Database
PostgreSQL: 15.x
MongoDB: Cloud-hosted (MongoDB Atlas – latest stable)

Containerization
Docker Engine: 24.x+
Frontend Base Image: node:20-alpine
Alpine Linux: 3.19
Backend Base Image: python:3.11-slim
Base OS: Debian (stable)
   
   
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
            ├── utils/
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
    │       ├── services/
    │       ├── utils/
    │       ├── App.jsx
    │       └── main.jsx
