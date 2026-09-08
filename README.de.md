<h1 align="center">📋 Docker Planka</h1>

<p align="center">
  <em>Docker Compose Bereitstellung für Planka, ein selbstgehostetes Task- und Projektmanagement-Tool</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose">
</p>

<p align="center">
  <a href="README.md">🇬🇧 English version</a>
</p>

---

## 📖 Über das Projekt

Eine Docker Compose-Konfiguration zur Bereitstellung von Planka, einem modernen selbstgehosteten Task-Management- und Projektorganisations-Tool mit einer sauberen, intuitiven Benutzeroberfläche.

## 🛠️ Tech-Stack

| Technologie | Version | Zweck |
|---|---|---|
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) Docker | Latest | Container-Laufzeit |
| ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) Docker Compose | 1.29+ | Orchestrierung |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) PostgreSQL | 13+ | Datenbank |

## ✨ Funktionen

- **Task-Management** — Organisiere Arbeit mit Boards und Karten
- **Kollaborativ** — Teile Projekte und weise Aufgaben zu
- **Selbstgehostet** — Halte deine Daten privat auf deinem eigenen Server
- **Persistente Speicherung** — PostgreSQL-Datenbank für Zuverlässigkeit

## 🚀 Erste Schritte

### Voraussetzungen

- Docker
- Docker Compose

### Installation

```bash
git clone https://github.com/cooolinho/docker-planka.git
cd docker-planka
cp .env.example .env
docker compose up -d
```

### Konfiguration

Bearbeite `.env`, um Datenbankzugansdaten und Port zu setzen:

```bash
POSTGRES_PASSWORD=yourpassword
PLANKA_PORT=3000
```

Greife auf Planka unter `http://localhost:3000` zu.

## 📋 Verwendung

```bash
# Dienste starten
docker compose up -d

# Logs anzeigen
docker compose logs -f

# Dienste beenden
docker compose down
```

## 📄 Lizenz

Freigegeben unter der MIT-Lizenz.
