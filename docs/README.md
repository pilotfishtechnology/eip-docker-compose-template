# Start

```bash
docker-compose up -d
```

# Stop

```bash
docker-compose down
```

# View Logs

```bash
docker-compose logs -f
```

# Upgrade

```bash
docker-compose down
docker pull pilotfishtechnology/eiplatform
docker-compose up -d
```