# WordPress Docker Stack

Ce projet déploie une stack WordPress + MySQL avec Docker Compose.

## 📁 Structure du projet

- `compose.yml` : Configuration principale des services
- `.env` : Contient les variables d’environnement **non sensibles**
- `secrets/` : Contient les mots de passe utilisés via Docker Secrets
- `volumes` : Créés automatiquement pour persistance

## ▶️ Démarrage rapide

```bash
docker compose up -d

