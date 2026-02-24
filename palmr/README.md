# Palmr

1. Generate an encryption key (example):
   - `openssl rand -base64 32`
2. Update `ENCRYPTION_KEY` in `docker-compose.yml`.
3. Start the service: `docker compose up -d`

Web UI: `http://localhost:5487`
