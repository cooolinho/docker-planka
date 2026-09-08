<h1 align="center">📋 Docker Planka</h1>

<p align="center">
  <em>Docker Compose deployment for Planka, a self-hosted task and project management application</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose">
</p>

<p align="center">
  <a href="README.de.md">🇩🇪 Deutsche Version</a>
</p>

---

## 📖 About

A Docker Compose configuration for deploying Planka, a modern self-hosted task management and project organization tool with a clean, intuitive interface.

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) Docker | Latest | Container runtime |
| ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) Docker Compose | 1.29+ | Orchestration |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) PostgreSQL | 13+ | Database |

## ✨ Features

- **Task management** — Organize work with boards and cards
- **Collaborative** — Share projects and assign tasks
- **Self-hosted** — Keep your data private on your own server
- **Persistent storage** — PostgreSQL database for reliability

## 🚀 Getting Started

### Prerequisites

- Docker
- Docker Compose

### Installation

```bash
git clone https://github.com/cooolinho/docker-planka.git
cd docker-planka
cp .env.example .env
docker compose up -d
```

### Configuration

Edit `.env` to set database credentials and port:

```bash
POSTGRES_PASSWORD=yourpassword
PLANKA_PORT=3000
```

Access Planka at `http://localhost:3000`.

## 📋 Usage

```bash
# Start services
docker compose up -d

# View logs
docker compose logs -f

# Stop services
docker compose down
```

## 📄 License

Released under the MIT License.
