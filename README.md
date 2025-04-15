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
`POST` `/signUp` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`POST` `/login` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`GET` `/userDetails/:id` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`PATCH` `/updateUser` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>

<br>
<br>

```shell
clientRoutes
```
`POST` `/registerClient` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`GET` `/consultClient` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`GET` `/clientDetails/:clientId` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`GET` `/searchClients` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`PUT` `/updateClient/:clientId` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`GET` `/dashboardClients` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>

<br>
<br>

```shell
chargeRoutes
```
`POST` `/addCharge` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`GET` `/allCharges` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`GET` `/chargeDetails/:idCharge` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`GET` `/searchCharges` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`PUT` `/updateCharge` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`DELETE` `/deleteCharge/:idCharge` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>
`GET` `/dashboardCharges/` _Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation_<br>

## _Tecnologias usadas_
- Javascript
- Node.js
- Express.js
- JSON
