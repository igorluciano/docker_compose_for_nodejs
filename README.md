# Docker-compose for NodeJS

## Sobre

Esse projeto apresenta um modelo de Dockerfile e Docker-compose para possibilitar conteinerizar aplicações NodeJS.

## Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Docker](https://www.docker.com)

## Como começar

- Instale o Docker e configure o Docker-compose.

- Clone o projeto:

```bash
git clone git@github.com:igorluciano/docker_compose_for_nodejs.git
```

- Acesse a pasta do projeto:

```bash
cd docker_compose_for_nodejs
```

- Crie um arquivo denominado `package.json` e um `yarn.lock`.

- E para criar o container da aplicação, siga os passos abaixo:

```bash
# Criar e subir o container na primeira execução
docker-compose up --build
```

## Comandos úteis

```bash
# Subir o container nas demais execuções
docker-compose up
```
