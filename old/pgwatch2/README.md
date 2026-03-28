## pgwatch2 

[see docs](https://pgwatch2.readthedocs.io/en/latest/)

```sh
docker run -d --restart=unless-stopped --name pw2 ^
  -p 3000:3000 -p 8080:8080 -p 127.0.0.1:5432:5432 ^
  -e PW2_ADHOC_CONN_STR=postgres://postgres:emsys@db-pg-umfcd.qa.local:5432/sd2024 ^
  -e PW2_ADHOC_CONFIG='rds' ^
  cybertec/pgwatch2-postgres:latest
```
