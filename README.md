# Inti Configuration Files

This repository contains the deployment configuration files for the Inti AI voice interface project.

## Files

- `swarm-deploy.yml` - Docker Swarm deployment configuration for the complete stack
- `.env` - Environment variables (contains sensitive tokens - not committed)
- `docker-compose.yml` - Alternative Docker Compose configuration (if present)

## Deployment Stack

The deployment includes:
- Frontend PWA (Next.js with React)
- Backend API server  
- LLM service (Gemma 3n model)
- STT (Speech-to-Text) service
- TTS (Text-to-Speech) service 
- Traefik reverse proxy with SSL
- Network overlay for service communication

## Key Domains

- Main PWA: https://inti.intellipedia.ai
- API Backend: https://intiai.info/api
- Traefik Dashboard: https://traefik.intiai.info

## Related Repositories

- Frontend Source: https://github.com/StevenVincentOne/inti-lightboard-frontend
- Docker Images: https://hub.docker.com/repositories/intellipedia

## Backup Information

Configuration backups are created regularly and stored locally in tar.gz format.

Last updated: 2025-08-06