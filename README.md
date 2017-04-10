# dockerize-truffle
## Requirements

- docker
- docker-compose

## Quickstart

Build images (only needed on first run)

```bash
❯ docker-compose build
```

Run it

```bash
❯ docker-compose up
```

After is up run migrations
```bash
❯ docker-compose exec truffle truffle migrate --reset
```

Happy hacking! :heart:
