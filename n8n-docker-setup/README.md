# n8n Docker Setup for Render

This project contains a full Docker setup for deploying n8n on Render with PostgreSQL.

## Services:
- n8n (latest)
- PostgreSQL 15
- Persistent volumes for both services

## Deploy Steps:
1. Upload this repo to GitHub
2. Go to Render → New Web Service
3. Select this repo
4. Choose "Docker" environment
5. Set Start Command:
   docker-compose up
6. Add Environment Variable:
   WEBHOOK_URL = https://your-render-url
7. Deploy 🎉