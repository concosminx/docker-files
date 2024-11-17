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
| [apche-guacamole](apache%guacamole/README.md)  | [source](https://wiki.opensourceisawesome.com/books/guacamole-rdp/page/setup-oidc-for-guacamole)  | Remote Desktop Gateway |
| [authentik](authentik/docker-compose.yml)  | [source](https://wiki.opensourceisawesome.com/books/authentik/page/install-and-setup-authentik)  | IdP (Identity Provider) and SSO (single sign on) |
| [bind9](bind9/docker-compose.yml)  | [source](https://www.isc.org/bind/)  | DNS system |
| [caddy](caddy/README.md)  | [source](https://caddyserver.com/docs/quick-starts/reverse-proxy)  |  Web server with automatic HTTPS |
| [cadvisor](cadvisor/docker-compose.yaml)  | [source](https://github.com/google/cadvisor)  | Resource usage and performance characteristics of running containers |
| [checkmk](checkmk/README.md)  | [source](https://checkmk.com/) | IT monitoring platform |
| [ctop](ctop/README.md)  | [source](https://github.com/bcicen/ctop)  | Top-like interface for container metrics |
| [DocuSeal](docuseal/)  | [source](https://www.docuseal.com/on-premises)  | Document Signing |
| [draw.io](draw-io/README.md)  | [source](https://hub.docker.com/r/jgraph/drawio)  | Flowchart Maker and Online Diagram Software |
| [duplicati](duplicati/docker-compose.yml)  | [source](https://shownotes.opensourceisawesome.com/duplicati/)  | Backup Manager |
| [elk](elk/README.md)  | [source](https://www.elastic.co/elastic-stack)  | ELK Stack - Elasticsearch, Kibana, Beats, and Logstash |
| [firefox](firefox/README.md)  | [source](https://hub.docker.com/r/linuxserver/firefox)  | Run Firefox in Docker |
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
| [jellyfin](jellyfin/README.md)  | [source](https://jellyfin.org/) | Software Media System |
| [jenkins](jenkins/README.md)  | [source](https://www.jenkins.io/) | Automation Server / CI / CD|
| [kafka](kafka/docker-compose-simple.yml)  | [source](https://kafka.apache.org/)  | Distributed Event Streaming Platform |
| [keycloak](keycloak/README.md)  | [source](https://www.keycloak.org/)  | Identity and Access Management |
| [mealie](mealie/docker-compose.yml)  | [source](https://nightly.mealie.io/)  | Recipe Management |
| [minio](minio/docker-compose.yml)  | [source](https://min.io/)  | Object Storage |
| [mongo-db](mongo/README.md)  | [source](https://www.mongodb.com/)  | Document Oriented Database |
| [mongo-db-cluster](mongo-cluster/docker-compose.yml)  | [source](https://www.mongodb.com/)  | Document Oriented Database Cluster |
| [musicbrainz](musicbrainz/docker-compose.yml)  | [source](https://musicbrainz.org/)  | Music Metadata |
| [navidrome](navidrome/docker-compose.yml)  | [source](https://shownotes.opensourceisawesome.com/navidrome-music-streaming/)  | Music Streaming |
| [netdata](netdata/README.md)  | [source](https://www.netdata.cloud/)  | Monitoring Platform |
| [nginx-docs](nginx/README.md)  | [source](https://www.nginx.com/)  | Web Server |
| [nginx-nodejs-redis](nginx-nodejs-redis/compose.yaml)  | [source](https://www.nginx.com/)  | Web Server - Redis Example |
| [nginx-proxy-manager](nginx-proxy-manager/README.md)  | [source](https://www.nginx.com/)  | Nginx used as a proxy |
| [oauth2-proxy](oauth2-proxy/docker-compose.yml)  | [source](https://github.com/oauth2-proxy/oauth2-proxy)  | Reverse proxy |
| [odoo](odoo/README.md)  | [source](https://hub.docker.com/_/odoo)  | Open Source ERP and CRM | 
| [Oracle](oracle-versions/README.md)  | [source](https://github.com/diemobiliar/minimized-oraclexe-image)  | Oracle XE | 
| [paperless](paperless/docker-compose.yml)  | [source](https://docs.paperless-ngx.com/)  | Document Management System |
| [passbolt](passbolt/README.md)  | [source](https://www.passbolt.com/) | Open Source Password Manager |
| [planka](planka/README.md)  | [source](https://docs.planka.cloud/docs/installation/docker/production_version) | Open Source Project Tracking |
| [Portainer](portainer/README.md)  | [source](https://docs.portainer.io/start/install/server/docker/linux)  | Container Management |
| [PostgreSQL](postgresql/README.md)  | [source](https://hub.docker.com/_/postgres)  | Database |
| [PostgreSQL with pgadmin](postgresql-pgadmin/README.md)  | [source](https://www.pgadmin.org/docs/pgadmin4/latest/container_deployment.html)  | Database & Tools |
| [Quant-UX](quant-ux/README.md)  | [source](https://github.com/bmcgonag/quant-ux-docker/)  | Prototyping |
| [Redmine](redmine/README.md)  | [source](https://hub.docker.com/_/redmine)  | Project Management | 
| [rocket-chat](rocket-chat/README.md)  | [source](https://docs.rocket.chat/quick-start/deploying-rocket.chat/rapid-deployment-methods/docker-and-docker-compose)  | Chat System |
| [smtp4dev](smtp4dev/README.md)  | [source](https://github.com/rnwood/smtp4dev/blob/master/docker-compose.yml)  | Fake SMTP Email Server |
| [SonarQUBE](sonar-qube/README.md)  | [source](https://www.sonarsource.com/products/sonarqube/)  | Static Code Analysis |
| [spring-and-postgresql](spring-postgresql/README.md)  | ~~[source](#)~~  | SpringBoot and PostgreSQL Example |
| [swag](swag/docker-compose.yaml)  | [source](https://docs.linuxserver.io/general/swag#swag)  | Web Server |
| [taiga](taiga/README.md)  | [source](https://github.com/docker-taiga/taiga) | Project Management |
| [Tomcat](tomcat/README.md)  | [source](https://hub.docker.com/_/tomcat)  | Web Server and Servlet Container |
| [Traefik](traefik/README.md)  | [source](https://traefik.io/traefik/)  | Proxy |
| [uptime-kuma](uptime-kuma/README.md)  | [source](https://github.com/louislam/uptime-kuma)  | Monitoring Tool |
| [varnish](varnish/docker-compose.yml)  | [source](https://hub.docker.com/_/varnish)  | Cache |
| [vault](vault/README.md)  | [source](https://ambar-thecloudgarage.medium.com/hashicorp-vault-with-docker-compose-0ea2ce1ca5ab) | Secure Storage |
| [wekan](wekan/README.md)  | [source](https://github.com/wekan/wekan/wiki/Docker)  | Project Management |
| [Wordpress](wordpress/README.md)  | [source](https://www.digitalocean.com/community/tutorials/how-to-install-wordpress-with-docker-compose)  | CMS |
| [WriteFreely](write-freely/README.md) | [source](https://writefreely.org/)  | Minimalist Blog |
| [xwiki](xwiki/README.md) | [source](https://hub.docker.com/_/xwiki)  | WIKI |
| [zabbix](zabbix/README.md) | [source](https://github.com/zabbix/zabbix-docker)  | Monitoring Platform |
| [zitadel](zitadel/README.md) | [source](https://zitadel.com/docs/self-hosting/deploy/compose)  | Identity Management |


 
