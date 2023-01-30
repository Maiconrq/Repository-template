# Passo a passo para rodar um projeto com Docker Compose e Dockerfiles no GitHub

**1. Instale o [Docker](https://docs.docker.com/get-docker/) e o [Docker Compose](https://docs.docker.com/compose/install/) em sua máquina local**

**2. Clone o repositório do GitHub que contém o projeto que você deseja executar**

```bash
$ git clone https://github.com/user/repository.git
```
**3. Acesse o diretório do projeto**

```bash
$ cd repository
```
**4. Execute o comando `docker-compose up` na pasta raiz do projeto para iniciar a construção e execução dos containers**

```bash
$ docker-compose up
```
**5. Verifique o status dos containers executando o comando `docker ps`**

```bash
$ docker ps
```
**6. Acesse a aplicação em `http://localhost:3000` ou na porta especificada no arquivo `docker-compose.yml`**

> Observe que as configurações de build, teste e deploy do projeto podem ser encontradas nos arquivos `Dockerfile` e `docker-compose.yml`. 

> Para mais informações sobre Docker Compose, consulte a [documentação](https://docs.docker.com/compose/).
