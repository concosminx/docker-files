# Authentik

A self-hosted, open source identity provider means prioritizing security and taking control of your most sensitive data.

Official docs: [https://docs.goauthentik.io/](https://docs.goauthentik.io/).

## Generate PostgreSQL password adn secret key

```sh
echo "PG_PASS=$(openssl rand -base64 36 | tr -d '\n')" >> .env
echo "AUTHENTIK_SECRET_KEY=$(openssl rand -base64 60 | tr -d '\n')" >> .env
```

Default user: `akadmin`