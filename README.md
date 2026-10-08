# University Project — Kamal Deployment

Fullstack web application deployed on VPS using Kamal.

## Stack

- Python — backend
- JavaScript — frontend
- SQLite — database
- Docker — containerization
- Kamal — deployment tool
- Docker Hub — image registry

## Structure

config/
  deploy.back.yml   # Backend deployment config
  deploy.front.yml  # Frontend deployment config
back/
  dockerfile        # Backend image
front/
  dockerfile        # Frontend image

## Deployment

Both services deployed on a single VPS with:
- Automatic SSL certificates managed by Kamal
- Reverse proxy via Kamal
- Separate Docker networks
- Volume mounts for persistent data
