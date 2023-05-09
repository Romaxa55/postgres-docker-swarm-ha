# Highly Available PostgreSQL Cluster in Docker Swarm

This repository provides a highly available PostgreSQL cluster setup using Docker Swarm, Patroni, and PgBouncer. Patroni is used to manage the PostgreSQL instances, while PgBouncer provides connection pooling to optimize resource usage.

## Requirements

- Docker Engine 18.06.0+ (with Swarm mode enabled)
- Docker Compose 1.24.0+

## Deployment

1. Clone this repository:

```bash
git clone https://github.com/Romaxa55/postgres-docker-swarm-ha.git
```

2. Update the `docker-compose.yml` file with the appropriate environment variables, such as PostgreSQL credentials and etcd cluster configuration.

3. Create the Docker Swarm overlay networks:

```bash
docker network create --driver=overlay --attachable etcd-network
docker network create --driver=overlay --attachable postgres-network
```


4. Deploy the PostgreSQL cluster using Docker Stack:

```bash
docker stack deploy -c docker-compose.yml postgres-ha
```


## Components

- PostgreSQL: The primary and replica instances are managed by Patroni.
- Patroni: Handles automatic failover, configuration management, and dynamic cluster membership for PostgreSQL instances.
- PgBouncer: Provides connection pooling to optimize resource usage when connecting to the PostgreSQL cluster.
- etcd: A distributed key-value store used by Patroni for maintaining the state of the PostgreSQL cluster.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
