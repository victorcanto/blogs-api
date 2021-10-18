# Projeto BlogsApi

## Descrição
Este projeto trata-se de uma aplicação backend utilizando a arquitetura MSC. Neste projeto é possível fazer o cadastro e login de pessoas usuárias, onde apenas essas pessoas poderão criar posts e categorias, ler, modificar e deletar posts.

## Habilidades

- Criar e associar tabelas usando models do sequelize
- Construir endpoints para consumir os models que criar
- Fazer um CRUD com o ORM

## Tecnologias usadas
- [NodeJs](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [JWT](https://jwt.io/)
- [Javascript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [Sequelize ORM](https://sequelize.org/)

## Clonando repositório
> No seu terminal, executar o comando:
```bash
git clone git@github.com:victorcanto/blogsApi.git
``` 
ou
```bash
git clone https://github.com/victorcanto/blogsApi.git
``` 

## Instalando Dependências

> Na pasta raiz do projeto, executar o comando:
```bash
npm install
``` 
## Iniciando servidor MySQL

> Iniciando servidor MySQL no Ubuntu
  `sudo systemctl start mysql.service`

> Iniciando servidor MongoDB no MacOs
 `mysql.server start`
 
> Iniciando servidor MongoDB no Windows
 `"C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqld" --console`
 
 ## Gerenciando banco de dados
 
> Criando banco de dados e executando as migrations
  ```bash
    npm run prestart
  ```
> Preenchendo dados das tabelas criadas
  ```bash
    npm run seed
  ```
> Removendo banco de dados
  ```bash
    npm run drop
  ```
 ## Executando aplicação
 
 > Na pasta raiz do projeto, para iniciar servidor, executar o comando:
  ```bash
    npm start
  ```
 
> Na pasta raiz do projeto, para iniciar servidor com o nodemon, executar o comando:
  ```bash
    npm run debug
  ```
 ## Utilizando aplicação
 
  Usar o [Postman](https://www.postman.com/) ou [Insomnia](https://insomnia.rest/download) para realizar as requisições.
  
## Executando Testes

> Na pasta raiz do projeto, executar o comando:
  ```
    npm test
  ```

Autor: [Victor Canto](https://www.linkedin.com/in/vscanto/)
Readme Original deste projeto: [README](https://github.com/victorcanto/trybe-projects/tree/victorcanto-sd-010-a-project-blogs-api)
