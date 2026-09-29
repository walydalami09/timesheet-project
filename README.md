# DevOps Project – Timesheet Application

Projet réalisé dans le cadre de ma formation d’ingénieur afin de mettre en pratique les principes et outils DevOps autour d’une application Java.

## Objectifs

- Mise en place d’un pipeline CI/CD avec Jenkins
- Gestion du build et des dépendances avec Maven
- Analyse de la qualité du code avec SonarQube
- Conteneurisation de l’application avec Docker
- Gestion de plusieurs services avec Docker Compose
- Déploiement et orchestration avec Kubernetes
- Monitoring avec Prometheus et Grafana

## Stack technique

**Application :** Java, Maven  
**CI/CD :** Jenkins  
**Conteneurisation :** Docker, Docker Compose  
**Orchestration :** Kubernetes  
**Qualité :** SonarQube  
**Monitoring :** Prometheus, Grafana  
**Versioning :** Git, GitHub

## Architecture DevOps

Code source
→ Maven
→ Jenkins
→ SonarQube
→ Docker
→ Kubernetes
→ Prometheus / Grafana

## Docker

Construction de l'image :

```bash
docker build -t timesheet-project .
