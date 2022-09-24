# Docker Node.js

Imagem Docker para compilaçao de projetos Node.js

Veja mais em [hub.docker.com/r/tmvdl/node](https://hub.docker.com/r/tmvdl/node)

## Tags

### current

```sh
docker pull tmvdl/node
```

### alpine

```sh
docker pull tmvdl/node:alpine
```

### docker

```sh
docker pull tmvdl/node:docker
```

### docker-alpine

```sh
docker pull tmvdl/node:docker-alpine
```

### git

```sh
docker pull tmvdl/node:git
```

### git-alpine

```sh
docker pull tmvdl/node:git-alpine
```

### heroku

```sh
docker pull tmvdl/node:heroku
```

### jest

```sh
docker pull tmvdl/node:jest
```

### nextjs

```sh
docker pull tmvdl/node:nextjs
```

### surge

```sh
docker pull tmvdl/node:surge
```

### vercel

```sh
docker pull tmvdl/node:vercel
```

## Como usar

Instalar o [Docker](https://docs.docker.com/engine/install/).

### Uso 1

1. Criar um arquivo `docker-compose.yaml` na raiz do projeto com a imagem [tmvdl/node](https://hub.docker.com/r/tmvdl/node).

```yaml
# docker-compose.yaml
version: '3'

services:
  app:
    image: tmvdl/node
    volumes:
      - .:/app
```

2. Subir o container para a construção do build

```bash
docker-compose up --build
```

### Uso 2

1. Executar como container do Docker

```sh
docker run --name nodejs tmvdl/node
```

## License

[MIT](LICENSE)

## Update

Atualizado em 27/12/2021
