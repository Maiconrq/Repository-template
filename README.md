<div align="center">
  <h1>
    Template Projeto X
  </h1>
</div>

<div>
  <p align="center">
    <img src="img/cIcd-template.png">
  </p>
</div>

[![Série](https://img.shields.io/badge/Maiconrq-TEMPLATE-orange)](https://github.com/Maiconrq/Repository-template)
[![licence mit](https://img.shields.io/badge/licence-MIT-blue.svg)](https://github.com/afonsopacifer/open-source-boilerplate/blob/master/LICENSE.md)
![language](https://img.shields.io/badge/java-language-yellow)
![language](https://img.shields.io/badge/python-language-blue)


:rocket: This is a project developed using CI/CD, commit pattern and Docker Compose. The aim is to provide an easy and efficient solution for project development, deployment and execution. 

> :rocket: **Este é um projeto desenvolvido com a utilização de CI/CD, padrão de commits e Docker Compose. O objetivo é fornecer uma solução fácil e eficiente para o desenvolvimento, implantação e execução do projeto.**

## Versioning and Commits Pattern  /  Versionamento e Padrão de Commits

- We follow the [commit message standard](https://www.conventionalcommits.org/en/v1.0.0/) and require that all contributions be made using [Commitizen](https://github.com/commitizen/cz-cli). Commitizen is a tool that helps format commit messages in a standardized way, following the Conventional Commits pattern. For more information on how to use Commitizen, see the [documentation](https://github.com/commitizen/cz-cli). We do this to maintain organization and a clear history of project changes which can be found in the [CHANGELOG](CHANGELOG.md).

> **Seguimos o [padrão de mensagens de commit](https://www.conventionalcommits.org/en/v1.0.0/) e exigimos que todas as contribuições sejam feitas usando o [Commitizen](https://github.com/commitizen/cz-cli). O Commitizen é uma ferramenta que ajuda a formatar mensagens de commit de forma padronizada, seguindo o padrão Conventional Commits. Para mais informações sobre como usar o Commitizen, consulte a [documentação](https://github.com/commitizen/cz-cli). Fazemos isso para manter a organização e histórico claro de mudanças no projeto que podem ser encontradas no [CHANGELOG](CHANGELOG.md).**

## CI/CD

- We use [GitHub Actions](https://github.com/features/actions) to automate the continuous integration and delivery process. With each push on the `main` branch, the build, test and deploy process starts.
- Note that the CI/CD process will be triggered upon receiving the pull request and the changes will only be merged after the build, test and deploy are successfully completed.

> **Utilizamos o [GitHub Actions](https://github.com/features/actions) para automatizar o processo de integração e entrega contínua. A cada push na branch `main`, o processo de build, teste e deploy é iniciado.**

> **Observe que o processo de CI/CD será acionado ao receber o pull request e as mudanças só serão mescladas após o build, teste e deploy serem concluídos com sucesso.**

## Docker Compose

- To facilitate the execution of the project, we use [Docker Compose](https://docs.docker.com/compose/) to manage the containers necessary for the execution of the project. It is important to note that there is a directory that separates the `Dockerfiles` for each part of the project, maintaining organization and ease of maintenance. Simply run the `docker-compose up` command in the project's root folder to start the application.

> **Para facilitar a execução do projeto, utilizamos o [Docker Compose](https://docs.docker.com/compose/) para gerenciar os containers necessários para a execução do projeto. É importante observar que existe um diretório que separa os `Dockerfiles` para cada parte do projeto, mantendo a organização e facilidade de manutenção. Basta executar o comando `docker-compose up` na pasta raiz do projeto para iniciar a aplicação.**

## How to run the project / Como executar o projeto

> 1. Clone this repository to your local machine
> 2. Run the `docker-compose up` command in the root folder of the project
> 3. Access the application at `http://localhost:3000`

**1. Clone este repositório para sua máquina local**
 
**2. Execute o comando `docker-compose up` na pasta raiz do projeto**

**3. Acesse a aplicação em `http://localhost:3000`**

## Contribuir

1. Faça um fork deste repositório
2. Instale e configure o Commitizen seguindo as instruções na [documentação](https://github.com/commitizen/cz-cli)
3. Crie sua feature em uma nova branch
4. Use o comando `git cz` ao invés de `git commit` para fazer o commit da sua feature
5. Envie um pull request para a branch `main`

## Contributing / Contribuindo

- Want to contribute? [Follow this recommendations](./CONTRIBUTING.md):  

> **Pretende contribuir? [Siga esses passos](./CONTRIBUTING.md):**

## License / Licença
[MIT License](https://github.com/Maiconrq/Repository-template/blob/main/LICENSE) © [Maicon Rodrigues](https://github.com/Maiconrq)
