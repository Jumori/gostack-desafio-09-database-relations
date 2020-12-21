

<h1 align="center">
  Backend Services for an e-commerce
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Jumori/gostack-desafio-09-database-relations?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Jumori/gostack-desafio-09-database-relations">

  <a href="https://github.com/Jumori/gostack-desafio-09-database-relations/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Jumori/gostack-desafio-09-database-relations">
  </a>

</p>

<h4 align="center">
	🚧 Em construção 🚀 🚧
</h4>

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre o projeto](#-sobre-o-projeto)
   * [Funcionalidades](#️-funcionalidades)
   * [Como executar o projeto](#-como-executar-o-projeto)
     * [Pré-requisitos](#pré-requisitos)
     * [Rodando o Backend](#-rodando-o-backend-servidor)
   * [Tecnologias](#-tecnologias)
   * [Autora](#-autora)
   * [Licença](#user-content--licença)
<!--te-->


## 💻 Sobre o projeto

Projeto desenvolvido durante o **GoStack Bootcamp** oferecido pela [Rocketseat](https://nextlevelweek.com/).

Repositório com as intruções do desafio [Desafio 09: Relacionamentos com banco de dados no Node.js](https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-database-relations)


## ⚙️ Funcionalidades

- [x] Usuário deve poder criar um novo usuário cliente
  - [x] Não deve ser possível criar um usuário cliente com um e-mail já registrado
- [x] Usuário deve poder criar um novo produto
  - [x] Não deve ser possível criar produtos duplicados
- [x] Usuário deve poder criar um novo pedido
  - [x] Não deve ser possível criar um novo pedido para um usuário cliente inválido
  - [x] Não deve ser possível criar um novo pedido para um produto com estoque insuficiente
  - [x] Deve ser possível de subtrair o estoque do produto após a realização do pedido
- [x] Usuário deve poder listar um pedido específico


## 🚀 Como executar o projeto

Este projeto exige que o servidor back-end esteja rodando em segundo plano.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/), [Yarn](https://yarnpkg.com/)

#### 🎲 Rodando o Backend (servidor)

```bash

# Clone este repositório
$ git clone git@github.com:Jumori/gostack-desafio-09-database-relations.git

# Acesse a pasta do projeto no seu terminal/cmd
$ cd gostack-desafio-09-database-relations

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn start

# A aplicação será aberta na porta:33333 - acesse http://localhost:3333

```

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

#### **Server**  ([NodeJS](https://nodejs.org/en/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Express](https://expressjs.com/)**
-   **[TypeORM](https://typeorm.io/)**
-   **[TSyringe](https://github.com/microsoft/tsyringe)**

> Veja o arquivo  [package.json](https://github.com/Jumori/gostack-desafio-09-database-relations/blob/master/package.json)


## 🦸 Autora

<a href="https://github.com/Jumori">
 <img style="border-radius: 50%;" src="https://avatars1.githubusercontent.com/u/44618499?s=460&u=691cddb486d4b665417d25d8a575e508d6ef9563&v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Juliana Morikoshi</b></sub></a>
 <br />

[![Linkedin Badge](https://img.shields.io/badge/-Juliana-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/julianamorikoshi/)](https://www.linkedin.com/in/julianamorikoshi/)
[![Gmail Badge](https://img.shields.io/badge/-julianamorikoshi@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:julianamorikoshi@gmail.com)](mailto:julianamorikoshi@gmail.com)

---

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por Juliana Morikoshi 👋 [Entre em contato!](https://www.linkedin.com/in/julianamorikoshi/)
