## pgwatch2 

[see docs](https://pgwatch2.readthedocs.io/en/latest/)

```sh
docker run -d --restart=unless-stopped --name pw2 ^
  -p 3000:3000 -p 8080:8080 -p 127.0.0.1:5432:5432 ^
  -e PW2_ADHOC_CONN_STR=postgres://postgres:emsys@some-ip:5432/sample ^
  -e PW2_ADHOC_CONFIG='rds' ^
  cybertec/pgwatch2-postgres:latest
```
