# Create a docker-compose.yml 

```yaml
services:
  dumbassets:
    container_name: dumbassets
    image: dumbwareio/dumbassets:latest
    restart: unless-stopped
    ports: 
      - ${DUMBASSETS_PORT:-3000}:3000
    volumes:
      - ${DUMBASSETS_DATA_PATH:-./data}:/app/data
    environment:
      NODE_ENV: ${DUMBASSETS_NODE_ENV:-production}
      DEBUG: ${DUMBASSETS_DEBUG:-true}
      SITE_TITLE: ${DUMBASSETS_SITE_TITLE:-DumbAssets}
      BASE_URL: ${DUMBASSETS_BASE_URL:-http://localhost:3000}
      DUMBASSETS_PIN: ${DUMBASSETS_PIN:-1234}
      ALLOWED_ORIGINS: ${DUMBASSETS_ALLOWED_ORIGINS:-*}
      APPRISE_URL: ${DUMBASSETS_APPRISE_URL:-}
      # ...other env vars
```

# Run it
```sh
docker compose up -d
```
