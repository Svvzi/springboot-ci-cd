# Spring Boot CI/CD – EFREI Master 1

## Pipeline CI/CD
- Build Maven
- Analyse Trivy
- Docker image + Push DockerHub
- Déploiement automatique sur VM locale

## Structure
- `Dockerfile` : pour builder l'app
- `.github/workflows/ci.yml` : pipeline CI/CD GitHub Actions
- `src/` : code Spring Boot

## Déploiement
