<br>

<p align="center" style='background-color:red'>
    <img alt="Rocketbox" src="https://github.com/RicardoBastos/transaction/blob/master/front/src/assets/logo.svg" />
</p>

<br>

<p align="center">
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-como-usar">Como usar</a>
</p>


<h1 align="center">
    <img alt="Rocketbox" src="https://github.com/RicardoBastos/transaction/blob/master/front/src/assets/go_finance.gif" />
</h1>

<br>

<h1 align="center">
    <img alt="Rocketbox" src="https://github.com/RicardoBastos/transaction/blob/master/front/src/assets/tests.png" />
</h1>


## :rocket: Tecnologias

Esse projeto foi desenvolvido com:

- [Node.js][nodejs]
- [React](https://pt-br.reactjs.org/)
- [Postgres](https://www.postgresql.org/)


IDE
- [VS Code][vc] 

## :information_source: Como usar

Para clonar e rodar essa aplicação você precisa ter o  [Git](https://git-scm.com), [Node.js v10.16][nodejs] ou higher + [Yarn v1.13][yarn] ou superior instalado em seu computador.


## Backend

```bash
# Opção para rodar com docker
docker run --name postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres

# Clone esse repositório
$ git clone https://github.com/ricadobastos/transaction.git

# Ir para pasta transaction
$ cd transaction


## Backend

# ir para pasta de backend
$ cd backend

# Instalar as dependências
$ yarn

# Rodar migrations
$ yarn typeorm migration:run

# Iniciar o servidor backend
$ yarn dev:server


## Frontend

# ir para pasta de frontend
$ cd frontend

# Instalar as dependências
$ yarn

# Iniciar o servidor frontend
$ yarn start


```

Developed with ♥ by Ricardo Bastos :wave: [Get in touch!](https://www.linkedin.com/in/ricardo-bastos-975592b0/)

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/

