# Docker containers

### Setup Docker on Ubuntu
- [read official docs](https://docs.docker.com/engine/install/ubuntu/) 

### Cleanup Docker
- containers `docker rm -f $(docker ps -q)`
- images `docker rmi $(docker images -q)`

# Container list

| Name  | Webpage | Description | 
| ------------- | ------------- | ------------- |
| [ansible-semaphore](ansiblesemaphore/docker-compose.yml)  | [source](https://www.ansible-semaphore.com/)  | Modern UI for Ansible |
| [authentik](authentik/docker-compose.yml)  | [source](https://wiki.opensourceisawesome.com/books/authentik/page/install-and-setup-authentik)  | IdP (Identity Provider) and SSO (single sign on) |
| [bind9](bind9/docker-compose.yml)  | [source](https://www.isc.org/bind/)  | DNS system |
| [caddy](caddy/README.md)  | [source](https://caddyserver.com/docs/quick-starts/reverse-proxy)  |  Web server with automatic HTTPS |
| [cadvisor](cadvisor/docker-compose.yaml)  | [source](https://github.com/google/cadvisor)  | Resource usage and performance characteristics of running containers |
| [checkmk](checkmk/README.md)  | [source](https://checkmk.com/) | IT monitoring platform |
| [ctop](ctop/README.md)  | [source](https://github.com/bcicen/ctop)  | Top-like interface for container metrics |
| [draw.io](draw-io/README.md)  | [source](https://hub.docker.com/r/jgraph/drawio)  | Flowchart Maker and Online Diagram Software |
| [duplicati](duplicati/docker-compose.yml)  | [source](https://shownotes.opensourceisawesome.com/duplicati/)  | Backup Manager |
| [elk](elk/README.md)  | [source](https://www.elastic.co/elastic-stack)  | ELK Stack - Elasticsearch, Kibana, Beats, and Logstash |
| [gitea](gitea/README.md)  | [source](https://docs.gitea.io/en-us/install-with-docker/)  | Git Repository manager |
| [glowroot](glowroot/README.md)  | [source](https://github.com/glowroot/glowroot/wiki)  | Open source Java APM |
| [gotenberg](gotenberg/README.md)  | [source](https://gotenberg.dev/docs/configuration)  | Stateless API for PDF files |
| [groovy](groovy/README.md)  | [source](https://hub.docker.com/_/groovy/)  | Apache Groovy |
| [haproxy-3-services](haproxy/3-services/docker-compose.yml)  | [source](https://www.haproxy.org/)  | HAProxy example with LB and 3 services (Echo Server) |
| [haproxy-python-services](haproxy/python-services/docker-compose.yml)  | [source](https://www.haproxy.org/)  | HAProxy example with LB and 3 services (Python) |
| [heimdall](heimdall/docker-compose.yaml)  | [source](https://github.com/linuxserver/Heimdall)  | Application Dashboard |
| [homeassistant](homeassistant/docker-compose.yaml)  | [source](https://www.home-assistant.io/)  | Home automation |
| [homepage](homepage/docker-compose.yml)  | [source](https://github.com/gethomepage/homepage)  | Application Dashboard |
| [homer](homer/docker-compose.yaml)  | [source](https://hub.docker.com/r/b4bz/homer)  | Application Dashboard |
| [invoiceninja](invoiceninja/README.md)  | [source](https://invoiceninja.com/)  | Invoicing Software |


# Container list (old)

| Name  | Webpage |
| ------------- | ------------- |
| ~~[Jasper Server](jasper-server/README.md)~~  | ~~[source](https://hub.docker.com/r/bitnami/jasperreports/)~~  |
| [jellyfin](jellyfin/README.md)  | [source](https://jellyfin.org/)  |
| [jenkins](jenkins/README.md)  | [source](https://www.jenkins.io/)  |
| [kafka](kafka/docker-compose-simple.yml)  | [source](https://kafka.apache.org/)  |
| [keycloak](keycloak/README.md)  | [source](https://www.keycloak.org/)  |
| [mealie](mealie/docker-compose.yml)  | [source](https://nightly.mealie.io/)  |
| [minio](minio/docker-compose.yml)  | [source](https://min.io/)  |
| [mongo-db](mongo/README.md)  | [source](https://www.mongodb.com/)  |
| [mongo-db-cluster](mongo-cluster/docker-compose.yml)  | [source](https://www.mongodb.com/)  |
| [musicbrainz](musicbrainz/docker-compose.yml)  | [source](https://musicbrainz.org/)  |
| [navidrome](navidrome/docker-compose.yml)  | [source](https://shownotes.opensourceisawesome.com/navidrome-music-streaming/)  |
| [netdata](netdata/README.md)  | [source](https://www.netdata.cloud/)  |
| [nginx-docs](nginx/README.md)  | [source](https://www.nginx.com/)  |
| [nginx-nodejs-redis](nginx-nodejs-redis/compose.yaml)  | [source](https://www.nginx.com/)  |
| [nginx-proxy-manager](nginx-proxy-manager/README.md)  | [source](https://www.nginx.com/)  |
| [oauth2-proxy](oauth2-proxy/docker-compose.yml)  | [source](https://github.com/oauth2-proxy/oauth2-proxy)  |
| [odoo](odoo/README.md)  | [source](https://hub.docker.com/_/odoo)  |
| [Oracle](oracle-versions/README.md)  | [source](https://github.com/diemobiliar/minimized-oraclexe-image)  |
| [paperless](paperless/docker-compose.yml)  | [source](https://docs.paperless-ngx.com/)  |
| [passbolt](passbolt/README.md)  | [source](https://www.passbolt.com/)  |
| [planka](planka/README.md)  | ~~[source](#)~~  |
| [Portainer](portainer/README.md)  | [source](https://docs.portainer.io/start/install/server/docker/linux)  |
| [PostgreSQL](postgresql/README.md)  | [source](https://hub.docker.com/_/postgres)  |
| [PostgreSQL with pgadmin](postgresql-pgadmin/README.md)  | [source](https://www.pgadmin.org/docs/pgadmin4/latest/container_deployment.html)  |
| [Quant-UX](quant-ux/README.md)  | [source](https://github.com/bmcgonag/quant-ux-docker/)  |
| [Redmine](redmine/README.md)  | [source](https://hub.docker.com/_/redmine)  |
| [rocket-chat](rocket-chat/README.md)  | [source](https://docs.rocket.chat/quick-start/deploying-rocket.chat/rapid-deployment-methods/docker-and-docker-compose)  |
| [smtp4dev](smtp4dev/README.md)  | [source](https://github.com/rnwood/smtp4dev/blob/master/docker-compose.yml)  |
| [SonarQUBE](sonar-qube/README.md)  | [source](https://www.sonarsource.com/products/sonarqube/)  |
| [spring-and-postgresql](spring-postgresql/README.md)  | ~~[source](#)~~  |
| [swag](swag/docker-compose.yaml)  | [source](https://docs.linuxserver.io/general/swag#swag)  |
| [taiga](taiga/README.md)  | ~~[source](#)~~  |
| [Tomcat](tomcat/README.md)  | ~~[source](#)~~  |
| [Traefik](traefik/README.md)  | [source](https://traefik.io/traefik/)  |
| [uptime-kuma](uptime-kuma/README.md)  | [source](https://github.com/louislam/uptime-kuma)  |
| [varnish](varnish/docker-compose.yml)  | ~~[source](#)~~  |
| [vault](vault/README.md)  | ~~[source](#)~~  |
| [wekan](wekan/README.md)  | ~~[source](#)~~  |
| [Wordpress](wordpress/README.md)  | ~~[source](#)~~  |
| [WriteFreely](write-freely/README.md) | ~~[source](#)~~  |
| [xwiki](xwiki/README.md) | ~~[source](#)~~  |
| [zabbix](zabbix/README.md) | ~~[source](#)~~  |
| [zitadel](zitadel/README.md) | ~~[source](#)~~  |
