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
  mysql:
    container_name: presta-mysql
    image: mysql:5.7
    restart: unless-stopped
    environment:
      MYSQL_ROOT_PASSWORD: <a-l0n6-57r0NG-p4ssworD>
      MYSQL_DATABASE: prestashop
    volumes:
      - ./dbdata:/var/lib/mysql
    networks:
      - prestashop_network
  prestashop:
    container_name: prestashop
    image: prestashop/prestashop:latest
    restart: unless-stopped
    depends_on:
      - mysql
    ports:
      - 8080:80
    environment:
      DB_SERVER: presta-mysql
      DB_NAME: prestashop
      DB_USER: root
      DB_PASSWD: <a-l0n6-57r0NG-p4ssworD>
      PS_INSTALL_AUTO: 0
      PS_DOMAIN: <shop.mygreatdomain.org>
    volumes:
      - ./psdata:/var/www/html
    networks:
      - prestashop_network
networks:
    prestashop_network:
```


2. Pull the images `docker compose pull`

3. Start the containers `docker compose up -d && docker compose logs -f`

4. Remove the Install Directory

```sh
docker compose exec -i prestashop rm -rf install
```

5. Change the Back End Folder Name

```sh
docker exec -i mv admin admin_1357
```

- Once changed, you'll get to the back-end by going to your domain / IP and the path 'admin_1357' (or the number you set)
