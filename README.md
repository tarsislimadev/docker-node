# Docker Node.js

[![github/actions/workflow/status](https://img.shields.io/github/actions/workflow/status/brtmvdl/docker-node/docker-push.yml)](https://img.shields.io/github/actions/workflow/status/brtmvdl/docker-node/docker-push.yml) [![github/license](https://img.shields.io/github/license/brtmvdl/docker-node)](https://img.shields.io/github/license/brtmvdl/docker-node) [![github/stars](https://img.shields.io/github/stars/brtmvdl/docker-node?style=social)](https://img.shields.io/github/stars/brtmvdl/antify?style=social)

Para compilaçao e entrega de projetos escritos em Node.js

Veja mais em [hub.docker.com/r/tmvdl/node](https://hub.docker.com/r/tmvdl/node)

## Como usar

Instalar o [Docker](https://docs.docker.com/engine/install/).

### Em ambiente de desenvolvimento

Criar um arquivo `docker-compose.yaml` na raiz do projeto com a imagem [tmvdl/node](https://hub.docker.com/r/tmvdl/node).

```yaml
version: '3'

services:
  app:
    image: tmvdl/node
    volumes:
      - .:/app
```

Subir o container para a construção do build

```bash
docker-compose up --build
```

### Em ambiente de produção

Executar como container do Docker

```sh
docker run tmvdl/node
```

## License

[MIT](./LICENSE) 
