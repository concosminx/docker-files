# Some resources on how to start with PostgreSQL HA

### Manual failover with [pg_ctl](https://vuyisile.com/high-availability-in-postgresql-replication-with-docker/)

### Automate failover with _Patroni_ resources:
- Patroni [docs](https://patroni.readthedocs.io/en/latest/)
- Patroni [github repo](https://github.com/zalando/patroni/tree/master)
- AWS setup article with [spilo](https://proventa.de/en/setting-up-postgresql-cluster-with-patroni-using-spilo-image/)
- PostgreSQL HA architecture [article 1](https://medium.com/@c.ucanefe/patroni-ha-proxy-feed1292d23f)
- PostgreSQL HA architecture [article 2](https://docs.microfocus.com/doc/AMX/2023.05/HASQLPatroni)
- How to run an `etcd` [cluster](https://etcd.io/docs/v3.5/op-guide/container/)


### Or use attached example with docker compose
- `docker-compose up -d postgres_primary postgres_replica`

Inspired by the article: [How to Setup Single-Primary PostgreSQL Replication with Docker-compose](https://medium.com/@eremeykin/how-to-setup-single-primary-postgresql-replication-with-docker-compose-98c48f233bbf) by Peter Eremeykin.
