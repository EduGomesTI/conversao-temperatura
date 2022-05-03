# conversao-temperatura
Desafio Docker

Passos para criar o container da aplicação em Node:

* Criar o arquivo dockerfile utilizando a imagem do node como base.

* Criar o arquivo .dockerignore com a pasta node_modules para não copiar arquvios desnecessários e potencialmente obsoletos.

* Rodar o comando **"docker build -t <imagem:versao> ."** para criar a imagem onde:

1. imagem:versao = É o nome da imagem e sua versão seguindo a convensão id_docker/nome:v1.

* rodar o comando **"docker container run -d -p 8080:8080 --name <container> <imagem:versao>"** onde:

1. <container> = nome do container.

1. <imagem:versao> = O nome da imagem criada e sua versão.
