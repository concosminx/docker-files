# SonarQUBE

- credentials: admin/admin
- create volumes
  
```sh
docker volume create --name sonarqube_data
docker volume create --name sonarqube_extensions
docker volume create --name sonarqube_logs
docker volume create --name sonarqube_temp
```
- run with `embedded` database

```sh
docker run \
    -v sonarqube_data:/opt/sonarqube/data \
    -v sonarqube_extensions:/opt/sonarqube/extensions \
    -v sonarqube_logs:/opt/sonarqube/logs \
    --name="sonarqube" -p 9000:9000 sonarqube:community
```

- run with separate db

```sh
docker run \
    -v sonarqube_data:/opt/sonarqube/data \
    -v sonarqube_extensions:/opt/sonarqube/extensions \
    -v sonarqube_logs:/opt/sonarqube/logs \
    -e SONAR_JDBC_URL="..." \
    -e SONAR_JDBC_USERNAME="..." \
    -e SONAR_JDBC_PASSWORD="..." \
    --name="sonarqube" -p 9000:9000 sonarqube:community
```

or use [docker-compose](docker-compose.yml)
