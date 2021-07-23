# Docker Node.js + Git

Imagem Docker para compilaçao de projetos Node.js com Git

## Como usar

1. Instalar o [Docker](https://docs.docker.com/engine/install/).

2. Criar um arquivo `docker-compose.yaml` na raiz do projeto com a imagem [tmvdl/node](https://hub.docker.com/r/tmvdl/node).

```yaml
# docker-compose.yaml
version: '3'

services:
  app:
    image: tmvdl/node
    volumes:
      - .:/app
```

3. Subir o container para a construção do build

```bash
docker-compose up --build
```

## License

[MIT](LICENSE)
