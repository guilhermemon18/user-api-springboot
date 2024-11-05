# API USUÁRIOS

**Introdução**

Esta API fornece funcionalidades para gerenciar usuário em um sistema. Ela é construída com Spring Boot e utiliza a própria memória RAM como um banco de dados.

**Como usar a API**

Para utilizar esta API, você precisará de um cliente HTTP como Postman ou Insomnia para fazer as requisições.

**Endpoints**

| Método | URL | Parâmetros | Resposta | Descrição |
|---|---|---|---|---|
| POST | /users | {"login": "teste", "password": "teste"} | - | Cria um novo usuário |
| GET | /users|  | JSON (usuários) | Retorna os usuários cadastrados |
| DELETE | /users/{code} | id (int) | - | Deleta um usuário |
