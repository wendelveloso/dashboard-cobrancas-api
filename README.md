# API | Collection Management

API RESTful que contém recursos de um sistema de gestão de cobranças, permite ao usuário visualizar e gerenciar seus clientes e cobranças.

<br>
<img align=center src="banner-collection-management.png">

## Como rodar

Para rodar o projeto localmente, você precisa:

- _Instalar as dependências_ 

```shell
npm install
```

- _Iniciar o projeto com:_

```shell
npm run dev
```

## _Rotas usáveis_ 

O servidor será iniciado na porta 3000 e você poderá acessá-lo em:

 <br>

 ```shell
 userRoutes
```
`POST` `/signUp` _Rota para cadastro de novos usuários. Recebe os dados do usuário no corpo da requisição e realiza a criação de uma nova conta._<br>
`POST` `/login` _Rota de autenticação. Valida as credenciais do usuário e retorna um token de acesso em caso de sucesso._<br>
`GET` `/userDetails/:id` _Retorna os detalhes de um usuário específico com base no ID informado como parâmetro de rota._<br>
`PATCH` `/updateUser` _Atualiza os dados de um usuário existente. Os dados atualizados devem ser enviados no corpo da requisição._<br>

<br>
<br>

```shell
clientRoutes
```
`POST` `/registerClient` _Registra um novo cliente no sistema. Os dados devem ser enviados no corpo da requisição._<br>
`GET` `/consultClient` _Consulta informações gerais sobre clientes cadastrados._<br>
`GET` `/clientDetails/:clientId` _Retorna os detalhes de um cliente específico, com base no clientId fornecido como parâmetro de rota._<br>
`GET` `/searchClients` _Realiza uma busca por clientes com base em critérios definidos via query parameters._<br>
`PUT` `/updateClient/:clientId` _Atualiza os dados de um cliente específico. O clientId é passado na URL e os novos dados no corpo da requisição._<br>
`GET` `/dashboardClients` _Fornece dados consolidados e estatísticas sobre os clientes, para uso em dashboards._<br>

<br>
<br>

```shell
chargeRoutes
```
`POST` `/addCharge` _Cria uma nova cobrança. Os dados precisam ser enviados no corpo da requisição._<br>
`GET` `/allCharges` _Retorna todas as cobranças cadastradas._<br>
`GET` `/chargeDetails/:idCharge` _Mostra os detalhes de uma cobrança específica, usando o idCharge na URL._<br>
`GET` `/searchCharges` _Permite buscar cobranças com base em filtros definidos por query params._<br>
`PUT` `/updateCharge` _Atualiza uma cobrança existente. Os dados novos devem ser enviados no corpo da requisição._<br>
`DELETE` `/deleteCharge/:idCharge` _Remove uma cobrança específica com base no idCharge informado na rota._<br>
`GET` `/dashboardCharges/` _Retorna dados gerais e estatísticas das cobranças para exibir em dashboards._<br>

## _Tecnologias usadas_
- Javascript
- Node.js
- Express.js
- JSON
