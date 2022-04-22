<h1 align="center">

<img src="https://raw.githubusercontent.com/brunnosena/ignews/main/public/images/avatar.svg" alt="ignews" width="100px"/>

</h1>

<p align="center">
  IGNEWS - Portal de notícias 📰🚀
  <br>
  <br>

  <img alt="Language count" src="https://img.shields.io/github/repo-size/brunnosena/ignews"/>

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1">
  </a>

  <a href="https://www.linkedin.com/in/brunnosena/">
    <img alt="Made by Brunno Sena" src="https://img.shields.io/badge/made%20by-brunnosena-%237519C1">
  </a>

  <a href="https://github.com/brunnosena/ignews/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/brunnosena/ignews">
  </a>

  <img alt="License" src="https://img.shields.io/github/license/brunnosena/ignews">
</p>

---

<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-começando">Começando</a> &#xa0; &#xa0; | &#xa0;
  <a href="#author">Autor</a> &#xa0; &#xa0;
</p>

<br>

## :dart: Sobre ##

Aplicação desenvolvida utilizando o framework NextJS aplicando conceitos como consumo de API externas, API Root, Server Side Rendering (SSR), Static Site Generation (SSG), STRIPE para pagamentos das subscriptions, NextAuth para autenticação com Github, FaunaDB para armazenar as informações do usuário em um banco de dados e Prismic CMS para adição e gerenciamento do conteúdo dos posts.

<br/>

O projeto foi desenvolvido como pratica das aulas do modulo 03 do [Ignite da Rocketseat](https://rocketseat.com.br/)


## :rocket: Tecnologias ##

- [ReactJS](https://reactjs.org/)
- [NextJS](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [SASS](https://sass-lang.com/)
- [Next-Auth](https://next-auth.js.org/)
- [Stripe](https://stripe.com/)
- [FaunaDB](https://fauna.com/)
- [Prismic CMS](https://prismic.io/)


## :checkered_flag: Começando ##

```bash
# Clone this project
$ git clone https://github.com/brunnosena/ignews

# Access
$ cd ignews

# Install dependencies
$ yarn install

# Run the project
$ yarn dev

# The server will initialize in the <http://localhost:3000>
```

```bash
# Execute yarn para instalar as dependências
$ yarn

# Na raiz do projeto crie uma copia do arquivo .env.local.example
# Altere o nome da copia para .env.local
# Preencha as variáveis ambiente de acordo com as instruções
$ cp .env.local.example .env.local

# Execute stripe listen para ouvir eventos do webhook
$ stripe listen --forward-to localhost:3000/api/webhooks 

# Para iniciar a aplicação
$ yarn dev

```

## :blush: Autor ##

👋🏽 Feito por Brunno Sena

[![Linkedin Badge](https://img.shields.io/badge/-BrunnoSena-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/brunnosena/)](https://www.linkedin.com/in/brunnosena/)
[![Gmail Badge](https://img.shields.io/badge/-brunnow@hotmail.com-red?style=flat-square&link=mailto:brunnowa@hotmail.com)](mailto:brunnow@hotmail.com)