# Dockerized Odysseus AI Platform Deployment

## Project Highlights

* Multi-container Docker Compose deployment
* Nginx reverse proxy implementation
* Container networking and service discovery
* Persistent volume management
* Self-hosted AI productivity platform
* Container monitoring and troubleshooting

---

## Project Overview

This project demonstrates the deployment of the Odysseus AI productivity platform using Docker Compose and multiple supporting services.

The deployment includes:

* Odysseus Application
* Nginx Reverse Proxy
* ChromaDB Vector Database
* SearXNG Search Engine
* NTFY Notification Service

The platform was deployed locally using Docker and Docker Compose and configured for persistent storage, container networking, and reverse proxy access.

---

## Architecture

```text
+------------------+
|   User Browser   |
+--------+---------+
         |
         v
+------------------+
|  Nginx Proxy     |
|   Port 8088      |
+--------+---------+
         |
         v
+------------------+
|    Odysseus      |
|    Port 7000     |
+--------+---------+
         |
         v
+------------------+
| Supporting       |
| Services         |
| - ChromaDB       |
| - SearXNG        |
| - NTFY           |
+------------------+
```

---

## Technologies Used

* Docker
* Docker Compose
* Nginx
* ChromaDB
* SearXNG
* NTFY
* PowerShell
* Windows

---

## Key Tasks Performed

* Deployed Odysseus using Docker Compose
* Managed multi-container architecture
* Configured container networking
* Configured persistent storage volumes
* Added Nginx reverse proxy layer
* Verified service connectivity
* Managed container lifecycle operations
* Monitored running containers and services
* Troubleshot deployment issues

---

## Screenshots

### Running Containers

![Docker Containers](screenshots/docker-containers.png)

### Odysseus Application

![Odysseus Homepage](screenshots/odysseus-homepage.png)

### Nginx Reverse Proxy

![Nginx Reverse Proxy](screenshots/nginx-reverse-proxy.png)

---

## Commands Used

```bash
docker compose up -d
docker ps
docker compose ls
docker compose config
```

---

## Outcome

Successfully deployed and managed a containerized AI productivity platform using Docker Compose, Nginx reverse proxy, and supporting services while implementing container networking, persistent storage, and service monitoring.

