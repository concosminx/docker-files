Digital library - [docs](https://www.kavitareader.com/)

Use with `docker run` or `docker compose`

```sh
docker run --name kavita -p 5000:5000 \
-v /your/manga/directory:/manga \
-v /your/storage/directory/kavita:/kavita/config \
--restart unless-stopped \
-e TZ=Your/Timezone \
-d jvmilazz0/kavita:latest
```