# Golang + Redis + Mongo

Configuração base de um projeto Golang

### Tecnologias
* [Go] - Linguagem de programação
* [Redis] - Datastore de chave e valor
* [MongoDB] - Banco de dadosn não relacional

### Pré-requisitos
 - Docker e Docker Compose instalado e configurado

### Instalação
Assume que atenda aos pré-requisitos informados acima para seguir com os passos abaixo:

```sh
$ git clone https://github.com/edujudici/golang-redis-mongo.git
```

Build e Start da aplicação

```sh
$ docker compose up -d && go run main.go
```

### Como acessar

 - Acessando o sistema: [localhost](http://localhost:8000/)


License
----

MIT

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [Go]: <https://tip.golang.org/>
   [Redis]: <https://redis.io/>
   [MongoDB]: <https://www.mongodb.com/>