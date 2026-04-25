# Docker Compose Files

A collection of Docker Compose configurations for various self-hosted applications and services.

---

## Applications

| Folder | App | Description |
|--------|-----|-------------|
| [dc-arr-stack](./dc-arr-stack/) | **Arr Stack** | Media automation suite including Sonarr, Radarr, Prowlarr, and related tools for managing movies, TV shows, and downloads. |
| [dc-authentik](./dc-authentik/) | **Authentik** | Self-hosted open source identity provider (IdP/SSO) with support for OAuth2, SAML, and LDAP. |
| [dc-caddy](./dc-caddy/) | **Caddy** | Powerful, enterprise-ready open source web server with automatic HTTPS, written in Go. Also includes a Ghost blog setup. |
| [dc-cadvisor](./dc-cadvisor/) | **cAdvisor** | Google's Container Advisor – provides resource usage and performance characteristics of running containers. |
| [dc-checkmk](./dc-checkmk/) | **CheckMK** | Comprehensive IT network and systems monitoring platform. |
| [dc-diun](./dc-diun/) | **Diun** | Docker Image Update Notifier – notifies when a Docker image is updated on a registry. |
| [dc-docuseal](./dc-docuseal/) | **DocuSeal** | Open source document signing platform for creating, filling, and signing PDF documents. |
| [dc-draw-io](./dc-draw-io/) | **draw.io** | Self-hosted diagramming and flowchart tool (diagrams.net). |
| [dc-dumb-assets](./dc-dumb-assets/) | **Dumb Assets** | Simple self-hosted static asset server. |
| [dc-duplicati](./dc-duplicati/) | **Duplicati** | Free backup software for storing encrypted backups online. |
| [dc-easy-appointments](./dc-easy-appointments/) | **Easy Appointments** | Open source appointment scheduling web application. |
| [dc-elk](./dc-elk/) | **ELK Stack** | Elasticsearch, Logstash, and Kibana in a single-node setup for log aggregation, analysis, and visualization. |
| [dc-firefox](./dc-firefox/) | **Firefox** | Containerized Firefox browser, useful for remote access or isolated browsing environments. |
| [dc-ghost](./dc-ghost/) | **Ghost** | Modern open source publishing platform and CMS for blogs and newsletters. |
| [dc-gitea](./dc-gitea/) | **Gitea** | Lightweight self-hosted Git service similar to GitHub/GitLab. |
| [dc-glowroot](./dc-glowroot/) | **Glowroot** | Open source Java APM (Application Performance Monitor) with embedded and central collector modes. |
| [dc-gotenberg](./dc-gotenberg/) | **Gotenberg** | Docker-powered stateless API for converting HTML, Markdown, and Office documents to PDF. |
| [dc-gotify](./dc-gotify/) | **Gotify** | Simple self-hosted server for sending and receiving push notifications and messages. |
| [dc-groovy](./dc-groovy/) | **Groovy** | Docker-based Groovy scripting environment for running Groovy scripts or an interactive shell. |
| [dc-guacamole](./dc-guacamole/) | **Apache Guacamole** | Clientless remote desktop gateway supporting VNC, RDP, and SSH via a web browser. |
| [dc-haproxy](./dc-haproxy/) | **HAProxy** | Reliable, high-performance TCP/HTTP load balancer and proxy server. |
| [dc-heimdall](./dc-heimdall/) | **Heimdall** | Application dashboard and launcher for self-hosted services. |
| [dc-homeassistant](./dc-homeassistant/) | **Home Assistant** | Open source home automation platform for controlling smart home devices. |
| [dc-homepage](./dc-homepage/) | **Homepage** | Modern, highly customizable, fully static application dashboard for self-hosted services. |
| [dc-jenkins](./dc-jenkins/) | **Jenkins** | Leading open source automation server for continuous integration and continuous delivery (CI/CD). |
| [dc-kafka](./dc-kafka/) | **Apache Kafka** | Distributed event streaming platform. Includes both simple and clustered setups. |
| [dc-kavita](./dc-kavita/) | **Kavita** | Fast, feature-rich self-hosted digital library for manga, comics, and books. |
| [dc-keycloak](./dc-keycloak/) | **Keycloak** | Open source Identity and Access Management (IAM) solution with SSO, OAuth2, and SAML support. |
| [dc-mealie](./dc-mealie/) | **Mealie** | Self-hosted recipe manager and meal planner with a REST API. |
| [dc-minio](./dc-minio/) | **MinIO** | High-performance, S3-compatible self-hosted object storage service. |
| [dc-mongo](./dc-mongo/) | **MongoDB** | Self-hosted NoSQL document database setup. |
| [dc-moodle](./dc-moodle/) | **Moodle** | Popular open source Learning Management System (LMS). |
| [dc-musicbrainz](./dc-musicbrainz/) | **MusicBrainz** | Self-hosted instance of the open music encyclopedia and metadata database. |
| [dc-navidrome](./dc-navidrome/) | **Navidrome** | Modern self-hosted music server and streamer compatible with Subsonic/Airsonic clients. |
| [dc-netdata](./dc-netdata/) | **Netdata** | Real-time performance monitoring for systems, containers, and applications. |
| [dc-nexterm](./dc-nexterm/) | **NexTerm** | Modern self-hosted terminal/SSH manager accessible via web browser. |
| [dc-nginx](./dc-nginx/) | **Nginx** | High-performance web server and reverse proxy. Includes simple setup and Node.js+Redis example. |
| [dc-nginx-proxy-manager](./dc-nginx-proxy-manager/) | **Nginx Proxy Manager** | Easy-to-use GUI for managing Nginx reverse proxy hosts with Let's Encrypt SSL. |
| [dc-nodejs-mongodb](./dc-nodejs-mongodb/) | **Node.js + MongoDB** | Sample Node.js web application backed by MongoDB, with Mongo Express UI. |
| [dc-odoo](./dc-odoo/) | **Odoo** | Open source ERP and CRM platform covering business needs like accounting, sales, and inventory. |
| [dc-ollama](./dc-ollama/) | **Ollama** | Run large language models (LLMs) locally in a Docker container. |
| [dc-oracle-monitoring](./dc-oracle-monitoring/) | **Oracle Monitoring** | Monitoring setup for Oracle databases. |
| [dc-oracle-versions](./dc-oracle-versions/) | **Oracle Versions** | Docker examples for running various Oracle Database (XE) versions. |
| [dc-paperless](./dc-paperless/) | **Paperless-ngx** | Document management system that transforms physical documents into a searchable online archive. |
| [dc-passbolt](./dc-passbolt/) | **Passbolt** | Open source password manager designed for teams with sharing and collaboration features. |
| [dc-pgwatch2](./dc-pgwatch2/) | **pgwatch2** | PostgreSQL metrics monitoring tool with a built-in dashboard. |
| [dc-planka](./dc-planka/) | **Planka** | Open source, self-hosted Kanban board for project management (Trello alternative). |
| [dc-portainer](./dc-portainer/) | **Portainer** | Lightweight management UI for Docker environments – manage containers, images, networks, and volumes. |
| [dc-postgresql](./dc-postgresql/) | **PostgreSQL** | Open source relational database. Includes simple, pgAdmin, and high-availability replication setups. |
| [dc-prestashop](./dc-prestashop/) | **PrestaShop** | Open source e-commerce platform for creating online stores. |
| [dc-privatebin](./dc-privatebin/) | **PrivateBin** | Self-hosted, minimalist, open source pastebin where the server has zero knowledge of pasted data. |
| [dc-quant-ux](./dc-quant-ux/) | **Quant-UX** | Open source UX/UI prototyping and user research tool. |
| [dc-rclone](./dc-rclone/) | **rClone** | Command-line program for managing and syncing files across cloud storage providers. |
| [dc-redmine](./dc-redmine/) | **Redmine** | Flexible open source project management web application with issue tracking. |
| [dc-restic](./dc-restic/) | **Restic** | Fast, secure, efficient backup program for Docker volumes and data. |
| [dc-rocket-chat](./dc-rocket-chat/) | **Rocket.Chat** | Open source team collaboration and messaging platform (Slack alternative). |
| [dc-smtp4dev](./dc-smtp4dev/) | **smtp4dev** | Fake SMTP server for development – captures outgoing emails without actually sending them. |
| [dc-sonar-qube](./dc-sonar-qube/) | **SonarQube** | Continuous code quality and security inspection platform. |
| [dc-spring-postgresql](./dc-spring-postgresql/) | **Spring + PostgreSQL** | Sample Java Spring Framework application connected to a PostgreSQL database. |
| [dc-stirling-pdf](./dc-stirling-pdf/) | **Stirling PDF** | Self-hosted web application for performing various PDF operations (merge, split, convert, etc.). |
| [dc-swag](./dc-swag/) | **SWAG** | Secure Web Application Gateway – Nginx + Let's Encrypt + Fail2Ban in a single container. |
| [dc-taiga](./dc-taiga/) | **Taiga** | Open source agile project management platform with Scrum and Kanban support. |
| [dc-tomcat](./dc-tomcat/) | **Tomcat** | Apache Tomcat servlet container example with a custom Dockerfile and Compose setup. |
| [dc-traefik](./dc-traefik/) | **Traefik** | Modern cloud-native reverse proxy and load balancer with automatic service discovery. |
| [dc-uptime-kuma](./dc-uptime-kuma/) | **Uptime Kuma** | Self-hosted monitoring tool for tracking uptime of websites and services. |
| [dc-varnish](./dc-varnish/) | **Varnish** | High-performance HTTP accelerator and caching reverse proxy. |
| [dc-vault](./dc-vault/) | **HashiCorp Vault** | Tool for securely storing and managing secrets, tokens, passwords, and certificates. |
| [dc-vaultwarden](./dc-vaultwarden/) | **Vaultwarden** | Lightweight, self-hosted Bitwarden-compatible password manager server. |
| [dc-wekan](./dc-wekan/) | **Wekan** | Open source, self-hosted Kanban board (Trello alternative). |
| [dc-wordpress](./dc-wordpress/) | **WordPress** | Popular open source CMS for building websites and blogs. |
| [dc-write-freely](./dc-write-freely/) | **WriteFreely** | Minimalist, privacy-focused self-hosted blogging and writing platform. |
| [dc-xwiki](./dc-xwiki/) | **XWiki** | Open source enterprise wiki platform with a rich extension ecosystem. |
| [dc-zabbix](./dc-zabbix/) | **Zabbix** | Enterprise-class open source distributed monitoring solution for networks, servers, and applications. |
| [dc-zitadel](./dc-zitadel/) | **Zitadel** | Open source identity infrastructure platform providing authentication, authorization, and user management. |

---

> Each subfolder contains a `docker-compose.yml` and optionally a `README.md` with setup instructions specific to that application.
