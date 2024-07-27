# NodeJS + MongoDB

### Docker

1. create docker network `docker network create mongo-network `
2. start mongodb `docker run -d -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=admin -e MONGO_INITDB_ROOT_PASSWORD=password --name mongodb --net mongo-network mongo`
3. start mongo-express `docker run -d -p 8081:8081 -e ME_CONFIG_MONGODB_ADMINUSERNAME=admin -e ME_CONFIG_MONGODB_ADMINPASSWORD=password --net mongo-network --name mongo-express -e ME_CONFIG_MONGODB_SERVER=mongodb mongo-express`

### Docker Compose

1. start mongodb and mongo-express `docker compose -f docker-compose.yaml up`
2. open mongo-express from browser `http://localhost:8081`
3. create `my-db` _db_ and `my-collection` _collection_ and _document_ with `{myid: 1, data: "some dynamic data loaded from db"}` in mongo-express
4. access you nodejs application UI from browser `http://localhost:3000`   
