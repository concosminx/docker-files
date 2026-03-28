Run with docker 

```bash
docker run \
  -p 8080:8080 \
  -v </path/to/config>:/config \
  jwetzell/guacamole:1.5.5
```

or with docker compose: 

```yaml
version: "3"
services:
  guacamole:
    image: jwetzell/guacamole
    container_name: guacamole
    volumes:
      - ./postgres:/config
    ports:
      - 8080:8080
    environment:
      - EXTENSIONS=auth-sso-openid
    restart: unless-stopped
volumes:
  postgres:
    driver: local
```
