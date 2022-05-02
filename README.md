# Projeto Individual GCES 2021.2

## Como rodar
Para rodar o projeto basta acessar a pasta aplicacao e rodar o seguinte comando:
```
docker-compose up --build
```

Para acessar o projeto após subir o docker basta entrar no http://localhost/

## Rodar Migrations
Para rodar as migrations do projeto basta rodar os comandos:
```
docker-compose run web rake db:create
docker-compose run web rake db:migrate
```
