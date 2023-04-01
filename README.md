# Docker Node.js

[![github/actions/workflow/status](https://img.shields.io/github/actions/workflow/status/brtmvdl/docker-node/docker-push.yml)](https://img.shields.io/github/actions/workflow/status/brtmvdl/docker-node/docker-push.yml) [![github/license](https://img.shields.io/github/license/brtmvdl/docker-node)](https://img.shields.io/github/license/brtmvdl/docker-node) [![github/stars](https://img.shields.io/github/stars/brtmvdl/docker-node?style=social)](https://img.shields.io/github/stars/brtmvdl/antify?style=social)

To compile and deploy [Node.js]() projects.

See more in [hub.docker.com/r/tmvdl/node](https://hub.docker.com/r/tmvdl/node)

## How to

Install [Docker](https://docs.docker.com/engine/install/).

### Development

```yaml
version: '3'

services:
  app:
    image: tmvdl/node
    volumes:
      - .:/app
```

```bash
docker-compose up --build
```

### Production

```sh
docker run tmvdl/node
```

## License

[MIT](./LICENSE) 
