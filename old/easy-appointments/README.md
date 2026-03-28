### Install docker, setup a server with a non-root, sudo user

```sh
add user <username>
usermod -aG sudo <username>
curl https://get.docker.com | sh
sudo usermod -aG docker <username>
```

### Setup prestashop 

1. Create a docker-compose.yaml

```yaml
---
services:
  easyapointments:
    image: alextselegidis/easyappointments
    environment:
      - BASE_URL=http://localhost
      - DEBUG_MODE=TRUE
      - DB_HOST=mysql
      - DB_NAME=easyappointments
      - DB_USERNAME=easyappt
      - DB_PASSWORD=<longstR0n6Pa5sw0rdTh4at1sUn1qu3>
    ports:
      - '80:80'  # you can change the left side port if needed.
    # extra_hosts: 
      # - "<your.freeipa.server>:<your-server-local-ip"
  mysql:
    image: mysql
    volumes:
      - ./data/mysql:/var/lib/mysql
    environment:
      - MYSQL_USER=easyappt
      - MYSQL_PASSWORD=<longstR0n6Pa5sw0rdTh4at1sUn1qu3>
      - MYSQL_ROOT_PASSWORD=<it-must-be-some-other-diffErent-paSsword>
      - MYSQL_DATABASE=easyappointments
```


2. Pull the images `docker compose pull`

3. Start the containers `docker compose up -d && docker compose logs -f`
