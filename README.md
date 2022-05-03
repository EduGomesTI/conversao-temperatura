# conversao-temperatura
Desafio Docker

Passos para criar o container da aplicação em Node:

* Criar o arquivo dockerfile utilizando a imagem do node como base.

* Criar o arquivo .dockerignore com a pasta node_modules para não copiar arquvios desnecessários e potencialmente obsoletos.

* Rodar o comando **"docker build -t _\<imagem:versao\>_ ."** para criar a imagem onde:

1. _\<imagem:versao\>_ = É o nome da imagem e sua versão seguindo a convensão id_docker/nome:v1.

* rodar o comando **"docker container run -d -p 8080:8080 --name _\<container\>_ _\<imagem:versao\>_"** onde:

1. _\<container\>_ = nome do container.

1. _\<imagem:versao\>_ = O nome da imagem criada e sua versão.
