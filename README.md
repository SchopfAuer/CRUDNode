## 💻 Projeto

CRUD desenvolvido em Node.js utlizando REST API

## Como usar?

Clone este repositório e execute os seguintes comandos

```bash
npm install
npm run start
```

Acesse o endereço [http://localhost:8000](http://localhost:8000) no seu navegador

A API tem os seguintes usos:
GET: /users - Lista os usuários cadastrados no banco de dados
GET: /user/:id (trocar :id pelo id do usuário, exemplo "\user\1") - Lista os dados de um usário específico
POST: /user/ - Envie os parâmetros nome, senha e email e será retornado se foi cadastrado com sucesso, assim adicionando o usuário ao banco de dados
PATCH: /user/:id (trocar :id pelo id do usuário, exemplo "\user\1") - Envie os parâmetros nome, senha e email e será retornado se foi editado com sucesso, assim editado os dados do usuário no banco de dados
DELETE: /user/:id (trocar :id pelo id do usuário, exemplo "\user\1") - O usuário será deletado do banco de dados

Para realizar o POST e PATCH é recomendada a utilização dos POSTMAN, os dados devem ser inseridos no Body e enviar os parâmetos no "x-www-form-urlencoded"

<br />

<div align="center">
  <small>Desenvolvido por Alecsandro Schopf Auer Junior - Maio/2023</small>
</div>
