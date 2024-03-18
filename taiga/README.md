# Setup 

### Read the official docs [here](https://community.taiga.io/t/taiga-30min-setup/170)

- Start the application `docker compose -f docker-compose.yml up -d` 
- Create the superuser `docker compose -f docker-compose.yml -f docker-compose-inits.yml run --rm taiga-manage createsuperuser`