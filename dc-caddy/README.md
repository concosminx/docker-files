# Caddy + Ghost

Caddy is a powerful, enterprise-ready, open source web server with automatic HTTPS written in Go



Official docs: 
- [https://caddyserver.com/docs/install](https://caddyserver.com/docs/install).
- [https://ghost.org/resources/](https://ghost.org/resources/)


## Guide:

```sh
# create the networks
docker network create web
docker network create --internal caddy_internal

#launch the stack 
docker compose up -d
```


