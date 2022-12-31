# Docker Node.js

To compile Node.js projects

See more [github.com/tmvdl/docker-node](https://github.com/tmvdl/docker-node)

## How to

Install [Docker](https://docs.docker.com/engine/install/).

### At Docker Compose

Create a file `docker-compose.yaml` with [tmvdl/node](https://hub.docker.com/r/tmvdl/node).

```yaml
# docker-compose.yaml
version: '3'

services:
  app:
    image: tmvdl/node
    volumes:
      - .:/app
```

Up the project

```bash
docker-compose up
```

### At Docker environemt

Run using Docker

```sh
docker run tmvdl/node
```

## License

[MIT](https://github.com/tmvdl/docker-node/blob/main/LICENSE)
