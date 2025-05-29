### Install docker, setup a server with a non-root, sudo user

```sh
add user <username>
usermod -aG sudo <username>
curl https://get.docker.com | sh
sudo usermod -aG docker <username>
```

### Setup moodle 

1. Create a docker-compose.yaml

```yaml
---
services:
  mariadb:
    image: docker.io/bitnami/mariadb:latest
    container_name: moodle_mysql
    environment:
      - MARIADB_ROOT_PASSWORD=<a-long-strong-password>
      - MARIADB_PASSWORD=<a-different-long-strong-password>
      - MARIADB_USER=moodle
      - MARIADB_DATABASE=moodle
      - MARIADB_CHARACTER_SET=utf8mb4
      - MARIADB_COLLATE=utf8mb4_unicode_ci
    volumes:
      - ./mariadb_data:/bitnami/mariadb
  moodle:
    image: docker.io/bitnami/moodle:4.5
    container_name: moodle
    ports:
      - 80:8080
      - 443:8443
    environment:
      - MOODLE_DATABASE_HOST=mariadb
      - MOODLE_DATABASE_PORT_NUMBER=3306
      - MOODLE_DATABASE_USER=moodle
      - MOODLE_DATABASE_NAME=moodle
      - ALLOW_EMPTY_PASSWORD=no
      - MOODLE_DATABASE_PASSWORD=<a-different-long-strong-password> # <-- same as the MARIADB_PASSWORD from the first section.
      - MOODLE_HOST=<name.mygreatdomain.org>
      - MOODLE_REVERSEPROxY=true # <-- if you're using a reverse proxy make it true, otherwise false
      - MOODLE_SSLPROXY=true # <-- if you are using LetsEncrypt through your proxy, again make it true, otherwise false
      - MOODLE_SMTP_HOST=<smtp.somemailprovider.com>
      - MOODLE_SMTP_PORT=587
      - MOODLE_SMTP_USER=<leanring@somemailprovider.com>
      - MOODLE_SMTP_PASSWORD=<some-email-password-for-the-user-above>
      - MOODLE_SMTP_PROTOCOL=tls
      - MOODLE_LANG=en
      - MOODLE_USERNAME=<admin_username>
      - MOODLE_PASSWORD=<admin_password>
    volumes:
      - ./moodle_data:/bitnami/moodle
      - ./moodledata_data:/bitnami/moodledata
    depends_on:
      - mariadb
```


2. Pull the images `docker compose pull`

3. Start the containers `docker compose up -d && docker compose logs -f`
