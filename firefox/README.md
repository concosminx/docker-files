# Run Firefox in a Docker container

- linux
```sh
docker run -d \
  --name=firefox \
  --security-opt seccomp=unconfined \
  -e PUID=1000 \
  -e PGID=1000 \
  -e TZ=Etc/UTC \
  -e FIREFOX_CLI=https://www.linuxserver.io/ \
  -p 3000:3000 \
  -p 3001:3001 \
  -v /path/to/config:/config \
  --shm-size="1gb" \
  --restart unless-stopped \
  lscr.io/linuxserver/firefox:latest
```

- windows
```batch
docker run -d ^
  --name=firefox ^
  --security-opt seccomp=unconfined ^
  -e PUID=1000 ^
  -e PGID=1000 ^
  -e TZ=Etc/UTC ^
  -e FIREFOX_CLI=https://www.linuxserver.io/ ^
  -p 3000:3000 ^
  -p 3001:3001 ^
  -v /path/to/config:/config ^
  --shm-size="1gb" ^
  --restart unless-stopped ^
  lscr.io/linuxserver/firefox:latest
```
